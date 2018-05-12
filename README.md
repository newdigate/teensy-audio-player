# teensy_audio_player
sd-card music player using a teensy 3.6 micro-controller; based on the example provided in ardiuno-teensy-codec by Frank Boesing

* plays mp3, aac files using arduino-teensy-codec library - https://github.com/FrankBoesing/Arduino-Teensy-Codec-lib
* parses mp3 tags (id3v2.3 & id3v2.4)
* displays mp3 song title and album on 128x128 st7735 color display.

### This example is specific to the hardware combination below. 
* 1 x Teensy 3.6 board
* 1 x Teensy Guitar Audio shield
* 1 x ST7735 128 x 128 oled tft lcd 
   
### Todo:
* read jpeg album cover images from tag in mp3 if available
* add compatibility
  * teensy audio board
  * ili9341 320x240 display
