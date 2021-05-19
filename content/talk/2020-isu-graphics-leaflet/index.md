---
title: Crash data visualization using leaflet
event: ISU Graphics Group Meeting
event_url: https://isu-graphics.rbind.io/2020/09/crash-data-visualization-using-leaflet
location: Online meeting
summary: Demonstration of the interactive mapping capabilities of the leaflet R package

date: 2020-09-03T16:00:00Z
date_end: 2020-09-03T17:00:00Z

categories:
  - talk
tags:
  - r
  - data viz
  - xaringan
  - leaflet
  - interactive maps
  - crash data
links:
- icon: images
  icon_pack: fas
  name: slides
  url: https://isugg20-crash-viz.netlify.app
- icon: github
  icon_pack: fab
  name: materials
  url: https://github.com/ashirwad/isu-graphics_crash-data-viz
---

In the recent years, RStudio has ported Leaflet, a widely used open-source JavaScript library for creating interactive maps, to R as a package called leaflet and has made it possible to create maps in R using the familiar ggplot2 style syntax. Additionally, a bunch of Leaflet plugins that extend Leaflet's functionalities have also been ported to R by the community members, enabling users to create a variety of maps with ease. In this talk, I will demonstrate the use of the leaflet R package for visualizing fatal crash data for the state of Iowa in many different ways, such as heat maps, choropleth maps, etc. Towards the end of the presentation, I will also introduce some data visualization software such as kepler.gl and deck.gl that support large scale data and provide an intuitive interface for creating geospatial visualizations without any coding.
