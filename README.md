# teensy audio player
breadboard and firmware project for teensy 3.6 devices to play mp3 and aac audio files from an sdcard on teensy guitar audio shield
* based on the example provided in ardiuno-teensy-codec by Frank Boesing
* plays mp3, aac files using arduino-teensy-codec library 
  * https://github.com/FrankBoesing/Arduino-Teensy-Codec-lib
* parses mp3 tags (id3v2.3 & id3v2.4)
* displays mp3 song title and album on 128x128 st7735 color display.
* use rotary encoder to change directory

## bill of materials
| | Component |  |  |
|--|----|----|----|
| 1 | teensy 3.6 board | https://www.pjrc.com/store/teensy36.html | $29 |
| 1 | teensy guitar audio shield |  https://www.tindie.com/products/Blackaddr/arduino-teensy-guitar-audio-shield/ | $69 |
| 1 | ST7735 128 x 128 tft lcd (1.44") | | $5 |
| 2 | tactile switch | | $4 |
| 1 | rotary encoder | | $4 |
|  | **total** | | **$111** |

## todo:
* read and display jpeg album cover images from tag in mp3 if available
* add compatibility
  * teensy audio board
  * ili9341 320x240 display
