OrphanNets()
============

Report a list of named wire-nets that have only one entry in the tree.

This is good for finding "orphan" netw which have been added somewhere
on your schematic but don't have any corresponding net elsewhere on the
schematic. Maybe there's a typo (CLK vs CKL, etc). 

This is an action rather than a menu entry or shortcut. It doesn't take
any parameters. The results are printed in the message window `{wm}`.

Example:

```
OrphanNets
```
