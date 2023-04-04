---
title: Nanode Project Bot
date: 2023-02-23T07:21:31.139Z
summary: " "
slides:
  theme: league
  highlight_style: dracula
authors: []
tags:
  - Tutorials
image:
  preview_only: true
  caption: ""
  alt_text: ""
categories: []
---
# Nanode Bot

by Ariya Seng, S M Raisul Alam Bhuiyan, and Tom Tran.

C﻿SCI 310-01

1﻿7 April 2023

- - -

## Introduction

{{< fragment >}}  

* W﻿hat is the Nanode Bot?

 {{< /fragment >}}
{{< fragment >}}  

* W﻿hat hardware are we using?

 {{< /fragment >}}

{{< speaker_note >}}

* N﻿anode is an Arduino like 8 bit microcontroller board with integrated Ethernet connectivity.
* T﻿he bot portion of the project are the sensors and motors we're using.

H﻿ardware:

* Arduino Uno R3
* Ultrasonic Sensor Module (HC-SR04)
* GY-521 Module (gyroscope & accelerometers)
* ESP32 Camera Module
* IO Expansion Block
* Cell Box (Lithium Ion Battery)

{{< /speaker_note >}}

- - -

## Modules

p﻿ut the images up here, this will not be here in the final slides, i'll get the images here sooner or later

{{< speaker_note >}}

* What do the individual modules do? Camera module, ultrasonic module, GY-521 module (gyroscope & accelerometers), line tracking module.

{{< /speaker_note >}}

- - -

## U﻿ses

{{< fragment >}} 

* W﻿hat are we using the Nanode Bot to demonstrate?

 {{< /fragment >}}

{{< speaker_note >}}

* E﻿xplain what we're using the Nanode Bot to demonstrate: camera module, ultrasonic module, etc.

{{< /speaker_note >}}

- - -

## TB6612

here we will show the diagrams for the modules we're using. might not show the arduino uno r3 diagram bc that's just \*way\* too much. first one up is the **tb6612**.

- - -

## MPU6050 GY-521

diagram for the mpu6050 here. at this slide, we'll also explain why we don't have a diagram for every module we're using -- **COMPLEXITY**! this project was a lot more complex than we thought, so we're making it as simple as possible while still understandable.

- - -

## Beginning Stages of Code

{{< fragment >}} 

* We got lucky

 {{< /fragment >}}

{{< fragment >}} 

* We did **not** copy and paste.

 {{< /fragment >}}

{{< speaker_note >}}

* E﻿xplain that there were a set of files of code that we sifted through in order to fully understand how to operate all of the modules.
* C﻿larify that the code we have are not simply copy and pasted; we went through the painstaking journey of going through thousands of lines of code in order to understand how everything works.

{{< /speaker_note >}}

- - -

## Beginning Stages of Code

W﻿e can show certain screenshots of code that we looked over (not the actual code we worked on yet).

- - -

## C﻿ompiling Our Code

we then clarify what we did with our code.

{{< speaker_note >}}

* What did we mess with coding in prospect with the modules. Most, if not all, of the coding has to do with the modules. Talk about things like the dataset for the object tracking of the camera module, or how the GY-521 works with the motors of the bot in order to keep it heading straight. Things like this. Notes will be refined as soon as possible. This can take up multiple slides to talk about.

{{< /speaker_note >}}

- - -

## Demonstration

we can then try and demonstrate the bot.

- - -

## slide

this is just a messaging area for others who see this before it gets refined. i dont know if i missed anything else, i'll make sure to talk to you guys about that. we can include videos of the processes of what you guys went through with the code, the trial and errors, all that good stuff and whatever.

- - -

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)