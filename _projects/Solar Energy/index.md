---
layout: post
title: Solar Energy Projects (Industry and Research)
description:  This is a brief overview of some of the solar energy projects I've worked on over my 3 years in the industry. I worked as a Junior Project Engineer for two years at Mynt Systems, a solar design/installation firm of both residential and commercial projects. This past year, I worked with the Spatial Climate Solutions lab at UCSB to study agrivoltaics potential in Washington State.

skills: 
- PVSyst (Advanced)
- Helioscope
- Data Analytics
- API and CLI Programming
- Energy Metrics
- Construction Planning
- Customer Reporting
main-image: /GraniterockHQ.jpg

--- 

## Agrivoltaics - Overview
Agrivoltaics is the practice of placing solar panels over orchards or vegetable fields to generate electricity while preventing crop overheating or sunburn. I led the 3D design, energy modeling, and data analysis of over 670 agrivoltaic sites across Washington State. This project was funded by the Washington Department of Commerce to distribute clean energy grants and involved collaboration with The Nature Conservancy and American Farmland Trust. The images here are sourced from our published report, found [here](https://www.researchgate.net/publication/393794180_Low_hanging_fruit_for_Washington's_energy_future_Agrivoltaic_feasibility_for_agricultural_and_energy_resilience_in_the_Evergreen_State). I've co-authored two more reports with broader modeling, which are being published by the Spatial Climate Solutions Lab.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/AgrivoltaicsCoverPhoto.jpg" height="270" alt="Hub1">
</div>
Artist rendition of crops and livestock under photovoltaics

## Agrivoltaics - PV Design
To measure the shading impacts on crops, I developed a new method of calculating the shading impacts of overhead panels on crops through PVSyst. This method was adapted with over 40 unique agrivoltaic system designs, varying panel height, size, and tracking ability over a number of crop layouts to determine which arrangement had the best impact on crop yield or quality. Site-specifc PV designs were made using local geographic data (topography, large objects, available land) for custom farm designs. 

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/DesignVsIrradiance.jpg" height="270" alt="Hub1">
</div>
A representative agrivoltaic design and corresponding shading impact on the apples beneath
<br>

## Agrivoltaics - Programming and Data Analysis
Batch calls to PVSyst were made using the PVSyst CLI tool, which I operated through a number of Python scripts to automate the process of calculating the solar fluxes on shaded and unshaded crop variants. These results were then adapted into metrics of fruit/vegetable yield or impacts on overall marketability through custom scripts interfacing with crop models.


<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/RedwanSunburnRisk.jpg" height="300" alt="Hub1">
  <img src="/imagesreal/StrawberryYieldReduction.jpg" height="300" alt="Hub3">
</div>
Apple sunburn risk and percentage yield of strawberries at representative Washington locations

## Agrivoltaics - Energy Metrics

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/ChordRefinement.png" height="300" alt="Hub1">
  <img src="/imagesreal/ForceDistribution.png" height="300" alt="Hub3">
</div>
My functions of chord length and force calculations over the length of the blade

---

## Industrial Solar - Overview
I worked for two years at Mynt Systems, beginning as an Intern and getting promoted to Junior Design Engineer. My work spanned all the full-cycle PV design and installation process, working on both the design mock-ups during the sales process and for-construction designs. I also helped with BOM generation and supply during the construction process, as well as doing client-side site reporting and repair. My time at Mynt ended in the Spring Quarter of my Senior year, when I started TAing undergraduate classes.  

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/MyntLogo_Crop.jpg" height="150" alt="Hub3">
</div>

## Industrial Solar - Site Design and Modeling
I modeled over 50+ rooftop solar arrays and carports during my time at Mynt Systems. These included PE-approved permitted designs, as well as post-construction mock-ups to be used for generation verification or as a sales resources. For-construction arrays and building plans were developed using AutoCAD, while production simulations and verification models were created in Helioscope.

<div style="display: flex; gap: 10px;">
  <img src="/imagesreal/HelioscopeDrone.jpg" height="250" alt="Hub2">
  <img src="/imagesreal/HelioscopeSLD.jpg" height="250" alt="Hub1">
</div>
Post-construction Helioscope model and corresponding SLD

## Industrial Solar - Production Metrics and Reporting
I generated monthly reports using actual vs. synthesized production data as part of my role on the site management and client-facing side at Mynt Systems. Prior to my inclusion on the team, reports were generated manually and had an average turnaround time of three days. I hired and managed a third-party contractor to write PHP code and scrape the SolarEdge API. I then automated the report generation process in JavaScript to generate 50+ monthly production reports within the hour. 

## Industrial Solar - Troubleshooting and Site Repair 
Part of my role at Mynt Systems was system troubleshooting for both residental and commercial arrays. I flagged any production discrepencies between the expected and actual electrical generation to investigate before our installation crew could be called to the sites. On multiple occassions, I restored over 90% of the system production by identifying and switching off faulty strings until replacement parts could be ordered.
