# VOIDBREAKER-VR
A custom UEVR profile for VOID/BREAKER

0.5 by help im a ghost

This profile intends to bring immersive and kinetic 6DOF VR support to VOID/BREAKER. Use the latest UEVR Nightly!


The UEVR profile adds 6DOF motion controls to VOID/BREAKER, while the lua scripts extend functionality with features like a VR-oriented control scheme, gesture-based attacks, haptics, and other fixes and improvements.

UEVR Profile

- 6DOF motion controls
- Hides gloves and body meshes, and some Niagra effects
- Visual fixes and enhancements

    
Lua scripts with the following features:

- Gesture-based combat functions for grenades, gravity tether, weapon readying, and melee attacks
- VR-oriented, gesture-based control scheme
- Haptic responses to combat actions
- Removed camera shake while sprinting
    
    
Installation

1. Delete any previous VOIDBREAKER profiles from your UEVR global directory ( C:\Users\<username>\AppData\Roaming\UnrealVRMod )

2. Import the profile via your preferred methodolgy. I personally use Rai Pal for UEVR injection and profile importing profiles:
https://raicuparta.com/rai-pal/. Note that this UEVR profile is named for the Steam version of the game, you may have to rename the .zip file for other versions!

3. Launch the game, ensure that display is set to Windowed, and Continue or Start a new game.

4. Once the game has loaded, Inject UEVR- this will take a few seconds to complete.

5. Recenter the game when in your playspace (hold right Oculus/Universal Menu button)- This is now a much more active game, standing in adequate space to swing your arms around is highly recommended!!

Note: If the Right Controller is not moving the crosshair, press and release Right Grip. If Right Stick movement is opening the map, try pressing different controls until it clears, or try restarting the game.


IN-GAME SETTINGS

- Set Display Mode to Windowed
- Set preferred DLSS mode, DLAA is a big help here if you can afford it
- Disable camera shake

    
Controls

This profile assumes that all in-game control bindings are set to their default values.

Interaction & Combat

Here's how this plays:
Yeah, it's a first person shooter, but your aim isn't actually tied to your gun most of the time, but the headset- bear with me for a minute.

Think Psi-Ops Supersoldier- you have a gun, but that's not the only thing in your arsenal. You also have:

- Gravity Tether- You look around your environment to find something throwable (and preferably explosive). Use your telekinetic mind powers to pick it up by swinging your left hand up near your head, and throw it by flinging     or pushing it away. No grenades or melee while you're carrying something!

- Grenades- If you're NOT carrying something, grenades are good for AOE damage, and staggering enemies so that they drop health when killed. Throw a grenade by holding Right Grip, looking at where you want your grenade to go, and then throwing or flicking the Right Controller as you release. You can throw grenades across your body or over to your right as well, as long as you can look at where you want the grenade to go. You can sidearm grenades into alleys or hookshot then over your head if that's your style.

- Sword- Sometimes things get too close and a sword is your best option. Swing your sword by performing a sharp, horizontal slash with your Left Controller.

- Gun- Yes, this is a first person shooter and you have access to several different firearms, with more coming in the future. Raise your right hand to ready your gun, which will dynamically switch your aiming mode to shoot at whatever you want to shoot at. Lower your right hand to switch aiming back to the headset for other combat functions, or keep it up if you prefer to aim things that way. Reload with (B), Ammo Quickswap eventually coming to (A).
NOTE- Re-center your view if the crosshair feels off! It is not 100% perfect, but should line up pretty well.


Movement

- Dash - Left Grip
- Sprint - Left Stick Click (or set to Always Sprint in settings)
- Jump - Right Stick Up
- Crouch/Slide - Right Stick Down


    
Known Issues

- The Main Menu appears at a 45-degree angle above your head, and the map at your feet. Tougher to fix.
- Sometimes the touchpads seem to stick, resulting in Right Stick malfunction. Restarting the game fixes
- Sometimes the game fails to render in the right eye on launch. Restarting the game fixes
- Menus/Inventory are currently cumbersome to navigate
- If there are scopes in this game, they almost certainly don't work
    


PLANNED FEATURES AND OVERLY AMBITIOUS WISHLIST MIXED TOGETHER

- Better menu, inventory, map and cursor support
- Better mesh and special effects attachments
- Refine and improve gesture accuracy and responsiveness
- Improved haptic support
- Better controller layout and input masking that doesn't break menu navigation
- Fix certain visual effects (wireframe effects are too thick at a distance, some shadow/reflection effects)
- 2-handed weapon holding
- Better crosshair attachment for Right Hand
- Better HUD- certain widgets attached to HMD
- Gesture-based weapon wheel
- BHaptics/Protube support
    

Special thanks to Keyser-Soze, DJ, Pande4360, Ashok, Praydog, and the rest of the F2VR community
