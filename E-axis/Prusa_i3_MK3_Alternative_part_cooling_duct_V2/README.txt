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


https://www.thingiverse.com/thing:3063554
Prusa i3 MK3 Alternative part cooling duct V2 by robrps is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

An update to my previous Prusa MK3 part cooling fan duct (https://www.thingiverse.com/thing:2808683). A great improvement on doing actual cooling, but the nozzle viewing cutout has been dropped (sorry, no room).

The airflow in this model has a much smoother path, which starts up in the blower fan rather than just below it. It is split in to three channels and smoothly moves the air to a point just below the nozzle. A lot of part cooling ducts for the Prusa, especially the stock duct, have the airflow hit a large flat surface before forcing the air at a 90° angle. Prusa have brought out a newer duct which angles the blower at 45° which helps a great deal, but I have much better results with this design. Take a look at the last image which shows an overhang test (https://www.thingiverse.com/thing:699366) using the stock MK3, the R3 duct at 45°, and this design. Printed with Extrudr's NX PLA, which looks lovely, but is a awful at overhangs.

I've printed this in PETG, ABS and Onyx (Mark Forged FTW!). So far, even the PETG version has shown no sign of warping. However, I recommend printing in one material better that your usual printing material. i.e. Print in PETG if you mainly print PLA, ABS if you mainly print PETG and Polycarbonate if you print ABS etc.

*This works with the current Prusa R3 extruder parts. But you will have to mount this without the 45° bracket. See last couple of images. ~~Although the fan will only be held in by one screw, this duct goes up into the fan so it will be secure.~~ Updated version with an arm. I will be looking in to making this duct work with the 45° bracket.*
_______
Updates
=======
Version 31
------------
+ Has a stronger mounting screw block - wider and thicker.
+ 1.2mm adjustment on the mounting screw to allow for moving the fan lower if your nozzle is lower than normal(?)
+ Tweaked the bottom of the custom supports so they print a little easier.

Version 32
------------
+ Requested by @yojenh - added an arm to help hold the duct in place. This only works with the Prusa R3 extruder cover. You will need to raid your Prusa spares for an M3 thin square nut and at least an M3x18 screw.
+ Thickened up the outer side walls for easier printing, and to reduce the witness lines from the internal ducts on the outside walls.
+ Tweaked the PINDA cutout. I might get rid of it entirely in the next version.
+ Tided up the original screw block after it had been strengthen.


# Print Settings

Printer Brand: Prusa
Printer: i3 MK3
Rafts: No
Supports: No
Resolution: 0.2 or less
Infill: 25%

Notes: 
~~Line widths should be set in Slic3r as no more than 0.45mm, with external perimeters set to 0.4. Otherwise the cutout for the PINDA probe will not print as intended. Also, if you print the model with custom supports, then make sure your first layer is not wider than 0.45mm line width, otherwise the first layer of the 3 supports won't print.~~ Should be good to print at the standard 0.45 line widths, just turn off 'detect think walls' in Slic3r

I've added the g-code file that I used to print the part in Extrudr MF-PETG. You can try that, or you can import the settings in Slic3r (File -> Load Config) and change your filament setting to suite.