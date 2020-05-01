---
layout: home
permalink: /
title: "Seafloor Mapping for Multibeam Sonar"
excerpt: ""
image:
  feature: /banners/00_banner.jpg
page.button1.external_url:
  url: https://www.nespmarine.edu.au/
  caption: NESP
---

[Vanessa Lucieer](mailto:vanessa.lucieer@utas.edu.au), Kim Picard, Justy Siwabessy, Alan Jordan, Maggie Tran, Jacquomo Monk

![](images/MBES.png)

Chapter citation:
Lucieer V, Picard K, Siwabessy J, Jordan A, Tran M, Monk J. 2018. Seafloor mapping field manual for multibeam sonar. In Field Manuals for Marine Sampling to Monitor Australian Waters, Przeslawski R, Foster S (Eds). National Environmental Science Programme (NESP). pp 42-64. 

| Chapter Contents                                                                                                                                       |
|-------------------------------------------------------------------------------------------------------------------------------------------------|
|  **[Platform Description](https://multibeam-echosounder-field-manual.github.io/platform-description)**   
|  __[Scope](https://multibeam-echosounder-field-manual.github.io/scope)__                                                                        |
|  **[Multibeam Acoustics for Marine Monitoring](https://multibeam-echosounder-field-manual.github.io/multibeam-acoustics-for-marine-monitoring)** |
|  **[Pre-Survey Preparations](https://multibeam-echosounder-field-manual.github.io/pre-survey-preparations)**                                   |
|  **[Data Acquisition](https://multibeam-echosounder-field-manual.github.io/data-acquisition)**                                                   |
|       _[Installation offsets](https://multibeam-echosounder-field-manual.github.io/data-acquisition#installation-offsets)_                   |
|       _[Data logging](https://multibeam-echosounder-field-manual.github.io/data-acquisition#data-logging)_                                     |
|       _[Sound velocity profiles](https://multibeam-echosounder-field-manual.github.io/data-acquisition#sound-velocity-profiles)_                |
|       _[Geodetic parameters](https://multibeam-echosounder-field-manual.github.io/data-acquisition#geodetic-parameters)_                      |
|       _[Survey speed](https://multibeam-echosounder-field-manual.github.io/data-acquisition#survey-speed)_                                  |
|       _[Line spacing](https://multibeam-echosounder-field-manual.github.io/data-acquisition#line-spacing)_                                     |
|       _[Pulse length](https://multibeam-echosounder-field-manual.github.io/data-acquisition#pulse-length)_                                   |
|       _[Tides and GPS tides](https://multibeam-echosounder-field-manual.github.io/data-acquisition#tides-and-gps-tides)_                        |
|  **[Data Processing](https://multibeam-echosounder-field-manual.github.io/data-processing)**                                                    |
|       _[Bathymetric data processing](https://multibeam-echosounder-field-manual.github.io/data-processing#bathymetric-data-processing)_        |
|       _[Backscatter data processing](https://multibeam-echosounder-field-manual.github.io/data-processing#backscatter-data-processing)_        |
|  **[Data Interpretation](https://multibeam-echosounder-field-manual.github.io/data-interpretation)**                                             |
|  **[Data Release](https://multibeam-echosounder-field-manual.github.io/data-release)**                                                           |
|  **[Field Manual Maintenance](https://multibeam-echosounder-field-manual.github.io/field-manual-maintenance)**                                   |
|  **[References](https://multibeam-echosounder-field-manual.github.io/references)**                                                               |




 $(document).ready(function(){
  $(window).scroll(function(){
      if ($(this).scrollTop() > 100) {
          $('.scrollUpButton').fadeIn();
      } else {
          $('.scrollUpButton').fadeOut();
      }
  });
  $('.scrollUpButton').click(function(){
      $("html, body").animate({ scrollTop: 0 }, 500);
      return false;
  });
 });
Step 2 - The CSS

.scrollUpButton {
 display: none;
 opacity: 0.6;
 position: fixed;
 bottom: 10px;
 right: 10px;
 display: none;
 background: #000;
 color: #fff;
 font-size: 1.5em;
 text-decoration: none;
 padding: 5px 10px 5px 10px;
}
.scrollUpButton:hover, .scrollUpButton:focus {
 outline: none;
 text-decoration: none;
 color: #fff;
 opacity: 1;
}
Step 3 - The HTML (Add this somewhere before the closing body tag)

<a href="#" class="scrollUpButton">&#9650</a>
