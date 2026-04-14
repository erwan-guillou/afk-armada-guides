
# Mining Items — Complete Reference 

> Ships and modules related to mining.
> Ships are classified by class, modules are classified by slot (high / mid / low) and then by resource type.

---

## 🚀 Ships

Each ship has a mining multiplier that amplifies overall yield. Dedicated gas and ice ships have a specialized multiplier for their target resource, higher than their generic multiplier — this is the one applied when mining the corresponding resource.

---

### Corvette

Starter ship, not purchasable. Provides minimal service but allows you to start mining immediately.

| Name            | Slots H/M/L | Cargo | mine× | Requirements | Price | Rarity |
| --------------- | :---------: | ----: | :---: | ------------ | ----: | ------ |
| Starter Shuttle |    2/1/1    |   100 |   —   | —            |  free | common |

---

### Mining Ship

First accessible industrial ships. Good balance between multiplier, cargo, and speed for getting started.

| Name         | Slots H/M/L | Cargo | Speed | mine× | Requirements                      |     Price | Rarity   |
| ------------ | :---------: | ----: | :---: | :---: | --------------------------------- | --------: | -------- |
| Prospector   |    3/2/2    |   500 |  120  |  ×1.5 | Mining L5 + Industrial Command L1 |  5,000 cr | uncommon |
| Mining Skiff |    4/3/3    | 1,000 |  120  |  ×2.0 | Mining L8 + Industrial Command L5 | 12,000 cr | uncommon |

---

### Barge

Heavy mining ships. High multipliers and large cargo at the cost of reduced speed. Represent the natural progression for an experienced miner.

| Name               | Slots H/M/L | Cargo | Speed | mine× | Requirements                                                                                |      Price | Rarity   |
| ------------------ | :---------: | ----: | :---: | :---: | ------------------------------------------------------------------------------------------- | ---------: | -------- |
| Ironclad           |    3/5/5    | 1,000 |   75  | ×1.75 | Shield Management L8 + Industrial Command L10 + Mining Ship Spec L5                         |  90,000 cr | uncommon |
| Extractor          |    6/3/3    |   800 |   90  | ×2.75 | Mining L15 + Industrial Command L10 + Mining Ship Spec L8                                   | 100,000 cr | uncommon |
| Mining Barge       |    5/4/4    | 1,500 |   90  | ×2.25 | Industrial Command L12 + Mining Ship Spec L8                                                |  18,000 cr | rare     |
| Bastion            |    4/6/6    | 1,300 |   65  | ×2.25 | Defense Systems L10 + Shield Management L10 + Industrial Command L18 + Mining Ship Spec L12 | 280,000 cr | rare     |
| Heavy Mining Barge |    6/5/5    | 2,000 |   75  |  ×3.0 | Mining L25 + Industrial Command L30 + Mining Ship Spec L28                                  |  25,000 cr | rare     |
| Titan Drill        |    8/4/4    | 4,000 |   70  | ×3.75 | Mining L30 + Mining Turrets L25 + Industrial Command L35 + Mining Ship Spec L35             | 400,000 cr | rare     |

---

### Gas Mining Ship

Gas-specialized ships. Their gas multiplier is significantly higher than their generic multiplier and automatically activates when mining gas.

| Name             | Slots H/M/L | Cargo | Speed | mine× | gas× | Requirements                                                                            |      Price | Rarity   |
| ---------------- | :---------: | ----: | :---: | :---: | :--: | --------------------------------------------------------------------------------------- | ---------: | -------- |
| Nebula Runner    |    2/2/2    |   400 |  110  |  ×1.0 | ×2.0 | Mining L8 + Gas Harvesting L5 + Gas Ship Command L1                                     |  20,000 cr | uncommon |
| Vapor Collector  |    2/2/3    | 1,200 |   90  |  ×1.5 | ×2.5 | Gas Harvesting L10 + Gas Ship Command L2 + Industrial Command L8                        |  80,000 cr | uncommon |
| Mining Leviathan |    2/3/3    | 1,800 |   75  | ×1.75 | ×4.0 | Gas Harvesting L20 + Gas Ship Command L3 + Industrial Command L15 + Gas Mining Spec L10 | 250,000 cr | rare     |

---

### Ice Mining Ship

Ice-specialized ships. Same logic as gas ships — the ice multiplier activates when mining ice.

