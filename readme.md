# Hushbutton PCI Q-SYS Example Program

----
## Getting Started
Open the Scriptable Controls script by double clicking the Scriptable Controls block, then clicking the *S* button.  

Then change the *host* variable to the IP Address of your PCI board and *save* the script.  

----
## Description Of The Block Pins
Red 1-8  
* Trigger a channel to turn the red LED on.  
* Indicates the status of a channel's red LED.  

Green 1-8  
* Trigger a channel to turn the green LED on.  
* Indicates the status of a channel's green LED.  

Off 1-8  
* Trigger a channel to turn the LED's off.  
* Indicates if the status of a channel's LED's are off.  

Pressed  
* Indicates if channel's ring is pressed.  

Red All On  
* Trigger to turn all red LED's on.  

Green All On  
* Trigger to turn all green LED's on.  

All Off  
* Trigger to turn all LED's off.  

Poll All  
* Trigger to turn poll the state of all LED's.  

Managed  
* Trigger to turn managed mode for all channels on.  

Not Managed  
* Trigger to turn managed mode for all channels off.  

## Managed Mode  
Managed mode enables the PCI to manage the state of the LED's.  
When managed mode is on, pressing a ring will toggle that channel'S LED's between red and green.

When managed mode is off, pressing the ring will have no effect on the LED's.
For systems with a control system, managed mode is typically turned off.

When a ring is pressed, the control system can use that as a trigger to toggle the mute status of a mic input.
Feedback from the mic input can be used as a trigger to turn the red or green LED on.