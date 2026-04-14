# Vaisseaux et modules recommandés par rôle et palier

> Les yields indiqués sont des yields bruts de base (équipement × multiplicateur vaisseau)
> avant application des skills, modules de support et buffs.
> Le fitting des slots hauts tient compte des contraintes CPU et Power Grid de chaque vaisseau.
> Chaque palier représente soit un changement de vaisseau, soit un changement de module.

---

## 🪨 Mineur de Base

Le Mining Laser III (CPU 100, PG 25) est le module ore le plus puissant mais aussi le plus consommateur. Selon le vaisseau, tous les slots hauts ne peuvent pas l'accueillir — les slots restants sont comblés par des Mining Laser I (CPU 40, PG 8) ou des Starter Lasers (CPU 15, PG 2).

> Temps calculés avec Basic Learning L5 + Advanced Learning L5 (-35% sur tous les temps de formation).

| Palier | Vaisseau | Fitting hauts | mine× | Yield | Cargo | Δ palier | Cumulé |
|:------:|---------|--------------|:-----:|:-----:|------:|:--------:|:------:|
| Base P1 | Starter Shuttle | 2× Starter Mining Laser | — | **20** | 100 | — | — |
| Base P2 | Prospector | 2× Laser III + 1× Laser I | ×1.5 | **84** | 500 | 56m | 56m |
| Base P3 | Mining Skiff | 3× Laser III | ×2.0 | **132** | 1 000 | 29m | 1h25 |

**Base P2 :** Mining L0→L5 (24m) + Mining Turrets L0→L5 (32m)
**Base P3 :** Mining L5→L8 (29m)

> **Starter Shuttle** (CPU 150, PG 30) : les 2 Starter Lasers (CPU 30, PG 4) rentrent sans contrainte. Le vaisseau n'a pas de multiplicateur — yield = somme brute des modules.
>
> **Prospector** (CPU 320, PG 70) : 2 Laser III occupent CPU 200 + PG 50. Il reste CPU 120 et PG 20 pour le 3e slot — un Laser I (CPU 40, PG 8) y rentre, pas un Laser III.
>
> **Mining Skiff** (CPU 350, PG 75) : 3 Laser III consomment CPU 300 et PG 75 exactement — PG saturé, le 4e slot reste vide.

---

---

## ⛏️ Ore Miner

> Temps calculés avec Basic Learning L5 + Advanced Learning L5 (-35%). Cumulé inclut les paliers Mineur de Base.

| Palier | Vaisseau | Fitting hauts | mine× | Yield | Cargo | Δ palier | Cumulé |
|:------:|---------|--------------|:-----:|:-----:|------:|:--------:|:------:|
| P1 — Crystal Caverns | Mining Barge | 3× Laser III + 2× Laser I | ×2.25 | **202** | 1 500 | 5h22 | 6h47 |
| P2 — Titanium Ridge | Extractor | 3× Laser III + 1× Laser I + 2× Starter | ×2.75 | **270** | 800 | 6h12 | 13h |
| P3 — Cobaltine | Bastion | 4× Laser III | ×2.25 | **198** | 1 300 | 1j | 1j13h |
| P4 — Deep Core Sector | Heavy Mining Barge | 4× Laser III + 1× Laser I + 1× Starter | ×3.0 | **330** | 2 000 | 4j05h | 5j18h |
| P5 — Titan Drill | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4 000 | 5j16h | 11j11h |
| P6 — Void Rift Alpha | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4 000 | 13j21h | 25j09h |
| P7 — Starium Nebula | Titan Drill | 6× Laser III + 1× Laser I | ×3.75 | **540** | 4 000 | 86j02h | 111j11h |

