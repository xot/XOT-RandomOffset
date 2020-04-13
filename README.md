# XOT-RandomOffset

Max for Live MIDI effect. Add or subtract a random offset to incoming MIDI notes.

(c) Jaap-Henk Hoepman (info@xot.nl)

Released under the [MIT](https://opensource.org/licenses/MIT) license. 

## Description

A random offset is added to each incoming MIDI note. This offset equals the value set by the 'Offset' dial multiplied by a random factor between -2 and 2. 
The probability that a particular factor is selected equals the height of the corresponding bar in the weight table, divided by the sum of all heights of all bars in the table. The height of the bar thus determines the weight given to its corresponding factor

For example, if only one factor has a non-zero weight, this factor is chosen with probability 1. If two bars have equal height, and all other weights are zero, each corresponding factor is chosen with probability 0.5.


