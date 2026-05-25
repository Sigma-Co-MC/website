---
title: "Modding: Druids"
description: "Backstory and other stuff about the Druids mod"
pubDate: "May 25 2026"
heroImage: "https://cdn.modrinth.com/data/flHIknzE/images/c981bd32ae0690d78ffa27e8ec74e34247736451.png"
---

![title](https://raw.githubusercontent.com/NuttiesNuts/druids/refs/heads/1.21.1/title%20text.png)


[![Modrinth](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/modrinth_vector.svg)](https://modrinth.com/mod/druids)
[![CruseForge](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/curseforge_vector.svg)](https://www.curseforge.com/minecraft/mc-mods/druids)


This project adds RPG-style combat focused class, introducing the druid archetype (inspired by popular RPG games).

I was able to develop this mod using the powerfull data-driven [Spell Engine API](https://modrinth.com/mod/spell-engine). It's so god damn cool. 

Here are some stuff it is capable of:
- Spells can be assigned to any weapon (data driven with automatic weapon compatibility)
- Spells deal damage based on Spell Power entity attributes
- Spells defined in JSON format with hot-reloading and network synchronization
- Spell Container System with proxy mode, equipment slots, and dynamic spell resolution
- Universal pattern matching for tags, regex, and exact matches across all spell properties
- Programmatic spell generation with SpellBuilder and SpellGenerator for mod developers

Latest Druids update added a fully functional skill tree with many different spell passives and modifiers to choose from.


## Get started

To become a Druid, obtain Nature **Wands** and **Staves**, these come with your first spell.

**Runes** serve as ammunition for cast spells (much like arrows for bows). [More information about crafting runes.](https://modrinth.com/mod/runes)

![](https://cdn.modrinth.com/data/flHIknzE/images/b664ea151a27b885a435c72fb4f05585f0c3cb00.png)

## Spell Books

Become a Druid by creating the respective Spell Book, and unlocking all of its powerful spells!

To do it, find a Spell Binding Table in village [Gazebos](https://modrinth.com/mod/gazebos), or build your own (just don't forget bookshelves around the Spell Binding Table).

To use the spell books: equip them and hold a weapon!

![](https://cdn.modrinth.com/data/flHIknzE/images/8cf8f98ff68f03911f9f3f4152cb817016b1e0ff.png)

### Druidic Grimoire

Offers druid spells, to lock down and damage targets over time.

Best used with Nature Stave/Wands that provide the respective spell attribute.

![](https://cdn.modrinth.com/data/flHIknzE/images/b1d825edb8d5a73f19f119c061c3e865ecbce318.png)

## Explore the equipment

Explore new, craftable, druid equipment, with bonuses to boost spell damage.

2 armor sets, Nature Staves and Wands and Fatal Poison Potions.

Equipment bonuses are configurable in `config/druids/equipment.json`.

## New structure

Find a Druid Camp, where you can find magic equipment & artifacts!

![](https://cdn.modrinth.com/data/flHIknzE/images/f3e05680ecc13f5e43d3feba7bb0015a5ad566a3.png)

## Planned Features

- [Armory](https://modrinth.com/mod/armory-rpg-series) compat (new **EPIC** tier armor)
- Spell Expansion (more spell choices)