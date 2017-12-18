---
layout: project-page
title: "Tech Impact on Home Values: Silicon Valley "
linkname: tech-impact-on-home-values-silicon-valley-
author: "Andrew Strong"
tagline: "Map of home value changes in Silicon Valley between 1997 and 2017. Focus on the impact of prominent tech companies on the region's real estate. "
location:
    - place: San Jose, California, USA
    - place:  San Francisco, California, USA
    - place:  California, USA
project-link:
    - href: https://atstrong.carto.com/builder/ab8df3c0-d5fa-403d-a6bd-7427c624e06f/embed
    - href: https://atstrong.carto.com/builder/4db9d511-509d-474a-a3f1-8ab23d100bde/embed 
tags:
    - tag: tech, housing, real estate, home values
thumbnail-path: img/tech-impact-on-home-values-silicon-valley-/ybvxQIt.png
img-folder: ../../img/tech-impact-on-home-values-silicon-valley-/
timestamp: 12/15/2017 20:52:27
---
Tech Impact on Home Values: Silicon Valley 

In recent years, issues of social inequality, gentrification, and affordability have come to a head in Silicon Valley where the prosperity of the regions tech sector has skyrocketed housing prices and displaced many of the regions residents as a result. The maps below express the local and regional changes in home values between 1997 and 2017. 

Housing data for this project is drawn from Zillow’s Median Housing Value Dataset which can be accessed through their [data portal](https://www.zillow.com/research/data/). Data by zipcode and by neighborhood were both used. The data was then filtered by state and region and then narrowed down by year to avoid seasonal fluctuations in the real estate market and focus on other trends. The data was also manipulated to account for inflation by altering the values of each year by their corresponding CPI (Consumer Price Index) value. The CPI for each year was collected through [the US Bureau of Labor Statistics](https://data.bls.gov/cgi-bin/cpicalc.pl?).  

Data on technology companies is drawn from [the 2017 SV150 rankings](http://www.mercurynews.com/2017/05/01/sv150-2017-ranking-of-silicon-valleys-top-150-public-tech-companies/). The SV150 rankings are based on international profit of companies headquartered in Silicon Valley. This often also correlates with the size of the companies and is useful in understanding the connections to global capital flowing through this regions.  Supplemental information on location was found through Google Maps and information on founding and IPO dates was collected through [Crunchbase](https://www.crunchbase.com/). 

The following map visualizes the IPO dates of major technology companies as the industry grows. An IPO is important because this is when companies become publicly traded on the stock exchange and as a result this allows for fluidity and accumulation of capital in ways that hadn’t previously existed. The spatialization of IPO dates reveals a concentration of tech companies in specific places as well as concentrated opportunity for wealth fluidity at specific times.  

<iframe width="100%" height="520" frameborder="0" src="https://atstrong.carto.com/builder/4db9d511-509d-474a-a3f1-8ab23d100bde/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

The following maps compare these IPO dates with the changing home value across the Bay Area. 

<video preload="auto" autoplay="autoplay" loop="loop" style="width: 454px; height: 640px;">
    <source src="//i.imgur.com/ZsOGH7W.mp4" type="video/mp4"></source>
</video>

The South Bay, Silicon Valley, has had a longer history with tech companies because of their developmental origins with ties to Stanford University in Palo Alto. 

<video preload="auto" autoplay="autoplay" loop="loop" style="width: 640px; height: 446px;">
    <source src="//i.imgur.com/eVFMQeu.mp4" type="video/mp4"></source>
</video>

San Francisco has become particularly contentious in recent years because they have experience later effects of tech companies on their real estate as Silicon Valley expands.

<video preload="auto" autoplay="autoplay" loop="loop" style="width: 640px; height: 446px;">
    <source src="//i.imgur.com/ilurXC2.mp4" type="video/mp4"></source>
</video>

This impacts of the growing tech industry is felt not only in the immediate geographic vicinity but also across the state. 

<video preload="auto" autoplay="autoplay" loop="loop" style="width: 640px; height: 448px;">
    <source src="//i.imgur.com/UVIp9Xa.mp4" type="video/mp4"></source>
</video>

What is particularly interesting to note is that during the financial crash of 2008, one of the few areas to retain its home value was that to the west of San Jose near Palo Alto and Stanford University. Additionally, following 2008, there is an increased speed with which the discrepancy between home values in Silicon Valley and areas toward the center of the state near Sacramento and Fresno widens. 

The following map allows individuals to explore the top 150 technology companies by sales in the Bay Area. Through this map individuals can link place with company as well as find out information about their current rank, their founding and IPO dates, and the previous year’s revenue from sales. 

<iframe width="100%" height="520" frameborder="0" src="https://atstrong.carto.com/builder/ab8df3c0-d5fa-403d-a6bd-7427c624e06f/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Future work on this project will entail building out the interactive interface for acquiring information about each company with the hope of including the number of employees contractors, and subcontractors associated with each company. I would also like more formally spatialize the locations of each of these sites. Right now each company is located as a point at their headquarters but many of these companies have multiple campus throughout the Bay Area. I am currently working with zoning data from local cities and with data from Open Street Maps to determine the best way to organize and visualize this data.  
