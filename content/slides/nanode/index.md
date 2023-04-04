---
title: Nanode Project Bot
date: 2023-02-23T07:21:31.139Z
summary: " "
slides:
  theme: league
  highlight_style: dracula
authors: []
tags: []
image:
  preview_only: true
  caption: Nanode in his natural habitat
  alt_text: ""
  filename: featured.jpg
  focal_point: center
categories: []
---
# Nanode Bot

by Ariya Seng, S M Raisul Alam Bhuiyan, and Tom Tran

C﻿SCI 310-01-SPRING-2023

**0﻿4/17/2023**

- - -

## Introduction

{{< fragment >}}  

* W﻿hat is the Nanode Bot?
  {{< /fragment >}}

{{< fragment >}}  

* W﻿hat hardware are we using?
  {{< /fragment >}}

{{< speaker_note >}}

* Nanode is a 4-wheel robot that can move around in all four directions
* Nanode can also do basic object detections as well via the camera & sensor modules
*

{{< /speaker_note >}}

- - -

## Hardware Design

{{< fragment >}}  

* W﻿hat hardware are we using?
  {{< /fragment >}}

{{< speaker_note >}}
H﻿ardware:

* Arduino Uno R3
* Ultrasonic Sensor Module
* GY-521 Module (gyroscope & accelerometers)
* Camera Module
* Line Tracking Module (ITR200001)
* IO Expansion Block
* Cell Box (Lithium Ion Battery)
  {{< /speaker_note >}}

- - -

## Software Design

{{< fragment >}} 

* W﻿hat are we using the Nanode Bot to demonstrate?

 {{< /fragment >}}

{{< speaker_note >}}

* E﻿xplain what we're using the Nanode Bot to demonstrate: camera module, ultrasonic module, etc.

{{< /speaker_note >}}

- - -

## PID Algorithm & Datapath

P﻿ress to Play!

{{< fragment >}} $\mathbf{y} =  $ {{< /fragment >}}


{{< fragment >}} $X\boldsymbol\beta$ {{< /fragment >}}


{{< fragment >}} $+ \boldsymbol\varepsilon$ {{< /fragment >}}

{{< fragment >}} $\mathbf{y} =  $ {{< /fragment >}}



- - -

## slide

if we talk about code, we can talk about what we went through.

{{< speaker_note >}}

* E﻿xplain that there were a set of files of code that we sifted through in order to fully understand how to operate all of the modules.
* C﻿larify that the code we have are not simply copy and pasted; we went through the painstaking journey of going through thousands of lines of code in order to understand how everything works.
* W﻿e can show certain screenshots of code that we looked over (not the actual code we worked on yet).

{{< /speaker_note >}}

- - -

## slide

we then clarify what we did with our code.

{{< speaker_note >}}

* What did we mess with coding in prospect with the modules. Most, if not all, of the coding has to do with the modules. Talk about things like the dataset for the object tracking of the camera module, or how the GY-521 works with the motors of the bot in order to keep it heading straight. Things like this. Notes will be refined as soon as possible. This can take up multiple slides to talk about.

{{< /speaker_note >}}

- - -

## slide

we can then try and demonstrate the bot.

- - -

## slide

this is just a messaging area for others who see this before it gets refined. i dont know if i missed anything else, i'll make sure to talk to you guys about that. we can include videos of the processes of what you guys went through with the code, the trial and errors, all that good stuff and whatever.

- - -

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)