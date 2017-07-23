# Renesas-S3A7-SSP1.2.0

In this tutorial, you will learn to upgrade/install latest Board Support Package(BSP) version 1.2.0 for Renesas S3A7 Fast Prototyping board. 

This allows developers to create application like Internet of things (IoT) using Renesas Synergy Software Platform (SSP)1.2.0 or above driver/frameworks. 

Included Blinky Demo Project which can be tested easily on the board OR follow screen shots to build your own Blinky Project. Renesas SSP create complete source.

# Prerequisites:

1) S3A7 IoT Fast Prototyping Kit including the J-Link debugger. Product details

https://www.renesas.com/en-us/products/software-tools/boards-and-kits/renesas-synergy-kits/renesas-synergy-s3a7-prototyping-kit.html

2) Renesas e2 studio - latest version is 5.4.0.018 as of 6/13/2017. - Need to signup to download this software.

https://www.renesas.com/en-us/products/synergy/gallery.html  


3) Renesas Synergy Software Package SSP v 1.2.0 (not available part of E2Studio, but required for this board). Board Support Package can be downloaded from this github link

4) Segger J-Flash Lite 6.14a or later.

https://www.segger.com/downloads/jlink/

To install E2Studio follow this book Chapter 4

https://www.renesas.com/en-us/products/synergy/book.html

1. Import BSP1.2.0 to E2Studio

 a. Download Board support pacakge from here

https://github.com/RaspiRepo/Renesas-S3A7-SSP1.2.0/blob/master/Renesas.S3_IOT_BOARD.1.2.0-b.1.1.pack
 
 b. Open E2Studio in workspace.
 c. File->Import-> Select "CMSIS Pack".  OR 
 
Other option directly copy userpack into "C:\Renesas\e2_studio\internal\projectgen\arm\Packs"

2. Download Blinky Project from this github.

https://github.com/RaspiRepo/Renesas-S3A7-SSP1.2.0/blob/master/2017-06-13_s3a7_Blinky_ssp1_2_v0.zip

3. Import project into Workspace.
4. Build and install Blinky application into S3A7 board. 

# Summary 
All 4 LED's blinks.  E2Studio create all required source code to blink onboard LEDs (No coding required).

For addiotional help check out screen shots.

Many other tutorials can be found here

http://learn.iotcommunity.io/
