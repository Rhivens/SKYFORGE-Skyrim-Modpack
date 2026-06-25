# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 618 — Splashes of Storms ENB Fix**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md` — placeholder créé, collage manuel du load order complet à effectuer
- Le snapshot 600 devient un jalon historique post-600.
- Prochaine étape attendue : **Étape 619**
- Compteur ESP + ESM non-light post-618 : **133**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 601 à 618**

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
- **Compteur ESP + ESM non-light final post-618 :** 133
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; non relancé pendant les étapes 601 à 618
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md` — snapshot courant post-618, placeholder créé, collage manuel à effectuer
4. `docs/procedure/99_changelog_validation_part_22.md`
5. `docs/procedure/10_landscape_grass_trees_water_part_4.md`
6. `docs/procedure/06_decisions_differees_part_8.md`
7. `docs/procedure/05_1_lighting_effects_particles_part_2.md`
8. `docs/procedure/05_2_parallax_framework_textures_part_1.md`
9. `docs/procedure/02_skse_core_utilities_part_2.md`
10. `docs/procedure/99_changelog_validation_part_21.md`
11. `docs/procedure/05_1_lighting_effects_particles_part_1.md`
12. `docs/procedure/06_decisions_differees_part_7.md`
13. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md` — jalon historique post-600
14. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md` — jalon historique post-578

## Étapes récentes validées / documentées

### Étapes 579 à 581 — Fin complément Visual Base / meshes

- Installation de meshes FYX, collisions, coffres, carrioles détaillées, symboles du Collège, boissons uniques et correction caméra bûcheronnage.
- Compteur ESP + ESM non-light conservé à **129**.
- État final post-581 : SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide.

### Étapes 582 à 600 — Ouverture du bloc Lighting Effects & Particles

- Création / validation du séparateur `[05.1 - LIGHTING EFFECTS & PARTICLES]`.
- Installation de fumées, impacts de sorts, patchs d’impacts, poussières, nombreux ENB Particle Lights, Rudy HQ More Lights, VFX élémentaires, VFX Kittytail, FleshFX, MIF et Separated Slash Effects X - MIF.
- Compteur ESP + ESM non-light : **129 → 130** à l’étape 582, puis **130 → 131** à l’étape 583.
- Étape 600 validée avec `MIF - Mu Impact Framework` et `Separated Slash Effects X - MIF`.
- État final post-600 : SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide, compteur ESP + ESM non-light **131**.
- Snapshot MO2 panneau gauche post-600 créé avec placeholder dans `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md`.

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
