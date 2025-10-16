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
main-image: /SolarField3.jpg

---

## Cleansheet Furnace Design
I modeled a green-energy refractory furnace in COMSOL as part of my application material for a local sustainable heating company. Working from the company patent and using company-reported energy metrics I found online, I was able to simulate the furnace's total thermal storage capacity and potential for electrical generation. I also found the steady-state radial temperature distribution to later measure internal stresses in the insulation.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/BraytonCycle_Real.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/RadialTempDistribution_Real.jpg" height="270" alt="Hub2">
</div>
3D plot of the furnace's energy efficiency using my Brayton Cycle analysis and the steady-state temperature distribution in COMSOL
<br>

I ran a series of transient studies to measure the lifecycle of the furnace with the insulation design described in the patent. I found that the stress experienced during the heating/cooling cycle was much higher than allowable material values, and that the temperature at the furnace's surface was too hot to comfortably work around during operation. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/TooMuchStress.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/TempDistrib1.jpg" height="270" alt="Hub1">  
</div>
COMSOL results showing the furnace stress distribution and transient temperature during operation and cooling
<br>

Finially, I redesigned the furnace with a different insulation order to drastically reduce the stress experienced and lower the outer surface temperature. The results can be seen below. 
<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ImprovedStress.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/TemperatureImproved.jpg" height="270" alt="Hub1">  
</div>

---

## Boundary Layer Development in Orchards
I explored the boundary layer development and wind speed reduction in agrivoltaic orchards to confirm approximate models found during literature review. This project studied fluid-structure interaction and required a detailed, custom mesh. Trellised apple trees were modeled as uniform rods and the geometry was reflected multiple times to give insights into an orchard at scale. The results from this study helped confirm our agrivoltaic wind speed scaling. 


<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/MeshStructure.jpg" height="270" alt="Hub1">
  <img src="/imagesreal/SurfacePressure.jpg" height="270" alt="Hub2">
</div>
Close-up mesh of the boundary layer control volume and surface pressure of the system
<br>

---

## Wave Evolution in Lake
I modeled the 2-dimensional wave dynamics of a lake with an initial Gaussian disturbance to solve Feynman's inverse wave problem. I showed agreement with the shallow wave approximation in 2D and 1D to confirm my mesh resolution and boundary conditions before optimizing the PDE to best match outer boundary hydrograph data. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ShallowWaveConfirmation.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/OptimizationResults.jpg" height="250" alt="Hub1">
</div>
These images show agreement between the shallow wave approximation and numerical solution and agreement between experimental hydrograph data and my optimized PDE

---

## Transient Ice Sheet Growth
I confirmed transient ice growth analytical models proposed by Huybrechts and Payne for large-scale ice sheets. I was able to show perfect agreement in the ice profiles and mass flux throughout the sheet in both the 2D and 3D case. I also introduced and solved the growth profiles with a periodic condition to simulate environmental patterns over a 500 year cycle. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ComsolContour.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/AnalyticalContour.jpg" height="250" alt="Hub1">
</div>
Comparison between my numerical solution and the analytical profile suggested by Huybrechts and Payne

---

## Gravity Current Leveling
I studied the transient leveling of free-surface peturbations for both the Newtonian and Bingham cases. This included a PDE-driven characterization from the small perturbation expansion formula being implemmented into COMSOL and a comparison between the  analytical and numemrical solutions for different fluid parameters. In the non-Newtonian case, I added a yield stress and plastic viscosity to study how the results developed differently. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/FreeSurfaceNewtonian.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/FreeSurfaceBingham.jpg" height="250" alt="Hub1">
</div>
Graphs of the fluid's free surface in both the Newtonian and Bingham case. Note that the Bingham rheology has a linear profile as it levels to minimize shear stress. 

---

## Lava Flow Rheology
I studied the rheology of high-viscosity lava flow in rectangular channels as presented by Tallarico and Dragoni. I used the Power Law profile for non-Newtonian viscosities to match my velocity profile to their analytical solution, for which I wrote an iterative solver to help inform my COMSOL mesh sizing. I was able to show perfect agreement between their solution and my manufactured one, both in terms of velocity and shear stress profiles throughout the flow's cross section. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/NumericalLava.jpg" height="300" alt="Hub1">
  <img src="/imagesreal/AnalyticalLava.jpg" height="300" alt="Hub3">
</div>
My optimized numerical velocity profile compared to Tallarico and Dragoni's analytical solution
---
