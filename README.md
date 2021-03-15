# lucidgloves-firmware
This repo contains the arduino firmware as well as the STL files for Prototype 3 of the LucidVR glove prototype. This is a finger tracking glove that allows you to use your hands in VR. Follow along with Lucas_VRTech's developments on his Tiktok page:
https://www.tiktok.com/@lucas_vrtech

# Firmware
Use the lucidgloves.ino file in the firmware folder and flash it onto an arduino nano (one for each hand).

# Hardware
STL files for 3D printing are located in the hardware folder. 

The assembly for each hand is as follows:
* Spool (5x)
* Tensioner (5x)
* Cover (5x)
* Holder (5x)
* GuideRing (2x per finger, 1x for thumb)
* EndCap (1x per finger, can be substituted for smaller guide ring) 

Disclaimer: You WILL need to print multiple sizes of the EndCap and GuideRing to fit the size of your fingers. Resize these in your slicer. Alternatively, you could print them in TPU for more flexible sizing. I reccomend resizing the EndCaps non-uniformally to squish them down to fit the oval shape of your fingers, this way they don't rotate around.

Required parts for each hand: (Please wait on ordering parts as I will be releasing a parts list soon)
1. WL b10k ohm Potentiometer (5x)
   - You will also need the nuts that are included with the potentiometers.
3. Arduino (Nano)
   - Will eventually be switching to ESP32 development boards for BTLE/Wifi
4. Wiring/Connectors/Breadboards as needed.
    - I recommend crimping/using JST connectors, 5 pin JST-XH 2.54mm fit great on the potentiometers.
5. Cheap retractable badge reels (for the rotary springs)
6. Glove material of your choice.
   - Recommended: Nylon Inspection Gloves (more flexy), Cycling/Golf gloves (stronger, easier to put on)
7. Something to mount the controller/tracker on your hand
   - Elastic works well for oculus controllers, I will be making some 3d printed mounts eventually

More information will be available on the LucidVR site very soon.
Will be releasing video tutorials on how to assemble and setup the gloves.

# Driver
This project uses the open source OpenVR driver created by LucidVR and Danwillm:
https://github.com/LucidVR/lucidgloves-openvr
