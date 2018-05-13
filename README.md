# teensy audio player
sd-card music player using a teensy 3.6 micro-controller; based on the example provided in ardiuno-teensy-codec by Frank Boesing

* plays mp3, aac files using arduino-teensy-codec library - https://github.com/FrankBoesing/Arduino-Teensy-Codec-lib
* parses mp3 tags (id3v2.3 & id3v2.4)
* displays mp3 song title and album on 128x128 st7735 color display.

### Bill of materials
| | Component | Notes | approx. price |
|--|----|----|----|
| 1 | teensy 3.6 board | https://www.pjrc.com/store/teensy36.html | $29 |
| 1 | teensy guitar audio shield |  https://www.tindie.com/products/Blackaddr/arduino-teensy-guitar-audio-shield/ | $69 |
| 1 | ST7735 128 x 128 tft lcd (1.44") | | $5 |
| 2 | tactile switch | | $4 |
| 1 | rotary encoder | | $4 |
|  |  | | $111 |

### Todo:
* read and display jpeg album cover images from tag in mp3 if available
* add compatibility
  * teensy audio board
  * ili9341 320x240 display
