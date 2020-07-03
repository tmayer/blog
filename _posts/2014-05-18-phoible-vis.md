---
title: "Phoible Visualization"
description: "Combining areal and genealogical information of the PHOIBLE database"
toc: false
comments: true
layout: post
image: images/phoible-vis.png
hide: false
search_exclude: true
categories: [visualization, d3js, typology]
---

![]({{ site.baseurl }}/images/phoible-vis.png)

The <a href="http://tmayer.github.io/PhoibleVis/" target="_blank"><b>PHOIBLE Explorer</b></a> shows the values for all <a href="http://phoible.org" target="_blank"><i class="fa fa-external-link"></i> PHOIBLE</a>
phonemes by combining the geolocation of the respective languages with their genealogy in
a <a href="http://www.cc.gatech.edu/gvu/ii/sunburst/" target="_blank"><i class="fa fa-external-link"></i> sunburst visualization</a>
(Stasko and Zhang 2000). The map and the sunburst is enhanced with interactive functionalities.
You can select a region in the world map to get only those languages spoken in that area
displayed in the sunburst. The sunburst itself is zoomable. If you click on a segment, only
the languages of the respective subfamily are displayed.

All data for the <b>PHOIBLE Explorer</b> (including the genealogical information) has been taken from PHOIBLE (Moran et al. 2014). The macro areas are adapted from Dryer (1992).

If you use the <b>PHOIBLE Explorer</b> in your research, please cite the third paper in the References section (Mayer et al. 2014). The <b>PHOIBLE Explorer</b> is based on the <em>WALS Sunburst Explorer</em> (<a href="http://th-mayer.de/wals/" target="_blank">http://th-mayer.de/wals/</a>) and the <em>World's Languages Explorer</em>
by Christian Rohrdantz, Michael Hund, Thomas Mayer, Bernhard Wälchli and Daniel A. Keim
(Rohrdantz et al. 2012).

The <b>PHOIBLE Explorer</b> is implemented in JavaScript using the D3 library (Bostock et al. 2011). 

The visualization has been funded by the DFG project
<a href="http://paralleltext.info" target="_blank">“Algorithmic corpus-based approaches to typological
comparison”</a> at the <a href="http://www.uni-marburg.de" target="_blank">Philipps-Universität Marburg</a>. 

# Bibliography

Bostock, Michael, Vadim Ogievetsky and Jeffrey Heer. 2011. D3: Data-driven documents. <i>IEEE Transactions on Visualization &amp; Computer Graphics</i> (Proc. InfoVis), 17(12), 2301–2309.

Dryer, Matthew S. 1992. The Greenbergian word order correlations. <i>Language</i>, 68(1), 81-138.

Mayer, Thomas, Bernhard Wälchli, Christian Rohrdantz and Michael Hund. 2014. From the extraction of continuous features in parallel texts to visual analytics of heterogeneous areal-typological datasets. In Nolan, Brian and Carlos Pascual-Periñán (eds.),&nbsp;<em>Language processing and grammars: The role of functionally oriented computational models</em> (SLCS) (Serie: Studies in Language). Amsterdam: John Benjamins, 13-38.

Moran, Steven, Daniel McCloy and Richard Wright (eds.) 2014. 
PHOIBLE Online. 
Leipzig: Max Planck Institute for Evolutionary Anthropology. 
(Available online at http://phoible.org, Accessed on 2014-09-30.) 

Rohrdantz, Christian, Michael Hund, Thomas Mayer, Bernhard Wälchli and Daniel A. Keim. 2012.
The World’s Languages Explorer: Visual analysis of language features in genealogical and areal
contexts. In <i>Computer Graphic Forum</i>, 31(3), 935–944.
[<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-8659.2012.03086.x/abstract" target="_blank"><i class="fa fa-external-link"></i> link</a>]

Stasko, John and Eugene Zhang. 2000. Focus+context display and navigation techniques for
enhancing radial, space-filling hierarchy visualizations. In <i>Proceedings of the IEEE Symposium on Information Visualization</i>, 57–65. Los Alamitos CA: IEEE Computer Society.