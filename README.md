# UEBomberMan

## BomberMan Rapid prototype for 2-Local Players, in Unreal Engine within in 15 hours

> Engine version 4.18.2 (4.19 is out, but I will differ the update after this)

 This is going to be a quick 15 hour hacky prototype implementation in UE 4.18.2. I will be doing this is 1-2 sessions. This is supposed to be implemented with a mix of C++ and Blue-print scripting. But I am not yet certain on which parts to seperate out that way, as there  may not be need for a Centrailzed 'Game Manage' or Game-mode for the simple gameplay.  I prefer to implement this in Entity-Component system, and not much of Parent, Child classes as the logic is quite simple.  I personally, prefer to *Write Code* than connect nodes and graphs, as most programmers do.  
 
My goal here is to get a Polished feel to the game rather than a Programmersque Box-Sphere-Plane POC (Besides, I'm reluctant to install Windows 8 SDK, Unreal VS Extension, etc on my overloaded Laptop). Pure blue-print approach will probably save time,in the 15 hours, I rather use to make it polished, create sounds and P-FX instead

>2:04 am (Almost 6 hours into the project).  I am not happy with the progress.  
>Have to blame on getting 2-pawns to move with a keyboard hack.  Took up most of 
>my planned time.

## Tasks remaining
1 - Bomb blueprint, Spawn by player, timed destroy and explosion
2 - Bomb - Ray-trace and destroy Breakables (Probably Tags needed)
3 - Track bombs destroyed by each player
4 - Random spawn of powerups when walls break
5 - Each Powerup's gameplay implementation  (Assets for powerups)

HUD Design
Player1 stats 
Player2 stats
Pause Menu
Game Over Dialogue/Menu

Low-Priority
  Particle effects for explosion of Bombs and other destructibles
  Audio Effects and Game-state feedback via audio