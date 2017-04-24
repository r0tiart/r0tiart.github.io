---
layout: post
title:  "Ski Resort Status - CLI Gem Project"
date:   2017-04-24 16:51:00 +0000
---

Every winter, the process restarts. The process of looking for that ski resort that is both open and just got hit with lots of snow. I was introduced to the sport of snowboarding back in highschool and although thrilling was not yet my passion as I got injured on the mountain. 

Years down the line, I picked it back up again and boy was it thrilling. Now I go every winter, and http://www.onthesnow.com/ is checked frequently throughtout the snow season. So for my Ruby CLI Gem project I've decided to build a scraper that would scrape the snow status page on http://www.onthesnow.com/ 

<img src="https://www.snowskool.com/uploads/files/Snowboarding_Switch.jpg" alt="snowboarding" />


To start off my project, I read the entire readme and watched all the videos under the resource section - while writing notes on what I wanted to see. The Resources definitely helped me. There were some good tips on starting / building a Ruby Gem, like bundle gem. While working on the actual codes, I've frequently referenced back to either google search or one of the resources that was provided. 

At the begining, it was pretty daunting building something from scratch. However I kept a notes doc to help me along (recommended from one of the resoure videos). As I coded, what I wanted to output didn't make sense and I had to adjust to what was available. Originally I only wanted to scrape US ski resorts, but I ended up building one that should be able to scrape all they have available. However I only scraped for Canada and the United States. 

There were so many iterations of the each class and how they interconnected before I even gotten to the scrapping. Since I was building from CLI interface in, every time I added a new method or any other functionality I would have to open the console and test the outputs of my CLI to make sure everything was working. It was a slow process of build - test - debug - implement fixed - test; until it eventually worked and I can move on to the next element in my code. 

When I finally got to the actual scraping, it was the same process, but instead of testing the entire CLI, I was testing each scraped item. The data I was trying to get was within a Table, and each element did not have a unique class so it took a lot of playing around to get each element. When I finally thought I got every single line in the table - testing for the first and last elements within the Nokogiri doc, it crashed when trying to build my Resorts class. 

Everytime I tested an element I would save it in my notes on how to pull it. After many attempts I finally managed to make it pull correctly. The entire scrape - create Objects and associating each other was working, but my CLI wasn't... My menus were not working properly and displaying properly. 

In the end, everything finally worked and displayed correctly. My code can be neater and I'm sure there are things I could've made more efficient and put some things elsewhere. But all in all I'm pretty proud of the work I did. It may have took some time to complete, but it worked out. 