
The old secondhand printer Ender 3 Pro (fdm2) has been in the corner for some time. It was upgraded with three MGN12 linear rails for three axes. After fdm3 was modified to be a laser engraver, this machine is now the most fit to be modified as a lightweight spindle CNC machine. 

Simply dismantle the original toolhead to expose the MGN12 sliding block, then mount the new x carriage to it, a simple spindle will be done. 

The drawing as below:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/1fad5101-28bf-4d5b-b07c-2954bc448c22)

And the actual installation is as below: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/82f22717-c29f-4a58-a4ed-c55b21f5eb08)

This design involved M3x30 SHCS, M3x35 SHCS and 3x4x5 heart inserts to minimize the use of plastic while maximizing the stiffness of the parts. 

The interesting thing about this design is that the belt mount style is rarely seen for linear rail on 2020 extrusion, by using M3 screws as the main parts holding the ends of the belt. Proper detailing was applied to ensure the M3 screws will be stably fixed on the x carriage. The belt is still almost hidden in the 2020 extrusion as before. I chose to flip the belt mount part on top of the 2020 extrusion for easy maintenance. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/9ef6d6a3-e5e2-48b0-a700-62c0a3d6adbe)

Engraving in progress: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/57a9feca-f0b5-4d0f-bb9a-30bf8306b245)

Result:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/1fdd38db-9e43-443d-aead-31269c2df651)

By the way, this machine is driven by Klipper firmware, using OrcaSlicer to generate the gcode file. When slicing, make sure the z hopping is on, then everything will be fine. 


Overall speaking it's good. However, the verticality is not enough since i was using the external hand drill as the toolhead, therefore a proper spindle should be installed to get better precision. 
