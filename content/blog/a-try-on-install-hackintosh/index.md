---
title: A Try On Installing Hackintosh
date: "2019-02-03T10:54:22.169Z"
---


hello everybody, this is my first blog and I would like to try it with Gatsby so here it is.
If you see mistakes on my blog please let me know, as my English is not as good as native ones ,although I am improving constantly, so let's go to our journey.


## preface

I am a junior android developer. I have studied the Civil engineering at a small college and after goofing off 5 fucking years I finally found out that I had no interest in it. So I left it behind and decided to try my chance as a programmer, then I have started learning android programming and completed my internship at a company that its main business is providing content for Kids and teens.
After 5 months they suggested a permanent contract to me and I started my professional career as an android developer.


## Beginning of the story

After working a year and a half I have been assigned a project that I shoulda written in React Native from scratch. I was so excited cuz I've had a chance to learn and experience many new materials and it was very exciting to code once and see the result both in android and ios simultaneously.

After some months working on the project I made up my mind to learn Swift and native ios so that I can get better understanding of what I am doing on the ios side and if needed create native modules for the project.

As most of you know learning ios is an expensive stuff. you must have a MacBook or IMac and an Iphone for testing. actually ios simulator covers most of your requirements
 and you can use it instead of Iphone but having a mac device is necessary cuz you need XCode for development and it's only available on Mac OS.
 
 The currency value in Iran is very low. At the time that I'm writing this article one dollar is equivalent to about 110,000 Rials, so I couldn't afford a MacBook.

 ![Rial Value](rial-value.jpg)

 I borrowed the company's macBook and signed a 300,000,000 Rials promissory note that is equivalent to 1.5 years of my salary.
 I'd put it in my backpack and carried it with myself every time I'd went to work and came back.
 
 It was a super high risk , I might had damage it or lose it by a rubber, so I'd been so nervous and afraid so much.

 ## The Big Decision
 
 I have a high config PC.
 when the inflation rate in Iran was lower and the value of Rial was double of its current value I bought my PC. I decided to install Hackintosh on it.
 
 first I downloaded High Sierra installer in a persian website.
 I tried to boot it in my flash drive by [UniBeast](http://www.tonymacx86.com/resources/unibeast-8-3-2-high-sierra.383/)
 but I failed.
 I didn't know what was wrong with the downloaded file. I remembered one of my coworkers had a newer version (Mojave) so I get the Mojave installer from him and tried [Step By Step Process To Install Hackintosh macOS Mojave](http://techhowdy.com/process-to-install-hackintosh-macos-mojave/) but it didn't work for me.

 I watched [This](https://www.youtube.com/watch?v=VdRSYogDygs) guide on Youtube and successfully installed Mac OS Mojave on my PC. I was very happy at first but I found out Nvidia doesn't support Mojave yet. The display resolution was very low andy none of browsers I Installed worked correctly. I was disappointed.

 I had two choices: 

 1. wait until Nvidia release the web driver for Mojave
 2. downgrade to High Sierra version
   
I chose the second.

By my coworker's help I downloaded a correct High Sierra from [here](https://p30download.com/fa/entry/75015/).

![screenshot](screenshot.png)

I tried some of youtubers' guide but I Couldn't succeed.

finally I found this [guide](https://hackintosher.com/guides/high-sierra-install-full-guide/) and follow it step by step and at last I installed High Sierra and its drivers successfully.

and this is the result of my two weeks try and error: 

![result](result.jpg)

If you wanna try too, pay attention that the contents of EFI folder in boot loader is very important. If you set it up improperly your install process will fail. do it exactly like the guide said.

for intel systems if AppleCDA.kext or AppleHDA.kext sound driver doesn't work download VoodooHDA clover from this [direct link](https://github.com/chris1111/VoodooHDA-2.9.0-Clover-V12/files/2087523/VoodooHDA.2.9.0.Clover-V12.zip).
install and restart your pc.

Ok guys! have a good luck.




 
 


