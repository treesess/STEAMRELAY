FDM is indeed powerful and capable of printing many things. But it is just one CNC approach amongst the many. 

Before we make real of our dreams, we need to get real and know the boundaries. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/f61b81c8-b452-412a-8ef3-9e7573561e53)

In this case, a building model derived from Revit was wanted by our relayed friends as shown above. 

Slicers based on Slic3r were unable to load this STL file in, therefore i tried to open it by importing it to Fusion 360 as a mesh file. We can find that this STL model had many openings and event negative volume as analyzed by Fusion 360. Fusion 360 has the mesh repair function but this model cannot be successfully repaired. i think it is because there were too many surfaces in the original Revit model which had no thickness and therefore cannot be meshed as solid entities. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/4bee160e-6829-4160-b2b8-e9e6df15b861)

Here is the basic point: **Only solid entities with positive volume can be printed by FDM since FDM is Additive Manufacturing (AM).**

---

But Cura is different from Slic3r-based CAM software and able to load this STL file (also with model warnings). i sliced the model with necessary supports as below: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/4dad1f96-a306-46ac-bc56-d55b03e5e695)

i know this is not possible to be successfully printed for the listed reasons below: 

- The details of this model were too small to be sliced (less than 0.4 mm which is the commonly used dia. of printer nozzle);
- Even larger than 0.4 mm, they were too slim/thin to be printed;
- Even successfully printed, it was impossible to remove the supports in the post process because the supports went through the whole building's internal space.

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/667f7cb9-14a5-4004-85d5-3fe09de62403)

Though i still spent time printing it out. The reason was simple: action speaks louder than talking. A failed print can be quite direct and intuitive to the friends why this model is not printable. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/bf723f0b-09bc-4cb3-ab69-0c07e15ad1fc)

Here goes the printed one:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/c05a6716-89ba-4796-92d8-6ab91ab94dda)

And after 2 hours time removing the outer supports as possible and repaired the thin stair parts using a steel iron: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/c468fd46-455c-40c9-9764-3bf256eb7a51)

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/b61b53af-e148-4871-898e-685c5e1d31fb)

(Note that the top wasn't finished not because of printer error but running out of filament. Yes, my printer has no detection on filament supply.)

And these were the outer supports removed: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/08070583-f8c1-4fb4-849f-4362c100fde1)

The photo below shows the impossible-to-remove-supports which went through the whole internal of the shell. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/64cc10dd-8546-40ae-9674-afdf613a49c9)

---

By the way, i was still a bit surprised that some very thin parts were able to be printed. Well, most of the parts were failed. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/08c3cc22-a7ab-4fa7-bf80-30ca54a6c671)

At last, the same printer, can print out pretty detailed building miniature like the below one. This further explains why the original modelling in CAD software (no matter in Revit, Fusion 360, SW, CATIA, etc) is crucial for a successful print. FDM has its own special way of modelling which has some differences from CAD modelling for other purposes. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/e29dadf3-e581-4861-bc35-f3056e17f925)

(Frauenkirche Dresden miniature by vandragon_de at https://www.thingiverse.com/thing:3657111)



