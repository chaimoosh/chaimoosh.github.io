---
layout: post
title:      "Public, Private, and Protected"
date:       2018-11-22 09:56:09 -0500
permalink:  public_private_and_protected
---


In Java when declaring a variable there are three specifiers you can choose from in deciding how that variable can be changed and where it can be changed. When you declare a variable in a class and you want to be able to access that variable in any other class directly and not through a setter or getter method you declare it public. If you want a variable to be accessible in child classes then you declare it protected and then you can access it directly in all child classes but not in any other class. If you want a variable to only be accessible in the class it's declared and not be accessible anywhere else in the program then you declare it private. Generally it's best practice to not let your variables be manipulated in any place where it's not absolutely neccesary so when you're able to declare it private you do and if not declare it protected and you use setters and getters to change it.
