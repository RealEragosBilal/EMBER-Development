<div align="center">

# 🔥 EMBER

### A custom Call of Duty: Black Ops III client

**An independent community project for Multiplayer & Zombies**

[![Status](https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-8b5cf6?style=for-the-badge)](https://github.com/RealEragosBilal/EMBER-Development)
[![Client](https://img.shields.io/badge/CLIENT-NOT%20RELEASED-555?style=for-the-badge)](https://github.com/RealEragosBilal/EMBER-Development)
[![Roadmap](https://img.shields.io/badge/ROADMAP-PUBLIC-6d28d9?style=for-the-badge)](#development-roadmap)

**[Development roadmap](#development-roadmap) · [Progress updates](#progress-updates) · [About](#about-ember)**

</div>

---

> [!IMPORTANT]
> **EMBER is not available for download yet.** This repository is a public development tracker only. It does **not** contain the EMBER source code, game files, client binaries, or installers. Dates and release windows have not been announced.

## About EMBER

**EMBER** is an experimental Windows client project built around **Call of Duty: Black Ops III**, with a custom launcher, its own backend infrastructure, and a focus on the game's **Multiplayer** and **Zombies** modes.

Our goal is to create a cohesive EMBER experience with account services, an in-game server browser, and support for community-hosted servers.

The project is based on the open-source **[Ezz BOIII / boiii-free](https://github.com/Ezz-lol/boiii-free)** codebase. EMBER is an independent fork, and the original contributors remain credited for their work.

### Planned features

- Custom EMBER launcher and visual design
- EMBER Network accounts and HTTPS-backed services
- Multiplayer and Zombies
- In-game browser for community servers
- Dedicated server support
- An EMBER-specific update and release system

**Matchmaking is not part of the initial release plan.**

## Development roadmap

These checkboxes show **development progress**, not guarantees that a feature works in every environment. Work that exists in code but has not been validated end to end may remain unchecked.

### 🎨 Client & user interface
- [x] Rename the compiled executable to `ember_client.exe`
- [x] Build a customized EMBER launcher interface
- [x] Add EMBER-themed styling and an application icon
- [ ] Verify the launcher on a clean installation

### 🌐 EMBER Network
- [x] Set up an HTTPS backend and PostgreSQL database
- [x] Implement basic account registration, login, and session endpoints
- [x] Add initial EMBER Network client-side API code
- [ ] Validate authentication throughout the full game lifecycle
- [ ] Complete secure server registration, heartbeats, and session tickets
- [ ] Verify online services under real multiplayer use

### 🎮 Multiplayer
- [x] Compile an initial Windows x64 client build
- [ ] Start and validate an EMBER dedicated Multiplayer server
- [ ] Connect to a Multiplayer server from an EMBER client
- [ ] Integrate and validate the in-game EMBER server browser
- [ ] Complete multiplayer compatibility testing

### 🧟 Zombies
- [ ] Start and validate an EMBER dedicated Zombies server
- [ ] Join and play a Zombies session using EMBER
- [ ] Validate Zombies server browser listings
- [ ] Test official maps and supported custom content

### 🚀 Updates & release
- [ ] Implement GitHub-based EMBER update checks
- [ ] Authenticate update packages and verify file integrity
- [ ] Test safe installation, recovery, and rollback
- [ ] Publish installation instructions
- [ ] Release the first public EMBER build

## Progress updates

Development changes will be recorded here as milestones are completed. A checked item means that the specific work listed has been implemented or verified at the stated level; it does **not** imply that the entire feature group is production-ready.

| Date | Update |
| --- | --- |
| 2026-10-23 | Launched the public EMBER development tracker. |
| 2026-10-23 | Initial EMBER client modifications and launcher styling committed to the private development repository. |
| 2026-10-23 | Work ongoing on client stability, update infrastructure, and dedicated server bring-up. |

> [!NOTE]
> This checklist is maintained manually, so it may not reflect every local experiment or uncommitted change.

## Downloads & source code

**There are no public EMBER downloads at this time.**

- **EMBER client:** Not released
- **EMBER installer:** Not released
- **Public EMBER source:** Not published
- **Release date:** To be announced

The implementation is currently developed in a separate **private** repository. This public repository is intentionally documentation-only.

## Community & contributions

You can follow changes by clicking **Watch** on this repository. Suggestions and bug reports can be submitted through [Issues](https://github.com/RealEragosBilal/EMBER-Development/issues) when enabled.

Please do not submit credentials, access tokens, copyrighted game assets, or private user information.

## Credits, license & disclaimer

EMBER is an independent project derived from [Ezz BOIII / boiii-free](https://github.com/Ezz-lol/boiii-free). Credit belongs to the upstream BOIII contributors and their community. The private EMBER client source retains upstream license obligations, including the **GNU GPL v3.0** as applicable; distribution arrangements will be reviewed before a public build or source release.

EMBER is **not affiliated with or endorsed by Activision, Treyarch, Valve, or the BOIII maintainers**. Call of Duty and Black Ops III are trademarks of their respective owners. Users must obtain their game files through legitimate sources; this project does not distribute those files.

---

<div align="center">

**EMBER • In Development**

*Built for the community. Shared when ready.*

</div>
