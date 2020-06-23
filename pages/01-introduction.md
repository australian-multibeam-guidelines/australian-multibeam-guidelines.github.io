---
layout: home
permalink: /introduction
title: "1. Introduction"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
toc: true
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

High-resolution seafloor mapping has developed into a significant component of the marine surveying industry in the past few decades, with a rapid growth in demand for this fundamental marine geospatial data. There is a large and increasing number of drivers and applications for this data, including:



*   Navigation and safety of life at sea
*   Environmental assets management (including Fisheries management)
*   Ocean and climate modelling
*   Hydrodynamic modelling
*   Coastal and nearshore sediment mapping
*   Resource development
*   Aquaculture planning
*   Oil and gas subsea assets integrity
*   Telecommunication cable deployment
*   Renewable energy assessments
*   Marine spatial planning
*   Territorial claims
*   Demonstration of Antarctic presence
*   Underwater cultural heritage management
*   Artificial reef development

These applications have resulted in seafloor mapping in locations from the upper reaches of estuaries to the abyssal plains from the tropics as far north as Papua New Guinea to the Southern Ocean to the waters of the Australian Antarctic Territory.

In Australia, apart from port and harbour surveying, much of the focus has been on mapping areas of the continental shelf and slope at varying levels of coverage and resolution, which reflect the drivers for mapping, vessel and gear availability, and the combination of targeted and opportunistic data collection. However, despite a significant increase in survey coverage in the past decade, less than 25% of the seafloor in Australia’s maritime jurisdiction has been mapped to a relatively high-resolution.

Since only the narrow coastal margin of the seafloor can be detected by airborne or satellite sensors (e.g. lasers; multi-spectral scanners), swath acoustic mapping systems, principally multibeam echosounders (MBES) and bathymetric sidescan sonars (interferometric sonar), are used to map Australia’s seafloor. These systems measure water depth, seabed backscatter (commonly known as seabed hardness), and in some cases with MBES, water-column backscatter. Multibeam sonar data is acquired by a wide range of organisations, however, to better realise the value of the data collaboration is needed to build broad regional and national seabed data sets and data needs to be acquired to a common standards. This data needs to be openly available, and easily accessible for reuse to benefit the wider community (Table 1). 

The primary objective of this guideline is thus to establish common approaches to the acquisition and processing of MBES data. Use of these guidelines will improve consistency in the collection and description of the data, enhancing its quality and utility.