| Name         | Slots H/M/L | Cargo | Speed | mine× | ice× | Requirements                                                                            |      Price | Rarity   |
| ------------ | :---------: | ----: | :---: | :---: | :--: | --------------------------------------------------------------------------------------- | ---------: | -------- |
| Ice Skimmer  |    2/2/2    |   400 |  110  |  ×1.0 | ×2.0 | Mining L8 + Ice Harvesting L5 + Ice Ship Command L1                                     |  20,000 cr | uncommon |
| Frostbreaker |    2/2/3    | 1,200 |   90  |  ×1.5 | ×2.5 | Ice Harvesting L10 + Ice Ship Command L2 + Industrial Command L8                        |  80,000 cr | uncommon |
| Glacier King |    2/3/3    | 1,800 |   75  | ×1.75 | ×4.0 | Ice Harvesting L20 + Ice Ship Command L3 + Industrial Command L15 + Ice Mining Spec L10 | 250,000 cr | rare     |

---

### Hauler

Pure support ship. Does not mine — its role is cargo transport and fleet command via Mining Links. Its massive cargo makes it essential for fleet operations.

| Name      | Slots H/M/L |  Cargo | Speed | Requirements                               |     Price | Rarity |
| --------- | :---------: | -----: | :---: | ------------------------------------------ | --------: | ------ |
| Oremaster |    0/3/2    | 20,000 |   70  | Mining Foreman L1 + Industrial Command L15 | 50,000 cr | epic   |

---

---

## ⚙️ Modules

---

### 🔴 High Slot

#### Ore — Mining Lasers

Increase solid ore extraction yield. Their efficiency is reduced to 20% of their nominal value on gas and ice — they only make sense on an ore-focused ship. Compatible with all mining ship classes.

| Name                 | Bonus yield ore | Requirements      |    Price | Rarity   |
| -------------------- | :-------------: | ----------------- | -------: | -------- |
| Starter Mining Laser |       +10       | —                 |     free | common   |
| Mining Laser I       |       +12       | Mining Turrets L1 |   500 cr | common   |
| Mining Laser II      |       +16       | Mining Turrets L3 | 2,500 cr | uncommon |
| Mining Laser III     |       +22       | Mining Turrets L5 | 8,000 cr | rare     |

---

#### Gas — Gas Siphon

Increase gas extraction yield. Their efficiency is reduced to 20% of their nominal value on ore and ice. Ship compatibility becomes more restrictive with each tier.

| Name           | Bonus yield gas | Requirements                            | Compatible Ships                    |     Price | Rarity   |
| -------------- | :-------------: | --------------------------------------- | ----------------------------------- | --------: | -------- |
| Gas Siphon I   |       +12       | Gas Harvesting L5 + Mining Turrets L5   | Gas Mining Ship, Mining Ship, Barge |  2,500 cr | common   |
| Gas Siphon II  |       +20       | Gas Harvesting L12 + Mining Turrets L12 | Gas Mining Ship, Barge              |  8,000 cr | uncommon |
| Gas Siphon III |       +30       | Gas Harvesting L20 + Mining Turrets L20 | Gas Mining Ship only                | 25,000 cr | rare     |

---

#### Ice — Ice Harvester

Increase ice extraction yield. Their efficiency is reduced to 20% of their nominal value on ore and gas. Ship compatibility becomes more restrictive with each tier.

| Name              | Bonus yield ice | Requirements                             | Compatible Ships                    |     Price | Rarity   |
| ----------------- | :-------------: | ---------------------------------------- | ----------------------------------- | --------: | -------- |
| Ice Harvester I   |       +15       | Ice Harvesting L5 + Mining Turrets L8    | Ice Mining Ship, Mining Ship, Barge |  8,000 cr | common   |
| Ice Harvester II  |       +24       | Mining Turrets L18 + Ice Mining Spec L15 | Ice Mining Ship, Barge              | 25,000 cr | uncommon |
| Ice Harvester III |       +36       | Mining Turrets L28 + Ice Mining Spec L30 | Ice Mining Ship only                | 80,000 cr | rare     |

---

### 🟡 Mid Slot

#### Generic — Survey Scanner

Improves asteroid analysis, increasing overall mining yield. Applies fully to ore, gas, and ice. Scanner effectiveness is amplified by the Survey Upgrades skill.

| Name              | Bonus survey | Requirements       |     Price | Rarity   |
| ----------------- | :----------: | ------------------ | --------: | -------- |
| Survey Scanner I  |   +5 levels  | Survey L5          |  2,000 cr | common   |
| Survey Scanner II |  +10 levels  | Survey Upgrades L3 | 10,000 cr | uncommon |

