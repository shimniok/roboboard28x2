# roboboard28x2
Robot controller board for PICAXE-28X2.

Built for 5th grade robotics club that I'm leading. It's a low cost "baseboard" for the
PICAXE with built-in USB connector and FTDI chip.

By using an onboard FTDI we save versus the retail cost of FTDI breakout boards which are
also easy to lose.

Breaks out each pin with a corresponding VCC and GND for convenient hookup of sensors and
controllers.

The board has a footprint for a Pololu S10V4F5 step-up/step-down switching regulator
daughterboard (or anything with an equivalent pinout) to provide a steady 5V from 4AA 
batteries for sake of predictability.

Also expects to use a separate motor control board (using the Pololu DRV8835 breakout in
this case but any low voltage motor controller will work).
