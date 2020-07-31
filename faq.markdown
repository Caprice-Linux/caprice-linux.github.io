---
layout: page
title: FAQ
permalink: /faq/
---

## Frequently Asked Questions

* __Why is the project called _Caprice_ ?__ 

As I mentioned before, there are two reasons behind this. First, Caprice is a musical forms, where variations and movements have sudden changes. Also, it's a model from Chevrolet. I love that car and these are my reasons for calling it Caprice. 

* __What's the difference between _Caprice Linux_ and _Debian GNU/Linux_ in general?__ 

_Caprice Linux_ is a step further, comparing to the _Debian GNU/Linux_. Actually, Debian is the parent project and Caprice Linux is the child of Debian. But, we have different repositories (with  different update cycle) and we also have different policies. 

And to be honest, Debian Live discs are really good (some of them have even more packages pre-installed comparing to Caprice Linux TBH) but they're very _Debian-is_. I mean, Debian developers have to follow Debian guidelines, and Caprice Linux developers have to follow their own guidelines as well. Some things are a bit easier in process of Caprice Linux development such as shipping with `non-free` branch enabled by default. 

In middle of June 2020, we also decided to implement _NetBSD_'s `pkgsrc` as a secondary and _pro-friendly_ package/port management system in Caprice Linux. 

* __What's the difference between _Caprice Linux_ and _Debian GNU/Linux Live/Install Images_ which are shipped with _XFCE_?__

This is the point. When we ask _What's the difference between Caprice and Debian?_, it means we actually didn't study Debian so well, and know nothing about Caprice Linux. But this one, is the actual point. I haven't tested _live_ discs shipped with XFCE. But I tested installation images. First of all, install images are not really easy to use for beginners and they don't provide much packages (mostly because of non-free dependencies or dependencies which are not classified as _XFCE_ tools or programs) but in Caprice, we provided a lot of tools from GNOME to make working with the system much easier. 

* __What's the difference between _Caprice Linux_ and _Debian Live Project_?__

_Debian Live Project_ doesn't focus on any certain GUI. They make images with most known DE's such as _GNOME, KDE, XFCE, LXQt_ and _Cinnamon_. But _Caprice Linux_ is focused on _XFCE_ as the main DE for now. 

* __Why does _Caprice Linux_ still uses `systemd`__? 

There's a funny story behind this. I used to make the `filesystem.squashfs` of _Caprice Linux_ using `debootstrap` on my main laptop, which has Ubuntu installed and as I made Caprice to be a _light_ port of another project, I wanted to keep to as close as possible to that. This is the reason why Caprice still ships with `systemd`. 

* __Is _Caprice Linux_ a national or local project?__ 

No. It's not. Although we're sponsered by _Iranian free/open-source software association_ and companies which support the association, but _Caprice_ is never going to be called a _national_ project. And as we never included Persian(Farsi) locales or Persian keyboard settings by default in _Caprice_, it's even not a _local_ project. 

* __Is there any plans for dropping `systemd`__? 

Of course. As _Caprice Linux_ has nothing to do with any other projects, we have some plans to change the init system. But, for now, Caprice will be shipped with `systemd`. 

For now, _NetBSD_ init system works besides `systemd` and we hugely suggest it for installing services.

* __How can I contribute to _Caprice Linux_?__ 

We have built most of our packages from [Debian's Salsa](https://salsa.debian.org) and we also got our own [Git repositories](https://github.com/Caprice-Linux) and you can contribute to both of these. Contribution to Debian or Ubuntu, is contribution to Caprice and vice-versa. 

* __Will _Caprice Linux_ be available for other architectures?__

For now, we prefer to stick to _amd64_. Most of machines currently have _amd64_ and this makes _Caprice Linux_ a fine choice for every home or work machine. For future, we may have some other ports for _ARM_ processors as well. 