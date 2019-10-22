

Fuzzy grips setup instructions, for use in Cura. The attached Cura profile is for an mostly stock ender 3 using PETG.
Im sure its by no means perfect but worked for me, if you improve on it please let me know so I can improve. 

*MODIFY THE FRAME AND DO YUR CRAZY DESIGN I WANNA SEE INNOVATION!*
If you come up with something neat send me a message and show me!

OVERVIEW:
Adding extra bodies flush with the the surface allows to select them to have
a fuzy texture and this texture to be applied to the main body.

In Cura import all the files as seperate bodies.
In Preferences->Configure Cura->General-> uncheck "Automatically drop models to build plate"
Hit CTRL+A and right click the model -> select "Merge Models"
I have no F**ing clue how it knows where to go it has just always gone to the right place...
Reposition the model in the orientation you want (it usually shifts after the last step)
Click the Rotate button and select lay flat.
Hit CTRL+A and right click the model -> select "Ungroup Models"
Ensure Fuzzy skin is turned on in the experimental preferences and Thickness .3, Density 6. Point distance should automatically go to .1667
Now click on ONLY the main model and click the Per Model Settings->Select settings->Fuzzy Skin-> uncheck Fuzzy skin.
This should apply fuzzy skin to every body except the model.
 
Notes:
Adding fuzzy skin feature adds about .02 thickness to the part that is fuzzy.
The rest of the added bodies are only exposed where the fuzzy skin is desired.
If you want some dumb design in the grip just extrude it through the respective pannel.
Overlaying the fuzzy panels with the OEM glock grip texture, might yeild a neat hybrid texture. 
Overlaying the fuzzy panels with the other frame should work too as they are the same grip?


The regular G19 has a cutout for the manendez mags, the rest dont. sorry it was an afterthought and was a bitch to do.
If you really want to use manendez mags, an easy fix is to remove 2mm from the bottom. 
