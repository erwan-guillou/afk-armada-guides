# Mining — Overview Guide

---

## 1. Resources

Mining is a gathering system that allows players to harvest three types of resources, each requiring dedicated equipment and specific skills.

### Resource types

| Type | Access requirement | Description |
|------|:-----------------:|-------------|
| **Ore** ⛏️ | Mining ≥ L1 | Solid minerals, accessible from the start |
| **Ice** 🧊 | Ice Harvesting ≥ L1 | Ice, unlocked from Mining L15 |
| **Gas** 💨 | Gas Harvesting ≥ L1 | Gas, unlocked from Mining L15 |

### Minerals — Ore

| Rarity | Mineral | Mining required | Value |
|--------|---------|:---------------:|:-----:|
| Common | Ferrite | L0 | 5 cr/u |
| Common | Copite | L5 | 8 cr/u |
| Uncommon | Luminite | L10 | 15 cr/u |
| Uncommon | Crystite | L15 | 25 cr/u |
| Uncommon | Titanite | L20 | 40 cr/u |
| Rare | Cobaltine | L25 | 60 cr/u |
| Rare | Iridite | L30 | 100 cr/u |
| Very Rare | Voidstone | L40 | 200 cr/u |
| Legendary | Starium | L50 | 500 cr/u |
| Mythic | Unicornium | L50 | 1,000 cr/u |

### Minerals — Ice

| Rarity | Mineral | Mining required | Value |
|--------|---------|:---------------:|:-----:|
| Common | Clear Ice | L15 | 12 cr/u |
| Uncommon | Glacial Mass | L20 | 20 cr/u |
| Rare | Blue Ice | L30 | 45 cr/u |
| Very Rare | Dark Glitter | L40 | 100 cr/u |

### Minerals — Gas

| Rarity | Mineral | Mining required | Value |
|--------|---------|:---------------:|:-----:|
| Common | Fullerite Gas | L15 | 10 cr/u |
| Uncommon | Cytoplasm | L20 | 22 cr/u |
| Rare | Mykocerosin | L30 | 55 cr/u |
| Very Rare | Neurotoxin Cloud | L45 | 150 cr/u |

---

## 2. Belts

Each belt has a fixed resource type, a minimum Mining level requirement, and a base yield multiplier. Some advanced belts carry the risk of encountering hostile NPCs.

### Ore

| Belt | Type | Mining | Multiplier | Accessible minerals |
|------|------|:------:|:----------:|---------------------|
| Rookie Fields | Common | L0 | ×1.0 | Ferrite |
| Frontier Belt | Common | L5 | ×1.1 | Copite, Luminite |
| Crystal Caverns | Rich | L15 | ×1.2 | Crystite |
| Titanium Ridge | Rich | L20 | ×1.3 | Titanite, Cobaltine |
| Deep Core Sector | Deep Space | L30 | ×1.5 | Iridite |
| Void Rift Alpha | Void Rift | L40 | ×2.0 | Voidstone ⚠️ |
| Starium Nebula | Nebula | L50 | ×2.5 | Starium, Unicornium ⚠️ |

### Ice

| Belt | Type | Mining | Multiplier | Accessible minerals |
|------|------|:------:|:----------:|---------------------|
| Frozen Expanse | Common | L15 | ×1.0 | Clear Ice |
| Permafrost Cluster | Rich | L25 | ×1.3 | Glacial Mass |
| Dark Ice Nebula | Nebula | L40 | ×1.8 | Dark Glitter ⚠️ |

### Gas

| Belt | Type | Mining | Multiplier | Accessible minerals |
|------|------|:------:|:----------:|---------------------|
| Fullerite Pocket | Common | L15 | ×0.9 | Fullerite Gas |
| Organic Nebula | Rich | L25 | ×1.2 | Cytoplasm |
| Toxic Maelstrom | Void Rift | L45 | ×1.6 | Neurotoxin Cloud, Mykocerosin ⚠️ |

> ⚠️ **Void Rift** and **Nebula** type belts are located in deep space and feature hunter NPCs. Each mining session in these zones increases the ship's sensor signature, making it progressively easier to detect.

### Belt types and their characteristics

| Type | Color | Risk | Typical multiplier |
|------|-------|:----:|:-----------------:|
| Common | Cyan | None | ×0.9 – ×1.1 |
| Rich | Green | None | ×1.2 – ×1.3 |
| Deep Space | Blue | Moderate | ×1.5 |
| Void Rift | Purple | High | ×1.6 – ×2.0 |
| Nebula | Yellow | High | ×1.8 – ×2.5 |

---

## 3. Ships

Five main families of ships are involved in mining, each with a distinct role.

### Corvette
Starting ship provided for free. Very limited capabilities, with no mining multiplier. Allows players to learn the basics but quickly becomes a bottleneck to progression.

### Mining Ship
First industrial ships dedicated to ore mining. Good balance between multiplier, cargo, and speed. The natural step after the corvette before gaining access to barges.

### Barge
Heavy ore ships. High multipliers and large cargo capacity, at the cost of reduced speed. Represent the main progression path for ore miners, from the Mining Barge up to the endgame Titan Drill.

### Gas Mining Ship / Ice Mining Ship
Ships specialized for gas and ice. They have a dedicated multiplier for their target resource, significantly higher than their generic multiplier. Essential for optimizing yield in their respective specialization.