**P1 :** Mining L8→L15 (3h) + Industrial Command L5→L12 (1h44) + Mining Ship Spec L0→L8 (37m)
**P2 :** Mining L15→L20 (6h12)
**P3 :** Mining L20→L25 (15h27) + Industrial Command L12→L18 (4h47) + Mining Ship Spec L8→L12 (32m) + Defense Systems L0→L10 (1h24) + Shield Management L0→L10 (2h04)
**P4 :** Mining L25→L30 (1j14h) + Industrial Command L18→L30 (2j09h) + Mining Ship Spec L12→L28 (6h06)
**P5 :** Mining Turrets L5→L25 (1j09h) + Industrial Command L30→L35 (3j23h) + Mining Ship Spec L28→L35 (7h24)
**P6 :** Mining L30→L40 (13j21h)
**P7 :** Mining L40→L50 (86j02h)

> **Mining Barge** (CPU 420, PG 95) : 3 Laser III (CPU 300, PG 75) + 2 Laser I (CPU 80, PG 16) = CPU 380, PG 91. Le PG restant (4) est insuffisant pour un Starter supplémentaire.
>
> **Extractor** (CPU 420, PG 90) : 3 Laser III (CPU 300, PG 75) + 1 Laser I (CPU 40, PG 8) = CPU 340, PG 83. PG restant 7 — insuffisant pour un second Laser I (PG 8). Les 2 derniers slots accueillent 2 Starters (CPU 30, PG 4).
>
> **Bastion** (CPU 480, PG 110) : 4 Laser III (CPU 400, PG 100) s'insèrent proprement — tous les slots hauts sont remplis par le module principal.
>
> **Heavy Mining Barge** (CPU 500, PG 115) : 4 Laser III (CPU 400, PG 100) + 1 Laser I (CPU 40, PG 8) = CPU 440, PG 108. PG restant 7 — insuffisant pour un second Laser I. Le dernier slot accueille 1 Starter (CPU 15, PG 2).
>
> **Titan Drill** (CPU 650, PG 160) : 6 Laser III (CPU 600, PG 150) + 1 Laser I (CPU 40, PG 8) = CPU 640, PG 158. Les 2 derniers slots n'ont plus assez de CPU ni PG pour d'autres modules.
>
> **Note P3 — Bastion :** son yield brut (198) est inférieur à l'Extractor (270) mais son cargo est supérieur (1 300 vs 800). C'est un vaisseau orienté survie et cargo en attendant le Heavy Mining Barge.
>
> **Notes P6 et P7 :** aucun nouveau vaisseau ni module ne se débloque entre Mining L30 et L50. Ces paliers sont des paliers d'accès aux ceintures endgame uniquement.

### Progression du yield ore

```
Base P1 →   20  (Starter Shuttle  + Starter×2)              —       cumulé: —
Base P2 →   84  (Prospector  ×1.5 + L3×2 + L1×1)       ×4.2    56m   cumulé: 56m
Base P3 →  132  (Mining Skiff×2.0 + L3×3)               ×1.6    29m   cumulé: 1h25
Ore  P1 →  202  (Mining Barge×2.25+ L3×3 + L1×2)        ×1.5   5h22   cumulé: 6h47
Ore  P2 →  270  (Extractor   ×2.75+ L3×3 + L1×1 + St×2) ×1.3   6h12   cumulé: 13h
Ore  P3 →  198* (Bastion     ×2.25+ L3×4)                —     1j   cumulé: 1j13h
Ore  P4 →  330  (Heavy M.B.  ×3.0 + L3×4 + L1×1 + St×1) ×1.7* 4j05h   cumulé: 5j18h
Ore  P5 →  540  (Titan Drill ×3.75+ L3×6 + L1×1)         ×1.6  5j16h   cumulé: 11j11h
Ore  P6 →  540  (Titan Drill inchangé)                    —    13j21h   cumulé: 25j09h
Ore  P7 →  540  (Titan Drill inchangé)                    —    86j02h   cumulé: 111j11h
```
*Le Bastion est un palier cargo/survie. Le yield reprend sa progression à P4 (×1.7 vs P2 Extractor).

---

---

## 💨 Gas Miner

