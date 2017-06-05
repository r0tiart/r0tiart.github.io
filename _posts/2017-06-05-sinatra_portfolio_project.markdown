---
layout: post
title:  "Sinatra Portfolio Project"
date:   2017-06-05 21:39:24 +0000
---


I decided to build my project on the collection of games. I have some thought on what i wanted to do and had that written down on the side. I started off by setting up all the directories and gems that i needed. After the initial set up, i started out building migrations and models afterwards with associations.

Most of my time was spent on the application controller and each view. I decided i wanted to do a sluggable - to display the actual game name / character name or username versus their respective ID. because i decided to do sluggable i made it so usernames had to be unique. With every section being built something had to be edited in the other sections. 

Primiarly I was building one page as a stand alone, making sure my initial controller get or post and the respective view was working on it's own. I had to go reiterate on past sections as I started linking them to each other. For example after I included the characters page - i realized my it - was just showing the user that had been logged in and i could not see other peoples characters - so I went back and refractor my code so that the show character view and the controller that loaded the view - would note who the current_user was along with who the profile belonged to.

The toughest part was going back and refractoring and making sure everything worked accordingly when i started to link it. As on ocassions something would break or I had to edit the url so that i could get more information to show and compare.


