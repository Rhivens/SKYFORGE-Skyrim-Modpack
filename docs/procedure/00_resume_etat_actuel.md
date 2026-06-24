# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 600 — Banner fix + MIF + Separated Slash Effects X**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md` — placeholder créé, collage manuel du load order complet à effectuer
- Le snapshot 578 devient un jalon historique post-578.
- Prochaine étape attendue : **Étape 601**
- Compteur ESP + ESM non-light post-600 : **131**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 451 à 600**

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
- **Compteur ESP + ESM non-light final post-600 :** 131
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; non relancé pendant les étapes 451 à 600
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md` — snapshot courant post-600, placeholder créé, collage manuel à effectuer
4. `docs/procedure/99_changelog_validation_part_21.md`
5. `docs/procedure/05_1_lighting_effects_particles_part_1.md`
6. `docs/procedure/05_visual_base_meshes_textures_part_3.md`
7. `docs/procedure/06_decisions_differees_part_7.md`
8. `docs/procedure/99_changelog_validation_part_20.md`
9. `docs/procedure/05_visual_base_meshes_textures_part_2.md`
10. `docs/procedure/06_decisions_differees_part_6.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md` — jalon historique post-578
12. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md` — jalon historique post-567

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
