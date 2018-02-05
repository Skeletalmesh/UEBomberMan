# UEBomberMan

## BomberMan Rapid prototype for 2-Local Players, in Unreal Engine within in 15 hours

> Engine version 4.18.2 (4.19 is out, but I will differ the update after this)

 This is going to be a quick 15 hour hacky prototype implementation in UE 4.18.2. I will be doing this is 1-2 sessions. This is supposed to be implemented with a mix of C++ and Blue-print scripting. But I am not yet certain on which parts to seperate out that way, as there  may not be need for a Centrailzed 'Game Manage' or Game-mode for the simple gameplay.  I prefer to implement this in Entity-Component system, and not much of Parent, Child classes as the logic is quite simple.  I personally, prefer to *Write Code* than connect nodes and graphs, as most programmers do.  
 
My goal here is to get a Polished feel to the game rather than a Programmersque Box-Sphere-Plane POC (Besides, I'm reluctant to install Windows 8 SDK, Unreal VS Extension, etc on my overloaded Laptop). Pure blue-print approach will probably save time,in the 15 hours, I rather use to make it polished, create sounds and P-FX instead

>2:04 am (Almost 6 hours into the project).  I am not happy with the progress.  
>Have to blame on getting 2-pawns to move with a keyboard hack.  Took up most of 
>my planned time.

## Session 2
Could not get Visual studio 2015 to work with my recent update to UE 4.18.2. Need VS2017 for it. The 128GB SSD on my laptop is a pain (Always on 10GB free space borderline). Gotta remove vs2015 to make space (D: for VS not a good idea).

Created a Project section with simple kanban board(Github only keeps getting better)
Current task https://github.com/Skeletalmesh/UEBomberMan/projects/1#card-7172737  
Taaking a couple of hours - break 

## Session 3 - I love Unreal Editor, but C++ workflow is too inefficient compared to Unity3D.  
 
 I used up 15 hours. Lot of things to be done. Attempting C++ version(of BOMB blueprint) turned out very frustrating and **SLOW**, that I reverted the whole project.  Lost a lot of time.  Overall, I am not happy with C++ scripting for Unreal. Unreal's heavy MACRO dependence for UPROPERTY, UFUNCTION, etc. means Intellisense or VisualAssist dont help there. (Infact, I could not get VA_X to work)  The whole workflow is terribly inefficient, compared to Unity - C#. Change something in .h file and you loose 10 mins. Totally not worth, whatever performance gain with CPP. But this project aint pushing nothing.  In 2003, I was part of the only team in India to get Unreal 2.5 Source license, and I was the only Engine side C++ Developer. Worked mostly on D3D9 and XBoxRenderer modules.   But, now after using Unity, I feel like Unreal-Engine is slowing me down, when working in C++.  For simple gameplay, its not a good idea.  And Unreal Engine, despite all its awesomeness is fundamentally a different philosophy from Unity.   It DOES NOT give you a Blank Sandbox. Its' design along with the "Gameplay Framework" is centered around FPS, TPS (or vehicle) *Games*.  Stuck in same 'Import everything as .uasset; paradigm. In Unity3D an FBX is an FBX and png is a png. (Platform specific imports hidden in Cache).  UI workflow is poor and not suited well for 3D app development (May be ArchiViz and FP-simulations are fine), But if I have to build a non-game Platform, User uploadable content, Rapid interaction with external SDKs and APIS, Mixed Reality apps = Unity3D is a better choice in many respects. Visual quality is 90% close to UE.  You can further push to 96% with Asset store plugins. (And there are tons, more than many for every purpose).  
