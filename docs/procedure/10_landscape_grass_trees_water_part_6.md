# Landscape, grass, trees & water — partie 6

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Fin documentaire du module **06 - LANDSCAPE GRASS TREES WATER**.

Périmètre : étapes **640 à 644**.

Important : ces étapes sont des vérifications / validations documentaires sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 640 — Météo / ciel vérifiés

### Mods concernés

- `Picta Series - Improved Sky Meshes`
- `Obsidian Mountain Fogs`
- `Morning Fogs SSE - Thin Fog`
- `Vanilla And Morning Fogs SSE - Easy Seam Fixer`
- `Rainbows Remade - 4K Version`
- `Rainbows Remade - Hotfix Patch`
- `Rainbows Remade - No Initialization Notification Patch`
- `Shooting Stars SE`

### Plugins relevés

- `Obsidian Mountain Fogs.esm`
- `Morning Fogs SSE.esp`
- `Rainbows over Waterfalls.esp`
- `Rainbows over Waterfalls - Natural Waterfalls patch.esp`
- `Rainbows Remade.esp`
- `ShootingStars.esp`

### Résultat

- SKSE / menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : oui
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

### Décision

- Mods présents dans le bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Étape de vérification uniquement, sans nouvelle installation.
- Aucun ajout au compteur non-light.
- Vigilance conservée sur la coexistence `Rainbows over Waterfalls` / `Rainbows Remade`.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.

---

## Étape 641 — High Poly Canticle Tree + retouches Canticle Tree

### Mods concernés

- `High Poly Canticle Tree`
- `Canticle Tree Retexture - Bark`
- `Canticle Tree Retexture - Tree`
- `Canticle Tree Retexture - Draw Knife`

### Plugins relevés

- Aucun plugin relevé pour ce pack.

### Résultat

- SKSE / menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : oui
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

### Décision

- Mods présents dans le bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Étape de vérification uniquement, sans nouvelle installation.
- Aucun plugin ajouté.
- Aucun ajout au compteur non-light.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.

---

## Étape 642 — Detailing the Eldrich / Apocrypha

### Mod concerné

- `Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books`

### Plugins relevés

- Aucun plugin relevé pour ce mod.

### Résultat

- SKSE / menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : oui
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

### Décision

- Mod présent dans le bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Étape de vérification uniquement, sans nouvelle installation.
- Mod considéré comme visuel / textures-meshes Apocrypha.
- Aucun plugin ajouté.
- Aucun ajout au compteur non-light.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.

---

## Étape 643 — Vérification groupée fin du bloc 06

### Objectif

Valider en groupe les derniers mods déjà présents du bloc `[06 - LANDSCAPE GRASS TREES WATER]`, sans les traiter comme des installations individuelles.

### Mods concernés

#### Canticle Tree / Apocrypha

- `High Poly Canticle Tree`
- `Canticle Tree Retexture - Bark`
- `Canticle Tree Retexture - Tree`
- `Canticle Tree Retexture - Draw Knife`
- `Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books`

#### Objets / paysages / flore

- `Diverse Windmill Sails - Base Object Swapper`
- `Giant Crab Shells- Mihail's Shards of Immersion (SE-AE version)`
- `Sovngarde HD`
- `Remove Hanging Moss From Trees`
- `Remove Hanging Moss From Trees - FR`
- `Edmond's Official Unique Flowers and Plants SSE`
- `Better Dirt Cliffs and Alphas (2K)`
- `the Pebbles SE`
- `Man-Eater Giants - Base Object Swapper`
- `Man-Eater Giants - Base Object Swapper - FR`
- `Bloody Mammoth Carcasses- Mihail's Shards of Immersion (SE-AE version)`
- `Bloody Mammoth Carcasses - My optimized textures and Hi-Poly meshes SE by Xtudo`

### Plugins relevés

- `Diverse Windmill Sails.esp`
- `mihailcrabshell.esp`
- `Remove Hanging Moss From Trees.esp`
- `Unique Flowers & Plants.esp`
- `waterplants.esp`
- `ManEaterGiants.esp`
- `mihailbloodymammothbones.esp`

### Test de référence utilisé

Dernier test global déjà validé :

- SKSE / menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : oui
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

### Décision

- Validation groupée par continuité du dernier test SKSE/menu propre.
- Aucun nouveau fichier actif installé pendant cette étape.
- Aucun test SKSE supplémentaire demandé pour chaque mod visuel isolé.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.

### Dettes / surveillance

