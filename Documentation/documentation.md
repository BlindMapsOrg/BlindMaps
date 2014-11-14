# Documentation

## Handle casing
For the cane handle there are momentarily two designs available. One general casing and one that has a left and right vibration pad. The casing is pretty straightforward and can be closed using two m4, 15mm bolts. The tread is not integrated in the design and has to be tapped manually (the holes are in the design). The design has been tested on a Makerbot 2, however the tolerances might need to be adjusted for various printers and fitting could need some manual work. 

There is also a separate button, it can be placed on a widely available tactile switch (example: http://uk.farnell.com/te-connectivity-alcoswitch/fsm8jh/switch-spst-0-05a-24vdc-pcb/dp/1555985?Ntt=1555985). There is space in the casing for snapping in the button.

For the casing with the vibration pads the pads can be printed separate (preferably from a rubber material).


## Beacon casing
For the first beacon prototype a oversized beacon casing is made to easily fit components for prototyping. For the prototype a philips speaker (http://www.amazon.com/Philips-SBA3011-37-SoundShooter-Portable/dp/B008OQLM18) is used together with a Arduino with mp3 shield (linked to a RFduino. This all was battery powered. The back of the casing fits can be closed with m4 15mm bolts (of which the tread has to be tapped manually). Please note that the wall-thickness of the casing was kept thin to reduce printing costs. However makes it fragile too. In later version the wall-thickness will be increased. 
The beacon has a separate button which can be placed on a 12mm tactile switch (http://uk.farnell.com/te-connectivity/fsm101/switch-spst-0-05a-24vdc-smd/dp/1813631)

Additionally there is a beacon holder to easily mount the beacon to a wall. 

## Electronics

For the prototypes we used some basic prototype tools to test the concept (Arduino + RFduino). Although all the tools use technologies, like Bluetooth LE, that would be used in an eventual product. They are not optimized for our application. This means the code is not as efficient as possible nor power consumption and bluetooth range. We used it as a proof of concept and user testing setting. 

For the canes we used an RFduino bluetooth module together with some miniature vibration motors. This all powered by two AAA-batteries. For the beacons we used a RFduino linked to a Arduino with a MP3-shield. 

Links to major electronic components:
- www.rfduino.com 
- www.arduino.cc
- www.sparkfun.com/products/10628

# iOS Demo App

We used an iOS Demo App to send vibrations for left/right to one handle. This demo app is based on the RFduiono example apps:
- https://github.com/RFduino/RFduino/tree/master/iPhone%20Apps