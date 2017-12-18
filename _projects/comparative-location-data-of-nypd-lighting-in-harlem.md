---
layout: project-page
title: "Comparative Location Data of NYPD Lighting in Harlem"
linkname: comparative-location-data-of-nypd-lighting-in-harlem
author: "Paul Beasley"
tagline: "This map attempts to locate correlations between the placement of NYPD floodlights in Central Harlem with crime and community facilities data."
location:
    - place: Central Harlem
project-link:
    - href: https://thenewschool.carto.com/u/beasp992/builder/0b167c00-f8a4-4302-95a3-7c91ee990adb/embed
tags:
    - tag: crime, NYPD, Omnipresence, social justice, policing
thumbnail-path: img/comparative-location-data-of-nypd-lighting-in-harlem/YobUEfz.png
img-folder: ../../img/comparative-location-data-of-nypd-lighting-in-harlem/
timestamp: 12/15/2017 23:55:50
---
In 2014, newly-elected Mayor Bill DeBlasio rolled out a program aimed at reducing crime in the city’s most impacted neighborhoods. The plan, titled the Mayor’s Action Plan for Neighborhood Safety, focused on implementing a variety of initiatives, one which was a pilot study researching the effect of enhanced lighting on streets and around buildings to reduce crime. Initially, only 15 sites, all NYCHA properties were chosen for the study. Polo Grounds in Harlem was the only Manhattan NYCHA development involved in the study. However, the use of high-powered floodlights has become concentrated in the northeastern part of Central Harlem, away from the original Polo Grounds site. Now, every block from 142nd to 147 between 7th and Lenox Avenues has been placed in this blinding landscape of light. The Lincoln Houses on 132-135th Streets and between Madison and 5th Avenues also contend with this. I wanted to try to figure out why the lights seemed to be placed where they were.

Finding data that had geometries and was directly associated with the lighting program was almost impossible. Instead, I ended up attempting to draw a landscape that might suggest some correlations and relationships between other relevant datasets and the locations of the lights I had mapped myself.

I found a shape file file on NYC Open Data that contained polygons for all NYCHA developments in New York City and of course I included it.

![]({{ page.img-folder }}ZY3ZmqDr.png)

I also found a CSV file that had a list of all community-based facilities such as child care, senior community centers, community centers, job training centers, and other kinds of places that hosted programs that might deter crime or fight the effects of poverty that might lead to crime. I added a dynamic widget so that people could view the density and number of them in a given area. I also added multiple colors to the facility types.

![]({{ page.img-folder }}m1bcTff.png)

I realized that it might be helpful to add photographs to the pop-ups about the lights and so I added those. I added information about the addresses of the lights and if they had existed in their current location in 2016.

![]({{ page.img-folder }}Q2LJhTf.png)

Finally, I thought that instead of showing crimes as points it would be better to show them as an animation across time. I used conditional statements to limit the results to the longitude and latitude of Central Harlem between 125th and 148th Street and St. Nicholas to 5th Avenue. I also only included data on assaults, robberies, and dangerous weapons--serious crimes likely to stand out spatially or cause a disruption in the neighborhood. I took the crime map data for 2017 and animated it placing it on a shapefile for Empower Zones, special zones set up in low income communities around which engagement and social work is planned.

![]({{ page.img-folder }}1WOW3VB.png)