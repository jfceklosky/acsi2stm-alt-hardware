# acsi2stm-alt-hardware
Alternate PCB designs for the acsi2stm using a DB-19 or and IDC-20 connector

  - **db19**: contains the EasyEDA schematics, schematic pdf, and PCB layout for the DB-19 board
  
  - **idc20**: contains the EasyEDA schmeatics, schematic pdf, and PCB layout for the IDC-20 board
  
  - **gerbers**: contains various standard generated PCB gerber files as zip files

  - **images**: renders of each of the boards

# Description
The db19 uses soldered in pins that plug into the Atari ST's DMA port while the idc20 uses and Ultrasatan style IDC-20 and ribbon cable to connect to the ST's DMA port.  

These boards are designed and tested to work with the software from this project:
  https://github.com/retro16/acsi2stm
  
Versions 3.X and 4.X will work.

The Ultrasatan style board can be found here:  https://github.com/jfceklosky/idc2ribbon

# Building
The gerbers can be used with various PCB manufacturers like JLBPCB, PCBway, and others.

Links to a source for each of the major components:

|Parts            | Source links                                |
| :---            | :---                                        |
| SD card         | https://www.amazon.com/gp/product/B08CMLG4D6/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1 |
| STM32 Blue Pill | https://www.amazon.com/gp/product/B07VKSVM21/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1 |
| Battery Holder  | https://www.digikey.com/en/products/detail/mpd-memory-protection-devices/BS-7/389447 |
| DB19 Pins       | https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/9103-0-00-80-00-00-08-0/7322902|
| db-25 Female (cut down) | https://www.digikey.com/en/products/detail/norcomp-inc/171-025-213R001/858148 |
| db-25 Male (cut down) | https://www.digikey.com/en/products/detail/norcomp-inc/171-025-113R001/858139 |
| 100 uF Cap | https://www.amazon.com/gp/product/B096QSKNP2/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1 |
| IDC 20 Male | https://www.amazon.com/uxcell-16-Pin-Straight-Connector-Sockets/dp/B010V43ACO/ref=sr_1_4?crid=1G2HM3EDUJ1RP&keywords=idc+20+male+solder+in&qid=1689535789&s=electronics&sprefix=idc+20+male+solder+in%2Celectronics%2C99&sr=1-4} |
| Pin Headers 2.54 mm | https://www.amazon.com/gp/product/B07VNXL5BD/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1 |
| CR 2032 | https://www.amazon.com/Amazon-Basics-Lithium-Resistant-Packaging/dp/B08J4QR18R/ref=sr_1_12?crid=3DT82X3FY3ZTL&keywords=cr+2032&qid=1689538157&s=electronics&sprefix=cr+2032%2Celectronics%2C121&sr=1-12 |
| Round Header M/F pins 2.54 mm | https://www.amazon.com/gp/product/B07BS126FK/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1 |


# Board Images
**DB19** 
![db19_image](images/db19.png)

**IDC20**
![idc20 image](images/idc20.png)
