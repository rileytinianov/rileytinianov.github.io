---
layout: post
title: Cause-and-Effect Vehicle
description:  I designed a Cause-and-Effect vehicle to be used by children with Cerebral Palsy in physical therapy settings. I led the design and manufacturing for the chassis, drivetrain, and electronic hardware. This was my senior Capstone project and won the Mech E Top Technical Achievement award. 
skills: 
- Solidworks
- Structural analysis
- GD&T
- System Integration
- PCB Design
- Soldering
- CNC
main-image: /therapistcontrols.jpg 
---

## Overview
For my year-long senior Capstone project, I led a team of 4 engineers in designing and manufacturing a safe and accessible device to be used in therapy sessions for children with Cerebral Palsy. The device was able to seat children aged 2-7 and respond to button presses or joystick inputs to move. The device could also be operated by the physical therapist to ensure user safety and tune parameters. 

{% include gallery2.html images="imagesreal/CapstoneWithShell.jpg" height="300" %} 
![Test Image](/imagesreal/CapstoneWithShell.jpg)
![Test Image](/imagesreal/Hub1.png)
<img src="/imagesreal/Hub1.png" height="100" alt="Hub1">


## User Control
Due to the nature of Cerebral Palsy, the device had 5 independent nodes for control, each of which could support four buttons to control all mdodes of movement for the device. These nodes were spaced throughout the vehicle to allow for actuation using any limb, or by head movement if the patient struggled with limb control. The user moved the device by either pressing and holding or simply pressing the buttons, depending on their ability. 

{% include image-gallery.html images="/imagesreal/Hub1.png, /imagesreal/Hub2.png" height="100" %} 


## Therapist Control
The device could be controlled through a 2-axis potentiometer joystick by the therapist controller, which would immediately cancel user inputs. The therapist controller also had speed and duration knobs, which would control the speed of movement or the length of time movement persisted after the button was pressed. An emergency stop button cut power off to the motor drivers and engaged the drum brakes. The therapist also had access to a radio-controlled remote stop button. 

{% include image-gallery.html images="/imagesreal/PTController.png, /imagesreal/RemoteStop.png" height="300" %} 
Physical Therapist controller and remote stop


## PCB
I designed and soldered a double-sided PCB to interface directly with the Arduino Mega used to control the device. This PCB was made overseas due to our in-house machines not being suitable for double-sided boards.

{% include image-gallery.html images="/imagesreal/AssembledPCB.png, /imagesreal/PCBSLD.png" height="300" %} 
Assembled PCB and diagram

## Machining 
All metal components (chassis, motor mounts, supporting bars, PT controller) were designed with GD&T standards and machined in-house, either by waterjet or CNC machine. FEA simulations were performed on all load-bearing components to allow for a sufficient factor of safety. 

{% include image-gallery.html images="/imagesreal/WaterjetResults.jpg, /imagesreal/GDandT.png, /imagesreal/ExplodedPT.png" height="300" %} 

## Wiring
In an effort to keep wiring out of sight and safe, electronic elements were controlled using M12 6 position cables, which could be easily removed and adjusted without tools. A rechargable e-bike battery served as the power supply, which could be slid off a fixed mount for recharging. 

{% include image-gallery.html images="/imagesreal/Battery1.jpg, /imagesreal/MotorDriver1.jpg" height="300" %} 
