---
layout: home
permalink: /multibeam-acoustics-for-marine-monitoring
title: "Multibeam Acoustics for Marine Monitoring"
excerpt: ""
image:
  feature: /banners/03_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

The use of MBES for mapping and monitoring marine habitats has experienced a rapid increase since 2000 (Figure 3.3), and there is now a wealth of knowledge from which we can synthesise a ‘best practices’ document.


![image alt text](images/figures/image_2.png)

Figure 3.3. Annual total of peer reviewed papers featuring multibeam mapping for seafloor survey (Web of Science 2017- search words "multibeam seafloor habitat survey").

The **objectives** of MBES surveys conducted by mapping programs are to collect seafloor data to identify, delineate and map biogenic, anthropogenic and geological features. This objective requires particular data to be collected that can a) chart the water depths creating a high resolution bathymetric map at an appropriate resolution in regards to the target habitat or feature and b) be able to differentiate boundaries between different substrate and/or habitat types.

 

To meet these objectives, there are two particular needs for mapping and surveying that can be defined as either baseline surveys or monitoring surveys (see Table 2). MBES can be used for both survey types, however, they have different acquisition and post-processing standards.  A **baseline survey** is for exploratory purposes where data will be collected in a ‘single pass operation’. These data are used to map the distribution of marine benthic habitats at a particular spatial scale, and provide information necessary for more targeted field surveys using such tools as towed video, AUVs and stereo baited remote underwater video stations (BRUVs) (Lucieer et al. 2013, Monk et al. 2016). In contrast, a **monitoring survey** may have already identified target habitats or features  (such as rocky outcrops) from previous broad scale  or other hydrographic data that are to be monitored to assess change in distribution and extent (Rattray et al. 2009, McGonigle et al. 2010). This type of survey will require MBES data to be collected at a higher resolution and with a greater degree of positional accuracy.  Mapping for baseline survey and monitoring surveys will be dealt with separately throughout the manual, with their differences and the requirements that need to be considered to meet the aims of each survey type outlined in Figure 3.4.

 

 ![image alt text](images/figures/image_3.png)

Figure 3.4. Decision tree for seabed classification survey design (adapted from Anderson et al. (2007)). For generalised MBES survey workflow, refer to Figure 2 of the Australian Multibeam Guidelines (Picard et al., 2018).

Table 3.2 Standard Operating Procedures identified according to survey purpose: Baseline or Monitoring

<table>
  <tr>
    <td>Specification</td>
    <td>NESP Baseline</td>
    <td>NESP Monitoring</td>
  </tr>
  <tr>
    <td>Purpose</td>
    <td>·         Used to identify seafloor habitats and potential biodiversity hotspots.
·         Used for discovery purposes in regions that have had no baseline mapping conducted.</td>
    <td>·         Used to ensure spatio-temporal assessment of the seabed and habitat. The survey accuracy standard is very high to ensure reproducibility over time.
·         Used for repeat mapping and for targeting key habitats for monitoring purposes.</td>
  </tr>
  <tr>
    <td>Pre survey preparation</td>
    <td>·         The coverage of the area to be surveyed (bounding box) with the datum and coordinate system clearly identified.
·         Apply for appropriate permits
·         Establishment of line spacing
·         Determination of the system offsets and calibration area (patch test) area to be conducted as soon as practical and after system is completely set up ready for survey.
·         The location and scheduling of the Sound Velocity Profiles</td>
    <td>·         In addition to baseline survey specifications:
·         Synthesis of all pre-existing survey data into survey region  database
·         Identification of locations of seafloor targets to be monitored
 
 
 </td>
  </tr>
  <tr>
    <td>Installation Offsets</td>
    <td>·         Provide Mobilisation Calibration Reports and logs</td>
    <td>·         Provide Mobilisation Calibration Reports and logs</td>
  </tr>
  <tr>
    <td>Data Logging</td>
    <td>·         Bathy: Mandated
·         Seabed Backscatter: Mandated
·         Water column backscatter: Recommended (if available)</td>
    <td>·         Bathy: Mandated
·         Seabed Backscatter: Mandated
·         Water column backscatter: Mandated (if available)</td>
  </tr>
  <tr>
    <td>Acquisition setting</td>
    <td>·         Mode: Equidistant mode where system allows
·         Minimise setting changes to optimise backscatter</td>
    <td>·         same</td>
  </tr>
  <tr>
    <td>Sound Velocity Profiles (SVP)</td>
    <td>·         Min of 1 per day, but should be monitored.
·         If sound speed at the transducer varies by > 2m/s another SVP should be collected</td>
    <td>·         Min of 2 per day (beginning and end of survey), but should be monitored.
·         If sound speed at the transducer varies by > 1m/s another SVP should be collected</td>
  </tr>
  <tr>
    <td>Geodetic Parameters</td>
    <td>·         GDA2020. Horizontal accuracy: 5m + 5% of water depth. Vertical accuracy: 1% water depth</td>
    <td>·         GDA2020 -– Horizontal accuracy: absolute positioning to be < 2 m. Vertical accuracy: < 0.5 m</td>
  </tr>
  <tr>
    <td>Survey Speed</td>
    <td>·         at survey speed appropriate to capture resolution required (typically 5 knots or less)</td>
    <td>·         at survey speed appropriate to capture resolution required (typically 5 knots or less)</td>
  </tr>
  <tr>
    <td>Mapping Coverage & Overlap</td>
    <td>·         100% Coverage with 30% overlap between survey lines of data with an 80% confidence level.</td>
    <td>·         100% coverage with 60% overlap between survey lines of data with an 80% confidence level.</td>
  </tr>
  <tr>
    <td>Resolution</td>
    <td>·         1 m resolution in < 50m depth ; 5% of depth beyond 50 m</td>
    <td>·          1 m resolution</td>
  </tr>
  <tr>
    <td>Tides and GPS Tide</td>
    <td>·         Record GPS tides. All soundings shall be reduced to the ellipsoid.</td>
    <td>·         Record GPS tides. All soundings shall be reduced to the ellipsoid.
 </td>
  </tr>
  <tr>
    <td>Point data attribution</td>
    <td>·         All data should be attributed with its uncertainty estimate at the 80% confidence level for both position and, if relevant, depth.</td>
    <td>·         All data should be attributed with its uncertainty estimate at the 95% confidence level for both position and, if relevant, depth.</td>
  </tr>
  <tr>
    <td>Metadata and Reports</td>
    <td>·         Metadata report shall include heading and data deliverables outlined in this manual. Calibration Report and Report of Survey.</td>
    <td>·         Metadata report shall include heading and data deliverables outlined in this manual. Calibration Report and Report of Survey.</td>
  </tr>
  <tr>
    <td>Archiving</td>
    <td>·         Australian Online Data Network (AODN) data portal.
·         National MBES Data Centre</td>
    <td>·         Australian Online Data Network (AODN) data portal.
·         National MBES Data Centre</td>
  </tr>
</table>
