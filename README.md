# Ritual Master (AI: made by claude.ai)

A visual helper addon for Zealot and Runepriest in Warhammer Online Return of Reckoning

## Installation

* Download the latest release from the Releases page
* Extract the RitualMaster folder into your Interface AddOns directory
* Launch or reload the game and enable the addon in the User Interface menu

## Commands

* `/rm` displays status, commands, and sizes
* `/rm on` enables everything (all elements)
* `/rm off` disables everything
* `/rm reset` resets settings, sizes, positions, and icon dimensions to default
* `/rm dps` shows or hides the Harbinger DPS icon
* `/rm heal` shows or hides the Harbinger HEAL icon
* `/rm pointer` shows or hides the pointer (icon on the player, points toward the Nexus)
* `/rm symbol` shows or hides the symbol (icon on the Nexus)
* `/rm colors` enables or disables colors (otherwise default color)
* `/rm size pointer 0 | symbol 0 | dps 0 | heal 0` replace 0 with the size in pixels of YOUR images (0 = 64, the default value)

* Invalid commands display the list of commands
* Any change displays the status (or sizes for `/rm size`)
* Settings are saved per character

## Colors and Mechanics

* **Zealot Colors** Superiority = cyan | Lunacy = yellow | Innervation = orange | default = pink
* **Runepriest Colors** Fury = orange | Stability = yellow | Adamant = deep blue | default = turquoise
* **DPS and Out of Range** = Red: out of range of Nexus/Conduit healing (the pointer returns to default on the next heal), or DPS version of the Nexus or Conduit

* The DPS Nexus/Conduit tactic is detected when placed so you must cancel and recast the Nexus/Conduit after changing tactics
* The symbol only tracks YOUR ritual while the color also tracks another Zealot or Runepriest ritual and healing

## Custom Images

Images must be 32-bit TGA with transparency and the SAME SIZE as your chosen value in-game with `/rm size` (default is 64x64)

* `zealot_dps` / `zealot_heal` / `runepriest_dps` / `runepriest_heal` (TGA format, 64x64) Harbinger icons (any colors)
* `symbol` / `rp_symbol` (TGA format, 64x64) symbol on the Nexus for Zealot or Runepriest, preferably WHITE (tinted by the color)
* `pointer` / `rp_pointer` (TGA format, 64x64) pointer player icon with notch at the BOTTOM facing the Nexus, preferably WHITE (tinted by the color)
* 
* To change a picture, replace any in the main addon folder
* You can use a square image with larger dimensions and then change the settings in-game with `/rm size`

## Bonus Content

* The BONUS folder contains 2 image packs, plus a 3rd one containing blank images
* There is also a directory with a short collection of images, keep what you want and delete the rest

## UI Layout Editor

Two elements can be moved in the UI layout editor

* Ritual Master - Harbinger
* Ritual Master - Pointer

Remember `/rm reset` to go back to original settings

## Credits

* This addon was created by Claude.ai (AI) under the supervision of a brainless Zealot, thanks to the addon creators listed below
* We decline all responsibility in the event of an explosion, possession by a daemonic entity, or any Warp anomaly caused by this addon
* You are free to modify this addon

Huge thanks to:

* **Sullemunk**: "Harbinger" is the base of this addon
* **Talvinen**: "TargetRing" for the technique of attaching a symbol to a world object
* **Laydie** For the legendary help

-Abyss
