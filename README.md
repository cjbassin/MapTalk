# MapTalk

- We spend hours making beautiful and informative interactive maps for data analysis and vizualization
- When we go to present our work to an audience, we should be able to use a platform that stays true to the original intent of the visualiztion
- This is my early atempt at making a simple platform to incorporate a map visualization with a talk createed with Mapbox GL JS
- The startegy is that each "slide" is a chapter of information that includes:
 - textual information specific to that chapter
 -  function calls to be performed at the transition of the chapter
    - standard functions like, Zoom, Pan and center
    - calling any other function


## Organization
	### Index.html
		- Main html page with your map
	### all_chapters.js
	    - This file contains a variable all_cahpters which is a json
	###  