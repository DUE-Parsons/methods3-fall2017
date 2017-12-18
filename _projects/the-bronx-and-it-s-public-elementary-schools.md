---
layout: project-page
title: "The Bronx and it's Public Elementary Schools"
linkname: the-bronx-and-it-s-public-elementary-schools
author: "Selamawit Yemeru"
tagline: "My project is seeking to make academic and demographic statistics of elementary schools in the Bronx accessible and transparent"
location:
    - place: Bronx, NY, USA
project-link:
    - href: https://thenewschool.carto.com/u/yemes842/builder/31f22a5e-c2b2-49b7-a8d9-76c49d6b4d74/embed
tags:
    - tag: social justice
    - tag:  failing school system
thumbnail-path: img/the-bronx-and-it-s-public-elementary-schools/lu2jhVHr.png
img-folder: ../../img/the-bronx-and-it-s-public-elementary-schools/
timestamp: 12/15/2017 14:18:41
---
There are more than 1.1 million students in over 1,700 public schools across NYC. In a perfect world all students in NYC would have equal access to a quality education, yet the reality is quite the opposite. Countless articles, reports and investigations have found that some of NYC’s poorest children, whom happen to be of students of color, are facing some of the worst schooling conditions. In an article published by NY Daily News, some of the worst schools are in school districts located in the South Bronx. What’s more, that roughly 1 in 10 students in these schools are homeless, 93% are economically disadvantaged and have the lowest proficiency rate in English in the city.

For this reason, I thought I should produce a map of the Bronx showing exactly which students are being affected by the failing school system, and how they compare to other parts of the Bronx. While there is a substantial amount of data on the demographics and performance levels of NYC’s public schools online, none focus on the students being affected in the Bronx. 


To start, I downloaded a map of NYC’s School Districts and NYC’s Public Schools, and uploaded both to QGIS. Next, I manually selected and deleted all School Districts and Public Schools that were not in the Bronx.

Then, I downloaded all Demographics and Academic Performance Data of NYC’s Public Schools from the Department of Education’s website. 

![]({{ page.img-folder }}ljoYnqwr.png)

The data included information on both the school and district level. I filtered for all schools in the Bronx and narrowed the search even further to just elementary schools in the Bronx. I included all schools with students in grades 1 to 5.  In addition, I filtered my demographics data to include only school districts within the Bronx. I saved the data onto two different excels based on whether it was district wide statistics or on the school level.


Next, I uploaded both excel sheets to QGIS. I joined my school level statistics with the NYC’s Public Schools map layer, and did the same for my district level statistics and the NYC’s School Districts map layer. Once the files were transferred to Carto, I tried to style my data based on any obvious correlations I could find. For the most part, there was no clear geographic difference between the lowest and highest performing schools in the Bronx. Therefore, I’ve concluded that the most important part of this map is the data behind the map. I tried to include as much relevant information I could find as popups for both the School Districts and the individual Schools.

For the School Districts, I have included information on the poverty levels of students from the years 2011-2016. What’s more, I've included breakdowns of gender, race, socioeconomic status, academic performance, and English Learning students. 


![]({{ page.img-folder }}xZ6z8LZ.png)
![]({{ page.img-folder }}CqDATRc.png)
![]({{ page.img-folder }}cZlOUvg.png)
![]({{ page.img-folder }}VivUB92.png)



****Poverty levels are based on the number of students with families who have qualified for free or reduced price lunch****
