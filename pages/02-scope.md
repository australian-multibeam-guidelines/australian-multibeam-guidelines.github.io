---
permalink: /scope
title: "Scope"
excerpt: ""
image:
  feature: /banners/02_banner.jpg
layout: home

---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

This manual refers to the use of multibeam or interferometric echosounders (referred herein as just MBES) to conduct surveys of seafloor bathymetry and backscatter that can be used to derive maps of geomorphic features and benthic habitats. It does not mandate use of a specific interferometric3 or beamforming4 multibeam. The examples given herein refer to Kongsberg systems merely as an exemplar of the procedure to be conducted. Similarities can be drawn from these examples to any particular MBES system being employed on the survey.

 

There are several MBES that have been commonly used for surveying in Australian waters that would be suited to marine monitoring activities. It is important that the seafloor mapper be mindful that there are differences in the way bathymetric measurements are made from both interferometric and beamforming multibeam echosounders, and these influence the scale and resolution of features being detected and the fidelity of the acoustic measurements (which is important for monitoring). The main difference is namely due to beam formers measuring range for each of a set of angles, and interferometers measuring angle for each of a set of ranges (Table 5). We have outlined the standard methods that are relevant to any of these systems to provide a framework to create a nationally consistent MBES data archive for Australian marine and coastal waters.

 

This field manual details the specific four main phases of a seabed mapping survey (acquisition, processing, interpretation, reporting) that are required to meet the needs of monitoring programs (Figure 3.2). Although MBES can be used for water column data collection, these data are outside the scope of this standard operating procedural document in its current version (Version 0.1). This document provides guidance to organisations responsible for permitting and supporting research programs (e.g. Parks Australia) to collect multibeam data for monitoring programs (e.g. government research agencies, universities) to ensure consistency in acquisition and processing of multibeam acoustic data. This will increase the chance that data and spatial data products from different organisations and swath systems can be combined and reused into the future and become a valuable data asset for national research objectives; ongoing monitoring and planning.

 

![image alt text](image_1.png)

Figure 3.2. Workflow from MBES survey design to spatial data products and reporting

Table 3.1. Comparison of bathymetric systems (reference: Bathyswath.com)

<table>
  <tr>
    <td>Parameter / Function</td>
    <td>Interferometric Multibeam</td>
    <td>Beamforming Multibeam
(single-head configuration)</td>
    <td>Notes</td>
  </tr>
  <tr>
    <td>Number of depth measurements</td>
    <td>6000+</td>
    <td>60-400</td>
    <td>Depends on range</td>
  </tr>
  <tr>
    <td>Range vs. water depth</td>
    <td>10 - 20</td>
    <td>3-5</td>
    <td>Beam former footprint becomes unacceptably large at far range.</td>
  </tr>
  <tr>
    <td>Amplification / processing channels</td>
    <td>4-5</td>
    <td>60 +</td>
    <td>In a harsh environment, simplicity is important</td>
  </tr>
  <tr>
    <td>Outboard transducer electronics</td>
    <td>Passive</td>
    <td>Active</td>
    <td>The outboard component of an interferometer is extremely robust, and cheaper to replace if damage does occur</td>
  </tr>
  <tr>
    <td>Outboard transducer size and weight</td>
    <td>350x160x60mm
5 kg (air)</td>
    <td>120x190x450mm
13 kg (air)</td>
    <td>Dimensions for a common portable beam former. Many beam formers are much larger.</td>
  </tr>
  <tr>
    <td>Horizontal resolution at range</td>
    <td>Good</td>
    <td>Poor</td>
    <td>Beam former footprint becomes unacceptably large at far range.</td>
  </tr>
  <tr>
    <td>Angular coverage</td>
    <td>260°(including 20° overlap)</td>
    <td>90°- 180°</td>
    <td> </td>
  </tr>
  <tr>
    <td>Co-incident sidescan</td>
    <td>True</td>
    <td>Partial</td>
    <td>An interferometer collects amplitude in the same way as its bathymetry: as a time-series.</td>
  </tr>
  <tr>
    <td>Profile data density</td>
    <td>Increases with reducing grazing angle</td>
    <td>Decreases with reducing grazing angle</td>
    <td>Higher complete profile data confidence with an interferometer.</td>
  </tr>
  <tr>
    <td>Ability to resolve several targets at the same range</td>
    <td>No</td>
    <td>Yes</td>
    <td> </td>
  </tr>
  <tr>
    <td>Ability to resolve several targets at the same angle</td>
    <td>Yes</td>
    <td>No</td>
    <td> </td>
  </tr>
  <tr>
    <td>Profile data density</td>
    <td>Increases with reducing grazing angle</td>
    <td>Decreases with reducing grazing angle</td>
    <td>In the first 5 m of horizontal range, a beam former collects slightly more depth samples. Beyond that, an interferometer collects many more.</td>
  </tr>
  <tr>
    <td>Capacity to acquire water column information?</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Interferometric systems can identify targets in the water column but are unable to characterise them accurately due to lack of beam forming angles to locate the target.</td>
  </tr>
</table>


