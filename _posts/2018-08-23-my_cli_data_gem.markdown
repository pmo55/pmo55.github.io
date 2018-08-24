---
layout: post
title:      "My CLI Data Gem"
date:       2018-08-24 03:17:49 +0000
permalink:  my_cli_data_gem
---


I'm going to admit, I was a little bit nervous going into this project.  I am definitely a novice at best programmer, but with big ambitions.  I started this project with the idea of using Rotten Tomatoes website and scrubing the movies that are opening soon.  I planned on obtaining the movie titles and release date and creating a CLI that showed this to the user and allowed them to manipulate that data. 

I started by creating the file sctructure to have an executible program.  Watching Avi's Daily Deals video was a big help in setting that up.  Once I got that out of the way, I decided I would have a MovieScraper class, a Movie class and a CLI class.  I quickly worked through and defined my Movie class,  but then I ran into a problem.  I COULD NOT get the data that I wanted to scrub from the website.  I tried and tried and tried, over days and days.  I began to get frustrated, I tried every css selector I foung on the DOM, and got nothing. What looked like a simple scrubbing solution turned into an impossibility.  I set up a 1 on 1 to get some help but I had to wait a few days.  The wait felt long.

This morning, I decided im going to build out my program and scrape a slightly different website, one that would show the top 10 box office movies of all time. I was a bit uneasy after trying to scrape Rotten Tomatoes, but I was able to scrape and get the data I wanted fairly quickly and painlessly.  I then used a little bit of Regex to make the data look pretty, as there was some loose odds and ends to the text.  After I was able to scrape the site, I worked on iterating through the selectors and creating movie objects containing the necessary variables and data. At this point, 2 out of 3 pieces to the puzzle were complete.

Work on the CLI was a bit more difficult than I had initially expected, but I was able to get it done fairly quickly.  I created a method that listed the movies right off the bat for the end user to see.  Not only did I list the movies, but I placed them in a movies array so I can refer back to them later in the CLI.  Once the user is shown the top ten movies, the user is then prompted to select a movie or type in 'exit'.  From this point, it was just a matter of using if statements and pushing out the right data(from the movies array I created earlier) to the end user. 

All in all, not only was this a great experience, but it was a great confidence builder.  I created a gem from scratch and interacted with git hub and it was wonderful.  I look forward to doing something like this again in the near future.  Back to learning. 



