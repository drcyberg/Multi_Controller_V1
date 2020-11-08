# Multi Controller V1

---

## Description:

It can display: Everest stats, Speedfan stats, MBM stats (your CPU temp, fan/cooler speed, etc), BBC World News (or any other RSS feed!), WinAmp stats (currently playing tracks title, length, position, etc), Network stats (speed, total bytes, etc), CPU Speed, Disk available/free, memory usage, Email details, game stats, and many more...
Grabs information from the kernel and some subsystems and displays it on an external liquid crystal display.
The Multi Controller V1 modules are designed to fit into 5,25" drive bays. They contain an LCD display that is 20 characters wide and 2 lines high surrounded by 2 buttons labeled Fan+, Fan- controlls with LED indicator and Buzzer, and controlls RGB Leds Strip.
The Multi Controller V1 modules are connected to the PC using a USB connection getting operating power using the standard HDD/CD/DVD drive power connector.

---

## Specifications:

- Bars can be linear or logarithmic
- Can display user-defined icons, and these icons can even be animated
- CPU utilisation: user, nice, system, busy, idle
- Memory statistics: total, used, free, available, shared, buffers, cached
- Disk statistics: read/written blocks or bytes
- Network statistics (LAN and PPP): packets or bytes received/transmitted
- ISDN statistics: bytes in/out; ISDN connected (very useful if connected to a LED with a GPO!)
- Temperatures: Up to 9 temperature sensors can be displayed
- APM: battery percentage, status and duration
- PPP: bytes read and written (useful for xDSL connections!)
- DVB (Digital Video Broadcast, i.e. a digital satellite receiver card): Signal Strength and Signal/Noise Ratio
- Mail and News: local, POP and IMAP mailboxes, unread news messages from NNTP
- Seti@home: % completed, CPU time needed
- WIFI: link, signal level, noise
- MySQL: statistics from a MySQL database
- XMMS: infos from the XMMS player
- The output of external commands can be displayed
- Arbitrary lines from a text file can also be displayed

---

## Extra Additionals:

- RGB Led Strip controller (SMD 2835 RGB; 12V/1,5A)
- PC 2 Fan controller (PWM 50% or 100%; 12V/1,5A)
- Fans LED indicator
- Buzzer speakers for ones push button feedback
- USB I2C slide switch buttons
- USB connection interface
- ICSP connection header (Programming interface)
- TX/RX LED indicators
- Adjustable LCD contrast
- Reset button
- LCD 1602A (16X2) Display connection interface
- Based on the Atmega328P chip

---

## Samples:

![](/Documents/1.jpg)
![](/Documents/2.jpg)
![](/Documents/3.jpg)
![](/Documents/8.jpg)
![](/Documents/7.jpg)
![](/Documents/6.jpg)
![](/Documents/5.jpg)
![](/Documents/9.jpg)

---

## Firmwares:

- [Without Bootloader](https://github.com/drcyberg/Multi_Controller_V1/blob/master/Firmwares/multi_controller.hex "Without Bootloader") (Development users)
- [With Bootloader](https://github.com/drcyberg/Multi_Controller_V1/blob/master/Firmwares/multi_controller_with_bootloader.hex "With Bootloader") (Normal users)

---

## Softwares:

- [LCD Smartie](http://lcdsmartie.sourceforge.net/ "LCD Smartie") (Windows)
- [LCDproc](http://lcdproc.omnipotent.net/ "LCDproc") (Linux)
- [LCD4Linux](https://lcd4linux.bulix.org/ "LCD4Linux") (Linux)

---

## How to flash:

- [Guide](https://www.arduino.cc/en/Guide/ArduinoISP "Guide")
- [Tutorial](https://www.arduino.cc/en/tutorial/arduinoISP "Tutorial")

---

## BOM (Bill Of Materials): [View](https://htmlpreview.github.io/?https://github.com/drcyberg/Multi_Controller_V1/blob/master/Documents/multi_controller.jpg "View")

---

## PCB Gerber file: [Download](https://github.com/drcyberg/Multi_Controller_V1/blob/master/Manufacturing/multi_controller.zip "Download")

---

## 3D Model:

![](/Documents/multi_controller.jpg)

- [Bay](https://github.com/drcyberg/Multi_Controller_V1/blob/master/stl/multi_controller.stl "Bay")

## Required other parts:

- 8x M3 4mm screw
- 8x M3 4mm insert nut
- 1x M3 nut
- 1x M3 10mm screw

---

## Thingiverse: [Link](https://www.thingiverse.com/thing:4270109 "Link")

---

## If you want to support me: [Donate](https://www.paypal.me/Kunee82 "Donate")

---

## Have a nice day!
