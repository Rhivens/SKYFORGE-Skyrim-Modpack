# Landscape, grass, trees & water — partie 5

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Suite du module **06 - LANDSCAPE GRASS TREES WATER**.

Périmètre : étapes **619 à 639**.

---

## Étape 619 — Nettoyage noms bloc 06

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Actions

- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement.

### Corrections effectuées

- `Majestic Mountains - FOMOD A REVOIR PLUS TARD`
- `Happy Little Trees - FOMOD A REVOIR PLUS TARD - FR`
- `Atlantean Landscape -Complete- 2K - DECOCHE - FOMOD-PILE LANDSCAPE A REVOIR PLUS TARD`
- `Atlantean Landscape -Complete- 2K - DECOCHE - FOMOD-PILE LANDSCAPE A REVOIR PLUS TARD - FR`

### Test

- Non relancé.
- Raison : aucun changement réel de fichiers/plugins.

Étape 619 validée comme clarification administrative.

---

## Étape 620 — Pack eau mesh-only

### Bloc

`[06 - LANDSCAPE GRASS TREES WATER]`

### Ajoutés

- `Water in Wash Basins - Mesh-only Replacer`
- `Water in Wells - mesh-only animated wells - FOMOD A REVOIR PLUS TARD`
- `Water Effects Brightness and Reflection Fix - FOMOD A REVOIR PLUS TARD`

### Placement

- Après `Water for ENB - No Parallax - FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD

#### Water in Wells

- Tous les types de puits installés en version No Parallax.
- Options Parallax non installées.
- À revoir plus tard si la pile water/parallax est finalisée.

#### Water Effects Brightness and Reflection Fix

- Vanilla DynDOLOD meshes : non.
- Nchardak waterfall fix : oui.
- Skyrim Particle Patch fix : non, à revoir plus tard.

### Non installé

- `Water Effects Brightness and Reflection Fix - Realistic Water Two Patch`
  - Raison : SKYFORGE utilise `Water for ENB`, pas `Realistic Water Two`.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `133`

Étape 620 validée.

---

## Étape 621 — Wade In Water

### Ajoutés

- `Loki's Wade In Water`
- `Wade In Water Redone`

### Placement

- Après `Water in Wells - mesh-only animated wells - FOMOD A REVOIR PLUS TARD`.

### Rôle

- Ajout d’un ralentissement cohérent des acteurs lorsqu’ils se déplacent dans l’eau.
- `Wade In Water Redone` apporte une gestion SKSE plus propre.

### Vigilance

- Mod sensible SKSE/DLL.
- Version compatible Skyrim SE 1.5.97 / SKSE 2.0.20 retenue.
- Aucun message DLL au test.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `134`

Étape 621 validée. Le compteur passe de `133` à `134`.

---

## Étape 622 — Splashes Of Skyrim

### Ajouté

- `Splashes Of Skyrim`

### Version

- Version `1.5.0` retenue.
- Raison : version plus récente que la 1.4.0 utilisée comme référence Nolvus Awakening, avec correctifs ultérieurs.
- Vérification : lancement SKSE/menu sans message DLL.

### Placement

- Après `Water Effects Brightness and Reflection Fix - FOMOD A REVOIR PLUS TARD`.

### Rôle

- Ajout d’éclaboussures / ripples / effets d’impact sur l’eau pour projectiles.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `134`

Étape 622 validée.

---

## Étape 623 — Natural Waterfalls

### Ajouté

- `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`

### Placement

- Après `Splashes Of Skyrim`.
- Avant `WAVY Waterfalls Effect`.

### Choix FOMOD

- Meshes : Brighter Foam.
- Texture Size : 4K.
- Blackreach : non coché.
- Sound FX : non coché.
  - Raison : remplace les sons waterfalls/rivers/rapids via plugin ESL, à revoir avec audio/eau.
- Volcanic Mineral Pools : non coché.
- Disable Jumping Fish : non coché.
- Water Overhaul : non coché.
  - Raison : SKYFORGE utilise Water for ENB.
- ERM patches : non cochés.

### Patches retenus

- `Skyrim Landscape and Water Fixes (SLaWF)`.
- `Water for ENB (Shades of Skyrim)`.

### Patches non retenus

- Realistic Water Two.
- Water for ENB Mineral Teal / Nordic Blue / Tropical Green.
- Aonghus House.
- Fallen Trees.
- Half Moon Creek.
- Shadows Over Ilinalta.
- The Forgotten City.
- Unique Locations Riverwood Forest.

### À revoir plus tard

- WiZkiD Meshes.
- Blackreach.
- Sound FX.
- Volcanic Mineral Pools.
- Water Overhaul.
- ERM / Parallax / Complex Parallax.
- Patches lieux/mondes futurs.
- LOD / DynDOLOD.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 623 validée. Le compteur passe de `134` à `135`.

---

## Étape 624 — FYX Water Mesh Optimization

