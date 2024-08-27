# EvilCrow-h-RAT
DIY : https://www.youtube.com/watch?v=oAPZG4rk3v0&amp;t=5s


 bought Evil Crow device on online shopping and much simplier.

Material:
2 x ESP 32 
2 x CC1101 
1 x SD Card Module
1 x SD card
Kabel wiring
PCB
2 x Push Button 

Wiring CC1101 to ESP32

 ECRF         Jammer
 ------------------------       ------------
 Mod 1  Mod 2

SCK 14  14  14
MISO 12  12  12
MOSI 13  13  13
------------------------------------------------
CSN 5  27  27
GDO 2  25  25
GD02 4  26  26
------------------------------------------------
Push Button
-----------
Button 1   34 : 5V ESP32  Resistor 10K to D34 ESP32, then connect to D4 ESP32 to Switch to GND ESP32

Button and Battery wiring: https://www.mediafire.com/file/uzcwgs...

Micro SD
----------
SCK 18
MISO 19
MOSI 23
CSN/SS 22

Note:
For ECRF I only use 1 x CC1101 Module 2, so please setting in CC1101 menu connect to ECRF SSID Password 123456789, web menu 192.168.4.1 to Module 2 both Transmitter & Receiver 
Button 2   35 do the wiring as per Button 1 logic
