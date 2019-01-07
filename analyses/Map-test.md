---
title: "Interactive Map"
output: 
  html_document:
    keep_md: yes
---



Use the leaflet map below to explore the actual Maunga Whau volcano in Auckland, NZ. 


```r
leaflet() %>%
  setView(lng=174.764, lat=-36.877, zoom = 16) %>% 
  addTiles() %>%
  addMarkers(lng=174.764, lat=-36.877, popup="Maunga Whau") 
```

<!--html_preserve--><div id="htmlwidget-c28fc36d09d9a7d48639" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-c28fc36d09d9a7d48639">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"setView":[[-36.877,174.764],16,[]],"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[-36.877,174.764,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"Maunga Whau",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[-36.877,-36.877],"lng":[174.764,174.764]}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

