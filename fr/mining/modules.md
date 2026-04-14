# Items de minage — Référence complète

> Vaisseaux et modules liés au minage.
> Vaisseaux classés par classe, modules classés par slot (haut / milieu / bas) puis par type de ressource.

---

## 🚀 Vaisseaux

Chaque vaisseau possède un multiplicateur de minage qui amplifie l'ensemble du rendement. Les vaisseaux gas et ice dédiés ont un multiplicateur spécialisé pour leur ressource cible, plus élevé que leur multiplicateur générique — c'est celui qui s'applique quand ils minent la ressource correspondante.

---

### Corvette

Vaisseau de départ, non achetable. Rend un service minimal mais permet de commencer à miner immédiatement.

| Nom | Slots H/M/L | Cargo | mine× | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-----:|-----------|-----:|--------|
| Starter Shuttle | 2/1/1 | 100 | — | — | gratuit | common |

---

### Mining Ship

Premiers vaisseaux industriels accessibles. Bon équilibre entre multiplicateur, cargo et vitesse pour débuter.

| Nom | Slots H/M/L | Cargo | Vitesse | mine× | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-------:|:-----:|-----------|-----:|--------|
| Prospector | 3/2/2 | 500 | 120 | ×1.5 | Mining L5 + Industrial Command L1 | 5 000 cr | uncommon |
| Mining Skiff | 4/3/3 | 1 000 | 120 | ×2.0 | Mining L8 + Industrial Command L5 | 12 000 cr | uncommon |

---

### Barge

Vaisseaux miniers lourds. Multiplicateurs élevés et cargo important au prix d'une vitesse réduite. Représentent la progression naturelle pour un mineur confirmé.

| Nom | Slots H/M/L | Cargo | Vitesse | mine× | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-------:|:-----:|-----------|-----:|--------|
| Ironclad | 3/5/5 | 1 000 | 75 | ×1.75 | Shield Management L8 + Industrial Command L10 + Mining Ship Spec L5 | 90 000 cr | uncommon |
| Extractor | 6/3/3 | 800 | 90 | ×2.75 | Mining L15 + Industrial Command L10 + Mining Ship Spec L8 | 100 000 cr | uncommon |
| Mining Barge | 5/4/4 | 1 500 | 90 | ×2.25 | Industrial Command L12 + Mining Ship Spec L8 | 18 000 cr | rare |
| Bastion | 4/6/6 | 1 300 | 65 | ×2.25 | Defense Systems L10 + Shield Management L10 + Industrial Command L18 + Mining Ship Spec L12 | 280 000 cr | rare |
| Heavy Mining Barge | 6/5/5 | 2 000 | 75 | ×3.0 | Mining L25 + Industrial Command L30 + Mining Ship Spec L28 | 25 000 cr | rare |
| Titan Drill | 8/4/4 | 4 000 | 70 | ×3.75 | Mining L30 + Mining Turrets L25 + Industrial Command L35 + Mining Ship Spec L35 | 400 000 cr | rare |

---

### Gas Mining Ship

Vaisseaux spécialisés gaz. Leur multiplicateur gaz est nettement supérieur à leur multiplicateur générique et s'active automatiquement lors du minage de gaz.

| Nom | Slots H/M/L | Cargo | Vitesse | mine× | gas× | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-------:|:-----:|:----:|-----------|-----:|--------|
| Nebula Runner | 2/2/2 | 400 | 110 | ×1.0 | ×2.0 | Mining L8 + Gas Harvesting L5 + Gas Ship Command L1 | 20 000 cr | uncommon |
| Vapor Collector | 2/2/3 | 1 200 | 90 | ×1.5 | ×2.5 | Gas Harvesting L10 + Gas Ship Command L2 + Industrial Command L8 | 80 000 cr | uncommon |
| Mining Leviathan | 2/3/3 | 1 800 | 75 | ×1.75 | ×4.0 | Gas Harvesting L20 + Gas Ship Command L3 + Industrial Command L15 + Gas Mining Spec L10 | 250 000 cr | rare |

---

### Ice Mining Ship

Vaisseaux spécialisés glace. Même logique que les vaisseaux gaz — le multiplicateur ice s'active lors du minage de glace.

