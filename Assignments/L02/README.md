# Lab 2: LED Fundamentals

---

## Introduction

In this lab, we were to choose from a variety of different sensors and then connect them to a breadboard along with another different part. I went with a RFID card reader alongside a servo motor. The idea was simple: once the RFID reader detected a specific RFID card code, it would activate the servo. A realistic implementation of this device would be a smart lock. Once the RFID reader checks the specific keycode of the card, it will lock or unlock a door.
---

## Breadboard implementation

This time I used a smaller breadboard, with the RFID sensor connected directly to it. Right behind the sensor are multiple jumper cables that connect to different digital connectors on the Arduino. Connected nearby those connectors is a jumper cable for the signal input/output of the servo. The servo also connects to the arduino for power and ground. I tested with two different codes, as I realize you can use your phone or watch to scan the RFID sensor. One code was more secure, only allowed a specified tag ID entry. This required me to find the ID of the tag that came with the RFID sensor using code. Once found, it only activated with that tag. I also tried another route, which just allowed any tag through. That part was fun because I got to watch a servo rotate when my phone touched the sensor. THe reason it had to be any tag allowed through is due to the fact that phones and other mobile devices are more secure, with their base tag changing every scan. To only allow my phone to scan it, I would have to use external software to mess it with.

Below is it in action. Watch as it goes

<img src="NFCGIZMO.gif" width="300" />

---
