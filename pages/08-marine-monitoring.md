---
layout: home
permalink: /marine-monitoring
title: "8. Multibeam Acoustics for Marine Monitoring"
excerpt: ""
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

There are two particular needs for mapping and surveying when considering multibeam acoustics for marine monitoring, these can be defined as either baseline surveys or monitoring surveys. MBES can be used for both survey types, however, they have different acquisition and post-processing standards. A decision tree to help you decide on which set of specifications apply to the work you are carrying out is provided in Figure 6. A baseline survey is for exploratory purposes and data will be collected in a ‘single pass operation’. These data are used to map the distribution of marine benthic habitats at a particular spatial scale, and provide information necessary for more targeted field surveys using such tools as towed video, AUVs and stereo baited remote underwater video stations (BRUVs) (Lucieer et al. 2013, Monk et al. 2016). In contrast, a monitoring survey may have already identified target habitats or features (such as rocky outcrops) from previous broad scale or other hydrographic data that are to be monitored to assess change in distribution and extent (Rattray et al. 2009, McGonigle et al. 2010). This type of survey will require MBES data to be collected at a higher resolution and with a greater degree of positional accuracy. The survey specifications and requirements needed to meet the aims of each survey type are presented in Table 11. 

The principles developed in the preceding chapters of these guidelines should still inform and influence the planning through to acquisition phases of MBES work and the requirements detailed in this section should be seen as a complementary lens used to refine efforts so that data is fit for purpose for work carried out for marine monitoring or within state or commonwealth marine parks.


<img src="images/figures/image6.png" width="" alt="alt_text" title="image_tooltip">

<em>Figure 6 . Decision tree for seabed classification survey design (adapted from Anderson et al. (2007)).</em>

<em>Table 11 Standard Operating Procedures for MBES surveys according to survey purpose: Baseline or Monitoring</em>

<table>
  <tr>
   <td>Specification
   </td>
   <td>NESP Baseline
   </td>
   <td>NESP Monitoring
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
   <td>
<ul>

<li>Used to ensure spatio-temporal assessment of the seabed and habitat. The survey accuracy standard is very high to ensure reproducibility over time.

<li>Used for repeat mapping and for targeting key habitats for monitoring purposes.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Pre survey preparation
   </td>
   <td>
<ul>

<li>The coverage of the area to be surveyed (bounding box) with the datum and coordinate system clearly identified.

<li>Apply for appropriate permits

<li>Establishment of line spacing

<li>Register upcoming survey with the AusSeabed Survey Coordination Tool (<a href="#heading=h.2xcytpi">section 2.1.3</a>)

<li>Determination of the system offsets and calibration area (patch test) area to be conducted as soon as practical and after the system is completely set up ready for survey. 

<li>The location and scheduling of the Sound Velocity Profiles
</li>
</ul>
   </td>
   <td>
<ul>

<li>In addition to baseline survey specifications:

<li>Synthesis of all pre-existing survey data into survey region  database

<li>Identification of locations of seafloor targets to be monitored 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Installation Offsets
   </td>
   <td colspan="2" >
<ul>

<li>Provide Mobilisation Calibration Reports and logs (<a href="#heading=h.zu0gcz">section 6.1</a>)

<li>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Data Logging
   </td>
   <td colspan="2" >
<ul>

<li>Bathy: Mandated

<li>Seabed Backscatter: Mandated

<li>Water column backscatter: Recommended (if available)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Acquisition setting
   </td>
   <td colspan="2" >
<ul>

<li>Mode: Equidistant mode where system allows

<li>Minimise setting changes to optimise backscatter (avoid running system on auto mode) <a href="#heading=h.39kk8xu">section 4.3.2</a>

<li>
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

<li>GDA2020. Horizontal accuracy: 5m + 5% of water depth. Vertical accuracy: 1% water depth
</li>
</ul>
   </td>
   <td>
<ul>

<li>GDA2020 -– Horizontal accuracy: absolute positioning to be &lt; 2 m. Vertical accuracy: &lt; 0.5 m
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Survey Speed
   </td>
   <td colspan="2" >
<ul>

<li>at survey speed appropriate to capture resolution required (typically 5 knots or less)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Mapping Coverage & Overlap
   </td>
   <td>
<ul>

<li>100% Coverage with 30% overlap between survey lines of data with an 80% confidence level.
</li>
</ul>
   </td>
   <td>
<ul>

<li>100% coverage with 60% overlap between survey lines of data with an 80% confidence level.
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

<li> 1 m resolution 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Tides and GPS Tide
   </td>
   <td colspan="2" >
<ul>

<li>Record GPS tides. All soundings shall be reduced to the ellipsoid.

<li>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Point data attribution
   </td>
   <td>
<ul>

<li>All data should be attributed with its uncertainty estimate at the 80% confidence level for both position and, if relevant, depth.
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
   <td colspan="2" >
<ul>

<li>Metadata should conform to the schema outlined in <a href="#heading=h.147n2zr">section 2.3.1.3</a>, Mobilisation, Calibration, and validation reports, as well as the Report of Survey should conform with <a href="#heading=h.2koq656">section 6</a>. 

<li>Templates are provided in <a href="https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates">Appendix H</a> that contain more detail. 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Data Release
   </td>
   <td colspan="2" >
<ul>

<li>Refer to <a href="#heading=h.3x8tuzt">section 7</a> for instructions on submitting data and metadata to AusSeabed and AODN for archiving. 

<li>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Notification
   </td>
   <td colspan="2" >
<ul>

<li>After the data has been successfully received by AusSeabed and AODN please contact <a href="mailto:marineparks@awe.gov.au">marineparks@awe.gov.au</a> to confirm delivery of data.
</li>
</ul>
   </td>
  </tr>