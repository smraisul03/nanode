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
  preview_only: false
  caption: Nanode in his natural habitat
  alt_text: ""
  filename: featured.jpg
  focal_point: smart
categories: []
---
{{< slide background-image="featured.jpg" >}}

# Nanode Bot

by Ariya Seng, S M Raisul Alam Bhuiyan, and Tom Tran 

C﻿SCI 310-01-SPRING-2023

**0﻿4/17/2023**

- - -

## Introduction

{{< fragment >}}  

* W﻿hat is the Nanode Bot?
  {{< /fragment >}}

{{< speaker_note >}}

* Nanode is a 4-wheel smart robot that can move around in all four directions
* Nanode can also do basic object detections as well via the camera & sensor modules

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

* The heart of Nanode Robot is the Arduino Uno R3

{{< fragment >}}  

* Due to it simplicity, availability, and affordability, it is one of the best candidate to have
  {{< /fragment >}}

{{< speaker_note >}}

* Arduino Uno R3
  {{< /speaker_note >}}

- - -

{{< slide background-image="arduinounor3.png" >}}

- - -

* The next part is the custom board with the driver chip, TB6612

{{< fragment >}}  

* This hardware is especially useful in the ability for us to control the robot
  {{< /fragment >}}

{{< speaker_note >}}

* TB6612 allows us to control the other parts of the movement, such as the wheels 
  {{< /speaker_note >}}

- - -

{{< slide background-image="tb6612.png" >}}

- - -

* The next part is the gyroscope module GY-521, which allows us to actuate the control motion for Nanode

{{< fragment >}}  

* This hardware lets us determine the speed, control movement, and so forth 

\*﻿ The driver chip inside of the GY-521 is the MPU6050 chip, which is used later for control
  {{< /fragment >}}

{{< speaker_note >}}

* GY-521
  {{< /speaker_note >}}

- - -

{{< slide background-image="mpu60503.png" >}}

- - -

## Software Design

{{< fragment >}} 

* W﻿hat are we using the Nanode Bot to demonstrate?

 {{< /fragment >}}

{{< speaker_note >}}

* E﻿xplain what we're using the Nanode Bot to demonstrate: camera module, ultrasonic module, etc.

\*﻿ The nanode bot's original function required us to use a remote controller to control the movement of the bot. We wanted to implement the idea where the robot doesn't require a controller for it to function. 

*  We then implemented a "follow mode" that allows the nanode bot to auto-detect an object in front of its' ultrasonic sensor and follow it on its own. 

\*﻿ The nanode bot also uses a ESP32 camera module to detect and recognize faces. 

* The camera can also be live streamed through the camera wi-fi.



{{< /speaker_note >}}
- - -

{{< slide background-image="ultrasonicsensor.png" >}}

- - -

{{< slide background-image="ultrasonicwithbody.png" >}}
- - -


* Languages that are used in the programming of Nanode are

{{< fragment >}} 

\*﻿ C 

* C﻿++

\* Arduino Programming Language

 {{< /fragment >}}

{{< speaker_note >}}

* E﻿xplain as well as to the importance of using those languages 
  ﻿* C++ because it is easier for us to do some HLL abstraction, which comes in handy with some of the code*
  ﻿ Arduino native language because it is easier to support with some of the aspect of initialization with the Uno R3
  {{< /speaker_note >}}

- - -

## PID Algorithm & Datapath

* Proportional Integral & Derivative (PID) Algorithm is used for control loop movement of Nanode's wheels
* The equation of the PID can be seen below:

{{< fragment >}} $u(t) $ {{< /fragment >}}
{{< fragment >}} $ = K*p e(t) $ {{< /fragment >}}
{{< fragment >}} $ + K_i \int*{0}^{t} e(t)dt $ {{< /fragment >}}
{{< fragment >}} $ + K_d \frac{de(t)}{dt} $ {{< /fragment >}}

{{< speaker_note >}}

* Should also mention that the PID algorithm is directly based upon the TB6612 driver chip, and the datapath it is using to direct from that point
* Allows Nanode to freely move, yet also stay focused in the direction it is heading in

{{< /speaker_note >}}

- - -

{{< slide background-image="mpu60503.png" >}}

{{< speaker_note >}}

* From the PID Algorithm, we have successfully derivative from the datapath

{{< /speaker_note >}}

- - -

## Angular Velocity

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

{{< fragment >}}

* W﻿hat is the Nanode Bot? {{< /fragment >}}

{{< fragment >}}

- - -

# Questions?