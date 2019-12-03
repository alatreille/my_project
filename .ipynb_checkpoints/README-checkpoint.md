# Individual project: natural hazards and underwater communication networks.

![Map](Map_cables.PNG)

## Why did I choose this topic?

Last year, while writing my thesis on the consequences of Hurricane Irma on water systems in Sint Maarten, I discovered the analysis of the spread of network risks. This year, I decided to deepen this research theme by studying a new type of network: underwater communication cables. These cables are very interesting objects in terms of risk analysis: deposited on the ocean floor, they can be weakened by underwater mass movements (caused by earthquakes, volcanoes, landslides), but also by human activities (boat anchors, fishing). In the event of an incident, some parts of the world may be affected by telephone and Internet outages.  For example, operators are currently concerned about the development of a volcano in the sea off Mayotte, which threatens to deprive part of Asia of the Internet.

## My project

I would like to use what I learned in this "Research Computing" class to better analyse the natural and anthropogenic risks to which submarine cables are exposed by creating maps that superimpose hazards and infrastructure. By the end of my analysis, I hope to be able to answer the following question: *is the cable routing optimal to reduce their exposure to risks?*

## My datasets

For this project, I would like to use 3 types of data: 
- the data relating to the submarine cables that can be downloaded from this [Github page](https://github.com/telegeography/www.submarinecablemap.com): official submarine cable system name, ready for service date (RFS), cable system length in kilometers, owners of the system, oficial URL of the system, landing points.
- the data relating to natural hazards: [submarine volcanoes](https://www.ngdc.noaa.gov/nndc/struts/results?type_0=Like&query_0=&op_8=eq&v_8=&type_10=EXACT&query_10=None+Selected&le_2=&ge_3=&le_3=&ge_2=&op_5=eq&v_5=&op_6=eq&v_6=&op_7=eq&v_7=&t=102557&s=5&d=5), [earthquakes](https://data.humdata.org/dataset/catalog-of-earthquakes1970-2014).
- the data relating to human activities: [fishing effort](https://github.com/GlobalFishingWatch/paper-global-footprint-of-fisheries).

## My analysis

My analysis will consist of graphs and maps: 
- infrastructure location map 
- graph illustrating the evolution of the number of submarine cables over time (the idea is to show that this is a growing technology)
- seismic map + map overlaying earthquakes and cables
- volcano map + map overlaying volcanoes and cables
- maritime traffic map + map overlaying maritime traffic and cables
- map of vulnerable cables

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alatreille/my_project/master) 
