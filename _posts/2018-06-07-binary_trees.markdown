---
layout: post
title:      "Binary trees"
date:       2018-06-07 22:02:32 +0000
permalink:  binary_trees
---


Recently I started to play more with binary trees to try to understand the data structure. This all came about as I was trying to build out a delete function that deletes a given node from the tree. I have manage to successfully delete nodes that either have only 1 child or no childe at all. My only problem is to delete a node with two children. 
I understand the concept of how It should be done - the nodes needs to be replaced by the lowest node (if the node is to the right of the root) or the largest node (if the node is to the left of root). 

I implemented a min and max function that finds the max and min nodes - but only given either the left or right side of the tree. The issue arises in replacing the data. After replacing the data and trying to delete the lowest node it  erases everything under the original deletenode. My thought is that because the tree itself hasn't change, i'm just changing a stored information called "deleteNode" which resembles that of one of the branches of the tree. But when I just change that I'm just changing the variable deleteNode, but not the tree itself... how do I edit the tree? 

Right now i've decided to convert it to an array and just delete the number and rebuild the tree. hopefully that works out well. Right now I have just implemented a tree to array function, but let's see if this route turns out well. 
