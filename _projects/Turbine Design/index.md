---
layout: post
title: Fluids Research
description:  This section details my work in the two fluids labs I worked in during college. In the Multiphase and Multiscale lab, I experimented on micro-scale fluids to validate analytical capillary bridge models. I built and programmed a PID-controlled humidity chamber to prevent any evaporation during the testing process. In the Fluid Energy Science Lab, I designed, 3D printed, and tested a scale wind turbine using XFOIL to test optimal rotor theory. I later experimented on airborne wind turbines by taking wind tunnel wake measurements and validating entrainment theory models. 
skills: 
- Solidworks
- Fluid Mechanics
- Computational Fluid Dynamics
- Experimental Process
- Matlab
- Data Interpretation
- Circuit Design
main-image: /SreeramPaper.jpg

---

## Capillary Bridges - Microscale Research (Co-Author)
I used high-speed cameras to capture videos of capillary bridges suspended between slowly separating spheres. By post-processing the image with Python, I was able to measure the specific volume for every frame and compare it to a continuous measurement of the force between particles. This work is being published as Sreeram Rajesh's PhD dissertation on axial forces in liquid bridges. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/SreeramBridgeImage.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/SreeramBreakingForce.jpg" height="270" alt="Hub2">
</div>
My image of a quasi-static capillary bridge and the corresponding length of bridge before rupture 
<br>

To prevent instant evaporation at such low volumes, I built and programmed a PID-controlled humidity chamber to maintain the fluid volume while preventing condensation. To allow for actuation of the force sensor setup, the humidity chamber had to be easily disassembleable and not impede the motion of the linear track.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/SreeramTestingSetup.jpg" height="270" alt="Hub1">
</div>
Image of the testing setup, including humidity chamber

---

## Aerial Wind Energy - Entrainment Research (Co-Author)
I assisted in research confirming an annular wake model for airborne wind turbines, closely following the entrainment theory for wind turbines by Dr. Luzzatto-Fegiz (pictured above). Experimental measurements were taken in the UC Santa Barbara wind tunnel by suspending porous discs and measuring localized flow velocity at various distances downstream of the discs. The results of these experiments are being published as part of the PhD dissertation of Sam Kaufman-Martin at UCSB. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/WindTunnelExperimentalSetup.png" height="270" alt="Hub1">
  <img src="/imagesreal/WindTunnelResultsSD.jpg" height="270" alt="Hub2">
</div>
Wind tunnel testing apparatus and comparison of measured/aanalytical annular wake development
<br>

---

## Horizontal Axis Wind Turbine Design - Project
I used computational fluid dynamics (CFD) to design an optimize a scale wind turbine as part of a green energy project during college. To design the turbine I chose airfoil an existing airfoil (S8038) for its high Cl/Cd at low Re. I then iterated through Reynolds numbers and angles of attack using XFOIL to optimize the chord length across the blade and ensure structural integrity at characteristic operating speeds.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>
My functions of chord length and force calculations over the length of the blade

## Turbine Testing
I then modeled the turbine using Solidworks and printed it in SLS. It was tested using a small-scale wind tunnel and PMDC motor, where the turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performance calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/TunnelTesting.PNG" height="250" alt="Hub1">
</div>
Testing wind turbine with a wind generator and hot wire anemometer

---
