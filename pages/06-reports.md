---
layout: home
permalink: /reports
title: "6. Reports"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

In order to ensure consistent documentation of all aspects of survey planning, mobilisation, calibration and acquisition, all information (reports and logs) should be recorded throughout the process. At a minimum, metadata ([section 2.3.1.3](https://australian-multibeam-guidelines.github.io/pre-survey-planning#231-data-type-formats-and-metadata)), records for Mobilisation, Calibration and Validation ([section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records)), and the records proposed in [section 6.2](https://australian-multibeam-guidelines.github.io/reports#62-record-keeping) are recommended. The proposed templates for these reporting requirements can all be found in [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates).

# 6.1 Mobilisation, calibration and validation records
Methodology and results of the mobilisation and calibration should be outlined in the mobilisation and calibration report, and the associated records created using templates provided in [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates).

# _6.1.1 Logs_
Mobilisation and calibration logs should include:
*   tests survey lines, including patch test and final acceptance test
*   SVP deployments (filename, time, lat, long, depth, SV sonar head reading (used for comparison)
*   squat and draft tables

# _6.1.2 Report_
Mobilisation and calibration report should document the integrated survey system, methodology, raw results and processed results, i.e. once the calibration is accepted. At a minimum, it is recommended to include the following (modified from AHO, 2018) and if needed, [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates) provides a template:

**Report Heading:**
*   seabed mapping survey title and associated reference number
*   mapped by (agency/company/etc. and Seabed mapping lead)
*   dates of mapping
*   mobilisation, calibration and validation report
*   version
*   date of the report

**Introduction:** includes an overview of the procedures conducted for the installation and calibration of equipment that comprise the seabed mapping system (SMS).


*   Background and outline of events: a narrative giving an overview and timeline for the set-to-work of the survey platform(s).
*   Platforms: a description of, and justification for, the survey platforms chosen to undertake the survey.
*   Geodetic controls: geodetic parameters for the control survey, station diagrams and descriptions outlining the geodetic control utilised for the survey. 

**Equipment:** summary of equipment that forms the SMS as installed on the survey platforms, including all relevant offsets and calibrations.


*   Hardware: summary of the hardware relating to data acquisition including manufacturer, model and serial number is to be tabulated.
*   Software: summary of the acquisition and processing software, including version numbers is to be tabulated.
*   Sensor mounting systems: a description of the mounting system utilised for data acquisition is to be provided, e.g. pole mount, gondola, moon pool etc.
*   Sensor offsets: the measurement method and results for the dimension control that determine the relationship between the measurement sensors and the platform CRP are to be provided. Sensor offsets may be annexed to the report. 
*   MRU heading checks.
*   Built-in test results (e.g., BIST, BITE).

**Underway calibration:** outline the checks and calibrations of the platform when underway. These may include:

*   acoustic sensor bar checks
*   draft, settlement and squat
*   primary and secondary positioning
*   patch test; the method undertaken, and results of the patch test for the pitch, roll and heading bias are to be calculated and rendered
*   reference surface (if performed): difference statistics between manoeuvring lines and the reference surface are to include; beam number; mean, maximum and minimum differences and standard deviation
*   target detection (if performed): the ability of the SMS to meet the target detection criteria of the specified order are to be demonstrated
*   acoustic interference check (if performed): results of the pre-survey acoustic interference check are to be rendered

# 6.2 Record Keeping
This section includes logs that should be used during acquisition of data as well as information required in the Report of Survey provided at the end of the survey. This section also points to legal notification requirements in regards to Dangers found ([section 4.6.1](https://australian-multibeam-guidelines.github.io/acquisition#461-dangers-found--hydrographic-notes)) and Underwater Cultural Heritage ([section 4.6.2](https://australian-multibeam-guidelines.github.io/acquisition#462-underwater-cultural-heritage-notification)). Templates of the reports and logs can be found in [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates) for a summary of minimum requirements and in the IHO M-13 Manual on Hydrographic Surveying for a comprehensive report.

# _6.2.1 Logs_
Survey logs should include:

*   relevant information on survey lines, including data types recorded and daily events. Minimum parameter requirements found in [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates).
*   system parameters relevant to backscatter data acquisition include:
    *   environmental parameters controlling sound speed and absorption within the water column
    *   weather and sea conditions
    *   backscatter intensity
    *   source level
    *   pulse length
    *   transmit beam patterns
    *   receive beam patterns
    *   receiver time varying gain functions
    *   path length attenuation characteristics (spherical spreading and absorption coefficient)
    *   seabed grazing angle
*   SVP deployments (filename, time, lat, long, depth, SV sonar head reading (used for comparison)
*   log for additional data collected, such as seabed samples (section 2.6)

# _6.2.2 Report of Survey_
The Report of Survey (ROS) should give a comprehensive account of how the seabed mapping survey was carried out, the results achieved, and any difficulties encountered. A template can be found in [Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates), but at a minimum, it is recommended to include the following (modified from AHO, 2018):

**Report heading:**

*   seabed mapping survey title and associated reference number
*   mapped by (agency/company/etc. and seabed mapping lead)
*   dates of mapping
*   report of seabed mapping
*   version
*   date of the report

**Introduction:**

*   dates: give start and end dates with activities that took place during the survey, especially where swath acoustic data was acquired while executing other activity (transit and sampling)
*   map: give general map of where the data was collected, including coordinates of coverage
*   setting conditions: general statement on weather and sea conditions as these are essential to understand data quality. Provide also information on oceanographic conditions which explain SVP frequency
*   completion: comment on completeness of the survey, including opinion in regards to coverage and line spacing, and MBES data type recorded

**Standards:**

  *   local datum epoch and transformation parameters: provide a table with the relevant information that was used within the acquisition software. In addition, all software used on the survey must contain the correct datum parameters and this should be checked independently and evidenced here.
  *   horizontal and vertical accuracy: the following section confirms that the horizontal and vertical accuracy of soundings acquired during the _Survey Name_ seabed mapping survey are compliant/non-compliant with the (IHO/LINZ/Other) standard for position and depth accuracy 
  *   TPU:_ _comment on TPU in reporting relative to various industry standards and provide a Table (see example Table 5 from section 5.2) with a detailed analysis of the TPU estimates for the relevant depth bands mapped for the project, using _name of software_

**Seabed sampling:**

*   method: describe method used and problems with equipment or recovery of the samples, state sampling interval and any particular samples obtained from interesting features, state the number, plan for analysis and submission of samples

**Tides and sounding datum** (see section 13.4.1.9 in AHO, 2018)

**Wrecks and danger found:**

*   Provide a table with any notifications made in accordance with legislation ([section 4.6](https://australian-multibeam-guidelines.github.io/acquisition#46-mandatory-notifications))