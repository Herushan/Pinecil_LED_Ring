# Pinecil_LED_Ring
Finished board with ideal LED combination.
![Finished on Pinecil V2](https://user-images.githubusercontent.com/11600701/229526712-a325feed-b0db-4e21-88da-b15dfb0e2050.jpg)

White boards are shown are with smaller holes and new design (November 2023) has larger holes with better spacing and have the two LED methods of assembly shown (can use SMD on the through hole pads as shown). The yellow board is 1st draft of 3 LED design that missed some PCB info.
![White boards are final one with 3 SMD LEDs and one with ideal kitting 2 through hole and 1 SMD LED](https://user-images.githubusercontent.com/11600701/229527973-ac94ad17-4ff0-4593-b01a-694673d7ccf6.jpg) New updated wire connection holes that are oval and square (November 2023). ![1000003776](https://github.com/Herushan/Pinecil_LED_Ring/assets/11600701/a4525656-6f33-4f23-bb19-37d8116f10a0)


LED ring attachment for the Pinecil V2 soldering iron (should work for V1 as well as it goes on the body)
Recommend looking at the pictures and details to the inital two LED writeup (Pinecil_LED_Ring_writeup.pdf) that is here in the GitHub. The square holes are negative and round is positive. Arrow points to negative or left looking at board with LED at bottom.
![LED position](https://user-images.githubusercontent.com/11600701/229527044-bc8cfd04-92c3-4f6d-9502-6295e74ce870.jpg)

The board is all done in KiCad and the zip file is all you need to produce a board. 
The LED is a 3mm LED with a third LED that is 0805
The SMD resistor is an 0805 with hand soldering footprint
Updated with an 0805 LED on the bottom to help with shadowing.

Kit with all the parts.
![Kit](https://user-images.githubusercontent.com/11600701/229527068-05a625a5-869c-4610-959b-0d75b36e5cd8.jpg)

Assembly of kit video (Video of soldering to Pinecil V2 coming later)
https://youtu.be/LMbjwjDbSew

Calculate your resistor based on the LED you choose and the power source form the Pinecil you decide to use as well. Resistor should be around 75ohms with 3.2V forward voltage and 20 mA forward current on the LED.

Recommend soldering (being careful small gap and size to board holes) the power and ground with sold strand wire preferrably to the holes and to the iron. Wire should be small as 30/32 awg is currently what I am using but hole supports upto .015 inch wire which should be around 26 awg max.

***May not happen*** Will update to SPI controlled lights when a known SPI connection is possible. This might not come and optional mod to add switch for on/off control for those that do not want to always be on will be looked at. I actually find it always being on nice.

Recommend reading the wiki (https://wiki.pine64.org/wiki/Pinecil) for guides to opening the Pinecil (https://www.youtube.com/watch?v=aK01V5DrrVk).

The info on size of board according to Oshpark is: 2 layer board of 0.84 x 0.67 inches (21.2 x 17.1 mm)
Any 3mm through hole LED will work.
SMD LED that works for the pad: https://www.digikey.com/en/products/detail/harvatek-corporation/B1701TX-20P000614U1930/16671745
Resistor that works: https://www.digikey.com/en/products/detail/rohm-semiconductor/ESR10EZPF75R0/1983560

Contact me on discord (@ahall(RuShan)) on the Pine64 channel for any questions through DM is fine.
If you would like to use my referral link to elecrow for boards: https://www.elecrow.com/referral-program/MTM5NjdqMnQ/

I also shared the project on Elecrow here: https://www.elecrow.com/sharepj/pinecil-led-ring-add-on-358.html
