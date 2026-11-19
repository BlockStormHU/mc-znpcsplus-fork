<div align="center">

# 👤 ZNPCsPlus

**Packet-based NPCs for Spigot, Paper and Folia servers.**

![Minecraft 1.8 - 26.2](https://img.shields.io/badge/Minecraft-1.8%20%E2%80%93%2026.2-62b47a)
![Spigot | Paper | Folia](https://img.shields.io/badge/server-Spigot%20%7C%20Paper%20%7C%20Folia-0e7490)
![Java 8+](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk&logoColor=white)
[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)

> BlockStorm's fork of [Pyrbu/ZNPCsPlus](https://github.com/Pyrbu/ZNPCsPlus).

</div>

---

ZNPCsPlus lets server admins place fake entities (players, villagers, zombies and most other mob types) that players
can click to run commands, get messages or switch servers on a BungeeCord-style network. Everything is sent as
packets, so the NPCs are not real entities on the server.

This fork has no code changes. It mirrors upstream and is kept so BlockStorm can patch the plugin if it ever needs to.

## ✨ At a glance

- 👥 Player NPCs with static, per-viewer, mirrored, URL or file skins, plus most other entity types
- 🖱️ Click actions: console command, player command, player chat, message, server switch
- 🪧 Holograms above NPCs, text or item lines, with optional refresh for placeholders
- 🔒 Per-NPC visibility permission, look-at-player, knockback and many entity properties
- 💾 YAML, SQLite or MySQL storage, with import from ZNPCs, Citizens and FancyNpcs
- 🧩 Optional PlaceholderAPI support and a Java API for other plugins

## 📖 Documentation

Full documentation is in the [wiki](https://github.com/BlockStormHU/mc-znpcsplus-fork/wiki):

- [Installation](https://github.com/BlockStormHU/mc-znpcsplus-fork/wiki/Installation): requirements, downloads, building from source
- [Commands and Permissions](https://github.com/BlockStormHU/mc-znpcsplus-fork/wiki/Commands-and-Permissions): every `/npc` command and permission
- [Configuration](https://github.com/BlockStormHU/mc-znpcsplus-fork/wiki/Configuration): `config.yaml`, storage and data import
- [Original README](https://github.com/BlockStormHU/mc-znpcsplus-fork/wiki/Original-README): upstream's README, unchanged

Upstream also has its own [wiki](https://github.com/Pyrbu/ZNPCsPlus/wiki) with the full list of NPC types and properties.

---

<div align="center">
<sub>Created by <b>Pyr</b> and <b>D3v1s0m</b> (<a href="https://github.com/Pyrbu/ZNPCsPlus">Pyrbu/ZNPCsPlus</a>) · Maintained in this fork by <b>BlockStorm</b> · Licensed under the <a href="LICENSE">GNU GPL v3.0</a></sub>
</div>
