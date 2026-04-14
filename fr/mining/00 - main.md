# Le Minage — Guide de synthèse

---

## 1. Les ressources

Le minage permet de récolter trois types de ressources, chacun nécessitant des équipements dédiés et des compétences spécifiques.

### Types de ressources

| Type | Prérequis d'accès | Description |
|------|:-----------------:|-------------|
| **Ore** ⛏️ | Mining ≥ L1 | Minerais solides, accessibles dès le début |
| **Ice** 🧊 | Ice Harvesting ≥ L1 | Glace, débloquée à partir de Mining L15 |
| **Gas** 💨 | Gas Harvesting ≥ L1 | Gaz, débloqué à partir de Mining L15 |

### Minerais — Ore

| Rareté | Minerai | Mining requis | Valeur |
|--------|---------|:-------------:|:------:|
| Common | Ferrite | L0 | 5 cr/u |
| Common | Copite | L5 | 8 cr/u |
| Uncommon | Luminite | L10 | 15 cr/u |
| Uncommon | Crystite | L15 | 25 cr/u |
| Uncommon | Titanite | L20 | 40 cr/u |
| Rare | Cobaltine | L25 | 60 cr/u |
| Rare | Iridite | L30 | 100 cr/u |
| Very Rare | Voidstone | L40 | 200 cr/u |
| Legendary | Starium | L50 | 500 cr/u |
| Mythic | Unicornium | L50 | 1 000 cr/u |

### Minerais — Ice

| Rareté | Minerai | Mining requis | Valeur |
|--------|---------|:-------------:|:------:|
| Common | Clear Ice | L15 | 12 cr/u |
| Uncommon | Glacial Mass | L20 | 20 cr/u |
| Rare | Blue Ice | L30 | 45 cr/u |
| Very Rare | Dark Glitter | L40 | 100 cr/u |

### Minerais — Gas

| Rareté | Minerai | Mining requis | Valeur |
|--------|---------|:-------------:|:------:|
| Common | Fullerite Gas | L15 | 10 cr/u |
| Uncommon | Cytoplasm | L20 | 22 cr/u |
| Rare | Mykocerosin | L30 | 55 cr/u |
| Very Rare | Neurotoxin Cloud | L45 | 150 cr/u |

---

## 2. Les ceintures

Chaque ceinture a un type de ressource fixe, un niveau de Mining minimum requis, et un multiplicateur de rendement de base. Certaines ceintures avancées comportent des risques de rencontre avec des PNJ hostiles.

### Ore

| Ceinture | Type | Mining | Multiplicateur | Minerais accessibles |
|----------|------|:------:|:--------------:|---------------------|
| Rookie Fields | Common | L0 | ×1.0 | Ferrite |
| Frontier Belt | Common | L5 | ×1.1 | Copite, Luminite |
| Crystal Caverns | Rich | L15 | ×1.2 | Crystite |
| Titanium Ridge | Rich | L20 | ×1.3 | Titanite, Cobaltine |
| Deep Core Sector | Deep Space | L30 | ×1.5 | Iridite |
| Void Rift Alpha | Void Rift | L40 | ×2.0 | Voidstone ⚠️ |
| Starium Nebula | Nebula | L50 | ×2.5 | Starium, Unicornium ⚠️ |

### Ice

| Ceinture | Type | Mining | Multiplicateur | Minerais accessibles |
|----------|------|:------:|:--------------:|---------------------|
| Frozen Expanse | Common | L15 | ×1.0 | Clear Ice |
| Permafrost Cluster | Rich | L25 | ×1.3 | Glacial Mass |
| Dark Ice Nebula | Nebula | L40 | ×1.8 | Dark Glitter ⚠️ |

### Gas

| Ceinture | Type | Mining | Multiplicateur | Minerais accessibles |
|----------|------|:------:|:--------------:|---------------------|
| Fullerite Pocket | Common | L15 | ×0.9 | Fullerite Gas |
| Organic Nebula | Rich | L25 | ×1.2 | Cytoplasm |
| Toxic Maelstrom | Void Rift | L45 | ×1.6 | Neurotoxin Cloud, Mykocerosin ⚠️ |

