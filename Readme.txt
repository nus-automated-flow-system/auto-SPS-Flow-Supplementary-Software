Includes:

SPS Flow System folder: subfolder containing Application exe and subfolder containing Installer exe
LabVIEW Source Code folder
Readme.txt
Test automation for  prexasertib synthesis  using SNAr as 5th step.txt




System requirements
==================================================
Software operating systems
Compatible with Windows 7, 8.1, and 10

Versions the software has been tested on:
Windows 10 Home
Windows 10 Pro

NI LabVIEW 2018 (32-bit) NI LabVIEW Runtime 2018 
NI-Serial Runtime 17.5 or higher
NI-VISA Runtime 18.0 or higher

LabVIEW license is necessary to view source code

Note: the program is made for the specified instruments. 
Missing instruments will result in a connection error. 


Required instrument models
===================================================
SF-10 Reagent pump
Manufacturer: Vapourtec Ltd

Asia Flow Chemistry Syringe Pump
Manufacturer: Syrris Ltd

Valco Dead-end Selector with Universal Actuator serial interface: RS-232
Manufacturer: VICI Valco Instruments Co. Inc

Hei-Connect Magnetic Stirrer
Manufacturer: Heidolph Instruments 


Application Installation guide
==================================================
1. Install the USB drivers for each instrument, before plugging in the USB cable.
   The USB interface will appear as a virtual COM port.

2. Install the SPS Flow System Automation program.

Go to the SPS Flow System Automation Installer subfolder
Double click the "setup.exe" file to start installation
Install to default directory
Accept licenses
Proceed through installer prompts. Note: it is not necessary to disable windows fast startup
Restart computer after installation
Go to either the installation directory or the SPS Flow System Automation Application subfolder
Double click the "SPS Flow System Automation.exe" application file


Typical downloading and install time: 10min



Instruction and Demo
==================================================
For instructions to run the software, refer to Supplementary Information, section S7.3

Demo test table included in the folder:
"Test automation for  prexasertib synthesis  using SNAr as 5th step.txt" 

After successful completion of the program, the message "No more entries left. The operation will now stop." will be displayed

Expected run time for demo: ~ 21 hr

If the required instruments are not connected properly, an error will occur with the reason:
"VISA:  (Hex 0xBFFF000E) The given session or object reference is invalid."

For pseudocode, refer to Supplementary Information Section S7.2.3



