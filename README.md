Script created to work with the citizenfx framework.

This script limit entities spawning amount per server. Reducing lagging significantly. 
To modify ped density, change the ```cfg.density``` value for peds or vehicles in ```cfg.config```. The "0" value meaning it won't spawn at all.

You can also set a spawning restriction for specific entities.  
There is some pre-configured peds, if you want to add more, write the ped model name in ```cfg/npcs.lua```


#### STEP 1
 Clone this repository in your ```[script]``` folder.
#### STEP 2
 Add ```start npc_control``` in your server.cfg file. Doesn't matter the placement order
#### STEP 3
 Write ```server restart``` in your local/vps server terminal.


