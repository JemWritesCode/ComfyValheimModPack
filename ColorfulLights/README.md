**Recommended to use with**
- [Configuration Manager](https://www.nexusmods.com/valheim/mods/740)﻿. Then press F1 for mod options.

# ColorfulLights

  * You can color any torch, firepit, stone hearth and bonfire using RGB and HTML color codes!
  * Fireworks launched from bonfires will also be colored **AND** visible to others with the mod.
  * Those without the mod will still see yellow torches, green guck torches and standard yellow fireworks.
  * Color alpha value is now saved and loaded for more transparent lights.

# Configuration
You can hide the "Change Color" prompt using Configuration Manager if you don't want to see that all the time.

# Instructions

  1. Unzip `ColorfulLights.dll` to your `/Valheim/BepInEx/plugins/` folder.
  2. In-game, press F1 to bring up the ConfigurationManager and navigate to the ColorfulLights section.
     * Change the target color using the RGB sliders or using an HTML color code.
  3. Hover or any torch or fireplace and a prompt to change its color will appear.
  4. Hit `LeftShift + E` to change the color.

## Links

Github: [https://github.com/redseiko/ComfyMods](https://github.com/redseiko/ComfyMods)

Looking for a chill server? Join us on [Comfy Valheim Discord](https://discord.gg/ameHJz5PFk)

Looking for great Valheim servers to play on? Check out our community driven listing site at [https://valheimlist.org](https://valheimlist.org)


## Changelog

### 1.5.0

  * Added an option to change the font-size for the text prompt on hover.

## 1.4.0

  * Updated for Hearth & Home.
  * Renamed `LastColoredByPlayerId` ZDO key to `LightLastColoredBy`.

## 1.3.0

  * Fixed colors not applying to the Light component in the `Point light` GameObject.
  * Now writes the PlayerId to a new ZDO field: `LastColoredByPlayerId`.

## 1.2.0

  * Fixed a memory leak when caching lights/fires. Now starts a coroutine to clean-up the cache.

## 1.1.0

  * Adding configuration setting to hide the 'change color' prompt over a torch or fireplace.
  * Now saves the target color's **alpha** value to the ZDO and reads/uses this alpha value if present in the ZDO.

## 1.0.0

  * Initial release.