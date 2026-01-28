# UHF-RFID SAM interface Board
A PCB for connecting UHF-RFID readers to your flipper, and a SEC1210 iC to allow you to interface and use a SAM.
Also has a 6 pin ICSP header and an SPI header to use with various FAPs.

This board is made for the flipper zero and uses https://github.com/frux-c/uhf_rfid for the UHF-RFID part, and https://github.com/bettse/seader for the SAM part.
The SPI and ICSP headers on this board are here for use with the SPI_Mem_Manager fap, and the AVR_Flasher fap respectively, among, I'm sure, others faps.

Thanks to the UHF|RFID gang over on the flipper zero discord for all the nice comments, all the info, and especially, the initial push on the UHF|RFID project!


This repository is meant to be used as a reference for users to be able to build/debug their own boards. Making boards for you and your friends is absolutely permitted.
If you want to make my board for yourself or free distribution, I only ask you keep the links present on the boards linking to this repository, as well as my name.
Comercial sales of boards ***using my design*** are not allowed unless you contact me first and we reach an agreement.
