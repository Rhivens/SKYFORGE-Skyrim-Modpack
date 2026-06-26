# SKYFORGE — Changelog / validation — partie 23

Période couverte : étapes **619 à 639**.

Cette partie documente la poursuite du bloc `[06 - LANDSCAPE GRASS TREES WATER]`, avec nettoyage administratif, pile eau / cascades, correctifs Footprints, glace / cendre, puis vérifications finales météo / ciel.

---

## Résumé global

### Étapes 619 à 628 — Eau, cascades, reflets et glace

- Nettoyage de noms MO2 dans le bloc 06, sans changement réel de fichiers/plugins.
- Ajout du pack eau mesh-only : `Water in Wash Basins`, `Water in Wells`, `Water Effects Brightness and Reflection Fix`.
- Ajout de `Loki's Wade In Water` + `Wade In Water Redone`, avec vigilance SKSE/DLL validée.
- Ajout de `Splashes Of Skyrim` version 1.5.0.
- Ajout de `Natural Waterfalls`, avec patches `SLaWF` et `Water for ENB (Shades of Skyrim)`.
- Ajout / vérification de `FYX - Water Mesh Optimization C 128`, `WAVY Waterfalls Effect`, `Rainbows over Waterfalls`, `TMD The Rift Leaves - 2K`, `Animated Ice Floes`.
- Compteur ESP + ESM non-light : **133 → 134** à l’étape 621, **134 → 135** à l’étape 623, puis stable jusqu’à l’étape 628.

### Étapes 629 à 635 — Cendre dynamique et Footprints

- Ajout de `Better Dynamic Ash SE`.
- Ajout de la pile Footprints active : `Footprints`, `Footprints - ENB`, `SPID for Footprints`, `SPID for Footprints fix`, `SPID for Footprints - Player Footprints Fix`.
- `Ultimate fix - SPID for Footprints` installé mais **décoché** en réserve, avec FOMOD / MCM `Reset counts` à reprendre plus tard.
- `Footprints Sand Patch` non installé car deprecated / remplacé par `Footprints - Alternative Design`.
- Compteur ESP + ESM non-light : **135 → 137** à l’étape 629, **137 → 138** à l’étape 630, puis stable jusqu’à l’étape 635.

### Étapes 637 à 639 — Vérifications neige / orages / nuages

- `Snowy Surfaces Sound Collision and Aesthetics` vérifié, déjà installé, nom conforme.
- `Storm Lightning for SSE and VR (Minty Lightning 2019)` vérifié, déjà installé, nom conforme.
- `ETHEREAL CLOUDS - Special Edition` vérifié, déjà installé, nom conforme.
- Aucun changement MO2 actif sur ces vérifications.

---

## Étapes validées

### Étape 619 — Nettoyage noms bloc 06

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Aucun nouveau fichier installé.
- Aucun changement plugin.
- Renommage MO2 uniquement.
- Corrections effectuées sur les noms `Majestic Mountains`, `Happy Little Trees - FR`, `Atlantean Landscape` et `Atlantean Landscape - FR`.
- Test non relancé : aucun changement réel de fichiers/plugins.
- Étape validée comme clarification administrative.

### Étape 620 — Pack eau mesh-only

- Bloc : `[06 - LANDSCAPE GRASS TREES WATER]`.
- Mods ajoutés :
  - `Water in Wash Basins - Mesh-only Replacer`.
  - `Water in Wells - mesh-only animated wells - FOMOD A REVOIR PLUS TARD`.
  - `Water Effects Brightness and Reflection Fix - FOMOD A REVOIR PLUS TARD`.
- Placement : après `Water for ENB - No Parallax - FOMOD A REVOIR PLUS TARD`.
- `Water in Wells` : tous les types de puits installés en version No Parallax ; options Parallax non installées.
- `Water Effects Brightness and Reflection Fix` : Nchardak waterfall fix coché ; vanilla DynDOLOD meshes et Skyrim Particle Patch fix non cochés.
- Patch `Realistic Water Two` non installé, SKYFORGE utilisant `Water for ENB`.
- Test SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide.
- Compteur : **133**.

### Étape 621 — Wade In Water

