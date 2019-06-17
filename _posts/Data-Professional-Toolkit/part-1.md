---
title: Designing a Flag
image: /assets/images/shubham-beeharry-223969.jpg
author: Dan Thompson
categories:
    - work
    - projects
layout: post
---
I keep having meetings with people where I'm certain there are other data platform options that could be used to process/store data much more efficiently, but I'd like to be able to spin up a little test rig to prove/disprove that theory. So I was thinking the other day, wouldn't it be great to have a place where I could spin up pretty much any data platform I wanted to. This blog post will show you how to spin up an environment where you can do just that.

# What you'll need:
- msdn account (activated with Azure so you can use your msdn Azure credit!)
- (or) a Linux VM hosted somewhere for you
- A bit of time

# Outcome:
- An environment where you can spin up temporary instances of data platforms, like:
    - SQL Server
    - MongoDB
    - Casandra
    - MySQL
- Some great resources for further reading

# Disclaimer
I read a lot of random articles, and some of them are a bit bias so I thought it would be relevant to let you know I'm pretty much a SQL Server DBA, that's my background - SQL Server, MongoDB, MySQL and Oracle. But in particular SQL Server for the last long while. For this blog post though, we're pretty neutral - its Linux based with some data platforms spun up and losely configured.

# Linux?
Yeah... Wouldn't it be great to have a world where everything could run on the same platform? You could just learn one thing and how it interacts and then spin up whichever database platform you liked based on the use case? I really think the future is Linux for that and this toolkit makes the most of that idea.