- Les mods `- FR` restent volontairement décochés ou en attente selon la méthode SKYFORGE.
- Surveiller les mods Base Object Swapper uniquement si anomalie visuelle en jeu.
- `Sovngarde HD`, `Better Dirt Cliffs and Alphas`, `the Pebbles SE`, Canticle Tree et Detailing the Eldrich sont considérés comme visuels / meshes / textures, sans plugin relevé dédié.
- Les éléments liés au paysage, à la flore et aux objets devront être revus lors de la passe finale LOD / DynDOLOD.
- Pas de génération DynDOLOD tant que le bloc complet et les choix LOD ne sont pas stabilisés.

---

## Étape 644 — Clôture provisoire du bloc 06

### Objectif

Clôturer provisoirement le bloc `[06 - LANDSCAPE GRASS TREES WATER]` sur la base des snapshots MO2 complets fournis après l’étape 640.

Cette clôture ne signifie pas que le bloc est définitivement figé pour les LOD, Seasons, parallax ou FOMOD complexes. Elle signifie que le bloc est stable pour continuer vers le bloc suivant.

### Sous-ensembles validés

- Terrain / grass / landscape.
- Water / waterfalls / splashes.
- Snow / ash / footprints / weather / sky.
- Fin de bloc : objets / flore / paysages.

### Plugins principaux relevés pour le bloc 06

Plugins visibles dans le panneau droit complet, notamment :

- `Grass Patch - All CC Mods.esp`
- `Landscape Fixes For Grass Mods.esp`
- `Complementary Grass Fixes.esp`
- `Landscape and Water Fixes.esp`
- `MajesticMountains.esp`
- `MajesticMountains_Landscape.esm`
- `HappyLittleTrees.esp`
- `Dilon Vul SSE.esp`
- `Cathedral - 3D Pine Grass.esp`
- `Origins Of Forest - 3D Forest Grass.esp`
- `Folkvangr - Grass and Landscape Overhaul.esp`
- `QW's Grass Patch 2.esp`
- `GKBWavesReborn.esp`
- `Water for ENB.esm`
- `Water for ENB (Shades of Skyrim).esp`
- `WIZ_FoscsF.esp`
- `WAVY Waterfalls Effect.esp`
- `StormLightning.esp`
- `Diverse Windmill Sails.esp`
- `mihailcrabshell.esp`
- `Remove Hanging Moss From Trees.esp`
- `Unique Flowers & Plants.esp`
- `waterplants.esp`
- `ManEaterGiants.esp`
- `mihailbloodymammothbones.esp`

### Décision

- Bloc 06 considéré comme stable pour avancer.
- Clôture provisoire validée.
- Aucun nouveau fichier actif installé pendant cette clôture.
- Aucun test SKSE supplémentaire demandé mod par mod.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.

### Dettes / reprises à prévoir

#### FOMOD à revoir plus tard

- `Complementary Grass Fixes`
- `Skyrim Landscape and Water Fixes`
- `Majestic Mountains Main`
- `Happy Little Trees`
- `Water for ENB - No Parallax`
- `Water in Wells`
- `Water Effects Brightness and Reflection Fix`
- `Natural Waterfalls`
- `Snowy Surfaces Sound Collision and Aesthetics`
- `Rainbows over Waterfalls - New Gen`
- `Animated Ice Floes`

#### Mods décochés / réserve

- `Atlantean Landscape -Complete- 2K`
- `Ultimate fix - SPID for Footprints`

#### LOD / DynDOLOD

À reprendre plus tard :

- `Happy Little Trees - Patch`
- `Natural Waterfalls`
- `Animated Ice Floes`
- arbres / paysages / waterfalls / ice floes
- cohérence finale avec DynDOLOD Resources et génération LOD

Aucune génération LOD ne doit être faite tant que les blocs villes, lieux, architecture et worldspaces ne sont pas stabilisés.

#### Seasons / parallax / complex grass

À revoir plus tard :

- pile grass ENB Complex Grass
- choix parallax paysage
- cohérence Seasons si Seasonal Landscapes est retenu plus tard
- cohérence avec Simplicity of Snow / Snowy Surfaces / Majestic Mountains
- Water for ENB et choix No Parallax

#### Traductions FR

Les mods `- FR` restent volontairement en attente selon la méthode SKYFORGE.

### État final bloc 06

- Bloc `[06 - LANDSCAPE GRASS TREES WATER]` : **clôturé provisoirement**.
- Dernière étape du bloc : **Étape 644**.
- Compteur ESP + ESM non-light : **138**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé**.
