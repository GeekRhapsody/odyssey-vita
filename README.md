# Odyssey Vita

A theme for [Odyssey Launcher](https://github.com/GeekRhapsody/OdysseyLauncher) inspired by the PlayStation Vita's home screen: every system is a glassy pebble the colour of its logo, the logo on its front, floating over a bright blue background, with deep blue menus.

## Installing

In Odyssey Launcher: Menu, then **Look**, then **Download themes**, then **Odyssey Vita**. Choose it under **Theme**.

By hand: put this folder in the launcher's `themes` folder as `odyssey-vita` (`%APPDATA%\OdysseyLauncher\themes\odyssey-vita\`, or `userdata\themes\odyssey-vita\` in a portable install).

## What's in it

- `theme.toml`: the look (background, lights, menus) and the pebble for every system.
- `models/pebble.glb`: the pebble, a glass lens of 12,096 triangles. All of it is the `label` slot: the system's logo is projected onto its front (and, mirrored, its back, as if seen through the glass), and the rim takes the logo's colour.
- `logos/<system id>.webp`: a logo for each of the launcher's built-in systems, and for Favourites, Recently played and All games. A system without one shows its name on its pebble. To give one a logo of your own, add `logos/<its id>.png` (or `.jpg` or `.webp`); a file you add stays when the theme updates.

Game templates and the systems' colours are the launcher's base theme's.

## Credits

The system logos (`logos/`) come from [**canvas-es-de**](https://github.com/Siddy212/canvas-es-de) by [Siddy212](https://github.com/Siddy212), a theme for ES-DE; canvas-es-de credits its original artwork and layouts to fagnerpc. They're used under the [Creative Commons Attribution-NonCommercial-ShareAlike 2.0](https://creativecommons.org/licenses/by-nc-sa/2.0/) licence (CC BY-NC-SA 2.0). 

The logos show console makers' and publishers' trademarks, which belong to their owners. PlayStation Vita is a trademark of Sony Interactive Entertainment; this theme isn't affiliated with or endorsed by Sony.
