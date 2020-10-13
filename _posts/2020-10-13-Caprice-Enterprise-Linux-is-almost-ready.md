---
layout: post
title: Caprice Enterprise Linux is almost ready
---

I expected things get a bit better by the end of September, but for now I really beg Billie Joe Armstrong to sing another song _Wake me up when October ends_. Why? I don't know. Maybe because the COVID-19 is getting worse again? I have no idea. 

But let's be honest, in this crazy time, we can help ourselves to feel a bit better and doing technical stuff is how I can help myself. In the whole time, almost two months, I was developing _Caprice Enterprise Linux_. The server edition of Caprice Linux, but with a little bit of difference between the community edition and enterprise edition. 

In the previous blog post, I started talking about the importance of the monetization of the project. There's no better way to monetize a linux distribution than having enterprise level support. There was some ideas and plans and I will explain them in the next couple of paragraphs.

## Caprice Enterprise Linux for workstations (aka Caprice Enterprise Desktop)

So, this was one of the very first implementations of the enterprise edition. It had Cinnamon desktop and a bunch of necessary applications for the daily use. But keeping in mind that we had a desktop project previously and it works and it's one the greatest projects I personally have done, we decided to drop this. 

And to be honest, at least in my region, people do not really like to leave Windows. Desktop Linux users here are usually geeky/nerdy people who love the concepts of POSIX, freedom of software, etc. Other people prefer Microsoft Windows or if they're a bit more fortunate, maybe macOS. So, instead of doing an awful lot of time-wasting jobs on making a workstation edition, we have dropped it. Now enterprise desktop. 

## Challenges for _Caprice Enterprise Linux_ development. 

### The installer 

On the desktop version we have released by August 1st, we have used the amazing [calamares](http://calamares.io) which is a distribution-agnostic graphical installer. It's not really perfect yet, but it does what it should do. 

In case of a server operating system, we needed something which works in the command line environment. I personally wanted to have calamares here as well. So I exchanged a few emails with _Adriaan de Groot_, the developer of this installer and asked him for some help about a CLI/TUI version of calamares. 

He told me that they don't have any command-line options yet. So, he just guided me about how the installer works and it really made me happy. I had the skeleton of what I needed. So, I asked one of my interns to work on that. She came up with a pretty good algorithm and after a few days, I came up with the idea of _Caprice Unified Base System_ or `cubs` for short as the backend for a good system installer. 

More information on `cubs` will be available soon. But I'm proud I wrote it from scratch and it now can be used as a very versatile and flexible installation framework for other distributions as well!

### Repositories 

Although we still have access to [Iranian Free Software Association](http://flossir.org/) servers and even our desktop version is still using those mirrors, but we wanted to have the __full__ authority over our product. So, Finding a server with reliable uptime and enough space, wasn't an easy task to be done. 

I was searching over the internet in past couple of days to find a good provider. Fortunately, I found one. I ordered my desired server and I also asked them for custom operating system installation. When everything was all set, I created the mirror and it will be announced very very soon. 

## Target market of _Caprice Enterprise Linux_ 