# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

Dernière étape validée : Étape 618 — Splashes of Storms ENB Fix
Dernière étape d’installation validée : Étape 618 — Splashes of Storms ENB Fix
Module en cours : 06 - LANDSCAPE GRASS TREES WATER
Sous-bloc en cours : paysages / eau / ciel / atmosphère
Dernier fichier thématique mis à jour : docs/procedure/10_landscape_grass_trees_water_part_4.md
Dernier changelog de validation : docs/procedure/99_changelog_validation_part_22.md
Dernier fichier de décisions différées : docs/procedure/06_decisions_differees_part_8.md
Dernier snapshot MO2 panneau gauche : docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md — placeholder créé, collage manuel du load order complet à effectuer
Prochaine étape attendue : Étape 619
Profil stable de référence : à créer / nommer après décision Fabien si nécessaire
Runtime : Skyrim SE 1.5.97 Best of Both Worlds
AE / Creation Club : conservé
MO2 : portable
Compteur ESP + ESM non-light : 133
LOOT : non lancé
LOD / DynDOLOD : non générés
BodySlide Output : non généré
Pandora : généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 601 à 618

---

## État technique validé

SKSE via MO2 : OK
Menu principal : OK
Aucun master manquant
Aucun message DLL bloquant
Tous les plugins attendus cochés
Overwrite vide
Compteur ESP + ESM non-light final post-618 : 133
LOOT non lancé
LOD / DynDOLOD non générés
BodySlide Output non généré
Pandora non relancé depuis les dernières étapes documentées

---

## Documents de procédure

