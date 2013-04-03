# ELSMo

EVE Linker SMF Mod - An EVE Online mod for the Simple Machines Forum that allows adding links to characters, corporations, solar systems and stations (Info Panels in IGB, EVE-Who / -Wiki links in OOGB)

IGB links are looked up by API request (no Key required) and stored within the SMF's database. OOGB links are just compiled using [EVE WHO](http://evewho.com) (Pilots and Corporations) or [Evelopedia].

Copyright (c) 2013 by Andreas Windt aka ta2edchimp.


## Prerequisites

- [Pheal by Peter Petermann](http://github.com/ppetermann/pheal)


## Installation

Download as ZIP and rename as "ELSMo_0_0_1.zip" (for Version 0.0.1), upload it using the SMF Package Manager and eventually "install modification".
Ensure to have [Pheal by Peter Petermann](http://github.com/ppetermann/pheal) installed and everything should work properly.


## Known Issues

### System and Station Links (OOGB)
Solar System and Station linking in an out-of-game Browser is not guaranteed to work. It just creates a link to the EVE Online Wiki to a possible document of that name; for example http://wiki.eveonline.com/en/wiki/Jita_(System) for "Jita" or http://wiki.eveonline.com/en/wiki/Jita_IV_-_Moon_4_-_Caldari_Navy_Assembly_Plant for the J4M4 Trade Hub, wiki document existence for other stations cannot be guaranteed.
IGB links are not affected and work as intended.

### Icons look like sh**
I'll eventually be working on these. Until then, please be patient or try your luck on them. I'd be glad to hear from you, if you come up with something nice :-)