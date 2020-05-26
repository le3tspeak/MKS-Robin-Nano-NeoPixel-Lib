# Adafruit NeoPixel Library [![Build Status](https://travis-ci.org/adafruit/Adafruit_NeoPixel.svg?branch=master)](https://travis-ci.org/adafruit/Adafruit_NeoPixel)

Arduino library for controlling single-wire-based LED pixels and strip such as the [Adafruit 60 LED/meter Digital LED strip][strip], the [Adafruit FLORA RGB Smart Pixel][flora], the [Adafruit Breadboard-friendly RGB Smart Pixel][pixel], the [Adafruit NeoPixel Stick][stick], and the [Adafruit NeoPixel Shield][shield].

After downloading, rename folder to 'Adafruit_NeoPixel' and install in Arduino Libraries folder. Restart Arduino IDE, then open File->Sketchbook->Library->Adafruit_NeoPixel->strandtest sketch.

Compatibility notes: Port A is not supported on any AVR processors at this time

[flora]:  http://adafruit.com/products/1060
[strip]:  http://adafruit.com/products/1138
[pixel]:  http://adafruit.com/products/1312
[stick]:  http://adafruit.com/products/1426
[shield]: http://adafruit.com/products/1430

---

## Supported chipsets

We have included code for the following chips - *sometimes these break for exciting reasons that we can't control* in which case please open an issue!

 * AVR ATmega and ATtiny (any 8-bit) - 8 MHz, 12 MHz and 16 MHz
 * Teensy 3.x and LC
 * Arduino Due
 * Arduino 101
 * ATSAMD21 (Arduino Zero/M0 and other SAMD21 boards) @ 48 MHz
 * ATSAMD51 @ 120 MHz
 * Adafruit STM32 Feather @ 120 MHz
 * ESP8266 any speed
 * ESP32 any speed
 * Nordic nRF52 (Adafruit Feather nRF52), nRF51 (micro:bit)

Check forks for other architectures not listed here!