---

#### Generic — Mining Computer

Increases overall mining yield by a fixed percentage. Applies fully to ore, gas, and ice, after all other bonuses.

| Name               | Bonus % yield | Requirements |    Price | Rarity   |
| ------------------ | :-----------: | ------------ | -------: | -------- |
| Mining Computer I  |      +3%      | Mining L5    |   750 cr | common   |
| Mining Computer II |      +6%      | Mining L15   | 2,500 cr | uncommon |

---

#### Generic — Mining Foreman Link

Increases the yield of deployed mining drones. Applies to ore, gas, and ice.

| Name                   | Bonus drone yield | Requirements              |     Price | Rarity   |
| ---------------------- | :---------------: | ------------------------- | --------: | -------- |
| Mining Foreman Link I  |        +3%        | Mining Drone Operation L5 |  2,500 cr | common   |
| Mining Foreman Link II |        +6%        | Mining Foreman L3         | 12,000 cr | uncommon |

---

#### Generic — Cargo Coordinator

Reduces unloading time during auto-cycle, decreasing time spent between belt and station. Only the most effective module is taken into account — equipping multiple provides no additional benefit. Restricted to industrial and mining ships.

| Name                  | Unload reduction | Requirements      |     Price | Rarity |
| --------------------- | :--------------: | ----------------- | --------: | ------ |
| Cargo Coordinator I   |       −15%       | Mining Foreman L1 | 12,000 cr | rare   |
| Cargo Coordinator II  |       −25%       | Mining Foreman L3 | 25,000 cr | rare   |
| Cargo Coordinator III |       −35%       | Mining Foreman L5 | 50,000 cr | epic   |

---

#### Fleet — Mining Link

Increases mining yield for all allied fleet members. Usable only on command ships — unusable solo.

| Name            | Fleet bonus | Requirements      |     Price | Rarity |
| --------------- | :---------: | ----------------- | --------: | ------ |
| Mining Link I   |     +5%     | Mining Foreman L1 |  8,000 cr | rare   |
| Mining Link II  |     +8%     | Mining Foreman L3 | 16,000 cr | rare   |
| Mining Link III |     +12%    | Mining Foreman L5 | 32,000 cr | epic   |

---

### 🔵 Low Slot

#### Generic — Mining Yield Amplifier

Increases overall mining yield by a fixed percentage, in addition to the Mining Computer. Applies fully to ore, gas, and ice.

| Name                      | Bonus % yield | Requirements                         |     Price | Rarity   |
| ------------------------- | :-----------: | ------------------------------------ | --------: | -------- |
| Mining Yield Amplifier I  |      +5%      | Mining L10 + Mining Amplification L1 |  5,000 cr | uncommon |
| Mining Yield Amplifier II |      +10%     | Mining L25 + Mining Amplification L4 | 25,000 cr | rare     |

---

#### Generic — Speed Modules

Increase ship movement speed, reducing travel time between belt and station during unloading cycles. The faster the ship, the more time it spends mining and the less time moving.

> Afterburners and Microwarpdrives do not increase travel speed in the context of mining — they only have an effect in combat.

| Name                       | Speed bonus | Requirements     |    Price | Rarity   |
| -------------------------- | :---------: | ---------------- | -------: | -------- |
| Reaction Drive Injector I  |     +10%    | Navigation L1    | 1,000 cr | common   |
| Reaction Drive Injector II |     +15%    | Navigation L2    | 3,800 cr | uncommon |
| Mass-Reduced Frame I       |     +12%    | Hull Upgrades L1 |   800 cr | common   |
| Mass-Reduced Frame II      |     +18%    | Hull Upgrades L2 | 3,000 cr | uncommon |

---

#### Generic — Fitting Modules (CPU & Power Grid)

These modules do not directly increase yield but expand the ship’s fitting capacity — allowing more or more powerful modules to be equipped, which consume more system resources.

| Name                    |      Bonus      | Requirements             |    Price | Rarity   |
| ----------------------- | :-------------: | ------------------------ | -------: | -------- |
| Co-Processor I          |     +10% CPU    | CPU Management L1        | 2,000 cr | common   |
| Co-Processor II         |     +15% CPU    | CPU Management L3        | 6,000 cr | uncommon |
| Reactor Control Unit I  | +10% Power Grid | Power Grid Management L1 | 2,000 cr | common   |
| Reactor Control Unit II | +15% Power Grid | Power Grid Management L3 | 6,000 cr | uncommon |

