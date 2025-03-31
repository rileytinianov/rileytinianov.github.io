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

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/CapstoneWithShell.jpg" height="300" alt="Hub1">
</div>

---

## User Control
Due to the nature of Cerebral Palsy, the device had 5 independent nodes for control, each of which could support four buttons to control all modes of movement for the device. These nodes were spaced throughout the vehicle to allow for actuation using any limb, or by head movement if the patient struggled with limb control. The user moved the device by either pressing and holding or simply pressing the buttons, depending on their ability. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Hub1.png" height="300" alt="Hub1">
  <img src="/imagesreal/Hub2.png" height="300" alt="Hub2">
</div>

---

## Therapist Control
The device could be controlled through a 2-axis potentiometer joystick by the therapist controller, which would immediately cancel user inputs. The therapist controller also had speed and duration knobs, which would control the speed of movement or the length of time movement persisted after the button was pressed. An emergency stop button cut power off to the motor drivers and engaged the drum brakes. The therapist also had access to a radio-controlled remote stop button. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/PTController.png" height="300" alt="Hub1">
  <img src="/imagesreal/RemoteStopped.jpg" height="300" alt="Hub2">
</div>
Physical therapist controller and remote stop

---

## PCB
I designed and soldered a double-sided PCB to interface directly with the Arduino Mega used to control the device. This PCB was made overseas due to our in-house machines not being suitable for double-sided boards.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/AssembledPCB.png" height="250" alt="Hub1">
  <img src="/imagesreal/PCBSLD.png" height="250" alt="Hub2">
</div>
Assembled PCB and diagram

---

## Machining 
All metal components (chassis, motor mounts, supporting bars, PT controller) were designed with GD&T standards and machined in-house, either by waterjet or CNC machine. FEA simulations were performed on all load-bearing components to allow for a sufficient factor of safety. 
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Waterjet.jpg" height="250" alt="Hub1">
  <img src="/imagesreal/GDandT.png" height="250" alt="Hub2">
  <img src="/imagesreal/ExplodedPT.png" height="250" alt="Hub3">
</div>
Waterjet chassis, CAD tolerencing for waterejetting, and exploded PT controller drawing
---

## Wiring
In an effort to keep wiring out of sight and safe, electronic elements were controlled using M12 6 position cables, which could be easily removed and adjusted without tools. A rechargeable e-bike battery served as the power supply, which could be slid off a fixed mount for recharging. 
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Battery1.jpg" height="230" alt="Hub1">
  <img src="/imagesreal/MotorDriver1.jpg" height="230" alt="Hub2">
</div>
Integrated e-bike battery and motor controller box
---
