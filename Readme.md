AnalogTouch 1.0.0
=================

This library lets you measure the capacitive touch of an Arduino pin.
Simply connect a wire (with a 10kresistor to not kill the pin because of ESD) to any analog pin of the Arduino.

If you move closer to the wire, the higher the values will get.
You can measure if a pin was touched or if you are just very close to the pin.
Make sure to calibrate the offset, see the example on how to do.

####Compatible with:
* Arduino IDE 1.0.x
* Arduino IDE 1.6.x
* Arduino Uno/Nano/Mini
* Arduino Leonardo/Micro (not tested yet!)

It should work with any AVR which has ADC pins.
If it doesnt work open an issue on Github.

Installation
============

Download the zip, extract and remove the "-master" of the folder.
Install the library [as described here](http://arduino.cc/en/pmwiki.php?n=Guide/Libraries).

Credits/Links
=============
The code was not my own work, I just improved it from these sources and provided a simpler API.

* http://playground.arduino.cc/Code/ADCTouch
* http://tuomasnylund.fi/drupal6/content/capacitive-touch-sensing-avr-and-single-adc-pin

Version History
===============
```
1.0.0 Release (12.06.2015)
* Initial Release
```

License and Copyright
=====================
If you use this library for any cool project let me know!

```
Copyright (c) 2015 NicoHood
See the readme for credit to other people.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
