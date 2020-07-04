---
layout: post
title: Caprice Linux 1.0-STABLE is under development (2020/04/07)
---

In past couple of months, I worked on this project in any free time I had. By beginning of the July, I had more free time and so I decided to dedicate more of my potentials on the project. In this article, I'm going to explain what have I done with the help of _Caprice Linux Community_. 

## A new look

First of all, a new interface is designed for _Caprice Linux_ desktop. This is how it looks like: 

![New look]({{site.url}}/assets/images/the-new-look.png)

For now, it includes : 

* A dock. Dock makes access to _favorite software_ easier. This is why we decided to add the dock to the desktop. 
* Global menus. Global menus are also beautiful and useful. They give you the ability to use more space on your display. 
* A new desktop background. I just contacted a few friends, and one of them offered this beautiful photo and people of the _Caprice Linux Community_ just voted for this and we decided to pay for the photo to use it as the main background. 

## Stability of Linux, Flexibility of NetBSD 

To be honest, this sections title should be _Stability of Debian GNU/Linux_. Debian is famous for being stable. But I personally was a BSD user and administrator as well (I even had FreeBSD as my desktop operating system back then), I decided to bring something from BSD's to this project. 

First, I was thinking of making something like _Caprice kFreeBSD_, but it's really useless and pointless. Waste of time and resources. I decided to bring something better to this project. So, I decided to bring `pkgsrc`, which is one of [NetBSD](http://netbsd.org)'s great creations. It has a few benefits. I list them below: 

* It brings a few useful tools from _BSD_ operating systems to this one. The boldest one for me, was `bmake`, which is an equivalent to _GNU Make_ and it made me happy. Of course, it has a few other tools from BSD to create packages and install them. 
* It makes _Caprice Linux_ a _source based_ Linux distribution. The most famous source based Linux distribution is [Gentoo](http://gentoo.org) and as you may know, it also borrowed a lot from BSD operating systems. So, why not? 

Of course, there are a few challenges in the process of changing the package manager, but we can solve the problems with the help of _Caprice Linux Community_ and _IRBUG_ (stands for _Iranian BSD Users' Group_) members. 

The first challenge, might be the update process of the system. The second one is that _services_ need another init system. These problems will be solved by the release of future versions of _Caprice Linux_. 

## And final words ... 

One of the most asked questions about _Caprice Linux_ is this: 

__What makes _Caprice Linux_ a different distribution?__

Now I have a strong answer for this. You have the __stability__ of _Debian GNU/Linux_, __beauty__ of _Apple's macOS_ and __flexibility__ of _NetBSD_ in one package. It has these benefits and best of all, it's _Caprice Linux_ and not replication of other distibutions or operating systems. 

I hope I can make the final builds for a release in maximum of ten days. Please wait for a revolutionary project!