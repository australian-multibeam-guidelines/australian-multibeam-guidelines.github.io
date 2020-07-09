---
layout: home
permalink: /acquisition
title: "4. Acquisition"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

# 4.1 Survey plan
Acquisition of the MBES data should follow the pre-survey plan discussed in [section 2](https://australian-multibeam-guidelines.github.io/pre-survey-planning), unless the on-board seabed mapping lead decides otherwise based on the environmental situation and new information at-hand, which are difficult to account for in the planning stage. It is recommended that any changes to the acquisition plan are captured in the Report of Survey ([section 6.2.2](https://australian-multibeam-guidelines.github.io/reports#622-report-of-survey)). Wherever possible, nearing the conclusion of data acquisition, a review of data coverage is highly recommended and infill lines conducted to ensure there are no gaps in the bathymetry, as this impacts the suitability of the data for end use. Additional lines over significant shoal features are also recommended to ensure good density of soundings and determination of least depth. For efficiency, such lines may be conducted concurrently to other activities such as during transits or seabed sampling. Emphasis here is put on the system settings and other specifics that were not recommended in [section 2](https://australian-multibeam-guidelines.github.io/pre-survey-planning), especially [section 2.5](https://australian-multibeam-guidelines.github.io/pre-survey-planning#25-field-survey-instructions).

# 4.2 Project structure and nomenclature
Although the project structure and nomenclature is specific to the project, it is recommended that the following conventions be considered to facilitate data submission and interoperability:

*   project structure:
    1. reports
    2. tides
    3. QA DataPack
    4. products
    5. raw data ([see 2.3.1](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata))
    6. processed data
    7. backscatter
    8. WC data
*   file naming convention should be sequential, include timestamp and system type, e.g. nnnn_yyyymmdd_hhmmss_system, where: nnnn is the sequential number; yyyymmdd is the date; hhmmss is the time

# 4.3 Systems settings
System settings should depend on the purpose of the seafloor mapping and the data types that are being recorded. 

# _4.3.1 Bathymetry_
While acquiring data, the power, pulse width and gain need to be monitored and adjusted during the course of the survey to ensure good bathymetry. For high resolution/high frequency operations a short pulse width is desirable. As water depth increases, longer pulse widths will become necessary.

# _4.3.2 Backscatter_
If the MBES system is capable, it is required that you ensure backscatter data (both the Beam Average Backscatter and the Time Series “Snippets” Backscatter data) are being logged and stored with the bathymetry data files. It is imperative that the Range (R), intensity (I), angle (Ɵ) information are all recorded. Collecting these data may require custom settings to be applied during the initial set up of the acquisition software.

When acquiring data, it is essential that a log is kept of all settings and changes made to settings during acquisition ([section 6.2.1](https://australian-multibeam-guidelines.github.io/reports#621-logs)). Do NOT run the MBES system on auto mode as this will make it very difficult to normalise the backscatter data due to the dynamic changes in the pulse length. If possible:
*   avoid changes to the pulse length and pulse type or keep to a minimum
*   collect in equidistant mode
*   stop logging at the end of the line and apply new settings before starting to next line if changes are made (capturing changes in the log accordingly)
*   minimise constant saturation of the seabed backscatter signal. 

At the end of a survey, an **additional backscatter calibration test is essential** if you have used pulse lengths that differ from your original patch test and backscatter calibration. This calibration test is made up by running the same line once for each pulse length that was used during the survey. It is important that enough space is given for the turn so that the line can be intersected straight on because the calibration requires the lines to directly overlap for at least 500 m. Please record which pulse length coincides with which line number for each calibration run. 

# _4.3.3 Transit data_
It is recommended that the system settings during transit data acquisition be set to maximise data quality by considering the overall characteristics of the transit rather than maximise data coverage or swath width. Refer also to [section 2.5.5](https://australian-multibeam-guidelines.github.io/pre-survey-planning#255-line-planning).

Unless a deep water CTD or XBT cast is available throughout the transit and when water depth is greater than 200m, a generic SVP tool, such as the [Hydroffice Sound Speed Manager](https://www.hydroffice.org/soundspeed/main) tool can be used to improve profiles. Should no SVP option be available, the sound velocity should be set to 1500m/sec.

# 4.4 Ancillary systems
# _4.4.1 Sound velocity Profile_
It is recommended that: 
*   for shelf waters (&lt; 200m water depth), at least one SVP be conducted every 24 hours. However, every 6 hours would better align with Bureau of Meteorology (BOM) weather reporting requirements 
*   for “off the shelf” surveys (> 200 m), SVP may not be necessary daily, but monitoring of the SVP is still recommended as per point below.
*   SV be constantly monitored and SVP be collected if visual changes are observed in the acquired swath (e.g. frown or smiles), or the SV vessel probe indicate greater changes than 2 m/s at the sonar head for a consistent period of time. 

Note that SVP for all depths are also highly valued by other types of users, such as oceanographers and ecologists. To further accommodate such users it is recommended that SVPs are also collected during deployment and retrieval of deep-tow systems, ROVs and AUV.

# _4.4.2 Tides_
During a survey, acquisition of GNSS tide (ellipsoidal height of the vessel minus the geoid model at the same location) can be monitored; however, it is difficult to monitor tide gauges unless regular download of the data is undertaken. Therefore, for GNSS tides acquisition, it is recommended to:
*   ensure that all the bathymetry files include GNSS height, otherwise GNSS tides will be computed to less than 10 cm vertical accuracy.
*   use an updated Geoid model (e.g. AUSGeoid2020) keeping in mind that this model is unsuitable offshore.
*   acquire the delayed heave from the MRU without gaps and ensure that the bathymetry data has a complete delayed heave coverage applied.
*   compute GNSS tide for all the files.

During the survey, data QC should be done using predicted tides from the [Bureau of Meteorology](http://www.bom.gov.au/australia/tides/) (BOM) for standard ports or [AusTides](http://www.hydro.gov.au/prodserv/publications/ausTides/tides.htm) for secondary ports. Refer also to [section 2.5.2](https://australian-multibeam-guidelines.github.io/pre-survey-planning#252-tidal-or-ellipsoidal-datum).

# 4.5 Monitoring, QA/QC & data backup
During a survey the following information should be constantly monitored, including:
*   depth
*   vessel draft
*   GNSS (see [section 4.5.1](https://australian-multibeam-guidelines.github.io/acquisition#451-gnss-positioning)) or subsea positioning for sub-sea platform
*   motion sensor
*   sound velocity
*   backscatter consistency and saturation
*   overlap
*   data density

To ensure safe data transport it is recommended that multiple copies of the data be made and transported separately in the time between data collection and submission ([section 7](https://australian-multibeam-guidelines.github.io/data-release)).

# _4.5.1 GNSS positioning_
Most seafloor mapping and GNSS software provide real-time monitoring capabilities. The quality of the GNSS data should be monitored while mapping to ensure that the horizontal positioning falls within the seafloor mapping specification. Any deviations outside of the survey specification should be noted and included within the Report of Survey ([section 6.2](https://australian-multibeam-guidelines.github.io/reports#62-record-of-survey)). Maintaining a minimum QC requirement will provide data that is interoperable with many providers and uses. This integrity information includes (LINZ, 2016):
*   sigma values or semi-major axis of the positional error ellipse are not to exceed 3.5m at the 95% confidence level
*   the DGNSS correction age is not to exceed 10 secs
*   PDOP is not to exceed 6 for recording and continued sounding. If PDOP is greater than 7 then surveying is to be halted until it improves.
*   the minimum number of observable healthy satellites being tracked during survey operations is to be 5
*   the minimum elevation for SVs is to be 10° above the horizon.

# 4.6 Mandatory notifications
# _4.6.1 Dangers found – hydrographic notes_
It is **imperative** that any feature found, which may be a <span style="text-decoration:underline;">potential navigational hazard</span> to vessels, **is reported to the Australian Hydrographic Office ([datacentre@hydro.gov.au](mailto:datacentre@hydro.gov.au))** by hydrographic note ([AHO, AH102](http://www.hydro.gov.au/feedback/AA217160-hydro-note.pdf)) and <span style="text-decoration:underline;">if an immediate danger exists</span>,** the Joint Rescue Coordination Centre (JRCC) Australia (AMSA)**. Once danger is reported and received by these agencies, the agencies noted assume responsibility for further reporting to mariners. Should reports not be lodged and an incident occurs, liability may be passed on to operators who failed to notify dangers during operational activities.

# _4.6.2 Underwater cultural heritage notification_
Thousands of historic ship and plane wrecks are known to exist within Australian waters, although the locations of many of these remain unknown. Information about known shipwrecks can be found using the [Australian National Shipwreck Database](http://environment.gov.au/heritage/historic-shipwrecks/australian-national-shipwreck-database). Notifying relevant State and Commonwealth management agencies, when underwater cultural heritage sites are discovered, will greatly assist these organisations to manage fragile and irreplaceable resources (Table 8). Notification of underwater cultural heritage finds is also a legal requirement under the _[Historic Shipwrecks Act 1976](https://www.legislation.gov.au/Details/C2016C01026) _(Cth) (HSA)_ _and state heritage protection legislation (see section 17 (1) of the Act).

A notification report should include a snapshot of the scan image, coordinates, water depth and a brief description of the site giving dimensions of the object. It is requested that the Australian Hydrographic Office ([datacentre@hydro.gov.au](mailto:datacentre@hydro.gov.au)) is included as an information addressee on all notification reports to the relevant authorities.

_**Table 8:** Contact details of management agencies to notify for wrecks_
<table>
<tbody>
  <tr>
    <td><strong>Commonwealth:</strong><br>Historic Heritage SectionDepartment of the Environment and EnergyGPO Box 787CANBERRA ACT 2601Tel: (02) 6274 2116Website: <a href="http://www.environment.gov.au/heritage/historic-shipwrecks">www.environment.gov.au/heritage/historic-shipwrecks</a></td>
    <td><strong>Northern Territory:</strong><br>Heritage BranchDepartment of Lands, Planning and the EnvironmentGPO Box 1680DARWIN NT 0801Tel: (08) 8999 5039Email: heritage@nt.gov.auWebsite: <a href="http://www.dlp.nt.gov.au/heritage/maritime-heritage">www.dlp.nt.gov.au/heritage/maritime-heritage</a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><strong>Commonwealth:</strong><br>Great Barrier Reef Marine Park AuthorityHeritage, International and GovernanceProject Manager, Maritime Cultural HeritageGPO Box 1379TOWNSVILLE QLD Tel: (07) 4750 0618 <br>Email: <a href="mailto:info@gbrmpa.gov.au">info@gbrmpa.gov.au</a>Website: <a href="http://www.gbrmpa.gov.au/">www.gbrmpa.gov.au/</a> </td>
    <td><strong>South Australia:</strong><br>State Heritage UnitDepartment for Environment, Water and Natural ResourcesGPO Box 1047ADELAIDE SA 5001Tel: 08) 8124 4960Email: DEWNRheritage@sa.gov.auWebsite: <a href="http://www.environment.sa.gov.au/our-places/cultural-heritage/Maritime_heritage%20">www.environment.sa.gov.au/our-places/cultural-heritage/Maritime_heritage </a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><strong>Queensland:</strong><br>Heritage BranchDepartment of Environment and Heritage ProtectionGPO Box 2454BRISBANE QLD 4001Tel: 13 74 68Email:  info@ehp.qld.gov.auWebsite: <a href="http://www.qld.gov.au/environment/land/heritage/archaeology/maritime/%20">www.qld.gov.au/environment/land/heritage/archaeology/maritime/ </a></td>
    <td><strong>Tasmania:</strong><br>Historic HeritageParks and Wildlife ServiceGPO Box 1751HOBART TAS 7001Tel: 1300 827 727Email: mike.nash@parks.tas.gov.auWebsite: <a href="http://www.parks.tas.gov.au/index.aspx?base=1729">www.parks.tas.gov.au/index.aspx?base=1729</a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><strong>New South Wales:</strong><br>Heritage DivisionOffice of Environment and HeritageLocked Bag 5020PARRAMATTA NSW 2124Tel: (02) 9873 8500Email: heritage@heritage.nsw.gov.auWebsite: <a href="http://www.environment.nsw.gov.au/maritimeheritageapp/WebsiteSearch.aspx%20">www.environment.nsw.gov.au/maritimeheritageapp/WebsiteSearch.aspx </a></td>
    <td><strong>Victoria:</strong><br>Heritage VictoriaDepartment of Planning and Community DevelopmentGPO Box 2392MELBOURNE VIC 3001Tel: (03) 9938 6894Email: heritage.victoria@delwp.vic.gov.auWebsite: <a href="http://www.dtpli.vic.gov.au/heritage/shipwrecks-and-maritime">www.dtpli.vic.gov.au/heritage/shipwrecks-and-maritime</a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><strong>Norfolk Island:</strong><br>Norfolk Island MuseumKingstonNORFOLK ISLAND 2899Tel: (0011) 672 323 788Email: admin@museums.gov.nfWebsite: <a href="http://norfolkislandmuseum.com.au/exhibitions/hms-sirius/%20">http://norfolkislandmuseum.com.au/exhibitions/hms-sirius/ </a></td>
    <td><strong>Western Australia:</strong><br>Western Australian MuseumMaritime Archaeology Department45-47 Cliff StreetFREMANTLE WA 6160Tel: (01) 300 134 081Email: reception@museum.wa.gov.auWebsite:  <a href="http://museum.wa.gov.au/research/research-areas/maritime-archaeology">http://museum.wa.gov.au/research/research-areas/maritime-archaeology</a></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>