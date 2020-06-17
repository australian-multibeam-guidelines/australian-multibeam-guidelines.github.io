---
layout: home
permalink: /data-release
title: "7. Data Release"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

The AusSeabed Data Hub is the national repository for all seabed mapping data collected within the legal boundaries of the Australian Continental Shelf and the Australian Charting Area and any data that lies outside this region but is considered of value to the Australian marine community or was commissioned by Australian entities. Data submitted to this repository will be made publicly visible and available through the [AusSeabed Marine Data Portal](https://portal.ga.gov.au/persona/marine) under a [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/legalcode) unless that data is subject to embargos or confidentiality agreements. Data delivered through the AusSeabed Marine Data Portal is done so under the proviso that it is not used for navigational purposes. To submit data to the AusSeabed Data Hub first check that it complies with section 6.1.1 Final QA/QC checklist and then follow the steps outlined in section 6.1.2 Data Submission to AusSeabed.

# 7.1 Final QA/QC
The final QA/QC checklist for data acceptance includes:
*   Vessel configuration file for the survey is updated with the latest information received from the survey acquisition report. Ensure to not apply the calibration values twice, i.e. in the acquisition and processing software.
*   AusSeabed’s policy and preference is for data to be reduced using GNSS heights to the ellipsoid. However, if appropriate, accurate tide files should be contained within data being submitted.
*   All ancillary systems, SVP, true heave, etc., are applied and if not, these have been noted in the survey report or logs.
*   SV artefacts were applied where necessary and noted in the processing report. 
*   Any other surface artefacts, e.g. resulting from calibration errors have been addressed and parameters that have been applied have been noted in a processing report.
*   Random errors (ambient noise) have been removed using Filters/CUBE or manual techniques and have been noted in the processing report.

# 7.2 Data Submission to AusSeabed
In the future, a data submission portal will be integrated with the Survey Coordination Tool and the QC Tools suite currently being developed by AusSeabed. This will make the provision of data to the AusSeabed repository a seamless and efficient user experience, utilising metadata captured during earlier stages of the surveying process and providing automated quality assurance of collected data. In the interim, data can be transferred to AusSeabed using any one of a number of secure online data transfer mechanisms (Google Drive, One Drive, Cloudstor, Drop Box, directly through the National Computing Infrastructure, by sharing permissions to Amazon S3, etc.) or if no online data transfer method is possible by sending through a hard drive to Geoscience Australia. Please follow the steps outlined below to ensure efficient delivery of data and contact [ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au) if unsure during any stage of the process.



1. Ensure that data meet the Final QA/QC requirements above ([section 7.1](https://australian-multibeam-guidelines.github.io/data-release#71-final-qaqc)) and that all files outlined in Table 9 have been gathered or prepared for submission. 
2. Contact AusSeabed ([ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au)) and AHO ([datacentre@hydro.gov.au](mailto:datacentre@hydro.gov.au)) to inform of the intention to submit data. This communication with AusSeabed can be used to determine the most convenient method for file transfer. If hard drives are used, they will be returned to the sender within 2 weeks after being received.
3. Send data and associated files to AusSeabed.
4. Publish metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been quality controlled. This can be done in one of two ways:
*   If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 
*   Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit/). Note that user registration is required, but this is free and immediate.

_Table 10 Data required for submission to AusSeabed_
<table>
<thead>
  <tr>
    <th>Deliverable item</th>
    <th>Information</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>L0 data (unprocessed instrument data)</td>
    <td><strong>Description:</strong> It is required that raw data include SV profile, attitude, navigation, heading, raw bathymetry, raw backscatter per beam and, if available, raw backscatter in time series i.e. the equivalent seabed image or snippet style. Water column data, recorded as (separate files) are only required when the data files have been requested specifically during survey planning. For more info see<a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata"> section 2.3.1.2</a><br><strong>Data Format:</strong> native format as produced by the acquisition system (see <a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">table 5</a> for formats) <br><strong>Datagram:</strong> logged automatically for Kongsberg EM series. However, for Reson SeaBat, datagrams with the following IDs are required: 1003, 1012, 1013, 7000, 7001, 7002, 7004, 7006, 7005, 7007, 7012, 7018, 7022, 7028, 7200, and 7504.</td>
  </tr>
  <tr>
    <td>True Heave</td>
    <td><strong>Description:</strong> Delayed, processed heave saved independently from raw sonar file, logged in 600-720 minutes period.<br><strong>Data Format:</strong> Applanix True Heave or equivalent</td>
  </tr>
  <tr>
    <td>Coverage shape file</td>
    <td><strong>Description:</strong> Shape file showing the coverage of the collected data. <br><strong>Data Format:</strong> GeoJSON (compulsory)</td>
  </tr>
  <tr>
    <td>L2 data (Derived geophysical/georeferenced variables)</td>
    <td><strong>Description:</strong> Processed multibeam bathymetry data, including processed multibeam backscatter data (if collected)<br><strong>Data Format:</strong> .GSF (compulsory)</td>
  </tr>
  <tr>
    <td>L3 data (Variables mapped to a grid)</td>
    <td><strong>Description:</strong> Processed multibeam bathymetry surface grid (for BAG the TPU is a compulsory inclusion)<br><strong>Data Format:</strong> 32-bit floating point GeoTIFF and BAG (both compulsory)</td>
  </tr>
  <tr>
    <td>Visual Imagery</td>
    <td><strong>Description:</strong> Two visual images of the bathymetric surface one with sun illumination from two orthogonal directions and the other with five time’s vertical exaggeration. These images are for quick manual inspection of the data quality.<br><strong>Data Format:</strong> 8-bit or 24-bit RGB GeoTIFF</td>
  </tr>
  <tr>
    <td>Processed backscatter mosaic</td>
    <td><strong>Description:</strong> Processed multibeam time-series generated backscatter mosaic<br><strong>Data Format:</strong> 32-bit floating point GeoTIFF (values have to be provided in dB).</td>
  </tr>
  <tr>
    <td>Sound velocity profile</td>
    <td><strong>Description:</strong> Sound velocity casts used in SIS or equivalent acquisition system together<br><strong>Data Format:</strong> ASCII *.csv, *.asvp, *.svp</td>
  </tr>
  <tr>
    <td>Log file (SVP cast)</td>
    <td><strong>Description:</strong> SVP cast info (date, time, depth of cast and seafloor, location and line applied to)<br><strong>Data Format:</strong> ASCII text</td>
  </tr>
  <tr>
    <td>Records (Report and log)</td>
    <td>As per section 6 of the Australian Multibeam Guidelines</td>
  </tr>
  <tr>
    <td>Metadata</td>
    <td><strong>Description:</strong> Metadata should as a minimum conform to the list of attributes outlined in <a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">section 2.3.1.3 </a>and described in detail in <a href="https://australian-multibeam-guidelines.github.io/appendices#h2-ausseabed-minimum-required-metadata">appendix H.2</a><br><strong>Data Format:</strong> .xml (preferred) txt file or spreadsheet also accepted</td>
  </tr>
</tbody>
</table>
