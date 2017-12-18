---
layout: project-page
title: "Shadows of Development"
linkname: shadows-of-development
author: "Maha Aslam"
tagline: "My project is about mapping data about the city and building narratives for collective knowledge sharing to empower vulnerable communities.
"
location:
    - place: Lahore, Punjab, Pakistan.
project-link:
    - href: https://docs.google.com/presentation/d/19zo7XsQvvKCqcgGUogz_GBIccJPFHfShBf0VuXWFfIg/edit?usp=sharing
    - href: https://thenewschool.carto.com/u/aslam462/builder/56f3b99b-38fa-48de-8288-164a474ed10e
    - href: https://mahaaslamrajaa.wixsite.com/oltresearch/maps
tags:
    - tag: social justice
    - tag:  development
    - tag:  transportation
    - tag:  knowledge sharing
thumbnail-path: img/shadows-of-development/ETGEAf8.jpg
img-folder: ../../img/shadows-of-development/
timestamp: 12/10/2017 18:32:30
---
My work on the Orange Line Train project is centered on finding ways to make data about the city of Lahore more accessible and readable to its residents. The lack of access to information regarding ongoing developmental projects in the city has alienated the residents from the quickly urbanizing city. My aim is to be able to make people understand their own city better and actively engage in shaping its future course. In order to achieve this I am using the Orange Metro Line Train construction as a case study and organizing the data related to it in a single platform for public access. The platform, once activated will continue to receive and organize data regarding not only the OLT-Train project but also other projects in the city to empower the people.
![]({{ page.img-folder }}kdpnQrWr.png)
The Orange metro line (shown in the above map) is an automated rapid transit system under construction in Lahore, Punjab, Pakistan. When operational in October 2019, the Orange line will become Pakistan's first metro rail line. The Orange line is the first of the three proposed rail lines proposed for the Lahore Metro. The line will span 27.1 km (16.8 mi) with 25.4 km (15.8 mi) elevated and 1.72 km (1.1 mi) underground. The line will be served by 26 stations and is expected to handle 250,000 passenger daily. I began my project by mapping the stops on to a map as there was none available online document that I could use to map the route.
Currently along the route for stations, track, and related infrastructures land is being acquired from schools, hospitals/clinics, site of religious worship as well as shops, homes and public amenity plots as well seizing viable space from thousands of street hawkers and vendors. 

![]({{ page.img-folder }}yzHs2Tz.png)
The first map I created was with Maryam Hussain’s data. She is an activist who has been working actively to support communities around the construction sites along the route of the orange metro line who are in fear of eviction. After receiving her consent, I used data from her social media and created a dataset that I could geographically locate.

![]({{ page.img-folder }}WUezfJwr.png)
Lahore Conservation Society is one of the main activist groups that has been protesting against the environmental degradation being caused by The Orange Metro Line. They have been rallying for environmental justice causes and have mobilized people to show support to people facing evictions. We spatially located their activities in order to understand their role in creating this narrative of the city

![]({{ page.img-folder }}q3JEus7.png)
![]({{ page.img-folder }}mzImR9yr.png)
Chief Minister of Punjab has the highest authority on the issues relating to the province of Punjab.  And since Lahore is the capital of Punjab his influence in the city's development is crucial to our narrative of the orange line train project. (chart shown)Lahore Development Authority is another key agency in this narrative as they are responsible for all the new development in Lahore area and they have control over land use and zoning of the city. The map spatially locates the press releases made by the office of the chief minister during the orange line construction. The data for this map was tricky as the press releases were in Urdu and so I could not perform a search on the database thereby limiting the data I could find.

![]({{ page.img-folder }}eKxtluR.png)
One of the main objectives of our research work was to understand the vulnerable components of the city under threat by developmental projects like the Orange Metro line. So by joining our multiple data sets by common attributes we were able to identify points of Interest. These areas faced the most conflicts as well as received the most attention via media, social organizations etc. So for our future direction we would like to explore these areas further.
Using Maryam Hussain's data on evictions I created a parameter around the route of the Orange Metro Line that would encapsulate the existing limits of effected communities (300 ft. along the line).  Overlaying the low income communities along the metro line with this buffer indicates the areas that need to be protected in the future proceedings of the Orange Metro Line as the construction continues.
Some of the issues I faced with locating the low income communities and informal settlements is the lack of data available on it. I used a file with incomplete data issued by a government agency while also verifying from satellite imagery and contacting people of the neighborhood.

![]({{ page.img-folder }}biE0CTDr.png)
Going through ‘Master plan for Lahore 2020’ I found a data set showing densities in different neighborhoods of the city. Although the data set was from 2001 and doesn’t represent the current population status but I thought it was a good starting point for me to analyze the densities with regard to the affected areas. So I traced the neighborhoods in google maps and exported them into qgis (as the neighborhood data was not available on open street maps) and overlaid it with my existing datasets. The map gives an insight into the neighborhoods that will face the most displacement. As a way forward I would like to find a way to map the renters vs owner occupation in these areas to strengthen my research.

https://www.youtube.com/watch?v=M8NblhzDltc
This time lapse created using data from Maryam Hussain's work visualizes the evictions that have taken place due to the ongoing construction of the train line, As a way forward we would like to collect the data on the actual number of people evicted and re-design this time lapse according to that.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/aslam462/builder/56f3b99b-38fa-48de-8288-164a474ed10e/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

The interactive map made in Carto synthesizes all the information I have come across to build the narrative of Orange Metro Line and links all the sources that have been used. It allows the user to explore these issues on their own by clicking the points and find more details linked to them.

