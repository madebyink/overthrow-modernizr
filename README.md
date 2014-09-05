# overthrow-modernizr

Quick and dirty overflow:auto detection for Modernizr. 

This reports as `touch-overflowauto` or `no-touch-overflowauto` depending on whether the device is (a) touch based, and (b) has overflow:auto support that can be determined in a reliable manner.

Based upon the detection used in Overthrow (http://filamentgroup.github.com/Overthrow) by Scott Jehl, Filament Group, Inc. 

Beware! This approach does resort to UA sniffing when all else fails.
