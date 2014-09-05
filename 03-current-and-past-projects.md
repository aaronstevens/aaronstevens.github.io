---
layout: page
title: Projects
permalink: current-and-past-projects/
---

Here you can find a few projects I've done, mainly as a hobby or when I needed something to work in a certain way.

### This Jekyll Blog!

After some badgering from @j-mes and @virtuosus I got around to creating a Github account to host a Jekyll blog system. Which is, to [quote](http://jekyllrb.com/docs/home/):

>_"Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through Markdown (or Textile) and Liquid converters, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server."_

So far it's pretty fun to work on, and I'm impressed by how it works especially the responsive design - everything is still viewable even if you resized the browser window to a smaller size, or viewed it on mobile.

<a href="/assets/workspace.png" data-lightbox="workspace" data-title="My Workspace"><img src="/assets/workspace_thumb.gif" alt="Workspace" title="My Workspace"></a>

---

### Home Theater PC

In 2011, I set out to spec and build a cost-effective system for watching media with hardware acceleration. My previous setup involved using a 10m HDMI cable from the PC to TV and extending the displays, but this wasn't very convenient as I always had to get out of the sofa to access the keyboard on the PC to pause/rewind or adjust subtitle sync.

I initally planned on an Intel Sandy Bridge i3 build and making use of the onboard HD graphics which would have been sufficient for 1080p playback, but I later added a discrete graphics card due to an unfixable 24hz refresh rate bug on the Sandy Bridge architecture - which was causing a slight playback hitch every ~50 seconds on 23.976fps content.

I also had the idea of using it as a NAS of sorts, so I added a 2TB drive in there and had SyncBack mirror the latest changes from my PC daily at 6pm over a gigabit link. It's always a good idea to have a backup!

---

### IPCop - Linux Firewall

In 2003 I wanted to get away from the annoyance of software firewalls. I was still on a dial-up Internet connection while everyone else was in the fast lane, plus there was no dial-up routers back in the day (at least I don't think so).

I dusted off my old Intel Pentium 166, and installed [IPCop](http://www.ipcop.org) - a Linux firewall distribution. Once done the monitor and keyboard was unplugged and left to run in a corner of my room. One of the greatest benefits of IPCop was how effective the Squid web caching was, which was a great help to have when you only had 56K connectivity.

By 2004 ADSL became available at my exchange and I decided to continue using IPCop. Branded hardware routers were still incredibly bad from what I heard - crashing and locking up, so I didn't want that. I went to purchase an external ADSL ethernet modem and installed an additional NIC in the IPCop box for the modem to connect to.

This carried on well until 2007, at which point hardware routers were now becoming decent. I switched over to a Netgear DG834G to save on running electricity costs and gain the use of Wi-Fi. I still miss IPCop to this day - it was extremely configurable and fun to use.

---

### MSFN

I created [MSFN.org](http://www.msfn.org) (Microsoft Software Forum Network) in 2001 as a non-profit website to publish Microsoft news and be involved in an active community helping out with forum users’ Windows issues. The website rose to its peak in 2003 when I wrote simple guides aimed at the end-user for the first time on how to create an unattended Windows XP deployment CD, with the latest hotfixes, custom tweaks, and additional software all installed automatically.

<a href="/assets/msfn.png" data-lightbox="MSFN" data-title="MSFN Unattended XP CD Guide"><img src="/assets/msfn_thumb.gif" alt="MSFN" title="MSFN Unattended XP CD Guide"></a>

The effects of publishing a guide like this are still felt today, with third-party applications such as nLite and DriverPacks being born as a result, and popular among those attempting this project.

---
