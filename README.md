# Blue Pill Challenge 2.2: Button-Blinky

This project contains the code required to test for a button press and blink the built-in LED on the Blue Pill if the button is pressed and stop blinking when the button is released.

<br>
Hardware Requirements and Wiring<br>
Install a button (tactile switch) between pin A12 on the Blue Pill and ground. <br>
<br>
Setup<br>
The default makefile is set up to work with an ST-LINK V2 programming dongle under Linux. For other
setups, open Makefile and edit as required. There are hints in the Makefile for different programming
options.
<br>
Running make will compile and attempt to upload the program to the Blue Pill. Of course the resulting .elf
file can be uploaded manually later.<br>
<br>
Software Requirements:<br>
Editor of your choice<br>
arm-none-eabi-gcc toolchain<br>
make<br>
git-bash (for windows)<br>
STM32_Programmer_CLI.exe Program to upload .elf file to the microcontroller / Blue Pill<br>
