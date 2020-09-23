---
layout: post
title:      "Recipe Pick - Single Page Application"
date:       2020-09-23 03:44:37 +0000
permalink:  recipe_pick_-_single_page_application
---


## Introduction
---
I will be honest, I came into this project with a big head. I really thought javascript was going to be easy. I was finally understanding some of the more complicated logic relating to Rails and Ruby. It didn't take long for me to realize how wrong I was. Topics like hoisting, asynchronous events, etc. These topics weren't too hard to understand but to implement was a different story. 

*Hoisting* happens in the first run of the code, this is where Javascript runs through your code once and stores your functions and variables. Then it executes the code after that. After trying to figure this out, began to really appreciate Ruby and Rails. I never had to think about when something will run in Ruby, it just ran as it showed. But **JavaScript**, was not having it. It was probably hour 40 or 50 when I finally started to get the hang of things. Being able to store functions inside variables is ingenious. I've never appreciated functions like I did now.

## Functions
---

Maybe its just me, but I find this very satisfying.

![Image of some JS](https://imgur.com/GTo0rWZ.png)

I will admit that maybe I have some questionable IDs up there. But being able to put all my elements in one place to reference later was one of the most satisfying things that I learned JS can do. 

## Recipe Picker
---
As for the actual website, it took me a long time to figure out what I wanted to do for my project. I ended up creating a Recipe Picker. The idea came to me when I was deciding what to cook for dinner. Thats how I decided to get started. I ran into many hurdles trying to figure out how to use the [spoonacular api](https://spoonacular.com/food-api), once I figured that out I had to decide how I was going to implement that into my own website. After hitting my head against my keyboard a few times I was able to get a working version of my website. The only problem was that I wanted to implement a user interface. Normally I could just use rails and [bcrpt](https://github.com/codahale/bcrypt-ruby), or even [devise](https://github.com/heartcombo/devise) to be able to do that. Unfortunately it wasn't going to be that easy with a single page application. Since I didn't want to implement a refresh into the app, It took me a long time to figure out how to do user authentication. At one point I contemplated just giving up and trying again. Like I had to do last lab. Luckily I didn't I found a way to do it using a var rather than a const or let. This var stored the user id after signing in. This allowed me to set up nested routes inside the post request for the rails backend. In this single page application I am actually using my own backend to save users and recipes. But storing the recipes using the spoonacular api. This was a pain in the neck to implement but after I was able to accomplish it, I started to feel proud of what I had accomplished. The more I got used to using JavaScript Object Orientation the more ways I found to refactor my code. Then it became fun messing with different fetch requests and sending data back and forth. 

## Completion 
---
Once I finally got a final product working as expected, I had fun changing and reformatting the code. I tried to use a Mcdonalds theme mixed with a Checkered background. Although I had my website finally working, I couldn't help but think that I probably could of done better. Now that I finally got comfortable with messing with JavaScript, I couldn't shake the need to try to start from scratch. In the end I decided to accept what I had for the moment, but I am really excited to see how much more I improve in the next few months. I want to come back to this project and try to remake it again. 


