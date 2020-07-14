---
permalink: /pre-survey-planning
title: "2. Pre-survey Planning"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
layout: home

---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

The acquisition of data is the most expensive element of a seabed mapping project. Therefore, it is essential that this phase of a survey is optimised by undertaking adequate pre-survey planning. This section of the guidelines identifies key aspects of the planning phase that can be improved for more efficient and effective surveys. They also present tools and resources available that can help (Table 3). These resources are also hosted on the [AusSeabed](http://www.ausseabed.gov.au/) website, and we encourage using the website to discover the full breath of available resources and future updates. The [IHO C-13 Manual on Hydrography](https://iho.int/uploads/user/pubs/cb/c-13/english/C-13_Chapter_1_and_contents.pdf) also provides an appendix on planning considerations and how to best calculate survey timings.

_**Table 3:** Summary list of pre-survey planning tools proposed in the section_
<table>
<thead>
  <tr>
    <th>Tool or Resource</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><a href="https://portal.ga.gov.au/restore/bfa7d693-9a0a-4305-bb5e-3c70d329ea42">Upcoming Survey Register</a></td>
    <td>Register the survey to encourage collaboration and contribute to national coverage</td>
  </tr>
  <tr>
    <td><a href="https://portal.ga.gov.au/restore/c8ad335e-2ac6-4318-80ac-bc7089a3b155">AusSeabed Bathymetry Holdings</a></td>
    <td>Coverage of MBES dataset by various agencies.</td>
  </tr>
  <tr>
    <td><a href="http://www.iogp.org/geomatics/#ssdm">Seabed Survey Data Model</a></td>
    <td>The SSDM is a GIS model that has been developed since 2010 by the International Association of Oil &amp; Gas Producers (IOGP) to facilitate management, integration and sharing of survey data at all levels, i.e. international, national, local, etc. (<a href="http://www.iogp.org/bookstore/product/guidelines-for-the-use-of-the-seabed-survey-data-model/">IOGP, 2017</a>).</td>
  </tr>
  <tr>
    <td>A priori tools<br>1) <a href="https://www.rijkswaterstaat.nl/formulieren/aanvraagformulier-software-hydrografische-normen.aspx">Amust</a> <br><br><br><br><br><br><br><br><br><br><br><br><br>2) <a href="https://hydrochart.dk/hydrobib/">Hydrobib</a></td>
    <td>These tools help to determine expected uncertainties for a system. <br>Amust link points to a registration page on the Rijkswaterstaat (Dutch Hydrographic Service) website. See also <a href="https://australian-multibeam-guidelines.github.io/appendices#appendix-e--total-propagated-uncertainties">Appendix E</a> for a list of possible errors to take into account.<br><img src="https://lh3.googleusercontent.com/puPcqbKlDqqFbzknFhd-3BaRhQYu8iuBkvvqrrpcxAU5WQvN9A4S2oYAM8rM7QwKVo6UQ6Q54RpL4FyNKHIryVM6L-0BLl_BCSosYXEdLdcOGuIGtzUHOvk2t6oYmxKAee29DSIw" alt="G:\Kim_bckup_021217\GA other projects\AusSeabed\Guideline\Templates\AMUST.JPG" width="368" height="219">  <br><br>Hydrobib provides integrated utilities for survey planning. It is more specific to R2Sonic echosounder, but can be adopted for other echosounders.</td>
  </tr>
  <tr>
    <td>Datum tools<br><a href="https://vdatum.noaa.gov/">1) </a><a href="https://vdatum.noaa.gov/">VDatum</a><br>2) <a href="http://www.icsm.gov.au/what-we-do/permanent-committee-tides-and-mean-sea-level">AusCoastVDT</a></td>
    <td><br>1) Designed to vertically transform geospatial data among a variety of tidal, orthometric and ellipsoidal vertical datums.<br>2) A vertical datum transformation tool for the Australian coast.</td>
  </tr>
  <tr>
    <td>Line planning tool</td>
    <td>Most survey acquisition software packages (QPS, EIVA, HYPACK) have line planning capability built into them. See also <a href="https://hydrochart.dk/hydrobib/">Hydrobib</a> above</td>
  </tr>
</tbody>
</table>

# 2.1 National coverage consultation and upcoming survey register
AusSeabed is currently developing a suite of pre-survey tools to view the current extent of national bathymetry data holdings, consult a map of national seabed mapping priority areas, and utilise a survey coordination tool to register and query upcoming surveys. These tools are aimed at providing seabed mappers with information to promote collaboration in areas of common interest and eliminate effort duplication. This initiative is likely to benefit all parties by reducing overall costs and facilitating more efficient data collection in Australian waters.

Seamap Australia is a complementary mapping and analysis service that provides information about the Australian shelf collated from data providers (e.g. seafloor imagery, habitat classification) that may also inform proposed mapping areas (Lucieer et al., 2017).

