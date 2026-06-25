# SKYFORGE — Changelog / validation — partie 22

Période couverte : étapes **601 à 618**.

Cette partie documente la clôture provisoire du bloc `[05.1 - LIGHTING EFFECTS & PARTICLES]`, l’ouverture / clôture provisoire de `[05.2 - PARALLAX FRAMEWORK TEXTURES]`, puis la reprise du bloc `[06 - LANDSCAPE GRASS TREES WATER]` avec clarifications FOMOD et ajouts atmosphériques.

---

## Résumé global

### Étapes 601 à 603 — Fin provisoire Lighting Effects & Particles

- Ajout de `Enhanced Volumetric Lighting and Shadows - EVLaS`.
- Ajout de `Dripping Mist Reduction` et `SpiderWIP`.
- Clôture provisoire du bloc `[05.1 - LIGHTING EFFECTS & PARTICLES]`.
- `Spiderweb` renommé en `SpiderWIP`.
- Dettes conservées : Undead Creatures FOMOD, Rudy HQ Daedric Armor FOMOD, Animated Forge Water patch Embers XD.
- Compteur ESP + ESM non-light stable à **131**.

### Étapes 604 à 606 — Parallax Framework Textures

- Ouverture du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Ajout de `Dlizzio's Mesh Fixes - Parallax Mesh Patch`.
- Confirmation de `Auto Parallax` dans `[01 - SKSE PLUGINS & CORE UTILITIES]`, après `SkyPatcher - SE`.
- Clôture provisoire du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Plusieurs gros choix parallax / landscape restent différés.
- Compteur ESP + ESM non-light stable à **131**.

### Étapes 607 à 618 — Reprise Landscape / Grass / Trees / Water

- Clarifications administratives de plusieurs FOMOD / notes MO2 : `Complementary Grass Fixes`, `Skyrim Landscape and Water Fixes`, `Majestic Mountains`, `Atlantean Landscape`, `Happy Little Trees`, `Water for ENB`, `Snowy Surfaces`.
- Ajout atmosphérique : `Obsidian Mountain Fogs`, `Morning Fogs SSE`, `Vanilla And Morning Fogs SSE - Easy Seam Fixer`.
- Ajout du fix ENB `Splashes of Storms - ENB Fix`.
- Compteur ESP + ESM non-light : **131 → 132** à l’étape 615, puis **132 → 133** à l’étape 616 ; stable à **133** jusqu’à l’étape 618.

---

## Étapes validées

### Étape 601 — Enhanced Volumetric Lighting and Shadows EVLaS

- Bloc : `[05.1 - LIGHTING EFFECTS & PARTICLES]`.
- Mod ajouté : `Enhanced Volumetric Lighting and Shadows - EVLaS`.
- Version compatible Skyrim SE 1.5.97 / SKSE 2.0.20 installée.
- `EVLaS Skyrim Underside` non installé.
- Raison : underside à revoir plus tard avec DynDOLOD / LOD.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 602 — Dripping Mist Reduction + SpiderWIP

- Bloc : `[05.1 - LIGHTING EFFECTS & PARTICLES]`.
- Mods ajoutés :
  - `Dripping Mist Reduction`.
  - `SpiderWIP`.
- `Dripping Mist Reduction` : source Discrepancy / guide Nolvus Awakening ; téléchargement manuel Mega noté.
- `SpiderWIP` : overhaul léger des toiles d’araignée.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 603 — Clôture provisoire du bloc 05.1

- Bloc clôturé provisoirement : `[05.1 - LIGHTING EFFECTS & PARTICLES]`.
- Aucun nouveau mod installé.
- Snapshot ciblé du bloc vérifié.
- Correction de nom : `Spiderweb` renommé en `SpiderWIP`.
- Dettes conservées :
  - `Particle Lights For ENB SE - Undead Creatures - FOMOD A REVOIR PLUS TARD`.
  - `Rudy HQ - More Lights for ENB SE - Daedric Weapons and Armor - FOMOD ARMOR A REVOIR PLUS TARD`.
  - `Animated Forge Water - PATCH EMBERS XD A REVOIR PLUS TARD`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 604 — Ouverture du bloc 05.2 Parallax Framework Textures

- Bloc ouvert : `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Mod ajouté : `Dlizzio's Mesh Fixes - Parallax Mesh Patch`.
- Non installé : `Assorted Mesh Fixes main file`, déjà installé dans `[02 - BUG FIXES & ENGINE PATCHES]`.
- Non installé : `Assorted Mesh Fixes - parallax shit (unsupported)`.
- Raison : fichier explicitement unsupported ; à revoir seulement si la pile snow/parallax/landscape/ENB le justifie.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 605 — Auto Parallax

- Bloc : `[01 - SKSE PLUGINS & CORE UTILITIES]`.
- Mod ajouté : `Auto Parallax`.
- Placement : après `SkyPatcher - SE`.
- Rôle : plugin SKSE de gestion automatique du parallax, préparant les futurs ajouts du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 606 — Clôture provisoire du bloc 05.2

- Bloc clôturé provisoirement : `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Contenu validé : `Dlizzio's Mesh Fixes - Parallax Mesh Patch`.
- `Auto Parallax` confirmé dans `[01 - SKSE PLUGINS & CORE UTILITIES]`, après `SkyPatcher - SE`.
- Non installés / différés :
  - `Assorted Mesh Fixes - parallax shit (unsupported)`.
  - `Noble Skyrim`.
  - `Skyrim 202X`.
  - `SRP Architecture`.
  - `The Omnibus`.
  - `HD Remastered Landscapes`.
  - `Tomato's Complex Landscapes`.
  - `Skyrim 202X Complex Terrain Parallax`.
