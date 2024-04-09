+++
title = "Journey to Linux from Windows"
slug = "journey-to-linux-from-windows"
date = "2024-04-04"
description = "The journey of switching to Linux from Windows"
images = [ "~/images/journey-to-linux-from-windows/index.webp" ]
tags = [
    "windows",
    "linux",
    "manjaro"
]
draft=true
+++
![Tux holding Windows logo](/images/journey-to-linux-from-windows/index.webp)

So, hello again? It's been a while.

I'm trying to switch to a different operating system, namely Linux, more specifically Manjaro. 

This is not my first rodeo tho. I've tried multitude of distros back in the day, but after a while, I always found myself back in Windows. Whether it be a little annoyance to a huge problems, Linux has always been rough for me.

But it's been about a month now and it's my personal record of not returning to Windows, so, yay!

I wanted to write this post to share my experience, help someone else a bit - maybe you and reference it back if I need to in the future. Please note that it's not a guide on how you can setup and/or apply these apps and customizations, I'm just going to mention them and try to explain why I made these choices.

## A quick note for the tech savvy

So, if you know what I'm talking about, you might say to yourself "Then why the hell are you trying to switch to an Arch-based system?". Well, let me explain.

As I said before, I've tried most them, ranging from Ubuntu to Arch. Ubuntu is a bit friendly, but I don't like Canonical anymore - I can list bunch of reasons but ditching Ubuntu Phone and Touch alone is enough, so, it's not an option for me anymore. Also Arch is too demanding and living on the bleeding edge is not something I want to do on my daily driver. Manjaro is stable enough and offers rolling updates. That's pretty much it. Flexibility of Arch, stability (kinda) of Ubuntu. Perfect middle ground for me. Also, I have this itch that says "Try it again. Why not?" and I already had to format my PC because it was time - Windows problems, so, I scratched that itch and installed it. 

## Apps

Let's start with what apps I'm using. I also want to mention as a side note that, you have to enable Flatpak and AUR support within the software center to find and install some of the applications below.

### Browser - Google Chrome and Firefox

One of the things that I can't change right now is the browser that I use. I'm too bound to Google Chrome and Google in general - which is something that I also don't like, but, hey, I'm also the person who chose to use these "free" services back in the day, so, it is what it is at the moment. I'm trying to use Firefox in the mean time and maybe I'll switch to it in the future.

### Music Player - [Cider](https://cider.sh/) 

Music is an important part of my life. I've switched to Apple Music about a month ago from Spotify because of the music quality difference between them and I enjoy Hi-res Lossless music from my Android phone. Windows has a great app directly from Apple but Linux on the other hand, don't. Cider is a great alternative that has the Linux version. It has two versions, one of them is called "Classic" and it's free. It's not in active development anymore but it does the job. The other one is paid but after using Classic for a while, I decided to buy it and I'm happy with my purchase. 

Beware that, it doesn't support Lossless options at the moment and may never will, because of Apple and how they designed their API's that these kind of applications can use. To remedy this a bit, Cider has something called "Cider Adrenaline Processor™" that processes the sound that is coming out of your speakers and I think it's pretty solid.

### Sound - EasyEffects and Presets

As I said before, music is an important part of my life and hence, sound is kind of a deal-breaker for me. Sadly, when I switched to Manjaro, the sound quality was bad. My machine supports THX technology but as far as I was able to hear, it was not in use. Did a little bit of digging and found out that the drivers for linux was non-existent - I'm really not surprised. But not all was lost because Linux had a couple of tricks under it's sleeve for this exact situation.

