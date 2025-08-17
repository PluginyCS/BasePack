<div align="center">
 <img align="center" src="https://user-images.githubusercontent.com/5860435/111066129-040e5e00-84f0-11eb-9e1f-7a7e8611da2b.png" alt="ReHLDS"/>

## BasePack — Stable CS 1.6 base package

[![Releases](https://img.shields.io/github/v/release/PluginyCS/BasePack)](https://github.com/PluginyCS/BasePack/releases/latest)
[![Discord](https://img.shields.io/discord/1016101167404695653?label=discord)](https://dc.pluginycs.pl)
[![Web](https://img.shields.io/badge/web-pluginycs.pl-brightgreen)](https://pluginycs.pl)

Stable base package for Counter-Strike 1.6 servers containing ReHLDS, ReGameDLL, ReAPI, Rechecker and other commonly used modules.
This package is intended for Linux-based servers.

<p align="center">
  <a href="#installation">Installation</a> ·
  <a href="#modules">Modules</a> ·
  <a href="#downloads">Downloads</a> ·
  <a href="#optional">Optional</a> ·
  <a href="#descriptions">Descriptions</a> ·
  <a href="#credits">Credits</a>
</p>

</div>

---

## Quick start

1. Download the latest release: https://github.com/PluginyCS/BasePack/releases/latest
2. Upload the package contents to your server (replace existing files if you know what you are doing).
3. Configure `reunion.cfg` (see note below), then restart the server.

> **Note:** You should set a 32-character SteamIdHashSalt in `reunion.cfg` (recommended hex string).

<details>
<summary>Example: SteamIdHashSalt</summary>

Add the following line to `reunion.cfg`:

```ini
SteamIdHashSalt = 9f3a2b7c1d4e5f6081a2b3c4d5e6f701
```

Save and restart the server. The warning about a missing or too-short SteamIdHashSalt should disappear.
</details>

## Modules

| Main                                                                                | Author / Source        | Version       |
|:------------------------------------------------------------------------------------|:-----------------------|:--------------:|
| 🔧 [AMX Mod X](https://www.amxmodx.org/amxxdrop/1.10/)                              | AMXX Dev Team          | 1.10.0.5468    |
| 💣 [Metamod-r](https://github.com/rehlds/Metamod-R)                                 | ReHLDS                 | 1.3.0.149      |
| 📈 [ReHLDS](https://github.com/rehlds/ReHLDS)                                       | ReHLDS                 | 3.14.0.857     |
| ⚙️ [ReAPI](https://github.com/rehlds/ReAPI)                                         | ReHLDS                 | 5.26.0.338     |
| 💡 [ReGameDLL](https://github.com/rehlds/ReGameDLL_CS)                              | ReHLDS                 | 5.28.0.756     |
| 🔐 [Reunion](https://github.com/rehlds/ReUnion)                                     | ReHLDS                 | 0.2.0.25       |
| 🔊 [ReVoice Plus](https://github.com/Garey27/revoice-plus)                          | Garey27                | 2.1.0          |

## Optional

| Optional                                                                            | Author / Source        | Version       |
|:------------------------------------------------------------------------------------|:-----------------------|:--------------:|
| ⚔️ [Rechecker](https://github.com/rehlds/rechecker)                                  | ReHLDS                 | 2.7            |
| 🔍 [ReAuthCheck](https://dev-cs.ru/resources/63/download)                            | Adidasman              | 0.1.6          |
| 📛 [WHBlocker](https://dev-cs.ru/resources/76/download)                              | s1lentq                | 1.5.697        |
| 💮 [ReSemiclip](https://github.com/rehlds/resemiclip)                               | ReHLDS                 | 2.4.3          |
| 👤 [Hitbox Fixer](https://github.com/Garey27/hitbox_fixer/releases)                 | Garey27                | 1.1.4          |

## Downloads

- Official releases: https://github.com/PluginyCS/BasePack/releases/latest
- Shop & extras: https://pluginycs.pl

## Descriptions

Please refer to the linked project pages in the Modules table for details about each module.

## Installation

1. Download the latest release archive and extract it locally.
2. Upload the extracted files to your game server (usually the game folder containing `cstrike/` and `valve/`).
3. Ensure `reunion.cfg` contains a valid `SteamIdHashSalt` (see Quick start section).

Optional: enable any optional modules by adding them to `cstrike/addons/metamod/plugins.ini`.

## Credits

- Arkshine
- Adidasman
- dreamstalker
- s1lent
- PRoSToTeM@
- theAsmodai
- Garey27
- ReHLDS Team
