# Landscape, grass, trees & water

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes classées dans le module **06 - LANDSCAPE GRASS TREES WATER**.

---

### 211. Ouverture du module 06

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Ouvrir officiellement le séparateur paysage / herbe / arbres / eau.

**Séparateur confirmé existant et vide :**

`[06 - LANDSCAPE GRASS TREES WATER]`

**Statut :**  
Étape 211 validée.

---

### 212. Terrain Fixes for CC Mods

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Installer les corrections de terrain liées aux contenus Creation Club.

**Mod installé :**

- `Terrain Fixes for CC Mods`

**Choix FOMOD :**

- `All CC Mods`

**Placement :**

```text
[06 - LANDSCAPE GRASS TREES WATER]
Terrain Fixes for CC Mods
```

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 212 validée.

---

### 213. Bloc paysage léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Installer les correctifs de paysage / herbe de base sans encore choisir de grass mod final.

**Déjà installé ailleurs :**

- `Lightened Skyrim - Base Object Swapper edition` est déjà installé dans `[02 - BUG FIXES & ENGINE PATCHES]`.

**Décision :**  
Ne pas réinstaller `Lightened Skyrim - Base Object Swapper edition`.

**Mods installés :**

- `Landscape Fixes For Grass Mods - A REINSTALL PLUS TARD`
- `Complementary Grass Fixes - A REINSTALL PLUS TARD`

**Choix Complementary Grass Fixes :**

- Core uniquement
- Aucun patch optionnel

**Patches différés pour plus tard selon les futurs choix :**

- JK’s Skyrim
- The Great Cities and Towns
- Arthmoor towns
- Helgen Reborn
- Moon and Star
- Expanded Towns and Cities
- Holds
- Verdant ou autre grass mod
- Ryn’s modules
- Cutting Room Floor
- JK’s Whiterun Outskirts
- Riften Extension

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 213 validée.

---

### 214. Contrôle plugins bloc herbe

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Vérifier que les plugins du bloc herbe sont actifs.

**Plugins confirmés actifs :**

- `Landscape Fixes For Grass Mods.esp`
- `Complementary Grass Fixes.esp`

**Statut :**  
Étape 214 validée.

---

### 215. Skyrim Landscape and Water Fixes

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Installer `Skyrim Landscape and Water Fixes` avec une sélection prudente de patches compatibles avec la base actuelle.

**Mod installé :**

- `Skyrim Landscape and Water Fixes - A REINSTALL PLUS TARD`

**Choix FOMOD validés :**

- Options générales : toutes décochées
- Patches Creation Club : autodétectés gardés
- Walkway Wall Mesh Fix : `SMIM`
- ELFX Interiors : `None`
- ELFX Exteriors : `None`
- Navigator : `Navigator ESL version`
- Unofficial Skyrim Modders Patch : coché
- Landscape Fixes for Grass Mods + Ghost of the Tribunal : coché

**Options non prises :**

- Parallax SLaWF meshes
- Free Crops
- Missing Lights Fixes
- v1.5.97.esm-s and USSEP
- Helgen Light Sources
- Water for ENB
- Majestic Mountains
- Lanterns of Skyrim II
- No Snow Under the Roof
- Helgen Reborn
- The Hunt for the Spectre
- Alternate Start
- Big combo Water for ENB

**Conflits constatés :**  
Normaux. SLaWF écrase certains fichiers SMIM / Assorted / Dlizzio.

**Décision :**  
Garder `Skyrim Landscape and Water Fixes` après les fixes précédents.

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK
- Plugins cochés : OK

**Statut :**  
Étape 215 validée.

---

### 216. Contrôle ordre module 06

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Contrôler l’ordre initial du module paysage / herbe / eau.

**Ordre confirmé :**

```text
[06 - LANDSCAPE GRASS TREES WATER]
Terrain Fixes for CC Mods
Landscape Fixes For Grass Mods
Complementary Grass Fixes - A REINSTALL PLUS TARD
Skyrim Landscape and Water Fixes - A REINSTALL PLUS TARD
```

**Statut :**  
Étape 216 validée.

---

### 217. Majestic Mountains

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Installer la base montagne / roches avec Majestic Mountains.

**Mod installé :**

- `Majestic Mountains - A REINSTALL PLUS TARD`

**Choix FOMOD :**

- Landscape ESM : `AE version`
- Moss Rocks ESL Version : décoché
- Effect Meshes : décoché
- Sun Direction : `None`

**Rappel décision :**  
Même en Skyrim SE 1.5.97, le choix `AE version` est correct car le contenu AE / Creation Club est conservé.

**Conflits constatés :**  
Normaux. Majestic Mountains écrase certains fichiers de SMIM / Dlizzio / SLaWF.

**Décision :**  
Garder `Majestic Mountains` après `SLaWF`.

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK
- Plugin coché : OK

**Statut :**  
Étape 217 validée.

---

### 218. Contrôle ordre après Majestic Mountains

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Contrôler l’ordre du bloc après ajout de Majestic Mountains.

**Ordre confirmé :**

```text
Terrain Fixes for CC Mods
Landscape Fixes For Grass Mods
Complementary Grass Fixes - A REINSTALL PLUS TARD
Skyrim Landscape and Water Fixes - A REINSTALL PLUS TARD
Majestic Mountains - A REINSTALL PLUS TARD
```

**Statut :**  
Étape 218 validée.

---

### 219. Atlantean Landscape

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Statut :**  
Suspendue proprement.

**Décision générale ajoutée :**

- Textures 2K par défaut si disponibles
- 1K : petits objets / optimisation
- 4K : éléments très visibles uniquement si justifié
- 8K : exclu par défaut

**Fichier choisi :**

- `Atlantean Landscape -Complete- 2K`

**Nom MO2 prévu :**

`Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD`

**Choix FOMOD retenus :**

- Patches : tous décochés
- Standard version
- Atlantean Snowy Bridges Fix : décoché
- Mountains Textures : `Brown with moss`

**Problème rencontré :**

`Atlantean Landscape.esp` requiert :

`Parallax TXST Fixes.esp`

**Décision :**

`Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD` est décoché.

Atlantean est différé pour un futur bloc :

`Parallax / Complex Terrain / ENB / textures paysage avancées`

**Test après décochage :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 219 suspendue proprement.

---

### 220. Happy Little Trees

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Installer la base arbres avec Happy Little Trees.

**Mods installés :**

- `Happy Little Trees - A REINSTALL PLUS TARD`
- `Happy Little Trees - HLT Patch`

**Fichiers pris :**

- `Happy Little Trees`
- `HLT Patch`

**Fichier non pris :**

- `Tree Billboards - HLT 1.01`

**Choix FOMOD :**

- `Default`

**Options Alternate non prises :**

- Alternate 1
- Alternate 2
- Alternate 3

**Raison :**  
Les alternatives neige seront revues plus tard avec le bloc neige / météo / ENB.

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK
- Plugin activé : OK

**Statut :**  
Étape 220 validée.

---

## État de pause

**Dernière étape validée :**  
`Étape 220 — Happy Little Trees`

**Module en cours :**  
`06 - LANDSCAPE GRASS TREES WATER`

**Reprise prévue :**  
`Étape 221 — Contrôle ordre + suite arbres / herbe / eau`

**Consignes maintenues :**

- Ne pas lancer LOOT.
- Ne pas toucher au panneau droit sauf master manquant.
- Garder Atlantean décoché.
- Continuer les tests courts SKSE / menu / masters / DLL / Overwrite.
