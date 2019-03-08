---
layout: home
permalink: /data-processing
title: "Data Processing"
excerpt: ""
image:
  feature: /banners/06_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

There are a number of software packages available for processing MBES data and many of the software are in commercial proprietary to the specific MBES system used for acquisition. Regardless of the data processing software that is used, the goal is for the minimum final products to be released at the completion of a field survey (summarised in Table 3.3).

 

The data acquisition parameters are established to ensure that the data are fit for the purposes of benthic habitat mapping (i.e. baseline) and monitoring of Australia’s waters. The post-processing parameters and techniques, on the other hand, are generally optimised for a targeted purpose (and differ for a baseline or monitoring survey (i.e. data fit for purpose)). Section 5 of the Australian Multibeam Guidelines provides generic information related to processing during and after a sea floor mapping survey (Picard et al., 2018).

 

During the survey, bathymetry and backscatter datasets shall be processed and plotted onboard to monitor the data coverage and quality. This will allow for additional survey lines to be collected prior to the finalisation of the survey, in the event of data gaps between survey lines for example.

 

## Bathymetric data processing

Uncertainty related to the bathymetric measurements can be quantified and incorporated into a statistical model to derive the total propagated uncertainty (TPU) of the resulting bathymetric surfaces. A number of factors (see appendix E in Picard et al., 2018) will influence this uncertainty including: draft setting of the transducer, incorrect sound velocity profiles, spatial variation in the sound velocity, temporal variation in the sound velocity, instrumental uncertainty (internal precision of the MBES unit) and motion (incorrect heave, pitch and roll corrections), settlement and squat of the vessel in the water and incorrect tidal corrections to name a few.

 

Where possible the TPU should be computed using the CUBE (Combined Uncertainty and Bathymetry Estimator).  CUBE uses soundings and their associated uncertainty estimates as input and through spatial and uncertainty weighting, while also relying on the very high data density of multibeam data sets, outputs a bathymetry gridded surface and its associated uncertainty (error) surface. In addition, it tracks the statistical hypotheses for each depth point, and where there is more than one estimate, makes an attempt to determine which the most likely value is. This makes it a very powerful tool for identifying and removing outliers in the data. Once these have been removed from the data, CUBE is rerun to generate the final bathymetry and uncertainty surfaces. See "CUBE Bathymetric data Processing and Analysis (CHS February 2012)". The uncertainty surface is a quantification of the survey quality, which can be compared against specifications and used as input to the metadata for the survey (CHS 2013).

## Backscatter data processing

For optimal processing procedures for MBES backscatter image generation, refer to Lurton and Lamarche, 2015. A final compensated geotiff mosaic of the acoustic backscatter for the survey region should be generated.
