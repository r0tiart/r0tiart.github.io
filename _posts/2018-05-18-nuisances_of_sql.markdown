---
layout: post
title:      "nuisances of sql "
date:       2018-05-18 14:35:38 +0000
permalink:  nuisances_of_sql
---


I recently had a coding challenge and wanted to share my thoughts. I was working with a SQL query and my original answer invovled joining two seperate queryies to create a new table where something that was 'checked out' is not 'commited'. After the actual challenge I decided to take it upon myself to implement it to see how well it does; in thought it was sound - you want things that are "checked out" but not "commited" so it would make sense to have one not in the other. 

In thought the question seemed more complex, and I decided to utilize what I've learned in flatiron via math/logic testings to solve it on my spare time after the challenge. I ended up also creating a subquery, but this time it utilizes math logic to determine wether or not the item shows. I've even built out a table and crafted two different scenarios where something was just checked out and another that is commited - i've tested both and the query seems to be working. You can find my sql here http://sqlfiddle.com/#!9/4c99f5/48  . 

The power of math is strong, and I'm wondering what else I could do with it. There is so much to explore still #learningeveryday. 

