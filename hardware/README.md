# Hardware: Build a PicoLED strip (_./hardware/_):

Raspberry Pi Pico or PicoW:
* This setup has been tested with both boards. Other boards that can run circuitpython will probably work as well.

LED Strips:
* Use WS2812b led strips. The box design above is set up for 20 LEDs at 144 leds/meter, but any number of these leds and any density can be used.
* Connections from Pico -> LED strip: 
    * Ground -> Ground
    * GPIO (default GP27) -> Data
    * 5V -> 5V
 
 Design for laser-cut box (optional):
* SVG: _./hardware/pico-strip-box-single.svg_
* Original Corel Draw files: _./hardware/pico-strip-box-single.cdr_

PCB (Optional):
* This is a PCB design that facilitates mounting the Pico to the box and attaching the wires for the LED strip, but, it's not necessary.
    * (_./hardware/pico-LED-Touch-Analog-1x-v3.zip_).
* We use 2 mm diameter nylon bolts (8 mm long) and nuts to secure the Pico to the PCB, then solder the five marked contacts. 
* A 3-pin terminal block (0.1 inch/0.245 mm spacing) can then be soldered to the marked pins to make it easier to attach and adjust the wires going to the led strip. 