Tous les vaisseaux gas ont 2 slots hauts. Les Gas Siphons rentrent tous dans les limites CPU/PG de leur vaisseau dédié — aucune contrainte de fitting sur cette spécialisation.

> Temps calculés avec Basic Learning L5 + Advanced Learning L5 (-35%). Cumulé part de zéro (spécialisation distincte).

| Palier | Vaisseau | Fitting hauts | gas× | Yield | Cargo | Δ palier | Cumulé |
|:------:|---------|--------------|:----:|:-----:|------:|:--------:|:------:|
| P1 — Fullerite | Nebula Runner | 2× Gas Siphon I | ×2.0 | **48** | 400 | 4h53 | 4h53 |
| P2 — Cytoplasm | Vapor Collector | 2× Gas Siphon I | ×2.5 | **60** | 1 200 | 1h04 | 5h57 |
| P3 — Organic Nebula | Vapor Collector | 2× Gas Siphon II | ×2.5 | **100** | 1 200 | 1j | 1j06h |
| P4 — Mykocerosin | Mining Leviathan | 2× Gas Siphon II | ×4.0 | **160** | 1 800 | 1j23h | 3j06h |
| P5 — Toxic Maelstrom | Mining Leviathan | 2× Gas Siphon III | ×4.0 | **240** | 1 800 | 39j | 42j07h |

**P1 :** Mining L0→L15 (3h54) + Mining Turrets L0→L5 (32m) + Gas Harvesting L0→L5 (24m) + Gas Ship Command L0→L1 (3m)
**P2 :** Gas Harvesting L5→L10 (1h) + Gas Ship Command L1→L2 (4m)
**P3 :** Mining L15→L25 (21h39) + Mining Turrets L5→L12 (2h19) + Gas Harvesting L10→L12 (44m)
**P4 :** Mining L25→L30 (1j14h) + Gas Harvesting L12→L20 (7h58) + Gas Ship Command L2→L3 (5m) + Gas Mining Spec L0→L10 (1h24)
**P5 :** Mining L30→L45 (38j14h) + Mining Turrets L12→L20 (10h37)

### Progression du yield gas

```
P1 →  48  (Nebula Runner    ×2.0 + Siphon I×2)    —      cumulé: 4h53
P2 →  60  (Vapor Collector  ×2.5 + Siphon I×2)    +25%   cumulé: 5h57
P3 → 100  (Vapor Collector  ×2.5 + Siphon II×2)   +67%   cumulé: 1j06h
P4 → 160  (Mining Leviathan ×4.0 + Siphon II×2)   +60%   cumulé: 3j06h
P5 → 240  (Mining Leviathan ×4.0 + Siphon III×2)  +50%   cumulé: 42j07h
```

---

---

## 🧊 Ice Miner

Tous les vaisseaux ice ont 2 slots hauts. Même remarque que pour le gas — les Ice Harvesters rentrent tous dans les limites CPU/PG de leur vaisseau dédié.

> Temps calculés avec Basic Learning L5 + Advanced Learning L5 (-35%). Cumulé part de zéro (spécialisation distincte).

| Palier | Vaisseau | Fitting hauts | ice× | Yield | Cargo | Δ palier | Cumulé |
|:------:|---------|--------------|:----:|:-----:|------:|:--------:|:------:|
| P1 — Frozen Expanse | Ice Skimmer | 2× Ice Harvester I | ×2.0 | **60** | 400 | 5h33 | 5h33 |
| P2 — Glacial Mass | Frostbreaker | 2× Ice Harvester I | ×2.5 | **75** | 1 200 | 1h04 | 6h37 |
| P3 — Permafrost Cluster | Frostbreaker | 2× Ice Harvester II | ×2.5 | **120** | 1 200 | 1j09h | 1j16h |
| P4 — Blue Ice | Glacier King | 2× Ice Harvester II | ×4.0 | **192** | 1 800 | 1j23h | 3j15h |
| P5 — Dark Ice Nebula | Glacier King | 2× Ice Harvester III | ×4.0 | **288** | 1 800 | 18j11h | 22j03h |

