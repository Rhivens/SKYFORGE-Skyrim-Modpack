# Landscape, grass, trees & water — partie 4

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Suite du module **06 - LANDSCAPE GRASS TREES WATER**.

Périmètre : étapes **607 à 618**.

---

## Étape 607 — Complementary Grass Fixes FOMOD clarifié

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Complementary Grass Fixes - FOMOD A REVOIR PLUS TARD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Nom MO2 clarifié pour signaler que des choix FOMOD restent à revoir plus tard.

### Choix FOMOD actuellement retenus

- Core installé.
- Patches cochés :
  - `Ryn's Loreius Farm`
  - `Ryn's Sarethi Farm`
  - `Ryn's Snow-Shod Farm`
  - `Cutting Room Floor`

### Patches non cochés à revoir si mods ajoutés plus tard

- `Markarth Outskirts`
- `Ryn's Dragon Mounds`
- `Ryn's Farms`
- `Ryn's Merryfair Farm`
- `Ryn's Whiterun City Limits`
- `Riften Extension - Southwoods District`
- `JK's Whiterun Outskirts`

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins depuis le dernier test propre.

Étape 607 validée.

---

## Étape 608 — Skyrim Landscape and Water Fixes FOMOD clarifié

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Skyrim Landscape and Water Fixes - FOMOD A REVOIR PLUS TARD**

### Choix FOMOD retenus

- `v1.5.97 .esm's and USSEP` : coché.
- Creation Club patches visibles : cochés.
  - Alternative Armors - Elven Hunter
  - Farming
  - Fishing
  - Hendraheim
  - Myrwatch
  - Tundra Homestead
  - Vigil Enforcer Armor Set
- Walkway Wall Mesh Fix : `SMIM`.
- ELFX Interiors : `None`.
- ELFX Exteriors : `None`.
- Navigator : `Navigator ESL version`.
- Unofficial Skyrim Modders Patch : coché.
- No Harvesting Permission Dialogue : non coché.
- Complete Alchemy and Cooking Overhaul : non coché.

### À revoir plus tard

- Parallax SLaWF meshes.
- Free Crops.
- Missing Lights Fixes.
- Helgen Light Sources.
- Majestic Mountains patch.
- Water for ENB / gros combos de patches.
- Autres patches conditionnels selon mods futurs.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `131`

Étape 608 validée.

---

## Étape 609 — Majestic Mountains renommé / FOMOD à revoir

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Majestic Mountains - FOMOD A REVOIR PLUS TARD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement :
  - Ancien nom : `Majestic Mountains Main - A REINSTALLER PLUS TARD`.
  - Nouveau nom : `Majestic Mountains - FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD actuellement visibles / à conserver

- Landscape ESM : `Non AE version`.
- Moss Rocks ESL Version : non coché.
- Effect Meshes : non coché.
- Sun Direction : `None`.

### À revoir plus tard

- Moss Rocks.
- Effect Meshes.
- Sun Direction.
- LOD / DynDOLOD.
- Cohérence avec neige, ENB final et paysages.

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 609 validée comme clarification administrative.

---

## Étape 610 — Atlantean Landscape clarifié / différé

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Atlantean Landscape -Complete- 2K - DECOCHE - FOMODPILE LANDSCAPE A REVOIR PLUS TARD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement pour clarifier le statut.

### Décision

- Atlantean Landscape reste décoché pour l'instant.
- Raison : mod landscape structurant à revoir avec la pile complète :
  - Majestic Mountains.
  - Snow shaders / neige.
  - SLaWF parallax meshes.
  - Water for ENB.
  - Complex grass.
  - Patches landscape futurs.

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 610 validée comme clarification administrative.

---

## Étape 611 — Happy Little Trees renommé / FOMOD à revoir

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Happy Little Trees - FOMOD A REVOIR PLUS TARD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement :
  - Ancien nom : `Happy Little Trees - A REINSTALLER PLUS TARD`.
  - Nouveau nom : `Happy Little Trees - FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD actuellement visibles / à conserver

- Trees : `Pines only`.
- Tree size : non coché.

### À revoir plus tard

- Choix `All Trees` éventuel.
- Tree size.
- Patches.
- LOD / DynDOLOD.
- Cohérence avec arbres, paysages, neige et génération LOD.

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 611 validée comme clarification administrative.

---

## Étape 612 — Happy Little Trees Patch clarifié

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Happy Little Trees - Patch - A REVOIR AVEC LOD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement :
  - Ancien nom : `Happy Little Trees - Patch - A REVOIR APRES REINSTALLATION HLT`.
  - Nouveau nom : `Happy Little Trees - Patch - A REVOIR AVEC LOD`.

### Décision

- Le mod est un patch simple, sans FOMOD.
- Il reste à revoir lors de la passe arbres / LOD / DynDOLOD.

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 612 validée comme clarification administrative.

---

