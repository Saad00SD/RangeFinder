By Saad Fahim.
CS 3rd Sem
COAL Project ( Range Finder )

-----------------------------------------------------

---How to burn HEX file into 8051 Microcontroller.---

-----------------------------------------------------

1.Set Arduino as ISP
2.Upload the ISP code into Arduino Uno Board
3.Open CMD 
4.Enter code like this;;


"C:\Users\saadf\Downloads\arduino-1.8.19-windows\arduino-1.8.19\hardware\tools\avr\bin\avrdude.exe" 
-C C:/AVR8051.conf -c stk500v1 -P COM5 -p 89s51 -b 19200 -U flash:w:"C:\8051\Hex Files\COAL_Project 2.hex":a

----------------------------->
Code Format
_____________

"<arduino avrdude location>"-C :/AVR8051.conf -c stk500v1 -P COM<Port Number> -p 89s51/2 -b 19200 -U flash:w "<hex file location>" :a

_____________


NOTE:::: Make sure to save AVR8051.conf file in the Local Disk C ::::