---

#### Non-mining specific — Cargo Expander

General-purpose module that increases cargo capacity. Useful in mining to reduce the frequency of unloading trips.

| Name               | Bonus cargo | Requirements          |    Price | Rarity   |
| ------------------ | :---------: | --------------------- | -------: | -------- |
| Cargo Expander I   |     +5%     | —                     |   500 cr | common   |
| Cargo Expander II  |     +10%    | Cargo Optimization L3 | 1,500 cr | uncommon |
| Cargo Expander III |     +15%    | Cargo Optimization L5 | 5,000 cr | rare     |

---

## 🤖 Mining Drones

Mining drones extend ship yield without occupying slots. Each deployed drone adds its own extraction yield, amplified by drone skills and Mining Foreman Link modules. The number of drones that can be deployed simultaneously depends on the Mining Drone Operation skill.

| Name             | Yield per drone | Requirements |    Price | Rarity   |
| ---------------- | :-------------: | ------------ | -------: | -------- |
| Mining Drone Mk1 |        +5       | —            |   200 cr | common   |
| Mining Drone Mk2 |       +12       | —            |   750 cr | uncommon |
| Mining Drone Mk3 |       +25       | —            | 3,000 cr | rare     |

---

## Summary — Requirements by Type

### Ore only

| Item                 | Key requirement   |
| -------------------- | ----------------- |
| Starter Mining Laser | —                 |
| Mining Laser I       | Mining Turrets L1 |
| Mining Laser II      | Mining Turrets L3 |
| Mining Laser III     | Mining Turrets L5 |

---

### Gas only

| Item           | Key requirement                         |
| -------------- | --------------------------------------- |
| Gas Siphon I   | Gas Harvesting L5 + Mining Turrets L5   |
| Gas Siphon II  | Gas Harvesting L12 + Mining Turrets L12 |
| Gas Siphon III | Gas Harvesting L20 + Mining Turrets L20 |

---

### Ice only

| Item              | Key requirement                          |
| ----------------- | ---------------------------------------- |
| Ice Harvester I   | Ice Harvesting L5 + Mining Turrets L8    |
| Ice Harvester II  | Mining Turrets L18 + Ice Mining Spec L15 |
| Ice Harvester III | Mining Turrets L28 + Ice Mining Spec L30 |

---

### Universal — yield (ore + gas + ice)

| Item                      | Key requirement                      |
| ------------------------- | ------------------------------------ |
| Mining Computer I         | Mining L5                            |
| Survey Scanner I          | Survey L5                            |
| Mining Yield Amplifier I  | Mining L10 + Mining Amplification L1 |
| Mining Computer II        | Mining L15                           |
| Survey Scanner II         | Survey Upgrades L3                   |
| Mining Yield Amplifier II | Mining L25 + Mining Amplification L4 |

---

### Universal — cycle & unloading

| Item                       | Key requirement   |
| -------------------------- | ----------------- |
| Reaction Drive Injector I  | Navigation L1     |
| Mass-Reduced Frame I       | Hull Upgrades L1  |
| Reaction Drive Injector II | Navigation L2     |
| Mass-Reduced Frame II      | Hull Upgrades L2  |
| Cargo Coordinator I        | Mining Foreman L1 |
| Cargo Coordinator II       | Mining Foreman L3 |
| Cargo Coordinator III      | Mining Foreman L5 |

---

### Universal — fitting

| Item                    | Key requirement          |
| ----------------------- | ------------------------ |
| Co-Processor I          | CPU Management L1        |
| Reactor Control Unit I  | Power Grid Management L1 |
| Co-Processor II         | CPU Management L3        |
| Reactor Control Unit II | Power Grid Management L3 |

---

### Universal — cargo & fleet

| Item                   | Key requirement           |
| ---------------------- | ------------------------- |
| Cargo Expander I       | —                         |
| Cargo Expander II      | Cargo Optimization L3     |
| Mining Foreman Link I  | Mining Drone Operation L5 |
| Cargo Expander III     | Cargo Optimization L5     |
| Mining Foreman Link II | Mining Foreman L3         |
| Mining Link I          | Mining Foreman L1         |
| Mining Link II         | Mining Foreman L3         |
| Mining Link III        | Mining Foreman L5         |
