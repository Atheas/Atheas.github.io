---
title: "A project that failed"
date: 2019-04-18T15:34:30-04:00
categories:
  - projects
tags:
  - mini-project
  - big-project
  - terradom
---

What I wanted to do was create a website where people can compete in mini-tournaments for specific games. But. There's a lot more into creating a production-ready website.
And what I did is not ready at all for production. I went and leaped straight into the idea of the website existing, but, as I said, there's a lot more to be done for it exist steadily, and I failed to recognise that. 
And so. Here comes the retrospective blogging of the creation of the website.

I will be discussing the features that the website did or does, the past tense is for when if the website is not functional and not being hosted anymore, and it's likely that's the case.

The website consists of the basic features of a typical website plus other features:
- A login page
- A sign-up page 
- A change-email page
- A change-profile page 
- A reset-password page
- A home page where it shows parsed RSS feed from another wordpress website
- A page where you can create the mini-tournaments
- A page where created mini-tournaments are displayed 
- A page where a specific mini-tournament can be viewed in detail 

The backend consists of:
- Celery tasks 
- Processsor for the mini-tournaments 
- Processor for sign-up, login, change-profile, reset-password processes
- And more.

The tools used for creating the website:
- Django 
- Celery Tasks
- Docker 
