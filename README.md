# bliepill-HID
Human Interface Device (HID) example for the bluepill (STM32F103C8T6)

Last night as I couldn't sleep I had the idea that I should see if the bluepill, which I made a [build](https://github.com/alxhoff/bluepill) for a couple of days ago could do USB HID, aka could the bluepill send HID commands to the computer and emulate a mouse or keyboard.

I played around with this a few years ago when I was working on [this](https://github.com/alxhoff/STM32-Mechanical-Keyboard) keyboard project. But the project has been dead for a while and the code itself isn't exactly great. But after how quick and easy it was with a bluepill I might just revive the old project.

This repo contains two example, one is a pure CubeMX generated example, then modified to be either a mouse and keyboard and a user defined build using the [bluepill cmake build](https://github.com/alxhoff/bluepill). Each can be found in the respective folders in this repo.