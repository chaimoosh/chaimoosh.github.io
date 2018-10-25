---
layout: post
title:      "Javascript Closures"
date:       2018-10-25 17:24:00 +0000
permalink:  javascript_closures
---


In Javascript one of the things you come across is a closure. The idea of it is that you have variables throughout your program but you don't want all your variables to be accesible everywhere because that can lead to strange bugs that are hard to trace like if you tyr to declare a variable that has already been declared or change a variable that was declared with const so in order to avoid that you make a closure. The way to make a closure is that inside any function that function has access to everything that was declared outside of it and anything declared inside of it but the ones that are declared inside of it can only be accessed by that function and not anywhere else in the program. So by declaring a variable inside a function you create a closure because it cannot be accessed outside of that function. 
