# Recommended Ships and Modules by Role and Tier

> Yields shown are base raw yields (equipment × ship multiplier)
> before applying skills, support modules, and buffs.
> High slot fitting accounts for each ship's CPU and Power Grid constraints.
> Each tier represents either a ship change or a module change.

---

## 🪨 Basic Miner

Mining Laser III (CPU 100, PG 25) is the most powerful ore module but also the most demanding. Depending on the ship, not all high slots can accommodate it — remaining slots are filled with Mining Laser I (CPU 40, PG 8) or Starter Lasers (CPU 15, PG 2).

> Training times calculated with Basic Learning L5 + Advanced Learning L5 (−35% on all training times).

| Tier | Ship | High Slot Fitting | mine× | Yield | Cargo | Δ tier | Cumulative |
|:----:|------|------------------|:-----:|:-----:|------:|:------:|:----------:|
| Base T1 | Starter Shuttle | 2× Starter Mining Laser | — | **20** | 100 | — | — |
| Base T2 | Prospector | 2× Laser III + 1× Laser I | ×1.5 | **84** | 500 | 56m | 56m |
| Base T3 | Mining Skiff | 3× Laser III | ×2.0 | **132** | 1,000 | 29m | 1h25 |

**Base T2:** Mining L0→L5 (24m) + Mining Turrets L0→L5 (32m)
**Base T3:** Mining L5→L8 (29m)

> **Starter Shuttle** (CPU 150, PG 30): the 2 Starter Lasers (CPU 30, PG 4) fit without constraint. The ship has no multiplier — yield = raw sum of module bonuses.
>
> **Prospector** (CPU 320, PG 70): 2 Laser III use CPU 200 + PG 50. The 3rd slot has CPU 120 and PG 20 remaining — a Laser I (CPU 40, PG 8) fits, a Laser III does not.
>
> **Mining Skiff** (CPU 350, PG 75): 3 Laser III consume exactly CPU 300 and PG 75 — PG is saturated, the 4th slot remains empty.

---

---

## ⛏️ Ore Miner

> Training times calculated with Basic Learning L5 + Advanced Learning L5 (−35%). Cumulative includes Basic Miner tiers.

| Tier | Ship | High Slot Fitting | mine× | Yield | Cargo | Δ tier | Cumulative |
|:----:|------|------------------|:-----:|:-----:|------:|:------:|:----------:|
| T1 — Crystal Caverns | Mining Barge | 3× Laser III + 2× Laser I | ×2.25 | **202** | 1,500 | 5h22 | 6h47 |
| T2 — Titanium Ridge | Extractor | 3× Laser III + 1× Laser I + 2× Starter | ×2.75 | **270** | 800 | 6h12 | 13h |
| T3 — Cobaltine | Bastion | 4× Laser III | ×2.25 | **198** | 1,300 | 1d | 1d13h |
| T4 — Deep Core Sector | Heavy Mining Barge | 4× Laser III + 1× Laser I + 1× Starter | ×3.0 | **330** | 2,000 | 4d05h | 5d18h |
| T5 — Titan Drill | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4,000 | 5d16h | 11d11h |
| T6 — Void Rift Alpha | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4,000 | 13d21h | 25d09h |
| T7 — Starium Nebula | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4,000 | 86d02h | 111d11h |

**T1:** Mining L8→L15 (3h) + Industrial Command L5→L12 (1h44) + Mining Ship Spec L0→L8 (37m)
**T2:** Mining L15→L20 (6h12)
**T3:** Mining L20→L25 (15h27) + Industrial Command L12→L18 (4h47) + Mining Ship Spec L8→L12 (32m) + Defense Systems L0→L10 (1h24) + Shield Management L0→L10 (2h04)
**T4:** Mining L25→L30 (1d14h) + Industrial Command L18→L30 (2d09h) + Mining Ship Spec L12→L28 (6h06)
**T5:** Mining Turrets L5→L25 (1d09h) + Industrial Command L30→L35 (3d23h) + Mining Ship Spec L28→L35 (7h24)
**T6:** Mining L30→L40 (13d21h)
**T7:** Mining L40→L50 (86d02h)

