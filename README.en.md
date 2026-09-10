# 📦 Shopi — Impossible Deliveries

> A 2D vertical arcade platformer where Shopi, a delivery worker carrying a package, must do his job while dealing with absurdly troublesome customers.

🇧🇷 [Português](README.md) · 🇺🇸 **English** · 🇪🇸 [Español](README.es.md)

[![Play](https://img.shields.io/badge/🎮-Play%20now-orange)](https://shopi-climb-dash.base44.app/)
[![Status](https://img.shields.io/badge/status-6%20playable%20levels-brightgreen)](#current-status)
[![Built with](https://img.shields.io/badge/built%20with-Base44-blue)](#development)

## 🎮 Play now

[**Open Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

The current game runs in a web browser on desktop and mobile. All six campaign levels are playable and have been tested through the end.

## 🧾 About

**Shopi — Impossible Deliveries** is an independent game project developed incrementally with Base44 and documented on GitHub.

The game combines vertical platforming, ladders, obstacles, score chasing, campaign progression and situational comedy.

Instead of traditional villains, Shopi faces **troublesome customers** who turn ordinary deliveries into absurd gameplay challenges.

> **Shopi isn't trying to save the world. He just wants to finish the delivery.**

## 👥 Characters

### 📦 Shopi
The protagonist and delivery worker. He is determined, charismatic and slightly clumsy. During the levels, he carries the package he is supposed to deliver.

### 🚚 Etvaldo
Shopi's truck assistant and recurring partner. Etvaldo is part of the ongoing story and frequently finds himself in ridiculous situations.

### 😡 Customers / Bosses
The current campaign features six troublesome customers:

- **Tabacudo** — complains about everything.
- **Cleovasdo** — wants to return the delivery.
- **Osvaldêncio** — blocks access routes.
- **Jocelvânio** — is never at the stated address.
- **Ubiratânio** — ordered something absurd.
- **Edivaldir** — wants to exchange the delivery.

## 🗺️ Campaign

All six current levels are playable:

| Level | Location | Customer | Problem |
|---|---|---|---|
| 1 | Building | Tabacudo | Complains about everything |
| 2 | House | Cleovasdo | Wants to return the delivery |
| 3 | Condominium | Osvaldêncio | Blocks routes |
| 4 | Shopping center | Jocelvânio | Is never at the stated address |
| 5 | Shopping mall | Ubiratânio | Ordered something absurd |
| 6 | Distribution center | Edivaldir | Wants to exchange the delivery |

The full campaign has been tested by the author through the completion of Level 6.

## 🎮 Current gameplay

The game includes:

- 6 playable levels;
- 3 difficulty levels;
- platforms and ladders;
- jumping;
- lives;
- checkpoints;
- scoring;
- campaign progression;
- customer bosses;
- desktop keyboard controls;
- mobile touch controls.

### Difficulty

🟢 **Calm Delivery** — “Just deliver the package.” — ×1

🟡 **Complicated Delivery** — “Are you sure this is the right address?” — ×1.5

🔴 **Impossible Delivery** — “Did you call the manager?” — ×2

On Level 1, Calm Delivery has no objects falling from above. Higher difficulties increase pressure, quantity, speed or behavior of obstacles according to the level.

## 📱 Controls

### Desktop

- ← / → — move
- ↑ / ↓ — climb and descend ladders
- Space — jump

### Mobile

The current version includes touch controls for movement and jumping.

## 🏆 Scoreboards and leaderboard

The game already has a leaderboard and is evolving toward two scoring views:

- **Per-level scoreboard:** best recorded score for each of the six levels, associated with the player and selected difficulty.
- **Overall scoreboard:** sum of the player's best scores across the six levels.

The new system must preserve existing ranking data and keep the higher per-level record when a new attempt scores lower.

## 👥 Visitor counter

The global visitor counter remains planned. It should persist across sessions, stay separate from the player ranking and not interfere with gameplay.

## 🎯 Collectibles

Collectibles remain a planned future feature rather than a confirmed current feature. The proposal is two items per level, revealed through exploration and jumping, with score bonuses.

## 🎯 Game identity

Shopi's identity is built around:

- unusual characters;
- unexpected names;
- everyday situations turned into comedy;
- customers as bosses;
- delivery problems transformed into gameplay challenges;
- Shopi and Etvaldo as a recurring duo.

Classic arcade platformers are a genre reference only. The project must maintain its own characters, art direction, level design and audiovisual identity.

## 🛠️ Development

Base44 is the main prototyping and game-evolution tool.

Current workflow:

**Idea → Prompt → Base44 → Test → Adjust → Document in GitHub**

Changes should be incremental so each version can be tested before the next one is introduced.

## 📁 Documentation

- [Concept](docs/01_conceito.md)
- [Characters](docs/02_personagens.md)
- [Levels and campaign](docs/03_fases.md)
- [Gameplay](docs/04_gameplay.md)
- [Customers / Bosses](docs/05_clientes_bosses.md)
- [Scoreboards and leaderboard](docs/06_ranking.md)
- [Metrics](docs/07_metricas.md)
- [Base44 and development process](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)
- [Change history](CHANGELOG.md)
- [MVP prompt](prompts/01_mvp.md)
- [Touch controls prompt](prompts/02_controles_touch.md)
- [Leaderboard prompt](prompts/03_ranking.md)
- [Visitor counter prompt](prompts/04_contador_visitantes.md)
- [Level 2 prompt](prompts/05_fase_2_casa.md)
- [Difficulty prompt](prompts/06_dificuldade.md)
- [Per-level and overall scoreboard prompt](prompts/08_placar_fases_geral.md)

## 📊 Current status

**Development status:** 6-level playable campaign.

**Implemented and tested:** 6 levels, 3 difficulty levels, Shopi, Etvaldo, six customer bosses, platforms, ladders, jumping, lives, checkpoints, scoring, campaign progression, leaderboard and desktop/mobile controls.

**Next:** validate the per-level and overall scoreboard implementation, then return to collectibles, gameplay polish and other roadmap improvements.

## 👨‍💻 Author

**Filipe G Morais**

Independent game project exploring game design, technology, visual design and incremental development with AI/no-code tools.
