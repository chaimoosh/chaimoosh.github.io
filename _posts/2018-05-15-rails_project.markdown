---
layout: post
title:      "Rails Project"
date:       2018-05-16 00:54:58 +0000
permalink:  rails_project
---


So now I'm doing the rails project which is tuning out to be a big challenge. When i was doing the sinatra project I found it much easier because sinatra is easier and has less details moving around. In rails everything is in different places which can make it much hrder to debug.
When thinking about an idea for the project i decided on an app where users could book appointments with a hair stylist.
I would need a user model an appointment model and a service model. Getting that started was the first challenge to figure out how they would relate to each other. After a few tries I settled on a user having many appointments and having services through the appointments. The appointment table besides having a time would also serve as a join table between users and services. 
The next step was taking this and building out the controllers and views. Building the user model was easy enough I made a signup page and a link to sign in with google. The next step was building the services controller and views so when the appointment model was built it would have services to choose from. I built that out and made full crud actions for it.
Well after all this I just needed to do the best part cleaning it up and making it nice. It wasnt the biggest deal and it went well over all.