1. [Résumé de l’état actuel](procedure/00_resume_etat_actuel.md)
2. [Préparation base Skyrim / MO2](procedure/01_preparation_base_skyrim_mo2.md)
3. [SKSE, dépendances et core utilities](procedure/02_skse_core_utilities.md)
4. [SKSE, dépendances et core utilities — partie 2](procedure/02_skse_core_utilities_part_2.md)
5. [Bug fixes & engine patches — partie 1](procedure/03_bug_fixes_engine_patches_part_1.md)
6. [Bug fixes & engine patches — partie 2](procedure/04_bug_fixes_engine_patches_part_2.md)
7. [Bug fixes & engine patches — partie 3](procedure/04_bug_fixes_engine_patches_part_3.md)
8. [Visual base meshes & textures](procedure/05_visual_base_meshes_textures.md)
9. [Visual base meshes & textures — partie 1](procedure/05_visual_base_meshes_textures_part_1.md)
10. [Visual base meshes & textures — partie 2](procedure/05_visual_base_meshes_textures_part_2.md)
11. [Visual base meshes & textures — partie 3](procedure/05_visual_base_meshes_textures_part_3.md)
12. [Lighting effects & particles — partie 1](procedure/05_1_lighting_effects_particles_part_1.md)
13. [Lighting effects & particles — partie 2](procedure/05_1_lighting_effects_particles_part_2.md)
14. [Parallax framework textures — partie 1](procedure/05_2_parallax_framework_textures_part_1.md)
15. [Décisions différées et points à revoir](procedure/06_decisions_differees.md)
16. [Décisions différées et points à revoir — partie 2](procedure/06_decisions_differees_part_2.md)
17. [Décisions différées et points à revoir — partie 3](procedure/06_decisions_differees_part_3.md)
18. [Décisions différées et points à revoir — partie 4](procedure/06_decisions_differees_part_4.md)
19. [Décisions différées et points à revoir — partie 5](procedure/06_decisions_differees_part_5.md)
20. [Décisions différées et points à revoir — partie 6](procedure/06_decisions_differees_part_6.md)
21. [Décisions différées et points à revoir — partie 7](procedure/06_decisions_differees_part_7.md)
22. [Décisions différées et points à revoir — partie 8](procedure/06_decisions_differees_part_8.md)
23. [UI, HUD et menus](procedure/07_ui_hud_menus.md)
24. [UI, HUD et menus — partie 2](procedure/07_ui_hud_menus_part_2.md)
25. [UI, HUD et menus — partie 3](procedure/07_ui_hud_menus_part_3.md)
26. [Survival, immersion et roleplay](procedure/08_survival_immersion_roleplay.md)
27. [Audio, musiques et sons](procedure/09_audio_music_sounds.md)
28. [Audio, musiques et sons — partie 2](procedure/09_audio_music_sounds_part_2.md)
29. [Landscape, grass, trees & water](procedure/10_landscape_grass_trees_water.md)
30. [Landscape, grass, trees & water — partie 2](procedure/10_landscape_grass_trees_water_part_2.md)
31. [Landscape, grass, trees & water — partie 3](procedure/10_landscape_grass_trees_water_part_3.md)
32. [Landscape, grass, trees & water — partie 4](procedure/10_landscape_grass_trees_water_part_4.md)
33. [Cities, towns, interiors & lighting](procedure/11_cities_towns_interiors_lighting.md)
34. [Cities, towns, interiors & lighting — partie 2](procedure/11_cities_towns_interiors_lighting_part_2.md)
35. [Cities, towns, interiors & lighting — partie 3](procedure/11_cities_towns_interiors_lighting_part_3.md)
36. [Cities, towns, interiors & lighting — partie 4](procedure/11_cities_towns_interiors_lighting_part_4.md)
37. [Cities, towns, interiors & lighting — partie 5](procedure/11_cities_towns_interiors_lighting_part_5.md)
38. [Cities, towns, interiors & lighting — partie 6](procedure/11_cities_towns_interiors_lighting_part_6.md)
39. [Cities, towns, interiors & lighting — partie 7](procedure/11_cities_towns_interiors_lighting_part_7.md)
40. [Cities, towns, interiors & lighting — partie 8](procedure/11_cities_towns_interiors_lighting_part_8.md)
41. [Ajouts personnels SKYFORGE](procedure/96_ajouts_personnels_skyforge.md)
42. [Registre central de dette technique](procedure/97_registre_dette_technique.md)
43. [Registre central de dette technique — partie 2](procedure/97_registre_dette_technique_part_2.md)
44. [Audit de continuité des étapes](procedure/98_audit_continuite_etapes.md)
45. [Changelog / validation](procedure/99_changelog_validation.md)
46. [Changelog / validation — partie 2](procedure/99_changelog_validation_part_2.md)
47. [Changelog / validation — partie 3](procedure/99_changelog_validation_part_3.md)
48. [Changelog / validation — partie 4](procedure/99_changelog_validation_part_4.md)
49. [Changelog / validation — partie 5](procedure/99_changelog_validation_part_5.md)
50. [Changelog / validation — partie 6](procedure/99_changelog_validation_part_6.md)
51. [Changelog / validation — partie 17](procedure/99_changelog_validation_part_17.md)
52. [Changelog / validation — partie 19](procedure/99_changelog_validation_part_19.md)
53. [Changelog / validation — partie 20](procedure/99_changelog_validation_part_20.md)
54. [Changelog / validation — partie 21](procedure/99_changelog_validation_part_21.md)
55. [Changelog / validation — partie 22](procedure/99_changelog_validation_part_22.md)

---

## Documents de configuration

1. [Règles de configuration SKYFORGE](configuration/00_regles_configuration.md)
2. [Configurations moteur / SKSE](configuration/01_engine_skse_ini.md)
3. [Configurations UI / HUD / menus](configuration/02_ui_hud_ini.md)
4. [Configurations audio](configuration/03_audio_ini.md)
5. [Configurations survival / immersion / roleplay](configuration/04_survival_immersion_mcm.md)
6. [Configurations frameworks spécifiques](configuration/05_sexlab_devious_mcm.md)
7. [Configurations différées](configuration/99_configurations_differees.md)
8. [Changelog configuration](configuration/CHANGELOG_CONFIGURATION.md)
9. [Load Order MO2 panneau gauche — Étape 618](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md)
10. [Load Order MO2 panneau gauche — Étape 600](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md)
11. [Load Order MO2 panneau gauche — Étape 578](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md)
12. [Load Order MO2 panneau gauche — Étape 567](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md)
13. [Load Order MO2 panneau gauche — Étape 553](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md)
14. [Load Order MO2 panneau gauche — Étape 530](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md)

---
