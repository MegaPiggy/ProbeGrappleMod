# Probe Grap(p)le Mod v.1.1.1
Mod for the Alpha Outer Wilds version 1.2 that adds a grapple rope to the game

### How do I install it?

0. Follow instalation of [DIMOWA](https://github.com/ShoosGun/DIMOWA) if you haven't already. 
1. Download the dll from one of the [releases](https://github.com/ShoosGun/ProbeGrapleMod/releases).
2. Place the dll from the mod in the `mods` folder.
3. Place the `assets` folder in the `\OuterWilds_Alpha_1_2_Data\` folder, if one already exists merge them together
4. Run the installer.

### How do I uninstall it?

Using [DIMOWA](https://github.com/ShoosGun/DIMOWA), select the uninstall option.

### What it does?

It gives the player a new equipment to use: a *grappling rope*, it acts like a long rubber band and can have its size increased and decreased

### How do I use it?

Here is what each button does:

  **G** - Throws the rope anchor | Retrieves the anchor
  
  **T** - Makes the rope longer: at each quarter of a second that the button is held, it has an increase of  25 cm (untill it reaches 100m)
  
  **Y** - Same as the **T** button, but it decreases the rope size (untill it reaches 75 cm)
  
  * The rope starts with a length of 5m, and you can change its size before throwing it
  * The rope *breaks* when you are 25m + its length away from it
  
  ### Known bugs
  - [ ] *NullReferenceException
  at (wrapper managed-to-native) UnityEngine.Rigidbody:INTERNAL_get_worldCenterOfMass*
  - [ ] *NullReferenceException
  at (wrapper managed-to-native) UnityEngine.Rigidbody:INTERNAL_get_worldCenterOfMass*
  - [ ] *NullReferenceException
  at (wrapper managed-to-native) UnityEngine.Rigidbody:INTERNAL_get_worldCenterOfMass*
  - [ ] *NullReferenceException
  at (wrapper managed-to-native) UnityEngine.Rigidbody:INTERNAL_get_worldCenterOfMass*
  - [ ] *NullReferenceException
  at (wrapper managed-to-native) UnityEngine.Rigidbody:INTERNAL_get_worldCenterOfMass*
