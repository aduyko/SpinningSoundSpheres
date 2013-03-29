SpinningSoundSpheres
====================
Introduction:
This html program, which runs in browsers which can use the HTML5 canvas and audio elements,
can be used to create interesting sound-scapes of orbs. They both look and sound interesting
and can be made however the user desires.


Controls:
Left Click to add and select a "node". The horizontal position of the node determines
the note that will be played by thenode, the vertical position determines the volume;
higher is louder.

If nodes are selected, clicking anywhere on the background not occupied by a node will
deselect all selected nodes. Clicking on a node will add it to the list of selected nodes.

When a node/nodes are selected, press Z to add a "spinner". Spinners play the sound 
that is determined by their parent node whenever they cross the x axis to the right of the
parent node. 

Moving your mouse around will also move around all un-ancored spinners.

Pressing X deletes the last added spinner of all selcted nodes.
Pressing C will lock down all unlocked spinners for selected nodes. Unselecting 
the nodes will also lock down all unlocked spinners.
Pressing F will clear and reset the canvas.

WARNING:
Be careful about making too many spinners, because Audio elements are not well supported
in HTML5 yet, so your browser may crash.
