# AERONET-Wet-Sensor
*A custom designed replacement for the consumable rain sensors you can build in your own lab for a fraction of the cost* 
## Files and guide to assemble the conductive rain sensor custom design for the NASA AERONET instruments.  
![Overview image](/Images/00.jpg)
### BOM 
1. [PCB (*MUST USE ENIG, HASL degrades far too fast*) (Check /Hardware directory for Eagle .brd files and gerbers) ](https://oshpark.com/shared_projects/1m1oY7qL)
2. [100K 0603 resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/RMCF0603JT100K/1758100) 
3. [3D printed support (Use PLA for cheap and easy but ASA or PETG for better UV resistance)](/Mechanical/SupportV3.stl)
4. [4Core telephone wire RJ11](https://www.digikey.com/en/products/detail/cnc-tech/530-26-04-SV-0100F/3442474) 
5. [RJ22 4P4C connector](https://www.digikey.com/en/products/detail/stewart-connector/940-SP-3044/388264) 
6. [3M 5200FC marine sealant/adhesive](https://www.3m.com/3M/en_US/p/dc/v000311743/)
----
### Build Instructions 
**Step 1** 
![](/Images/01.jpg)
Solder 100K resistor across pads.

**Step 2** 
![](/Images/02.jpg)
Print support (.2 layer height, 30% infill, standard temps and feed rates).

**Step 3** 
![](/Images/03.jpg)
Fit check PCB, should be slightly snug.

**Step 4** 
![](/Images/04.jpg)
Strip end of 4C cable, seperate out Yellow and Green, tin ends, thread through cable pass.

**Step 5** 
![](/Images/05.jpg)
Solder conductors to through holes on PCB, polarity doesn't matter then add adhesive under PCB, snug into pocket. 

**Step 6** 
![](/Images/07.jpg)
Fill the cable pass with sealing adhesive, add strain relief fillet and cover resistor and solder points. 

**Step 7** 
![](/Images/08.jpg)
Crimp 4P4C connector according to the image, looking down at tab yellow to the right, at terminals, yellow to the left. 

***Let cure and you're done!***