> **Mining Barge** (CPU 420, PG 95): 3 Laser III (CPU 300, PG 75) + 2 Laser I (CPU 80, PG 16) = CPU 380, PG 91. The remaining PG (4) is insufficient for an additional Starter.
>
> **Extractor** (CPU 420, PG 90): 3 Laser III (CPU 300, PG 75) + 1 Laser I (CPU 40, PG 8) = CPU 340, PG 83. PG remaining: 7 — not enough for a second Laser I (PG 8). The 2 remaining slots take 2 Starters (CPU 30, PG 4).
>
> **Bastion** (CPU 480, PG 110): 4 Laser III (CPU 400, PG 100) fit cleanly — all high slots are filled by the primary module.
>
> **Heavy Mining Barge** (CPU 500, PG 115): 4 Laser III (CPU 400, PG 100) + 1 Laser I (CPU 40, PG 8) = CPU 440, PG 108. PG remaining: 7 — not enough for a second Laser I. The last slot takes 1 Starter (CPU 15, PG 2).
>
> **Titan Drill** (CPU 650, PG 160): 6 Laser III (CPU 600, PG 150) + 1 Laser I (CPU 40, PG 8) = CPU 640, PG 158. The 2 remaining slots have insufficient CPU and PG for any additional module.
>
> **Note T3 — Bastion:** its raw yield (198) is lower than the Extractor (270) but its cargo is higher (1,300 vs 800). It is a survival/cargo-oriented ship serving as a bridge toward the Heavy Mining Barge.
>
> **Notes T6 and T7:** no new ship or module unlocks between Mining L30 and L50. These tiers are purely endgame belt access milestones.

### Ore Yield Progression

```
Base T1 →   20  (Starter Shuttle  + Starter×2)                —      cumul: —
Base T2 →   84  (Prospector  ×1.5 + L3×2 + L1×1)         ×4.2   56m   cumul: 56m
Base T3 →  132  (Mining Skiff×2.0 + L3×3)                 ×1.6   29m   cumul: 1h25
Ore  T1 →  202  (Mining Barge×2.25+ L3×3 + L1×2)          ×1.5  5h22   cumul: 6h47
Ore  T2 →  270  (Extractor   ×2.75+ L3×3 + L1×1 + St×2)   ×1.3  6h12   cumul: 13h
Ore  T3 →  198* (Bastion     ×2.25+ L3×4)                  —    1d   cumul: 1d13h
Ore  T4 →  330  (Heavy M.B.  ×3.0 + L3×4 + L1×1 + St×1)  ×1.7* 4d05h   cumul: 5d18h
Ore  T5 →  540  (Titan Drill ×3.75+ L3×6 + L1×1)          ×1.6  5d16h   cumul: 11d11h
Ore  T6 →  540  (Titan Drill unchanged)                     —   13d21h   cumul: 25d09h
Ore  T7 →  540  (Titan Drill unchanged)                     —   86d02h   cumul: 111d11h
```
*Bastion is a cargo/survival tier. Yield resumes progression at T4 (×1.7 vs T2 Extractor).

---

---

## 💨 Gas Miner

All gas ships have 2 high slots. Gas Siphons all fit within their dedicated ship's CPU/PG limits — no fitting constraints on this specialization.

> Training times calculated with Basic Learning L5 + Advanced Learning L5 (−35%). Cumulative starts from zero (separate specialization).

| Tier | Ship | High Slot Fitting | gas× | Yield | Cargo | Δ tier | Cumulative |
|:----:|------|------------------|:----:|:-----:|------:|:------:|:----------:|
| T1 — Fullerite | Nebula Runner | 2× Gas Siphon I | ×2.0 | **48** | 400 | 4h53 | 4h53 |
| T2 — Cytoplasm | Vapor Collector | 2× Gas Siphon I | ×2.5 | **60** | 1,200 | 1h04 | 5h57 |
| T3 — Organic Nebula | Vapor Collector | 2× Gas Siphon II | ×2.5 | **100** | 1,200 | 1d | 1d06h |
| T4 — Mykocerosin | Mining Leviathan | 2× Gas Siphon II | ×4.0 | **160** | 1,800 | 1d23h | 3d06h |
| T5 — Toxic Maelstrom | Mining Leviathan | 2× Gas Siphon III | ×4.0 | **240** | 1,800 | 39d | 42d07h |

**T1:** Mining L0→L15 (3h54) + Mining Turrets L0→L5 (32m) + Gas Harvesting L0→L5 (24m) + Gas Ship Command L0→L1 (3m)
**T2:** Gas Harvesting L5→L10 (1h) + Gas Ship Command L1→L2 (4m)
**T3:** Mining L15→L25 (21h39) + Mining Turrets L5→L12 (2h19) + Gas Harvesting L10→L12 (44m)
**T4:** Mining L25→L30 (1d14h) + Gas Harvesting L12→L20 (7h58) + Gas Ship Command L2→L3 (5m) + Gas Mining Spec L0→L10 (1h24)
**T5:** Mining L30→L45 (38d14h) + Mining Turrets L12→L20 (10h37)

### Gas Yield Progression

```
T1 →  48  (Nebula Runner    ×2.0 + Siphon I×2)    —      cumul: 4h53
T2 →  60  (Vapor Collector  ×2.5 + Siphon I×2)    +25%   cumul: 5h57
T3 → 100  (Vapor Collector  ×2.5 + Siphon II×2)   +67%   cumul: 1d06h
T4 → 160  (Mining Leviathan ×4.0 + Siphon II×2)   +60%   cumul: 3d06h
T5 → 240  (Mining Leviathan ×4.0 + Siphon III×2)  +50%   cumul: 42d07h
```

---

---

## 🧊 Ice Miner

