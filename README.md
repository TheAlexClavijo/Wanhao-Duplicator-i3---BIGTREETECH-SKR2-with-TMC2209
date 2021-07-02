# Wanhao Duplicator i3 - Firmware SKR 2 + TMC2209
Firmware for Wanhao Duplicator i3 with BIGTREETECH SKR 2 board & TMC2209 Drivers

<img align="center" width=100% src="https://user-images.githubusercontent.com/86481337/124321334-cfe1aa80-db7d-11eb-856c-7e5d3ff10942.jpg" />

Your hardware:

1- BIGTREETECH SKR 2 (Mosfet HY1904)

2- BIGTREETECH TMC2209 V1.2 Drivers

3- BIGTREETECH TFT35-E3.0 V3.0 (Optional but recommended)

Install firmware in your 3D Printer:
- Copy the file "firmware.bin" in a SD card (no bigger than 16GB) formatted in FAT
- Insert the SD card into the SD slot of the BIGTREETECH SKR 2 board
- Reset or turn off/on the BIGTREETECH SKR 2 board
- Check that the file "firmware.bin" on SD Card changed the extension to: "FIRMWARE.CUR". 
- Done!, The firmware is uploaded!. 

HARDWARE BOARD SKR 2:

BIGTREETECH with TMC2209 in UART Mode (Jumpers)
A very frequent question is how many jumpers and in what position they must be on the SKR 2 board to achieve UART Mode. For this, you have to do the following:

- 2 jumpers in TMC slot for X stepper (see "https://github.com/TheAlexClavijo/Wanhao-Duplicator-i3---BIGTREETECH-SKR2-with-TMC2209/blob/main/Wanhao%20Duplicator%20i3%20-%20SKR%202%20wiring.jpg") if you will use SENSORLESS
- 2 jumpers in TMC slot for Y stepper (see "https://github.com/TheAlexClavijo/Wanhao-Duplicator-i3---BIGTREETECH-SKR2-with-TMC2209/blob/main/Wanhao%20Duplicator%20i3%20-%20SKR%202%20wiring.jpg") if you will use SENSORLESS
- 1 jumper in TMC slot for Z (ZA & ZB) stepper (see "https://github.com/TheAlexClavijo/Wanhao-Duplicator-i3---BIGTREETECH-SKR2-with-TMC2209/blob/main/Wanhao%20Duplicator%20i3%20-%20SKR%202%20wiring.jpg")
- 1 jumper in TMC slot for E0 stepper (see "https://github.com/TheAlexClavijo/Wanhao-Duplicator-i3---BIGTREETECH-SKR2-with-TMC2209/blob/main/Wanhao%20Duplicator%20i3%20-%20SKR%202%20wiring.jpg")

#Following the next guide, you can see the jumpers position for UART mode: (https://github.com/bigtreetech/SKR-2/blob/master/Hardware/BIGTREETECH%20SKR%202%20user%20manual.pdf)

INTERESTING: For install the board inside the box in our Wanhao Duplicator i3, I used this STL. You can download STL here:
(https://www.thingiverse.com/thing:4587387)


* HARDWARE TFT35-E3 V3.0 (OPTIONAL, BUT RECOMMENDED):

In order to give my Wanhao Duplicator i3 a new and improved life, I opted to purchase the TFT35-E3 V3.0 display from BIGTREETECH. The display offers the option of combining the Marlin LCD mode and the TFT mode. I prefer the TFT mode as it offers a lot more configuration options to the 3D printer, as well as giving it a fresh look.
I am attaching the updated firmware (I am using) with the TFT bootscreen that I designed for Wanhao i3 (powered by BIGTREETECH). I hope you like it!

Install firmware in your TFT35:
- Copy all files and folder included in the folder TFT35 in a SD card: "BIGTREE_TFT35_V3.0_E3.27.x.bin", "language_es.ini" and folder "TFT35"(SD no bigger than 16GB and formatted in FAT)
- Insert the SD card into the SD slot of the Bigtreetech TFT35-E3 V3.0
- Reset or turn off/on the BIGTREETECH TFT35-E3 V3.0
- Update will start 

INTERESTING: If your Wanhao Duplicator i3 is from the first generations. I designed a frame where the TFT35 screen fits perfectly as it is slightly larger than the stock LCD. You can download STL here:
(https://www.thingiverse.com/thing:4859228)

#NOTE: You can download the latest TFT firmware here: (https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware)


IMPORTANT: After configuring all the Marlin files and compiling the firmware, it is checked and functional on my Wanhao Duplicator i3 3D printer. This does not mean that it can work properly on your 3D printer. Please use it at your own risk.
