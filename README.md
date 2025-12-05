# constant-current-drive

This is a simple circuit for sending constant current to a load, even if the load is varying over time.

## Single-directional drive

### Schematic
This picture below shows the current-sink configuration. In the **ltspice folder**, the more common current-source configuration is used for simulations.  

Note: replace IRF540 with IRFZ44N   
<img src="./eagle_pcb/schematic.png" width="600">

### PCB
![](https://github.com/auralius/constant-current-drive/blob/main/eagle_pcb/pcb.png)

## Two-directional drive

<img src="./bidirectional_drive/prototype.png" width="600">

<img src="./bidirectional_drive/schematic.png" width="700">
