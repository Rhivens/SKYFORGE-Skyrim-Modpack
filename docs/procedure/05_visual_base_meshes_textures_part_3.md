# SKYFORGE — Procédure — 05 - VISUAL BASE MESHES TEXTURES — partie 3

Suite du module **05 - VISUAL BASE MESHES TEXTURES** après le snapshot post-578.

Ce fichier couvre les étapes **579 à 581**, avant l’ouverture officielle du sous-bloc `05.1 - LIGHTING EFFECTS & PARTICLES` à l’étape 582.

---

## Étape 579 — FYX meshes : cabanes, docks, charbon, barques

### Mods ajoutés

- **FYX - 3D Shack Kit Walls**
  - https://www.nexusmods.com/skyrimspecialedition/mods/67123
- **FYX - 3D Dock Ramp**
  - https://www.nexusmods.com/skyrimspecialedition/mods/64529
- **FYX - 3D Shack Kit Roofs**
  - https://www.nexusmods.com/skyrimspecialedition/mods/67488
- **FYX - 3D Coal in the Shovel**
  - https://www.nexusmods.com/skyrimspecialedition/mods/76422
- **FYX - RowBoat**
  - https://www.nexusmods.com/skyrimspecialedition/mods/78566

### Objectif

Poursuivre le module `05 - VISUAL BASE MESHES TEXTURES` avec un pack FYX léger : cabanes, rampes de docks, toits de cabanes, charbon dans les pelles et barques vanilla.

### Choix / décisions

- `FYX - 3D Shack Kit Walls` installé avec l’archive `Collision` si disponible.
- Aucun patch additionnel installé.
- Mods différés :
  - `FYX - Nordic Doors and Traps Collisions`
  - `FYX - Hrothgar Steps Collisions`
  - `Wood Wall Trap Mesh and UV Fix`
  - `Better Chests`
  - `Detailed Carriages`

### Résultat / test

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- SKSE/menu principal : OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide
- Compteur ESP + ESM non-light inchangé : `129`

### Statut

Étape 579 validée.

---

## Étape 580 — Collisions FYX + coffres

### Mods ajoutés

- **FYX - Nordic Doors and Traps Collisions**
  - https://www.nexusmods.com/skyrimspecialedition/mods/100295
- **FYX - Hrothgar Steps Collisions**
  - https://www.nexusmods.com/skyrimspecialedition/mods/100088
- **Wood Wall Trap Mesh and UV Fix**
  - https://www.nexusmods.com/skyrimspecialedition/mods/78686
- **Better Chests**
  - https://www.nexusmods.com/skyrimspecialedition/mods/71680

### Objectif

Poursuivre le module `05 - VISUAL BASE MESHES TEXTURES` avec corrections meshes/collisions FYX, correction du piège mural en bois et amélioration des coffres vanilla.

### Choix / décisions

- `Better Chests` installé en version `2K Optimised` si disponible.
- `Detailed Carriages` différé pour vérification de conflit avec `WiZkiD Carriages`.
- `College of Winterhold - Glowing Symbols` différé pour mini-bloc magie/Collège.
- `Skyrim’s Unique Drinks` différé pour mini-bloc nourriture/boissons.

### Résultat / test

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- SKSE/menu principal : OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide
- Compteur ESP + ESM non-light inchangé : `129`

### Statut

Étape 580 validée.

---

## Étape 581 — Carrioles détaillées + Collège + boissons

### Mods ajoutés

- **Detailed Carriages 2.0**
  - https://www.nexusmods.com/skyrimspecialedition/mods/89604
- **College of Winterhold - Glowing Symbols**
  - https://www.nexusmods.com/skyrimspecialedition/mods/108076
- **SUDs - Skyrim's Unique Drinks**
  - https://www.nexusmods.com/skyrimspecialedition/mods/85824
- **Wood Chopping Camera Glitch Fix**
  - https://www.nexusmods.com/skyrimspecialedition/mods/123984

### Choix FOMOD / options

#### Detailed Carriages 2.0

- CFTO Patch : non coché
- Convenient Carriages Patch : non coché
- Convenient Carriages - Helgen Reborn Patch : non coché
- Convenient Carriages - Spaghetti's Towns AIO Patch : non coché
- Convenient Carriages - Thuldor's Ivarstead Patch : non coché
- SMIM Patch : coché
- Markarth Outskirts Patch : non coché
- Note MO2 recommandée : `FOMOD A REVOIR PLUS TARD`

#### College of Winterhold - Glowing Symbols

- Option ENB Light intégrée acceptée si proposée dans le FOMOD.

#### SUDs - Skyrim's Unique Drinks

- Patch `Ryn's Sleeping Giant Inn` installé.
- Patch `JK's Interior of EEK's Whiterun / Bannered Mare` installé.
- Autres patchs différés.
- Note MO2 recommandée : `PATCHES A REVOIR PLUS TARD`.

### Plugins ajoutés

- `JKEEKBanneredMare - Skyrim Unique Drinks Patch.esp`
- `Ryn's Sleeping Giant Inn - Skyrim Unique Drinks Patch.esp`
- `SUDs.esp`
- `DetailedCarriages 2.0.esp`
- `DetailedCarriages 2.0 - SMIM Patch.esp`

### Résultat / test

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- SKSE/menu principal : OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide
- Compteur ESP + ESM non-light inchangé : `129`

### Statut

Étape 581 validée.

---

## État final du module 05 avant bascule 05.1

- Dernière étape du fichier : **581**
- Compteur ESP + ESM non-light : **129**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **non relancé**

À partir de l’étape 582, SKYFORGE ouvre officiellement le sous-bloc :

`[05.1 - LIGHTING EFFECTS & PARTICLES]`
