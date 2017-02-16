# De Bruijn keyboard indicator light

Note: this is an old local project share to public, so files are not so tidy.  I'm planning to take a look later, but now these files are as is.

If you are using a wireless keyboard, then it is likely there is no keyboard status light on it. This project help you build a keyboard status light of your own, it is attached to the USB port of your computer and sync with the status (caps lock, num lock, scroll lock) of your keyboard, so you will never mess with these keys.   This keyboard light would change color and looks great in the night.

This status light also use a little bit math called ['De Bruijn sequence'](https://en.wikipedia.org/wiki/De_Bruijn_sequence).   It is awesome to see a piece of math working in this little thing.

HW build guide

To build this thing you need:
* A 3D printer.
* A [Teensy2.0 USB development board](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.O0TGUH&id=521711123240&_u=gbdbs20b2e).
* An [RGB LED module from DFRobot, model name 5050](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.O0TGUH&id=21133243824&_u=gbdbs26352).
* A [Stepper motor, model name 28YBJ-48](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.O0TGUH&id=15811333148&_u=gbdbs20c58)
* Some connect cables because you will need to connect the Teensy board with RGB LED module.
* A usb cable connect the Teensy2.0 board with your PC, choose the length fits you.

Build steps:
* print each parts under [directory](3D_print_parts), you need to print the following pieces:
    * a base
    * a lid
    * a mask
    * a rotary
