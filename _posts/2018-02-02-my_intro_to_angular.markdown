---
layout: post
title:      "My Intro to Angular"
date:       2018-02-02 15:04:43 +0000
permalink:  my_intro_to_angular
---


So I have decided to continue learning something new and there happens to be an Angular stack within Flatiorn school. So I've decided to dive into it. I haven't gotten super far, but the similarities to React seems marginal at the moment. Instead of building components, containers, actions and reducers; there seems to be only controllers and modules. At first glance controllers seem to be similar to components in React. That is where the bulk of the logic is and instead of having components you input your variable or function directly into HTML using ng-controller, ng-app or ng-click. So far I haven't utilize modules as much, but they are containers for different view, routes and etc. 

At the moment I can't say which is more intuitive, but the basics of Angular is more direct, whatever you want to render - create the controller with a variable for example this.name and in the HTML make sure it is assocatied with that controller and reference the variable <div  ng-controller="ContactController as Contact" >Your name is {{ Contact.name }}</div>

Where as in react you don't have to deal with straight HTML you work directly in your JS component or container and you tell it what to render using JavaScript XML.  The difference is the seperation of languages with React. 