| Nom | Slots H/M/L | Cargo | Vitesse | mine× | ice× | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-------:|:-----:|:----:|-----------|-----:|--------|
| Ice Skimmer | 2/2/2 | 400 | 110 | ×1.0 | ×2.0 | Mining L8 + Ice Harvesting L5 + Ice Ship Command L1 | 20 000 cr | uncommon |
| Frostbreaker | 2/2/3 | 1 200 | 90 | ×1.5 | ×2.5 | Ice Harvesting L10 + Ice Ship Command L2 + Industrial Command L8 | 80 000 cr | uncommon |
| Glacier King | 2/3/3 | 1 800 | 75 | ×1.75 | ×4.0 | Ice Harvesting L20 + Ice Ship Command L3 + Industrial Command L15 + Ice Mining Spec L10 | 250 000 cr | rare |

---

### Hauler

Vaisseau de support pur. Ne mine pas — son rôle est le transport de cargo et le commandement de flotte via les Mining Links. Son cargo massif le rend indispensable pour les opérations en flotte.

| Nom | Slots H/M/L | Cargo | Vitesse | Prérequis | Prix | Rareté |
|-----|:-----------:|------:|:-------:|-----------|-----:|--------|
| Oremaster | 0/3/2 | 20 000 | 70 | Mining Foreman L1 + Industrial Command L15 | 50 000 cr | epic |

---

---

## ⚙️ Modules

---

### 🔴 Slot Haut

#### Ore — Lasers de minage

Augmentent le rendement d'extraction de minerais solides. Leur efficacité est réduite à 20% de leur valeur nominale sur le gaz et la glace — ils n'ont de sens que sur un vaisseau ore. Compatibles avec toutes les classes de vaisseaux mineurs.

| Nom | Bonus yield ore | Prérequis | Prix | Rareté |
|-----|:---------------:|-----------|-----:|--------|
| Starter Mining Laser | +10 | — | gratuit | common |
| Mining Laser I | +12 | Mining Turrets L1 | 500 cr | common |
| Mining Laser II | +16 | Mining Turrets L3 | 2 500 cr | uncommon |
| Mining Laser III | +22 | Mining Turrets L5 | 8 000 cr | rare |

---

#### Gas — Gas Siphon

Augmentent le rendement d'extraction de gaz. Leur efficacité est réduite à 20% de leur valeur nominale sur le minerai et la glace. La restriction de vaisseaux compatibles se durcit à chaque tier.

| Nom | Bonus yield gas | Prérequis | Vaisseaux compatibles | Prix | Rareté |
|-----|:---------------:|-----------|----------------------|-----:|--------|
| Gas Siphon I | +12 | Gas Harvesting L5 + Mining Turrets L5 | Gas Mining Ship, Mining Ship, Barge | 2 500 cr | common |
| Gas Siphon II | +20 | Gas Harvesting L12 + Mining Turrets L12 | Gas Mining Ship, Barge | 8 000 cr | uncommon |
| Gas Siphon III | +30 | Gas Harvesting L20 + Mining Turrets L20 | Gas Mining Ship uniquement | 25 000 cr | rare |

---

#### Ice — Ice Harvester

Augmentent le rendement d'extraction de glace. Leur efficacité est réduite à 20% de leur valeur nominale sur le minerai et le gaz. La restriction de vaisseaux compatibles se durcit à chaque tier.

| Nom | Bonus yield ice | Prérequis | Vaisseaux compatibles | Prix | Rareté |
|-----|:---------------:|-----------|----------------------|-----:|--------|
| Ice Harvester I | +15 | Ice Harvesting L5 + Mining Turrets L8 | Ice Mining Ship, Mining Ship, Barge | 8 000 cr | common |
| Ice Harvester II | +24 | Mining Turrets L18 + Ice Mining Spec L15 | Ice Mining Ship, Barge | 25 000 cr | uncommon |
| Ice Harvester III | +36 | Mining Turrets L28 + Ice Mining Spec L30 | Ice Mining Ship uniquement | 80 000 cr | rare |

---

---

### 🟡 Slot Milieu

#### Générique — Survey Scanner

Améliore l'analyse des astéroïdes, augmentant le rendement global de minage. S'applique pleinement sur ore, gaz et glace. L'efficacité du scanner est amplifiée par le skill Survey Upgrades.

| Nom | Bonus survey | Prérequis | Prix | Rareté |
|-----|:------------:|-----------|-----:|--------|
| Survey Scanner I | +5 niveaux | Survey L5 | 2 000 cr | common |
| Survey Scanner II | +10 niveaux | Survey Upgrades L3 | 10 000 cr | uncommon |

