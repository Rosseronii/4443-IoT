# Lab 2: LED Fundamentals

---

## Introduction

In this lab, we were to choose from a variety of different sensors and then connect them to a breadboard along with another different part. I went with a RFID card reader alongside a servo motor. The idea was simple: once the RFID reader detected a specific RFID card code, it would activate the servo. A realistic implementation of this device would be a smart lock. Once the RFID reader checks the specific keycode of the card, it will lock or unlock a door.
---

## Breadboard implementation

Just like it says, this is about gettong one LED powered via the Arduino. To achieve this, one LED was connected to the breadboard. One one rail was the positive side, and on the other rail was the negative side.
In this lab, I connected the resistor to the rail that had the negative side. Upon researching more, I found out that in most cases it does not matter which rail the resistor is connected to. After connecting the resistor, one jumper cable goes from the positive side to a numbered connector on the Arduino (for power from the board and control via code) and another jumper cable goes from the negative side to the ground connector on the Arduino.

I forgot to take a picture of what part 1 looked like, so for now here is the diagram of what it is supposed to look like.

<img src="NFCGIZMO.gif" width="300" />

---
