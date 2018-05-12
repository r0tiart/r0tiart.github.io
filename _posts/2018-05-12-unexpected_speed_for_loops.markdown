---
layout: post
title:      "Unexpected speed; for loops"
date:       2018-05-12 15:57:01 +0000
permalink:  unexpected_speed_for_loops
---


I recently read this blog comparing the speeds of different functions that JS has in comparison to for loops and for each loops. It was a pretty interesting read, and for loops out performed everything else in terms of pure speed. The nuiances of efficiency and speed goes a little deeper. 

When thinking of Big O - in actuality it is faster to build a for loop then using pre written functions that JS offers.  Of course there is the time efficiency of going through every single element with in big O, but in fact it can perform marginally better if a for loop takes the place of say a filter function or a map function. It does infact means that function calls take that much extra time to delay the actual loop, since the pre written functions like filter or map all have callback functions before iterating over the arrays. 

When comes to terms on wether to utilize for loops for speed or not. I personally utilize the prewritten functions all the time as there are less pure code involved and it is way more readiable. Big O notation is still the same, but it is in fact slightly slower then a pure for loop. In the end it's all about writting code that is either readiable or possible more efficient? 
