---
layout: default
title: Home
nav_order: 1
---

### Overview
{: .no_toc .fs-9 }

This document makes up the <i>Starborn Trials Game Design Document</i> which is the game prototype design used to inform implementation strategies for the architecture of Peligro Labs' [AetherCore](https://github.com/peligrolabs/AetherCore) game framework. This design document is open source and can its GitHub repository can be accessed here: [Starborn Trials Design](https://github.com/peligrolabs/starborn-trials-design).
{: .fs-6 .fw-300 }

### Table of Contents
{: .no_toc .text-delta }

* TOC
{:toc }

---

### 1. Purpose of the Prototype

To begin construction of the AetherCore Game Framework, designed to power Quest for the Morningstar, Trinity Fighters, Cyber Surfers, and future titles by:
- Establishing core modular systems
- Testing plug-in integration (BeeHave, Dialogue)
- Proving architectural scalability for MMO-lite infrastructure
- Serving as an “Initiation Game” that captures mythos and mechanics

---

### 2. Genre & Core Loop

<b>Genre</b>: 2D top-down action RPG<br>
<b>Loop</b>: Explore → Fight → Speak → Grow → Traverse
- Unlock secrets of a single World-Server Seed Map
- Combat mythic beasts, uncover relics, dialogue with spirit-NPCs
- Receive temporary “Blessings of the Aether” that alter combat/play
- Reach the Ember Chamber, survive the Trial
