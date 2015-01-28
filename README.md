SmartThings SmartApp Energy Logger for Thingspeak
=======
<br>
SmartThings SmartApp to send energy meter data (kWh and watts) to
Thingspeak.  Testing with HEMv1 but will likely work with any
device that supports EnergyMeter capabilities with SmartThings.

Requirements
------------
- SmartThings HUB
- Device that supports the "EnergyMeter" capability (tested with HEMv1)
- [Thingspeak](http://www.thingspeak.com) account - Free

Installation
--------------------
1. Create a Thingspeak account and create a new channel.
2. Name your fields in the channel <b>the Display Name of your Eneryg Device
from [SmartThings](https://graph.api.smartthings.com/device/list), then append
.power to it.</b> For instance, if my device is called "Panel 1 (Generator)" my
Field 1 name would be "Panel 1 (Generator).power"
3. You'll need to go into your channel and create a Write API id.
5. Now, add a [SmartApp](https://graph.api.smartthings.com/ide/apps) and do
from Source Code and copy the RAW data from Github.
6. Save and publish the app. 
7. Go to your phone, +, add Smart App and add the API key and Channel #.
8. If you have multiple devices, you'll need to duplicate this again and name
it something different. 

Bugs/Contact Info
-----------------
Bug me on Twitter at [@brianwilson](http://twitter.com/brianwilson) or email me [here](http://cronological.com/comment.php?ref=bubba).


