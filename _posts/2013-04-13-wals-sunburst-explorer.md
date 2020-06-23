---
title: "The WALS Sunburst Explorer"
description: "Combining areal and genealogical information of the WALS database"
toc: false
comments: true
layout: post
image: images/WALS-sunburst.png
hide: false
search_exclude: true
categories: [visualization, d3js, typology]
---

The *WALS Sunburst Explorer* shows the values for all <a href="http://wals.info" target="_blank"><i class="fa fa-external-link"></i> WALS</a>
features by combining the geolocation of the respective languages with their genealogy in
a <a href="http://www.cc.gatech.edu/gvu/ii/sunburst/" target="_blank"><i class="fa fa-external-link"></i> sunburst visualization</a>
(Stasko and Zhang 2000). The map and the sunburst is enhanced with interactive functionalities.
You can select a region in the world map to get only those languages spoken in that area
displayed in the sunburst. The sunburst itself is zoomable. If you click on a segment, only
the languages of the respective subfamily are displayed.

All data for the <b>WALS Sunburst Explorer</b> (including the genealogical information) has been taken from WALS Online (Dryer and Haspelmath 2013). WALS Online data export created 2013-10-29 23:06:51.451389 from <a href="http://wals.info/" target="_blank"><i class="fa fa-external-link"></i> http://wals.info/</a>. The macro areas are adapted from Dryer (1992).

If you use the <b>WALS Sunburst Explorer</b> in your research, please cite the fourth paper in the References section (Mayer et al. 2014). The <b>WALS Sunburst Explorer</b> is based on the <em>World's Languages Explorer</em>
by Christian Rohrdantz, Michael Hund, Thomas Mayer, Bernhard Wälchli and Daniel A. Keim
(Rohrdantz et al. 2012).

The <b>WALS Sunburst Explorer</b> is implemented in JavaScript using the D3 library (Bostock et al. 2011). The ordinal scale is taken from <a href="http://colorbrewer2.org/" target="_blank"><i class="fa fa-external-link"></i> Cynthia Brewer's colorbrewer</a>.

This work has been funded by the DFG project
<a href="http://paralleltext.info" target="_blank">“Algorithmic corpus-based approaches to typological
comparison”</a> at the <a href="http://www.uni-marburg.de" target="_blank">Philipps-Universität Marburg</a>. 


# Bibliography

Mayer, Thomas and Christian Rohrdantz. 2013. PhonMatrix: Visualizing co-occurrence constraints in sounds. In Proceedings of the ACL 2013 System Demonstration.

Mayer, Thomas, Christian Rohrdantz, Frans Plank, Peter Bak, Miriam Butt, Daniel A. Keim. 2010. Consonant co-occurrence in stems across languages: Automatic analysis and visualization of a phonotactic constraint. In Proceedings of the ACL 2010 Workshop on NLP and Linguistics: Finding the Common Ground (NLPLING 2010), 70–78.

Mayer, Thomas, Christian Rohrdantz, Miriam Butt, Frans Plank and Daniel A. Keim. 2010. Visualizing Vowel Harmony. Journal of Linguistic Issues in Language Technology (LiLT), Vol. 4 Issue 2, 1–33.

Rohrdantz, Christian, Thomas Mayer, Miriam Butt, Frans Plank and Daniel A. Keim. 2010. Comparative visual analysis of cross-linguistic features. In Proceedings of the International Symposium on Visual Analytics Science and Technology (EuroVAST 2010), 27–32.