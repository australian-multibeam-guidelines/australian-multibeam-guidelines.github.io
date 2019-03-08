---
layout: home
permalink: /data-acquisition
title: "Data Acquisition"
excerpt: ""
image:
  feature: /banners/05_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

## Installation offsets

Mobilisation, calibration and validation of the MBES, aims to establish the spatial relationship between all of the system’s components (e.g., GPS, transducer, motion reference unit ) with the vessel’s frame of reference, and is paramount to obtaining high resolution and accurate data. Section 3 of the Australian Multibeam Guidelines provide an overview and details of these steps (Picard et al. 2018).

 

The vessel’s Central Reference Point (CRP) is determined upon each *new *installation of a MBES system and to best suit the vessels balance, and installation criteria (if the MBES is hull or pole mounted) (Edward and Martin 2015; Figure 7 of Picard et al., 2018).  The CRP is defined and recorded along with the installation offsets of the system’s components within the various logging software Where possible the CRP should be defined at the MBES transducer directly. All installation offsets are required to be recorded and detailed within the survey report and processing log of the supplied raw data files (see proposed reporting templates in Picard et al. 2018)

 

Although this manual recommends that depths be provided in relation to the ellipsoid, to enable other users to reduce data to chart datum, vessel draft should be measured at the start and end of surveys and dynamic draft taken into consideration with measurements of the waterline conducted regularly. This will ensure that the depth charted is the true depth and not depth under keel and will account for changes due to for example, fuel usage where applicable. The vessel draft is recorded during a survey in the vessel log and/or entered in the acquisition system.

 

## Data logging

During a survey with a MBES system there are a number of data products that should be recorded and settings that should be taken into consideration. These mainly include the following, but section 4 of the Australian Multibeam Guidelines provides further details.:

 

1.	MBES Raw data: log raw proprietary format (e.g. *.all for Kongsberg, *.s7k for Reson) or ancillary systems. Files should be recorded for a duration of 30 minutes for shallow systems (< 150 m) and 120 minutes for deep systems (> 150 m) to account for computer processing speed. Raw positional data and motion datagrams are to be recorded within the raw sonar file and at a rate of 1Hz and 100Hz respectively.

2.	Seabed backscatter sonar data: Log complete backscatter i.e. beam intensity (RIq and snippets or equivalent).

3.	Water column data [Recommended, if available]: log to a separate file in proprietary format (e.g. *.wcd for Kongsberg). These files can take up a large amount of storage space (~ 10 times raw bathymetry), and the surveyor must ensure necessary disc space prior to collection.

4.	Delayed heave: delayed heave datagrams are recorded by the acquisition computer and logged to files in the proprietary format.

5.	File naming convention: It is important that the surveyor adhere to a consistent and acceptable naming convention that links to the metadata of the raw data format. The convention should be sequential, include timestamp and system type, e.g. nnnn_yyyymmdd_hhmmss_system, where: nnnn is the sequential number; yyyymmdd is the date; hhmmss is the time  

6.	Filters and settings: Both noise and spike filters should be monitored during the survey to ensure the data quality and integrity is maintained over the course of the survey. Beam spacing mode should be set to equidistant. It is very important that the pulse length should not be changed at any time during the survey so that all data are standardised.

7.	GNSS track: Should be provided as track plots (in x, y format) to enable interpretation of the vessel transits.

## Sound velocity profiles

A SVP measures the speed of sound in water at different vertical levels in the water column. This information is used for ray tracing (path length and refraction) and to accurately form the beam of the sound in the case of MBES with flat array transducers. It is thus important that a SVP sensor be deployed to collect this information.  The SVP can be determined using one of the following four methods:

 

·         Direct observation via deployment of a SVP measuring device (e.g. Valeport monitor)

·         Calculation of SVP through deployment of an eXpendable Bathy Thermograph (XBT)

