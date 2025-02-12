# MP3-TFT-Fether (# featherPlayer-esp32)
This project creates a MP3 Player with the TFT Fether and includes a screen that has display options. This project is made up of various other libraries and code examples have been integrated into one large project. 

This PlatformIO project is intended for a [Adafruit ESP32-S2 Reverse TFT Feather](https://www.adafruit.com/product/5691)
combined with a
[Adafruit Music Maker FeatherWing](https://www.adafruit.com/product/3357).

<img src="https://cdn-shop.adafruit.com/970x728/5691-04.jpg" alt="Adafruit ESP32-S3 Reverse TFT Feather" width="350"> <img src="https://cdn-shop.adafruit.com/970x728/3357-03.jpg" alt="Adafruit Music Maker FeatherWing" width="350">

## What is it?

An esp32 music player for local music files(MP3).<br>Sound output comes from a VS1053 mp3/aac/ogg/wav decoder board.
- Plays local files from a mounted filesystem.

## Interface

This player has a default screen save that will alternate while music is not being played.  The Adafruit ESP32-S2 Reverse TFt Fether has three button as input options:
- D0: Plays the song in queue , Screen will show the name of the song playing 
- D1: Pauses/Resume the song Playing, Screen will show Media is Paused till Resumed. 
- D2: Next Song in queue is played, Screen will show the name of the song playing. 

## What you need

[Ardunio IDE]([https://code.visualstudio.com/](https://www.arduino.cc/en/software)).

# Libraries:
- Adafruit_GFX.h
- Adafruit_ST7789.h
- Adafruit_VS1053.h
- SPI.h
- SD.h


# Clone this project to your pc

- Open a terminal in the PIO project folder.
- Clone the project with the following command:

```
git clone https://github.com/Zack1017/MP3-TFT-Fether.git
```
