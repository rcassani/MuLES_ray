# MuLES (MuSAE Lab EEG Server)
## Windows and OS X development

Modification from Mac
<p align="center">
<img src="https://github.com/MuSAELab/MuLES/blob/master/images/MuLES_logo.png" width="400" align="middle">
</p>

## Introduction

MuSAE Lab EEG Server (MuLES) is an open source EEG acquisition and streaming server that aims at creating a standard interface for portable EEG headsets. It provides a minimalist graphical user interface (GUI) to allow quick and simple interfacing with different portable EEG consumer devices.

MuLES is a piece of software designed in LabVIEW, that aims at simplifying the use of common commercial electroencephalography (EEG) devices. It allows easy EEG data acquisition and recording of EEG data as well as data streaming to other software (clients) programmed in any language that supports basic TCP/IP network socket programming. In this sense, it is not necessary for the user to delve into the available SDKs and APIs of the different devices. Moreover, the provided common interface allows complete interchangeability between the devices, making easier to create applications that work with different EEG headsets. The MuLES software is distributed as an installer for Windows 32 and 64bit versions. Future releases of MuLES will include different operative systems.

<p align="center">
<img src="https://github.com/MuSAELab/MuLES/blob/master/images/diagram.png" width="500" align="middle">
</p>

R. Cassani, H. Banville, and T. Falk, MuLES: An Open Source EEG Acquisition and Streaming Server for Quick and Simple Prototyping and Recording, 20th ACM conference on intelligent user interfaces, 2015. [Paper](http://musaelab.ca/pdfs/C90A.pdf) and [Poster](http://musaelab.ca/pdfs/C90B.pdf).



## Installation

The installation processes for MuLES is simple
- Download the newest MuLES installer (```MuLES_installer.zip```) from [https://github.com/MuSAELab/MuLES/releases](https://github.com/MuSAELab/MuLES/releases)  
  This file contains the LabVIEW Run Time Engine installer, needed by MuLES
- Unzip the ```MuLES_installer.zip``` file and run ```setup.exe``` located in ```\MuLES_installer\```

## Test
- Run ```mules.exe```, a Desktop shortcut is created by the MuLES installer  
  Alternatively, MuLES executable is located in: </br>
```C:\Program Files (x86)\MuSAE_Lab\MuLES\``` for Windows 64bit  
 ```C:\Program Files\MuSAE_Lab\MuLES\```  for Windows 32bit

- Open the Simple Client Example for Matlab or Python (2 and 3): </br> (```C:\Program Files (x86)\MuSAE_Lab\MuLES\client_examples\matlab\example_simple_client.m```) </br> or </br> (```C:\Program Files (x86)\MuSAE_Lab\MuLES\client_examples\python\example_simple_client.py```) </br> respectively. </br> And follow the instructions in the scripts.