- Aucun nouveau mod installé à cette étape.
- Aucun changement depuis le dernier test propre.
- Compteur stable : **131**.

### Étape 607 — Complementary Grass Fixes FOMOD clarifié

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Complementary Grass Fixes - FOMOD A REVOIR PLUS TARD`.
- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Nom MO2 clarifié pour signaler que des choix FOMOD restent à revoir plus tard.
- Choix FOMOD actuellement retenus : Core installé ; patches `Ryn's Loreius Farm`, `Ryn's Sarethi Farm`, `Ryn's Snow-Shod Farm`, `Cutting Room Floor`.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 608 — Skyrim Landscape and Water Fixes FOMOD clarifié

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Skyrim Landscape and Water Fixes - FOMOD A REVOIR PLUS TARD`.
- Choix FOMOD retenus : version 1.5.97 / USSEP, patches Creation Club visibles, Walkway Wall Mesh Fix SMIM, Navigator ESL, Unofficial Skyrim Modders Patch.
- Plusieurs options parallax, lights, water / ENB et patches conditionnels restent à revoir plus tard.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 609 — Majestic Mountains renommé / FOMOD à revoir

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Majestic Mountains - FOMOD A REVOIR PLUS TARD`.
- Renommage MO2 uniquement.
- Ancien nom : `Majestic Mountains Main - A REINSTALLER PLUS TARD`.
- Nouveau nom : `Majestic Mountains - FOMOD A REVOIR PLUS TARD`.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 610 — Atlantean Landscape clarifié / différé

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Atlantean Landscape -Complete- 2K - DECOCHE - FOMODPILE LANDSCAPE A REVOIR PLUS TARD`.
- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement pour clarifier le statut.
- `Atlantean Landscape` reste décoché pour l’instant.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 611 — Happy Little Trees renommé / FOMOD à revoir

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Happy Little Trees - FOMOD A REVOIR PLUS TARD`.
- Renommage MO2 uniquement.
- Choix visibles à conserver : Trees `Pines only`, Tree size non coché.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 612 — Happy Little Trees Patch clarifié

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Happy Little Trees - Patch - A REVOIR AVEC LOD`.
- Renommage MO2 uniquement.
- Le mod est un patch simple, sans FOMOD.
- Il reste à revoir lors de la passe arbres / LOD / DynDOLOD.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 613 — Water for ENB FOMOD clarifié

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Water for ENB - No Parallax - FOMOD A REVOIR PLUS TARD`.
- Choix FOMOD retenus : Shades of Skyrim for ENB, textures 4K, waterfalls transparent 4K, No Parallax, aucune customization, FWMF None, iNeed No Legacy Support.
- Patches retenus : JK’s Bannered Mare, Candlehearth Hall, Winking Skeever, Folkvangr, Generic Landscape Patch, JK’s Ragged Flagon si actif/coché, Landscape Fixes For Grass Mods, Song of the Green.
- Plusieurs patches ENB, Lux, New Worldspaces, Atlas Map Markers et options LOD/eau distante restent différés.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 614 — Snowy Surfaces renommé / FOMOD à revoir

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod concerné : `Snowy Surfaces Sound Collision and Aesthetics - FOMOD A REVOIR PLUS TARD`.
- Renommage MO2 uniquement.
- Choix visibles à conserver : Options `Vanilla`, Meshes `Vanilla Standard Meshes`, Seasonal Landscapes - Unfrozen patch non coché.
- Test non relancé : aucun changement réel de fichiers/plugins.

### Étape 615 — Obsidian Mountain Fogs

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod ajouté : `Obsidian Mountain Fogs`.
- Placement : zone ciel / atmosphère du bloc 06 ; après `Picta Series - Improved Sky Meshes`, avant `Rainbows Remade - 4K Version`.
- Rôle : brouillards atmosphériques autour des montagnes, profondeur visuelle des reliefs.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur : **131 → 132**.

### Étape 616 — Morning Fogs SSE

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod ajouté : `Morning Fogs SSE`.
- Placement : zone ciel / atmosphère du bloc 06, après `Obsidian Mountain Fogs`.
- Rôle : brouillards matinaux au-dessus de certains lacs et rivières.
- Non installés : `Vanilla And Morning Fogs SSE - Easy Seam Fixer` et `Supreme and Volumetric Fog SE`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur : **132 → 133**.

### Étape 617 — Morning Fogs Seam Fix

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod ajouté : `Vanilla And Morning Fogs SSE - Easy Seam Fixer`.
- Placement : zone ciel / atmosphère du bloc 06, après `Morning Fogs SSE`.
- Rôle : correction / réduction des seams visibles dans les brouillards vanilla et Morning Fogs SSE.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **133**.

### Étape 618 — Splashes of Storms ENB Fix

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mod ajouté : `Splashes of Storms - ENB Fix`.
- Mod installé : `Rudy fix for Splashes of Storms and ENB`.
- Choix FOMOD : `ENB Intensity (OLD)`.
- Placement : après `Splashes Of Storms`.
- Rôle : fix ENB pour Splashes of Storms ; meilleur contrôle des particules via `[PARTICLE]` de l’ENB.
- Note méthode : les mods volontairement décochés doivent porter une mention explicite `DECOCHE - raison courte`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **133**.

---

## État final post-618

- Dernière étape validée/documentée : **Étape 618 — Splashes of Storms ENB Fix**.
- Prochaine étape attendue : **Étape 619**.
- Compteur ESP + ESM non-light : **133**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé**.
