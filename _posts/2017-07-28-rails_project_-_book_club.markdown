---
layout: post
title:  "Rails Project - Book Club"
date:   2017-07-28 15:54:31 +0000
---


So I decided to build my app, for a book club, where you can track the books you are reading, add a book - bookmark a book; to pick what page you are up to or have it as complete.
Once book was completed user profile would have a list of currently reading and a list for completed books. 

Users can also add friends so they can easily see their profile via the friendlist and check out what your friends are reading. 

This was the first time I wrote a rspec for a lab, and it was tough, there was a lot of syntax errors. My first couple of tests were actually build in reverse - I build the database and model associations before building my test association, just to get a hang of the idea of building test. 

I have used multiple resources to help me with building test and setting up rspec with capybara. Google and previous labs were my friends. I looked at how the specs were built from old labs and wrote my specs based off of tests I wanted to create and features I wanted to create. 

One of the toughest aspects was building the users have many friends(users) - so it was a table associating with itself through a join table the links a user id to a friend id. I tried multiple methods I have found via googling. I ended up with one that worked, but friends were associating immediately, but I wanted users to have to accept the friend requests, before they were associated. Enter the Class scope method and instance methods that work with this scope to find friend requests. It was tough, but I managed to trudge through it, once one thing started working things started to click into place. 

Both the friends association and the writing of tests took up the most time. Once those were in place, things started to move more smoothly.. and now here I am mission complete. 


