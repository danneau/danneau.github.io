---
layout: post
title: 'Honors Thesis'
---
## Overview
### The Potential Correlation of Public Transit Accessibility and Voting Turnout; A Study in Worcester, Massachusetts and Baton Rouge, Louisiana
This project was my Honors Thesis for Clark University's Graduate School of Geography within the School of Climate Environment and Society, Defended April 17th 2026.

## Abstract
This thesis looks at the potential impact public transit has on voting turnout through a look at two cities, Worcester, Massachusetts and Baton Rouge Louisiana and their turnout in the 2024 election. Difficulty getting to one’s polling place has been shown to be a strong contributing factor in the likelihood that a person casts an in-person vote in an election (Dyck and Gimpel, 2005). A lack of access to polling places by public transit may be a barrier for households without a personal vehicle to vote. This study uses random forest regression to identify the relationship between the amount of time it takes to get to one’s polling place from the centroid of their precinct and the voting turnout of said precinct. This study finds that the relationship between the amount of time it takes for a potential voter to get to their polling place by taking public transit or by walking and turnout for that voter’s precinct is worthy of further study.

## Output Maps
![Baton Rouge, LA]({{ 'assets/img/projects/honorsthesis/TransitTimeTurnoutBatonRouge.png' | relative_url }})
![Worcester, MA]({{ 'assets/img/projects/honorsthesis/TransitTimeTurnoutWorcester.png' | relative_url }})
These two maps show the calculated transit time to get from the center of the precinct to the polling place utilizing public transit or walking, and the turnout from the precincts. The code used to calculate the transit time is located below. 
Worcester: Sources:  Esri, TomTom, Garmin, FAO, NOAA, USGS, (c) OpenStreetMap contributors, and the GIS User Community, Worcester City Clerk, US Census Bureau. Spatial Reference Name is NAD 1983 State Plane Massachusetts Mainland FIPS 2001 Feet. Datum is North American 1983; Projection is Lambert Conformal Conic.
Baton Rouge: Sources:  Esri, TomTom, Garmin, FAO, NOAA, USGS, (c) OpenStreetMap contributors, and the GIS User Community, East Baton Rouge Parish, Louisiana Secretary of State, US Census Bureau. Spatial Reference Name is NAD 1983 State Plane Louisiana South FIPS 1702 Feet, Datum is North American 1983 Projection is Lambert 

[View the project repository]([https://github.com/danneau/TransitTimeTurnout.git])


[View the thesis (PDF)]({{ 'assets/img/projects/honorsthesis/DNeau_HonorsThesisFull.pdf' | relative_url }})