**P1 :** Mining L0→L15 (3h54) + Mining Turrets L0→L8 (1h11) + Ice Harvesting L0→L5 (24m) + Ice Ship Command L0→L1 (3m)
**P2 :** Ice Harvesting L5→L10 (1h) + Ice Ship Command L1→L2 (4m)
**P3 :** Mining L15→L25 (21h39) + Mining Turrets L8→L18 (8h03) + Ice Mining Spec L0→L15 (3h54)
**P4 :** Mining L25→L30 (1j14h) + Ice Harvesting L10→L20 (8h42) + Ice Ship Command L2→L3 (5m)
**P5 :** Mining L30→L40 (13j21h) + Mining Turrets L18→L28 (2j01h) + Ice Mining Spec L15→L30 (2j12h)

### Progression du yield ice

```
P1 →  60  (Ice Skimmer  ×2.0 + Harvester I×2)    —      cumulé: 5h33
P2 →  75  (Frostbreaker ×2.5 + Harvester I×2)    +25%   cumulé: 6h37
P3 → 120  (Frostbreaker ×2.5 + Harvester II×2)   +60%   cumulé: 1j16h
P4 → 192  (Glacier King ×4.0 + Harvester II×2)   +60%   cumulé: 3j15h
P5 → 288  (Glacier King ×4.0 + Harvester III×2)  +50%   cumulé: 22j03h
```

---

---

## Comparaison gas / ice

| Palier | Gas yield | Ice yield | Écart | Cumulé gas | Cumulé ice |
|:------:|:---------:|:---------:|:-----:|:----------:|:----------:|
| P1 | 48 | 60 | Ice +25% | 4h53 | 5h33 |
| P2 | 60 | 75 | Ice +25% | 5h57 | 6h37 |
| P3 | 100 | 120 | Ice +20% | 1j06h | 1j16h |
| P4 | 160 | 192 | Ice +20% | 3j06h | 3j15h |
| P5 | 240 | 288 | Ice +20% | 42j07h | 22j03h |

L'ice est systématiquement plus rentable en yield brut à chaque palier équivalent, et s'avère également moins longue à progresser — l'endgame ice (P5) est atteint deux fois plus vite que l'endgame gas (23j vs 44j). L'avantage de l'ice vient à la fois des modules (valeurs de base supérieures : 15/24/36 vs 12/20/30) et de l'absence du goulot Mining L45 du gas. Le gas compense partiellement par la valeur unitaire des ressources endgame (Neurotoxin Cloud 150 cr vs Dark Glitter 100 cr).

---

## Rappel des contraintes CPU/PG — vaisseaux ore

| Vaisseau | CPU | PG | Slots H | Fitting optimal | CPU utilisé | PG utilisé | Yield |
|---------|:---:|:--:|:-------:|----------------|:-----------:|:----------:|:-----:|
| Starter Shuttle | 150 | 30 | 2 | 2× Starter | 30 | 4 | 20 |
| Prospector | 320 | 70 | 3 | 2× L3 + 1× L1 | 240 | 58 | 84 |
| Mining Skiff | 350 | **75** | 4 | 3× L3 *(PG saturé)* | 300 | 75 | 132 |
| Mining Barge | 420 | 95 | 5 | 3× L3 + 2× L1 | 380 | 91 | 202 |
| Extractor | 420 | **90** | 6 | 3× L3 + 1× L1 + 2× Starter | 370 | 87 | 270 |
| Bastion | 480 | 110 | 4 | 4× L3 | 400 | 100 | 198 |
| Heavy Mining Barge | 500 | **115** | 6 | 4× L3 + 1× L1 + 1× Starter | 455 | 110 | 330 |
| Titan Drill | **650** | **160** | 8 | 6× L3 + 1× L1 | 640 | 158 | 540 |

*En gras : la ressource limitante principale pour ce vaisseau.*
