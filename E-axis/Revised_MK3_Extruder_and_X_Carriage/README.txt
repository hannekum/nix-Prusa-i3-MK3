                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


https://www.thingiverse.com/thing:2843264
Revised MK3 Extruder and X Carriage by vekoj is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

This design aims at fine tuning the stock Prusa MK3 extruder and fixing some issues that I think are present with the stock design.

Although you can loosely use the Prusa assembly manual, please refer to the STEP Assembly with all the fasteners included to help out during assembly, some fasteners had their length changed. Any help with writing the assembly guide will be greatly appreciated. 

Files include the X carriage, considering some of the changes on the extruder affect the carriage as well, however I like to note that the belt positioning is adjusted for GT2 16  idler pulley (stock is 20). 

You can find the corresponding X ends with integrated belt tensioner here (MK2S style for the idler https://www.thingiverse.com/thing:2846079), or here (MK3 style for the idler https://www.thingiverse.com/thing:2957916).

If you insist on using the stock X ends, you should use this X-carriage combo instead (https://www.thingiverse.com/thing:3080153) with adjusted belt holder for GT2 20 idler pulley. 


The MK2.5 carriage should be compatible with the Zaribo frame, however I do not have the setup currently to test it on a stock frame. I am not sure about some clearances in the back, so please have that in mind. For now it remains untested.

STEP files are included for your modding pleasure and convenience. STL files were sliced and checked with Slic3r PE. Any constructive feedback is welcomed.

EDIT (01/09/2018): New version of the extruder. Please note changes affect all the parts, and probably none of the previous version will be directly compatible, besides maybe the X-carriage cable holder.

This version incorporates the R3 changes of the stock MK3 extruder.
Other major changes include: 
Closer stepper motor to the X rods, slightly reducing weight and moving the center of mass, also enabling the bondtech gears to fully rest on the stepper motor shaft. 

The stepper motor now should be a lot more constrained in order for the bondtech gear to properly align.

Significantly reduced the gap between the filament path and the bondtech gears.

The tensioning system for the idler received some polishing to ensure even tension. The compression spring rests on a metal washer, the screw has a lot more room to move when the idler opens, and the idler has the option of using a nylock nut.

The PINDA can be removed without the need of fully disassembling the extruder, also added a small channel to secure the cables for the angled part cooling fan.

The extruder now uses Prusa's R3 angled fan shroud with support that secures it on two screws (clears the cables for LDO motors, Moon motors owners have to rotate to clear the support, to be considered in the future)

EDIT (03/09/2018) Edited the X-carriage back to sort clearances with stock frame. Files affected are X-Carriage Back and X-Carriage Cable Holder.

# Print Settings

Printer Brand: Prusa
Printer: i3 MK2S
Rafts: No
Supports: No
Resolution: 0.2 mm
Infill: 20%

Notes: 
PETG - 2 perimeters, 20% infill, 5 top 5 bottom layers.

# Post-Printing

The filament path should print with less artifacts now, however make sure its free from any obstructions (in particular the path from the sensor cover to the bondtech gears). Insert a piece of filament and ensure it glides smoothly, use a 2mm drill bit in case you need to clean it up a bit.

![Alt text](https://cdn.thingiverse.com/assets/f5/1d/98/3b/f8/7.JPG)
The idler hole for the screw that it pivots on, is now intentionally a bit tight so you can clean up the excess material and get a clean circle. I used a M3 screw to thread the hole, then passed it with a 3mm drill bit by hand. Clean up until the idler rotates freely around the screw, don't over do it.

![Alt text](https://cdn.thingiverse.com/assets/91/aa/36/b2/1f/6.JPG)
I very lightly sanded (or scrape them with a blade) all the surfaces that come in contact and rotate, in specific the surfaces the plastic washers rest on, so you clean up minor printing artifacts if present and ensure smooth rotation.

![Alt text](https://cdn.thingiverse.com/assets/5a/8e/55/2a/7c/8.JPG)
Use a 3mm drill bit here in case the dowel pin is too hard to insert

# Notes

* The design uses the thinner version of the M3 square nuts (~1.8mm) which are the same as the stock ones. I am mentioning this info because there are thicker versions out there that most probably will cause issues with this design of the parts. If you insist on using the thicker ones, feel free to edit the STEP files provided to accommodate them.


* Because the M3x35mm screw for the Extruder Idler (that serves as its shaft) now secures on the X-carriage, please note that while assembling it you should skip that screw until the X-carriage is positioned. As in skip that screw until later in the assembly as per the Prusa online manual.

* Please note that the M3 square nut that secures the PINDA is now blocked by the X-carriage (the opening), please make sure to insert the square nut before any further assembly.

* The X-carriage belts holders are bit more fine tuned to hold the belts better, however in case they slip you can use the bend at the end to add more strength, see pictures.

* The tensioning screw for the idler uses a metal M3 washer for the compression spring to rest on

* The idler uses plastic washers (same specs as the ones for the idler shaft) to separate the bondtech gear and the printed part.

* IMPORTANT Make sure after you have fully inserted the dowel pin in the extruder idler, that the plastic part isnt pinching the gear (happens because of the pressure fit dowel pin). Just slightly push the tabs that hold the gear apart, to remove the pinch. The gear should rotate freely.

# Changes

* Removed the filament sensor "inspection/alignment" hole

  The hole is directly over the reflective surface of the sensor, and the opening is blocked with a silly small part that in my case at least, wouldn't sit tight and eventually fell off during printing. For inspection of the sensor I suggest opening the top cap (filament sensor cover) and doing any checkup/maintenance/alignment from there. Dust will eventually build up there, and cleaning it should be considered as part of regular maintenance in any case (inspection hole or not). My opinion is that this hole can cause more harm than good.

* Minor geometry changes to make the filament sensor enclosure a bit more light proof

* Added a cutout for a M3 square nut for the fan shroud mounting hole on the Extruder Cover, seeing how frequent assembly/disassembly of the fan shroud might damage it, and make the hole unreliable.

* The M3 screw for the Extruder Idler (that serves as its shaft) is now 35mm, and it screws on the x carriage to prevent the thin wall on the Extruder Body from bending when the screw is tightened. Please have this in mind when assembling.

* Adjusted the screw holes on the Extruder Sensor Cover, because on stock some screws were too close to each other and produced some thin walls, for no obvious reason for their position.

*  Ensured the bondtechs gears are aligned and mesh properly

*  Removed one spring screw, and adjusted the other to exert even pressure between the filament and the gearing.
 
* Added a M3x40mm screw to secure the corner where the PINDA holder is. The X-carriage has a M3 square nut to secure this screw, securing all three parts together (Extruder cover, body and X-Carriage). Adjusted geometries accordingly on each part.
  
  The parts have screws to secure every corner except the one near the PINDA holder, I have noticed on my prints, as well as others reporting that when you fully tighten all the screws that corner where the Extruder-Cover and Extruder-Body meet separates, that might cause the PINDA to move to a side and tilt.

* The PINDA holder itself has some minor geometry change because some users had it break when securing it. The gap between the parts is lowered so the screw cant bend the part as much and break it. And the overall geometry was adjusted to provide additional strength.


# Credit where credit is due

In no particular order I would like to thank the following people for helping me brainstorm.

Olof Ogland - https://www.thingiverse.com/Olorf/about
Chris Warkocki - https://www.thingiverse.com/codiac2600/about
Christopher Tilley - https://www.thingiverse.com/ctilley79/about
Fredrik Hjelm - https://www.thingiverse.com/Tibbeh/about
Wolfgang Schadow - https://www.thingiverse.com/wschadow/about
Ocie Ward - https://www.thingiverse.com/ocieward/about
Matt Klassen - https://www.thingiverse.com/MattyKay/about

A huge disclaimer however, although the people I mentioned helped me brainstorm and test few ideas, I would like to say I take full responsibility for the design of the model, the choices for the modifications and the possible issues that might show up. Thank you all.