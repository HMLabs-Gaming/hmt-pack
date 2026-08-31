![HMT Clan wordmark](https://cdn.modrinth.com/data/cached_images/72c4791f6ac95e09ed862e3a20c937793c9f7486.png)

# HMT Pack

A client-side Fabric modpack for Minecraft 26.2 focused on performance optimization, quality-of-life improvements, and visual enhancements. Managed with [packwiz](https://packwiz.tools/) and published to [Modrinth](https://modrinth.com/).

## Features

- **Performance** — Sodium, Sodium Extra, Reese's Sodium Options, Lithium, Iris, FerriteCore, Better Block Entities, C2ME, VMP, ImmediatelyFast, ModernFix, BadOptimizations, Entity Culling, More Culling, and Bobby
- **Visuals** — Complementary Reimagined, Complementary Unbound, and MakeUp Ultra Fast shaders, Euphoria Patches, 3D Skin Layers, Wavey Capes, Capes, Continuity, FancyMenu, OptiGUI, Rinku, Skin Shuffle, Here 'n' There, Cubes Without Borders, and Greenscreen ore resource packs
- **Quality of Life** — Zoomify, Dynamic Crosshair, Dynamic FPS, Simple Voice Chat, Xaero's Minimap, Xaero's World Map, AppleSkin, Jade, Better Advancements, Better Statistics Screen, Mouse Tweaks, Shulker Box Tooltip, Crafting Tweaks, Chat Heads, Controlling, Searchables, Do a Barrel Roll, Extreme Sound Muffler, Gamma Utils, Locator Heads, More Chat History, Show Me Your Skin!, Toggle Sprint Display, ukus Armor HUD, CalcMod, and Mod Menu
- **Utilities** — Litematica, MiniHUD, Freecam, Freelook, Client Sort, Command Keys, Accurate Block Placement Reborn, and Scribble
- **Privacy** — No Chat Reports and Auth Me
- **Cross-version support** — ViaFabricPlus

## Installation

Download the latest `.mrpack` from [Modrinth](https://modrinth.com/modpack/kUYTdD3h), then open it with the Modrinth App or any launcher that supports `.mrpack` files.

## Development

### Prerequisites

- [packwiz](https://packwiz.tools/) CLI

### Useful Commands

```sh
# Install a mod from Modrinth
packwiz modrinth add <mod-slug>

# Remove a mod
packwiz remove <mod-slug>

# Update all mods
packwiz update --all

# Export for distribution
packwiz modrinth export -o release.mrpack
```

### Project Structure

```
mods/            — Mod metadata (.pw.toml files)
resourcepacks/   — Resource pack metadata
shaderpacks/     — Shader pack metadata
config/          — Mod configuration files
pack.toml        — Modpack metadata (name, version, loaders)
```

## Release

Export the pack for distribution:

```sh
packwiz modrinth export -o release.mrpack
```

Upload the resulting `.mrpack` to [Modrinth](https://modrinth.com/) and attach it to the GitHub Release.
