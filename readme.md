# *Among Us* Settings

Custom game settings and preset files for **Among Us** and some of its mods.

## General Game Settings

The below options apply to unmodded and modded versions of *Among Us* and broadly establish a more competitive experience. Note that these all need to be adjusted manually as they are not part of any mod and can't be controlled by preset systems.

Setting | Value | Comments
--------|-------|---------
Number of Imposters | 1-3 | *Depends on lobby size*
Confirm Ejects | unchecked | *Adds mystery and gives remaining impostors a better chance*
Emergency Meetings | 1
Emergency Cooldown | 15s
Discussion Time | 0s | *Removes discussion time in favor of extended voting time*
Voting Time | 135s
Anonynous Votes | checked | *Gives certain roles the necessary cover to manipulate votes*
Player Speed | 1.00x
Crewmate Vision | 0.75x
Imposter Vision | 1.5x
Kill Cooldown | 30s | *Depends on the desired imposter/crewmate balance*
Kill Distance | short
Visual Tasks | unchecked | *Prevents free clears between crewmates*
Task bar Updates | meetings | *Adds to the suspense of close games*
Common Tasks | 2 (maximum)
Long Tasks | 3 (maximum)
Short Tasks | 5 (maximum)

## Preset Files

To use the modded preset files in this repository, download and place them in the following folder:
```
\Users\<User>\AppData\LocalLow\Innersloth\Among Us
```
The above path can be reached by pressing `Win + R` and pasting the following into the popup:
```
%APPDATA%\..\LocalLow\Innersloth\Among Us
```
Pressing `Enter` or clicking "OK" will open the folder into which the preset files need to be placed.

### Town Of Us

The preset files for the [*Town Of Us*](https://github.com/polusgg/Town-Of-Us) mod are named `GameSettings-Slot[1-3]`.

Once the files are placed, create an **Among Us** lobby, go to the "Game" tab of the `Customize` laptop, click "Load Custom Settings", and select the slot corresponding to the number in the filename (1-3).

Recommended usage:
- **5–7** players: `GameSettings-Slot1`
- **8–12** players: `GameSettings-Slot2`
- **12–15** players: `GameSettings-Slot3`
