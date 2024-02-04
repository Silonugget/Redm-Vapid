# RedM Vapid script - STANDALONE

## About

RedM Vapid is the port of a Gta-5-mod addon car along with script to make it functional for RedM servers. This modification was developed for an educational tutorial.

## Key Features

- **Synchronization**: Workarounds were discovered to keep the car visible upon new player join when tested with two people
- **Sounds**: Using the PMMS resource by Kibook, https://github.com/kibook/pmms, the Vapid has sounds similar to a real vehicle
- **Capablility**: Config file includes top speed and acceleration speed lines to fine tune handling
- **Wheel Rotation** Realistic wheel behaviour - Press A or D to see the wheels turn in the corresponding direction

## Important/Issues
- Please ensure your Advanced Graphics setting is on **Vulkan** instead of DX12 in game. The Vapid cannot render under DX12 and will crash
- Lights will display at night automatically when the engine is on

## Installation

1. Drag and drop Redm-Vapid into server resources
2. Ensure Redm-Vapid


## Commands
Change select commands such as spawn command in the config.lua file

| Command | Description |
| --- | --- |
| `/vapid` | Spawns the vapid next to player |
| `/deletevapid` | Deletes vapid |
| `/resetvapid` | Resets vapid |
| `/fixme` | Manual toggle for player visibility de-sync - Teleports player to Mexico and back |
| `/fixvapid` | Manual toggle for object visibility de-sync - Toggles vapid visibility |
| `/lock` | Preliminary idea for locking - Makes vehicle undriveable (wheels are likely to fall off/cannot be unlocked) |

# controls

Turn Engine on/off = Left Alt, 
   Rev = R


## Screenshots
![screen1copy](https://github.com/Silonugget/redm-vapid/assets/107784929/04963c48-c608-45d6-ac9c-5ab874d82066)

![screen2](https://github.com/Silonugget/redm-vapid/assets/107784929/47ca92c6-ead6-4e62-af09-71ce80295afb)

![screen3](https://github.com/Silonugget/redm-vapid/assets/107784929/ff2c9950-ab95-46b5-9e8a-7781a19477f1)

[Demo Video](https://silonugget.com)

## Credits
- johndoe968 / Mad Rodger  https://www.gta5-mods.com/vehicles/vapid-flivver-add-on
- Zelbeus for Script elements https://github.com/zelbeus/redm_car
- Kibook for PMMS resource https://github.com/kibook/pmms
- Thanks to Luman Studios for sharing knowledge that inspired the idea
