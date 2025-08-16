# RTL8720DN + 1.8" TFT + 3 Buttons - R4TKN BW16 Dual-Band Wi-Fi Deauther Firmware

![Project Banner](https://github.com/rusyln/R4TKN-FIRMWARE-BW16/blob/master/Screenshots/Banner.png)

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

## ⭐ If You Like This Project...
Your support means a lot! If you find this project useful, please consider giving it a star on GitHub. It helps others discover the project and motivates further development.


## Installation
![Flasher](https://github.com/rusyln/R4TKN-FIRMWARE-BW16/blob/master/Screenshots/Flasher.png)
1. **Run as Administrator**  
   - Right-click the **R4TKN FLASHER** and select `Run as administrator`.

2. **Configure Serial Port**  
   - Go to the `COM Port` section.  
   - Under `COM`, select the correct port for your connected **BW16**.  
   - Leave the rest of the settings as default.

3. **Put BW16 in Flash Mode & Start Flashing**  
   - If your BW16 is **not already in flash mode**, do the following:  
     - Hold the **BOOT** button.  
     - While holding BOOT, **press and release RESET**.  
     - Release the BOOT button.  
     - The BW16 is now in **flash mode**.  
   - Now click the `Run FLASH` button to flash the firmware.

4. **TFT Display Configuration Note**  
   - The 1.8" ST7735 TFT display has multiple color configurations available.  
   - If you need a specific firmware binary for your display's color configuration, please let me know and I can provide the appropriate firmware version.

5. **Completion**  
   - Wait for the flashing process to complete (progress bar will show status).  
   - Once done, reset your BW16 to boot into the new firmware.

## 📬 Support / Collaboration

Got questions, ideas, or want to collaborate?  
Drop an email at **web.r4tkn@gmail.com**

[Support on Throne](https://throne.com/r4tkn)

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](http://coff.ee/rusn)
