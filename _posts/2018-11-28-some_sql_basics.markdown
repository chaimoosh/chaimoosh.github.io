---
layout: post
title:      "Some SQL Basics"
date:       2018-11-28 18:18:04 +0000
permalink:  some_sql_basics
---

The backend of every website contain some sort of data and that data is genrally stored in a SQL database. The way a SQL database works is that there are tables and in those table there are columns and in every column there are rows which have the data stored in them. It's like an excel spreadsheet that you can think of every table as it's own spreadsheet that has rows and columns and each of them. For example if you would have a tabel of cars you would have a column for the id of each car then you would have a column for the year then another one for the make and then anothe one for the model. The next step is that you probably have a few tables in each database and you want them to be able to interact with each other. There are multiple ways to do this and the way you do it really depends on what your needs are at any given time. Continuing on the example from before with the cars let's say you had a list of dealers and each of those cars was by a specific dealer the way you would make that relationship is that you would add a column to the cars table that was called dealer id and every car would belong to a dealer and you would be able to find all the cars from a specific dealer by asking for all the cars with that dealer id. 