Manjaro uses [PipeWire](https://www.pipewire.org/) underneath by default. This project aims to improve handling of video and audio content for Linux. Coupled with an application called EasyEffects, you can tweak your sound profile by creating series of effects contained within a preset. But, to understand what needs to be done manually, you have to know couple of sound related stuff. If you are not a sound engineer(!), there are pre-made presets that you can download and apply. [EasyEffects-Presets by JackHack96](https://github.com/JackHack96/EasyEffects-Presets) is a popular project that I've encountered. It has 7 presets that you can choose from. I'm personally using "Laptop" preset and I'm happy with the results.

I've also followed a bit of this [tutorial post from Manjaro forum](https://forum.manjaro.org/t/how-to-make-linux-sound-great/146143) and it's comments. I also advise you to look at it if you want to traverse this path.

### Communication - WhatsApp, Telegram and Discord

One other thing that I do frequently is messaging from my PC, so it's important that I have an option for it in Linux. Sadly, WhatsApp doesn't have a native desktop version for Linux like it does on Windows and mac, but there is a community made Web wrapper called [WhatsApp Desktop for Linux](https://github.com/mimbrero/whatsapp-desktop-linux) and it does the job. It just launches Web version of WhatsApp in it and adds a couple of features. I've looked through the code and there is nothing that seems sketchy in it, so I'm using it. But remember, it's a community made package and I'm not affiliated with them nor have control over the code that runs on your computer, so use it on your own risk.

On the other hand, Telegram and Discord have native versions of their respective apps and I had no issues using them what so ever.

### Mail - Mozilla Thunderbird

I have two mail accounts at the moment, namely Outlook and GMail. I've been using the new Outlook on Windows, it's alright, but on Linux, I don't have that option. I wanted to try Thunderbird from Mozilla using this experiment as an excuse and it's been great. I would recommend using it for your mailing needs.

### Office Suite - Libre Office

My choice of office application is Libre Office. Linux have couple other options, so you can choose from any of them to your liking.

### Note - Microsoft OneNote and Obsidian

Yes, the service of choice for note taking purposes for me was and in some cases still is Microsoft OneNote. I did get used to it back on Windows and I've been using it for a long time. I also did use Obsidian a bit but it was not my go to app.

For OneNote, I'm using a community-made package called [P3X OneNote Linux](https://github.com/patrikx3/onenote). It does the job. The same statement that I did for WhatsApp Desktop for Linux also applies to this package.

For Obsidian, I've already created a repo in my GitHub account back in the day and I'm syncing my notes to it. I'm also using "Git" community plugin to make my setup work. They are also synced with OneDrive just in case, I'll be back on that later about how.

When I made the switch to Linux, I moved most of notes there. But not all of my notes are there at the moment, I'm still using OneNote for some of my notes. 

I'm trying to figure out how I'm going to reach to my notes through my phones at the moment. I need to be able to access to my notes from my iOS and Android phones as well as my PC. Obsidian for iOS has a sync option for iCloud but just that. I might consider subscribing to "Obsidian Sync" but not for now. I'll update this post when and if I find a solution for this situation.

### Editors - VS Code and Notepadqq

VS Code is my editor of choice for a lot of my editing needs. I've been using it on Windows a lot and the same app is also available for Linux.

I want to also mention in this section that, how Microsoft turned out to be after Satya Nadella started to run the company. It's more open now, thanks to him and VS Code is one of the things that was possible thanks to him.

I was also using Notepad++ on Windows and Notepadqq is a direct replacement for it. I've been using it with no issues.

### IDE - Rider EAP

One other thing that was keeping me in Windows was my IDE of choice; Visual Studio. It is a great piece of software that enables millions of developers to create much more great pieces of software. With this experiment, I decided to give Rider a try. It doesn't have a Community version like Visual Studio but instead it has an option called early access program. You can try the beta versions of the apps that they offer and in return they let you use it for free. It's not stable, so beware, but it's acceptable for personal use. If you want to use it professionally, I would suggest you to purchase a license from them.

### Gaming - Steam, Lutris, Heroic Games Launcher, BoilR and protonup-qt

Valve has made a lot of contribution and investments to open source community and Linux itself, so it's not a surprise that Steam works on Linux. Also, a lot of their games can run natively on Linux. They didn't stop there tho, they are trying to make Windows games work on Linux and they've come a long way with Proton. Proton is a layer that is based on Wine and it makes it possible to play a lot of Windows games on Linux. [ProtonDB](https://www.protondb.com/) is a great site to check if the game you want to play is supported by it but I would suggest you to try it even if you don't find it on the site, it's a really great piece of software that properly does a thing that was called a pipe dream once.

Lutris is another project and a package to ease installing and playing games on Linux. It has community made scripts, each different for the game you want to play, regardless of platform you have the game on. It's not standardized tho, you might have an option to install it through GOG but not on another one even though the game is available through GOG.

And this makes a great transition to Heroic Games Launcher. It's a unified launcher for Epic Store, GOG Store and Prime Gaming. You can login into this application and install your favorite games from it. 

You have to open your games from there or through clicking to the application executable tho. Wouldn't it be great if you only had Steam to deal with when you want to play your games? Steam have an option to add your non-steam games to it and launch it from there. It's a bit tedious if you have a lot of non-steam games. You can do it manually if you want but BoilR is an app that does exactly that, automatically with a click of a button. It also fetches artwork for specific games from [SteamGridDB](https://www.steamgriddb.com/) if you configure it so you can have cover art for non-steam games within Steam.

protonup-qt is an application to manage Proton versions. It also have another layer options you can install and use for your games.

### Various

#### Firewall - ufw and gufw

Manjaro also doesn't include any firewall management software, so it's a must if you want to use your computer safely. ufw is a CLI package and gufw is a GUI interface for that package. gufw is easy to use, just a click of a switch and you are safer.

#### System Recovery and Restore - Timeshift

It's another must have application and it's a direct replacement for an embedded application within Windows. It let's you create restore points manually or on schedule and restore back to it if you need to. You can also use a Live CD, install Timeshift there and restore your system if you can't open up your installed system.

#### DNS - dnsmasq

It's a package for having the functionality to have a system level DNS. It's especially useful for development purposes.

#### NVIDIA Optimus - optimus-manager and optimus-manager-qt

NVIDIA doesn't play nice with Linux and if you have a PC that is NVIDIA Optimus enabled, then you are in more trouble. Manjaro already includes a package called "mhwd" for detecting and installing open source or proprietary drivers for your hardware, including graphics cards but using only that doesn't solve the whole issue. It makes it hell of a lot easier tho.

The other piece of the puzzle is using "optimus-manager" and "optimus-manager-qt" packages. The second one is a GUI application that uses the first package and it makes it easy to switch between integrated and discrete graphics cards. You must use X11 tho. Wayland is not supported at the moment. This application is a must if you have that kind of configuration.

#### Windows Applications - Wine

It's a translation layer for Windows applications that makes it possible to run them within Linux. I've already mentioned it on gaming section but it's actually not for gaming. It's pretty capable of running them but it's not a silver bullet. You might have some problems running some demanding or obscure applications.

#### Media - VLC

VLC is a great piece of software for your media needs. I was using it on Windows already. Having it here also is really great.

#### Camera - Camera (snapshot)

Manjaro doesn't include any software for camera. I don't know why but you can install an app called "Camera (snapshot)". It does the job.

#### Torrent Client - Fragments

I found that "Fragments" is an easy to use application for torrent needs and I didn't have any problems using it.

#### "Windows Hello™" - Howdy

My computer also has a IR camera that Windows utilizes it to authenticate users. This service is called "Windows Hello™". Windows Hello™ also includes authentication options like fingerprint if your computer has it but mine does not.

Looking through the internet for options to authenticate in Linux using this IR camera, I encountered "Howdy". After dabbling with it for a while, I was able to setup and use it. Kinda. I still couldn't figure out how can I use it at the first login but other than that, I can just press enter to any password prompt and Howdy takes care the rest of it. 

I do not recommend it if you don't know what you are doing tho. Setting it up is a really involved process and there is a chance of bricking your system. If you still want to do it, do not proceed before taking a backup, you can use Timeshift I mentioned above to do it.

##### Note for me and to the people who decided to go down to this path

For Manjaro Plasma, make sure that you have "base-devel" package installed before installing "howdy" package. 

Add the Howdy lines below to the "sudo", "kde" and "polkit-1" pam files and right before the "auth include system-auth" line. They are located at /etc/pam.d

"polkit-1" file might not be there, just copy "sudo" file after modifying it and it works.

###### Howdy lines
```sh
auth    sufficient      pam_unix.so try_first_pass likeauth nullok
auth    sufficient      pam_python.so /lib/security/howdy/pam.py


```

#### Cloud Storage - rclone

I've got Google Drive, Microsoft OneDrive, Dropbox and MEGA accounts that I use and "rclone" is a tool for using your cloud storage right from your file explorer of choice. It's a bit of an involved process to setup but once you are done, it works great.

##### Note for me and to the people who decided to go down to this path

Follow [this](https://gist.github.com/Gyarbij/4dc1fe668b6e7d804b490bebddd3ac80) guide and [this](https://github.com/tynor88/docker-rclone-mount/issues/2#issuecomment-470129261) comment to set it up properly.

Remove the comments (parts that starts with #) from the sample configuration because it breaks the service.

Create different services and cache folders for each cloud storage you want to sync.

#### Disk Usage Analyzer - Baobab

I've been using WinDirStat on Windows for analyzing disk usage to find out which files and folders were eating up my storage. Baobab does exactly that on Linux and it's a great alternative.

### Optional

#### Microsoft Fonts - ttf-ms-win11-auto

If you have a license for Windows 11 and want to use the fonts from it, then you can just grab this package and install all of the fonts. Including Comic Sans. It just makes some sites to look how you used to and viewing and editing Office files easier and much more compatible.

Well, if you don't have Windows 11 but have 10 for example, then you can just use "ttf-ms-win10-auto" instead.

In fact, there are bunch of options to choose from [here](https://wiki.archlinux.org/title/Microsoft_fonts) depending on which version of Windows or Office you have. You can just use that package instead. Beware that you need your installation media ready for those "non auto" packages.

## Desktop Environment, Display Manager and Customization

The thing about Linux based operating systems is that you can customize them however you want. You didn't like the look of your desktop? Go ahead, customize it. You didn't like how your login screen works? Just change it. You want to delete your boot loader for some reason? Sure, go ahead! It's unrestricted control over every aspect of the system is unparalleled between other popular operating systems.

My desktop environment of choice is KDE Plasma. If you choose to download the Plasma variant of Manjaro, it's coming pre-installed. As a display manager, SDDM is also coming pre-installed with Plasma variant of Manjaro. I haven't changed them. What I did was tho, customize them. I've installed themes, widgets, icons, cursors... There are limitless options you can choose from and with them, you can create a unique system that fits you and your needs.

Let's get into what I'm using currently.

### Wallpaper - Picture of the Day (Bing)

Yes, I like having different wallpapers everyday. I was already using Bing daily wallpapers on my Windows machine and I was surprised and happy to see that I can use it here too.

### Theme - Utterly Sweet

This theme is a glossy dark theme and I really liked it when I saw it. It integrates really nicely and haven't given me any problems whatsoever. Here are some other customizations that I did to sub options.

- Plasma Style - Utterly-Round
- Window Decorations - Utterly-Round-Dark
- Icons - candy-icons
- Cursors - Sweet-cursors
- Splash Screen - Utterly Sweet

Please note that, for the login screen (SDDM) theme, you have to find and set it separately. I'm also using Utterly-Sweet theme here. Remember to "Apply Plasma Settings" after you set this theme to see all the effects and changes you've made so far is reflected to the login screen too.

### Widgets

#### Weather Report

It's a taskbar widget that allows you to see the current weather condition. When you click on it, you can see more information like temperature and brief hourly forecasts.

#### Advanced Radio Player

It's, again, an another taskbar widget that does what it says. It allows you to listen to couple of online radios. I'm not using it frequently but it's there if I need it.

#### Better Inline Clock 

It's a clock widget and personally it's really a better inline clock alternative from what you get by default. I've set it to show the date and time horizontally rather then vertically. It allows me to set my taskbar height to a much more smaller size.

#### Control Centre

It's a nice, macOS and Windows inspired control center widget. It's pretty handy to have volume, brightness, media, bluetooth and much more options in the same window.

## Last words

II'm pretty happy with my experience and setup at the moment. I don't plan to go back to Windows ever again on my personal computer and I'm hoping that I'll not feel the need to. I hope this was a good read and helpful a bit.