·         Calculation of SVP using CTD (Conductivity/Temperature/Depth) data and applying the UNESCO formula ([https://www.usna.edu/Users/physics/ejtuchol/documents/SP411/Chapter4.pdf](https://www.usna.edu/Users/physics/ejtuchol/documents/SP411/Chapter4.pdf)) or;

·         Calculation of SVP from Sea Surface Temperature and Climatology using SVP builder software (Sinquin et al. 2016).

 Depending on the location of the survey and the oceanographic conditions over the area (sea state, mixing regime, thermal layering etc.) of the survey, SVP should be conducted at the appropriate intervals or location. SVP must be taken *within* the survey area at least once per day, but up to multiple times a day where necessary. For example, profiles will vary in proximity to an estuary due to freshwater inflows from rivers or currents from areas with different salinity.

 

 

### Why are SVP so important?

 

A MBES system emits a sound pulse in an arc out from the transducer. As the sounds contacts the seabed, it is reflected/backscattered back towards the transducer and received. Each backscattered pulse from each individual seabed point can be considered a discrete beam. The speed of the beam through the water column is governed by the water temperature and density. Because the water column, in most cases, is not evenly mixed, the speed of the pulse changes at different levels in the water column. At each change in speed, refraction or ‘bending of the pulse path’ occurs, unless the angle of incidence is equal to 90 degrees, as with a single beam echosounder. Refraction can happen many times throughout the pulse’s path through the water column. Therefore, to enable best ray tracing possible and consequently depth conversion of each sounding, details of the water column sound profile are essential.

 

 

## Geodetic parameters

The datum parameters entered into the acquisition software will use the Global Navigation Satellite System (GNSS) datum. The use of differential GPS as a positioning system is required for all on-shelf and off-shelf multibeam acoustic data collection as we aim to resolve an absolute positional accuracy greater than 1 m. Any datum shifts will need to be applied at the post-processing stage. Section 2.5 of the Australian Multibeam Guidelines provides additional details regarding datum.

## Survey speed

The speed of the vessel will have a direct impact on the density of soundings reaching the seafloor, the quality of the data (in the return signal) and to some degree determine the resolution of the final raster datasets (as it dictates the distance along track between pings). The distance between pings along the track of the vessel is determined by the pulse repetition frequency (PRF) and ship speed; the faster the vessel, the fewer pulses ensonify the seafloor per distance along track. The swath width also limits the pulse rate- where a wide swath results in a lower ping rate or a greater space between pings. Aeration problems (bubble sweep) are a function of sea state but also of the heading with respect to the wave direction and the vessel speed. Aeration problems reduce the signal or the quality of the signal at the transducer head. Higher speeds also increase vibrations in the transducer head (depending on the installation- for example pole mounts).

 

It is strongly advised that the surveyor creates a record of aeration problems versus sea state with respect to heading and vessel speed. This record will be helpful in ensuring that the survey is performed efficiently with a minimum of line rejections and corresponding reruns and infills. This should be recorded in the field log book.

## Line spacing

Line spacing is the distance between adjacent survey lines. The best spacing between survey lines is determined by a combination of horizontal range limit (sonar coverage from one transducer) expected at that depth of water and the accuracy required from the survey (either baseline mapping or monitoring). The horizontal range expected depends on the water depth as well as the sea state, seabed type and the sonar frequency. If the surveyor is using two transducer heads, the total swath width from the port edge to the starboard edge increases the range by allowing you to ‘see’ a wider swath in terms of angle.  

 

The horizontal range is limited by two factors: grazing angle and spreading loss. The grazing angle limit is related to the angle that the sound "beam" makes with the seabed. At the grazing angle limit, the sound makes a very small angle with the seabed. Most of the sound at this point is reflected away and the signal scattered back from the seabed is too small to be detected.

 

Due to this loss of signal on the outer beams of the swath, some overlap in swath is required. A minimum of 30% overlap should take into account line keeping errors and where sea state is calm and create a 100% coverage of the seafloor. The type of survey being undertaken will determine the overlap with the highest quality requiring 60% overlap (monitoring) and the lowest quality requiring 30% overlap (baseline; Table 3.2).

 

The seafloor topography and the slope (gradient of the slope) is an important consideration for planning the survey lines. For MBES data collection, it is strongly advised to run the lines parallel to the seabed contours (along the slope, not up or down the slope). This is beneficial for keeping the coverage reasonably constant along the survey lines (as the swath width will vary with depth). It is also beneficial because less acoustic energy is reflected towards the transducer from steep slopes, causing poorer detections and the possibility of false detections in the sidelobes5. If survey lines must run up and down the slope, a reduction of vessel speed or reduction in swath width may be required to allow for the echo sounder to track the bottom continuously. Planned lines must be activated in this instance to ensure that gaps are not created between the survey lines as the swath coverage is reduced coming into shallow water and additional lines may need to be added.

 

For surveys where backscatter information is critical, the overlapping area should be increased (from 60% to 100%) to compensate for the high variability of individual backscatter intensities on the edges of the outer beam (Gavrilov & Parnum, 2010). For surveys where backscatter information is considered a secondary product, it is recommended that the overlapping be kept as minimal as practical (30% overlap).

 

Crosslines are survey lines that are run across the main set of survey lines. They are critical to ensuring the quality assessment of the data, especially the management of data uncertainties. It is thus highly recommended to plan multiple crosslines

## Pulse length

The pulse length affects the amount of the transmitted acoustic energy into the water and the vertical resolution of the observed depth.  Increasing pulse length enhances penetration through the water column but reduces vertical resolution.

 

Pulse length and sampling frequency must be considered as related to backscatter data. The sampling frequency of the system must be considered in order to hold the Nyquist-Shannon sampling theorem6. This enables the analogue signal to be reconstructed from the digital data (e.g. Kongsberg EM3002 systems recommended minimum pulse length of 100µsec or greater).

## Tides and GPS tides

All soundings shall be reduced to an ellipsoid with a minimum depth accuracy of 0.2% relative to water depth.  However, tidal information is useful for other applications and users, such as the production of chart. It is thus important to record at a minimum the GPS tides from the GNSS system. Refer to section 2.5 of the Australian Multibeam Guidelines for further details (Picard et al., 2018).  

 
