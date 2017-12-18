---
layout: project-page
title: "Boyle Heights: Affordable Housing Needs Assessment"
linkname: boyle-heights-affordable-housing-needs-assessment
author: "Lyric Kelkar"
tagline: "Assessing the need for affordable housing in LA County, particularly Boyle Heights and reviewing potential spaces for a Community Land Trust."
location:
    - place: Los Angeles, CA, USA
project-link:
    - href: https://thenewschool.carto.com/u/lkelkar/builder/18968dd8-cf2d-4e39-9246-170fac427aa2/embed
    - href:  https://thenewschool.carto.com/u/lkelkar/builder/953d2b64-b466-4de9-9863-c8a1b49e0ba0/embed
    - href:  https://thenewschool.carto.com/u/lkelkar/builder/949ccda6-9cc6-48ad-a847-f45833c902bf/embed
tags:
    - tag: Affordable Housing
    - tag:  Needs Assessment
    - tag:  Housing
    - tag:  Vacant Land
thumbnail-path: img/boyle-heights-affordable-housing-needs-assessment/WYuHJYcr.jpg
img-folder: ../../img/boyle-heights-affordable-housing-needs-assessment/
timestamp: 12/16/2017 12:46:34
---
Boyle Heights is a neighborhood just east of Downtown Los Angeles, bordering the ever-trendy Arts District. As the Arts District rapidly gentrifies, the people who lived there before are beginning to move east over to Boyle Heights where the property is much lower, and the cost of renting is far less than the Arts District. Despite this influx of money that is now happening, the neighborhood of nearly 100,000 has a history of disinvestment. Looking back to the redlining maps of the Home Owners Loan Corporation, Boyle Heights sits almost perfectly inside section D53.

![]({{ page.img-folder }}5zBlKWpr.png)

Looking at the current situation in Boyle Heights and identifying a few issues that are afflicting the people in the neighborhood, I wanted to see how these different issues layered on one another to show exactly which census tracts – according to census data from 2015 – are going to be the most affected by the influx of new residents. 

Picking four factors that can predict displacement, I translated census data into maps: housing tenure, income levels, poverty levels and unemployment levels.

![]({{ page.img-folder }}864fRWmr.png)

Seeing how high the rental tenure of the neighborhood was, it was clear that owning land is one tangible way to fight the widespread displacement that will occur.

![]({{ page.img-folder }}EzBWKuZr.png)

Because income is quite low in much of the neighborhood, it might be difficult for people to save up enough for a down payment.

![]({{ page.img-folder }}uL4vsMfr.png)

Also seeing that the neighborhood is very impoverished and much of them live below the poverty line, including about 47% of children, it became clearer that money was a huge issue for the neighborhood. So having displacement be a looming threat would ultimately create greater financial burden and further disenfranchise the people who have lived here for decades.

![]({{ page.img-folder }}PCJ0zNDr.png)

Because all of this data is opaque when separate from one another, I layered the different issues on an interactive map that shows the values for each of the measures, along with some additional information.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/lkelkar/builder/18968dd8-cf2d-4e39-9246-170fac427aa2/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Having so much information on one map is difficult to decipher so I came up with a metric that pulls all these contributors together into one number and ranks the different census tracts across LA County based on how badly they are affected by these different issues. This was done by seeing what the average of each category is in LA County, and from there determining appropriate increments to scale on a size from 1 to 10. Further, weighting two of the criteria – housing tenure and poverty levels – more than the other two because they are leading causes and contributors in being displaced. In total, after weighting those two, each census tract was given a score out of 100, with the lowest score being 10. The higher the number, the greater the need for affordable housing and potential alternative solutions.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/lkelkar/builder/953d2b64-b466-4de9-9863-c8a1b49e0ba0/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Seeing how heavily burdened the people in Boyle Heights are, I was curious to see what vacant lands were available that could potentially be used as a solution for the neighborhood, such as a community land trust or cooperative land ownership model. This would alleviate the high cost of ownership by allowing for cooperative ownership and taking some of the administrative and land costs and putting them on the non-profit that runs them. There are over 300 different vacant parcels in Boyle Heights, and about half of them are zoned as residential.

Trying to understand what each of these lots could be transformed, I wanted to see who owned these pieces of land, but it cannot be found online or through the tax accessors office. It needs to be found in person at their office, so instead I decided to look at which of these pieces of land were owned by the city because it would be easier for them to be acquired for affordable housing. As it turns out, there are only a few pieces of land that are vacant and city owned. But a few is better than none!

![]({{ page.img-folder }}GilZ5F9r.png)

Looking at where the transit line is and how close any of these vacant parcels are to the stations will also give some insight into future costs of property. As the line continues to extend, this will be another gentrifying factor in the neighborhood. So looking at the different areas that might be most heavily affected, I saw that there are a number of vacant pieces of land that are close to the stops, even some that are residential. Unfortunately none of the ones within a quarter mile radius are city owned, but there are a few that are close by. 

Lastly for analysis, overlaying the information of the metric with the vacant land and Gold Line stations and buffer will give an overview of where might be the best places to start a Community Land Trust in anticipation of the rising housing prices in the neighborhood. Providing opportunities for permanently affordable housing and home-ownership is key in preventing displacement in a neighborhood where the median income is about $34,500 per year. Having some of the vacant land transformed into a space for community members can be a small way to contribute to the existing community and ensure they are given a small chance in the battle against gentrification.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/lkelkar/builder/949ccda6-9cc6-48ad-a847-f45833c902bf/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
