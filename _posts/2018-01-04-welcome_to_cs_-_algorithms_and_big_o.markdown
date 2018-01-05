---
layout: post
title:      "Welcome to CS - Algorithms and Big O"
date:       2018-01-05 02:45:15 +0000
permalink:  welcome_to_cs_-_algorithms_and_big_o
---


I have decided to work on the CS stack to learn more about algorithms and Big O. It's definitely a new experience, something that I will need to continue to work on. Currently I'm near the end of the stack with the last remainder two labs; however the first of the 3 last labs took me a while to accomplish and took a lot of going back and forth into the lab. I'm definitly not comfortable with hash tables, merge sorts and etc. yet. There are different things I can accomplish with it, not just sorting but finding speicifc entries. To clarify the last lab I did was the two sum problem.

I'm defintely a more hands on type of learner, just reading the text was not going to cut it, so redoing some of the labs will defintely help. There is one problem a buddy of mine asked me if I can do ( he recieved this question as a technical interview question). 

Given two arrays full of icecream flavors 
- array_1 = [ chocolate, vanilla, strawberry, coffee ] // order
- array_2 = [ vanilla, chocolate, vanilla, coffee, strawberry, coffee ] // icecream sold.
Sort the second array based off of the first array. 

I was thinking I can hash map the first array:
function hashMap ( array1) {
    let hash = {}
		
		for ( let i = 0; i < array1.length; i++) {
       hash[array1[i] = i
  };
	return hash;
}



So the above would return a hash of:
{ chocolate : 0,
  vanilla: 1,
	strawberry: 2,
	coffee: 3
}

Then i would split the second array to indvidual arrays and do a merge sort using the hash as a key.
I haven't put it into testing yet, but that was my general idea. I believe I need to go over the CS - algorithms stack once more to have a better grasp of things. 
