# picoLED
Setup for using Raspberry Pi Picos for programming lessons.

# Software: Setup your PicoLED strip:

Install Circuitpython:
* The version of circuitpython you use depends on if you're using a Raspberry Pi Pico or the PicoW. Download and copy the circuitpython .uf2 to the Pico from either:
    * PicoW: https://circuitpython.org/board/raspberry_pi_pico_w/
    * or Pico: https://circuitpython.org/board/raspberry_pi_pico/
* Note: (Copies of version 9 of these files are included in the _./circuitpython/_ folder in this repository for convenience, but may not be the most up to date.)

Copy librarie/s:
* You will need the _neopixel.mpy_ library from the appropriate circuitpython bundle. The version for version 9 of circuitpython is included in the _./lib_ folder of this repo for convenience.
    * Copy _./lib/neopixel.mpy_ to the _lib/_ folder on the Pico. 

Run:
* On the Pico, run the _code.py_ file. The program _Thonny_ facilitates this:
    * [Thonny](https://thonny.org/): 
        * You will most likely need to set the interpreter on Thonny. This can be done either through Tools->Options->Interpreter menus, or clicking on the interpreter listed on the bottom right corner of the Thonny window.

# Hardware: Build a PicoLED strip (_./hardware/_):

Design for laser-cut box:
* SVG: _./hardware/pico-strip-box-single.svg_
* Original Corel Draw files: _./hardware/pico-strip-box-single.cdr_

LED Strips:
* Use WS2812b led strips. The box design above is set up for 20 LEDs at 144 leds/meter, but any number of these leds and any density can be used.
* Connections from Pico -> LED strip: 
    * Ground -> Ground
    * GPIO (default GP27) -> Data
    * 5V -> 5V
 