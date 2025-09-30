# STASIS_Exposure_Hardware
This is the repository for the exposure hardware of the STASIS project.
The corresponding software can be found in this repository: https://github.com/sOrzada/STASIS_Control

by Stephan Orzada @ German Cancer Research Center (DKFZ) 

# Overview
The STASIS RF exposure system is an open-source hardware and software platform designed for implant testing under exposure to radiofrequency (RF) fields, such as those encountered in the environment of an MRI system. For this purpose, the target RF frequency is 128 MHz, corresponding to the resonant frequency of protons in a 3 Tesla magnetic field. The system is capable of transmitting on eight independent RF channels, enabling parallel transmission.
To ensure the design is easily accessible to potential users, all design files and software are publicly available and can be accessed via the following repositories:
https://github.com/sOrzada/STASIS_Exposure_Hardware
https://github.com/sOrzada/STASIS_Control
All hardware components of the exposure system are licensed under the CERN-OHL-W while the software is licensed under a GNU GPL v3. In addition the project has been submitted to the conformity assessment body of the Open Source Imaging Initiative e.V. (https://www.opensourceimaging.org) to assess its open source status according to DIN SPEC 3105.  
To further improve accessibility, standard components with long production lifespans were selected wherever possible. For example, standard logic components were used instead of specialised microcontrollers or FPGAs.

