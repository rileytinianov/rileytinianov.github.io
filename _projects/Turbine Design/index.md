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
main-image: /FullTurbine.jpg

---

## Turbine Design 
I chose airfoil S8038 for its high Cl/Cd at low Re. By writing a program to iterate through Reynolds numbers and angles of attack, I was able to optimize the chord length across the blade. This blade was modeled in Solidworks and printed with SLS. The root bending moment was found across the blade to ensure it would not fail. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>


## Turbine Testing
The turbine was tested using a small-scale wind tunnel and PMDC motor. The turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performances calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/TunnelTesting.PNG" height="280" alt="Hub1">
</div>
---

## Entrainment Research
I assisted in research confirming an annular wake model for airborne wind turbines, closely following the entrainment theory for wind turbines by Dr. Luzzatto-Fegiz (pictured above). These experiments used porous disc to generate wakes representing the area swept by the turbine blades. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/Scanned.jpeg" height="270" alt="Hub1">
  <img src="/imagesreal/Stringing.jpg" height="270" alt="Hub2">
</div>

<br>

The air pressure was measured at various distances beyond the disc to find the affected velocity across the wake profile. 
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/AL10v1.png" height="400" alt="Hub1">
</div>

---
