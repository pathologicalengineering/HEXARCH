# HEXARCH

![hexarch](hexarch.jpg)

## [REVISION I](revision)

4 oscilators, ~~with selectable mute~~ *(one mute and cut-up momentary button for all 4 oscilators)* and selectable resistive/diode mixing. 2 power fuckers, 1 voltage starver. volume control. on/off and pulse on. large capacitor provides current when switched off for... a bit, 2200uF seems to be a minute or so. *(maybe replace with a 220uF)*

2.1mm center negative 9V power, 6.5mm mono audio out.

~~first design uses a 74HC14, the original design uses an older 40106.~~ *(I got my hands on a 40106 so i didn't have to use a 7807, but redesigns will probably need that for 74HC14s cause thats what i can easily get)*

see the [circuit](circuit) folder for drawings of the design.

there's a demo on [twitter](https://twitter.com/pathofunction/status/1434861551324852231).

- [x] REVISION I UPDATE: CHANGE CERTAIN CAPACITORS TO ELECTROLYTIC
- [x] REVISION I UPDATE: SEE IF A 40106 SOUNDS DIFFERENT *(it doesn't really)*

## TODO

- [ ] ~~fix leakage on oscilator mutes or remove them~~\* *(honestly they're fine unless the gain is super high)*
- [x] audio kill switch\*\*
- [x] audio "cut up" momentary kill switch\*\*
- [ ] ~~variable oscilator frequencies?~~
- [ ] ~~change resistive/diode mixing to one switch for all 4 oscilators?~~

~~\* _mute is currently on the "audio out" for each oscilator, potentially move the mute to the feedback resistor line (before the potentiometer)_~~  
~~\*\* _would probably be easier to do this in a external housing (like a mini stomp box)_~~ *(it was fine, also i did both)*  

## CONTROLS

![controls](controls.jpg)

should be fairly self explanitory from the drawing, xandra figured it out before i labelled them all.

## REVISION II

revision ii should have everything in the TODO list, may need a bigger housing. see the [revision](revision) folder.
