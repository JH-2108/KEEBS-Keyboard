---
title: "KEEBS keyboard "
github: "https://github.com/JH-2108/KEEBS-Keyboard/blob/main/README.md"
description: "A custom-designed 80% mechanical keyboard featuring a traditional TKL layout, soldered on switches, and a custom PCB. The keyboard will include an integrated side-mounted display for showing information such as time, volume, and keyboard settings, alongside a rotary encoder for volume control and menu navigation. The project will involve PCB design, embedded firmware development, and custom 3D-printed enclosure design. "
created_at: "2026-10-30"
total_time: "5h"
---

# October 30, 2026: Created the BOM.csv and readme.md
<!-- fabricate:entry 1633 -->

Before I go and work on the PCB design for the entire keyboard, I went and create the readme.md, this readme tells me what I would have to do, what kinds of components I need, what my keyboard layout would be like, what other components besides the keys would be on the keyboard and how I would put the firmware for the keyboard. 

As for the bom, I went online and search for vendors and purchase links, finding shops that sells enough of those keycaps, or stabilizers and diodes that this project would need, counting the total amount of money that I would need in this project and what tier this project should be counted as. 

![](https://fabricate.hackclub-assets.com/4f960f26080aa68bf7e5353015603359d4ca980b5f947176b5407c4ba6cd639f/image-png/image.png)

**Total time spent: 1h 30m**

# November 7, 2026: Designed the entire schematics and PCB
<!-- fabricate:entry 2268 -->

After writing my readme.md and the bom.csv, I went on to design the entire schematic, showing the planned connections for each key. Using the KEEB tutorial page, I learnt how to connect all of the keys together in a matrix, where each row and column is connected to one GPIO pin on the raspberry Pi Pico. After finishing the connections for the entire schematic, I realized there was also a file online for the SSD1306 0.96 inch OLED screen that I can use on this project, I then went back to the schematics to make changes to that. 

The next step was to definitely assign the footprints, you won't believe the amount of footprints that I had to assign for the 65 keys that this 60% keyboard had (including the diodes for each one of them), I turned on my auto-clicker, and just let it place it down automatically, such an efficient and easy way to assign the footprints.

![](https://fabricate.hackclub-assets.com/0aeac708fcb06730ef2dd8b03a8d685cb81cc9b5d06e0480684fae242839f78a/image-png/image.png)

Here comes the next step, routing the entire PCB, this one took the longest considering that there were many vias, the connections are quite confusing and I had to find the best path for each track to follow, taking me a very long time to route the entire PCB together. But anyways, I've done it in the end, and I have also assigned a CAD model to each of the key switches, however, their keycaps and stabilizers haven't been assigned (I would go and download their model from GrabCAD later and then add them when I design the case all together). 

![](https://fabricate.hackclub-assets.com/bf256a94aba5987badb03ad791b1cfa367c3ef8e2765b3f55f7699034a877101/image-png/image.png)

**Total time spent: 3h 30m**
