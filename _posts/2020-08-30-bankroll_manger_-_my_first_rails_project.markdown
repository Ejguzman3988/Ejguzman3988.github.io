---
layout: post
title:      "Bankroll Manger - My first Rails Project"
date:       2020-08-30 20:38:16 +0000
permalink:  bankroll_manger_-_my_first_rails_project
---


## Introduction
---
Like all great stories, in the beginning everything was looking up. I had a full week to get started on my project, I finally got an idea of what I wanted my rails project to be. I decided to make a poker [Bank Roll Manager](https://github.com/Ejguzman3988/bankroll-manager). I organized my thoughts, put them on paper, and got ready to code. 

## The Lead-Up
---

I have been an avid poker player for a few years. So I would track my bankroll with an excel spreadsheet. That looks like this:

![Image of Execel spreadsheet](https://i.imgur.com/SSManTv.png)

By doing it like this I was able to build a bankroll and play poker profitably. Eventually the spreadsheet became inefficient at tracking large numbers of tournaments. There were just certain things I couldn't do with this style of tracking. This is what spawned my idea to make the bankroll manager. 


## The Start
---
I began by organizing my ideas and filled out a table that described the architecture of the project.

![Image of Model Relationship](https://i.imgur.com/sB0Qgdf.png)

As you can see above. I decided to go with five models. User, Game, PokerSite, Tournament, and CashGame. I even used a polymorphic relationship so that I can make a game model have just one type of model. At this point I felt really good about the project, all that was left was getting started. 


## The Process
---

I was able to start off well and I created my own rails project with no problems. I added devise for user log in and then added the rest of the relationships. I was able to get the polymorphic relationship to work and every seemed good and dandy. But I began to realize that the set up of every single relationship was too complicated for me. I started running into problems setting up the logic and views for each game. I realized that this could be easily solved by just making three models. A user, join table, tournament. By doing this I could keep the logic simple and scale it afterwards. 

## Realization
---
So after spending most of my week trying to make the website work from my original idea. I ended up deciding it would make more sense to start over. Although it hurt to give up on so much work I got to a point where I couldn't move forward, and found a solution where I could just get the basics down. 

I think I learned a very valuable lesson about the architecture of code. I got a bit too overconfident and tried too add too many features when all I needed was a simple poker tracker. 

## Starting over


One of the good things about starting over was that I already did most of the heavy-lifting. Since I already spent all time working on the previous project I didn't have to spend time making the same mistakes as I did on the first run through.

I finally got to a point where I got the basics of my website working and now I can finish this project and get ready to learn more.


The content of your blog post goes here.
