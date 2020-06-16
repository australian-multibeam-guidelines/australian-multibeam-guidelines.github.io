---
layout: home
permalink: /acquisition
title: "Acquisition"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}


    19. 
Survey plan
Acquisition of the MBES data should follow the pre-survey plan discussed in 

<p id="gdcalert37" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 2"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert38">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 2](#heading=h.44sinio), unless the on-board seabed mapping lead decides otherwise based on the environmental situation and new information at-hand, which are difficult to account for in the planning stage. It is recommended that any changes to the acquisition plan are captured in the Report of Survey (

<p id="gdcalert38" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 6.2.2"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert39">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 6.2.2](#heading=h.1d96cc0)). Wherever possible, nearing the conclusion of data acquisition, a review of data coverage is highly recommended and infill lines conducted to ensure there are no gaps in the bathymetry, as this impacts the suitability of the data for end use. Additional lines over significant shoal features are also recommended to ensure good density of soundings and determination of least depth. For efficiency, such lines may be conducted concurrently to other activities such as during transits or seabed sampling. Emphasis here is put on the system settings and other specifics that were not recommended in 

<p id="gdcalert39" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 2"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert40">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 2](#heading=h.44sinio), especially 

<p id="gdcalert40" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 2.5"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert41">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 2.5](#heading=h.4f1mdlm).



    20. 
Project structure and nomenclature
Although the project structure and nomenclature is specific to the project, it is recommended that the following conventions be considered to facilitate data submission and interoperability:



*   project structure:
    1. reports
    2. tides
    3. QA DataPack
    4. products
    5. raw data (

<p id="gdcalert41" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "see 2.3.1"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert42">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[see 2.3.1](#heading=h.qsh70q))
    6. processed data
    7. backscatter
    8. WC data
*   file naming convention should be sequential, include timestamp and system type, e.g. nnnn_yyyymmdd_hhmmss_system, where: nnnn is the sequential number; yyyymmdd is the date; hhmmss is the time



    21. 
Systems settings
System settings should depend on the purpose of the seafloor mapping and the data types that are being recorded. 



        23. 
Bathymetry
While acquiring data, the power, pulse width and gain need to be monitored and adjusted during the course of the survey to ensure good bathymetry. For high resolution/high frequency operations a short pulse width is desirable. As water depth increases, longer pulse widths will become necessary.



        24. 
Backscatter
If the MBES system is capable, it is required that you ensure backscatter data (both the Beam Average Backscatter and the Time Series “Snippets” Backscatter data) are being logged and stored with the bathymetry data files. It is imperative that the Range (R), intensity (I), angle (Ɵ) information are all recorded. Collecting these data may require custom settings to be applied during the initial set up of the acquisition software.

When acquiring data, it is essential that a log is kept of all settings and changes made to settings during acquisition (

<p id="gdcalert42" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 6.2.1"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert43">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 6.2.1](#heading=h.2y3w247)). Do NOT run the MBES system on auto mode as this will make it very difficult to normalise the backscatter data due to the dynamic changes in the pulse length. Changes to the pulse length and pulse type should be avoided if possible, and if not, kept to a minimum. If you are required to change either of these settings please stop logging at the end of the line and apply new settings before starting to log the next line and detail in the log accordingly. Efforts should also be made to minimise constant saturation of the seabed backscatter signal. 

At the end of a survey, an **additional backscatter calibration test is essential** if you have used pulse lengths that differ from your original patch test and backscatter calibration**.** This calibration test is made up by running the same line once for each pulse length that was used during the survey. It is important that enough space is given for the turn so that the line can be intersected straight on because the calibration requires the lines to directly overlap for at least 500 m. Please record which pulse length coincides with which line number for each calibration run. 



        25. Transit data

It is recommended that the system settings during transit data acquisition be set to maximise data quality by considering the overall characteristics of the transit rather than maximise data coverage or swath width. Refer also to 

<p id="gdcalert43" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 2.5.5"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert44">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 2.5.5](#heading=h.111kx3o).

Unless a deep water CTD or XBT cast is available throughout the transit and when water depth is greater than 200m, a generic SVP tool, such as the [Hydroffice Sound Speed Manager](https://www.hydroffice.org/soundspeed/main) tool can be used to improve profiles. Should no SVP option be available, the sound velocity should be set to 1500m/sec.



    22. 
Ancillary systems


        26. 
Sound velocity Profile
It is recommended that: 



*   for shelf waters (&lt; 200m water depth), at least one SVP be conducted every 24 hours. However, every 6 hours would better align with Bureau of Meteorology (BOM) weather reporting requirements 
*   for “off the shelf” surveys (> 200 m), SVP may not be necessary daily, but monitoring of the SVP is still recommended as per point below.
*   SV be constantly monitored and SVP be collected if visual changes are observed in the acquired swath (e.g. frown or smiles), or the SV vessel probe indicate greater changes than 2 or 3 m/s at the sonar head for a consistent period of time. 

Note that SVP for all depths are also highly valued by other types of users, such as oceanographers and ecologists. To further accommodate such users it is recommended that SVPs are also collected during deployment and retrieval of deep-tow systems, ROVs and AUV.



        27. 
Tides 
During a survey, acquisition of GNSS tide (ellipsoidal height of the vessel minus the geoid model at the same location) can be monitored; however, it is difficult to monitor tide gauges unless regular download of the data is undertaken. Therefore, for GNSS tides acquisition, it is recommended to:



*   ensure that all the bathymetry files include GNSS height, otherwise GNSS tides will be computed to less than 10 cm vertical accuracy.
*   use an updated Geoid model (e.g. AUSGeoid2020) keeping in mind that this model is unsuitable offshore.
*   acquire the delayed heave from the MRU without gaps and ensure that the bathymetry data has a complete delayed heave coverage applied.
*   compute GNSS tide for all the files.

During the survey, data QC should be done using predicted tides from the [Bureau of Meteorology](http://www.bom.gov.au/australia/tides/) (BOM) for standard ports or [AusTides](http://www.hydro.gov.au/prodserv/publications/ausTides/tides.htm) for secondary ports. Refer also to 

<p id="gdcalert44" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 2.5.2"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert45">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 2.5.2](#heading=h.28h4qwu).



    23. 
Monitoring, QA/QC & Data backup
During a survey the following information should be constantly monitored, including:



*   depth
*   vessel draft
*   GNSS (see 

<p id="gdcalert45" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 4.5.1"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert46">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 4.5.1](#heading=h.319y80a)) or subsea positioning for sub-sea platform
*   motion sensor
*   sound velocity
*   backscatter consistency and saturation
*   overlap
*   data density

To ensure safe data transport it is recommended that multiple copies of the data be made and transported separately in the time between data collection and submission (

<p id="gdcalert46" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 7"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert47">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 7](#heading=h.3x8tuzt)).



        28. 
GNSS positioning
Most seafloor mapping and GNSS software provide real-time monitoring capabilities. The quality of the GNSS data should be monitored while mapping to ensure that the horizontal positioning falls within the seafloor mapping specification. Any deviations outside of the survey specification should be noted and included within the Report of Survey (

<p id="gdcalert47" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "section 6.2"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert48">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[section 6.2](#heading=h.1d96cc0)). Maintaining a minimum QC requirement will provide data that is interoperable with many providers and uses. This integrity information includes (LINZ, 2016):



*   Sigma values or semi-major axis of the positional error ellipse are not to exceed 3.5m at the 95% confidence level.
*   The DGNSS correction age is not to exceed 10 secs.
*   PDOP is not to exceed 6 for recording and continued sounding. If PDOP is greater than 7 then surveying is to be halted until it improves.
*   The minimum number of observable healthy satellites being tracked during survey operations is to be 5.
*   The minimum elevation for SVs is to be 10° above the horizon.



    24. 
Mandatory notifications


        29. 
Dangers found – hydrographic notes
It is **imperative** that any feature found, which may be a <span style="text-decoration:underline;">potential navigational hazard</span> to vessels, **is reported to the AHO** by hydrographic note ([AHO, AH102](http://www.hydro.gov.au/feedback/AA217160-hydro-note.pdf)) and <span style="text-decoration:underline;">if an immediate danger exists</span>,** the Joint Rescue Coordination Centre (JRCC) Australia (AMSA)**. Once danger is reported and received by these agencies, the agencies noted assume responsibility for further reporting to mariners. Should reports not be lodged and an incident occurs, liability may be passed on to operators who failed to notify dangers during operational activities.



        30. 
Underwater cultural heritage notification
Thousands of historic ship and plane wrecks are known to exist within Australian waters, although the locations of many of these remain unknown. Information about known shipwrecks can be found using the [Australian National Shipwreck Database](http://environment.gov.au/heritage/historic-shipwrecks/australian-national-shipwreck-database). Notifying relevant State and Commonwealth management agencies, when underwater cultural heritage sites are discovered, will greatly assist these organisations to manage fragile and irreplaceable resources [(Table 8)](#bookmark=id.1tuee74). Notification of underwater cultural heritage finds is also a legal requirement under the _[Historic Shipwrecks Act 1976](https://www.legislation.gov.au/Details/C2016C01026) _(Cth) (HSA)_ _and state heritage protection legislation (see section 17 (1) of the Act).

A notification report should include a snapshot of the scan image, coordinates, water depth and a brief description of the site giving dimensions of the object.



_Table 8 Contact details of management agencies to notify for wrecks_


<table>
  <tr>
   <td><strong>Commonwealth:</strong>
<p>
Historic Heritage Section \
Department of the Environment and Energy \
GPO Box 787 \
CANBERRA ACT 2601 \
Tel: (02) 6274 2116 \
Website: <a href="http://www.environment.gov.au/heritage/historic-shipwrecks">www.environment.gov.au/heritage/historic-shipwrecks</a>
   </td>
   <td><strong>Northern Territory</strong>:
<p>
Heritage Branch \
Department of Lands, Planning and the Environment \
GPO Box 1680 \
DARWIN NT 0801 \
Tel: (08) 8999 5039 \
Email: heritage@nt.gov.au \
Website: <a href="http://www.dlp.nt.gov.au/heritage/maritime-heritage">www.dlp.nt.gov.au/heritage/maritime-heritage</a>
   </td>
  </tr>
  <tr>
   <td><strong>Commonwealth:</strong>
<p>
Great Barrier Reef Marine Park Authority \
Heritage, International and Governance \
Project Manager, Maritime Cultural Heritage \
GPO Box 1379 \
TOWNSVILLE QLD  \
Tel: (07) 4750 0618 
<p>
Email: <a href="mailto:info@gbrmpa.gov.au">info@gbrmpa.gov.au</a> \
Website: <a href="http://www.gbrmpa.gov.au/">www.gbrmpa.gov.au/</a> 
   </td>
   <td><strong>South Australia:</strong>
<p>
State Heritage Unit \
Department for Environment, Water and Natural Resources \
GPO Box 1047 \
ADELAIDE SA 5001 \
Tel: 08) 8124 4960 \
Email: DEWNRheritage@sa.gov.au \
Website: <a href="http://www.environment.sa.gov.au/our-places/cultural-heritage/Maritime_heritage%20">www.environment.sa.gov.au/our-places/cultural-heritage/Maritime_heritage </a>
   </td>
  </tr>
  <tr>
   <td><strong>Queensland:</strong>
<p>
Heritage Branch \
Department of Environment and Heritage Protection \
GPO Box 2454 \
BRISBANE QLD 4001 \
Tel: 13 74 68 \
Email:  info@ehp.qld.gov.au \
Website: <a href="http://www.qld.gov.au/environment/land/heritage/archaeology/maritime/%20">www.qld.gov.au/environment/land/heritage/archaeology/maritime/ </a>
   </td>
   <td><strong>Tasmania:</strong>
<p>
Historic Heritage \
Parks and Wildlife Service \
GPO Box 1751 \
HOBART TAS 7001 \
Tel: 1300 827 727 \
Email: mike.nash@parks.tas.gov.au \
Website: <a href="http://www.parks.tas.gov.au/index.aspx?base=1729">www.parks.tas.gov.au/index.aspx?base=1729</a>
   </td>
  </tr>
  <tr>
   <td><strong>New South Wales:</strong>
<p>
Heritage Division \
Office of Environment and Heritage \
Locked Bag 5020 \
PARRAMATTA NSW 2124 \
Tel: (02) 9873 8500 \
Email: heritage@heritage.nsw.gov.au \
Website: <a href="http://www.environment.nsw.gov.au/maritimeheritageapp/WebsiteSearch.aspx%20">www.environment.nsw.gov.au/maritimeheritageapp/WebsiteSearch.aspx </a>
   </td>
   <td><strong>Victoria:</strong>
<p>
Heritage Victoria \
Department of Planning and Community Development \
GPO Box 2392 \
MELBOURNE VIC 3001 \
Tel: (03) 9938 6894 \
Email: heritage.victoria@delwp.vic.gov.au \
Website: <a href="http://www.dtpli.vic.gov.au/heritage/shipwrecks-and-maritime">www.dtpli.vic.gov.au/heritage/shipwrecks-and-maritime</a>
   </td>
  </tr>
  <tr>
   <td><strong>Norfolk Island:</strong>
<p>
Norfolk Island Museum \
Kingston \
NORFOLK ISLAND 2899 \
Tel: (0011) 672 323 788 \
Email: admin@museums.gov.nf \
Website: <a href="http://norfolkislandmuseum.com.au/exhibitions/hms-sirius/%20">http://norfolkislandmuseum.com.au/exhibitions/hms-sirius/ </a>
   </td>
   <td><strong>Western Australia:</strong>
<p>
Western Australian Museum \
Maritime Archaeology Department \
45-47 Cliff Street \
FREMANTLE WA 6160 \
Tel: (01) 300 134 081 \
Email: reception@museum.wa.gov.au \
Website:  <a href="http://museum.wa.gov.au/research/research-areas/maritime-archaeology">http://museum.wa.gov.au/research/research-areas/maritime-archaeology</a>
   </td>
  </tr>
</table>



