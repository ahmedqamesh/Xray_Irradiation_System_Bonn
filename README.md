# Characterization of the X-ray Irradiation System @ Bonn
This page contains information and timetable of the X-ray irradiation system in Bonn Uni Physics department, SILAB group. This facility is located at Bonn university. It is accessible, upon request, to all users from the HEP community.
## Main Characteristics and Setup
The available x-ray tube uses a high voltage to accelerate electrons released by thermoionic effect in the electric field set by the operational voltage of the machine. The tube can be operated in a voltage range of **2 kV** to **60 kV** and continuously powered at **3 kW**. The characteristics of the tube are summarized in Tab 4.1.<p align="center"><img src="https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/blob/master/images/tablexray.png" width = 600 title=""></p>The tube parameters are adjustable using a graphical user interface. The tube itself is installed at the top of a **110 cm× 70 cm × 103 cm** cabinet with lead-glass front window so that all measurements are performed inside this radiation safe housing (see Fig. 4.1(a)).<p align="center"><img src="https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/blob/master/images/tablexraycabinet.png" width = 700 title=""></p>.
The system has been assembled to radiation test silicon integrated circuits for Total Ionizing Dose (TID) effects at different temperatures. Temperatures approaching 0 degrees or below require a controlled dry atmoshpere using liquid nitrogen inside the irradiation cabinet.
## GEANT4 Simulation
A measurement of the X-ray spectrum is very crucial, since the X-ray distributions influence the penetration of the X-rays through the target and so the absorbed radiation dose received. An accurate measurement of the X-ray spectrum is complex and time consuming because of the high count rates of the beam. A simulation in this case is a more convenient way to get the spectrum. For that purpose **GEANT4** simulation (Version 4.10.p01 compiled with CLHEP 2.1.3.1 libraries) toolkit has been
used to simulate the X-ray spectrum produced by the tube and study the effect of tube potential and
filtration on the beam intensity.
### [Generation of X-ray Spectra]()
### [Spectrum Filtration]()

## System Characterization
The essential information required for the characterization of an X-ray system is the X-ray dose rate as a function of tube current, tube voltage, and distance from the source. The effects of various source filters are also of interest. The measure of radiation due to X-rays is commonly expressed in Roentgen unit. A Roentgen (R) is defined as the quantity of X- or gamma radiation that produces a charge of **2.58 x 10^-4** coulombs in one kilogram of dry air at 0^o C. In most applications, radiation effects in other materials (e.g., silicon) are of primary interest, and the energy deposited per unit mass is a more meaningful measure of dose. For example, a dose of 1 rad is defined as an energy deposition of **100 erg/g** of material. The official SI dose unit is the Gray, however the rad is still widely used where **1 Gy = 1 J/kg = 100 rad**.
### [1.Size and Shape of the X-ray Beam](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/1.Size-and-Shape-of-the-X-ray-Beam)
### [2.Determination of the Opening Angle](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/2.Determination-of-the-Opening-Angle)
### [3.Photodiodes Dosimetry Calibration](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/3.Photodiodes-Dosimetry-Calibration)
### [4.Measurement of the Absorbed Dose vs. Tube Current](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/4.Measurement-of-the-Absorbed-Dose-vs.-Tube-Current)
### [5.The Effect of the Tube Voltage](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/5.The-Effect-of-the-Tube-Voltage)

### [6.Measurement of the Absorbed Dose vs.Depth](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/6.-Measurement-of-the-Absorbed-Dose-vs.-Depth)

### [7.Homogeneity of the X ray Beam Spot](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/7.-Homogeneity-of-the-X-ray-Beam-Spot)
## Photo Gallery
A full view of the instrumentation installed in the room and related to the X-ray system can be found [here](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/wiki/Photo-Gallery). 
## Tools
### Tube Cooling: 
The temperature needed for the tube itself is supposed to be around 20C. 
### Cooling chiller:
The facility is equiped with a [JulaboFP50/HP](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/blob/master/docs/Manual_Julabo_FP50_HP.pdf) chiller for samples cooling in a temprature range up to -30^o.
## About the manufacurer
The manufacturer is [XRD Eigenmann GmbH](https://www.xrd-eigenmann.de/de/startseite).
Product : is a highly stabilized X-ray source (HV generator [ISO Debyeflex ID3003](https://github.com/ahmedqamesh/Xray_Irradiation_System_Bonn/blob/master/docs/Manual_ISO-DEBYEFLEX%203003_English.pdf), connecting cables, tube covers and tubes, control electronics and cooling units).

