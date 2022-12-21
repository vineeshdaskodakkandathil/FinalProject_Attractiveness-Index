**Attractiveness index of Bike-Sharing Stations for Brooklyn NYC**

Prepared by: Vineesh Das Kodakkandathil, MCRP, Rutgers University NJ

A recent article on the Brooklyn borough's booming nightlife and recreational activities prompted the initial project idea. It is found in the same article that Brooklyn has seen an increase in the number of taxis and for-hire vehicles mostly used for recreational purposes. I was curious about the status of bike share stations and systems in place and wanted to check whether they are doing their best to attract more riders, so I chose major NYC attractions (point of interest layer) that could attract bike share users and created an Attractiveness Index to determine where all bike share stations can gain more riders.  I  used the NYC open data, NYC.org, and Citybike portal to get the required information and then made a scoring and weightage-based index for each station.  Several data sources were updated regularly, one was updated in September and August of 2022, which was the most recent one. I used multiple geoprocessing tools in Geopandas to develop the final index layer. Initially, I was about to do it for NYC then when I started mapping in folium, but Google-colab had other plans and crashed, it couldn't handle the 9k point of attraction point feature to make a heatmap, So I scoped down to Brooklyn. In addition to the interactive map and attraction heatmap, I also created a few tract-level maps to see the bike and walk trips to work.  Now let's explore the map!

**Parameters and Scoring**
![Parameter and Scoring](https://github.com/vineeshdaskodakkandathil/FinalProject_Attractiveness-Index/blob/4d191e07ec64dde14ab2730fff08dda5851ad6d4/Scoring.png)





**Static Maps**
![Static Maps](https://github.com/vineeshdaskodakkandathil/FinalProject_Attractiveness-Index/blob/232fa5c4c9ed0ed33a555c21c40ab1c762fc9f1e/Staticmaps.jpg)





**Interactive Map**
<iframe src="Attractiveness Index.html" height="500" width="500"></iframe>

You can explore this map [as its own web page here](Attractiveness Index.html).
