# Pinecil_LED_Ring
LED ring attachment for the Pinecil V2 soldering iron (should work for V1 as well as it goes on the body)

The board is all done in KiCad and the zip file is all you need to produce a board. 
The LED is a 3mm LED with a third LED that is 0603
The SMD resistor is an 0603 with hand soldering footprint
Doing an update to add an 0805 LED on the bottom to help with shadowing. Will push updated files when prototypes get verified.

Calculate your resistor based on the LED you choose and the power source form the Pinecil you decide to use as well. Resistor should be around 75ohms with 3.2V forward voltage and 20 mA forward current on the LED.

Recommend a header for the power and ground or you can solder sold strand wire preferrably to the holes and to the iron. Wire should be small as 32 awg is currently what I am using but hole supports upto .015 inch wire which should be around 26 awg max.

Will update to SPI controlled lights when a known SPI connection is possible. This might not come and optional mod to add switch for on/off control for those that do not want to always be on will be looked at. I actually find it always being on nice.


The info on size of board according to Oshpark is: 2 layer board of 0.84 x 0.67 inches (21.2 x 17.1 mm)
