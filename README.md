# akeyboard
A custom 68 key mechanical keyboard which is QMK and VIA compatible

## Why
I started this project as I wanted a mechanical keyboard, so I decided to build it

## How 
1. First i made the [Keyboard Layout](https://www.keyboard-layout-editor.com/#/gists/36fe0ae4e5de0a0816a001b01f11648a) in keyboard-layout-editor, this gave me the idea of how I wanted the keyboard to be and the wiring matrix and the key summary
2. Then i got the layout into [QMK](https://qmk.fm/), defined the matrix and keymapped the keyboard 
3. Then I choose a microcontroller, I choose the raspberry pi pico h as the microcontroller as I had that one in my house, it was a bit hard to make the firmware for it as not much docs on it and was quite new to hardware
4. Then flashed the firmware onto the microcontroller and Ta da, I had a working keyboard but not a mechanical one 
5. I also made it [VIA](https://caniusevia.com/) compatible for easier keymaping 

### The problem
- but i never assembled it as i dont have a accessible 3D printer that i could use, I asked my school if i could use the 3D printer that was there in the school that no one used but they said no, sad 
- also because of the high mx switch prices

## Current Status
The firmware and keyboard matrix design are complete and tested on the microcontroller

The keyboard has not yet been assembled because the case and keycaps require a 3D printer to print, so the physical build is currently pending

## Components needed
- 1 raspberry pi pico h
- 3D printer 
- 68 mx switches
- 68 diodes to prevent ghosting and more
- i have made custom size of keys so just print the keycaps given as the premade purchasable ones wont fit 
- 16 M2 screws 
- wires as needed 

![image alt](https://github.com/deepdass/akeyboard/blob/18e11f1e9356c34f349c3b6af449c7cb92039433/diagrams/visionig/Screenshot%202025-02-03%20152631.png)

![image alt](https://github.com/deepdass/akeyboard/blob/18e11f1e9356c34f349c3b6af449c7cb92039433/diagrams/visionig/Screenshot%202025-03-02%20173529.png)

![image alt](https://github.com/deepdass/akeyboard/blob/18e11f1e9356c34f349c3b6af449c7cb92039433/diagrams/visionig/Screenshot%202025-03-02%20173341.png)

## Whats next 
- build this and fix any problem with the design but probably will build the split ergonomic keyboard first(WIP), 
- might make a docs on this like showing the whole process, also the problems i faced and solutions i came up with and easier and time saving ways of doing some things but i dont think im good at making appealing docs  
