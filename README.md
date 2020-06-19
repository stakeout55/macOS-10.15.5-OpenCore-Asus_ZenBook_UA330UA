# macOS-10.15.5-OpenCore-Asus_ZenBook_UX330UA
This is my working EFI for the Asus Zenbook UX330UA. 
Everything has been tested, including HDMI and works flawlessly. 
A note about the intel wifi / bluetooth card. It will never work so I purchased this card: [BCM94360NG](https://www.ebay.com/itm/M-2-NGFF-Network-Card-for-Broadcom-BCM94360NG-better-than-BCM94352Z-DW1560-BT4-0/264663343680?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649) and both WiFi and bluetooth worked natively on both Windows 10 and Catalina out of the box.

It is also important to note that for me, BIOS had to be on version 311 in order to work successfully. Please see [this guide](https://github.com/hieplpvip/ASUS-ZENBOOK-HACKINTOSH) for details (note that the original linked guide is clover and my repo is OpenCore)

General Setup and hack guide here: [dortania.github.io](https://khronokernel.github.io/Opencore-Vanilla-Laptop-Guide/)

System Spces:
* Intel Core i5-7200U
* Intel HD Graphics 620 2GB
* 8 GB Ram
* BCM94360NG WiFi/Bluetooth Card

Things to work on:
* For me, this is a Dualboot with windows 10 and in order to do so I have to boot Win 10 from the boot menu on my BIOS, the trackpad and keyboard do not work when I boot from OpenCore menu.