> ⚠️ Les ceintures de type **Void Rift** et **Nebula** sont situées en deep space et comportent des PNJ chasseurs. Chaque session de minage dans ces zones augmente la signature sensorielle du vaisseau, le rendant progressivement plus facile à détecter.

### Types de ceintures et leurs caractéristiques

| Type | Couleur | Risque | Multiplicateur typique |
|------|---------|:------:|:---------------------:|
| Common | Cyan | Nul | ×0.9 – ×1.1 |
| Rich | Vert | Nul | ×1.2 – ×1.3 |
| Deep Space | Bleu | Modéré | ×1.5 |
| Void Rift | Violet | Élevé | ×1.6 – ×2.0 |
| Nebula | Jaune | Élevé | ×1.8 – ×2.5 |

---

## 3. Les vaisseaux

Cinq grandes familles de vaisseaux interviennent dans le minage, chacune avec un rôle distinct.

### Corvette
Vaisseau de départ fourni gratuitement. Capacités très limitées, sans multiplicateur de minage. Permet d'apprendre les bases mais devient vite un frein à la progression.

### Mining Ship
Premiers vaisseaux industriels dédiés au minage ore. Bon équilibre entre multiplicateur, cargo et vitesse. Constituent l'étape naturelle après la corvette avant l'accès aux barges.

### Barge
Vaisseaux lourds ore. Multiplicateurs élevés et cargo important, au prix d'une vitesse réduite. Représentent la progression principale du mineur ore, du Mining Barge jusqu'au Titan Drill endgame.

### Gas Mining Ship / Ice Mining Ship
Vaisseaux spécialisés pour le gas et la glace. Disposent d'un multiplicateur dédié à leur ressource cible, nettement supérieur à leur multiplicateur générique. Indispensables pour optimiser le rendement dans leur spécialisation respective.

### Hauler
Vaisseau de support pur. Ne mine pas. Sert au transport de gros volumes et au commandement de flotte via les Mining Links. Son cargo massif en fait le pivot des opérations en flotte organisée.

---

## 4. Les modules

Les modules s'installent dans les slots hauts, milieu ou bas du vaisseau et agissent sur différentes dimensions du rendement.

### Slot Haut — Modules d'extraction

Ce sont les modules qui produisent directement le yield. Chaque type est optimisé pour une ressource et pénalisé à 20% de sa valeur hors de cette ressource.

| Catégorie | Ressource cible | Rôle |
|-----------|:--------------:|------|
| **Mining Laser / Strip Miner** | Ore | Extraction de minerais solides |
| **Gas Siphon** | Gas | Extraction de gaz |
| **Ice Harvester** | Ice | Extraction de glace |

### Slot Milieu — Amplification et support

Ces modules n'extraient pas directement mais améliorent l'efficacité globale de la session.

| Catégorie | Rôle |
|-----------|------|
| **Survey Scanner** | Augmente le multiplicateur de survey, qui amplifie l'ensemble du yield |
| **Mining Computer** | Ajoute un bonus % global sur tout le yield (ore, gas et ice) |
| **Cargo Coordinator** | Réduit le temps de déchargement en auto-cycle (seul le meilleur module compte) |
| **Mining Link** | En flotte, augmente le yield de tous les membres alliés (réservé aux vaisseaux de commandement) |
| **Mining Foreman Link** | Augmente le rendement des drones de minage déployés |

### Slot Bas — Optimisation du fitting

Ces modules n'ont pas d'effet direct sur le yield brut mais permettent d'optimiser la configuration globale.

| Catégorie | Rôle |
|-----------|------|
| **Mining Yield Amplifier** | Bonus % global supplémentaire sur le yield (cumulable avec le Mining Computer) |
| **Cargo Expander** | Augmente la capacité de cargo, réduisant la fréquence des déchargements |
| **Reaction Drive Injector / Mass-Reduced Frame** | Augmente la vitesse du vaisseau, réduisant le temps de déchargement en auto-cycle |
| **Co-Processor** | Augmente la capacité CPU, permettant d'équiper des modules plus nombreux ou plus puissants |
| **Reactor Control Unit** | Augmente la capacité Power Grid, même utilité que le Co-Processor |

---

## 5. Les drones de minage

