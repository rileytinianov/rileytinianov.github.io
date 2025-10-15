---
layout: post
title: Fluids Research
description:  This section details my work in the two fluids labs I worked in during college. In the Fluid Energy Science Lab, I designed, 3D printed, and tested a scale wind turbine using XFOIL to test optimal rotor theory. I later experimented on airborne wind turbines by taking wind tunnel wake measurements and validating entrainment theory models. In the Multiphase and Multiscale lab, I experimented on micro-scale fluids to validate analytical capillary bridge models. I built and programmed a PID-controlled humidity chamber to prevent any evaporation during the testing process.
skills: 
- Solidworks
- Fluid Mechanics
- Experimental Process
- Matlab
- Data Interpretation
- Circuit Design
main-image: /FullTurbine.jpg

---

## Turbine Design 
I chose airfoil S8038 for its high Cl/Cd at low Re. By writing a program to iterate through Reynolds numbers and angles of attack, I was able to optimize the chord length across the blade. This blade was modeled in Solidworks and printed with SLS. The root bending moment was found across the blade to ensure it would not fail. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>
Printed turbine and plots showing chord length and force experienced

## Turbine Testing
The turbine was tested using a small-scale wind tunnel and PMDC motor. The turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performance calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/TunnelTesting.PNG" height="280" alt="Hub1">
</div>
Testing wind turbine 

---

## Entrainment Research
I assisted in research confirming an annular wake model for airborne wind turbines, closely following the entrainment theory for wind turbines by Dr. Luzzatto-Fegiz (pictured above). Experimental measurements were taken in the UC Santa Barbara wind tunnel by suspending porous discs and measuring localized flow velocity at various distances downstream of the discs. The results of these experiments are being published as part of the PhD dissertation of Sam Kaufman-Martin at UCSB. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/WindTunnelExperimentalSetup.png" height="270" alt="Hub1">
  <img src="/imagesreal/WindTunnelResultsSD.jpg" height="270" alt="Hub2">
</div>
Wind tunnel testing apparatus and comparison of measured/aanalytical annular wake development
<br>

---

## Microscale Research
I used high-speed cameras to capture videos of capillary bridges suspended between slowly separating spheres. By post-processing the image with Python, I was able to measure the specific volume for every frame and compare it to a continuous measurement of the force between particles. To prevent instant evaporation at such low volumes, I built and programmed a PID-controlled humidity chamber to maintain the fluid volume while preventing condensation. This work is being published as Sreeram Rajesh's PhD dissertation on axial forces in liquid bridges.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Scanned.jpeg" height="270" alt="Hub1">
  <img src="/imagesreal/Stringing.jpg" height="270" alt="Hub2">
</div>
My image of a capillary bridge and corresponding force scale. 
<br>

To allow for actuation of the force sensor setup, the humidity chamber had to be easily disassembleable and not impede the motion of the linear track.
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/AL10v1.png" height="400" alt="Hub1">
</div>
Image of the testing setup, including humidity chamber.

---
