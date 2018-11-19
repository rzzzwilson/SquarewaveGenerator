SquareGen
=========

This project is a repackaging of the fast risetime Square Wave generator
that I built from the 
`video by W2AEW on YouTube <https://www.youtube.com/watch?v=9cP6w2odGUc>`_.
I originally put this circuit into an enclosure using the "dead bug" style
and it worked pretty well.  Here's the built circuit:

.. image:: IMG_5211.JPG

And here's the circuit running on the 'scope:

.. image:: DS1Z_QuickPrint3.png

Not bad for a cheap little circuit.  It draws less than 3mA at 5volts.

I have been building circuits on PCB lately using the PCB shops in China with
through-hole components, but now I want to get into surface-mounted components
so I'm using this circuit as a guinea-pig.  Using KiCAD here's the schematic:

.. image:: schematic.png

and the PCB itself:

.. image:: pcb.png

I'll put the PCB into the same 25x25x50mm enclosure as the first circuit, so the
PCB measures about 44x23mm.  I got the enclosures 
`from here <https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20180825211723&SearchText=50x25x25mm+Extruded+Aluminum>`_.


Status
======

The Gerber files haven't been submitted to the PCB fab shop yet, as I'm waiting
for my first set of orders to come back.  That order was for breakout boards for
SMD versions of things like AtMega328P and Si5351 chips.  Once I've built those
breakout boards and I'm happy with the layout of this board I'll send off the
order.
