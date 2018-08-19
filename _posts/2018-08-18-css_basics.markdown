---
layout: post
title:      "CSS Basics"
date:       2018-08-19 02:57:14 +0000
permalink:  css_basics
---


CSS is what makes the internet look pretty. All the colors and styles on any web page are all CSS. So just to go over some of the imprtant stuff to always remember when writing CSS code. The first thing is to remember what takes precedence because sometines an element can have a style from different places and only one will render. The problem is that there are some weird rules about this. The first thing is the !important tag anything you put this on will take precedence but it's considered bad practice because it can be very confising to change. The next is an inline selector like <p style...>. After that are styles that are defined through media queries. Next are user defined styles which are atyles that a user can select in the browser. After that is selector specificity that the more specific a selector is to an element that is the one that takes precedence over the one that's more general. Then goes the rule order that the last style written takes precedence. And then lastly there are browser defaults. 
