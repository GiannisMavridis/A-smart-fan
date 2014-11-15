A-temperature-controlled-fan
============================

We build a "smart" fan that turns on only when the temperature is more than 29 *C.
When the temperature is lower than 29*C ,the fan turns off automatically.

The materials we used are the following:
-LM35 temperature sensor so as to measure the room's temperature
-we hacked an old PC's motherboard and we took the CPU's fan.The fan is driven
by a 12Vdc motor.
-a 12Vdc adapter in order to power the motor
-a relay that is similar to this one
http://www.amazon.com/SRD-05VDC-SL-C-Channel-Power-Module-Shield/dp/B008MU1KQ8

The idea is the following:(check the schematic)
We power the motor through the relay.We measure the temperature and when we measure a temperature >29 *C
we trigger the relay and we turn on the fan.



