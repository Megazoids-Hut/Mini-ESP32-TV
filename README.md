# Mini ESP32 TV (remix)

![1_s](https://github.com/user-attachments/assets/1714ddee-1a2a-4d19-bdf6-d33a364765dd)


The project is a reworking of [Moononournation's Mini Retro TV](https://www.instructables.com/Mini-Retro-TV/). New case, PCB, code alterations for added fuctions (I had help!) and a movie file converter program. 

I've already splattered this project all over the Internet, but I wanted the files accessable on GitHub. It's posted on the following sites, which will have full build instructions :  
https://www.hackster.io/megazoid/mini-esp32-tv-remix-797a71  
https://www.instructables.com/member/Megazoids%20Hut/instructables/drafts  
https://www.thingiverse.com/thing:6330378  

> YouTube Demo : https://www.youtube.com/watch?v=mP0zoM2Ufms  


- [Supplies](#Supplies)
- [Story](#Story)

# Supplies

![5_s](https://github.com/user-attachments/assets/c64748a8-c6c0-4799-8fb2-880fb498b689)



1 x 1.69 Inch LCD display module (LCD Module - Square edges) [AliExpress](https://vi.aliexpress.com/item/1005003762571358.html)  
1 x D1 mini ESP32 - CH9102 Micro USB [AliExpress](https://vi.aliexpress.com/item/32816045916.html)  
1 x Max98357 I2S module [Aliexpress](https://vi.aliexpress.com/item/1005006711010527.html)  
4 x 10k SMD resistors (size 0805) 1/8W [Aliexpress](https://www.aliexpress.com/w/wholesale-10k-SMD-resistors-0805-1%252F8W.html)  
1 x 5.1k SMD resistors (size 0605) [Aliexpress](https://www.aliexpress.com/w/wholesale-5.1k-SMD-resistors-0603.html))  
1 x 9pin Micro SD card slot connector [LCSC.com](https://lcsc.com/product-detail/SD-Card-Connectors_G-Switch-GT-TF003-H0185-01_C5155563.html)  
1 x Battery Charger Boost Module TP4056 [Aliexpress](https://vi.aliexpress.com/item/1005005522998695.html)  
1 x 5.8x5.8x7mm Tactile Push Button Latching 6 Pin [AliExpress](https://vi.aliexpress.com/item/32948292577.html)  
1 x 6x6mm 9.5mm(total height) Momentary Push Button Switch [Aliexpress](https://www.aliexpress.com/w/wholesale-6x6mm-Momentary-Push-Button.html)  
1 x Ghxamp Mini Speaker 8Ohm 1W 34.8mm11.2mm6.0mm [Aliexpress](https://vi.aliexpress.com/item/33035261832.html)  
2 x M2*8mm Black Hex Countersunk Screws (total length 8mm) [Aliexpress](https://www.aliexpress.com/w/wholesale-M2-8mm-Black-Hex-Countersunk-Screws.html)  
1x Lithium battery 602535 or 603035 [Aliexpress](https://www.aliexpress.com/w/wholesale-Lithium-battery-602535.html)  
1 x Micro USB 4Pin Male Plug connector [Aliexpress](https://vi.aliexpress.com/item/32992732747.html)  
2 x 40-pin Header Pins 2.54mm Male Single Row [AliExpress](https://vi.aliexpress.com/w/wholesale-2-x-40%2525252dpin-Header-Pins-2.54mm-Male-Single-Row.html)  

Other Parts :  
1 x 32GB Micro SD Card  
Black and Red Silicone Wire (around 26AWG)  
Heat Shrink Tubing (optional)  
Brown, Black and Grey PLA+  

The PCB can be ordered from a PCB fabrication manufacturer Like JLBPCB : [Gerber File Zip](https://github.com/Megazoids-Hut/Mini-ESP32-TV/blob/main/gerber/Gerber_Mini_Esp32_Tv.zip) (Use default PCB board settings. 1.6mm thickness etc. Just upload the gerber zip and order)
Notes : When ordering parts, make sure they correspond with the ones in my pictures.For example there are two (or more) different 1.69 LCD displays out there, and many different D1 mini's

# Story

This Mini ESP32 TV project is remix of Moononournation's [Mini-Retro-TV](https://www.instructables.com/Mini-Retro-TV/) Instructable. I wanted to try something with a PCB, and the slightly cheaper D1 mini ESP32. It has a front facing on/off button, and a single multi function button that can change movie clips forwards and backward and mute the TV if needed.

**Licensing**: My PCB Gerber files and STLs are released under [The Unlicense](https://unlicense.org/). Everything else retains the licenses assigned by their creators.I take no responsibility for anything.

**Notes #1:** Some adjustment of the front panel STL might be needed to completely centre the LCD display module with the screen bezel.

**Notes #2:** The bin file's code source is unavailable.



