# VOIDBREAKER-VR
A custom UEVR profile for VOID/BREAKER

0.9 by help im a ghost

This profile intends to bring immersive and kinetic 6DOF VR support to VOID/BREAKER.


The UEVR profile adds 6DOF motion controls to VOID/BREAKER, while the lua scripts extend functionality with features like a VR-oriented control scheme, gesture-based attacks, haptics, and other fixes and improvements.

Use Windowed mode and the latest nightly UEVR build!!!
https://github.com/praydog/UEVR-nightly

IMPORTANT NOTE: For DLSS4 to work, after injecting & in-game, go to Settings in-game, click on "DLSS", and then re-select it from the dropdown to resolve. The game will appear much lower resolution with visual smearing otherwise!


UEVR Profile

- 6DOF motion controls
- Hides gloves and body meshes, and some Niagra effects
- Visual fixes and enhancements

    
Lua scripts with the following features:

- VR-oriented, gesture-based control functions for shooting, grenades, gravity tethering and throwing items, weapon readying, ammo quickswap and attachment changes, special abilities, and melee attacks
- Dynamic aim system that respects player intent- no guessing or manual aim method switches, everything just works
- Haptic responses to interaction, combat, and movement actions
- Customizable Right-stick tuning: set deadzone, linear zone, and acceleration curve for smoother and more responsive analog turning
- Removed camera shake while sprinting
- fixed menu orientations to the playspace
- fixed and stabilized inventory menu and map
- fixed start menu angle
- visual improvements
- (Quest) One-handed Gesture D-Pad (hold Right thumbrest and move the controller Up, Down, Left, or Right)
    
    
Installation

1. Delete any previous VOIDBREAKER profiles from your UEVR global directory ( C:\Users\<username>\AppData\Roaming\UnrealVRMod )

2. Import the profile via your preferred methodolgy. I personally use Rai Pal for UEVR injection and profile importing profiles:
https://raicuparta.com/rai-pal/. Note that this UEVR profile is named for the Steam version of the game, you may have to rename the .zip file for other versions!

3. Launch the game- ensure that display is set to Windowed, and Inject UEVR

4. You may need to press RB to take control of your character. Recenter the game when in your playspace (hold right Oculus/Universal Menu button)- This is now a much more active game, standing in adequate space to swing your arms around is highly recommended!!



IN-GAME SETTINGS

- Set Display Mode to Windowed
- Set preferred DLSS mode, DLAA is a big help here if you can afford it
- Disable camera shake

    
Controls

- This profile assumes that all in-game control bindings are set to their default values.

Interaction & Combat

Here's how this plays- STANDING HIGHLY RECOMMENDED:

- Gun- Fire with RT, reload by tapping (X)

- Gravity Tether- Move the Left Controller near your head to Grab the highlighted Throwable Object, and throw it by flinging or pushing the Left Controller. No grenades or melee while you're carrying something!

- Grenades- Throw a grenade by holding Right Grip, then throwing or flicking the Right Controller as you release. You can throw grenades across your body or over to your right as well, as long as you can look at where you want the grenade to go. You can sidearm grenades into alleys or hookshot then over your head if that's your style.

- Sword- Swing your sword by reaching your Left Controller to your right hip to grab it, and Swing the Left Controller outward to perform an attack. You cannot perform other attacks while holding the sword.

- Ability- Hold (X) and swing the Right Controller to use your Ability

Movement

- Dash - Left Grip
- Sprint - Left Stick Click (I personally recommend changing this to Always Sprint in settings)
- Jump - Right Stick Up
- Crouch/Slide - Right Stick Down

(Quest) Hold Right Thumbrest and move the controller in the corresponding direction to perform D-Pad presses:
- Up - Ammo Quickswap
- Down - Mission Objective
- Left - Weapon Attachments
- Right - Map/Mods/Inventory
    
Known Issues

- DLSS does not properly apply on launch, and needs to be selected again before it will take effect
- If there are scopes in this game, they almost certainly don't work
- CinematicCamera stabilization needed
- some effects do not properly render- you may wish to keep Reflections set to Low
- in-game FOV modifiers do not work correctly


PLANNED FEATURES AND OVERLY AMBITIOUS WISHLIST MIXED TOGETHER

- cursor support
- Better mesh and special effects attachments
- Refine and improve gesture accuracy and responsiveness
- Improved haptic support
- Fix certain visual effects (wireframe effects are too thick at a distance, some shadow/reflection effects)
- 2-handed weapon holding
- BHaptics/Protube support
    

Special thanks to Keyser-Soze, DJ, Pande4360, Lukasblaster, Ashok, Praydog, and the rest of the F2VR community