To achieve this objective, [AusSeabed](http://www.ausseabed.gov.au) was formed, a national seabed mapping coordination program run by a consortium of representatives from Commonwealth and State governments, universities and industry. AusSeabed’s role is to encourage and facilitate the acquisition of seabed mapping data and make it available for use by all stakeholders. As such, the program runs a series of coordinated initiatives, including:



*   the production of maps identifying priority areas for Commonwealth and State Government agencies
*   maintenance of the **Australian Multibeam Guidelines** (this document)
*   the [AusSeabed website](http://www.ausseabed.gov.au/) hosting various resources, survey planning and data management tools, including a [data portal](https://portal.ga.gov.au/persona/marine).

_Table 1 Key stakeholders benefiting from better coordination and availability of seabed mapping data and the type of data they preferentially use (note the list is not exhaustive, but intended to give examples)_


<table>
  <tr>
   <td rowspan="2" >Stakeholder
   </td>
   <td colspan="2" >Preferred data type
   </td>
  </tr>
  <tr>
   <td>Source data (raw or processed files) 
   </td>
   <td>Products (e.g. maps of seabed depths, habitat, morphology)
   </td>
  </tr>
  <tr>
   <td>Department of Defence (e.g. Hydrography, Mine warfare)
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Marine parks (Australia or States Marine Parks)
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Department of Industry, Innovation and Science (e.g. NOPSIMA)
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Industry (Oil & Gas; Infrastructure)
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>State coastal planning and management groups
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Maritime Jurisdiction (Geoscience Australia)
   </td>
   <td>X
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Australian Tsunami Advisory group
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>State and Commonwealth research institutions (e.g. CSIRO, Geoscience Australia, State environment and fisheries agencies)
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Universities
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
</table>


Overall these initiatives aim to achieve a number of specific objectives, including:



*   collation of a historically sorted dataset at an identified level of quality available to all stakeholders within Australia and beyond
*   identification of areas where new data is needed most
*   enabling stakeholders to better leverage Australia’s seabed mapping expertise and capabilities
*   providing tools to allow efficient and consistent pre-survey planning
*   promoting collaboration and innovation with stakeholders
*   utilising national resources and efforts to map Australia’s seabed
*   providing clear guidelines that aim to improve data acquisition methods and compliance with recognised standards
*   increasing data availability for stakeholders
*   ensuring better informed management of Australian waters through easy access to a larger set of standards-compliant seabed data


## 1.1 Scope
The Australian Multibeam Guidelines were established by the AusSeabed consortium. The guidelines provide recommended procedures for survey planning, data acquisition and submission, from the pre-survey planning phase to the data submission phase. They are designed for a range of audiences, from those experienced in seafloor mapping using multibeam sonar systems, non-experts who are developing mapping capabilities, and those contracting seafloor mappingsurveys using swath systems. 

These guidelines aim to improve interoperability, discoverability and accessibility of MBES system data, and encourage improved acquisition standards to better meet end-user requirements. We acknowledge that to achieve such an aim, adaptation of the project might be necessary and could impact time and cost. However, in most cases, the inconvenience of varying parameters will be outweighed by the increased utility of the data to a wider user base.

These guidelines provide a minimum set of requirements for seafloor mapping activities conducted in Australian waters. They are designed to complement the purpose-based requirements and associated documentation related to specific survey requirements (e.g., hydrographic surveys; seabed infrastructure planning or installation) (Figure 1).

<img src="images/figures/image1.png" width="75%" class="center">

_Figure 1 Anticipated key areas of relevance for the Australian Multibeam Guidelines._

The guidelines include a broad examination of data processing and guidance for data submission (Figure 2) with recommendations for all three types of swath acoustic data (bathymetry, backscatter and water column backscatter) relevant across all water depths and adopt international guidelines where appropriate. They do not include instrument preparation activities such as bench/workshop tests, personnel requirements, or provide survey costing information (see section 5.3.4 of Przeslawski et al. 2018a for MBES Costing). This revision of the Australian Multibeam Guidelines (version 2) contains information previously published in the _Seafloor Mapping Field Manual for Multibeam Sonar_ (Lucieer et al., 2018) as chapter 8 _(Multibeam acoustics for marine monitoring_) and, as such, will also succeed the _Seafloor Mapping Field Manual for Multibeam Sonar_ as chapter 3 in the second release of the National Environmental Science Program (NESP) _Field manuals for Marine Sampling to Monitor Australian Waters_ (Przeslawski and Foster, 2018). The decision to make this extension to the guidelines and inclusion in the NESP suite of Field Manuals was made by AusSeabed and the NESP to allow both initiatives to continue with a single reference document to inform seabed mapping and eliminate the complications and community confusion associated with the maintenance of two reference documents with extensive overlap.



## 1.2 How to use guidelines
To help navigate these guidelines, Table 2 identifies sections that are more relevant to various user-groups. Glossaries of abbreviations and terms are included in appendices [A](https://australian-multibeam-guidelines.github.io/appendices#appendix-a--abbreviations) and [B](https://australian-multibeam-guidelines.github.io/appendices#appendix-b--glossary), and a variety of tools and resources available are included in Table 3. Some tools are still under development and will be shared through the [AusSeabed website](http://www.ausseabed.gov.au/). 

These guidelines do not include a full and comprehensive technical description of MBES systems, but rather, provide a list of pertinent references, such as Hughes-Clarke (2017a). They also refer to related guidelines where relevant.

_Table 2 Relevance to the various user groups by document section number. However, all stakeholders will find useful information in all sections_


<table>
  <tr>
   <td><strong>Section</strong>
   </td>
   <td><strong>Non-expert groups</strong>
   </td>
   <td><strong>Expert groups</strong>
   </td>
  </tr>
  <tr>
   <td><strong>1 Introduction</strong>
   </td>
   <td>All
   </td>
   <td>All
   </td>
  </tr>
  <tr>
   <td><strong>2 Pre-survey planning</strong>
   </td>
   <td>All
   </td>
   <td>2.1; 2.2; 2.4; 2.5; 2.6
   </td>
  </tr>
  <tr>
   <td><strong>3 Mobilisation, Calibration & Validation</strong>
   </td>
   <td>3.1; 3.9
   </td>
   <td>All
   </td>
  </tr>
  <tr>
   <td><strong>4 Acquisition</strong>
   </td>
   <td>4.1; 4.6
   </td>
   <td>All
   </td>
  </tr>
  <tr>
   <td><strong>5 Processing and Rendering</strong>
   </td>
   <td>5.3
   </td>
   <td>All
   </td>
  </tr>
  <tr>
   <td><strong>6 Reports</strong>
   </td>
   <td>All
   </td>
   <td>All
   </td>
  </tr>
</table>

## 1.3 Related standards and publications
The following publications provide information to underpin the collection of geospatial data and augment these guidelines. The complete references can be found in [section 9](https://australian-multibeam-guidelines.github.io/references), but the most recent published versions of key documents are: 

1. AHO, 2017. Hydroscheme Industry Partnership Program - Statement of requirements 
2. AHO. [Hydrographic Note](http://www.hydro.gov.au/feedback/feedback-hydronote.htm), Australian Hydrographic Office 
3. AHO. [Seafarer’s Handbook for Australian Water](http://www.hydro.gov.au/prodserv/publications/ash.htm) (AHP20) 
4. CHS, 2013. [Hydrographic survey management guidelines](http://www.charts.gc.ca/data-gestion/guidelines-directrices/index-eng.asp)
5. Mills J. and Dodd D., 2014. [Ellipsoidally Referenced Surveying for Hydrography](http://www.fig.net/resources/publications/figpub/pub62/figpub62.asp). FIG Publication No. 62 
6. GeoHab Backscatter Working Group, 2015. [Backscatter measurements by seafloor-mapping sonars: Guidelines and Recommendations](http://geohab.org/wp-content/uploads/2013/02/BWSG-REPORT-MAY2015.pdf). 
7. Godin, A., 1998. [The Calibration of Shallow Water Multibeam Echo-Sounding Systems](http://www2.unb.ca/gge/Pubs/TR190.pdf), Technical Report No. 190. 
8. Hughes-Clarke, J.E., 2003. [A reassessment of vessel coordinate systems: what is it that we are really aligning?](http://www.google.com.au/url?url=http://citeseerx.ist.psu.edu/viewdoc/download%3Fdoi%3D10.1.1.491.4731%26rep%3Drep1%26type%3Dpdf&rct=j&frm=1&q=&esrc=s&sa=U&ved=0ahUKEwio2v-O1MHXAhUFlJQKHVVMDmoQFggUMAA&usg=AOvVaw3GHq_CvZfTbubftpVUnQOd) 
9. ICSM, 2018. [Geocentric Datum of Australia Technical Manual](http://www.icsm.gov.au/datum/gda2020-and-gda94-technical-manuals).
10. ICSM, 2004. [Australian Tides Manual (SP9)](http://icsm.gov.au/publications/australian-tides-manual-v44). 
11. ICSM, 2014a. [Guidelines for Control Surveys by GNSS (SP1)](https://www.icsm.gov.au/sites/default/files/2018-02/Guideline-for-Control-Surveys-by-GNSS_v2.1.pdf). 
12. ICSM, 2014b. [Guidelines for Control Surveys by Differential Levelling (SP1)](https://www.icsm.gov.au/sites/default/files/2018-02/Guideline-for-Control-Surveys-by-Differential-Levelling_v2.1.pdf). 
13. ICSM, 2014c. [Standard for the Australian Survey Control Network (SP1)](http://www.icsm.gov.au/publications/standard-australian-survey-control-network-special-publication-1-sp1). 
14. IHO, 2008. [IHO Standards for Hydrographic Survey, (S-44)](https://www.iho.int/iho_pubs/IHO_Download.htm)
15. IHO, 2013. [Manual on Hydrography (C-13)](https://www.iho.int/iho_pubs/IHO_Download.htm). 
16. IHO, 2015. [INT1 Symbols, Abbreviations and Terms used on Charts](https://www.iho.int/iho_pubs/IHO_Download.htm). 
17. IOGP, 2018. [Seabed Survey Data Model (SSDM)](http://www.iogp.org/geomatics/#ssdm)
18.  Lamarche G. and Lurton X., 2017. [Recommendations for improved and coherent acquisition and processing of backscatter data from seafloor-mapping sonars](https://link.springer.com/article/10.1007/s11001-017-9315-6). 
19. LINZ, 2016, [Contract Survey Specifications for Hydrographic Surveys, Vers. 1.3](https://www.linz.govt.nz/sea/charts/standards-and-technical-specifications-for-our-chart-and-hydrographic-work)
20. Lucieer V. et al., 2017. [Seamap Australia](http://seamapaustralia.org)
21. Przeslawski R. et al., 2018. [NESP field Manual for grab and box core sampling](https://grabs-and-boxcorers-field-manual.github.io/)
