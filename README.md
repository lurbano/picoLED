# picoLED
Setup for using Raspberry Pi Picos for programming lessons.

# Setup your PicoLED strip:

Install Circuitpython:
* The version of circuitpython you use depends on if you're using a Raspberry Pi Pico or the PicoW. Download and copy the circuitpython .uf2 to the Pico from either:
    * PicoW: https://circuitpython.org/board/raspberry_pi_pico_w/
    * or Pico: https://circuitpython.org/board/raspberry_pi_pico/
* Note: (Copies of version 9 of these files are included in the _./circuitpython_ folder in this repository for convenience, but may not be the most up to date.)

Copy librarie/s:
* You will need the _neopixel.mpy_ library from the appropriate circuitpython bundle. The version for version 9 of circuitpython is included in the _./lib_ folder of this repo for convenience.
    * Copy _./lib/neopixel.mpy_ to the _lib/_ folder on the Pico. 


# Build a PicoLED strip (_./hardware/_):

Box:
* Corel Draw design files: _./hardware/picoStripBox.cdr_