- Mods ajoutés : `Loki's Wade In Water`, `Wade In Water Redone`.
- Placement : après `Water in Wells - mesh-only animated wells - FOMOD A REVOIR PLUS TARD`.
- Rôle : ralentissement cohérent des acteurs dans l’eau ; gestion SKSE plus propre via Redone.
- Version compatible Skyrim SE 1.5.97 / SKSE 2.0.20 retenue.
- Test SKSE/menu principal OK, aucun message DLL.
- Compteur : **133 → 134**.

### Étape 622 — Splashes Of Skyrim

- Mod ajouté : `Splashes Of Skyrim`.
- Version retenue : **1.5.0**, plus récente que la 1.4.0 de référence Nolvus Awakening.
- Placement : après `Water Effects Brightness and Reflection Fix - FOMOD A REVOIR PLUS TARD`.
- Rôle : éclaboussures / ripples / impacts sur l’eau.
- Vigilance SKSE/DLL validée au lancement.
- Compteur stable : **134**.

### Étape 623 — Natural Waterfalls

- Mod ajouté : `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`.
- Placement : après `Splashes Of Skyrim`, avant `WAVY Waterfalls Effect`.
- Choix FOMOD retenus : `Brighter Foam`, textures `4K`.
- Options non cochées : Blackreach, Sound FX, Volcanic Mineral Pools, Disable Jumping Fish, Water Overhaul, ERM patches.
- Patches retenus : `Skyrim Landscape and Water Fixes (SLaWF)`, `Water for ENB (Shades of Skyrim)`.
- Nombreux patches worldspaces / parallax / Lux / Water for ENB variantes différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur : **134 → 135**.

### Étape 624 — FYX Water Mesh Optimization

- Mod ajouté : `FYX - Water Mesh Optimization C 128`.
- Placement : après `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`, avant / autour de `WAVY Waterfalls Effect`.
- Variante C 128 retenue, cohérente avec Nolvus Awakening.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **135**.

### Étape 625 — WAVY Waterfalls Effect vérifié

- Mods concernés : `WAVY Waterfalls Effect`, `WAVY Waterfalls Effect - FR`.
- Réinstallation effectuée ; aucun FOMOD détecté ; action MO2 : Replace.
- Nom conservé sans mention `FOMOD A REVOIR PLUS TARD`.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **135**.

### Étape 626 — Rainbows over Waterfalls

- Mod ajouté : `Rainbows over Waterfalls - FOMOD A REVOIR PLUS TARD`.
- Version retenue : `Rainbows Over Waterfalls - New Gen 1.7`.
- Placement : après `WAVY Waterfalls Effect` et après `Natural Waterfalls - FOMOD A REVOIR PLUS TARD`.
- Options cochées : `Rainbows over Waterfalls`, `Natural Waterfalls`.
- Options non cochées : interiors, player homes, fainter rainbows, pfftt, Lux, BS Bruma, Falls of Ivarstead.
- À revoir : Lux patch, BS Bruma, Falls of Ivarstead, intensité visuelle / fainter rainbows.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **135**.

### Étape 627 — TMD The Rift Leaves

- Mod ajouté : `TMD The Rift Leaves - 2K`.
- Placement : après `WAVY Waterfalls Effect`, avant `Rainbows over Waterfalls - FOMOD A REVOIR PLUS TARD`.
- Version 2K retenue.
- `Darker Reflection` non installé, à revoir si les reflets paraissent trop clairs.
- `Seasons Patch` non installé, Seasons non finalisé.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **135**.

### Étape 628 — Animated Ice Floes

- Mod ajouté : `Animated Ice Floes - FOMOD-LOD A REVOIR PLUS TARD`.
- Choix FOMOD : Dynamic Meshes Options `None`, ce qui installe les Dynamic Vanilla meshes.
- Seasons patch et Wells With Real Water - Helarchen Creek Patch non cochés.
- LOD textures patch et patches glace spécifiques différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **135**.

### Étape 629 — Better Dynamic Ash SE

