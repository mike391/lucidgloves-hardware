# lucidgloves-firmware
This repo contains the arduino firmware as well as the STL files for Prototype 3 of the LucidVR glove prototype. This is a finger tracking glove that allows you to use your hands in VR. Follow along with Lucas_VRTech's developments on his Tiktok page:
https://www.tiktok.com/@lucas_vrtech

# Firmware
Use the lucidgloves.ino file in the firmware folder and flash it onto an arduino nano (one for each hand).

# Hardware
STL files for 3D printing are located in the hardware folder. 
*Prototype 3.1 models are currently experimental*

The assembly **for each hand** is as follows:
* Spool (5x)
* Tensioner (5x)
* Cover (5x)
* Holder (5x)
* GuideRing(Will need to be resized) OR GuideNode(3.1) (2+ per finger, 1+ for thumb)

* EndCap (1x per finger, will need to be resized to fit) 

Guide for printing parts: [Printing guide](https://github.com/LucidVR/lucidgloves-hardware/wiki/Parts-Printing-Guide)

**Required parts for each hand: [Parts List](https://github.com/LucidVR/lucidgloves-hardware/wiki/Prototype-3-Parts-List)**  
Optional:  
* Joysticks for locomotion 
  - will be making a DIY treadmill eventually as well for those who would prefer that  
* Buttons (Most can be replaced with gestures)

More information will be available on the [LucidVR site](http://lucidvrtech.com/) very soon.  
Will be releasing video tutorials on how to assemble and setup the gloves.

# Driver
This project uses the open source OpenVR driver created by LucidVR and Danwillm:
https://github.com/LucidVR/lucidgloves-openvr
