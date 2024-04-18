# MXM Immobilizer

It's an MXM to PCIe adapter! All the ones on aliexpress and stuff are overpriced and incomplete smh 😔  
Also this one's open source lol.

It's not quite done yet, a lot of stuff is currently suboptimal, but it might actually work in its current state. No guarantees though.

<img src='front3d.png' width=75%/>
<img src='back3d.png' width=75%/>

## Insert more info here at some point
(there is a lot to say about the headers and the power inputs and stuff)

## Todo:
* Re-route PCIe and DP so the 3.3V rail isn't pushed down so far
* Fix the AUX diffpair abuse
* Make all the headers be not totally awful
* Add jumper storage header
* Add default position 0R resistors for headers
* Diffpair wiggles
* DP diffpair between-lane length matching
* Remove ground plane around PCIe traces
* Change mxm mount screw holes to be plated so you can solder on screw posts

<img src='pcb.png' width=75%/>