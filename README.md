# Box Fight — Unreal Engine / UEFN Multiplayer Project

A production multiplayer experience developed with **Unreal Editor for Fortnite (UEFN)** and **Verse**, built around fast-paced competitive multiplayer gameplay and reusable real-time game systems.
* No Ai assisted code was used in development.
The project became one of my most successful published multiplayer experiences, reaching:

* **35,000+ peak concurrent players**
* Featured by a major YouTube creator
* Released publicly through Fortnite / UEFN
* Built as part of my larger portfolio of shipped Unreal Engine multiplayer projects

🎮 [View Published Game](https://fortnite.gg/island/8760-5124-3263)
🎥 [YouTube Feature](https://www.youtube.com/watch?v=JLLwoqYCG6A&t=47s)
🕹️ [More Published Projects](https://fortnite.gg/creator/scarj)

Collab Maps With Other Studios -
Caseoh Escape Map-
https://youtu.be/K9qFuu0uIM8?is=6FG7uIvAQ01HBtbR
---

## Project Overview

This project was built as a live multiplayer experience using **Unreal Engine technology through UEFN**, with custom gameplay logic implemented in Verse.

The project required coordinating real-time multiplayer systems including player state, teams, classes, loadouts, teleportation, timers, UI, gameplay devices, arena state, and event-driven interactions.

Rather than relying entirely on editor configuration, custom Verse systems were used to control gameplay behavior and connect Unreal/UEFN devices into reusable systems.

---

## Multiplayer Systems

### Player State

The gameplay controller maintains player-specific state using Verse data structures.

Examples include tracking:

* Active players
* Player status
* Team assignments
* UI state
* Gameplay state
* Spectating state

This allows gameplay events to affect individual players without relying entirely on global game state.

### Team & Class Management

Custom logic integrates with UEFN's team and class systems to dynamically configure players during gameplay.

This includes:

* Team selection
* Class assignment
* Player-specific loadouts
* State transitions
* Match initialization

### Inventory & Loadouts

The project integrates item-granting and inventory systems to configure player equipment based on gameplay state.

Gameplay logic can dynamically grant or remove items rather than relying on a completely static loadout configuration.

### Event-Driven Gameplay

The project uses an event-driven architecture to respond to player actions and game events.

Verse systems coordinate devices such as:

* Item granters
* Team and class selectors
* Teleporters
* Timers
* Barriers
* Damage modifiers
* Movement modifiers
* HUD systems
* Audio devices
* Cinematic sequences
* Mutator zones
* Visual effects
* Gameplay triggers

---

## Technical Concepts

This project demonstrates experience with:

* Multiplayer programming
* Event-driven architecture
* Player state management
* Real-time game logic
* Maps and arrays
* Object-oriented programming concepts
* Gameplay event subscriptions
* Team and class systems
* Device abstraction
* UI integration
* Asynchronous gameplay logic
* Debugging multiplayer systems
* Production game development

---

## Technologies

**Project Technologies**

* Unreal Engine / UEFN
* Verse
* Unreal gameplay systems
* Fortnite Creative devices
* UEFN UI and gameplay APIs

### C++ / Unreal Engine Background

This repository contains the **Verse gameplay source** for the UEFN project.

My broader Unreal Engine development experience includes **C++, Verse, and Blueprints**, which I have used across more than **15 shipped multiplayer products**.

Those products have collectively reached **15M+ player sessions**, with five individual projects exceeding one million sessions and projects reaching more than **35,000 concurrent users**.

---

## Production Scale

| Metric                  |                 Result |
| ----------------------- | ---------------------: |
| Peak Concurrent Players |                35,000+ |
| Environment             | Production multiplayer |
| Engine                  |   Unreal Engine / UEFN |
| Gameplay Programming    |                  Verse |
| Published               |               Fortnite |

The scale of the project required systems that could operate reliably with large numbers of active players while handling state changes and multiplayer events in real time.

---

## My Contributions

My work included:

* Multiplayer gameplay programming
* Verse development
* Gameplay systems architecture
* Player state management
* Team and class logic
* Inventory and loadout systems
* UI integration
* Event-driven game logic
* Device integration
* Multiplayer debugging
* UEFN implementation
* Testing and live iteration

This project was developed as part of my work building and maintaining commercial multiplayer experiences within the Unreal Engine ecosystem.

---

## Source Code

A selected portion of the project's Verse gameplay implementation is available in this repository:

[`Box.verse`](./Box.verse)

The complete published experience also includes Unreal/UEFN level configuration, assets, device configuration, UI, and other editor-side content that cannot be represented by the Verse source file alone.