### Ajouté

- `FYX - Water Mesh Optimization C 128`

### Placement

- Après `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`.
- Avant / autour de `WAVY Waterfalls Effect`.

### Rôle

- Optimisation des meshes d’eau.
- Variante C 128 retenue, identique au choix observé dans Nolvus Awakening.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 624 validée.

---

## Étape 625 — WAVY Waterfalls Effect vérifié

### Mods concernés

- `WAVY Waterfalls Effect`
- `WAVY Waterfalls Effect - FR`

### Action

- Réinstallation du mod effectuée.
- Aucun FOMOD détecté.
- Action MO2 : Replace.

### Décision

- Aucun choix FOMOD à revoir.
- Nom conservé sans mention `FOMOD A REVOIR PLUS TARD`.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 625 validée.

---

## Étape 626 — Rainbows over Waterfalls

### Ajouté

- `Rainbows over Waterfalls - FOMOD A REVOIR PLUS TARD`

### Version

- `Rainbows Over Waterfalls - New Gen 1.7`.
- Version retenue car compatible avec SKSE / Papyrus Extender déjà présents dans SKYFORGE.

### Placement

- Après `WAVY Waterfalls Effect`.
- Après `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD

- Rainbows over Waterfalls : coché.
- Rainbows over interiors : non coché.
- Rainbows over player homes : non coché.
- Fainter rainbows : non coché.
- pfftt : non coché.
- Lux : non coché.
- Natural Waterfalls : coché.
- BS Bruma : non coché.
- Falls of Ivarstead : non coché.

### À revoir plus tard

- Lux patch.
- BS Bruma addon.
- Falls of Ivarstead addon.
- Intensité visuelle / fainter rainbows après test en jeu.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 626 validée.

---

## Étape 627 — TMD The Rift Leaves

### Ajouté

- `TMD The Rift Leaves - 2K`

### Placement

- Après `WAVY Waterfalls Effect`.
- Avant `Rainbows over Waterfalls - FOMOD A REVOIR PLUS TARD`.

### Choix

- Version 2K retenue.

### Non installés

- `TMD The Rift Leaves - Darker Reflection`
  - Raison : à revoir seulement si les reflets paraissent trop clairs en jeu.
- `TMD The Rift Leaves - Seasons Patch`
  - Raison : Seasons non finalisé dans SKYFORGE.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 627 validée.

---

## Étape 628 — Animated Ice Floes

### Ajouté

- `Animated Ice Floes - FOMOD-LOD A REVOIR PLUS TARD`

### Choix FOMOD

- Dynamic Meshes Options : None.
  - Note : installe les Dynamic Vanilla meshes.
- Seasons of Skyrim Patch : non coché.
- Wells With Real Water - Helarchen Creek Patch : non coché.

### Non installés / différés

- `Animated Ice Floes - LOD textures Patch`.
  - Raison : à revoir avec DynDOLOD / LOD.
- Patches de meshes glace spécifiques.
  - Raison : pile glace non finalisée.
- Seasons patch.
  - Raison : Seasons non finalisé.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `135`

Étape 628 validée.

---

## Étape 629 — Better Dynamic Ash SE

### Ajouté

- `Better Dynamic Ash SE`

### Placement

- Après `Animated Ice Floes - FOMOD-LOD A REVOIR PLUS TARD`.

### Rôle

- Gestion dynamique des surfaces couvertes de cendre sur Solstheim.
- Cohérent avec la transition glace / neige / ash du bloc 06.

### Non installé

- `Nature of the Wild Lands - Better Dynamic Ash Patch`.
  - Raison : `Nature of the Wild Lands` non installé/validé dans SKYFORGE.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `137`

### Note

- Le compteur ESP + ESM non-light passe de `135` à `137`.
- +2 plugins non-light ajoutés.
- À surveiller lors des prochaines étapes, mais marge encore confortable.

Étape 629 validée.

---

## Étape 630 — Footprints base + ENB

### Ajoutés

- `Footprints`
- `Footprints - ENB`

### Placement

- Après `Better Dynamic Ash SE`.

### Choix

- Main file : `Footprints 1.6.1`.
- Optional file : `Footprints - ENB`.
- Installation séparée, pas de merge, pour garder le correctif ENB visible.

### Rôle

- Ajout de traces de pas sur surfaces compatibles.
- Correctif ENB pour éviter les problèmes d’effets sur decals alpha transparents.

### Non installés / différés

- SPID for Footprints.
- SPID for Footprints fix.
- Ultimate fix - SPID for Footprints.
- Alternative Design.
- heels addon.
- kids addon.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

Étape 630 validée. Le compteur passe de `137` à `138`.

---

## Étape 631 — SPID for Footprints

### Ajouté

- `SPID for Footprints`

### Placement

- Après `Footprints`.
- Après `Footprints - ENB`.

### Ordre

- `Footprints`
- `Footprints - ENB`
- `SPID for Footprints`

### Rôle

- Distribution des effets Footprints via SPID.
- Remplace la logique cloak spell originale par une distribution plus adaptée à un gros modpack.

### Non installés / différés

- SPID for Footprints fix.
- Ultimate fix - SPID for Footprints.
- Footprints - Alternative Design.
- Footprints - heels addon.
- Kids addon.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

Étape 631 validée.

---

## Étape 632 — Ultimate fix - SPID for Footprints différé

### Installé mais décoché

- `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`

### Choix FOMOD provisoire

- choose version : original.
- fixed inis / SPID and KID : non coché.

### Placement

- Après `SPID for Footprints`.

### Raison du différé

- FOMOD à revoir plus tard.
- La page Nexus indique d’utiliser la fonction `Reset counts` dans le MCM après installation.
- À reprendre lors d’une passe Footprints en jeu / MCM.

### Impact

- Aucun impact actif tant que le mod reste décoché.
- Pas de test nécessaire.

### Décision

- Réserve installée proprement.
- Pile Footprints active actuelle conservée :
  - `Footprints`
  - `Footprints - ENB`
  - `SPID for Footprints`

---

## Étape 633 — SPID for Footprints fix

### Ajouté

- `SPID for Footprints fix`

### Placement

- Après `SPID for Footprints`.
- Avant `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`.

### Ordre actif

- `Footprints`
- `Footprints - ENB`
- `SPID for Footprints`
- `SPID for Footprints fix`

### Réserve décochée

- `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`

### Non installés / différés

- Footprints - SPID - Player Footprints.
- Footprints - Sand Patch.
- Footprints - Vigilant Patch.
- Footprints - Soul Cairn Patch.
- Footprints - Gray Cowl of Nocturnal Patch.
- Footprints - Beyond Skyrim Bruma Patch.
- Footprints - heels addon.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

Étape 633 validée.

---

## Étape 634 — SPID for Footprints - Player Footprints Fix

### Ajouté

- `SPID for Footprints - Player Footprints Fix`

### Placement

- Après `SPID for Footprints fix`.
- Avant `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`.

### Ordre actif

- `Footprints`
- `Footprints - ENB`
- `SPID for Footprints`
- `SPID for Footprints fix`
- `SPID for Footprints - Player Footprints Fix`

### Réserve décochée

- `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`

### Non installés / différés

- Footprints Sand Patch.
- Footprints - heels addon.
- Vigilant footprints patch.
- Soul Cairn footprints patch.
- Gray Cowl / Bruma / autres patches worldspaces.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

Étape 634 validée.

---

## Étape 635 — Footprints Sand Patch différé

### Non installé

- `Footprints Sand Patch`

### Raison

- Page Nexus signalée comme deprecated.
- Remplacé / succédé par `Footprints - Alternative Design`.
- À revoir lors d’une passe Footprints visuelle complète.

### Décision

- Ne pas installer maintenant.
- Pile Footprints active conservée :
  - `Footprints`
  - `Footprints - ENB`
  - `SPID for Footprints`
  - `SPID for Footprints fix`
  - `SPID for Footprints - Player Footprints Fix`

### Réserve décochée conservée

- `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`

---

## Étape 637 — Snowy Surfaces vérifié

### Vérifié

- `Snowy Surfaces Sound Collision and Aesthetics - FOMOD A REVOIR PLUS TARD`

### Statut

- Déjà installé.
- Nom conforme.
- Conservé en `FOMOD A REVOIR PLUS TARD`.

### Choix FOMOD actuellement retenus

- Options : Vanilla.
- Meshes : Vanilla Standard Meshes.
- Seasonal Landscapes Unfrozen patch : non coché.

### À revoir plus tard

- Majestic Mountains.
- Better Dynamic Snow / snow stack.
- Simplicity of Snow éventuel.
- Atlantean / parallax landscape.
- Complex Material / parallax.
- Seasons.
- LOD / DynDOLOD.

### Impact

- Aucun changement MO2.
- Aucun test nécessaire.

Étape 637 validée.

---

## Étape 638 — Storm Lightning vérifié

### Vérifié

- `Storm Lightning for SSE and VR (Minty Lightning 2019)`

### Statut

- Déjà installé.
- Nom conforme.

### Impact

- Aucun changement MO2.
- Aucun test nécessaire.

Étape 638 validée.

---

## Étape 639 — ETHEREAL CLOUDS vérifié

### Vérifié

- `ETHEREAL CLOUDS - Special Edition`

### Statut

- Déjà installé.
- Nom conforme.

### Impact

- Aucun changement MO2.
- Aucun test nécessaire.

Étape 639 validée.

---

## État final post-639

- Dernière étape validée/documentée : **Étape 639 — ETHEREAL CLOUDS vérifié**.
- Prochaine étape attendue : **Étape 640**.
- Compteur ESP + ESM non-light : **138**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé pendant les étapes 619 à 639**.
