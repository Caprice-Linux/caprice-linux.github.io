---
layout: post
title: Caprice Linux 1.0-BETA Release Notes
---

In past few months, the Iranian FLOSS community and I worked on this project. A lot of friends, a lot of enthusiasts and even a lot of people who were attracted to the open source and free software, joined us in this journey. 

So for now, I'm pleased to announce that the very first beta release of Caprice Linux is here. In this post, we review what happened, what's new in Caprice Linux and why you should use Caprice Linux. 

## Development Timeline

In last days of March, a group of people contacted me to join them in creating a desktop operating system suitable for Iranian/Persian-speaking users. I said "Hell Yeah! I'm in!" and I joined them. One or two weeks after that, I thought to myself that I need a playground or a test base for that project. As the company's project is based on Debian GNU/Linux, I decided to make a very simple Debian based distribution. So, Caprice Linux is born! This is the development timeline: 

* __16/04/2020__ : [Caprice is here!](http://capricelinux.org/2020/04/16/Caprice-is-here.html)
* __20/04/2020__ : [An Introduction](http://capricelinux.org/2020/04/21/An-Introduction.html)
* __02/05/2020__ : [Caprice is under development (as 02/05/2020)](http://capricelinux.org/2020/05/02/Caprice-is-under-development.html)
* __10/05/2020__ : [Caprice is under development (as 10/05/2020)](http://capricelinux.org/2020/05/10/Caprice-is-under-development2.html)
* __22/05/2020__ : [Caprice 1.0-BETA is under development](http://capricelinux.org/2020/05/22/Caprice-1-0-BETA-is-under-development.html)
* __27/05/2020__ : [1.0-BETA development is about to be finished](http://capricelinux.org/2020/05/27/1-0-BETA-development-is-about-to-be-finished.html)

So now, we have are on a very good point of development. We finished the first beta of the version `1.0`. 

## What's new in Caprice Linux 1.0-BETA

In this version, we have added these : 

* Full _UEFI_ support. The development release (which even didn't have any official announcement on the website) didn't have any regards for UEFI. But in this version, we have added that support. Thanks to the minds behind that old tool `remastersys`, their boot scripts helped solving this problem. 
* _VLC_ as a media player. Altough we had `Parole` and `Rhythmbox`, which both are great tools written in GTK+ and we tried to avoid using too much Qt, I decided to add VLC. Because VLC is a good media player and sometimes, it can be considered much more than a simple media player. 
* _Improved performance of the repositories_. As Caprice Linux has her very own repositroies now, we had to work on those repositories to have the best performance. Altough we even forked our own repositories, we didn't really changed anything and we inherit everything from Debian, with a little bit of difference in update/release cycle. So we tried to fix everything to have the best performance possible and now, we have some sort of fast and great repositories for our project. 

## Why you should use Caprice Linux?

Ok, this is one of the questions I personally bombarded with. Something like _Why someone should use Caprice?_. I ask you, why do you use Ubuntu, Linux Mint, MX Linux or any other operating systems available? My personal answer is _They have something I need._. About Caprice, she was the need herself and answered very well. 

A lot of people out there want to try a _Debian Stable_ based operating system. But most of Linux distributions available are based on testing or unstable branches. Of course they had a point to do that. But Caprice will always remain based on stable branch of Debian GNU/Linux. Why? because we just want to provide _safe_ and _easy_ form of computation to desktop users. So if you have the question of _Why should I try Caprice Linux?_ we tell you that Caprice Linux has a package of different things available (which are not usually shipped with Debian official images) and it also has a different type of release and development structure. 

After talking too much, I make the long story short. If you're enthusiastic about Debian GNU/Linux, but don't want to fall into the hard process of the installation, just use Caprice Linux. We're not trying to replace Debian, but we're going to offer a better Debian user experiment. 

## Where and how can I download Caprice Linux? 

Just visit [downloads](/downloads) page and there, you can grab ISO images and checksums. There are some different download mirrors available. 

Main download server is located in France. If you live in Europe or the Americas, I think it's a better choice. Ilam LUG server is located in Iran. If you live in the Middle East, Russia, Turkey and North Africa, it's a better choice. By the way, we need some mirrors for east Asia as well. So if you can help us mirror in east Asia (China, Japan, Korea, etc.) please let us know using [this github repository](https://github.com/Caprice-Linux/discuss)

## Special Thanks

* __Ilam Linux Users' Group__ for their kind support and letting us using their servers as a mirror. 
* __Shiraz Linux Users' Group__ for their kind support of the project. 
* __Iranian Free/Libre/Open Source Association__ for their kind support of the project, providing a platform for creation of the project and repositories. 
* __Caprice Linux Community__ for their kind support and technical helps. A bunch of really cool kids joined us in the process of making Caprice Linux and withouth their help, it wasn't possible to create this big project! 