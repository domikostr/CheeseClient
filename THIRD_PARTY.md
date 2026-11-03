# Third-party components

Käse Client is made of our own code and assets plus the components listed here.
Third-party components keep their own licenses. This file lists them, but the
license texts shipped with each component are the authoritative source.

## Fonts (bundled in the mod)

| Font | Author / copyright | License | Source |
|---|---|---|---|
| Inter | Copyright (c) 2016 The Inter Project Authors | SIL Open Font License 1.1 | https://github.com/rsms/inter |
| JetBrains Mono | Copyright 2020 The JetBrains Mono Project Authors | SIL Open Font License 1.1 | https://github.com/JetBrains/JetBrainsMono |
| Poppins | Copyright 2020 The Poppins Project Authors | SIL Open Font License 1.1 | https://github.com/itfoundry/Poppins |

The full license text for each font is included in the mod under
`licenses/fonts/` (`inter-ofl.txt`, `jetbrains_mono-ofl.txt`, `poppins-ofl.txt`).
The fonts are not sold on their own and are not renamed. If a font is modified,
the Reserved Font Name rules of its license apply.

## Sounds and music (bundled in the mod)

All sound effects and music loops (`click_*.ogg`, `music_*_loop.ogg`) were
generated synthetically with a Python script for this project. They contain no
third-party samples, recordings or music. They are part of Käse Client and covered
by the project license.

## Graphics (bundled in the mod)

The logo (cheese symbol), the mod icon, the cheese sun texture, the cosmetic
textures and the preview image were created for this project.

## Libraries and tools (NOT bundled unless stated)

| Component | Role | License |
|---|---|---|
| Fabric Loader | required at runtime, installed by the user | Apache License 2.0 |
| Fabric API | required at runtime, installed by the user | Apache License 2.0 |
| Fabric Loom | build tool only, not part of the jar | MIT License |
| SpongePowered Mixin | provided by Fabric Loader at runtime | MIT License |
| JUnit 5 | tests only, not part of the jar | Eclipse Public License 2.0 |
| Gson | provided by Minecraft at runtime | Apache License 2.0 |

Licenses are given to the best of our knowledge. Check the current license of
each project before a release and update this table if a dependency changes.

## Minecraft

Käse Client is a mod for Minecraft: Java Edition. It does not contain
Minecraft code or assets. Minecraft is a trademark of Mojang Studios / Microsoft.
This project is not an official Minecraft product and is not approved by or
associated with Mojang or Microsoft.

## External services and helper scripts

Käse Client does not send personal data to any service.
- Media control (Windows only): the file `kaese_client/media_session.ps1` reads
  the Windows media session (the same one the Windows volume popup shows) and
  sends play / next / previous commands to it. It runs locally, only talks to
  Windows and to the client, and sends nothing over the network.
- Features that open links (for example the NameMC link) only open the page in
  your browser.

## Report a problem

If you think a component is missing or wrongly credited, please open an issue
or contact us: [YOUR DISCORD LINK / CONTACT].
