# Better Vehicle Menu

Better Vehicle Menu is a BepInEx plugin for **Global Rescue** by Suchti On Tour.

It adds a dedicated on-screen vehicle shortcut menu for faster access to Police, SWAT, Fire, and Rescue vehicles, while still using the original in-game vehicle menu in the background.

## Info

[Suchti Mod Manager](https://github.com/SuchtiOnTour/GR_Suchti_ModManager) is recommended for changing settings in-game.

## Features

- Adds a custom on-screen vehicle shortcut menu
- Quick access buttons for Police, SWAT, Fire, and Rescue
- Opens the original vehicle menu automatically after selecting a shortcut
- Applies the correct department tab in the original menu
- Applies the correct base filter in the original menu
- Skips the base dropdown when only one matching base exists
- Uses renamed base names from the savegame
- Optional vehicle list sorting inside the original menu
- In-game UI positioning and scale settings through the Suchti Mod Manager

## Installation

1. Install BepInEx for Global Rescue.
2. Download `GR_Suchti_BetterVehicleMenu.zip` from Releases.
3. Extract the ZIP into the Global Rescue game folder.
4. The files should look like this:

```text
BepInEx/plugins/GR_Suchti_BetterVehicleMenu/GR_Suchti_BetterVehicleMenu.dll
BepInEx/plugins/GR_Suchti_BetterVehicleMenu/icons/fire.png
BepInEx/plugins/GR_Suchti_BetterVehicleMenu/icons/police.png
BepInEx/plugins/GR_Suchti_BetterVehicleMenu/icons/rescue.png
BepInEx/plugins/GR_Suchti_BetterVehicleMenu/icons/swat.png
```

## Notes

- Tested with Global Rescue `0.3.18`.
- Config is stored next to the DLL.
- The mod can be configured in-game with `GR_Suchti_ModManager`.
