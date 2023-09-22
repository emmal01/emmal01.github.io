---
layout: project
type: project
image: img/vacay/vacay-square.png
title: "Assessing CO2 error in clear-sky parameterized radiation models"
date: 2023
published: true
labels:
  - Python
  - Intake
summary: "A responsive web application for travel planning that my team developed in ICS 415."
---

<img class="img-fluid" src="../img/clear_sky_square.jpg">

For my senior thesis, I compared parameterized and line-by-line model output from experimental protocol outlined by the CMIP6 Radiative Forcing Model Intercomparison Proect (RFMIP). The purpose of this was to understand how well the parameterized radiation models that are incorporated in Global Climate Models (GCMs) quantify the radiative energy balance of the atmosphere. 

In order to increase efficiency and reduce cost, parameterized models approximate the emission spectra of atmospheric gases to minimize the calculations necessary to compute atmospheric radiation levels. In my thesis, parameterized models were compared to 'line-by-line' models that fully evaluate emission spectra of atmospheric gases to understand the magnitude and sources of error arising from the parameterization of emission spectra. I focused specifically on this parameterization error under a variety of atmospheric CO2 concentrations, ranging from pre-industrial to 8x modern-day CO2 scenarios.


Here is some example code to illustrate Simple Schema use:

{% gist 9defa1fb3f4eb593ba5fa9eacedca960 %}
 
Source: <a href="https://github.com/theVacay/vacay">theVacay/vacay</a>
