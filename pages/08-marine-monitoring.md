---
layout: home
permalink: /marine-monitoring
title: "8. Multibeam Acoustics for Marine Monitoring"
excerpt: ""
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

This section is particularly relevant to the acquisition of MBES data within the Australian Marine Parks (AMPs), but can be used for any surveys where habitat monitoring is a key focus. The principles presented in the preceding sections of the Australian Multibeam Guidelines should still inform and influence the planning through to acquisition phases of MBES work undertaken in AMPs and the requirements detailed in this section should be seen as a complementary lens used to refine effort for the particular needs of benthic habitat monitoring.

The AMPs were established to protect and conserve areas of ecological significance within the Australian marine estate and cover 36 per cent of our oceans, or around 3.3 million square kilometres. To ensure adequate and appropriate management of these areas, the National Environmental Science Program Marine Biodiversity Hub, AusSeabed Community and Parks Australia have defined the requirements of MBES acquisition carried out within Australian Marine Parks. These requirements will maximise the environmental and societal benefits of any MBES data collection done in these areas.

There are two particular needs for mapping habitats in AMPs: 1) baseline surveys or monitoring surveys, which are first—time acquisition of high-resolution data for exploratory purposes; and 2) monitoring surveys, which consist of repeat mapping for monitoring benthic habitat change. MBES can be used for both survey types, however, they have different acquisition and post-processing specifications.

Baseline surveys are used to map the distribution of marine benthic habitats at a particular spatial scale and provide information necessary for more targeted field surveys using such tools as towed video, AUVs and stereo baited remote underwater video stations (BRUVs) (Lucieer et al. 2013, Monk et al. 2016, Wines et al. 2020). In contrast, monitoring surveys are used to assess change in distribution and extent of targeted habitats or features (such as rocky outcrops) identified during previous baseline surveys (Rattray et al. 2009, McGonigle et al. 2010). This type of survey requires MBES data to be collected at a higher resolution and with a greater degree of positional accuracy. The survey specifications and requirements needed to meet the aims of each survey type are presented in [Table 12](#bookmark=id.338fx5o).



<em><strong>Table 12:</strong> Standard Operating Procedures for MBES surveys aimed for benthic habitat mapping according to purpose: Baseline surveys or Monitoring surveys</em>

<table>
  <tr>
   <td>Specification
   </td>
   <td>Baseline surveys
   </td>
   <td> Monitoring surveys
   </td>
  </tr>
  <tr>
   <td>Purpose
   </td>
   <td>
<ul>

<li>Used to identify seafloor habitats and potential biodiversity hotspots.

<li>Used for discovery purposes in regions that have had no baseline mapping conducted.
</li>
</ul>
   </td>
   <td>
<ul>

<li>Used to ensure spatio-temporal assessment of the seabed and habitat through repeat mapping of targeted key benthic habitats. 

<li>The survey accuracy standard is very high to ensure reproducibility over time.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Pre survey preparation
   </td>
   <td>
<ul>

<li>as per <a href="#2-pre-survey-planning-6">section 2</a>
</li>
</ul>
   </td>
   <td>In addition to baseline survey specifications:
<ul>

<li>Synthesis of all pre-existing survey data into survey region database

<li>Identification of locations of seafloor targets to be monitored 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Mobilisation and calibration
   </td>
   <td colspan="2" >
<ul>

<li>As per <a href="#3-mobilisation-calibration-and-validation-21">section 3</a>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Data Logging
   </td>
   <td>
<ul>

<li>Bathy: Mandated

<li>Seabed Backscatter: Mandated

<li>Water column backscatter: Recommended (if available)
</li>
</ul>
   </td>
   <td>
<ul>

<li>Bathy: Mandated

<li>Seabed Backscatter: Mandated

<li>Water column backscatter: Mandated (if available)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Acquisition setting
   </td>
   <td colspan="2" >
<ul>

<li>As per <a href="#4-acquisition-27">section 4 </a>

<li>Set to equidistant mode and minimise setting changes
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Sound Velocity Profiles (SVP)
   </td>
   <td>
<ul>

<li>Min of 1 per day, but should be monitored.

<li>If sound speed at the transducer varies by > 2m/s another SVP should be collected
</li>
</ul>
   </td>
   <td>
<ul>

<li>Min of 2 per day (beginning and end of survey), but should be monitored.

<li>If sound speed at the transducer varies by > 1m/s another SVP should be collected
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Geodetic Parameters
   </td>
   <td>
<ul>

<li>WGS 84 (ITRF); GDA2020

<li>Horizontal accuracy: 5m + 5% of water depth. Vertical accuracy: 1% water depth
</li>
</ul>
   </td>
   <td>
<ul>

<li>WGS 84 (ITRF); GDA2020

<li> Horizontal accuracy: absolute positioning to be &lt; 2 m. Vertical accuracy: &lt; 0.5 m
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>
    Mapping Coverage & Overlap
   </td>
   <td>
<ul>

<li>100% Coverage with 30% overlap between survey lines of data with 95% confidence level.
</li>
</ul>
   </td>
   <td>
<ul>

<li>100% coverage with 60% overlap between survey lines of data with 95% confidence level.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Resolution
   </td>
   <td>
<ul>

<li>1 m resolution in &lt; 50m depth ; 5% of depth beyond 50 m
</li>
</ul>
   </td>
   <td>
<ul>

<li>1 m resolution 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Tides and GPS Tide
   </td>
   <td>
<ul>

<li>Record GPS tides. All soundings shall be reduced to the ellipsoid.
</li>
</ul>
   </td>
   <td>
<ul>

<li>Record GPS tides. All soundings shall be reduced to the ellipsoid.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Point data attribution
   </td>
   <td>
<ul>

<li>All data should be attributed with its uncertainty estimate at the 95% confidence level for both position and, if relevant, depth.
</li>
</ul>
   </td>
   <td>
<ul>

<li>All data should be attributed with its uncertainty estimate at the 95% confidence level for both position and, if relevant, depth.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Metadata and Reports
   </td>
   <td colspan="2" >As per <a href="#heading=h.3o7alnk">section 2.3.1.3 </a>and <a href="#6-reports-36">section 6</a>
   </td>
  </tr>
  <tr>
   <td>Data Release
   </td>
   <td colspan="2" >As per Chapter 7. Until further notice, a metadata record should also be filled with AODN for archiving. For agencies with regular metadata harvest by the AODN, follow agency-specific protocols for metadata, otherwise create and submit metadata records via the <a href="https://metadataentry.aodn.org.au/submit/">AODN Data Submission Tool</a>. Note that user registration is required, but this is free and immediate.
   </td>
  </tr>
  <tr>
   <td>Notification
   </td>
   <td colspan="2" >After the data has been successfully received by AusSeabed and metadata uploaded to the AODN, please contact <a href="mailto:marineparks@awe.gov.au">marineparks@awe.gov.au</a> to confirm delivery of data.
   </td>
  </tr>
</table>