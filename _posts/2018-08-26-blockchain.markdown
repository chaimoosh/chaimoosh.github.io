---
layout: post
title:      "Blockchain"
date:       2018-08-26 21:26:50 +0000
permalink:  blockchain
---


Blockchain is what's behind bitcoin and all other cryptocurrencies and here's a brief overview of how it works. The basic idea is that there has to be some way to keep everything secure. The way this is done is that you make it that every elemet has a hash that is almost impossible to hack. The way this is done is SHA256 which takes data and makes a hash out of it but if even the slightest thing changes in the data the hash that's made is completely different. So first every element has a hash based on the data inside of it. Next what you do is you make every element know about the previous element by storing the previous hash inside of it. Now if you try to change anything within any of the elements on the chain you mess up the entire thing because you change the hash of that element and then if you check it against what's in the next element it will show that the data was corrupted. Another way the data is kept secure is by having copies of the database with all the blocks in them stored in multiple places and every time a change is made it updates everywhere and the if anyone tries to corrupt the data in one the other ones will show that it was played with and it will be stopped.
