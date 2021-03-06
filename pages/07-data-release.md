---
layout: home
permalink: /data-release
title: "7. Data Submission and Release"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

The AusSeabed Data Hub is the national repository for all seabed mapping data collected within the legal boundaries of the Australian Continental Shelf and the Australian Charting Area and any data that lies outside this region but is considered of value to the Australian marine community or was commissioned by Australian entities. Data submitted and distributed through the hub, in accordance with the AusSeabed Data Submission and Distribution policies, will be made publicly available through the [AusSeabed Marine Data Portal](https://portal.ga.gov.au/persona/marine) under a [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/legalcode). Data Distributed through the AusSeabed Marine Data Portal are done so under the proviso that they are not used for navigational purposes. Data subjected to embargos or confidentiality agreements will not be considered. It is worth noting that this infrastructure is undergoing development to function as a federated hub, whereby, organisations can emulate the architecture of the AusSeabed Data Hub, retaining custodianship over their data while making it discoverable and accessible through the AusSeabed Portal. Institutions wishing to pursue this path are encouraged to contact [ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au) for more information.

# 7.1 Data submission to AusSeabed
Data submitted to the AusSeabed Data Hub needs to comply with the following final QA/QC checklist:

*   Ensure that calibration values have been applied adequately, i.e. not doubled up through the various software used (e.g. applied by the acquisition software and again by the processing software). See [section 3](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation).
*   Data should be delivered according to formats and specifications listed in [Table 5](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata) of [section 2.3.1](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata)
*   Where processing or cleaning has been applied it has been done according to [section 5](https://australian-multibeam-guidelines.github.io/data-processing).

Data can be transferred to AusSeabed using any one of a number of secure online data transfer mechanisms (Google Drive, One Drive, Cloudstor, Drop Box, directly through the National Computing Infrastructure, by sharing permissions to Amazon S3, etc.). If no online data transfer method is possible, data can be sent to Geoscience Australia using a hard drive. Please follow the steps outlined below to ensure efficient delivery of data and contact [ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au) if unsure during any stage of the process:

1. Ensure that data meet the Final QA/QC requirements above and that all files outlined in [Table 11](https://australian-multibeam-guidelines.github.io/data-release#71-data-submission-to-ausseabed) have been prepared for submission. 
2. Contact AusSeabed ([ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au)) and AHO ([datacentre@hydro.gov.au](mailto:datacentre@hydro.gov.au)) to inform of the intention to submit data. This communication with AusSeabed can be used to determine the most convenient method for file transfer. If hard drives are used, they will be returned to sender. If your submission is a requirement of your funder or regulator (e.g. permit provider) please include the funder or regulator in your correspondence.
3. Send data and associated files to AusSeabed.
4. Provide access to the data’s metadata record by either:
    1. publishing the metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been quality controlled and pass the publication details of the metadata record on to [ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au). Publishing the record with AODN can be done in one of two ways:
        1. If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 
        2. Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit/). Note that user registration is required, but this is free and immediate.
    1. providing the metadata record with the data for AusSeabed to assume custodianship of the data and exclusive publication through the AusSeabed Data Hub and associated services.

Please note that other funder, or regulator metadata requirements may apply.

_**Table 11:** Data required for submission to AusSeabed_
<table>
<thead>
  <tr>
   <td><strong>Deliverable item</strong>
   </td>
   <td><strong>Specifications</strong>
   </td>
  </tr>
  </thead>
  <tbody>
  <tr>
   <td>Sonar file L0, L2 and L3
   </td>
   <td><a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">Table 5</a>
   </td>
  </tr>
  <tr>
   <td>Navigation, Heave and Attitude files L0 and L2
   </td>
   <td><a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">Table 5</a>
   </td>
  </tr>
  <tr>
   <td>Ancillary files L0 and L2 (Tide, SVP, etc.)
   </td>
   <td><a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">Table 5</a>
   </td>
  </tr>
  <tr>
   <td>Backscatter L3
   </td>
   <td><a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">Table 5</a>
   </td>
  </tr>
  <tr>
   <td>Records (Reports and logs)
   </td>
   <td><a href="https://australian-multibeam-guidelines.github.io/reports">Section 6</a>
   </td>
  </tr>
  <tr>
   <td>Metadata
   </td>
   <td>
<a href="https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata">Section 2.3.1.3</a>
   </td>
  </tr>
  <tr>
   <td>Two visual images of the bathymetric surface for manual inspection of data quality (one with sun illumination from two orthogonal directions and the other with five time’s vertical exaggeration.)
   </td>
   <td>
   </td>
  </tr>
  </tbody>
</table>


In the future, a data submission portal will be integrated with the Survey Coordination Tool and the QC tools suite (both currently being developed by AusSeabed). This will make the provision of data to the AusSeabed Data Hub a seamless and efficient user experience, utilising metadata captured during earlier stages of the surveying process and providing automated quality assurance of collected data.