---

#### Générique — Mining Computer

Augmente le rendement global de minage d'un pourcentage fixe. S'applique pleinement sur ore, gaz et glace, après tous les autres bonus.

| Nom | Bonus % yield | Prérequis | Prix | Rareté |
|-----|:-------------:|-----------|-----:|--------|
| Mining Computer I | +3% | Mining L5 | 750 cr | common |
| Mining Computer II | +6% | Mining L15 | 2 500 cr | uncommon |

---

#### Générique — Mining Foreman Link

Augmente le rendement des drones de minage déployés. S'applique sur ore, gaz et glace.

| Nom | Bonus drone yield | Prérequis | Prix | Rareté |
|-----|:-----------------:|-----------|-----:|--------|
| Mining Foreman Link I | +3% | Mining Drone Operation L5 | 2 500 cr | common |
| Mining Foreman Link II | +6% | Mining Foreman L3 | 12 000 cr | uncommon |

---

#### Générique — Cargo Coordinator

Réduit le temps de déchargement lors de l'auto-cycle, diminuant le temps passé entre la ceinture et la station. Seul le module le plus performant est pris en compte — en équiper plusieurs n'apporte aucun bénéfice supplémentaire. Réservé aux vaisseaux industriels et miniers.

| Nom | Réduction déchargement | Prérequis | Prix | Rareté |
|-----|:----------------------:|-----------|-----:|--------|
| Cargo Coordinator I | −15% | Mining Foreman L1 | 12 000 cr | rare |
| Cargo Coordinator II | −25% | Mining Foreman L3 | 25 000 cr | rare |
| Cargo Coordinator III | −35% | Mining Foreman L5 | 50 000 cr | epic |

---

#### Flotte — Mining Link

Augmente le rendement de minage de tous les membres de la flotte alliée. Utilisable uniquement sur des vaisseaux de commandement — inutilisable en solo.

| Nom | Bonus flotte | Prérequis | Prix | Rareté |
|-----|:------------:|-----------|-----:|--------|
| Mining Link I | +5% | Mining Foreman L1 | 8 000 cr | rare |
| Mining Link II | +8% | Mining Foreman L3 | 16 000 cr | rare |
| Mining Link III | +12% | Mining Foreman L5 | 32 000 cr | epic |

---

---

### 🔵 Slot Bas

#### Générique — Mining Yield Amplifier

Augmente le rendement global de minage d'un pourcentage fixe, en complément du Mining Computer. S'applique pleinement sur ore, gaz et glace.

| Nom | Bonus % yield | Prérequis | Prix | Rareté |
|-----|:-------------:|-----------|-----:|--------|
| Mining Yield Amplifier I | +5% | Mining L10 + Mining Amplification L1 | 5 000 cr | uncommon |
| Mining Yield Amplifier II | +10% | Mining L25 + Mining Amplification L4 | 25 000 cr | rare |

---

#### Générique — Modules de vitesse

Augmentent la vitesse de déplacement du vaisseau, réduisant ainsi le temps de trajet entre la ceinture et la station lors des cycles de déchargement. Plus le vaisseau est rapide, plus il passe de temps à miner et moins à se déplacer.

> Les Afterburners et Microwarpdrives n'augmentent pas la vitesse de déplacement au sens du minage — ils n'ont d'effet qu'en combat.

| Nom | Bonus vitesse | Prérequis | Prix | Rareté |
|-----|:-------------:|-----------|-----:|--------|
| Reaction Drive Injector I | +10% | Navigation L1 | 1 000 cr | common |
| Reaction Drive Injector II | +15% | Navigation L2 | 3 800 cr | uncommon |
| Mass-Reduced Frame I | +12% | Hull Upgrades L1 | 800 cr | common |
| Mass-Reduced Frame II | +18% | Hull Upgrades L2 | 3 000 cr | uncommon |

---

#### Générique — Modules de fitting (CPU et Power Grid)

Ces modules n'augmentent pas directement le rendement mais élargissent la capacité de fitting du vaisseau — permettant d'équiper des modules plus nombreux ou plus puissants, qui consomment davantage de ressources système.

