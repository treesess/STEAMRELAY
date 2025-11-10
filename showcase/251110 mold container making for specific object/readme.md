


to make an LSR mold container for a specific object can save you very lot of LSR (not only money saved, too much LSR used to mold an object may make it hard to demold. Also the mixing of LSR costs time, too much LSR requirement makes it difficult). 

if the object is a print with STL mesh file available, it could be easy to reduce the use of LSR by making a better fit container, mainly using Meshmixer. 

1) First open the STL in Meshmixer. Reduce the mesh if there are too many. 

<img width="795" height="767" alt="image" src="https://github.com/user-attachments/assets/400f8932-a1a2-4b55-91c4-61524f5a7065" />


2) Select All -> Edit -> Offset (Ctrl+D)

<img width="458" height="510" alt="image" src="https://github.com/user-attachments/assets/1feac1ce-8924-4e8e-9ba3-8fd246b4043c" />

To offset 5 to 10 mm is good i think. do it as you like. 

3) then inflate/deflate (hold Shift key to deflate) tool to make the surface smooth enough for vase mode printing

<img width="563" height="471" alt="image" src="https://github.com/user-attachments/assets/fa9a6c3c-2f1c-40af-b54b-3adb7c6d31c0" />

<img width="490" height="544" alt="image" src="https://github.com/user-attachments/assets/ebdfca42-a27c-4b38-bf14-7d88a88d3a04" />


4) Cut off the part below zero lever.

<img width="442" height="515" alt="image" src="https://github.com/user-attachments/assets/caf0f438-300f-4230-8b7f-a130c950f968" />

5) Export the modified STL to a new file and open it in your slicer (OrcaSlicer used in this case)

6) Flip it over and add a cylinder to make it more printable

<img width="635" height="596" alt="image" src="https://github.com/user-attachments/assets/7585f016-cfb4-404e-975e-3499b15c00bc" />

7) Slice it in vase mode. Remember to make the outer wall to 1.0 mm to ensure your print doesn't leak LSR (1.0 mm is the minimum line width i tried with PETG).

<img width="387" height="499" alt="image" src="https://github.com/user-attachments/assets/9fb7c9ba-3f02-407a-b571-ee5890065ad0" />

**Do double check the sliced line model to confirm there is no overhangs since overhangs may cause LSR leakage which you definitely don't want to see!**

8) Go print it out and cast LSR in

<img width="622" height="474" alt="image" src="https://github.com/user-attachments/assets/2ae5b173-87ca-42e6-a799-5afe400ee1ef" />

here i found it still a bit too much than i need so i add an additional spacer to lower the required liquid level. 

oh, you do know that all prints flow up in water or LSR, don't you? it's because most of the prints are hollow inside. so you need to get something heavy to hold it down in water. preferrable with a transparent PMMA plate so that you can be sure the object stay in the wanted position. 

<img width="649" height="465" alt="image" src="https://github.com/user-attachments/assets/20ff501b-973f-4fd9-8f05-6646ee27899b" />

finally you may need a book on top of them. i used Steven Pinker. 




------

link of model used in this case: https://makerworld.com/en/models/1039387-moai-in-hoodie-2
