---
layout: post
title:      "Sinatra Portfolio Project"
date:       2018-04-20 15:13:44 +0000
permalink:  sinatra_portfolio_project
---

I just finished the sinatra project and boy does it feel good. It's so nice to get to see that all the work that I'm putting in is really turning out to be something. I started this project by trying to come for an idea for ssomething that would work for this. To get some inspiration I decided to go outside for a walk. As I was walking something caught my eye and I was like I should do something about that. It was a car. 
I tried to think what could I make with my new knowledge of sinatra that had to do with cars. I threw around a few ideas and I decided the best way to go would be to just make a web app that could keep track of someones cars. So there I was starting the project. I took alot of the structure from other things that I had done previously so that was not that hard to set up.
Next I started to build out the functionality of the app. I put in a controller for users and set up the users with a username and secure password. The next thing was getting the car part to work. I ran into issues because I was having the users after they sign up go straght to their list of cars but they weren't putting in a car when they signed up. So I changed that it wouldn't break if you didn't put in a car. I also made it that in order to sign up you need to add a car to the database first. The last step was getting the index page to work because fro some reason it wasn't listin all the cars. I got some help for this and realized that I was searching for them wrong. I was looking through cars using th find_by method which just returns a single instance and not an array. This was the wrong way to look for it because I needed an array so I'd be able to iterate through it on the index page. I fixed this by finding cars based on the user because the user has many cars and then that worked fine.
The last thing I did was add flash messages that way when you interact with the site you would know what's going on. I was told me about this and showed the sinatra flash message options. I added a few messages in different places and then i was good to go.


