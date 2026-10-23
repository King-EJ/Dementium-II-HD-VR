# Dementium-II-HD-VR
VR mod for Dementium II HD


DEMENTIUM II HD VR  v0.1.7 (tested with Quest 3 VDXR)
==========================
VR mod for "Dementium II HD" (Unity 3.5.7f6, Mono, 32-bit) - BepInEx 5 (x86, included).

Install
-------
1. unzip into the game folder (next to the game's .exe):
   "Start Dementium II VR.bat" (in the game folder), or add  -force-opengl  to shortcut or Steam launch options.
   
2. Start Quest Link / Virtual Desktop / SteamVR first (it must be the active OpenXR runtime), then the game.
   The game is 32-bit, so the runtime must have a 32-bit OpenXR part and OpenGL support. Meta (Oculus) and SteamVR

You see the world from William's eyes. Head look: where you look is where he looks, walks, shoots and uses things.
The HUD floats in front of your eyes (see-through); menus, the journal / inventory and puzzles stand on a screen in
the room in front of you.

Controls (the game's own Xbox layout on the VR controllers)
--------
  Left stick ............ walk
  
  Right stick left / right .. turn (snap or smooth)
  
  Right trigger ......... fire / attack (RT) 
  
  Left trigger .............. run (same as L3)
  
  Right grip ............ reload (RB) 
  
  Left grip (tap) ........... crouch (LB)
  
  B ..................... use / pick up / open  
  
  X ......................... flashlight
  
  A ..................... jump     
  
  Y ......................... next weapon (cycles)
  
  Left stick click ...... run (L3) 
  
  Right stick click ......... zoom (R3)
  
  Right stick up ........ dagger (d-pad up)   
  
  Right stick down .......... sledgehammer (d-pad down)
  
  Hold left grip + right stick: right = revolver, left = shotgun, up = machine gun, down = flamethrower
  
  Menu button (tap) ..... pause menu (Start)  
  
  Menu button (hold) ........ journal / inventory (Back)
  
Tap both stick clicks . re-centre the view

Hold both stick clicks 1.2 s ... VR settings menu (**kinda hard to see**)

Weapons are in your hands (6DOF): right-hand weapons on the right controller, the flashlight in the left.
  Guns shoot along their barrel (red laser = where the shot goes). Melee weapons (dagger, sledgehammer, bonesaw)
  hit what the blade passes through when you swing - RT still does the game's own attack too.
  The game's arms on the weapons / flashlight are hidden ([Weapons] HideArms).
  Each weapon's place in your hand: VR settings menu > **"Adjust the weapon in your hand"** (hold left grip = grab and
  move / turn it, right stick = forward-back / roll, B = default, A = done; saved per weapon in [WeaponOffsets]).
  The flashlight: **"Adjust the flashlight in your left hand"** (turn it on first; hold RIGHT grip = grab, left stick =
  forward-back / roll, Y / B = default, X / A = done).
  
Menus / inventory / puzzles: point the right controller at the screen (blue laser = the mouse pointer),
  right trigger = click. The left stick also moves the pointer.

