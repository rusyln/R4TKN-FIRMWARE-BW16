# RTL8720DN + 1.8" TFT + 3 Buttons - R4TKN BW16 Dual-Band Wi-Fi Deauther Firmware

![Project Banner](https://github.com/rusyln/R4TKN-FIRMWARE-BW16/blob/master/Screenshots/rtl8720dn-bw16_0.png)

A firmware implementation for the R4TKN BW16 module featuring RTL8720DN Wi-Fi chip, ST7735 1.8" TFT display, and 3-button interface for Wi-Fi deauthentication functionality.

## Hardware Components
- **BW16 Module** with RTL8720DN (Dual-Band Wi-Fi)
- **1.8" ST7735 TFT Display** (128x160 resolution)
- **3 Tactile Buttons** for user interface

## Features
- Dual-band 2.4GHz/5GHz Wi-Fi deauthentication
- TARGETED (PER CLIENT / PER STATION)
- RANDOM SSID
- BEACON + DEAUTH
- Interactive TFT display interface
- 3-button navigation control

## Acknowledgements
 - [tesa-klebeband](https://github.com/tesa-klebeband/RTL8720dn-Deauther)
 - [cypher-5G-deauther - dkyazzentwatwa](https://github.com/dkyazzentwatwa/cypher-5G-deauther/)

 - [lopaka - sbrin](https://github.com/sbrin/lopaka)

 - [ambd_sdk](https://github.com/ambiot/ambd_sdk) Image Tool

 - [readme.so](https://github.com/octokatherine/readme.so) 

## Pinout Configuration

### ST7735 TFT Display Connections
| TFT Pin | BW16 Pin | Description          |
|---------|----------|----------------------|
| VCC     | 3.3V     | Power (3.3V)         |
| GND     | GND      | Ground               |
| SCL     | PA14    | SPI Clock            |
| SDA     | PA12    | SPI Data             |
| RES     | PA26    | Reset                |
| DC      | PA25    | Data/Command         |
| CS      | PA27    | Chip Select          |
| BLK     | PA30     | Backlight (optional) |



### Button Connections
| Button  | BW16 Pin |
|---------|----------|
| SELECT    | GPIOX    | 
| UP    | PB1    | 
|  OK SELECT   | PB3    | 
| DOWN  | PB2      | 






## Installation


## Usage
