it was part of the new design method adopted in the latest [vcp](https://github.com/treesess/desktop3dpc) toolhead. 


<img width="446" height="443" alt="image" src="https://github.com/user-attachments/assets/41e5fbcc-7e8e-4178-8d21-dddc039aa503" />

it took me some time to realize that i should do much more work to decouple the vibration of printer frame with the toolhead. since the toolhead is the active source of vibration (i called it "hypocenter". don't laugh XD), there should be tones of vibration absorption around the toolhead - without compromising the positioning of nozzle, which is the basic for accurate printing. 

then i thought about TPU which was the only flexible material that i was good at making. but 95A wasn't enough obviously. i already applied TPU buffers on the previous toolhead. then the solid silicon rubber (SSR) came up. yes, Shore 10, which was almost 2 orders of magnitude softer. 

just do it. 

(tbh, i was intuitively so afraid of failure at that moment since i saw no FDM players did similar stuff yet. there were may uncertainties, such as, how should i control the tolerance of molding for SSR to make a structural part, or, how should i decide the transmission path of force, or, would it leak if i use the screws as part of the mold)

<img width="982" height="544" alt="image" src="https://github.com/user-attachments/assets/6c4f7451-ffa2-4b7a-8f3a-8f04d350f7f5" />

anyway i tried. 

<img width="538" height="539" alt="image" src="https://github.com/user-attachments/assets/e45a7d89-68ce-4972-a87d-4bd53de03eef" />

not that bad. the vibration of printer frame was actually reduced a lot, and the flowrate thus became much stable (if the vibration of frame is coupled with the toolhead, the actual vibration on the nozzle would be unstable, and the bed would be shaking as well, which would be a bad bad thing). 

However, i must point out that the tolerance control was bad. the SSR part should be designed to be a bit thinner than you want, then you can stretch it up a bit (kinda pre-tension). if you made the SSR part fatter like i did, it's hard to shrink it down to the size you want. this is my superficial experience for now. 

and there are def many things to be improved for this version of design, so, wait for it, i will keep test it when i m free... 
