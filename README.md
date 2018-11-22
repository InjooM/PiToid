# PiToid

## Intro
Small beginner's electronics project with Raspberry Pi Zero

This is a small project I started about mid-way through my first semester as a freshman at the University of Georgia. It is a Raspberry Pi in an Altoids Tin that acts as an emulator for video games through Retropie. In order to have a functioning "gameboy" I needed several components:

-A display
-An audio system
-A power management system
-Controls

## Display
For the display, I am using a 1.8" TFT display sold from Adafruit that came with a display driver. It uses SPI to communicate with the Raspberry Pi, so I designed a compact breakout board, referenced from the Adafruit breakout board, that fit my Altoids tin and used an FPC connector.

## Audio
Audio is WIP

## Power
For power management I am using a 3.7V Li-Poly battery sold by Adafruit, and I designed a battery charger and step-up, referenced from the Adafruit PowerBoost 1000 Charger.

## Controls
For controls I designed a breakout board for the Raspberry Pi and soldered tactile switches onto it, which are connected to the GPIO pins. The Pi is running Adafruit's Retrogame, which configures some GPIO pins as keyboard inputs.

## Final Words
The purpose of this project was not simply to build a DIY gameboy, although I do find gameboys to be fun. I mainly wanted to do this project because I wanted more hands-on experience designing and manufacturing PCB's, as well as putting my circuit analysis skills to the test. Reverse engineering the schematics from Adafruit and reading the datasheets for all the complicated components was difficult, however I believe it helped greatly in developing my electronics design skills. I plan on using these skills in the future for other applications, such as specific instrumentation design.

Most, if not all, of my boards are designed through EAGLE, and fabricated through OshPark. I ordered all my components from Digi-key.