# _2.1.1 Existing data coverage_
Before planning a survey we recommend consulting the [Bathymetry coverage](http://www.ausseabed.gov.au/surveys-data/bathymetry) layer hosted on the AusSeabed website to avoid the collection of duplicate data. The identify tool in this portal provides metadata information for each coverage polygon submitted to AusSeabed and a URL to the location where the high resolution data can be downloaded if it is available. This ensures that users are able to find existing data, or data custodian and contact details for surveys already conducted that might meet some or all of their needs. The layer contains the spatial extents and metadata of all surveys submitted to Geoscience Australia (GA) by AusSeabed collaborators and external third-parties. It is being continually developed to display national data coverage, with input from an increasing number of organisations.

The GA [MARS database](http://dbforms.ga.gov.au/pls/www/npm.mars.search) contains information on seabed sediment samples collected in Australian waters, analysed, and provided to GA. Links to other data samples collected by different entities is acknowledged as an item for future development.

# _2.1.2 National Bathymetry priorities_
The AusSeabed website also hosts an interactive map of [national bathymetry priorities](http://ausseabed.gov.au/surveys-data/priorities) that show areas that are considered important to government in terms of safety of life at sea, conservation, and environmental monitoring. It is recommended that this tool be consulted in the early stages of survey planning to promote collaboration amongst stakeholders with interests in specific areas. 

# _2.1.3 AusSeabed Coordination Tool_
It is also highly recommended that the upcoming survey layer is consulted on the AusSeabed portal in the early stages of survey planning to look for collaboration opportunities should there be other organisations planning to carry out work in areas of close proximity. Upcoming survey plans can be registered using the [AusSeabed Coordination Tool](https://planning.ausseabed.gov.au/login) to enable further collaboration and future tracking of new data. The tool allows users to display the planned extent and details of an upcoming survey and collects a set of metadata that are considered a minimum for any seabed mapping activity ([section 2.3.1.3](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata)) that can be utilised for the survey report and data submission following the survey. If desired, a more detailed planning document can also be attached. The AusSeabed Coordination Tool also hosts the online forms for submissions to the Hydroscheme Industry Investment Program, run by the AHO. To request a user log in for access to the survey coordination tool email [ausseabed@ga.gov.au](mailto:ausseabed@ga.gov.au?subject=Request%20for%20profile%20to%20use%20AusSeabed%20Coordination%20Tool).


# 2.2 Research and survey permits
Various permissions are required to undertake research in Commonwealth, State and Territory waters. Due to the complexity of laws and intersecting jurisdiction’s, information on this page should be treated as a guide only and information from the relevant governing bodies should be consulted to ascertain that the correct permissions have been acquired prior to any research undertaking. 

Operators should contact and inform relevant national and local authorities well in advance of any intended survey work ashore and afloat. These include the local harbour authority that should be consulted at all stages of the planning and execution of any harbour surveys, marine reserves, etc. Be mindful that approvals and permits (e.g. Environment Protection and Biodiversity Conservation, Environmental Plan, local marine parks permits, etc.) may be needed before undertaking a survey. Legislation for approvals is slightly different in each state. More information regarding legislation and permitting can be found on the [AusSeabed](https://ausseabed.gov.au/resources/permit) website. [Appendix C](https://australian-multibeam-guidelines.github.io/appendices#appendix-c--legislation-and-permitting) provides a list of authorities that may need to be consulted and some links to general research permits for state waters.

# 2.3 Seabed mapping data collection considerations 
The **objectives** of MBES surveys conducted by mapping programs are to collect seafloor data to identify, delineate and map biogenic, anthropogenic and geological features. This objective requires particular data to be collected that can a) chart the water depths creating a high resolution bathymetric map at an appropriate resolution in regards to the target habitat or feature and b) be able to differentiate boundaries between different substrate and/or habitat types.

This national guideline provides the minimum requirements for all seabed mapping activities to enable national coordination and compilation. It is thus designed as an overarching document that can be complemented by more specific requirements. If data collection is for charting purposes, consult the [Australian Hydrographic Office](mailto:hydro.plans@defence.gov.au) and the Hydroscheme Industry Partnership Program (HIPP) Statement of Requirements (SOR) available at [www.hydro.gov.au/NHP](http://www.hydro.gov.au/NHP). 

The application of these guidelines to marine monitoring has been included as a case study in chapter 8 that outlines the mandated best practice data and metadata requirements, QA/QC and data submission practices for baseline surveying or more targeted feature monitoring. [Appendix D](https://australian-multibeam-guidelines.github.io/appendices#appendix-d--guideline-on-timeframe-for-actions) provides some approximate planning timeframes as a guide for the various activities related to seabed mapping surveys.

# _2.3.1 Data type, formats, and metadata_
In 2019, AusSeabed held a workshop on data formats and metadata attributes to establish an agreed set of preferences for the delivery and acquisition of seabed data. The outcomes of that workshop underpin the information presented in the following sections, as a set of best practice policies to maximise the utility of collected open data.  

### 2.3.1.1 Data type
The types of data derived from a MBES survey are: 
*   bathymetry: essential
*   seabed backscatter: essential
*   water column backscatter: encouraged

The minimum essential requirements of any seafloor mapping survey are the bathymetric data and seabed backscatter data (the collection of which may require manual activation). Water column backscatter data acquisition is encouraged if the system can collect it. In addition to scientific benefits (such as identifying gas flares and vegetation mapping), water column data is a common method used to confirm least depth over features and to identify bathymetric artefacts. It is both used in terms of 3D visualisation of the seabed and in observing oceanographic turbulence, such as internal waves, which may result in bathymetric artefacts (Hughes-Clarke, 2017b). 

### 2.3.1.2 Data levels and file formats
Consistent definitions of data levels allow the community to reduce ambiguity when discussing, delivering, processing or describing data. The AusSeabed definitions of data levels has been modelled on those prescribed by NASA for Earth Observations data products (Table 6). 

_**Table 4:** AusSeabed Data Level Definitions_
<table>
<thead>
  <tr>
    <th rowspan="3">Level</th>
    <th rowspan="3">Definition</th>
    <th colspan="4">Examples</th>
  </tr>
  <tr>
    <td rowspan="2"><strong>MBES</strong></td>
    <td rowspan="2"><strong>Navigation and attitude</strong></td>
    <td colspan="2"><strong>Ancillary files</strong></td>
  </tr>
  <tr>
    <td><strong>SVP</strong></td>
    <td><strong>Tide</strong></td>
  </tr>
</thead>
<tbody>
  <tr>
    <td>L0</td>
    <td><strong>Unprocessed instrument data</strong> <br>Unprocessed/raw instrument data at full resolution as received from the sensor. Includes MBES and ancillary files as well as all artefacts.</td>
    <td>Observed by sensor<br></td>
    <td>Observed by sensorPOSMV</td>
    <td>Observed by sensor<br></td>
    <td>Observed by sensor, proprietary formats</td>
  </tr>
  <tr>
    <td>L1</td>
    <td><strong>Data merged with ancillary information</strong><br>Reconstructed L0 data undergoes correction with ancillary information, either from within the L0 data itself or separately collected ancillary files (e.g., delayed heave and svp). This level may include radiometric and geometric correction and calibration, but not cleaning. This level may not exist for all data types and may depend on the software used.</td>
    <td>Processed depthIntegration with ancillary information</td>
    <td colspan="3">N/A: Data proceeds straight to L2</td>
  </tr>
  <tr>
    <td>L2</td>
    <td><strong>Cleaned and/or derived variables</strong><br>L1 data undergoes cleaning and filtering to create the first ‘usable’ data.</td>
    <td>Bathymetry productCleaned &amp; filtered</td>
    <td>Processed to SBET</td>
    <td>Processed to *.txt</td>
    <td>Processed to *.txt</td>
  </tr>
  <tr>
    <td>L3</td>
    <td><strong>Variables mapped on a grid</strong><br>L2 data undergoes additional processing/value-adding to create L3 products. Variables mapped on uniform grid scales, with some consistency to produce derived products. L3 products cannot be backwards engineered into L2. </td>
    <td>Additional value added, or data sampled (e.g. grid, DEM)</td>
    <td colspan="3">For the majority of commercial software available, backscatter data is progressed automatically through the L1 and L2 stages and saved directly as an L3 final product. Note: L2 is the final ‘product’ for ancillary data types.</td>
  </tr>
</tbody>
</table>

A set of data formats has been recommended for each of the data levels and types described above based on community consultation (Table 5). Data submission to AusSeabed requires that the required data follow the formats and specifications outlined in this table. For submission of data it is required that all Priority 1 formats that are possible to be provided are provided. If this is not possible then the next highest priority format should be provided. AusSeabed strongly supports open source technology and formats, therefore open formats (when available) are the preferred option over proprietary formats, for any sensor and at any data level. For L3 Bathymetry data provided to the AusSeabed Data Hub it is required that both Priority 1 BAG formats and the 32-Bit Floating Point GeoTIFF files detailed in the specifications column are provided.

_**Table 5:** Preferred data formats by data type and level._
<table>
<thead>
  <tr>
    <th rowspan="2">Level</th>
    <th colspan="5">Preferred formats</th>
    <th colspan="2">Specifications</th>
  </tr>
  <tr>
    <td><strong>Bathymetry</strong></td>
    <td><strong>Backscatter</strong></td>
    <td><strong>Navigation</strong></td>
    <td><strong>Ancillary data</strong></td>
    <td colspan="2"></td>
    <td></td>
  </tr>
</thead>
<tbody>
  <tr>
    <td>L0</td>
    <td><strong>Priority 1</strong><br><li>.all, .s7k, .kmall, .xse, .mbXX equivalent mbsystem formats</li><br>
    <strong>Priority 2</strong><br><li>.gsf</li><br><br>
    <strong>Priority 3</strong><br><li>.xtf</li><br><br></td>
    <td><strong>Priority 1</strong><br><li>.all, .s7k, .kmall, .xse, .mbXX equivalent mbsystem formats</li><br>
    <strong>Priority 2</strong><br><li>.gsf</li><br>
    <strong>Priority 3</strong><br><li>.xtf</li></td>
    <td><strong>Priority 1</strong><br><li>Any proprietary formats that contain navigation and attitude (*.000) since no open formats exist yet.</li></td>
    <td><strong>Priority 1</strong><br><li>ASCII (txt, csv)</li><br>
    <strong>Priority 2</strong><br><li>Proprietary</li></td>
    <td colspan="2">Bathymetry and backscatter should contain all necessary datagrams required for processing, including raw backscatter per beam (and time series), and all required ancillary data. Water column data is recommended and if possible should be stored in a separate file.<br>Navigation and Ancillaries should contain date and time (calendar or UTC, specify otherwise) and geodetic reference system (geographic WGS84 or GDA2020 with an ellipsoidal height datum).</td>
    <td></td>
  </tr>
  <tr>
    <td>L1</td>
    <td><strong>Priority 1</strong><br><li>.gsf</li><br></td>
    <td><strong>Priority 1</strong><br><li>.gsf</li><br>
    <strong>Priority 2</strong><br><li>Proprietary</li></td>
    <td><strong>N/A</strong></td>
    <td><strong>N/A</strong></td>
    <td colspan="2">Not Compulsory for data submission<br>L1 should also include all raw data as required in L0 that allow for processing at any stages if required. Header information and sign convention are required to accompany ASCII point cloud.<br></td>
    <td></td>
  </tr>
  <tr>
    <td>L2</td>
    <td><strong>Priority 1</strong><br><li>.gsf, .las/laz</li></td>
    <td><strong>Priority 1</strong><br><li>.gsf</li></td>
    <td>SBET data + RMS (for generation of TPU)</td>
    <td><strong>Priority 1</strong><br><li>Text files: (ASCII .txt, NetCDF, .csv)</li><br>
    <strong>Priority 2</strong><br><li>Proprietary</li></td>
    <td colspan="2">When L2 data are provided, also include all L0 data to allow for reprocessing at any stages, if required. L2 should contain data that enable reproduction of L3.<br><strong>Bathymetry and Backscatter</strong><br>Variables: coordinates, depth (m, neg value) or intensity (dB), uncertainty, flag.<br>Coordinate system: Geographic (GDA2020 or WGS84)<br>Precision: Metric variables with minimum of 2 decimals; Angular variables degree decimals with minimum of 6 decimals<br><strong>Navigation and Ancillaries</strong><br>Date and time: Calendar and UTC or specify otherwise<br>Coordinate system: Geographic WGS84 or GDA2020 with an ellipsoidal height datum</td>
    <td></td>
  </tr>
  <tr>
    <td>L3</td>
    <td><strong>Priority 1</strong><br><li>BAG single-resolution</li>
    <li>BAG multi-resolution</li>
    <li>32-bit floating point GeoTIFF (.tiff)</li><br>
    <strong>Priority 2</strong><br><li>.las/.laz</li><br></td>
    <td><strong>Priority 1</strong><br><li>BAG single-resolution</li><br>
    <strong>Priority 2</strong><br><li>32-bit floating point GeoTIFF (.tiff)</li></td>
    <td><strong>Priority 1</strong><br><li>Sensor trackline (GeoJSON)</li></td>
    <td><strong>N/A</strong></td>
    <td colspan="2"><strong>Bathymetry and Backscatter</strong><br>Vertical datums: both Ellipsoid and MSL<br>Resolution as per <a href="https://australian-multibeam-guidelines.github.io/data-processing#512-post-survey">Table 9</a><br>Variables: coordinates, depth (m, neg value) or intensity (dB), density (sounding/cell), uncertainty, flag (bathymetry in GeoTIFF format requires three separate files: depth, density, uncertainty).<br>Coordinate system: Geographic GDA2020 or WGS84<br>Precision: Metric variables with minimum of 2 decimals; Angular variables with deg decimals and 6 decimals<br><strong>Navigation and Ancillaries</strong><br>Date and time: Calendar and UTC or specify otherwise<br>Coordinate system: Geographic WGS84 or GDA2020 with an ellipsoidal height datum</td>
    <td></td>
  </tr>
</tbody>
</table>

### 2.3.1.3 Metadata
Metadata consistency is an essential aspect of data management and a key step in the move to coordinate a comprehensive national repository of seabed data in the Australian marine estate. The following list of metadata outlines the minimum set to meet ISO 19115.3 standards. The AusSeabed community propose that best efforts are made by collecting and processing institutions to utilise these fields. Appending organisation specific fields is acceptable but such fields should not be used in place of the fields below (Table 6). An example template with descriptions of the metadata fields to assist organisations in “mapping” metadata information is included in [appendix H.2](https://australian-multibeam-guidelines.github.io/appendices#h2-ausseabed-minimum-required-metadata).  

_**Table 6:** Overview of required metadata._
<table>
<thead>
  <tr>
    <th>Metadata Category</th>
    <th>General</th>
    <th>Citation</th>
    <th>Survey </th>
    <th>Technical</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Metadata Fields</td>
    <td><li>Survey Title</li>
    <li>Survey ID</li>
    <li>Abstract</li>
    <li>Lineage</li></td>
    <td><li>Data Owner</li>
    <li>Custodian</li>
    <li>Country (data ownership)</li>
    <li>Collecting Entity</li>
    <li>Attribution Licence</li>
    <li>Legal Constraints</li>
    <li>Access Constraints</li>
    <li>Use Constraints</li></td>
    <td><li>Survey Area (general)</li>
    <li>Bounding Box</li>
    <li>Coordinate reference system-bounding Box</li>
    <li>Coordinate reference system–Survey Data</li>
    <li>Geodetic Datum of the survey</li>
    <li>Horizontal datum</li>
    <li>Vertical datum</li></td>
    <td><li>Instrument type</li>
    <li>Sensor type</li>
    <li>Sensor Frequency</li>
    <li>Platform type</li>
    <li>Platform name</li></td>
  </tr>
</tbody>
</table>

This set of metadata is not exhaustive, and a large number of specific survey, calibration and acquisition parameters need to be recorded in addition to the above information to ensure complete documentation of the survey process. These are categorised and detailed in the [section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records) which outlines the Mobilisation, Calibration and Validation reports.

# _2.3.2 Survey area characterization_
Operational requirements, gear availability and technical capacity will determine the most appropriate type of MBES system to use. The characteristics of the survey area and mapping requirements are also key issues to consider, including:
*   survey duration and size of the area
*   anticipated depth range as this will affect line planning ([section 2.5.5](https://australian-multibeam-guidelines.github.io/pre-survey-planning#255-line-planning)) and acquisition parameter settings ([section 4.3](https://australian-multibeam-guidelines.github.io/acquisition#43-systems-settings))
*   wind and wave conditions and seasonal weather changes
*   tidal regime and tidal infrastructure
*   feature detection and sounding density requirements; reflected in required pulse repetition (ping rates), swath width and survey speed
*   the nature of the seabed, which is important for seabed backscatter data acquisition ([section 4.3.2](https://australian-multibeam-guidelines.github.io/acquisition#432-backscatter)). If one of the objectives of the mapping is to understand the nature of the seabed and to predict it over the area of interest, seabed sediment sampling/imaging needs to be considered ([section 2.5.6](https://australian-multibeam-guidelines.github.io/pre-survey-planning#256-seabed-samples)). See also the [NESP field manuals](https://marine-sampling-field-manual.github.io/) for standard operating procedures on sediment sampling and underwater imagery.
*   water column anomalies and feature anomalies, which may benefit from recording seabed water column backscatter ([section 4.3.2](https://australian-multibeam-guidelines.github.io/acquisition#432-backscatter))
*   the time of year and relevance to whale migrations for low frequency instruments
*   potential interactions with surface fishing gear

# _2.3.3 Data representation (seafloor coverage and resolution)_
Data representation, with respect to seafloor coverage, depends primarily on the MBES system utilised. For MBES systems, data representation will be dependent on the beam width of the system and the associated footprint on the seafloor [(Table 4).](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata) It is important to consider that the data representation of the final output has to be greater or equal to the beam footprint. For bathymetric sidescan, however, the sounding interval on the seafloor is constant. 

Horizontal and vertical accuracy are two key factors of resolution that should also be taken into consideration when choosing the right equipment or designing a survey plan (sections [3.3](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#33-horizontal-positioning) and [3.4](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#34-vertical-positioning)). These can be assessed by listing all sources of error and calculate interactively the total propagated uncertainties of a sounding (TPU; [section 5.2](https://australian-multibeam-guidelines.github.io/data-processing#52-total-propagated-uncertainties-tpu)). The Total Vertical Uncertainty (TVU) must not exceed the depth accuracy, and total horizontal accuracy (THU) actually refers to the accuracy of the position of sounding on the seafloor and not the accuracy of the GPS [GNSS] position of the survey vessel alone. Survey speed can also affect the data representation and accuracy (Hughes-Clarke, 2017b).

If data representation is not the primary driver in the choice of the system to use, it is recommended that data be collected at the best resolution achievable by the system. 

_**Table 7:** MBES footprint (m) at nadir and beam width (deg). The beam footprint for a MBES increases in the outer beams._
<table>
<thead>
  <tr>
    <th></th>
    <th></th>
    <th colspan="6">Beam Width (deg)	</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td></td>
    <td>0.5</td>
    <td>0.7</td>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
  </tr>
  <tr>
    <td rowspan="10">D<br>E<br>P<br>T<br>H<br>(m)</td>
    <td>10</td>
    <td>0.09</td>
    <td>0.12</td>
    <td>0.17</td>
    <td>0.35</td>
    <td>0.52</td>
    <td>0.70</td>
  </tr>
  <tr>
    <td>25</td>
    <td>0.22</td>
    <td>0.31</td>
    <td>0.44</td>
    <td>0.87</td>
    <td>1.31</td>
    <td>1.74</td>
  </tr>
  <tr>
    <td>50</td>
    <td>0.44</td>
    <td>0.61</td>
    <td>0.87</td>
    <td>1.74</td>
    <td>2.62</td>
    <td>3.49</td>
  </tr>
  <tr>
    <td>75</td>
    <td>0.65</td>
    <td>0.92</td>
    <td>1.31</td>
    <td>2.62</td>
    <td>3.92</td>
    <td>5.23</td>
  </tr>
  <tr>
    <td>100</td>
    <td>0.87</td>
    <td>1.22</td>
    <td>1.75</td>
    <td>3.49</td>
    <td>5.23</td>
    <td>6.97</td>
  </tr>
  <tr>
    <td>250</td>
    <td>2.18</td>
    <td>3.05</td>
    <td>4.36</td>
    <td>8.72</td>
    <td>13.08</td>
    <td></td>
  </tr>
  <tr>
    <td>500</td>
    <td>4.36</td>
    <td>6.11</td>
    <td>8.73</td>
    <td>17.45</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>1000</td>
    <td>8.73</td>
    <td>12.22</td>
    <td>17.45</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>1500</td>
    <td>13.09</td>
    <td>18.33</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2500</td>
    <td>21.82</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>

It is important to highlight that identification of features of specific sizes rely on a combination of parameters. It is generally accepted that when using side scan sonar as the feature detection tool, that a minimum of five boresight hits are made on the feature target. When using MBES as the feature detection tool, the common requirement is to achieve a minimum 3 along track hits and 3 across track hits on the feature target. The above requirements are to be considered conservative and in line with accepted sampling theory. Refer to section 7.5 from AHO (2018) for further information.

The general formula to calculate the depth at which five pulses should ensonify a target of a given size at different speed is (GBHD, 1996): 

<img src="images/figures/equation1.png" width="" alt="alt_text" title="image_tooltip">


Where:

D = least depth of detection (metres below transducers)

S = speed in knots

t = along track dimension of target to be detected (metres)

ф= echo sounder's beam width (fore and aft) in degrees.

prr = pulse repetition rate (pulses per second (Hz))


# _2.3.4 Quality assessment / uncertainty scheme_
The International Hydrographic Organisation (IHO) publishes a document for hydrographic standards – IHO Special Publication (SP-44). [Appendix G](https://australian-multibeam-guidelines.github.io/appendices#appendix-g--iho-standards-) of this publication details a range of survey standards for varying purposes. By surveying and providing data to these minimum standards, a collaborative approach to providing safe maritime navigation in future surveying areas can be assured in areas where there may be a future need to conduct operations. 

However, these standards may not fit the purpose of the survey or be flexible enough ([Figure 1](https://australian-multibeam-guidelines.github.io/introduction#11-scope)). Therefore, it is recommended that each parameter be evaluated separately when planning a survey. Consideration should be given to other user specifications or requirements, such as Port Authorities and Marine Parks, as these could also be met with little additional time, effort or cost (e.g. PPA, 2017, Lucieer et al., 2018). The data would then benefit more users and contribute to the National Seabed Mapping effort.  

Regardless of the standards used, it is important to provide quality and uncertainty statements based upon calibration and validation evidence to ensure consistency.  These should be quantitative statements where numerical analysis is conducted e.g. TVU = +/-0.1m, THU = +/-1.0m.

# _2.3.5 Platforms & systems_
Seabed mapping can be conducted from a variety of platforms, including ships, which can have hull or pole-mounted systems, towed-platform or automated underwater and remotely operated vehicles (AUV and ROV respectively). While this guideline provides information that applies to any platform, this section only provides general information on the various platforms and does not address the specific requirements of each. Refer to the material referenced for more information.

### 2.3.5.1 Hull or pole-mounted systems
A hull-mounted system refers to a system fixed to the vessel, and is the most robust way to mount a transducer. However, due consideration must be given to the effects of acoustic interference and bubble sweep down over the face of the MBES transmit and receive arrays.

A pole-mounted system refers to a system fixed to the end of a pole, which is commonly mounted to the side or the bow of the vessel. They are commonly used for smaller installations, allowing for permanent or deployable mounting. Rigidity and minimisation of the vibration of the pole are key to acquiring good quality data. It is also recommended that where possible, the motion reference unit (MRU) be installed and ‘tightly coupled’ on the pole at the transducer. 

For deployable pole-mounted systems, it is important to consider that every time the system is deployed, there should be assurance that the system returns to exactly the same position in order to negate the requirement for another patch test. An operating check, which is less robust than a patch test but verifies the mount is returned to the correct position, should be conducted if the pole is reset.  This may be as simple as performing cross perpendicular lines over a significant feature and analysing for incorrect alignments.

Regardless of which method is used to deploy the swath system, it is important to understand the negative impact of vessel hull, machinery noise and bubble sweep-down on the system. Care should be taken to install the transducers as far away from acoustic noise sources as possible and to ensure a smooth flow of water over the sonar(s) when the vessel is underway at the planned survey speed. Clients should be made aware that it is rarely possible to guarantee an acoustically silent installation on any vessel being used for the first time. Unfortunately, it is often a case of undertaking the installation and subsequently testing, before the suitability of the vessel and installation can be known.

This [website](http://www.bathyswath.com/installTransducers) provides additional information on various possible mounts and considerations. Note that the working group is not endorsing the company that this information is taken from.

# _2.3.6 Dimension control of sensor offsets_
Dimensional control, otherwise known as a sensor offset survey, is essential to any seafloor mapping survey and needs to be reported (see [section 3.2](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#32-dimensional-control)).

# 2.4 Project team
The project team should include personnel with relevant and adequate experience in swath acoustic instrumentation and survey requirements. These may consist of qualified people from various backgrounds, such as geophysicists, geologists, engineers, and hydrographic surveyors, but also increasingly includes marine ecologists and spatial analysts that manage seafloor mapping programs. 

It is recommended that for all survey reports each team member should be identified. This provides traceability for decisions and the data acquired. It is also highly recommended that a member of the team has completed professional training in the principles and operation of swath systems and provides evidence of recent field experience with swath acoustic systems.

# 2.5 Field survey instructions

# _2.5.1 Geodetic control and horizontal datum_
Seabed mapping surveys conducted within the Australian EEZ shall be referenced to a geodetic reference frame based on the International Terrestrial Reference System (ITRS), e.g. ITRF 2014 (GRS80 Spheroid) during collection.

Data should be processed on the Geocentric Datum of Australia 2020 ([Figure 2](https://australian-multibeam-guidelines.github.io/pre-survey-planning#251-geodetic-control-and-horizontal-datum); [GDA2020](https://www.icsm.gov.au/sites/default/files/GDA2020TechnicalManualV1.1.1.pdf)) which is being implemented to modernise the geodetic positioning, based on 1994 models (ICSM, 2018). Stage 1 of GDA2020 will be fixed to the epoch 2020.0 and Stage 2 (anticipated in 2020) will transition to a time dependent reference frame and will be known as the Australian Terrestrial Reference Frame (ATRF). Specific information regarding GDA2020 can also be found on [GA’s website](http://www.ga.gov.au/scientific-topics/positioning-navigation/datum-modernisation).

<img src="images/figures/image2.png" width="70%">

_**Figure 2:** Extent of GDA2020 on the Australian continental shelf (Geoscience Australia)_

Proposed Horizontal control should be reviewed for accuracy and if local control such as RTK base stations are to be used, then sites for local positioning systems should be determined. To establish shore-based geodetic control, refer to the procedures described in Intergovernmental Committee on Surveying and Mapping (ICSM, 2014a-c). 

Grid positions shall be referenced to the Universal Transverse Mercator (UTM) Grid.

# _2.5.2 Tidal or ellipsoidal datum_
The datum to which depths are to be reduced is fundamental to any seafloor mapping survey. Many datums can be used (Figure 3), but the common datums are the ellipsoidal or tidal chart datums (sections 2.5.2.1 and 2.5.2.2). While mapping however, the sounding datum should be used. 

<img src="images/figures/image3.png" width="70%">

_**Figure 3:** Schematic of datum and associated reduction information (Mills & Dodd, 2014)_

Regardless of the datum used for the final products, the following points need to be considered:
*   direct tide from the GNSS (GPS tide) should be recorded
*   all data should be acquired and processed in WGS84 or ITRF if available
*   all raw GNSS observations should be kept to allow post-processing 
*   all efforts should be made to improve positions to the highest accuracy possible, and post-processing will usually also improve horizontal positioning and minimise heave artefacts.

Typically, post-processing would involve:
*   offshore: Precise Point Positioning (PPP) corrections using the final International GNSS Service (IGS) products
*   coastal regions: kinematic post processing against land based fixed GNSS base stations, either permanent or deployed.

Transformation to the required ‘publication datum’ can be made after this process but retains the benefits of being connected to the global datum. These transformations can be done using [AusCoastVDT](https://www.icsm.gov.au/publications/australian-coastal-vertical-datum-transformation-auscoastvdt-software), which is a free software tool with a blanket accuracy of ± 0.5 m for MSL to LAT reductions. AusCoastVDT was developed by the Intergovernmental Committee on Surveying and Mapping, a collaboration between the Australian states, Defence Force and New Zealand.

### 2.5.2.1 Ellipsoidal datum
With the advancement of modern GNSS positioning systems and post-processing methods, ellipsoidal datum connections can be employed as an alternative to the Lowest Astronomical Tide (LAT) or chart datum (CD) connections. The GRS80 ellipsoid vertical reference surface has benefits to scientific and environmental disciplines with a consistent surface separation of seafloor features globally, please confirm that this ellipsoid is being used by your geodetic coordinate system.

When used in conjunction with GNSS connected/levelled tide gauge data, connections to CD/LAT can be estimated where required. For details on the issues of this method see “Ellipsoidally Referenced Surveying for Hydrography” (FIG, 2014).

### 2.5.2.2 Tidal Datum
When surveying for the purposes of nautical charting, it is essential to have knowledge of local tides. In many areas around Australia, the tidal network infrastructure is sparse and additional temporary tidal infrastructure will be required. To acquire ‘observed tide’ from a tide gauge, a number of tide gauges will need to be installed depending on the tidal complexity of the environment, albeit it is desirable to have at least one gauge installed. 

For specific advice regarding recommended tidal infrastructure for your survey area, please contact the Australian Hydrographic Office ([tides.support@defence.gov.au](file:///C:\Users\u99337\AppData\Local\Microsoft\Windows\Temporary%20Internet%20Files\Content.Outlook\13SAM0XD\tides.support@defence.gov.au)).

# _2.5.3 Sound velocity profiling_
Sound Velocity Profiling (SVP) of the water column is essential to the acquisition of swath mapping data, and is used for ray tracing through the water column. SVP influences directly the accuracy and uncertainty of both the horizontal and vertical position of each sounding and its impact is greatest towards the outer beams of the swath (farthest sounding). 

Physical processes such as fresh water influx, solar warming of the upper water column, presence of mesoscale currents, and storm mixing can affect the temperature and salinity profile, and hence the SVP. These changes can occur at various spatial and temporal scales and can sometimes be observed in the water column backscatter data. 

Acquisition of SVPs must be planned to identify the relevant number and distribution of profiles, and monitored carefully during the survey. It is recommended to commence a survey area with frequent SVPs until the behaviour of the water column is understood and then reduce the time and spatial interval as required to maintain best quality depth data. It is recommended that SVPs are conducted with a minimum interval of 6 hours. If sounding is restricted to the daytime only then SVPs should be conducted at the beginning and end of the day as the absolute minimum, but this is not recommended. The SVP can be determined using one of the following methods:

1. direct observation via deployment of a SVP measuring device 
2. calculation of the SVP through deployment of an expendable bathy thermograph (XBT)
3. bar check
4. calculation of the SVP using CTD (Conductivity/Temperature/Depth) data and applying the [UNESCO formula](https://www.usna.edu/Users/physics/ejtuchol/documents/SP411/Chapter4.pdf)


# _2.5.4 Time and date_

All digital data, field notebooks (logs) and samples should be set and recorded using the Coordinated Universal Time (UTC) and associated date. 

For descriptive text used in reporting, the time zone should be clearly specified (AWST, ACST, and AEST).

# _2.5.5 Line planning_
Survey line planning will vary based on the seafloor mapping objectives. However, the following minimum recommendations have to be taken into consideration:



1. <span style="text-decoration:underline;">Seabed topography</span>: lines should be designed parallel to the general direction of seabed contours as much as possible for swath systems.
2. <span style="text-decoration:underline;">Depth range</span>: the depth of the survey area changes the swath width and consequently the line spacing.  Large areas should be divided into similar depth ranges so that the requirement to run in-fill lines is reduced. 
3. <span style="text-decoration:underline;">Swath width (angle)</span>: depends on what type of swath system is used for the project (e.g. dual versus single-head MBES system), and hence the line spacing will differ. It is nearly always necessary to operate the swath system at less than published ‘maximum’ swath angles in order to improve the quality of the data collected and to improve the sounding density of the data collected.
4. <span style="text-decoration:underline;">Overlap</span>: for full (100%) seabed mapping coverage, a minimum of 10% overlap of the good data swath (data meeting the 95% uncertainty level) is recommended. This will enable validation by comparison of the data acquired at the edge of each swath. For partial coverage, where possible, it is recommended to use line spacing that will enable a subsequent in-fill mapping effort to complete the mapping of the area. 
5. <span style="text-decoration:underline;">Other requirements</span>: acquisition of other sonar data, seabed and water column backscatter data (see below), etc. may dictate a different line spacing.
6. <span style="text-decoration:underline;">Regular checks</span>: where there is an object of interest on the seabed detected in the survey, additional lines should be run to better delineate the feature and overall area.
7. <span style="text-decoration:underline;">Crosslines</span>: crosslines are essential quality indicators, especially for data uncertainty management, and hence it is **highly recommended** to plan multiple crosslines. 

  As a minimum, one cross line per “block” of data mapped should be acquired. Crossline(s) should normally be run last so that the cross line can be run perpendicularly across the whole extent of the data block collected. 

8. <span style="text-decoration:underline;">Turn data</span>: consists of data that is recorded during a vessel turning from one survey line to the next. While data quality may not be at its best during turns due to poor MRU stabilisation, this data nevertheless provides new information that can be useful for some users. BUT, it is strongly recommended to record turns as a **separate file** (i.e. stop recording before the turn, record the turn, and start recording new line.) so that the data can easily be removed if the artefacts outweigh the benefits of coverage.
9. <span style="text-decoration:underline;">Transit data</span>: consists of data generally acquired between port and the primary survey area and is used as “discovery” data. Data from transit or passage sounding, contributes significantly to the national good by increasing knowledge of our seabed, and oceanography. 

  Transit data should be:

   1. logged whenever possible unless the sea conditions are deemed too bad
   2. collected over new ground, i.e. not where previously mapped
    3. recorded and identified as a separate file to the primary survey lines
10. <span style="text-decoration:underline;">File length</span>: depending on the system used, the rate of data acquisition and data type being collected, the size of the digital file recorded will vary. To avoid data loss and facilitate data management, it is recommended that file size be managed and data collected as smaller files in preference to large continuous files (an upper limit of 500 MB is suggested).

Where **seabed backscatter data is the primary objective** of the survey, the same recommendations as above apply with the following exceptions:

11. <span style="text-decoration:underline;">Incidence angles</span>: overlap should be as the swath coverage but limited to incidence angles between 20 and 60 degrees [(Figure 4](https://australian-multibeam-guidelines.github.io/pre-survey-planning#255-line-planning); Lamarche and Lurton, 2017). This angle requirement is needed in order to compensate for the high variability of individual backscatter intensities (Gavrilov and Parnum, 2010; Kloser, 2017).

<img src="images/figures/image4.png" width="85%" class="center">

_**Figure 4:** Diagram of ideal swath overlap (After Lamarche and Lurton, 2017)._

12. <span style="text-decoration:underline;">Repeated seabed backscatter survey</span>: For survey using the same swath system, it is recommended that the survey strategies, such as survey direction and orientations, and the system settings are kept identical. Frequency should also not be changed.

See [section 4.2](https://australian-multibeam-guidelines.github.io/acquisition#42-project-structure-and-nomenclature) which provides information regarding the project structure and nomenclature

# _2.5.6 Seabed samples_
Seabed samples are often acquired during a seafloor mapping survey for various purposes, including seabed characterisation and seafloor backscatter data calibration. It is thus recommended that procedures outlined in the relevant chapters of the ‘Field manuals for marine sampling to monitor Australian waters’ (Przeslawski and Foster 2018) are followed. 

This manual recommends sending the samples to Geoscience Australia for analyses, such as grain-size, carbonate content, and results will be delivered in [MARS](http://dbforms.ga.gov.au/pls/www/npm.mars.search) public database. This analysis of samples contributes significantly to the knowledge of our seabed.

# 2.6 Submission of plan, data and notifications
See sections [2.1.3](https://australian-multibeam-guidelines.github.io/pre-survey-planning#213-ausseabed-coordination-tool), [7](https://australian-multibeam-guidelines.github.io/data-release) and [4.6](https://australian-multibeam-guidelines.github.io/acquisition#46-mandatory-notifications).
