---
layout: home
permalink: /mobilisation-calibration-validation
title: "3. Mobilisation, Calibration and Validation"
excerpt: "<br>"
image:
  feature: /banners/multibeam-banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

Mobilisation refers to the process of combining multiple equipment sets (echo sounder, positioning system, motion reference unit & sound velocity instrumentation) into a single functioning high precision and accurate system. Calibration refers to the measurement and removal of systematic errors in all installed sensors. For most installations, errors mainly consist of small offsets and rotations between system components. Validation refers to testing calibrated systems against known controls by conducting multiple observations in order to provide an analysis of the repeatability, precision and accuracy of an individual or combined system.

# 3.1 Overview
Mobilisation must be done with care since compromise to any part of the integrated equipment set will increase the risk of degrading the whole system and can result in no capacity to correct or post-process the problem. Calibration and validation are vital to assess the performance of the installed system against survey specifications, particularly TVU, TPU and datum control, as elaborated throughout this section. 

The mobilisation, calibration and validation process will vary between vessels. For example, a ‘vessel of opportunity’ commonly involves significantly more planning and setup time than permanently configured survey vessels. The steps below generalise the detailed processes outlined in the hardware and software manufacturer’s instructions for the deployed equipment. Specific information on some of the steps of the mobilisation, calibration and validation are included as a brief glossary in the following subsections. 