## Étape 613 — Water for ENB FOMOD clarifié

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Water for ENB - No Parallax - FOMOD A REVOIR PLUS TARD**

### Choix FOMOD retenus

- Water Style : `Shades of Skyrim for ENB`.
- Texture Resolution : `4K`.
- LOD Brightness : `Default`.
- Waterfalls Style : `Transparent`.
- Waterfalls Resolution : `4K`.
- Waterfalls Parallax : `No Parallax`.
- Customization : aucune option cochée.
- Flat World Map Framework SE : `None`.
- iNeed : `No Legacy iNeed Support`.

### Patches retenus

- JK's Bannered Mare.
- JK's Candlehearth Hall.
- JK's The Winking Skeever.
- Folkvangr.
- Generic Landscape Patch.
- JK's Ragged Flagon si actif/coché.
- Landscape Fixes For Grass Mods.
- Song of the Green (Auri Follower).

### Patches non retenus / à revoir plus tard

- Atlas Map Markers.
- Cabbage ENB.
- Rudy ENB for Cathedral Weathers.
- Lux / Lux-related patches.
- New Worldspaces.
- ENB final / options visuelles.
- LOD / DynDOLOD / eau distante.
- Patches conditionnels liés aux mods futurs.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `131`

Étape 613 validée.

---

## Étape 614 — Snowy Surfaces renommé / FOMOD à revoir

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod concerné

- **Snowy Surfaces Sound Collision and Aesthetics - FOMOD A REVOIR PLUS TARD**

### Action

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement :
  - Ancien nom : `Snowy Surfaces Sound Collision and Aesthetics - A REINSTALLER PLUS TARD`.
  - Nouveau nom : `Snowy Surfaces Sound Collision and Aesthetics - FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD actuellement visibles / à conserver

- Options : `Vanilla`.
- Meshes : `Vanilla Standard Meshes`.
- Seasonal Landscapes - Unfrozen patch : non coché.

### À revoir plus tard

- Majestic Mountains.
- Better Dynamic Snow / Simplicity of Snow.
- Atlantean Landscape.
- Complex Material / Parallax.
- Seasonal Landscapes.
- LOD / DynDOLOD.

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 614 validée comme clarification administrative.

---

## Étape 615 — Obsidian Mountain Fogs

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod ajouté

- **Obsidian Mountain Fogs**

### Placement

- Zone ciel / atmosphère du bloc 06.
- Placé après `Picta Series - Improved Sky Meshes`.
- Avant `Rainbows Remade - 4K Version`.

### Rôle

- Ajout de brouillards atmosphériques autour des montagnes.
- Améliore la profondeur visuelle des reliefs.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `132`

### Décision

- Le compteur ESP + ESM non-light passe de `131` à `132`.

Étape 615 validée.

---

## Étape 616 — Morning Fogs SSE

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod ajouté

- **Morning Fogs SSE**

### Placement

- Zone ciel / atmosphère du bloc 06.
- Placé après `Obsidian Mountain Fogs`.

### Rôle

- Ajout de brouillards matinaux au-dessus de certains lacs et rivières.
- Complète la couche atmosphérique après Obsidian Mountain Fogs.

### Non installés

- **Vanilla And Morning Fogs SSE - Easy Seam Fixer**
  - Raison : à revoir seulement si seams visibles en jeu ou pendant la passe eau/LOD.
- **Supreme and Volumetric Fog SE**
  - Raison : brouillard plus structurant, non empilé maintenant.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `133`

### Décision

- Le compteur ESP + ESM non-light passe de `132` à `133`.

Étape 616 validée.

---

## Étape 617 — Morning Fogs Seam Fix

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod ajouté

- **Vanilla And Morning Fogs SSE - Easy Seam Fixer**

### Placement

- Zone ciel / atmosphère du bloc 06.
- Placé après `Morning Fogs SSE`.

### Rôle

- Correction / réduction des seams visibles dans les brouillards vanilla et Morning Fogs SSE.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `133`

Étape 617 validée.

---

## Étape 618 — Splashes of Storms ENB Fix

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Mod ajouté

- **Splashes of Storms - ENB Fix**

### Mod installé

- **Rudy fix for Splashes of Storms and ENB**

### Choix FOMOD

- ENB Intensity : `OLD`.

### Placement

- Placé après `Splashes Of Storms`.

### Rôle

- Fix ENB pour Splashes of Storms.
- Permet un meilleur contrôle des particules via la section `[PARTICLE]` de l'ENB.

### Note méthode

Les mods volontairement décochés doivent porter une mention explicite :

```txt
DECOCHE - raison courte
```

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous les plugins attendus
- Overwrite : vide
- Compteur ESP + ESM non-light : `133`

Étape 618 validée.

---

## État final post-618

- Dernière étape validée/documentée : **Étape 618 — Splashes of Storms ENB Fix**.
- Module en cours : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Compteur ESP + ESM non-light : **133**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé**.
- Prochaine étape attendue : **Étape 619**.
