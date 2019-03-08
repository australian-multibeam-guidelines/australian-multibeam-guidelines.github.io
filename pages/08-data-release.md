---
layout: home
permalink: /data-release
title: "Data Release"
excerpt: ""
image:
  feature: /banners/08_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

At the time of writing this manual, there is not currently a complete repository for multibeam data collected in Australian waters, although several agencies house some multibeam data (e.g. AHO, GA, IMOS, CSIRO), and several portals promote its accessibility and visualisation (e.g.[ seamapaustralia.org](http://seamapaustralia.org/)). However, as part of the[ AusSeabed](http://www.ausseabed.gov.au/) program, the development of the AusSeabed data hub, managed by Geoscience Australia (GA), is underway and will be linked to appropriate visualisation platforms. It is estimated that the hub will be functional by 2020.

 

In the meantime data can be stored and archived by GA, and made discoverable through the[ AusSeabed data coverage](http://marine.ga.gov.au/#/mbes_coverage) and accessible via email request to AusSeabed@ga.gov.au. Following the steps listed below will ensure timely release of data and maximise data discoverability:

1.    Create metadata record(s) describing the survey and data collection (for both raw and QA/QC data products). Minimum metadata requirements for multibeam data include the following:

·      Title of the survey region (e.g., AMP name and ID) and, if not a well-established region, its geographic boundary;

·      Surveyor’s name and company;

·      Start and end dates of the survey;

·      Vessel name, type of vessel and MBES unit used, details regarding the positioning system, acquisition software, and operation parameters;

·      The number of lines recorded and corresponding number of kilometres; and

·      Summary of the main survey results (water depths, observed tidal range, sonar features of interest- anomalies, unusual targets etc.).

2.    Publish metadata record(s) to the[ Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:

·  	If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release.

·  	Otherwise, metadata records can be created and submitted via the[ AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit) at[ https://metadataentry.aodn.org.au/submit](https://metadataentry.aodn.org.au/submit). Note that user registration is required, but this is free and immediate.

3.    Generate interactive OGC complient web services layers of the following derived data layers:

·      Location map with limits of the survey area;

·      Bathymetric map showing the depths, slope and bathymetric hill shading results;

·      Backscatter data map showing boundaries between habitat features;

·      Location of auxiliary data sampling (point features of sediment grabs) or transect lines of video surveys; and

·      Map showing the track plot of the vessel position, indicating the region of the patch test calibration.

4.    Upload data files identified in Table 3.3 and all field records generated during the survey to a secure, publicly accessible online repository or on a portable hard drive and send to Geoscience Australia, attn AusSeabed. Please also inform AusSeabed@ga.gov.au of the delivery.

5.    If available, add links to the location of raw data and derived map imagery to the previously published metadata record. Metadata accompanied by map imagery as described above may be additionally showcased through the[ Australian Ocean Data Network portal](https://portal.aodn.org.au/data).

6.    Produce a technical or post-survey report documenting the purpose of the survey, sampling locations, sampling equipment specifications etc. Provide links to this report in all associated metadata records *[Recommended]*.

7.    Data to be made publicly available under a Creative Commons by attribution non-commercial licence.
