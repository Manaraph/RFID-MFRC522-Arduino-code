# RFID-MFRC522-Arduino-code
> Clone the repo
```
git clone https://github.com/manaraph/RFID-MFRC522-Arduino-code.git
```
## Typical pin layout used:

 Signal    |     MFRC522 Reader/PCD Pin | Arduino Uno Pin|    Arduino Mega  Pin     | Arduino Nano v3 Pin     |  Arduino Leonardo/Micro Pin            | Arduino Pro Micro Pin         |
 ----------|----------|-----------------|-------------|-----------|------------------|----------
 RST/Reset |  RST     |     9           |      5      |   D9      |   RESET/ICSP-5   |  RST
 SPI SS    |  SDA(SS) |     10          |      53     |   D10     |   10             |  10
 SPI MOSI  |  MOSI    |     11 / ICSP-4 |      51     |   D11     |   ICSP-4         |  16
 SPI MISO  |  MISO    |     12 / ICSP-1 |      50     |   D12     |   ICSP-1         |  14
 SPI SCK   |  SCK     |     13 / ICSP-3 |      52     |   D13     |   ICSP-3         |  15
 

### Hardware

<!-- ![Desktop | Hardware Testing ](assets/arduino-rfid.jpg) -->
<p align="center">
  <img width="500" height="350" src="assets/arduino-rfid.jpg">
</p>