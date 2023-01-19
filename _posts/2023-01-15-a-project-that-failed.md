---
title: "A project that failed"
date: 2023-01-15T15:34:30-04:00
categories:
  - projects
tags:
  - mini-project
  - big-project
  - terradom
---

What I wanted to do was create a website where people can compete in mini-tournaments for specific games. But. There's a lot more into creating a production-ready website.
And what I did was not ready at all for production. I went and leaped straight into the idea of the website existing, but, as I said, there's a lot more to be done for it exist steadily, and I failed to recognise that. 
And so. Here comes the retrospective blogging of the creation of the website.

I will be discussing the features that the website did or does, the past tense is for when if the website is not functional and not being hosted anymore, and it's likely that's the case.

The website is https://terradom.io, it might not be functional by the time you're reading this, just note that.

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
- Celery tasks.
- Processsor for the mini-tournaments.
- Processor for sign-up, login, change-profile, and reset-password processes.
- Processor for email notifications.
- And more.

The tools used for creating the website:
- Django 
- Celery Tasks
- Docker 
- AWS
- WinSCP
- Terminal
- Atlassian Jira for management of addition of new features, code changes, et cetera
- Notion for attempted team management, but all the time I was solo-devving Terradom.io

Overall, I played with a lot of tools and used few coding languages such as Python, CSS, HTML, Javascript.

Below this would be a collection of screenshots showing the website, right-click and open the image in a new tab to see more clearly.
---

The sign-up page:
![The sign-up page](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_222656_terradom.io.png)

The login page:
![The login page](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_222343_terradom.io.png)

The profile page:
![The profile page](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_223018_terradom.io.png)

The create-mini-tournament settings page:
![The create-mini-tournament settings page](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_221904_terradom.io.png)

The create-mini-tournament advanced settings page:
![The create-mini-tournament advanced settings page](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_221932_terradom.io.png)

The home page with posts from a wordpress website:
![The home page with posts from a wordpress website](/assets/images/perpost/a-project-that-failed/Opera Snapshot_2023-01-14_221354_terradom.io.png)

The administrator page:
![The administrator page](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-15 203124.png)

List of mini-tournament posts:
![Mini-tournament posts](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-15 202802.png)

Mini-tournament in detail, in the eyes of a NORMAL user:
![Mini-tournament posts](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-15 203848.png)

Mini-tournament in detail, in the eyes of a LOGGED-OUT user:
![Mini-tournament posts](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-15 202913.png)

Mini-tournament in detail, in the eyes of an ADMIN user:
![Mini-tournament posts](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-15 203214.png)

---

How I used Atlassian Jira:
![Mini-tournament posts](/assets/images/perpost/a-project-that-failed/Screenshot 2023-01-19 210103.png)

---




