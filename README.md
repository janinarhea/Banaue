# Banaue
Map generated by leaflet

Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 @janinarhea
Sign out
 Watch 0
 Star 0  Fork 0 janinarhea/Banaue
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Insights  Settings
Branch: master Find file Copy path Banaue/map.Rmd
4f63b29  2 minutes ago
@janinarhea janinarhea Add files via upload
1 contributor
RawBlameHistory    
25 lines (19 sloc)  547 Bytes
---
title: "8th Natural Wonder of the World"
author: "Janina Lazo-Cruz"
date: "January 12, 2019"
output: html_document
---

```{r setup, include=FALSE}
library(knitr)
library(leaflet)
knitr::opts_chunk$set(echo = FALSE)
```

## Banaue Rice Terraces

This is a map that shows the location of Banaue Rice Terraces in the Philippines. 


```{r banaue}
BRT <- c("<a href= 'http://www.banaueterraces.com' >Banaue Rice Terraces</a>")
leaflet() %>%
addTiles() %>%
addMarkers(lat=16.935385, lng=121.05762, popup = BRT)
        
```
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
Press h to open a hovercard with more details.
