# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 639 — ETHEREAL CLOUDS vérifié**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — placeholder créé, collage manuel du load order complet à effectuer
- Le snapshot 618 devient un jalon historique post-618.
- Prochaine étape attendue : **Étape 640**
- Compteur ESP + ESM non-light post-639 : **138**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 619 à 639**

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK sur les tests documentés
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur les tests documentés
- **Compteur ESP + ESM non-light final post-639 :** 138
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; non relancé pendant les étapes 619 à 639
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — snapshot courant post-639, placeholder créé, collage manuel à effectuer
4. `docs/procedure/99_changelog_validation_part_23.md`
5. `docs/procedure/10_landscape_grass_trees_water_part_5.md`
6. `docs/procedure/06_decisions_differees_part_9.md`
7. `docs/procedure/99_changelog_validation_part_22.md`
8. `docs/procedure/10_landscape_grass_trees_water_part_4.md`
9. `docs/procedure/06_decisions_differees_part_8.md`
10. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md` — jalon historique post-618
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md` — jalon historique post-600

## Étapes récentes validées / documentées

### Étapes 601 à 603 — Clôture provisoire du bloc Lighting Effects & Particles

- Installation de `Enhanced Volumetric Lighting and Shadows - EVLaS`, `Dripping Mist Reduction` et `SpiderWIP`.
- `EVLaS Skyrim Underside` différé pour la passe DynDOLOD / LOD.
- Bloc `[05.1 - LIGHTING EFFECTS & PARTICLES]` clôturé provisoirement à l’étape 603.
- Compteur ESP + ESM non-light conservé à **131**.

### Étapes 604 à 606 — Parallax Framework Textures

- Ouverture du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Installation de `Dlizzio's Mesh Fixes - Parallax Mesh Patch`.
- Installation / confirmation de `Auto Parallax` dans `[01 - SKSE PLUGINS & CORE UTILITIES]`, après `SkyPatcher - SE`.
- Bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]` clôturé provisoirement à l’étape 606.
- Compteur ESP + ESM non-light conservé à **131**.

### Étapes 607 à 618 — Reprise Landscape / Grass / Trees / Water

- Clarification administrative de plusieurs FOMOD / notes MO2 dans `[06 - LANDSCAPE GRASS TREES WATER]`.
- Ajouts atmosphériques : `Obsidian Mountain Fogs`, `Morning Fogs SSE`, `Vanilla And Morning Fogs SSE - Easy Seam Fixer`.
- Ajout du fix ENB `Splashes of Storms - ENB Fix`.
- Compteur ESP + ESM non-light : **131 → 132** à l’étape 615, puis **132 → 133** à l’étape 616.
- Étape 618 validée avec SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide, compteur **133**.
- Snapshot MO2 panneau gauche post-618 créé avec placeholder dans `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md`.

### Étapes 619 à 639 — Eau, cascades, Footprints, ash et vérifications météo

- Nettoyage administratif de noms MO2 dans le bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Ajout de la pile eau / cascades : `Water in Wash Basins`, `Water in Wells`, `Water Effects Brightness and Reflection Fix`, `Loki's Wade In Water`, `Wade In Water Redone`, `Splashes Of Skyrim`, `Natural Waterfalls`, `FYX - Water Mesh Optimization C 128`, `Rainbows over Waterfalls`, `TMD The Rift Leaves`, `Animated Ice Floes`.
- Ajout de `Better Dynamic Ash SE`.
- Ajout de la pile Footprints active : `Footprints`, `Footprints - ENB`, `SPID for Footprints`, `SPID for Footprints fix`, `SPID for Footprints - Player Footprints Fix`.
- `Ultimate fix - SPID for Footprints` conservé décoché en réserve avec FOMOD / MCM `Reset counts` à reprendre plus tard.
- Vérifications finales : `Snowy Surfaces`, `Storm Lightning`, `ETHEREAL CLOUDS`.
- Compteur ESP + ESM non-light : **133 → 134** à l’étape 621, **134 → 135** à l’étape 623, **135 → 137** à l’étape 629, **137 → 138** à l’étape 630.
- Étape 639 validée ; Overwrite vide ; LOOT non lancé ; DynDOLOD / LOD non générés ; BodySlide non généré ; Pandora non relancé.
- Snapshot MO2 panneau gauche post-639 créé avec placeholder dans `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md`.
