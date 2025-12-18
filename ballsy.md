---
title: Ballsy
description: Byebye studio, hello studio!
date: 2025-12-10
toc: true
---

# Ballsy

## The Studio `Box'

Got my IdeaPad in the mail on 2020-12-03 and it had an OEM licensed Windows 10 Pro on it and it had survived, barely, until this day.

Also coupled with a rather emotional day, I bit the bullet and reinstalled it, without planning it thoroughly or take a more recent full system backup than March of this year.

So some things got lost, of course, but most of all, it got rid in one single swoop, of the ~815 installed plugins, which is definitely not a good thing for every human being out there, except maybe that one person in the world who _doesn't_ have option- or parameter paralysis.

Installed right now (2025-12-14) is:

* 7-Zip File Manager
* Brave
* Discord
* Epic Games Launcher
* Media Preview Configuration (doesn't seem to work anymore imo)
* Opera GX Browser
* Oracle VirtualBox
* Steam
* Terminal (MSYS2)
* VLC media player
* ZSoft Uninstaller

## Layered-Nylons

I was thinking about trying to compartmentalize the Studio from "Just Windows", like a sort of a layer on the filesystem, but I can't find anything on how to do that.

So I tried Sandboxie, but Bitwig crashes hard inside that.

Then I've tried a VHDx virtual hdd and layer that on a mountpoint somewhere on my second disk, but the "grow automatically to full size" sounds better, a lot better, than it actually is. That only asks for more transactions before finally being able to open the DAW up, which is never a good thing.

## First DAW

So the first DAW installed is Bitwig Studio 5.3 right into the OS. No packages, yet.

## Filesystem control

I always like to have my filesystem under control, easier to backup or safeguard, imo.

### VST[23]

So I've created the directories VST, VST2 and VST3 in C:\Program Files [(x86)]\Common Files\ where I closed off the VST2 directories (no write access whatsoever) as well as the Steinberg folders in both %PROGRAMFILES% folders as well. I'd rather have an error pointing that out, than having plugins everywhere.

### VST3Presets

Same goes for VST3Presets, if possible _only_ in D:\Documents\VST3Presets which is on my second drive, not that it needs much space, but just one location would be preferable, of course.

## VSTs

Nope, maybe some more DAWs to be installed later on, but we're going to go with stock plugins only for at least the foreseeable future.

## DAW #2

It's 01:34 and I still have to finish watching Match of the Day, so let's get cracking to install a hopefully nearly clean Mixcraft Pro Studio 10.6. Reminder if you got more than just Recording Studio, an update usually also brings in the rest of instruments you get from Acoustica.

/sign_off
