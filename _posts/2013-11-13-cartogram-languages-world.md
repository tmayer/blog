---
title: "Cartogram of the World's Languages"
description: "Scaling the size of each country by the number of languages"
toc: false
comments: true
layout: post
image: images/cartogram.jpg
hide: false
search_exclude: true
categories: [visualization, d3js, typology]
---


![]({{ site.baseurl }}/images/cartogram.jpg "Cartogram screenshot")

The interactive cartogram can be accessed [here](http://th-mayer.de/cartogram){:target="_blank"}. 

The size of each country is scaled by
the number of languages that are spoken in its territory. 
Each language in the sample is only attributed to one country.
The sample contains [7,293
languages](http://th-mayer.de/data/nrlangs_dahl.txt). Each language is plotted with a small blue dot on the map if the
"Show language locations" option is selected. If you mouse over the (distorted) world map,
you see the number of languages for the respective countries. The cartogram of the world's languages is adapted from
[the cartogram example by Shawn Allen](http://prag.ma/code/d3-cartogram/). 