All ice ships have 2 high slots. Same as gas — Ice Harvesters all fit within their dedicated ship's CPU/PG limits without constraint.

> Training times calculated with Basic Learning L5 + Advanced Learning L5 (−35%). Cumulative starts from zero (separate specialization).

| Tier | Ship | High Slot Fitting | ice× | Yield | Cargo | Δ tier | Cumulative |
|:----:|------|------------------|:----:|:-----:|------:|:------:|:----------:|
| T1 — Frozen Expanse | Ice Skimmer | 2× Ice Harvester I | ×2.0 | **60** | 400 | 5h33 | 5h33 |
| T2 — Glacial Mass | Frostbreaker | 2× Ice Harvester I | ×2.5 | **75** | 1,200 | 1h04 | 6h37 |
| T3 — Permafrost Cluster | Frostbreaker | 2× Ice Harvester II | ×2.5 | **120** | 1,200 | 1d09h | 1d16h |
| T4 — Blue Ice | Glacier King | 2× Ice Harvester II | ×4.0 | **192** | 1,800 | 1d23h | 3d15h |
| T5 — Dark Ice Nebula | Glacier King | 2× Ice Harvester III | ×4.0 | **288** | 1,800 | 18d11h | 22d03h |

**T1:** Mining L0→L15 (3h54) + Mining Turrets L0→L8 (1h11) + Ice Harvesting L0→L5 (24m) + Ice Ship Command L0→L1 (3m)
**T2:** Ice Harvesting L5→L10 (1h) + Ice Ship Command L1→L2 (4m)
**T3:** Mining L15→L25 (21h39) + Mining Turrets L8→L18 (8h03) + Ice Mining Spec L0→L15 (3h54)
**T4:** Mining L25→L30 (1d14h) + Ice Harvesting L10→L20 (8h42) + Ice Ship Command L2→L3 (5m)
**T5:** Mining L30→L40 (13d21h) + Mining Turrets L18→L28 (2d01h) + Ice Mining Spec L15→L30 (2d12h)

### Ice Yield Progression

```
T1 →  60  (Ice Skimmer  ×2.0 + Harvester I×2)    —      cumul: 5h33
T2 →  75  (Frostbreaker ×2.5 + Harvester I×2)    +25%   cumul: 6h37
T3 → 120  (Frostbreaker ×2.5 + Harvester II×2)   +60%   cumul: 1d16h
T4 → 192  (Glacier King ×4.0 + Harvester II×2)   +60%   cumul: 3d15h
T5 → 288  (Glacier King ×4.0 + Harvester III×2)  +50%   cumul: 22d03h
```

---

---

## Gas / Ice Comparison

| Tier | Gas yield | Ice yield | Gap | Gas cumulative | Ice cumulative |
|:----:|:---------:|:---------:|:---:|:--------------:|:--------------:|
| T1 | 48 | 60 | Ice +25% | 4h53 | 5h33 |
| T2 | 60 | 75 | Ice +25% | 5h57 | 6h37 |
| T3 | 100 | 120 | Ice +20% | 1d06h | 1d16h |
| T4 | 160 | 192 | Ice +20% | 3d06h | 3d15h |
| T5 | 240 | 288 | Ice +20% | 42d07h | 22d03h |

Ice is consistently more profitable in raw yield at every equivalent tier, and also faster to progress — ice endgame (T5) is reached twice as fast as gas endgame (23d vs 44d). Ice's advantage comes from both superior module base values (15/24/36 vs 12/20/30) and the absence of the Mining L45 bottleneck that gas requires. Gas partially compensates through higher unit value of endgame resources (Neurotoxin Cloud 150 cr vs Dark Glitter 100 cr).

---

## CPU/PG Constraints Summary — Ore Ships

| Ship | CPU | PG | High Slots | Optimal Fitting | CPU Used | PG Used | Yield |
|------|:---:|:--:|:----------:|----------------|:--------:|:-------:|:-----:|
| Starter Shuttle | 150 | 30 | 2 | 2× Starter | 30 | 4 | 20 |
| Prospector | 320 | 70 | 3 | 2× L3 + 1× L1 | 240 | 58 | 84 |
| Mining Skiff | 350 | **75** | 4 | 3× L3 *(PG saturated)* | 300 | 75 | 132 |
| Mining Barge | 420 | 95 | 5 | 3× L3 + 2× L1 | 380 | 91 | 202 |
| Extractor | 420 | **90** | 6 | 3× L3 + 1× L1 + 2× Starter | 370 | 87 | 270 |
| Bastion | 480 | 110 | 4 | 4× L3 | 400 | 100 | 198 |
| Heavy Mining Barge | 500 | **115** | 6 | 4× L3 + 1× L1 + 1× Starter | 455 | 110 | 330 |
| Titan Drill | **650** | **160** | 8 | 6× L3 + 1× L1 | 640 | 158 | 540 |

*Bold: the primary limiting resource for that ship.*
