---
layout: post
title: Choosing the Right Basemap for Historical GIS Projects
tags:
- GIS
- digital humanities
- Google
- tools
- maps
- history
---

I've been looking at a lot of digital humanities GIS projects lately, both to learn from past approaches, and to see what they have in common with journalistic GIS and mapping projects. The (very official sounding) GeoHumanities Special Interest Group of the Alliance of Digital Humanities Organizations attempts to [maintain a catalog of such projects](http://geohumanities.org/gis) (originally seeded from [John Levin's *Anterotesis* blog](http://anterotesis.com/wordpress/mapping-resources/dh-gis-projects/)).

There are undoubtedly some impressive projects on the list, but a number of these sites left me underwhelmed. It felt like too many projects didn't really use GIS in any way beyond plotting some points (and much, much less often, lines and shapes) on a default Google map. Part of this disappointment is simple hindsight bias--the rapid improvement of web-based mapping technology has made ith hard for these projects to age gracefully. We certainly have many more (and more sophisiticated) GIS tools available now than in the early 2000's, when some of these projects were created. I understand that at the time they were created, Google Maps and Google Earth made online maps much easier to produce, and potentially empowered some digital scholarship that would have otherwise been less accessible.

But that ease of use came with several tradeoffs. As I thought more about why some projects were more successful than others, I realized that one big difference was whether (or not) researchers chose an appropriate basemap, the visual and spatial context that sits behind the data. A basemap is too important to be left up to the default settings. Here's why:

## The Familiarity Problem

Readers are very familiar with the default Google street map. It's what we use to plot our route from an airport to a hotel, or to navigate to a store or restaurant for the first time. So when we are confronted with this familiar interface, it's hard to resist falling into our learned navigational mindset, and even harder to see the same familiar map with a historic eye. For some viewers, the familiarity might seem comforting, potentially making the scholarship more approachable. But for others, including myself, it makes the work seem less scholarly.

## Maps Encourage Spatial Comparisons

The whole point of placing points, lines, and shapes on a map is to be able to visualize their spatial relationships--not only between themselves, but also in relationship to the basemap features. The problem with using a default basemap is that researchers have no control over which features are included, how they are labeled, or how they are depicted.

Maps are never neutral, and by selecting a basemap, the researcher is unintenionally absorbing its cartographer's biases. From this perspective, most modern basemaps seem to be obsessed by roads. Look at how they visually dominate this map of historical Irish barracks:

![barracks map screenshot]({{ site.url }}/images/barracks.png)


## History is a Foreign Land

Ideally, historic mapping projects should help transport us to a different time and place. This can be acheived in Google maps by using hisotical maps as a layer between the basemap and the data. A good example of this approach is the [Digital Harlem](http://digitalharlem.org/) project, where the Bromley Fire Risk Maps are overlaid on top of the modern street map. This serves a dual purpose, both providing a historic spatial context and highlighting the area of interest (outside of Harlem, like across the river in the Bronx, the modern basemap remains visible):

[![screenshot of Digital Harlem map and interface]({{ site.url }}/images/harlem.png)](http://digitalharlem.org/)

An even more effective example is found in the [imagineRio](http://imaginerio.org/#1603/16/-22.901794649394187/-43.17330837249756) project. Here, an interactive timeline let's you see the state of the city at any year in its development. As roads and buildings are built, they are added to the map. But importantly, the map starts blank, and labels are only added at the point in time in which they are named.

[![screenshot of imagineRio map and interface]({{ site.url }}/images/rio.png)](http://imaginerio.org/#1603/16/-22.901794649394187/-43.17330837249756)



