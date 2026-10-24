# Modded Sims

Mods and tools for [The Sims 4](https://www.ea.com/games/the-sims/the-sims-4) (Maxis, Electronic Arts).

## Mods

| Mod | Repository | What it does |
|---|---|---|
| Mod loader | `sims4-mod-loader` | The script extender of the game. It loads the DLL mods, checks them, and gives the in-game menu bar, the mod settings and a native module for script mods. |

## Templates

| Template | Repository | What it does |
|---|---|---|
| DLL mod template | `sims4-mod-template` | The folder structure, the config files, the build and the tests of a DLL mod for the mod loader. Use it to start a new mod. |

## Install

1. Install the mod loader with its install tool.
2. Put the DLL mods in the folder of DLL mods of the mod loader, and the script mods (`.ts4script`) and packages in
   `Documents\Electronic Arts\The Sims 4\Mods`.
3. Turn on mods and script mods in the game options, then start the game.

Each mod names the game versions that it is for. An update of the game can stop a mod until the mod has a new release.
