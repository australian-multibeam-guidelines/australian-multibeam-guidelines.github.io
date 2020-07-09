---
layout: home
permalink: /data-processing
title: "5. Data Processing"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

# 5.1 Data processing considerations
# _5.1.1 During survey_
Processing during a survey should at a minimum be done to QC the data, both bathymetry and backscatter data. QC includes:
*   checking for artefacts
*   consistency of seabed backscatter
*   meeting the required specifications, e.g. data density

A processing log should be kept and is required to be submitted alongside the survey reports ([section 6](https://australian-multibeam-guidelines.github.io/reports)).

# _5.1.2 Post-survey_
Post-survey processing should include:
*   reduction of soundings to appropriate vertical datum (observed or post-processed GNSS tides).
*   application of SVPs and refraction correction applied (where allowed).
*   data cleaning, which may vary depending on the purpose of the survey (see 5.1.2.1)
*   elimination of surface artefacts, e.g. resulting from calibration errors.
*   removal of random errors (ambient noise) using filters/CUBE or manual techniques
*   data QA using crosslines (if collected). If specific crosslines are not collected, consider using transit lines that cross main survey lines (e.g. data acquired while going to a sampling location).
*   TPU calculation for each sounding ([section 5.2](https://australian-multibeam-guidelines.github.io/data-processing#52-total-propagated-uncertainties-tpu)).
*   surface (grid) creation as per 5.1.2.1 if submitting to AusSeabed Data Hub
*   all interventions should be noted in a processing report, including parameters or techniques used.

See also section 10 of AHO, 2018 for more information on processing.

_5.1.2.1 AusSeabed data cleaning and creation of surfaces (grids)_
AusSeabed aims to have as few as possible manual interventions in the cleaning and processing of data to optimise delivery, and importantly, create reliably reproducible outputs with a clear provenance. As such, process automation is being adopted wherever possible. 

AusSeabed has adopted a banded depth approach for creating gridded products (L3) and optimising the horizontal resolution delivered from acquired multibeam data (table 8).

_Table 9 Matrix of depth range used to guide horizontal resolution of bathymetry grids. Modified from NOAA (2019)_


<table>
  <tr>
   <td colspan="3" >Normal depth band
   </td>
   <td colspan="3" >Steep slope depth band<sup>1</sup>
   </td>
   <td rowspan="2" >Res (m)
   </td>
   <td rowspan="2" >Ratio<sup>2</sup>
   </td>
  </tr>
  <tr>
   <td>D<sub>s</sub> (m)
   </td>
   <td>D<sub>d</sub> (m)
   </td>
   <td>Range Interval (m)
   </td>
   <td>D<sub>s</sub> (m)
   </td>
   <td>D<sub>d</sub> (m)
   </td>
   <td>Range Interval (m)
   </td>
  </tr>
  <tr>
   <td>0
   </td>
   <td>20
   </td>
   <td>20
   </td>
   <td>0
   </td>
   <td>20
   </td>
   <td>20
   </td>
   <td>0.5
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>18
   </td>
   <td>40
   </td>
   <td>22
   </td>
   <td>16
   </td>
   <td>40
   </td>
   <td>24
   </td>
   <td>1
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>36
   </td>
   <td>80
   </td>
   <td>44
   </td>
   <td>32
   </td>
   <td>80
   </td>
   <td>48
   </td>
   <td>2
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>72
   </td>
   <td>160
   </td>
   <td>88
   </td>
   <td>64
   </td>
   <td>160
   </td>
   <td>96
   </td>
   <td>4
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>144
   </td>
   <td>320
   </td>
   <td>176
   </td>
   <td>128
   </td>
   <td>320
   </td>
   <td>192
   </td>
   <td>8
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>288
   </td>
   <td>640
   </td>
   <td>352
   </td>
   <td>256
   </td>
   <td>640
   </td>
   <td>384
   </td>
   <td>16
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>576
   </td>
   <td>1280
   </td>
   <td>704
   </td>
   <td>512
   </td>
   <td>1280
   </td>
   <td>768
   </td>
   <td>32
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>1152
   </td>
   <td>2560
   </td>
   <td>1408
   </td>
   <td>1024
   </td>
   <td>2560
   </td>
   <td>1536
   </td>
   <td>64
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>2304
   </td>
   <td>5120
   </td>
   <td>2816
   </td>
   <td>2048
   </td>
   <td>5120
   </td>
   <td>3072
   </td>
   <td>128
   </td>
   <td>0.0250
   </td>
  </tr>
  <tr>
   <td>4608
   </td>
   <td>12000
   </td>
   <td>7392
   </td>
   <td>4096
   </td>
   <td>12000
   </td>
   <td>7904
   </td>
   <td>210
   </td>
   <td>0.0175<sup>3</sup>
   </td>
  </tr>
</table>

<sup>1</sup>In cases of steep slopes, the overlap between grids of different resolutions may need to be increased to prevent gaps in their junction. In these cases, the coarser resolution grid should have its shoaler extent modified to prevent this coverage gap.

<sup>2</sup>Highest resolution at which the dataset can support a minimum of five soundings per node (ideally, twice the maximum standard required survey resolution for the depth of the area, i.e. 2.5 % of water depth) (NOAA, 2019).

<sup>3</sup>Based on 1° beamwidth (highest resolution that the current technology of shipborne systems can effort) because of the constraint in the minimum capture distance in CUBE to a maximum of 100.

![alt_text](images/figures/figure6.png "image_tooltip")

_**Figure 6** Horizontal resolution according to depth range for various existing standards._

# _5.1.3 Backscatter processing requirements_ 
Please keep a processing log that records what processing software and settings are used to prepare the backscatter mosaic. When you process, it is important to specify the imagery type (Beam Average/Time Series); Beam Pattern Correction (yes/no); and Anti-aliasing (yes/no) selection.

Mandatory information to record for the backscatter data processing is:

•	the AVG window size 
•	AVG method
•	beam Pattern Correction (yes/no – if yes, please provide the beam pattern file)
•	the imagery type (Beam Average/Time Series)
•	gain (yes/no)
•	time varying gain (yes/no)

Other image processing information that is useful but not mandatory:
•	the speckle option (to remove noise)
•	anti-aliasing (yes/no) 

Further details about best-practice for backscatter data acquisition can be found in Lamarche and Lurton (2017).

Acquisition and processing logs should be delivered alongside all raw data (including calibration test) and processed mosaics in accordance with Section 7.

# 5.2 Total propagated uncertainties (TPU)
The total propagated uncertainty (TPU) for each sounding should be computed and included in the data submission ([Section 7](https://australian-multibeam-guidelines.github.io/data-release)).

The TPU is the combination of the total horizontal uncertainties (THU) and the total vertical uncertainties (TVU) of that sounding ([Appendix E](https://australian-multibeam-guidelines.github.io/appendices#appendix-e--total-propagated-uncertainties)). THU is a 2-dimensional quantity in the horizontal plane and is assessed only after the GNSS-Inertial system has been calibrated. TVU is a 1-dimensional quantity in the vertical dimension. TPU is not a linear addition of uncertainties in each system’s component. It is a propagated combination of uncertainties for the non-linear set of equations comprising the integrated swath acoustic-GNSS Inertial system. 

Uncertainty calculation is best addressed using most internationally accepted statistical models for determination of TPU, which are derived from Hare et al. (1995).  Current international best-practice statistical model for resolving the system of equations is the Combined Uncertainty Bathymetric Estimator (CUBE). The average horizontal and vertical TPU estimates determined by the software for a range of water depths is provided with respect to the IHO S-44 standard for position and depth accuracy in Table 6. 

_**Table 10:** Example Sounding Accuracy - TPU (calculated at 1σ, but most software computes at 2σ)_

<table>
<thead>
  <tr>
   <td><strong>Depth band (m)</strong>
   </td>
   <td><strong>0-5</strong>
   </td>
   <td><strong>5-20</strong>
   </td>
   <td><strong>20-50</strong>
   </td>
   <td><strong>50-100</strong>
   </td>
   <td><strong>100-200</strong>
   </td>
  </tr>
  </thead>
  <tbody>
  <tr>
   <td colspan="6" >Position Accuracy (m)
   </td>
  </tr>
  <tr>
   <td>IHO Standard
   </td>
   <td>5.25
   </td>
   <td>5.50
   </td>
   <td>6.00
   </td>
   <td>6.50
   </td>
   <td>7.25
   </td>
  </tr>
  <tr>
   <td>TPU Estimate
   </td>
   <td>0.27
   </td>
   <td>0.27
   </td>
   <td>0.30
   </td>
   <td>0.34
   </td>
   <td>0.42
   </td>
  </tr>
  <tr>
   <td colspan="6" >Depth Accuracy (m)
   </td>
  </tr>
  <tr>
   <td>IHO Standard
   </td>
   <td>0.38
   </td>
   <td>0.39
   </td>
   <td>0.44
   </td>
   <td>0.50
   </td>
   <td>0.63
   </td>
  </tr>
  <tr>
   <td>TPU Estimate
   </td>
   <td>0.27
   </td>
   <td>0.27
   </td>
   <td>0.28
   </td>
   <td>0.31
   </td>
   <td>0.35
   </td>
  </tr>
 </tbody>
</table>
