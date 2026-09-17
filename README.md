# scribrawl  
online multiplayer game about scribbling and brawling  
  
**update: unfortunately put on hold for the time being because Unity's relay system doesn't provide a low latency multiplayer solution, which is kind of necessary for a multiplayer pvp game (especially a physics based one.)**    
  
the game uses the [$1 Detection algorithm](http://depts.washington.edu/acelab/proj/dollar/index.html) to identfity drawn (scribbled) patterns  
we're using [SteBeeGizmo](https://github.com/SteBeeGizmo/DollarUnity)'s implementation for this game  
the goal is to make a PvP online fighting game where the players make use of synergies between shapes to damage their opponent  
heres what we've got so far:  

https://github.com/user-attachments/assets/3f521e39-aca7-4ca3-ac6d-3b955b208a6d


---
Todo:  
- [ ] circles (which become bombs, useful for destroying walls or altering the velocity of arrows)
- [ ] brainstorm some other shapes and how they could synergise with other shapes  
- [ ] multiplayer demo with a basic gameplay loop  
