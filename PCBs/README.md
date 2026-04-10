## A collection of PCBs for the PrintNC compatible with various controllers ##

I sell kits for the driver key PCBs that include IDC cable, connectors, jacks and pins (5 for $20 CAD, $10 for assembly, + shipping) and a kit with the toolhead and gantry PCBs that include screw terminals, ethernet jacks ($30 CAD, $10 for assembly, + shipping) though the PrintNC Discord https://discord.gg/rXNhba3C @logan2225

<img src=PCB-KIT.png>

### Fusion 360 and Step CAD files for 3d Printed Enclosures and Soldering Guides ###
Cad files are here: https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/CAD_Sensor_PCB_Cases

### Driver Key PCB ###
A convenient method to connect the Flexihal to the DM542T/DM556T or other drivers.

Version 1.3 here: https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/Driver_Key_1.3_PCB

Version 1.2 here: https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/Driver_Key_1.2_PCB

Assembly - Use the row of pins that matches your screw terminal spacing on your stepper drivers. 
Most current open loop drivers and closed loop drives without a brake input will use the 3.81mm spacing screw terminals.  
It will be marked on one end - 3.5 or 3.81 or 5.08.  Be careful to place the IDC connector on the same side as the outline
and with the notch lined up with the silkscreen - facing away from the pins for 1.2, and towards the pins for 1.3

### Endstop PCBs: ###
a collection of pcbs that provide various functions as follows: 

### Gantry Sensor PCB ### 
 
Updated with bypass jumpers to remove the inverting effect of the LED isolation circuit for the Flexihal

https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/Gantry_Sensor_PCB_2.1

### Toolhead Sensor PCB ###
for connecting X/Z axis and 3d probe at the toolhead to minimize individual cables in the cablechain.  

https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/Toolhead_Sensor_PCB_1.5

### Sensor Endstop Cabinet PCB ###
for connecting the cabinet end of the ethernet cable. Not needed for connection to GrblHal2k EST or FlexiHAL controllers.

https://github.com/LoganFraser/PrintNCMods/tree/main/PCBs/Enclosure_Sensor_PCB


