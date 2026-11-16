<p align="center">
  <img src="github_assets/title.png" width="450">
</p>

<p align="center">
  A small addon for <b>Create</b> that adds new tools and machines, plus some extras for <b>Sophisticated Backpacks</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.21.1-62B47A">
  <img src="https://img.shields.io/badge/Loader-NeoForge-E68A3C">
  <img src="https://img.shields.io/badge/Create-6.0.10-B48C5A">
  <img src="https://img.shields.io/badge/Version-1.0.0-4A90D9">
</p>

---

## Requirements

| Mod | Required? |
|---|---|
| [NeoForge](https://neoforged.net/) 21.1+ for Minecraft 1.21.1 | ✅ Required |
| [Create](https://modrinth.com/mod/create) 6.0.10+ | ✅ Required |
| [Sophisticated Backpacks](https://modrinth.com/mod/sophisticated-backpacks) + Sophisticated Core | ➕ Optional (needed for the Pressing Upgrade) |

---

## Features

### 🔋 Rotational Battery
Store rotational force and use it later.

- **Charging:** Without redstone power, the battery takes rotation from the shaft on **top** and charges itself. The faster the shaft spins, the faster it charges.
- **Discharging:** Give it a **redstone signal** and it turns into a generator. It outputs **32 RPM** through the shaft on the **bottom** until it is empty.
- Holds up to **100,000** charge, with 80 % efficiency.
- Goggles show the current charge.
- Has a **Ponder** scene (hold `W` while hovering the item).

**Recipe**
```
 [Vertical Gearbox]
 [Andesite Casing ]
 [Copper Backtank ]
```

### ⛏️ Multi-Tool
Pickaxe, axe, shovel and Create wrench in one diamond tool.

- Hold **Tab** to open the radial menu, move your mouse to a mode and let go to switch.
- Modes: **Pickaxe**, **Axe**, **Shovel**, **Wrench**.
- The model changes with the selected mode.

**Recipe (shapeless)**
Diamond Pickaxe + Diamond Axe + Diamond Shovel + Wrench

### 🎒 Pressing Upgrade *(Sophisticated Backpacks)*
An upgrade for your backpack that works like a Mechanical Press.

- Adds a tab to the backpack with an input slot and an output slot.
- Presses items with all of Create's pressing recipes (e.g. ingots into sheets).
- Only loaded when Sophisticated Backpacks is installed.

**Recipe**
```
               [Mechanical Press]
[Rot. Battery] [Upgrade Base    ] [Depot]
               [Vertical Gearbox]
```

---

## Installation

1. Install NeoForge for Minecraft 1.21.1.
2. Put **Create** (and optionally **Sophisticated Backpacks** + **Sophisticated Core**) into your `mods` folder.
3. Put the `create_tools_and_stuff` jar into your `mods` folder.
4. Start the game.

---

## More coming soon

This mod is still growing. More tools and machines will be added later.
