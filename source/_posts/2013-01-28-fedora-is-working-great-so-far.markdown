---
layout: post
title: "fedora is working great so far"
date: 2013-01-28 16:45
comments: true
categories: linux
---


Well, my migration from Ubuntu to Fedora on my workstation at work went
pretty smoothly.  There were a few hiccups (like my SATA to USB dock
decided to act up at one point and I had to wait until I scrounged up
another internal SATA cable to plug the old drive into the motherboard)
and Fedora had some strangeness at first, but after a <code>yum
upgrade</code> or two everything was a-ok.

<!-- more -->

The main bit of install-time strangeness was that I had to edit the
<code>/etc/sysconfig/network</code> file by hand to set my static IP
instead of DHCP. The network manager utility tried to load into the system tray
the first time I logged in, but it wouldn't come up at first (the error message
said that it wasn't compatible with this version of Fedora any more??), but the
next day after a <code>yum upgrade</code>it popped up in the system tray at the
top where it was supposed to be.  That was pretty weird.

I must say, I am liking Gnome 3 very much.  I got used to some of the Unity
keybindings but the Gnome 3 ones match exactly how I work.  I use a 2 monitor
configuration and I keep a Byobu terminal open on one screen at all times,
which is exactly how Gnome 3 does it.  I also prefer to have a single row of
virtual screens instead of the 2x2 grid.  I rarely used the virtual screen
feature of Unity until recently, but the Gnome 3 layout makes way more sense.

Canonical has done a great job with Unity, but Gnome 3 seems to fit my workflow
a lot better.  I also didn't like how with the latest version of Ubuntu, the
Unity menu would take forever to come up.  Fedora with Gnome 3 feels so much
snappier on the same hardware.

