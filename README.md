<div align="center">

# 🔥 EMBER

### A multi-game Call of Duty client project

**An independent community project for Multiplayer & Zombies**

[![Status](https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-8b5cf6?style=for-the-badge)](https://github.com/RealEragosBilal/EMBER-Development)
[![Client](https://img.shields.io/badge/CLIENT-NOT%20RELEASED-555?style=for-the-badge)](https://github.com/RealEragosBilal/EMBER-Development)
[![Roadmap](https://img.shields.io/badge/ROADMAP-PUBLIC-6d28d9?style=for-the-badge)](#development-roadmap)

**[Development roadmap](#development-roadmap) · [Progress updates](#progress-updates) · [About](#about-ember)**

</div>

---

> [!IMPORTANT]
> **EMBER is not available for download yet.** This repository is a public development tracker only. It does **not** contain the private EMBER source code, game files, client binaries, or installers. Dates and release windows have not been announced.

## About EMBER

**EMBER** is an experimental Windows client ecosystem for multiple classic Call of Duty titles. Development currently focuses on **Call of Duty: Black Ops III**, with a custom launcher, separate backend infrastructure, and Multiplayer and Zombies integration. The other listed games are planned targets, not currently playable EMBER releases.

Our goal is to create a cohesive EMBER experience across supported titles, with account services, in-game server browsing, and community-hosted servers where technically feasible. Game modes vary by title.

The project is based on the open-source **[Ezz BOIII / boiii-free](https://github.com/Ezz-lol/boiii-free)** codebase. EMBER is an independent fork, and the original contributors remain credited for their work.

## Game support & progress

**Supported** here means *targeted for future EMBER support*, **not playable today**. No game has a public EMBER release yet. Progress is tracked by verifiable milestones rather than made-up percentages.

| Game | Development status | Client build | Online gameplay tested | Public release |
| --- | --- | --- | --- | --- |
| Call of Duty: World at War | Planned | Not started | No | No |
| Call of Duty: Black Ops | Planned | Not started | No | No |
| Call of Duty: Black Ops II | Planned | Not started | No | No |
| Call of Duty: Black Ops III | **In development** | **Local x64 launcher/client build tested** | Full MP/Zombies end-to-end not verified | No |
| Call of Duty: Modern Warfare 2 (2009) | Planned | Not started | No | No |
| Call of Duty: Modern Warfare 3 (2011) | Planned | Not started | No | No |
| Call of Duty: Advanced Warfare | Planned | Not started | No | No |
| Call of Duty: Infinite Warfare | Planned | Not started | No | No |

**Status key:** Planned = no verified EMBER implementation; In development = active EMBER code/build work; Tested = verified in-game operation; Released = downloadable public EMBER build. The release and tested milestones are still pending for all eight titles.

### Per-game checklists

<details>
<summary><strong>World at War (T4) · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer and Zombies connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Black Ops 1 (T5) · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer and Zombies connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Black Ops 2 (T6) · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer and Zombies connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Black Ops 3 (T7) · In development</strong></summary>

- [x] Create customized client project
- [x] Compile initial Windows x64 EMBER executable
- [x] Implement initial EMBER launcher styling
- [x] Add initial backend API integration code
- [x] Verify account login in the EMBER launcher against the production backend
- [x] Implement and test Friends search, outgoing requests, and request listing in the launcher
- [x] Integrate and authenticate the Friends and Black Market APIs in the production backend
- [x] Implement and locally test Common/Rare Drops and the Six Pack economy flow
- [ ] Test Friends request acceptance and presence between two real clients
- [ ] Verify friend-to-friend Zombies game joining end to end
- [ ] Test Multiplayer join and dedicated hosting end to end
- [ ] Test Zombies join and dedicated hosting end to end
- [ ] Validate the EMBER in-game server browser end to end
- [ ] Finish, build, and test the EMBER update pipeline
- [ ] Publish a public build

</details>

<details>
<summary><strong>Modern Warfare 2 (2009) · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Modern Warfare 3 (2011) · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Advanced Warfare · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

<details>
<summary><strong>Infinite Warfare · Planned</strong></summary>

- [ ] Establish game-specific client project
- [ ] Compile first EMBER client
- [ ] Integrate launcher/network services
- [ ] Test Multiplayer and Zombies connections
- [ ] Test dedicated hosting
- [ ] Publish a public build

</details>

### Planned features

- Custom EMBER launcher and visual design
- EMBER Network accounts and HTTPS-backed services
- Multiplayer and Zombies where available in the respective game
- In-game browser for community servers
- Dedicated server support
- An EMBER-specific update and release system

**Matchmaking is not part of the initial release plan.**

## Development roadmap

The following development roadmap describes **Black Ops III and shared EMBER infrastructure**, not verified progress in the other seven games.

These checkboxes show **development progress**, not guarantees that a feature works in every environment. Work that exists in code but has not been validated end to end may remain unchecked. Verified local and production API results do not imply public client availability.

### 🎨 Client & user interface
- [x] Rename the compiled executable to `ember_client.exe`
- [x] Build a customized EMBER launcher interface
- [x] Add EMBER-themed styling and an application icon
- [x] Test the launcher with a production account and live Friends requests
- [ ] Verify the launcher on a clean installation

### 🌐 EMBER Network
- [x] Set up an HTTPS backend and PostgreSQL database
- [x] Implement basic account registration, login, and session endpoints
- [x] Add initial EMBER Network client-side API code
- [x] Verify production account login and authenticated Friends/Economy responses
- [x] Add friend search, request/response, list, remove, presence, and join API endpoints
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
- [x] Bring up a BO3 Zombies dedicated server in the development environment
- [x] Join and play a Zombies session using EMBER
- [x] Validate Zombies server browser listings
- [ ] Test official maps and supported custom content

### 🛒 Black Market & social
- [x] Integrate the Black Market backend with persistent wallets and cosmetics inventory
- [x] Test authenticated Economy responses against production account data
- [x] Implement Common and Rare Supply Drop purchase APIs
- [x] Implement the Six Pack: six Common Drops for 45 Cryptokeys, limited to once per 24 hours per account
- [x] Save and restore unopened Drops; verify Six Pack purchase/opening in the normal client
- [x] Implement Friends search, requests, lists, and presence APIs
- [x] Display outgoing Friends requests in the actual launcher
- [x] Validate the Friends join API using a simulated Zombies server
- [ ] Verify real-user acceptance, online status, and game joining between two clients
- [ ] Complete additional production regression and multiplayer testing

### 🤖 Discord bot & community operations
- [x] Deploy the EMBER Discord worker as a persistent Windows scheduled task
- [x] Implement administrative `/cpoints` and `/cryptokeys` commands with backend integration
- [x] Implement automated Zombies server-status channel updates
- [x] Publish the October 28 development announcement in three Discord embeds
- [ ] Expand Discord administration with ticketing, moderation, configurable announcements, and community automation

### 🖥️ EMBER Control Center & web services
The **EMBER Control Center** is a proposed Windows administration application; it has **not been released or implemented as a complete product**.

- [ ] Build a role-aware administrative dashboard with system health and audit history
- [ ] Add player and account administration, support workflows, and secure password-reset handling
- [ ] Add Discord management, economy controls, and live game-server operations
- [ ] Add community events, rewards, bug reports, and suggestions management
- [ ] Develop public Zombies leaderboards, player statistics, records, and profiles
- [ ] Add Discord OAuth2 account linking and website sign-in with server-side permission enforcement

### 🚀 Updates & release
- [ ] Finish GitHub-based EMBER update checks (implementation draft exists; not built or tested)
- [ ] Authenticate update packages and verify file integrity
- [ ] Test safe installation, recovery, and rollback
- [ ] Publish installation instructions
- [ ] Release the first public EMBER build

## Progress updates

Development changes will be recorded here as milestones are completed. A checked item means that the specific work listed has been implemented or verified at the stated level; it does **not** imply that the entire feature group is production-ready.

| Date | Update |
| --- | --- |
| 2026-10-23 | Launched the public EMBER development tracker. |
| 2026-10-23 | Added eight planned game targets with separate milestone checklists; only Black Ops III has verified initial EMBER client development. |
| 2026-10-23 | Initial EMBER client modifications and launcher styling committed to the private development repository. |
| 2026-10-23 | Work ongoing on client stability, update infrastructure, and dedicated server bring-up. |
| 2026-10-28 | Deployed the integrated Black Market, Network, and Friends APIs to the production backend; verified authenticated account, Friends, Economy, and public server-list responses. |
| 2026-10-28 | Tested the real EMBER launcher login and outgoing friend requests; actual acceptance and joining between two players remain pending. |
| 2026-10-28 | Integrated and tested the Six Pack: six Common Drops for 45 Cryptokeys, once per 24 hours per account, with persisted unopened Drops. |
| 2026-10-28 | Began a GitHub Releases-based auto-updater with manifest, file integrity, staging, and rollback design. This is an **unbuilt and untested implementation draft**, not a released feature. |
| 2026-10-28 | Deployed and tested the EMBER Discord worker with administrative COD Points / Crypto Keys commands and automated Zombies server-status channel updates. |
| 2026-10-28 | Published a three-part Discord community update covering current development, future features, and the proposed Control Center. |
| 2026-10-28 | Expanded the public roadmap with Discord management, administrative tooling, a future Control Center, and planned Zombies leaderboards and Discord OAuth2 integration. These remain plans unless marked completed above. |

> [!NOTE]
> This checklist is maintained manually, so it may not reflect every local experiment or uncommitted change.

## Downloads

**There are no public EMBER downloads at this time.**

- **EMBER client:** Not released
- **EMBER installer:** Not released
- **Release date:** To be announced

**EMBER's source code will remain private during active development for security reasons. The plan is to publish the source code after the project has been officially shut down.** This repository serves as the public development tracker, not a source-code mirror.

## Community & contributions

You can follow changes by clicking **Watch** on this repository. Suggestions and bug reports can be submitted through [Issues](https://github.com/RealEragosBilal/EMBER-Development/issues) when enabled.

Please do not submit credentials, access tokens, copyrighted game assets, or private user information.

## Credits, license & disclaimer

EMBER is an independent project derived from [Ezz BOIII / boiii-free](https://github.com/Ezz-lol/boiii-free). Credit belongs to the upstream BOIII contributors and their community. EMBER's source repository is intended to remain private while the project is active, with source publication planned after shutdown. Any distribution of EMBER binaries must nevertheless comply with applicable upstream licenses, including **GNU GPL v3.0** obligations where applicable; these will be reviewed before a public client release.

EMBER is **not affiliated with or endorsed by Activision, Treyarch, Valve, or the BOIII maintainers**. Call of Duty and Black Ops III are trademarks of their respective owners. Users must obtain their game files through legitimate sources; this project does not distribute those files.

---

<div align="center">

**EMBER • In Development**

*Built for the community. Shared when ready.*

</div>
