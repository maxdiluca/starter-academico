---
title: Stimulus timing
subtitle: We think computer are infallible, but when it comes to generating multisensory stimuli their timing can fall short.
date: 2021-04-11T22:41:39.165Z
summary: ""
draft: false
featured: true
authors: []
external_link:
links:

image:
  filename:   
  focal_point: Smart
  preview_only: false
---
Correct timing (whether it is measuring reaction time, presenting synchronous multisensory stimuli, or providing online feedback) is fundamental in several types of psychophysical research. The connections between the different components of digital computers introduce delays and asynchronies in the stimuli presented and in the recorded response time. It is possible to measure such delays by using sensors tailored to the stimuli produced by the apparatus and by record their signals in parallel. Sensors of multiple types can be utilized, as long as the delay that they introduce is minimal when compared to the one produced by the examined apparatus. The two most important sensors in my research are photodiodes and microphones. By employing these two sensors, recording can be done using an ubiquitous analog-recording device of modern computers: the audiocard.  
To record the asynchrony introduced by the difference in delay between audio and visual acquisition of a videocamera, for example, it is possible to capture physically synchronous audiovisual stimuli as seen in the movie. By placing the light sensor on the monitor and recording the sound with the microphone it is possible to measure the relative timing and hence the artifactual asynchrony (Maier, Di Luca, Noppeney, 2010).
To measure how much time is required to change the position of an image on the screen in response to a movement (as it happens in the case of Virtual Reality environments or in response to the movement of a mouse), it is possible to use two light sensing devices coupled with two images of a gradient going from white to black (Di Luca, 2010). One gradient is created with a static image, the other gradient is displayed on the screen and moves according to the mouse, for example. One light sensing device is attached to the screen and it captures the change in color of the gradient that moves, the other device is attached to the mouse and it is pointed to a static image of a gradient. As the mouse move, the light captured by the device attached to it changes. After some lag the image on the screen will move and so also the light captured by the other device will change. The difference in the two signals indicates how much delay is due to the computer that displays the image (code to do this computation can be found here).
