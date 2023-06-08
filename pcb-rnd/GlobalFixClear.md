GlobalFixClear(size)
--------------------

Iterate over all the subcircuits in your design and set the clearance
of all pads and pins to a user provided value.

When you get footprints from other sources it is common for them to have
different clearance values for the pads and pins. This will make all the
clearances the same value throughout your entire design.

This is an action, not a shortcut or menu entry, and it takes one 
parameter: the size of the clearance to apply.

Example:

```
GlobalFixClear(0.3mm)
```
