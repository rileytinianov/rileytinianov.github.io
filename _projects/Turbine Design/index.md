---
layout: post
title: Turbine Design and Analysis
description:  I designed, 3D printed, and tested a scale wind turbine using XFOIL to test optimal rotor theory. I later experimented on airborne wind turbines by taking wind tunnel wake measurements and validating entrainment theory models.
skills: 
- Solidworks
- Fluid Mechanics
- Experimental Process
- Matlab
- Data Interpretation
main-image: /therapistcontrols.jpg

---

## Turbine Design 
I chose airfoil S8038 for its high Cl/Cd at low Re. By writing a program to iterate through Reynolds numbers and angles of attack, I was able to optimize the chord length across the blade. This blade was modeled in Solidworks and printed with SLS. The root bending moment was found across the blade to ensure it would not fail. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/printedturbine.jpg" height="300" alt="Hub2">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>


## Turbine Testing
The turbine was tested using a small-scale wind tunnel and PMDC motor. The turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performances calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/TunnelTesting.png" height="300" alt="Hub1">
</div>
---

## Entrainment Research
I assisted in research 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/PTController.png" height="300" alt="Hub1">
  <img src="/imagesreal/RemoteStopped.jpg" height="300" alt="Hub2">
</div>
Physical Therapist controller and remote stop

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

---

## Wiring
In an effort to keep wiring out of sight and safe, electronic elements were controlled using M12 6 position cables, which could be easily removed and adjusted without tools. A rechargeable e-bike battery served as the power supply, which could be slid off a fixed mount for recharging. 
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Battery1.jpg" height="230" alt="Hub1">
  <img src="/imagesreal/MotorDriver1.jpg" height="230" alt="Hub2">
</div>

---

