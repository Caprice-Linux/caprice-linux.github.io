---
layout: post
title: Caprice is under development (as 02/05/2020)
---

I am happy to announce that caprice just passed a long way of development and tests. Now, we have something to offer, and this is why this artice is written. In this article, we'll take a look at what Caprice has to offer now. 

## Desktop-ready distribution 

As Caprice had the goal of being a minimalistic desktop distribution, we had to include a desktop environment and minimums of a small desktop system, such as a web browser, email client, image viewer, music/video player and an office suite as well. So, these packages are included in the mix: 

* Firefox as a powerful, free and trusty web browser. 
* Thunderbird as a good and powerful email client. 
* Shotwell as the image viewer, as it's one of the oldest and best applications I know. I think I use shotwell since Ubuntu 11.04. The damn application is really a good _gallery_ and I think it's a _must have_ application in any linux based systems. 
* Parole as an application responsible for music and video. This application is developed by the XFCE development team. So, why not?! 
* Libre Office as the office suite. Maybe because it's the only office suite available on linux (Open Office and KOffice are available as well, but I'm not sure how they hand bi-directional text or right-to-left languages.)

After all these, this is how Caprice looks like:

![Caprice Desktop]({{site.url}}/assets/images/desktop.png)

## More technical details 

As I chose `calamares` as the installer (This application is used in Debian live images as the installer as well.) and I had some serious problems with it, I wrote a bunch of scripts available [here](https://github.com/caprice-linux/install-scripts) and it still has a lot to do. But, installation using the script seems much easier than the calamares itself, and personally, I didn't modify calamares that much. The only change I made is I disabled automatic reboot in favor of my script to run. 

## When will Caprice be available to download?

I can't give you an exact date, but in a week or two, you'll be able to download a usable and installable version of __Caprice Linux__. 