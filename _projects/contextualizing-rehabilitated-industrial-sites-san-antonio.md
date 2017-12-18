---
layout: project-page
title: "Contextualizing Rehabilitated Industrial Sites: San Antonio"
linkname: contextualizing-rehabilitated-industrial-sites-san-antonio
author: "Jason Azar"
tagline: "This project examines the residential characteristics of neighborhoods surrounding six rehabilitated industrial facilities in San Antonio."
location:
    - place: San Antonio, TX, USA
project-link:
    - href: https://thenewschool.carto.com/u/jazar2/builder/eb6a5905-b876-4901-90b4-e9d25a2eab82/embed
    - href:  https://docs.google.com/a/newschool.edu/document/d/1VQ_JCfUP5WoIDE2moCrL6wfIDz4gCWq25Eh0H6OZKKk/edit?usp=sharing
tags:
    - tag: housing
    - tag:  neighborhood change
thumbnail-path: img/contextualizing-rehabilitated-industrial-sites-san-antonio/eTQfEdv.jpg
img-folder: ../../img/contextualizing-rehabilitated-industrial-sites-san-antonio/
timestamp: 12/9/2017 18:39:56
---
In the late 1980’s San Antonio started to appear among the top ten travel destinations in the world, ranking at number nine between Paris and Venice, and in the United States behind only Santa Fe and San Francisco. Today, San Antonio’s tourism and hospitality industry is one of the strongest in the nation, and has had an economic impact of over $13.5 billion over the past 10 years. Many of San Antonio’s historically famous attractions are unique and provide an ambiance that is difficult or impossible to recreate elsewhere, but it is a wholly new set of attractions that are drawing the attention of tourists and investors to San Antonio today. Not emphasized in new online travel guides is the city’s downtown, the Alamo, the River Walk barges, or the multiple theme parks, all attractions that for decades served as the most dominant elements of the city’s tourism and hospitality economies. The recent trend among travel sites’ reviews of San Antonio praise the city’s newest developments, chief among them being rehabilitated industrial sites transformed into high-end mixed-used districts with an industrial-ruin aesthetic. 

![]({{ page.img-folder }}RYiICdwr.jpg)

These sites are situated along resource lines, like rivers and railroads, that once were utilized by industry that circles downtown. Today, these same resource lines act as boundaries between the energies and investments growing in downtown San Antonio and the adjacent neighborhoods, many residents of which are employed within the massive service economy of downtown. These rehabilitated industrial facilities have the effect of lowering the conceptual resource-line barriers, but with the predominant trait of downtown forces moving outward. This project aims to examine the neighborhoods within a half-mile of these sites, focusing especially on the residential characteristics, and to compare them to the inner city as a whole. 

![]({{ page.img-folder }}3my9xPY.jpg)

I started with data available from the city of San Antonio’s online GIS portal and through a request with the Bexar County Appraisal district, which provided me with the most recent appraisal parcel data. In order to better understand the characteristics around these selected sites, I combined, reformatted, and created new fields within the parcel data to produce individual map layers that contain broad use categories, like single-family residential, retail, or industrial use. 

![]({{ page.img-folder }}fdUfamar.jpg)

The next step was to “clip” these layers to fit within ½ mile buffers around the rehabilitated industrial sites. 

![]({{ page.img-folder }}WQvgmAc.jpg)

Using the analysis in Carto, I then calculated the average appraisal value, the average year of construction, and the percent of single-family parcels that are owned by San Antonians. Using the pop-up features, this information is available with a click on the bright green lots labeled with a site name. Also available through pop-ups is information about each individual lot. Using Carto’s widget function, the map provides statistics about the land use within each of the buffer sites. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/jazar2/builder/eb6a5905-b876-4901-90b4-e9d25a2eab82/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

![]({{ page.img-folder }}Nv5EnEJ.png)

In comparing the selected neighborhoods to averages for the inner city loop, we find that the residential parcels within a half mile of the selected sites are appraised 50% higher than city averages, are owned by San Antonians at a rate of 4% less than city averages, and are on average 15 years older. 

Moving forward with this line of research, an examination of the historical appraisal values will reveal the rate at which these neighborhood’s appraisal values increased following the announcement and completion of these projects. This will allow a temporal understanding of how quickly these projects transform the residential populations around them. 
