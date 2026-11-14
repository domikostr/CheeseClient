# Käse Client

*Käse = cheese.*

A client-side Fabric mod for Minecraft Java Edition with a customizable glass-style interface, HUD modules, visual options, cosmetics, and local tools. No separate launcher, ads, combat hacks, or movement hacks.

> **Käse Client 1.0.0** supports Minecraft **1.21.11**. It is not an official Minecraft product and is not approved by or associated with Mojang or Microsoft.

## Features

### HUD and information modules

- **FPS Display**, **Ping Display**, **Coordinates**, **CPS Counter**, and **Combo Counter**
- **Day Counter**, **IRL Time**, **Speedometer**, **Reach Display**, **TPS Display**, and **Player Angle**
- **Keystrokes**, **Crosshair**, **Direction HUD**, **WAILA**, **Armor HUD**, and **Potion HUD**
- **Saturation**, **Scoreboard**, and **Boss Bar** modules
- Move, resize, and configure HUD modules in the live **Layout Editor**

### Quality-of-life modules

- **Freelook**, **Zoom**, **Toggle Sprint / Sneak**, and **Jump Reset Timing**
- **Waypoints**, including a saved last-death point, and **Ping Marker**
- **Name History**, **Nick Hider**, **Tier Tagger**, and **TNT Countdown**
- **Chat Tweaks** and **Better Screenshots**
- **Creative Flight** speed controls

### World and visual modules

- **No Fog**, **Fullbright**, and **Time & Weather Changer**
- **Block Outline**, **Custom Hitboxes**, **Cobweb Outlines**, and **Hit Color**
- **See-Through Armor**, **Old Animations**, **Kill Effects**, and **Locator Bar Heads**
- **Item Physics**, **Big Items**, **Item Lock**, **Shiny Pots**, **View Models**, and **Visual Items**
- **Motion Blur** and **Color Saturation**

### Cosmetics and customization

- Cosmetics: **Capes, Pets, Wings, Chains, Crowns, Halos, Auras, and Shields**
- **Emotes** with an emote wheel, plus a **Skin Library** and custom cosmetic pictures
- Main menu with module categories, keybinds, profiles, cosmetics, and settings
- Themes, custom colors, fonts, glass appearance, and configurable animations
- Configuration can be stored per game instance or shared between instances

### Sky Library, maps, and local statistics

- **Sky Library** for importing supported resource-pack skies, previewing them, and setting sky time and weather options
- **Built-in skies** and resource-pack sky selection
- **World Map** that records chunks loaded by Minecraft, separately by world and dimension
- Local **Playtime** and **Streak** statistics

### Media and other features

- **Dynamic Island / Now Playing** media controls
- UI sounds and sound muting options
- Screenshot helpers and chat enhancements

## Installation

1. Install [Fabric Loader](https://fabricmc.net/use/installer/) for Minecraft **1.21.11**.
2. Download [Fabric API](https://modrinth.com/mod/fabric-api) for Minecraft 1.21.11 and place it in your `mods` folder.
3. Download the latest Käse Client `.jar` from [GitHub Releases](https://github.com/domikostr/CheeseClient/releases) and place it in the same `mods` folder.
4. Start Minecraft with your Fabric profile.
5. Press **Right Shift** to open the Layout Editor or **Right Control** to open the main menu. You can change both keybinds in Minecraft's Controls settings.

Käse Client is a **client-side mod** and does not need to be installed on the server. Always check the rules of the server you play on.

## Supported versions

| Minecraft version | Status |
| --- | --- |
| 1.21.11 | Supported and tested |

Other Minecraft versions are not currently supported.

## Compatibility notes

- With VulkanMod, use **Simple** Motion Blur. **Camera** Motion Blur is unsupported with VulkanMod.
- Shader glass may fall back to its flat appearance if the graphics backend cannot use the shader.
- Dynamic Island media integration uses Linux MPRIS (`playerctl` or `dbus-send`).
- Sky imports enforce file and texture size limits. Oversized textures are rejected rather than resized. OptiFine/MCPatcher sky properties are read by the mod; those skies are not converted into another format.
- The World Map records only chunks Minecraft has loaded; it is not a complete server map.

## Privacy

Käse Client does not use telemetry. Some optional features contact external services when you use them:

- The Skin Library contacts Minecraft/Mojang services for profile, skin, and cape actions. Skin and cape changes send your Minecraft access token with the relevant request. The mod does not store or log that token.
- Tier Tagger requests tier data from MCTiers, SubTiers, or PvPTiers using a player name or UUID.
- Dynamic Island may download album artwork from the image URL supplied by your media player.
- Name History opens the selected player's NameMC profile in your browser.

## Feedback and bug reports

Open an [issue](https://github.com/domikostr/CheeseClient/issues) or contact us on [Discord](https://discord.gg/pra6k5WEFK). For bug reports, include your Minecraft version, other installed mods, and the `latest.log` file from your `logs` folder.

## License

Käse Client is **not open source**. It is distributed under the custom [Käse Client License](LICENSE), which allows free private, non-commercial use under its terms. Redistribution, modification, and reuse of project code or assets require written permission.

Third-party components are not covered by the Käse Client License and retain their own licenses. See [`src/main/resources/THIRD_PARTY.md`](src/main/resources/THIRD_PARTY.md) and the license files included with the mod.

## Credits

- Built with [Fabric](https://fabricmc.net/).
- Made by **khsp.** and **BayHarbotButcher**.
