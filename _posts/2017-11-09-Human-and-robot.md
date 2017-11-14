---
layout: post
comments: true
title:  "Human.txt and robot.txt"
date:   2017-11-07 10:00:42 +0100
categories: Blog post
---

### Robots.txt
Web site owners use the robot file to give instructions about their site to we robots, this is called The Robots Exclusion Protocol. The way it works it that when a robot whats to visit a Web site URL it checks for http://www.example.com/robots.txt and finds out what its allowed to visit on the site and not. The way I have configured my robot.txt is that I have disallowed robots from visiting any of my pages on the site.

```
User-agent: *
Disallow: /cgi-bin/
Disallow: /tmp/
Disallow: /~joe/
```

### Humans.txt
Humans is an initiative for knowing the people that are behind the website you are visiting. Its quite simple, its a text file that contains information about the different people that are behind the site and people that have contributed to building the website. The way that I have configured it on my site is that I have a chef which is me, I have my email there if someone wants to contact me about anything and then I have where i originally come from. 

```
Chef:Filip Mylläri
Contact: fm222hp@student.lnu.se
From:Mönsterås, Sweden
```
