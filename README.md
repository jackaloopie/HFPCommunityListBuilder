# Halo: Flashpoint Community List Builder

A lbrowser-based list builder for **Halo: Flashpoint**.  
All the features you've requested... and more.

## Use it online
List Builder: https://jackaloopie.github.io/HFPCommunityListBuilder/
## Features
- Build forces by **Faction**
- Tracks **Points**
- Validates **Required** slots and **Optional** caps
- Unit **upgrades** support
- **Copy roster** output for sharing
- **Save/Load JSON** list files
- **Print / Export to PDF**

## To Run locally
1. Download the `.html`
2. Open the `.html` file in your browser

## Notes
This is a fan-made community tool and is not affiliated with Microsoft, Mantic Games or Halo Stuidos

++ChangeLog++

V1.1-   8-6-2026

UI & Layout

* Sticky Header: Points total now floats at the top of the page when scrolling.
* Floating Button: Back to Editor button now only displays in gameplay mode.
* Keyword Display: Shortened Energy Shield Depleter to ESD and Weight of Fire to WoF.

Rules Fix

* ODST Captain: Can now be included with Spartans that do not have the Tactician keyword.

Weapon Profile Fix

* Hydra: Added ESD (1) keyword to profile.

Unit Profile Fixes

* Master Chief: Added HVT keyword.
* Carter & Jun: Replaced standard combat knife with M11 Combat Knife.
* CQB Spartans (Hammer & Sword): Fixed Speed to 1-3. Changed Hammer Fight to 4+. Changed Sword Survive to 6+.
* Gungnir Spartans: Added Guarded and Stable keywords to variants. Removed Tactician from M41 SPNKr variant.
* Zvezda Spartans: Fixed Speed to 1-3.
* Atriox: Added HVT and Imposing keywords. Created database entry for Power Gauntlet and added it to default weapons.
* Chosen Warrior: Added Guarded keyword and default Spike Grenade.
* Jiralhanae Warrior: Added default Spike Grenade.

v1.2-   9-6-2026

* Moved the 'Back To Editor' button from the bottom right to the top right.
* Removed the tickbox selections displaying text when selected in section 2.
* Re-fixed unit limitiations. Only 2 of each base unit, and only 1 of each legend.
* Removed the code that would attempt to automatically hide fireteam upgrade reference when switching detachments. BUG: On inital load, the manual tickbox to do this feature starts hidden, but then reveals once the first detachment/faction switch happens. It should ALWAYS be on but I couldn't fix it.
* Made the selected Detachment name display in the header/title box, which forced some UI movements in that section.
* Made the invalid list pdf printout a option instead of a hard no. Future: Can probably expand this to check if you have the required unit for each specific special order.
* Future Proofed, add rules around 'support' and their limit to only half the team.
* Updated some descriptions and things.

Changelog v1.3  14-06-2026

* New Content (99 pts placeholders): Added Target Acquired, Unggoy Plasma Assault, Hand Of Atriox (Special Orders), and the Sangheili Enforcer unit.
* ID Maintenance: Cleaned up various underlying Unit IDs.
* New List Validation Requirements
* The validation engine now strictly checks for the following dependencies before clearing a list:
* Spartan Requirements: Return to Sender and Snapshot require a Spartan unit (sp in ID).
* Legend Restrictions:
* Your Orders Have Changed requires Veronica Dare.
* One Man Army requires Master Chief.
* Lone Wolf requires Noble Six.
* Defiance requires Atriox.
* Hand Of Atriox requires Jega, Hyperius, or Tovarus.
* Faction / Unit Types:
* Hot Drop requires an ODST unit (odst in ID).
* Holograms requires a Noble Team member (noble in ID).
* Rampage requires a Jiralhanae unit (bru in ID).
* Reinforcements Incoming requires a Sangheili unit (elite in ID).
* Unggoy Plasma Grenade Assault! requires a Grunt unit (grunt in ID).
* Keyword Matching: Target Acquired requires a model with the exact standalone Support keyword (isolated via raw regex from Support Weapons).

Changelog v2.0 1/9/2026
* Should be fully updated to v1.5.
* Expanded list of reminders if list is invalid, such as 'too many support fireteam members'
* Expect minor errors, email if found
