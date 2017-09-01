---
layout: post
title:  "Rails App with a jQuery Front End"
date:   2017-09-01 19:20:23 +0000
---


Picking up where i left off from my origina Rails App project and creating a front end enviornment - utilizing AJAX get and post requests. Since my original project had only 2 types of forms - to create a new user and one to create a new book and adding said book to your library, i have implented the frontend request primarily on books.

The development process took a lot of "dubugger;" or alert("hijacked"). Firstly i would add an id or a class to my html objects and test the hijack of .on("click"). It was a step by step process from getting an alert to know am in that particular event and debugging and console.log to figure out where I was or what I was using. 

One issue the arose was that rendering the form for a new book on the user profile page. the JS needed for the form to work has already been loaded when the page was loaded. So i found the $.getScript() method which helped me rerender the script without reloading the page. 

There were a couple of other functions that i had to find, like .show() and .hide() so i can make you choose the option to create or select a new author or genre. 

There was a lot of trial and error to figure out if I'm getting the correct element and that I am in the correct "this" for example one of my event listeners is bound to a button - but i had to obtain the data of the form - so i utilized the this.closest("form") to locate the form of the submit button to find all the data fields.