| Nom | Bonus | Prérequis | Prix | Rareté |
|-----|:-----:|-----------|-----:|--------|
| Co-Processor I | +10% CPU | CPU Management L1 | 2 000 cr | common |
| Co-Processor II | +15% CPU | CPU Management L3 | 6 000 cr | uncommon |
| Reactor Control Unit I | +10% Power Grid | Power Grid Management L1 | 2 000 cr | common |
| Reactor Control Unit II | +15% Power Grid | Power Grid Management L3 | 6 000 cr | uncommon |

---

#### Non spécifique au minage — Cargo Expander

Module généraliste qui augmente la capacité de cargo. Utile en minage pour réduire la fréquence des trajets de déchargement.

| Nom | Bonus cargo | Prérequis | Prix | Rareté |
|-----|:-----------:|-----------|-----:|--------|
| Cargo Expander I | +5% | — | 500 cr | common |
| Cargo Expander II | +10% | Cargo Optimization L3 | 1 500 cr | uncommon |
| Cargo Expander III | +15% | Cargo Optimization L5 | 5 000 cr | rare |

---

---

## 🤖 Drones de minage

Les drones de minage étendent le rendement du vaisseau sans occuper de slot. Chaque drone déployé ajoute son propre rendement d'extraction, amplifié par les skills de drone et les modules Mining Foreman Link. Le nombre de drones déployables simultanément dépend du skill Mining Drone Operation.

| Nom | Yield par drone | Prérequis | Prix | Rareté |
|-----|:---------------:|-----------|-----:|--------|
| Mining Drone Mk1 | +5 | — | 200 cr | common |
| Mining Drone Mk2 | +12 | — | 750 cr | uncommon |
| Mining Drone Mk3 | +25 | — | 3 000 cr | rare |

---

## Synthèse — Prérequis par type

### Ore uniquement

| Item | Prérequis clé |
|------|--------------|
| Starter Mining Laser | — |
| Mining Laser I | Mining Turrets L1 |
| Mining Laser II | Mining Turrets L3 |
| Mining Laser III | Mining Turrets L5 |

### Gas uniquement

| Item | Prérequis clé |
|------|--------------|
| Gas Siphon I | Gas Harvesting L5 + Mining Turrets L5 |
| Gas Siphon II | Gas Harvesting L12 + Mining Turrets L12 |
| Gas Siphon III | Gas Harvesting L20 + Mining Turrets L20 |

### Ice uniquement

| Item | Prérequis clé |
|------|--------------|
| Ice Harvester I | Ice Harvesting L5 + Mining Turrets L8 |
| Ice Harvester II | Mining Turrets L18 + Ice Mining Spec L15 |
| Ice Harvester III | Mining Turrets L28 + Ice Mining Spec L30 |

### Universels — yield (ore + gas + ice)

| Item | Prérequis clé |
|------|--------------|
| Mining Computer I | Mining L5 |
| Survey Scanner I | Survey L5 |
| Mining Yield Amplifier I | Mining L10 + Mining Amplification L1 |
| Mining Computer II | Mining L15 |
| Survey Scanner II | Survey Upgrades L3 |
| Mining Yield Amplifier II | Mining L25 + Mining Amplification L4 |

### Universels — cycle et déchargement

| Item | Prérequis clé |
|------|--------------|
| Reaction Drive Injector I | Navigation L1 |
| Mass-Reduced Frame I | Hull Upgrades L1 |
| Reaction Drive Injector II | Navigation L2 |
| Mass-Reduced Frame II | Hull Upgrades L2 |
| Cargo Coordinator I | Mining Foreman L1 |
| Cargo Coordinator II | Mining Foreman L3 |
| Cargo Coordinator III | Mining Foreman L5 |

### Universels — fitting

| Item | Prérequis clé |
|------|--------------|
| Co-Processor I | CPU Management L1 |
| Reactor Control Unit I | Power Grid Management L1 |
| Co-Processor II | CPU Management L3 |
| Reactor Control Unit II | Power Grid Management L3 |

### Universels — cargo et flotte

| Item | Prérequis clé |
|------|--------------|
| Cargo Expander I | — |
| Cargo Expander II | Cargo Optimization L3 |
| Mining Foreman Link I | Mining Drone Operation L5 |
| Cargo Expander III | Cargo Optimization L5 |
| Mining Foreman Link II | Mining Foreman L3 |
| Mining Link I | Mining Foreman L1 |
| Mining Link II | Mining Foreman L3 |
| Mining Link III | Mining Foreman L5 |
