# Eviction in San Francisco (1997-2015)
**An interactive map built on CartoDB.js to provide multiple visualizations of the geography of eviction in San Francisco, CA.**

This map was produced as part of my senior research in Geography at Middlebury College. To learn more about how I made this map, check out [this post](http://parkerziegler.com/senior-research-programming-for-gis/2016/5/19/project-7-build-a-map-of-eviction-in-san-francisco-using-cartodbjs-or-how-to-make-a-map-you-believe-in) from my website. Or better yet, take a peak at the code by checking out the index.html file.

A few cool features of this map:
* Integration of Torque layers with static CartoDB layers using jQuery buttons. This does involve destroying and recreating the Torque layers on button clicks.
* Custom legends and infowindows using Mustache templates. Check out Daniel McGlone's post on how to do this (here)[https://www.azavea.com/blog/2015/09/09/making-custom-infowindows-and-legends-in-cartodb-editor/].