**Generalised steps for mobilising a vessel of opportunity:**
1. During the pre-survey planning phase, attempt to source previous mobilisation reports for the planned survey vessel and equipment (even if from another vessel). This information will assist in understanding any engineering requirements or complications, thus saving downtime during mobilisation. 
2. Ensure adequate resources are assigned for mobilisation of the swath acoustic system on the vessel of opportunity, which typically requires days (2-3 days), not hours.
3. Confirm the vessel reference frame to be used along with offsets and keep records and diagrams by either organising a survey of the vessel or re-use the results of a recent one. This establishes the spatial layout of equipment and sensors relative to each other.  The responsible seabed mapper should conduct QC on any offset report received from a third party or conducted by the team.
4. Make equipment structures as rigid as possible to ensure stable geometry. E.g. moon-pool, and/or over the side rigid mounts should return to exactly the same location when deployed.
5. Take care with the physical installation, particularly cable runs and joins, and account for vessel vibrations, vessel traffic, water ingress, power-stability (pure sine wave for inverters, earthing), etc. Consider under-keel and overhead clearances.
6. Minimise acoustic and vibration noise sources to acoustic sensors, IMU and electronics.
7. Check vessel sounder or engine vibration and noise over engine revolution range. Test a range of survey speeds for noise changes. Where possible check the swath systems performance at desired survey speed and sea state.
8. Check sky view of observed GNSS satellites in positioning system and minimise radio interference on GNSS antennas. Lost GNSS observations cannot be recovered.
9. Perform all manufacturer’s self-tests and calibrations (positioning system, swath sonar, sound velocity instruments) to ensure validity of entire system. This includes a patch test ([section 3.5](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#35-patch-test))
10. Record all sign conventions and calibrated geometries of installed sensors (screen captures and reports;[section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records)).
11. Backup system and parameter files on a separate location. This is also important for rolling back configurations when accidental, unknown system changes are made.
12. Preferably complete mobilisation and testing before leaving port for the survey area.
13. Check tidal observation equipment for connections to local tidal datum if required.
14. Double check all geodetic parameter settings in positioning and acquisition systems for consistency. Ensure no undesired/undocumented transformations are taking place.
15. Consider processing capability on the vessel for near real-time assessment of acquired data.
16. Confirm on-board vessel storage has enough capacity to capture all required raw data, including backup strategy.
17. Discuss planned survey lines with vessel master, survey ground sea-states, forecast weather and implication for survey plan. Communication strategies between MBES system operator and helm (including installing swath system helm display).
18. Describe the equipment and actions undertaken on the vessel before, during and after the survey to form part of a ‘mobilisation and calibration’ report to be submitted along with the data ([section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records)).

# 3.2 Dimensional control
This is the process of establishing the spatial relationships of the mounted equipment locations on the vessel. This includes the physical vessel offsets ([section 3.2.1](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#321-physical-offset-survey)) and angular rotational offsets ([section 3.2.2](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#322-rotation-offset-survey)) of the installed equipment, and the integration of them into the complete swath acoustic system. All recommended calibration and alignment procedures specified in the manufacturer’s equipment manuals should be carried out. These measurements are validated and refined during the patch test process.

# _3.2.1 Physical offset survey_
Establish the physical offsets of the installed equipment to permanent locations or marks on the vessel (Figure 5). This is achieved by adding equipment specific offsets to the previously carried out static (slipped) vessel system offsets survey or via surveyed measurements to the installed equipment. Preferably offsets should be known with centimetre level uncertainties, or better, to establish spatial relationships between soundings and external earth reference frames (WGS84, ITRF) via the GNSS equipment installed on the vessel.

It is important to note that the systematic errors and uncertainties associated with this control will feed directly into the overall quality of the data and will greatly increase with water depth. Acquiring accurate data ensures the long term benefits that accompany the “collect once, use many times” mantra. For more information, refer to Hughes-Clarke (2003).

![alt_text](images/figures/image5.jpg "image_tooltip")

_Figure 5 Diagram of dimensional control for MBES system (After Gardner et al., 2002)_

# _3.2.2 Rotation offset survey_
A rotation offset survey checks the alignment of individual equipment relative to the vessel’s reference frame. 

Establish all known rotations (angular offsets between the vessel and the reference frames of the installed equipment) for each equipment set. The offsets between rotational frame conventions (if any) of each equipment set should be accounted for as part of this process and recorded in the mobilisation, calibration and validation report ([section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records)). If equipment rotations (physical measurement) are known separately to calibrated rotations (patch test) and applied as such in the acquisition software, these details should also be included in the report. 

Rotation offset survey is normally associated with permanently-installed systems.

# 3.3 Horizontal positioning 
It is recommended to use a tightly coupled GNSS-Inertial system consisting of dual GNSS antennae and IMU integrated system that is tested. The GNSS-Inertial system has to be calibrated and validated prior to the commencement of the survey as this is critical to detect and correct setup errors, and estimate uncertainties. This process involves both static and dynamic validation if possible:

Static validation of GNSS positioning equipment involves verifying the performance of the system against a known reference position. This should be preferably done using land survey methods, however should a known reference point not exist near the point of mobilisation, points may be established and should be in accordance with ICSM (2014a-c). 

Dynamic validation or confidence checks involves carrying out dynamic comparisons between positioning systems (where more than one system is mobilised). These dynamic calibrations should be performed regularly and whenever any component or changes to the vessel positioning systems or setup are made.

Validations may include:
*   alongside checks using baseline and offset measurements to vessel datum points while logging on the acquisition system.
*   check of independent positioning system mounted on vessel with known offset to transducer and on-board primary positioning system. Vessel records of all systems while conducting a box, then perform comparative analysis between logged system data and the independent positioning system. The least preferred method is to conduct this while static, but this may be the only operational option.

Setting up positioning systems to transmit data to the swath system topside at a frequency of 1 Hz is adequate for most scenarios.

# 3.4 Vertical positioning 
# _3.4.1 Depth validation_
Depth validation should be done once the patch test ([section 3.5](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#35-patch-test)) has been performed. The system should be used to run a series of parallel and perpendicular sounding lines over a reference bottom surface where the depths have been previously determined and verified with an independent system of known accuracy. 

If none of these comparative methods are available, then a “bar check” can be undertaken understanding that the results will not be as accurate as the precedent methods. The results obtained by any of the methods should compare favourably and be within the accuracy requirements of the survey.

Prior to sailing, a lead line observation may also be conducted.

# _3.4.2 Settlement and squat_
Settlement occurs once the vessel is in a constant transit and is a vertical displacement which is constant at a given speed through water.  Squat is a relationship between depth of water and speed through water.  

All vessels are subject to settlement and squat, and measurements of these parameters should be made wherever practically possible by the most appropriate validation method. Ideally tests should be performed at various vessel speeds over a flat bottom using RTK GNSS or orthometric levelling heights at the transducer location. The heights should be measured at rest and then in increments of vessel speed with RPM noted, and then used to derive an appropriate squat/settlement table. A squat table is not necessary when using ellipsoidal reduction methods, however, should you need to revert to sounding reduction by tide, a table is best practice.

# _3.4.3 Vessel draft_
Vessel draft may be difficult to measure. However, it is possible to approximate distance from arbitrary reference points to the waterline before and after a survey as this is likely to change with fuel consumption. For validation, the vessel draft should be derived using quantitative measurement methods as for [section 3.4.2](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#342-settlement-and-squat) (Settlement and squat).

# _3.4.4 Sound velocity_
To ensure proper calibrated sound velocity reading, at least one probe (SVS or SVP) needs to be independently calibrated. Use a comparative method to validate other sensors (SVS at head and SVP). Assess speed of sound at the swath sonar head against SVP at same depth below surface. Where possible, compare SVP readings with external sensors (e.g. derived sound velocity from CTD).

# _3.4.5 Tidal station_
For shallow inshore work (&lt;30m), water level tidal observations, including local environmental effects, should be conducted for a minimum period of 35 days. If this is not possible, predictions based on tidal constituents may be used and in this instance tidal stations should be installed and calibrated as directed by ICSM (2004).

# 3.5 Patch test
The patch test confirms timing and alignment of the MBES sensor, vessel and IMU reference frames. It is essential to execute the standard patch test method as appropriate for sensor type (single or dual- head) and vessel ([Appendix F](https://australian-multibeam-guidelines.github.io/appendices#appendix-f--patch-test)). A patch test should be conducted at the beginning of the field season or whenever a piece of equipment is replaced or repaired and has to be undertaken once the calibration for the GNSS inertial system is complete ([section 3.3](https://australian-multibeam-guidelines.github.io/mobilisation-calibration-validation#33-horizontal-positioning)). The results of the patch test should be reported in the Mobilisation and Calibration Report ([Appendix H](https://australian-multibeam-guidelines.github.io/appendices#appendix-h--records-templates)).

# 3.6 Seafloor backscatter calibration
Lamarche and Lurton (2017) provide a comprehensive review of seafloor backscatter from data acquisition to processing. Calibrated seafloor backscatter is essential to enable comparison of data acquired by various systems. There are two types of calibrated backscatter: absolute and relative backscatter.

Calibration is executed through the use of reference areas of known seabed types (preferably flat, smooth, and geologically and acoustically homogeneous areas). Use roll lines of the patch test (no need to rerun for backscatter) and list overlap (for backscatter quality survey). For systems with multiple transmitting sectors it is recommended that the average backscatter level be consistent across all sectors and for different modes. 

It is also recommended that sediment samples and/or imagery samples be taken from the area to ground truth and calibrate backscatter data. As part of a sea-acceptance test practice, an overall calibration must be performed once the sonar system has been installed on the vessel. This involves both the customer’s technical team and operators.

# 3.7 Water column backscatter calibration
Calibration of water column data is desirable into the future and is best acquired if available on system. The same procedure for seabed backscatter calibration should be applicable for the water column backscatter calibration. While it is not practical to use the sphere calibration technique, inter-calibration with a calibrated fisheries single-beam echo sounder through the use of reference areas (Demer et al. 2015; Foote et al. 1987) may be employed. This at least provides assurance of self-consistency.

# 3.8 Built-in systems test
Built-in tests, such as built-in systems test (BIST) or built-in test environment (BITE) are a test of sonar head communication with software controllers and are useful for the validation of communication between systems. They becomes integral when troubleshooting and should be logged. It is recommended that, at a minimum, a BIST be done at the start and end of the mapping. The results should be reported in a Mobilisation and Calibration Report ([section 6.1](https://australian-multibeam-guidelines.github.io/reports#61-mobilisation-calibration-and-validation-records)).

# 3.9 Final acceptance test
A final check should be performed to ensure that all the equipment is working properly and that the logging systems are operating correctly. Care should be taken to ensure depth, position and if necessary water level values are being logged correctly. The positioning system should be checked for operation and periodically throughout the survey.