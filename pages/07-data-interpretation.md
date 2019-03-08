---
layout: home
permalink: /data-interpretation
title: "Data Interpretation"
excerpt: ""
image:
  feature: /banners/07_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

MBES bathymetric data will be processed to characterise and classify the seafloor in terms relevant to understanding the spatial and temporal distribution of benthic habitats. The combination of bathymetry and textural surfaces (backscatter) provide an excellent reference dataset for research and management of Australian marine seafloor habitats.

 

Geomorphological analysis can be used to classify the multibeam bathymetry data and define the extents of particular habitat types such as seagrass beds, rocky reef, and sand plains. We recommend the use of the national standardised benthic habitat classification nomenclature as documented by Seamap Australia (Butler et al. 2017). Importantly, this classification system includes other established and developing national classification schema such as CATAMI (Althaus et al. 2015) and Geoscience Australia’s *Classification and Glossary of Seabed Geomorphology*.

 

The backscatter Geotiff can be interpreted into a sediment distribution and habitat map using one of two automated segmentation methods:

 

1.	Image-based segmentation (e.g., using e-Cognition ([www.ecognition.com](http://www.ecognition.com/))) where the image is segmented into regions of similar backscatter characteristics and using the bathymetric data to identify these boundaries and transition zone. These segments are then classified as surface features, backscatter intensity patterns of sediment/habitat distribution etc (Lucieer and Lamarche, 2011).

2.	Signal based segmentation (e.g., using ENVI ([www.esriaustralia.com.au/envi](http://www.esriaustralia.com.au/envi)) where changes in the backscatter intensity, with increasing grazing angle from nadir, are analysed to classify the data (Hamilton and Parnum, 2011).

3.	Pixel based methods (Collier and Brown, 2005).

 

Table 3.3 Expected data deliverables for a baseline mapping or monitoring survey to accompany metadata reporting

<table>
  <tr>
    <td>Deliverable item</td>
    <td>Comment</td>
  </tr>
  <tr>
    <td>Raw sonar data</td>
    <td>Raw sonar data in native format as created directly from the native acquisition system of the multibeam system used. e.g. *.all for Kongsberg EM series, *.s7k for newer version of Reson SeaBat or *.xtf for the older one
Data format: native format as produced by the acquisition system, except for the *.xtf
Datagram: all logged automatically for Kongsberg EM series. For Reson SeaBat, datagrams with the following IDs are required:
1003, 1012, 1013, 7000, 7001, 7002, 7004, 7006, 7005, 7007, 7012, 7022, 7028, 7200, 7504
The water column data, recorded as separate files, for both Kongsberg and Reson are only required on special request in survey planning.
For all other multibeam systems, it is required that raw data include SV profile, attitude, navigation, heading, raw bathymetry, raw backscatter per beam and if available raw backscatter in time series i.e. the equivalent seabed image or snippet style</td>
  </tr>
  <tr>
    <td>Processed sonar data</td>
    <td>Processed multibeam bathymetry data, including processed multibeam backscatter data, if requested
Preferred format: Caris HIPS & SIPS project structure including processed bathymetry surface (see processed bathymetry grids below) (*.csar and XYZ) and time series-generated backscatter mosaic (*.csar) in Fieldsheets subfolder, processed line data & geobar in HDCS_Data subfolder, tide data used (*.tid) in Tide folder, individual sound velocity profiles (*.csv) used together with additional information on time and location of the cast in SVP subfolder. Backscatter mosaic and geobar are only required on request
Alternative format:
Processed line: SAIC GSF (*.gsf) if no other alternative</td>
  </tr>
  <tr>
    <td>True Heave</td>
    <td>Delayed, processed heave saved independently from raw sonar file, logged in 600-720 minutes period
Data format: Applanix ATH or equivalent (Caris compatible)</td>
  </tr>
  <tr>
    <td>Processed bathymetry grids</td>
    <td>Processed multibeam bathymetry surface grid
Data format: CSAR and xyz ASCII comma delimited (XY in specified UTM; z in negative metre at 2 decimal places) and/or ESRI ASCII *.asc (values in meter).</td>
  </tr>
  <tr>
    <td>Processed backscatter mosaic</td>
    <td>Processed multibeam time series-generated backscatter mosaic
Data format: xyz ASCII comma delimited (XY in specified UTM; z in dB at 2 decimal places) and/or ESRI ASCII *.asc , GeoTiffs (values in dB).</td>
  </tr>
  <tr>
    <td>Tide</td>
    <td>Tide data used for tide correction (date, time and depth(m.mm)/pressure (dBar)
Data format: Caris tide *.tid or ASCII *.csv</td>
  </tr>
  <tr>
    <td>Sound velocity profile</td>
    <td>Sound velocity casts used in SIS or equivalent acquisition system together
Data format: ASCII *.csv</td>
  </tr>
  <tr>
    <td>Log file (SVP cast)</td>
    <td>SVP cast info (date, time, depth of cast and seafloor, location and line applied to)
Data format: ASCII text</td>
  </tr>
  <tr>
    <td>TPU/ CUBE related information</td>
    <td>●      XYZ of MRU to Transducers
●      XYZ of NAV to Transducers
●      Transducers mounting angles (if not horizontal)
●      Type of Navigation system
●      Type of MRU system
●      Sign conventions used to calculate XYZ (Down positive etc)
Data format: ASCII text</td>
  </tr>
  <tr>
    <td>Records (Report and log)</td>
    <td>●      As per section 6 of the Australian Multibeam Guidelines (Picard et al., 2018)</td>
  </tr>
</table>


 
