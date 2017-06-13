  # Renesas-S3A7-SSP1.2.0

In this tutorial, you will learn how to update latest Board Support Package(BSP) version 1.2.0 for Renesas S3A7 Fast Prototyping board.
This allows develop Internet of things application using Renesas Synergy Software Platform (SSP)1.2.0 or above driver/frameworks. 

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
 a. Open E2Studio in workspace.
 b. File->Import-> Select "CMSIS Pack".  OR 
 
Other option directly copy userpack into "C:\Renesas\e2_studio\internal\projectgen\arm\Packs"

2. Download Blinky Project from this github.
3. Import project into Workspace.
4. Build and install Blinky application into S3A7 board. 

# Summary 
All 4 LED's blinks.

For detailed tutorial with screen shot.. Go Here




