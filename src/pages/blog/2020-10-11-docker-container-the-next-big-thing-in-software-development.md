---
templateKey: blog-post
title: "Docker container: The next big thing in Software Development"
date: 2020-10-11T21:36:26.211Z
description: Now you get it! The most versatile, modern and rich software
  development environment ever. Give it a sneak peek! See what you can do with
  Docker containers. Subscribe and follow me in the next posts.
featuredpost: false
featuredimage: /img/docker-container-software-development.jpg
tags:
  - Docker
---
![](/img/large_v-dark.png)

Here we go! We’ve just reached the last post of a series of four! In the previous posts, among a bunch of cool stuff, you were [presented to Docker container with all the benefits it brings](https://shareisthekey.com/2020/09/03/docker-container-software-development-1-4/), learned [how to set up the best software development environment ever](https://shareisthekey.com/2020/09/13/docker-container-software-development-2-4/) and started [playing with eShopOnWeb](https://shareisthekey.com/2020/09/30/docker-container-next-big-thing-in-software-development-3-4/), a Microsoft sample web application using ASP.Net Core. To follow the instructions below, I recommend the reading of all previous posts. There are precious instructions and pre-requisites to follow some of the next steps.

Now let’s take eShopOnWeb to another level. We will build a SQL Server 2019 image and run a container so that eShopOnWeb can persist data.

First, to accomplish this task, we will choose an already built image of SQL Server 2019. We always recommend you use official docker images from all vendors or communities that support their products. Many of them publish and maintain their images updated. Go to [dockerhub.com](https://hub.docker.com/), fillup the search field with **SQL Server** and hit Enter.