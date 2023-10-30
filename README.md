<div align="center">
  <img src="logo.png">
</div>

---

<div align="center">
  <img src="https://img.shields.io/github/v/release/BrandenEK/Blasphemous-Randomizer?style=for-the-badge">
  <img src="https://img.shields.io/github/last-commit/BrandenEK/Blasphemous-Randomizer?color=important&style=for-the-badge">
  <img src="https://img.shields.io/github/downloads/BrandenEK/Blasphemous-Randomizer/total?color=success&style=for-the-badge">
</div>

---

## Contributors

A very special thank you to everyone who has helped with the randomizer
- [@BrandenEK](https://github.com/BrandenEK) - ***Programming and design***
- [@ConanCimmerio](https://github.com/ConanCimmerio) - ***Spanish translations and image icons***
- [@EltonZhang777](https://github.com/EltonZhang777) - ***Chinese translations***
- [@RocherBrockas](https://github.com/RocherBrockas) - ***French translations***
- [@rcvrdt](https://github.com/rcvrdt) - ***UI design and creation***
- [@Exempt-Medic](https://github.com/Exempt-Medic) - ***Logic testing and improvements***
- [@JimmyDiamonds](https://github.com/JimmyDiamonds) - ***Logo design and creation***

---

## Useful Info

- Only works on the most current game version (4.0.67)
- Press 'Numpad 6' to display the current seed (If you are stuck in dialogue use this to break out of it)
- Save & Quit can be used to instantly return to your last Prie Dieu, which can fix softlocks and makes the 'Return to Port' prayer useless
- Consult the spoiler generated in the game directory if you are stuck or believe the seed is unbeatable
- Do not load a vanilla game in the randomizer or vice versa

---

## Gameplay Differences

Tirso's questline
- Tirso's helpers will never die, so herbs can be given to him at any time

Gemino's questline
- Gemino will never freeze, so the thimble can be given to him at any time

Viridiana's questline
- Viridiana will never die, so she can be used for all 5 boss fights and will always give her item at the rooftops

Cleofas' questline
- There is no longer an option to choose to slay Socorro
- He will not jump off of the rooftops, even after talking to him without the cord

Crisanta's questline
- The scapular will not skip the Esdras fight; instead, it is required to open the door to the chapel
- Perpetva's item can be retrieved even after defeating Esdras
- Crisanta will always hold the 'Holy Wound of Abnegation'
- Crisanta does not have to beaten with the True Heart equipped in order to obtain the holy wound, it just has to be in your inventory when talking to her

Door rando
- A command has been added to respawn the player from the chosen starting location
- All doors from the rooftops elevator and above will remain the same so that the main goal is still to find all 3 masks
- Some other doors will always remain the same as they are in the original game
- The spawn points of a few doors have been modified
- Platforms have been added to the main bell room in Jondo
- The sword heart doesn't have to be unequipped for the Library bone puzzle
- The chalice will never unfill
- The Cistern shroud puzzle will be automatically completed if the shroud is equipped
- The Albero warp room can not be teleported to until activated, and the gate has been removed

---

## Seeds

In order to choose a specific seed that you want to play on, click on the seed text box and type the desired number on the settings menu shown before starting a new game.  Seeds can be in the range of 1 to 99,999,999.
<br><br>
In order to make it easier for multiple people to play with the same item generation (Such as for races or multiplayer), a sequence of 7 images is shown in the top right corner of the settings menu.  This is a unique identifier of the seed that also takes into account the other configuration settings and ensures that items will be placed exactly the same for all players.

---

## Autotracking

Beginning in Randomizer 2.0.9, autotracking for the poptracker pack has been disabled

---

## Available commands
- Press the 'backslash' key to open the debug console
- Type the desired command followed by the parameters all separated by a single space

| Command | Parameters | Description |
| ------- | ----------- | ------- |
| `randomizer help` | none | List all available commands |
| `randomizer respawn` | none | Respawns the player from the chosen starting location |

---

## Logic difficulty

Easy
- No skips or glitches will be necessary
- Only the expected method of reaching items will be considered in logic
- Bosses require an extra 10% strength to be in logic

Normal
- Using dawn heart skips & mid-air stalls may be necessary
- Tiento may be required to access items in poison clouds without Silvered Lung

Hard
- Mourning and Havoc skip may be required
- Slash Upwarp skips, Dive Laser skips, and using Tirana to break switches are considered in logic
- Some items in poison clouds are considered in logic without Tiento or Silvered Lung
- Bosses require 10% less strength to be in logic

---

## Corpse hints

Each of the 34 corpses in the game can give a hint about the location of a random valuable item.  These include beads, prayers, sword hearts, relics, quest items, stat upgrades, and skills.  However, there are a few specific corpses that will always hint at the same location, so that some of the more inconvenient locations can possibly be avoided.
<br>
These are:
- Corpse in ossuary --> Isidora reward
- Corpse outside Sierpes --> Sierpes reward
- Corpse in Ferrous Tree --> Miriam reward
- Corpse in Echoes of Salt --> Chalice quest sword shrine
- Corpse outside wax puzzle room --> Wax puzzle chest
- Corpse outside Jocinero's room --> Jocinero's final reward
- Corpse at entrance of WhOTW --> White Lady tomb reward
- Corpse outside Albero church --> 50,000 tear donation reward

---

## Installation

Automatic installation
- This mod can be automatically installed using the [Blasphemous Mod Installer](https://github.com/BrandenEK/Blasphemous-Mod-Installer)<br>
- **Note:** Make sure to also enable the Modding API<br>
<br>

Manual installation
1. Download the latest release of the Modding API from https://github.com/BrandenEK/Blasphemous-Modding-API/releases
2. Follow the instructions there on how to install the api
3. Download the latest release of the Randomizer from the [Releases](https://github.com/BrandenEK/Blasphemous-Randomizer/releases) page
4. Extract the contents of the BlasphemousRandomizer.zip file into the "Modding" folder
