# Bedrock Feature to Java

[![Modrinth](https://img.shields.io/badge/Modrinth-BedrockFeatureToJava-00AF5C?logo=modrinth)](https://modrinth.com/mod/bedrockfeaturetojava)
[![Fabric](https://img.shields.io/badge/Loader-Fabric-EFEFEF?logo=fabric)](https://fabricmc.net/)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1--1.21.11-5C5C5C?logo=minecraft)](https://minecraft.net)

**Bring Bedrock Edition mechanics into Minecraft Java (1.21.1 – 1.21.11, Fabric).** Lightweight, configurable, and designed for players who miss specific Bedrock behaviors – no attack cooldown, forgiving villagers, random strongholds, and auto-shield on sneak.

## ✨ Features

| Feature | Description |
|---------|-------------|
| **No attack cooldown** | Spam-click as fast as you like – every hit deals full damage. |
| **Villagers never overcharge** | Hitting a villager does **not** increase their trade prices. |
| **Random stronghold generation** | Strongholds spawn randomly (~30% chance per eligible chunk) – no more fixed rings. |
| **Auto‑shield on sneak** | Hold `Shift` and your shield raises automatically. No flickering, smooth behavior. |

⚙️ **Every feature can be toggled on/off** via config file or [Mod Menu](https://modrinth.com/mod/modmenu).

## ❌ Planned (not yet available)

- Axe damage = sword damage – 1 & axe cannot break shields
- 80% accuracy for skeletons and pillagers
- Piston‑movable containers (use [Movable Block Entities](https://modrinth.com/mod/movable-block-entities) as a companion)
- Lever not breaking when pushed by piston (Java limitation)

## 📦 Installation

1. Install **Fabric Loader** (0.19.2 or later)
2. Install **Fabric API** (0.116.4+ for 1.21.x)
3. Download this mod from [Modrinth](https://modrinth.com/mod/bedrockfeaturetojava)
4. Place the `.jar` file into your `mods` folder
5. Launch Minecraft

> **Optional**: Install [Mod Menu](https://modrinth.com/mod/modmenu) for an in‑game configuration screen.

## ⚙️ Configuration

### With Mod Menu
Click the mod icon in the mod list to open the configuration screen.

### Manually
Edit `.minecraft/config/bedrockfeaturetojava.json`:

```json
{
  "removeAttackCooldown": true,
  "preventVillagerPriceIncrease": true,
  "randomStronghold": true,
  "autoShieldWhenSneaking": true
}
Set any value to false to disable that feature.




#📋 Requirements
Dependency	Version
Minecraft	1.21.1 – 1.21.11
Fabric Loader	≥0.19.2
Fabric API	0.116.4+ for 1.21.x
Mod Menu	≥11.0.3 (optional, for config screen)

#📄 License
All Rights Reserved
© 2026 FrostPierce.
You may not redistribute, modify, or claim ownership without explicit permission. Personal use is allowed.

#💬 Feedback & Support
Report issues or suggest features on GitHub Issues

Contact via Modrinth

#Enjoy your Bedrock‑flavored Java experience! 🧱☕