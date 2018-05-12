# teensy_audio_player
A little mp3 player based on the example provided in ardiuno-teensy-codec by Frank Boesing

This example is specifically for the hardware combination below. 
* 1 x Teensy 3.6 board
* 1 x Teensy Guitar Audio shield
* 1 x ST7735 128 x 128 oled tft lcd 
  * 

* reads id3 v2.3 & v2.4
* displays song title and album on st7735 display.

Arduino-Teensy-Codec 
* https://github.com/FrankBoesing/Arduino-Teensy-Codec-lib
  * extended to read mp3 tag information (seems to work okay but not much testing)
  
Todo:
* read jpeg album cover images from tag in mp3 if available
* add compatibility
  * teensy audio board
  * ili9341 320x240 display