### Hauler
Pure support ship. Does not mine. Used for transporting large volumes and fleet command via Mining Links. Its massive cargo hold makes it the cornerstone of organized fleet operations.

---

## 4. Modules

Modules are installed in the ship's high, mid, or low slots and act on different dimensions of yield.

### High Slot — Extraction modules

These are the modules that directly produce yield. Each type is optimized for one resource and penalized to 20% of its value outside that resource.

| Category | Target resource | Role |
|----------|:--------------:|------|
| **Mining Laser / Strip Miner** | Ore | Solid mineral extraction |
| **Gas Siphon** | Gas | Gas extraction |
| **Ice Harvester** | Ice | Ice extraction |

### Mid Slot — Amplification and support

These modules do not extract directly but improve overall session efficiency.

| Category | Role |
|----------|------|
| **Survey Scanner** | Increases the survey multiplier, which amplifies all yield |
| **Mining Computer** | Adds a global % bonus to all yield (ore, gas and ice) |
| **Cargo Coordinator** | Reduces unload time in auto-cycle (only the best module counts) |
| **Mining Link** | In fleet, increases the yield of all allied members (reserved for command ships) |
| **Mining Foreman Link** | Increases the yield of deployed mining drones |

### Low Slot — Fitting optimization

These modules have no direct effect on raw yield but allow for overall configuration optimization.

| Category | Role |
|----------|------|
| **Mining Yield Amplifier** | Additional global % bonus on yield (stackable with Mining Computer) |
| **Cargo Expander** | Increases cargo capacity, reducing the frequency of unloads |
| **Reaction Drive Injector / Mass-Reduced Frame** | Increases ship speed, reducing unload time in auto-cycle |
| **Co-Processor** | Increases CPU capacity, allowing more or more powerful modules to be fitted |
| **Reactor Control Unit** | Increases Power Grid capacity, same purpose as the Co-Processor |

---

## 5. Mining Drones

Mining drones add to the ship's yield without occupying a slot. They operate in parallel with extraction modules. The number of deployable drones depends on the **Mining Drone Operation** skill (1 slot per level, max 10) and the ship's drone bay capacity.

Drone yield is amplified by the **Drone Mining Yield** skill (+2% per level) and **Mining Foreman Link** modules.

---

## 6. Mining Modes

### 6.1 Standard Belt (manual session)

The player selects a belt, a fixed duration (15 min / 30 min / 1h / 2h), and starts the cycle. At the end of the chosen duration, the session ends and resources are available for collection. This is the simplest mode, with no setup constraints.

Yield is calculated once at launch using the full formula (ship × modules × skills × belt multipliers) and applied for the entire duration. If the cargo fills before the chosen duration ends, extraction automatically stops at the cap.

### 6.2 Belt with Auto-Cycle (Until Full)

By selecting the **"Until Full"** duration, the player activates auto-cycle mode. The session is calculated to fill exactly the free cargo space, then the ship automatically returns to the station, unloads, and resumes mining — without any player intervention.

This mode requires **Mining Automation L10** and is the most effective in terms of actual hourly yield as it eliminates downtime. Its performance depends on the ratio between mining time and unload time: the larger the cargo and/or the faster the unloading, the better the hourly yield.

The player can set a maximum number of cycles (1 to 100) or leave the session running indefinitely.

**Key factors in auto-cycle:**
- Effective cargo → determines the amount harvested per cycle
- Ship speed → determines unload time
- Cargo Coordinator → directly reduces unload time

### 6.3 Deep Space

Deep Space, Void Rift, and Nebula type belts are located in unsecured zones where hunter NPCs patrol. Each mining session in these zones increases the ship's **sensor signature** — the higher it is, the more detectable the ship becomes and the more exposed it is to attacks.

The **Signature Masking** skill slows the growth of this signature. In the event of an attack, the ship can flee but loses part of its cargo (**50% by default**, reduced by the **Emergency Warp Efficiency** skill).

Deep space offers the highest yield multipliers in the game (×1.5 to ×2.5) and provides access to endgame minerals (Voidstone, Starium, Unicornium, Neurotoxin Cloud). The trade-off is permanent risk and the need to manage signature between each session.

### 6.4 Clan Operations

Clan mining provides two additional layers of bonuses.

**Passive clan bonuses:** the clan can invest in collective skills that increase mining yield, drone yield, the survey bonus, and cargo capacity for all its members. These bonuses apply automatically to each individual session. They are amplified by the clan leader's **Leadership** skill.

**Territory bonus:** if the clan controls a territory, an additional mining yield bonus applies to all members mining in the controlled zone.

**Coordinated operations:** Coordinated operations can be launched by a clan member. They are carried out by multiple players (with conditions on the number of members involved and a minimum mining level). These operations can additionally yield a special resource, the `nexium shard`, which can only be found here and is used in the construction of space stations. During clan operations, a Hauler ship equipped with **Mining Links** can increase the yield of all allied fleet members without mining itself. This is a dedicated support role that requires the **Mining Foreman** skill and command ships to be fully effective.

Void Rift and Nebula endgame belts are designed to be mined in groups — the presence of hunter NPCs makes solo mining there particularly risky (data sourced from in-game pages — is this actually the case?).