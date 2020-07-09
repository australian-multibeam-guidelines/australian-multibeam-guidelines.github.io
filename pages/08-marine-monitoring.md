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

Baseline surveys are used to map the distribution of marine benthic habitats at a particular spatial scale and provide information necessary for more targeted field surveys using such tools as towed video, AUVs and stereo baited remote underwater video stations (BRUVs) (Lucieer et al. 2013, Monk et al. 2016, Wines et al. 2020). In contrast, monitoring surveys are used to assess change in distribution and extent of targeted habitats or features (such as rocky outcrops) identified during previous baseline surveys (Rattray et al. 2009, McGonigle et al. 2010). This type of survey requires MBES data to be collected at a higher resolution and with a greater degree of positional accuracy. The survey specifications and requirements needed to meet the aims of each survey type are presented in Table 12.



<em><strong>Table 12:</strong> Standard Operating Procedures for MBES surveys aimed for benthic habitat mapping according to purpose: Baseline surveys or Monitoring surveys</em>

<table>
<thead>
  <tr>
    <th>Specification</th>
    <th>Baseline&nbsp;&nbsp;&nbsp;surveys</th>
    <th> Monitoring surveys</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">Purpose</td>
    <td>●        &nbsp;&nbsp;&nbsp;Used to identify seafloor habitats and potential&nbsp;&nbsp;&nbsp;biodiversity hotspots.</td>
    <td>●        &nbsp;&nbsp;&nbsp;Used to ensure spatio-temporal assessment of the&nbsp;&nbsp;&nbsp;seabed and habitat through repeat mapping of targeted key benthic&nbsp;&nbsp;&nbsp;habitats. </td>
  </tr>
  <tr>
    <td>●         Used for discovery purposes in regions that have had no&nbsp;&nbsp;&nbsp;baseline mapping conducted.</td>
    <td>●        &nbsp;&nbsp;&nbsp;The survey accuracy standard is very high to&nbsp;&nbsp;&nbsp;ensure reproducibility over time.</td>
  </tr>
  <tr>
    <td rowspan="3">Pre survey preparation</td>
    <td rowspan="3"><a href="https://www.tablesgenerator.com/html_tables#RANGE!_Pre-survey_planning">●        &nbsp;&nbsp;&nbsp;as per section 2</a></td>
    <td>In addition to baseline survey&nbsp;&nbsp;&nbsp;specifications:</td>
  </tr>
  <tr>
    <td>●         Synthesis of all pre-existing survey data into survey region&nbsp;&nbsp;&nbsp;database</td>
  </tr>
  <tr>
    <td>●         Identification of locations of seafloor targets to be&nbsp;&nbsp;&nbsp;monitored </td>
  </tr>
  <tr>
    <td rowspan="2">Mobilisation and calibration</td>
    <td colspan="2" rowspan="2"><a href="https://www.tablesgenerator.com/html_tables#RANGE!_Mobilisation,_Calibration_and_1">●        &nbsp;&nbsp;&nbsp;As per section 3</a></td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td rowspan="3">Data Logging</td>
    <td>●        &nbsp;&nbsp;&nbsp;Bathy: Mandated</td>
    <td>●        &nbsp;&nbsp;&nbsp;Bathy: Mandated</td>
  </tr>
  <tr>
    <td>●         Seabed Backscatter: Mandated</td>
    <td>●        &nbsp;&nbsp;&nbsp;Seabed Backscatter: Mandated</td>
  </tr>
  <tr>
    <td>●         Water column backscatter: Recommended (if available)</td>
    <td>●        &nbsp;&nbsp;&nbsp;Water column backscatter: Mandated (if available)</td>
  </tr>
  <tr>
    <td rowspan="2">Acquisition setting</td>
    <td colspan="2"><a href="https://www.tablesgenerator.com/html_tables#RANGE!_Acquisition">●        &nbsp;&nbsp;&nbsp;As per section 4 </a></td>
  </tr>
  <tr>
    <td colspan="2">●        &nbsp;&nbsp;&nbsp;Set to equidistant mode and minimise setting&nbsp;&nbsp;&nbsp;changes</td>
  </tr>
  <tr>
    <td rowspan="2">Sound Velocity Profiles (SVP)</td>
    <td>●        &nbsp;&nbsp;&nbsp;Min of 1 per day, but should be monitored.</td>
    <td>●        &nbsp;&nbsp;&nbsp;Min of 2 per day (beginning and end of survey),&nbsp;&nbsp;&nbsp;but should be monitored.</td>
  </tr>
  <tr>
    <td>●         If sound speed at the transducer varies by &gt; 2m/s another&nbsp;&nbsp;&nbsp;SVP should be collected</td>
    <td>●        &nbsp;&nbsp;&nbsp;If sound speed at the transducer varies by &gt;&nbsp;&nbsp;&nbsp;1m/s another SVP should be collected</td>
  </tr>
  <tr>
    <td rowspan="2">Geodetic Parameters</td>
    <td>●        &nbsp;&nbsp;&nbsp;WGS 84 (ITRF); GDA2020</td>
    <td>●        &nbsp;&nbsp;&nbsp;WGS 84 (ITRF); GDA2020</td>
  </tr>
  <tr>
    <td>●         Horizontal accuracy: 5m + 5% of water depth. Vertical accuracy:&nbsp;&nbsp;&nbsp;1% water depth</td>
    <td>●        &nbsp;&nbsp;&nbsp; Horizontal&nbsp;&nbsp;&nbsp;accuracy: absolute positioning to be &lt; 2 m. Vertical accuracy: &lt; 0.5 m</td>
  </tr>
  <tr>
    <td>Mapping&nbsp;&nbsp;&nbsp;Coverage &amp; Overlap</td>
    <td>●        &nbsp;&nbsp;&nbsp;100% Coverage with 30% overlap between survey&nbsp;&nbsp;&nbsp;lines of data with 95% confidence level.</td>
    <td>●        &nbsp;&nbsp;&nbsp;100% coverage with 60% overlap between survey&nbsp;&nbsp;&nbsp;lines of data with 95% confidence level.</td>
  </tr>
  <tr>
    <td>Resolution</td>
    <td>●        &nbsp;&nbsp;&nbsp;1 m resolution in &lt; 50m depth ; 5% of depth&nbsp;&nbsp;&nbsp;beyond 50 m</td>
    <td>●        &nbsp;&nbsp;&nbsp;1 m resolution </td>
  </tr>
  <tr>
    <td>Tides&nbsp;&nbsp;&nbsp;and GPS Tide</td>
    <td>●        &nbsp;&nbsp;&nbsp;Record GPS tides. All soundings shall be reduced&nbsp;&nbsp;&nbsp;to the ellipsoid.</td>
    <td>●        &nbsp;&nbsp;&nbsp;Record GPS tides. All soundings shall be reduced&nbsp;&nbsp;&nbsp;to the ellipsoid.</td>
  </tr>
  <tr>
    <td>Point&nbsp;&nbsp;&nbsp;data attribution</td>
    <td>●        &nbsp;&nbsp;&nbsp;All data should be attributed with its uncertainty&nbsp;&nbsp;&nbsp;estimate at the 95% confidence level for both position and, if relevant,&nbsp;&nbsp;&nbsp;depth.</td>
    <td>●        &nbsp;&nbsp;&nbsp;All data should be attributed with its uncertainty&nbsp;&nbsp;&nbsp;estimate at the 95% confidence level for both position and, if relevant,&nbsp;&nbsp;&nbsp;depth.</td>
  </tr>
  <tr>
    <td>Metadata&nbsp;&nbsp;&nbsp;and Reports</td>
    <td colspan="2">As per section 2.3.1.3 and section 6</td>
  </tr>
  <tr>
    <td rowspan="2">Data Release</td>
    <td colspan="2"> </td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://metadataentry.aodn.org.au/submit/">As per Chapter 7. Until&nbsp;&nbsp;&nbsp;further notice, a metadata record should also be filled with AODN for&nbsp;&nbsp;&nbsp;archiving. For agencies with regular metadata harvest by the AODN, follow&nbsp;&nbsp;&nbsp;agency-specific protocols for metadata, otherwise create and submit metadata&nbsp;&nbsp;&nbsp;records via the AODN Data Submission Tool. Note that user registration is&nbsp;&nbsp;&nbsp;required, but this is free and immediate.</a></td>
  </tr>
  <tr>
    <td>Notification</td>
    <td colspan="2"><a href="mailto:marineparks@awe.gov.au">After the data has been successfully&nbsp;&nbsp;&nbsp;received by AusSeabed and metadata uploaded to the AODN, please contact&nbsp;&nbsp;&nbsp;marineparks@awe.gov.au to confirm delivery of data.</a></td>
  </tr>
</tbody>
</table>