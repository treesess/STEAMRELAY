


# Definition of problem  

An incoming competition will be held soon for high school students. As a competition, fairness is to be done and to be seen. 

We ordered 750x750x5 mm plywood plates as a part of the materials to be provided to the participants. The game rule says that only the centre 500x500 mm area is the "construction area". So before we dispatch those wood plates to different groups of participants, we need to mark the 500x500 mm area as precisely as possible. 

Here is the catch: you can never count on the bought wood plates to be precisely 750x750 mm since they were cut by human beings. Therefore you can't rely on the 4 edges to be the reference lines. 

So the marking matter is transformed into: how do you mark up a 500x500 mm square in the centre of those approx. 750x750 mm boards as precise as possible. 

It's a simple geometry/math problem. My answer is to find the centre point of the plate first, then take it as the centre of the 500x500 mm square and draw the lines. 

The next question is, how to make sure the marked area is 500x500 mm square? Also note that **there are 20 pcs. of this wood plates to be done the marking!** Efficiency matters. 

My answer is to make a template first then use its outline to make the marking. Because we don't have CNC for this job. 

# Make of template

## PLAN A Template by FDM

The largest printer here is 350x350 mm, so it has to be broken into parts: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/15ec57ad-bfdf-4a23-aaa4-8f368ebe306b)

And leave a hole in the centre:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/676ffb28-168c-4476-9b92-801ed0baf9bb)

Though it can be made pretty thin (2 layers), this large area took time and kind of waste of plastic. So it was made hollow: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/fe815f4b-a51e-4fa8-9227-3171ee5c2fa0)

Only took 0.5 hours to finish the printing:  

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/318371c6-76e7-46a1-92ed-856c01588ad7)

This looked like a balanced way of saving materials and holding the precision. 

BUT...

FDM5 failed me... 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/e67fcb0f-f642-482b-bf7a-d2b3f1cdb4fa)

The accuracy of printing was far off... After i taped them up to the 500x500 mm outline, they looked so bad:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/92593f67-b7e5-41d6-b09e-60a581e28302)

FDM5 should have some calibration then. My guess is the belt fastening problem causing this inaccuracy. 

## PLAN B Template by wood plate

Doesn't matter. Find a recycled wood plate, draw the lines, cut it into 500x500 mm square: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/3d64fccd-6594-4452-9db2-301e4823d25f)

Doesn't cost much time anyway. i double-checked all edges and corners, it's pretty much good enough as a hand cut. 

# Marking

Then we proceed to the marking. 

Make the diagnostic cross first: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/860b3ee0-88fb-4118-868b-02bb30c4b375)

Place the template in the centre: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/c82040b4-b740-4bac-8742-c09e42be6182)

Note that actually no need to use the centre point, aligning with the cross lines works the same way. To be reminded, the 750 mm plate isn't precise, therefore it doesn't matter if the centre is the exact centre. The only thing that matters is the 500x500 mm square. 

Mark the outline and double check the marking: 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/7401b39b-8fb0-4b32-bb47-04cc92a7a4b7)

To make the boundary of the "construction area" clear, tape was adopted:

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/6ee8ef74-3090-43d1-86e5-222d9cc76b54)

It's pretty much done at this stage. For one piece. 

-----

After the marking, the edges of wood plates were polished to avoid sharp wood sting or cut any participant's hand. 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/c55f68c8-028c-45d9-a2bd-2af12741b181)

# Review of PLAN A

FDM5 made me nervous about the accuracy of my VORONs. Therefore i printed the same thing again by FDM7 (300 build): 

![image](https://github.com/treesess/STEAMRELAY/assets/20311124/2d85130a-7f51-40ae-a3e4-252bfb837c02)

Good news that FDM7 is performing well, it's 500x500 mm square as designed to be. 

What a relief. 
