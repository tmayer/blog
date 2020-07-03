---
title: "Hessen Dialekterkenner"
description: "Aus welcher Region in Hessen kommen Sie?"
toc: false
comments: true
layout: post
image: images/hessen-dialekterkenner.png
hide: false
search_exclude: true
categories: [visualization, d3js, dialectology]
---

![]({{ site.baseurl }}/images/hessen-dialekterkenner.png)

Beantworten Sie 7 Fragen zu syntaktischen Dialektvarianten und ermitteln Sie, 
in welchem Gebiet in Hessen Ihr Dialekt gesprochen wird.

# Information
                                             
© 2012-2014 Michael Cysouw, Jürg Fleischer, Stephanie Leser, Thomas
Mayer<br>
<a href="http://www.hmwk.hessen.de/irj/HMWK_Internet?cid=a2396939885f8c8c0a3ba39bda517cbd" target="_blank">
Landesprogramm LOEWE</a><br> <a href="http://www.syhd.info/" target="_blank">Syntax hessischer
Dialekte (SyHD)</a><br>
<a href="http://paralleltext.info" target="_blank">
DFG-Projekt "Algorithmic corpus-based approaches to typological comparison"</a><br>

Der Dialekterkenner wurde mit Hilfe der JavaScript-Bibliotheken
<a href="http://d3js.org" target="_blank">D3.js</a> und
<a href="https://github.com/mbostock/topojson" target="_blank">TopoJSON</a>
erstellt.
Das Cartogram wird mit <a href="http://stamen.com/studio/shawn" target="_blank">
Shawn Allens</a> D3-kompatibler Implementierung des
<a href="http://lambert.nico.free.fr/tp/biblio/Dougeniketal1985.pdf" target="_blank"><i>Continuous Area Cartograms</i>
Algorithmus</a> von Dougenik et al. (1985) erzeugt. Die Voronoi-Tesselation wurde
mit Hilfe des R-Pakets <a href="http://www.spatstat.org" target="_blank">Spatstat</a> erzeugt.
