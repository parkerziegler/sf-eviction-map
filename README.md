# Eviction in San Francisco (1997-2015)
An interactive map built on CartoDB.js to provide multiple visualizations of the geography of eviction in San Francisco, CA.

This map was produced as part of my senior research in Geography at Middlebury College. To read a more in depth report of how I made this map, check out this post from my website: http://parkerziegler.com/senior-research-programming-for-gis/2016/5/19/project-7-build-a-map-of-eviction-in-san-francisco-using-cartodbjs-or-how-to-make-a-map-you-believe-in. Or better yet, take a peak at the code!

A few cool features of this map:
– Integration of Torque layers with static CartoDB layers using jQuery buttons. Note: this does involve destroying and recreating the Toruqe layer on button clicks. I would love any suggestions of how to do this more elegantly.
– Custom legends and infowindows using Mustache templates. Check out Daniel McGlone's post on this at: https://www.azavea.com/blog/2015/09/09/making-custom-infowindows-and-legends-in-cartodb-editor/
