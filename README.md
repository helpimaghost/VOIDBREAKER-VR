# VOIDBREAKER-VR
A custom UEVR profile for VOID/BREAKER

0.5 by help im a ghost

This profile intends to bring immersive and kinetic 6DOF VR support to VOID/BREAKER.

    A UEVR profile and .lua scripts. Use latest UEVR Nightly!


The UEVR profile adds 6DOF motion controls to VOID/BREAKER, while the lua scripts extend functionality with features like a VR-oriented control scheme, gesture-based attacks, haptics, and other fixes and improvements.

UEVR Profile

    6DOF motion controls
    Hides gloves and body meshes, and some Niagra effects
    visual fixes and enhancements

    
Lua scripts with the following features:

    Gesture-based combat functions for grenades, gravity tether, weapon readying, and melee attacks
    VR-oriented, gesture-based control scheme
    Haptic responses to combat actions
    Removed camera shake while sprinting
    
    
Installation

    Delete any previous VOIDBREAKER profiles from your UEVR global directory ( C:\Users\<username>\AppData\Roaming\UnrealVRMod )

    Import the profile via your preferred methodolgy. I personally use Rai Pal for UEVR injection and profile importing profiles:
    https://raicuparta.com/rai-pal/

    Launch the game, and Continue or Start a new game.

    Once the game has loaded, Inject UEVR- this will take a few seconds to complete.

    Recenter the game when in your playspace- Standing is highly recommended!!

    If the Right Controller is not moving the crosshair, press and release Right Grip. If Right Stick movement is opening the map, try pressing different controls until it clears, or try restarting the game.

    
Controls

    This profile assumes that all in-game control bindings are set to their default values.

General

    Move: LS
    Jump: Right Stick Up
    Crouch/Slide: Right Stick Down
    Sprint: Left Stick Click
    Dash: Left Grip

Interaction & Combat

    Ready your weapon: Move your Right Controller up from your side to switch your aim mode to the controller. Lower your hand to switch back to the default HMD aiming
    Fire: RT
    Reload: B
    Grenade - 'Grenade' gesture: hold Right Grip, aim where you want to throw with HMD, flick/throw right hand while releaseing Right Grip
    Gravity Tether - 'Telekinesis' gesture: move the Left Hand near head to Grab the highlighted object targeted by your HMD, flick/push Left Controller forward to Throw
    Melee - 'Sword' gesture: move the Left Controller near your right hip to grab and hold your sword; Swing the Left Conttroller outward to perform the attack. You can't perform other attacks while in melee!
    Main Menu: System
    Inventory - TO DO - currently D-pad
    Map - TO DO - currently D-pad
    Ammo Quickswap - TO DO - currently D-pad left

    
Known Issues

    The 'Melee' gesture may sometimes get hung and fire erratically - Recenter your view via your preferred methodology to correct.
    The Main Menu appears at a 45-degree angle above your head, and the map at your feet. Tougher to fix.
    Sometimes the touchpads seem to stick, resulting in Right Stick malfunction. Restarting the game fixes
    Sometimes the game fails to render in the right eye on launch. Restarting the game fixes
    Menus/Inventory are currently cumbersome to navigate
    If there are scopes in this game, they almost certainly don't work
    

IN-GAME SETTINGS

    Disable camera shake
    Set preferred DLSS mode, DLAA is a big help here if you can afford it


PLANNED FEATURES AND OVERLY AMBITIOUS WISHLIST MIXED TOGETHER

    Better menu, inventory, map and cursor support
    Better mesh and special effects attachments
    Refine and improve gesture accuracy and responsiveness
    Improved haptic support
    Better controller layout and input masking that doesn't break menu navigation
    Fix certain visual effects (wireframe effects are too thick at a distance, some shadow/reflection effects)
    2-handed weapon holding
    Better crosshair attachment for Right Hand
    Better HUD- certain widgets attached to HMD
    gesture-based weapon wheel
    BHaptics/Protube support
    

Special thanks to Keyser-Soze, DJ, Ashok, Praydog, and the rest of the F2VR community
