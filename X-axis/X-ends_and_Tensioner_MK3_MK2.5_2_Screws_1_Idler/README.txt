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


https://www.thingiverse.com/thing:2846079
X-ends and Tensioner MK3 MK2.5 (2 Screws 1 Idler) by vekoj is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

This design brings back the two screws that were present on the MK2S X-Idler used to slightly adjust the distance, accommodate slightly different length of smooth rods, relieve some pressure from the Z lead screws... and for whatever reason you find them to be useful for you. The stock MK3 departed from this design, however I saw users asking for it to be available at least as an optional part.

IMPORTANT. These parts work only in combination with each other (as a pair). The change affects both X-ends. Meaning the "stock" X-MotorHolder wont work with this version of the idler and you cannot print just the new idler. 

In case you don't want the M3x10mm rod adjusting screws, a version without them is available here (https://www.thingiverse.com/thing:2957916). 

MK2.5 users should print the MK2.5 version of the X-MotorHolder instead of the MK3, rest of the parts are compatible.

Please note that the X axis tensioner uses GT2 16 smooth or toothed pulley instead of the stock GT2 20 pulley (my personal opinion backed with data points, is that either smooth or toothed pulleys will work just fine for the current application).

You can find the X-carriage for the modified pulley size and the revised extruder here (https://www.thingiverse.com/thing:2843264). If you dont want to print the extruder, a carriage compatible with the stock R3 extruder can be found here (https://www.thingiverse.com/thing:3078619)

STEP files are included for your modding pleasure and convenience. STL files were sliced and checked with Slic3r PE.

Any constructive feedback is welcomed.

EDIT (12/06/2018) Complete overhaul of the X ends design. Majority are cosmetic or quality of life changes, most notable are that the tensioner fits a lot better, no more thin walls on the X-Idler and some problematic fillets were removed.

EDIT (01/07/2018): Added a version for each X-end with clamps as per Arnaud Rousseau design (https://www.thingiverse.com/thing:2964026). This is the only change, and the previous version will remain as an option, although the clamps are quite convenient when it comes to ease of assembly.

EDIT (01/09/2018): Version cleanup. Only left the ones with clamps.

# Print Settings

Printer Brand: Prusa
Printer: i3 MK2S
Rafts: No
Supports: No
Resolution: 0.2 mm
Infill: 20-30%

Notes: 
Printed and tested with PETG, 3 perimeters 20% infill.

STL files are positioned in the correct printing orientation.

# Post-Printing

Use an 8mm drill bit to clear the smooth rod holes from any printing artifacts if you have any issues inserting the rods fully (make sure the printed parts are cooled down to ambient temperature). Gently clearing the excess material just by hand (avoid power tools) should suffice and will ensure the smooth rods can be easily inserted.

I recommend clearing the rest of the holes with a 3mm drill bit to clear printing artifacts, ensure proper screw alignment and easier insertion.


# Notes

STEP assemblies are included in the files section and can be used as a guide when assembling.

The design uses two M3x10mm screws (for the smooth rods), two M3 washers (~0.6mm) and two M3 self securing (nylock) nuts. IMPORTANT: Make sure to use the M3 washers. The screws should be flat at the end (thread) and same size (some cheap screws can be considerably off and crudely cut).

The shaft for the Idler pulley uses a cut M3x40mm screw (14-15mm length) to get the non threaded part as a DIY solution, which works ok. An alternative that was tested by Chris Warkocki (thanks!) is a dowel pin 7/64" Diameter, 5/8" Long. Still working on a suitable metric alternative that can be easily sourced.

# Fasteners BOM

* Stepper motor
  x3 Screw M3x18mm Socket Head Cap
  x3 Washer M3

* POM Nut
 x4 Screw M3x18 Socket Head Cap
 x4 Nut M3 Hex

* Smooth rods (X-Idler)
 x2 Screw M3x10mm Socket Head Cap
 x2 Washer M3 (0.6mm)
 x2 Nut M3 Nylock

* Tensioner
 x2 Screw M3x20mm Socket Head Cap
 x2 Nut M3 Nylock

* Clamps
x2 Screw M3x10mm Socket Head Cap
x2 Nut M3 Nylock

* Tensioner shaft
 a) DIY version
 x1 Screw M3x40 Semi threaded (cut to get the non threaded part)

 b) Dowel Pin 
  x1 7/64" Diameter, 5/8" Long (https://www.mcmaster.com/#98381a022/=1dkcucn)

  *Trying to source a metric version as well, note that flat 3mm ones won't work

# Credit where credit is due

I would like to note that the tensioner was originally designed by Jon Madden (thanks!), found here (https://www.thingiverse.com/thing:2770019). 

The (12/06/2018) update is heavily inspired by Grégoire Saunier from Bear mod, found here (https://github.com/gregsaun/bear_extruder_and_x_axis).

Thanks to Arnaud Rosseau, great addition to the design. (https://www.thingiverse.com/thing:2964026)