- Mod ajouté : `Better Dynamic Ash SE`.
- Placement : après `Animated Ice Floes - FOMOD-LOD A REVOIR PLUS TARD`.
- Rôle : surfaces couvertes de cendre sur Solstheim.
- Patch `Nature of the Wild Lands - Better Dynamic Ash Patch` non installé, dépendance non validée dans SKYFORGE.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur : **135 → 137**.
- Note : +2 plugins non-light ajoutés, marge encore confortable.

### Étape 630 — Footprints base + ENB

- Mods ajoutés : `Footprints`, `Footprints - ENB`.
- Placement : après `Better Dynamic Ash SE`.
- Main file : `Footprints 1.6.1`.
- Optional file : `Footprints - ENB`.
- Installation séparée, sans merge, pour garder le correctif ENB visible.
- SPID / fixes / Alternative Design / heels / kids différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur : **137 → 138**.

### Étape 631 — SPID for Footprints

- Mod ajouté : `SPID for Footprints`.
- Placement : après `Footprints` et `Footprints - ENB`.
- Ordre actif : `Footprints`, `Footprints - ENB`, `SPID for Footprints`.
- Rôle : distribution Footprints via SPID, meilleure logique pour gros modpack.
- Fixes complémentaires et addons différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **138**.

### Étape 632 — Ultimate fix - SPID for Footprints différé

- Installé mais décoché : `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`.
- Choix FOMOD provisoire : version `original`; fixed inis / SPID and KID non cochés.
- Placement : après `SPID for Footprints`.
- Raison du différé : FOMOD à revoir ; MCM `Reset counts` à utiliser après installation active.
- Aucun impact actif tant que le mod reste décoché.

### Étape 633 — SPID for Footprints fix

- Mod ajouté : `SPID for Footprints fix`.
- Placement : après `SPID for Footprints`, avant `Ultimate fix - SPID for Footprints - DECOCHE - FOMOD ET MCM RESET COUNTS A FAIRE PLUS TARD`.
- Ordre actif : `Footprints`, `Footprints - ENB`, `SPID for Footprints`, `SPID for Footprints fix`.
- Patches Sand / Vigilant / Soul Cairn / Gray Cowl / Bruma / heels différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **138**.

### Étape 634 — SPID for Footprints - Player Footprints Fix

- Mod ajouté : `SPID for Footprints - Player Footprints Fix`.
- Placement : après `SPID for Footprints fix`, avant la réserve décochée `Ultimate fix`.
- Ordre actif : `Footprints`, `Footprints - ENB`, `SPID for Footprints`, `SPID for Footprints fix`, `SPID for Footprints - Player Footprints Fix`.
- Footprints Sand Patch, heels addon et worldspace patches différés.
- Test SKSE/menu principal OK, Overwrite vide.
- Compteur stable : **138**.

### Étape 635 — Footprints Sand Patch différé

- `Footprints Sand Patch` non installé.
- Raison : page Nexus signalée comme deprecated ; remplacé / succédé par `Footprints - Alternative Design`.
- À revoir lors d’une passe Footprints visuelle complète.
- Pile Footprints active conservée.

### Étape 637 — Snowy Surfaces vérifié

- Mod vérifié : `Snowy Surfaces Sound Collision and Aesthetics - FOMOD A REVOIR PLUS TARD`.
- Déjà installé, nom conforme, statut conservé.
- Choix FOMOD actuellement retenus : Options `Vanilla`, Meshes `Vanilla Standard Meshes`, Seasonal Landscapes Unfrozen patch non coché.
- À revoir : Majestic Mountains, Better Dynamic Snow / snow stack, Simplicity of Snow, Atlantean / parallax landscape, Complex Material / parallax, Seasons, LOD / DynDOLOD.
- Aucun changement MO2, aucun test nécessaire.

### Étape 638 — Storm Lightning vérifié

- Mod vérifié : `Storm Lightning for SSE and VR (Minty Lightning 2019)`.
- Déjà installé, nom conforme.
- Aucun changement MO2, aucun test nécessaire.

### Étape 639 — ETHEREAL CLOUDS vérifié

- Mod vérifié : `ETHEREAL CLOUDS - Special Edition`.
- Déjà installé, nom conforme.
- Aucun changement MO2, aucun test nécessaire.

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
- Snapshot MO2 courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md`.
