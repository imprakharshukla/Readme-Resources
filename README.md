

<p align="center">
<img src="https://raw.githubusercontent.com/imprakharshukla/Readme-Resources/master/images/app_logo_verticle.png?token=AJQWPWLM6UD7MLVJY4LVDZS6TKQJK"/>
</p>

<p align="center">
  <a href="https://circleci.com/gh/vuejs/vue/tree/dev"><img src="https://img.shields.io/badge/Questions%3F-Join%20our%20forum-blue?style=flat-square" alt="Build Status"></a>
  <a href="https://codecov.io/github/vuejs/vue?branch=dev"><img src="https://img.shields.io/badge/Join%20us%20on-Discord-blue?style=flat-square&logo=discord" alt="Coverage Status"></a>
  <a href="https://npmcharts.com/compare/vue?minimal=true"><img src="https://img.shields.io/badge/Documentation-Read%20the%20docs-blue?style=flat-square"></a>
  <a href="https://www.npmjs.com/package/vue"><img src="https://img.shields.io/badge/Download-Google%20Play-orange?style=flat-square&logo=google-play" alt="Version"></a>
  <a href="https://www.npmjs.com/package/vue"><img src="https://img.shields.io/badge/Download-GitHub%20Releases-orange?style=flat-square&logo=github" alt="License"></a>
  <a href="https://app.saucelabs.com/builds/50f8372d79f743a3b25fb6ca4851ca4c"><img src="https://img.shields.io/codacy/grade/1ae093576d614e51b3befa0ffd9d1071?style=flat-square" alt="Build Status"></a>
</p>

<br>
<h1 align="center">Install Linux on your Android 🔥</h1>
<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/imprakharshukla/Readme-Resources/master/images/app_dashboard_dark.png?token=AJQWPWO3CPM5OR7ONJ56EBK6TKGP2" width="250">
  <img src="https://raw.githubusercontent.com/imprakharshukla/Readme-Resources/master/images/app_dashboard_light.png?token=AJQWPWIS2QUTZVWDPWAAIAS6TKG5K" width="250">
 </p>

# How does this work?
Andronix is simple inside the hood (well not really, but most of it is simple to understand). Andronix uses **PRoot** to run your favourite Linux distribution on your Android devices.


### What exactly is PRoot?

As stated in the official website of PRoot

> PRoot is a user-space implementation of **chroot, mount --bind, and binfmt_misc**. This means that users don't need any privileges or setup to do things like using an arbitrary directory as the new root file system, making files accessible somewhere else in the file system hierarchy, or executing programs built for another CPU architecture transparently through QEMU user-mode.


or in easier words, the benefits of enabling PRoot include running Linux operating systems in a Termux [chroot](https://en.m.wikipedia.org/wiki/Chroot) on an Android smartphone, tablet and Chromebook.

We use **Termux** to provide the command line and the packages that are especially compiled for Termux implemented inside Andronix.

# Get started now 🚀
Hey! 😊, let's introduce to the basics of the documentations around here. This is the doc-hub for Andronix, from development to installations, you can find almost everything here.

### Introduction Docs 📒

Here you can find all the information necessary to understand Andronix better. Diving deep in **PRoot**, **app structure** and **Shell scripts** that actually make you understand about what's actually happening.

<br>

### Installation Docs 📱
All and everything for you to get up and running with your favourite Linux Distribution. If you're seeking for help installing a distribution, this is place you need to be.

<br>

### Apps Installation 💻
Here are the installation procedures of few most popular apps like **VS Code, IntelliJ Idea, GIMP, Blender** etc. Easy to follow and quick!

<br>

### Development Docs 👨‍💻
Looking into contributing and developing things around or for Andronix? Here you can find all the required documentation regarding **termux-packages, app, scripts** or anything to development.

## What can you do with Andronix?
Pretty much anything you like to do. You're just limited by the lack of the full Linux kernel, the SELinux policies of your Android versions, your CPU architecture and your device's hardware. We have users replacing their entire laptops and computer with Andronix. We are looking for something that can support web-browsing, coding or anything else that is not really taxing on your phone's hardware then you can use Andronix without any issues.

You don't have to worry about multi-booting your system which means you can have all the Un-Modded and Modded OS installed at once. **12 OS at once given that you have the storage for it.** Install as many as you like, uninstall them when you're done.

## Is it free?

Yes! ⚡ Andronix is completely **Ad-free** and all the Un-modded distros and **free to use as much as you want**. 

On the other hand [Modded OS](https://app.gitbook.com/@andronix-app/s/andronix-app/~/drafts/-M4c-rXqPL1Wt-aXeJcK/installations/modded-os) are paid but they are very economical considering it is a **lifetime purchase with unlimited installs on unlimited devices.**  (We spend hours optimizing and packing it, and these are very large files which we need to serve requiring a massive amount of bandwidth, which costs money).

You can also get **Andronix Premium** which is another way to support the developers. You also get a few perks including online sync with Andronix Commands and a web-app to access it from any device you want.

## What Andronix can't do?
Many users out there are looking for a viable resource to use Linux system on their Android devices without rooting their devices. AndroNix is a viable option for these purposes but with some limitations. We make our best efforts to provide a full Linux PC 💻experience to our users but some things are just out of our hand due to certain restrictions imposed by the Android layer, its SELinux 🔐 policies and the process we use to run the Linux on the Android devices.


-   AndroNix is not capable of running **STEAM 🎮** or any PC games on any of its Linux systems. The main reason for this is because Steam is only made for Intel/AMD based CPU's and not mobile based CPU's i.e. aarch64, armv8, arm64, arm, armv7, arm32 etc.
    
-   AndroNix is not capable of running any software except software complied for **arm64/armv8/aarch64** architecture if you are using any **Android device** based of **Android 7** or above and has **arm64/armv8/aarch64** chipset. You can check your device architecture by using [**CPUZ**](https://play.google.com/store/apps/details?id=com.cpuid.cpu_z). If you are using any device which has Android layer such as **Chromebook** then AndroNix will only be able to run software made for your architecture which may be **i386/i686/x86 or x86_64.**
    
-   AndroNix does not claim that it will run all the software even if the software complies to all the conditions mentioned in the above point. If the software is made in such a way that it requires the presence of Linux Kernel or any hardware support which is not present in the ⚠ **PRoot environment** then the software might fail to run**.** AndroNix uses PRoot environment which has certain inevitable limitations leading to unusable software.
  
-   AndroNix is not made for compiling large chunks of code 👩💻such as building an Android app, any software or compiling kernels. Code compilations sometimes require specific hardware which is not present in PRoot environment which may lead to errors while compiling code. Any such reports on any support channel will not be entertained.
    
-   Linux environments made available by AndroNix cannot be used for **hacking/cracking purposes** i.e. Wi-Fi hacking, packet capture etc. All these things require real hardware which supports all the features like packet capturing which is not available natively in Android phones.
    
-   Linux environments cannot mount/read any hardware such as drives or adapters 🖨. This is because fuse mount cannot be used under PRoot.
    
-   Any Linux OS cannot be installed on External Storage as Android does not give permission to write on External storage such as SD card or USB devices.
    
-   **SNAP/Docker** packages cannot be installed on any Linux environment. It is mainly due to two reasons. Primary being that both require kennel and bus modules which are unavailable in PRoot environment and second being that both are mainly focused on Intel/AMD based architectures and not for arm architecture.
