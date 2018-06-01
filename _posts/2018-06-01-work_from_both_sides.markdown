---
layout: post
title:      "Work from both sides"
date:       2018-06-01 15:56:12 +0000
permalink:  work_from_both_sides
---


Recently I had a technical interview involving strings and reversing the letters in a string. So given a string that can contain multiple words, reverse each word but leave the punctuations where they are at. As I was working through it, I was doing it one at the time, but the interviewer gavea great suggestion what if you work from both ends? 

..This was actually not the first time i've heard this, it feels like if a problem requires to work with the begining of the string or array and the end of it, it does make sense to work on both ends to solve it quicker. There are some other algo structures that are useful that I wouldn't originally think about, like finding if a linked list is connected or is it in one direction... think about it how does one do it? This was actually a problem presented to me by one of my buddies. I tried multiple scenarios, but he would say close and say there is a trick to it, but once oyu know it you can't unknow it. That was... drum roll please, to go at the linked list twice, so the first run through will go through it individually one item to the next. The trick is the second one runner is going every other so they are returning every other value vs the first is only returning the next value everytime. The idea is that if the 2nd runner hits a null for next value we know it's not true, but if it eventually meets up with the first runner then it is indeed a loop. #themoreyouknow
