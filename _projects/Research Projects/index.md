---
layout: post
title: Multiphysics Simulations
description: I've worked with (primarily) COMSOL to simulate fluid/structural/thermal interactions, either for industrial applications and design improvements or purely to hone my skills in matching numerical modeling with analytical/experimental results. I show snippets of several of my recent projects here, and would be happy to give more complete techinical reports of each upon request.

skills: 
- COMSOL
- Coupled Simulations
- Meshing
- Result Interpretation
- Analytical Confirmation
main-image: /SolarField2.jpg

---

## Cleansheet Furnace Design
I modeled a green-energy refractory furnace as part of my application material for a local company in COMSOL. Working from the company patent and using company-reported energy metrics I found online, I was able to simulate the furnace's total thermal storage capacity and potential for electrical generation. I also found the steady-state radial temperature distribution to later measure internal stresses in the insulation.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/BraytonCycle_Real.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/RadialTempDistribution_Real.jpg" height="270" alt="Hub2">
</div>
3D plot of the furnace's energy efficiency using my Brayton Cycle analysis and the steady-state temperature distribution in COMSOL
<br>

I ran a series of transient studies to measure the lifecycle of the furnace with the insulation design described in the patent. I quickly found that the stress experienced during the heating/cooling cycle was much higher than allowable material values, and that the temperature at the furnace's surface was too hot to comfortably work around during operation. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/TooMuchStress.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/TempDistrib1.jpg" height="270" alt="Hub1">  
</div>
COMSOL results showing the furnace stress distribution and transient temperature during operation and cooling

---

## Boundary Layer Development in Orchards
I assisted in research confirming an annular wake model for airborne wind turbines, closely following the entrainment theory for wind turbines by Dr. Luzzatto-Fegiz (pictured above). Experimental measurements were taken in the UC Santa Barbara wind tunnel by suspending porous discs and measuring localized flow velocity at various distances downstream of the discs. The results of these experiments are being published as part of the PhD dissertation of Sam Kaufman-Martin at UCSB. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/WindTunnelExperimentalSetup.png" height="270" alt="Hub1">
  <img src="/imagesreal/WindTunnelResultsSD.jpg" height="270" alt="Hub2">
</div>
Wind tunnel testing apparatus and comparison of measured/analytical annular wake development in Matlab
<br>

---

## Lava Flow Rheology
I used computational fluid dynamics (CFD) to design an optimize a scale wind turbine as part of a green energy project during college. To design the turbine I chose airfoil an existing airfoil (S8038) for its high Cl/Cd at low Re. I then iterated through Reynolds numbers and angles of attack using XFOIL to optimize the chord length across the blade and ensure structural integrity at characteristic operating speeds.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>
My functions of chord length and force calculations over the length of the blade

---

## Gravity Current Leveling
I then modeled the turbine using Solidworks and printed it in SLS. It was tested using a small-scale wind tunnel and PMDC motor, where the turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performance calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/TunnelTesting.PNG" height="250" alt="Hub1">
</div>
Testing wind turbine with a wind generator and hot wire anemometer

---

## Transient Ice Sheet Growth
I then modeled the turbine using Solidworks and printed it in SLS. It was tested using a small-scale wind tunnel and PMDC motor, where the turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performance calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/TunnelTesting.PNG" height="250" alt="Hub1">
</div>
Testing wind turbine with a wind generator and hot wire anemometer

---

## Wave Evolution in Lake
I then modeled the turbine using Solidworks and printed it in SLS. It was tested using a small-scale wind tunnel and PMDC motor, where the turbine's power generation could be deduced by spanning a resistor across the motor terminals and measuring the speed of rotation. The experimental results aligned with the theoretical performance calculations, although there were some optimal tip speed ratio discrepancies. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/printedturbine.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/TunnelTesting.PNG" height="250" alt="Hub1">
</div>
Testing wind turbine with a wind generator and hot wire anemometer