Les drones de minage s'ajoutent au yield du vaisseau sans occuper de slot. Ils fonctionnent en parallèle des modules d'extraction. Le nombre de drones déployables dépend du skill **Mining Drone Operation** (1 slot par niveau, max 10) et de la capacité de drone bay du vaisseau.

Le yield des drones est amplifié par le skill **Drone Mining Yield** (+2% par niveau) et les modules **Mining Foreman Link**.

---

## 6. Les modes de minage

### 6.1 Ceinture simple (session manuelle)

Le joueur sélectionne une ceinture, une durée fixe (15 min / 30 min / 1h / 2h) et lance le cycle. À l'issue de la durée choisie, la session se termine et les ressources sont disponibles à la collecte. C'est le mode le plus simple, sans contrainte de setup.

Le rendement est calculé une fois au lancement selon la formule complète (vaisseau × modules × skills × multiplicateurs de ceinture) et appliqué sur toute la durée. Si le cargo se remplit avant la fin de la durée choisie, l'extraction s'arrête automatiquement au plafond.

### 6.2 Ceinture avec auto-cycle (Until Full)

En sélectionnant la durée **"Until Full"**, le joueur active le mode auto-cycle. La session se calcule pour remplir exactement le cargo libre, puis le vaisseau retourne automatiquement à la station, se décharge et repart miner — sans intervention du joueur.

Ce mode nécessite **Mining Automation L10** et est le plus efficace en rendement horaire effectif car il élimine les temps morts. Sa performance dépend du rapport entre le temps de minage et le temps de déchargement : plus le cargo est grand et/ou le déchargement rapide, meilleur est le rendement horaire.

Le joueur peut définir un nombre maximum de cycles (1 à 100) ou laisser la session tourner indéfiniment.

**Facteurs clés en auto-cycle :**
- Cargo effectif → détermine la quantité récoltée par cycle
- Vitesse du vaisseau → détermine le temps de déchargement
- Cargo Coordinator → réduit directement le temps de déchargement

### 6.3 Deep Space

Les ceintures de type Deep Space, Void Rift et Nebula se trouvent dans des zones non sécurisées où des PNJ chasseurs patrouillent. Chaque session de minage dans ces zones augmente la **signature sensorielle** du vaisseau — plus celle-ci est élevée, plus il est détectable et exposé aux attaques.

Le skill **Signature Masking** ralentit la croissance de cette signature. En cas d'attaque, le vaisseau peut fuir mais perd une partie de son cargo (**50% par défaut**, réduit par le skill **Emergency Warp Efficiency**).

Le deep space offre les multiplicateurs de rendement les plus élevés du jeu (×1.5 à ×2.5) et donne accès aux minerais endgame (Voidstone, Starium, Unicornium, Neurotoxin Cloud). La contrepartie est le risque permanent et la nécessité de gérer la signature entre chaque session.

### 6.4 Opérations de clan

Le minage en clan apporte deux couches de bonus additionnels.

**Bonus passifs de clan :** le clan peut investir dans des skills collectifs qui augmentent le yield de minage, le rendement des drones, le bonus de survey et la capacité de cargo de tous ses membres. Ces bonus s'appliquent automatiquement à chaque session individuelle. Ils sont amplifiés par le skill **Leadership** du leader de clan.

**Bonus de territoire :** si le clan contrôle un territoire, un bonus de yield de minage supplémentaire s'applique à tous les membres minant dans la zone contrôlée.

**Opérations coordonnées :** Les opérations coordonnées peuvent être lancées par un membre du clan. Elles se réalisent à plusieurs (conditions de nombre de membres impliqués, de niveau de minage minimum). Ces opérations peuvent de plus apporter une ressource supplémentaire, la `nexium shard` qui ne peut être trouvée qu'ici et qui est utilisée pour la construction des stations spatiales. Lors des opérations de clan, un vaisseau Hauler équipé de **Mining Links** peut augmenter le yield de tous les membres de la flotte alliée sans miner lui-même. C'est un rôle de soutien dédié qui nécessite le skill **Mining Foreman** et des vaisseaux de commandement pour être pleinement efficace.

Les ceintures de type Void Rift et Nebula endgame sont conçues pour être minées en groupe — la présence de chasseurs PNJ y rend le minage solo particulièrement risqué (données issues des pages du jeu, est-ce vraiment le cas ?).