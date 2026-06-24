# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

Dernière étape validée : Étape 600 — Banner fix + MIF + Separated Slash Effects X
Dernière étape d’installation validée : Étape 600 — Banner fix + MIF + Separated Slash Effects X
Module en cours : 05.1 - LIGHTING EFFECTS & PARTICLES
Sous-bloc en cours : ENB Particle Lights / VFX / impacts / effets visuels
Dernier fichier thématique mis à jour : docs/procedure/05_1_lighting_effects_particles_part_1.md
Dernier changelog de validation : docs/procedure/99_changelog_validation_part_21.md
Dernier fichier de décisions différées : docs/procedure/06_decisions_differees_part_7.md
Dernier snapshot MO2 panneau gauche : docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md — placeholder créé, collage manuel du load order complet à effectuer
Prochaine étape attendue : Étape 601
Profil stable de référence : à créer / nommer après décision Fabien si nécessaire
Runtime : Skyrim SE 1.5.97 Best of Both Worlds
AE / Creation Club : conservé
MO2 : portable
Compteur ESP + ESM non-light : 131
LOOT : non lancé
LOD / DynDOLOD : non générés
BodySlide Output : non généré
Pandora : généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 451 à 600

---

## État technique validé

SKSE via MO2 : OK
Menu principal : OK
Aucun master manquant
Aucun message DLL bloquant
Tous les plugins attendus cochés
Overwrite vide
Compteur ESP + ESM non-light final post-600 : 131
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
13. [Décisions différées et points à revoir](procedure/06_decisions_differees.md)
14. [Décisions différées et points à revoir — partie 2](procedure/06_decisions_differees_part_2.md)
15. [Décisions différées et points à revoir — partie 3](procedure/06_decisions_differees_part_3.md)
16. [Décisions différées et points à revoir — partie 4](procedure/06_decisions_differees_part_4.md)
17. [Décisions différées et points à revoir — partie 5](procedure/06_decisions_differees_part_5.md)
18. [Décisions différées et points à revoir — partie 6](procedure/06_decisions_differees_part_6.md)
19. [Décisions différées et points à revoir — partie 7](procedure/06_decisions_differees_part_7.md)
20. [UI, HUD et menus](procedure/07_ui_hud_menus.md)
21. [UI, HUD et menus — partie 2](procedure/07_ui_hud_menus_part_2.md)
22. [UI, HUD et menus — partie 3](procedure/07_ui_hud_menus_part_3.md)
23. [Survival, immersion et roleplay](procedure/08_survival_immersion_roleplay.md)
24. [Audio, musiques et sons](procedure/09_audio_music_sounds.md)
25. [Audio, musiques et sons — partie 2](procedure/09_audio_music_sounds_part_2.md)
26. [Landscape, grass, trees & water](procedure/10_landscape_grass_trees_water.md)
27. [Landscape, grass, trees & water — partie 2](procedure/10_landscape_grass_trees_water_part_2.md)
28. [Landscape, grass, trees & water — partie 3](procedure/10_landscape_grass_trees_water_part_3.md)
29. [Cities, towns, interiors & lighting](procedure/11_cities_towns_interiors_lighting.md)
30. [Cities, towns, interiors & lighting — partie 2](procedure/11_cities_towns_interiors_lighting_part_2.md)
31. [Cities, towns, interiors & lighting — partie 3](procedure/11_cities_towns_interiors_lighting_part_3.md)
32. [Cities, towns, interiors & lighting — partie 4](procedure/11_cities_towns_interiors_lighting_part_4.md)
33. [Cities, towns, interiors & lighting — partie 5](procedure/11_cities_towns_interiors_lighting_part_5.md)
34. [Cities, towns, interiors & lighting — partie 6](procedure/11_cities_towns_interiors_lighting_part_6.md)
35. [Cities, towns, interiors & lighting — partie 7](procedure/11_cities_towns_interiors_lighting_part_7.md)
36. [Cities, towns, interiors & lighting — partie 8](procedure/11_cities_towns_interiors_lighting_part_8.md)
37. [Ajouts personnels SKYFORGE](procedure/96_ajouts_personnels_skyforge.md)
38. [Registre central de dette technique](procedure/97_registre_dette_technique.md)
39. [Registre central de dette technique — partie 2](procedure/97_registre_dette_technique_part_2.md)
40. [Audit de continuité des étapes](procedure/98_audit_continuite_etapes.md)
41. [Changelog / validation](procedure/99_changelog_validation.md)
42. [Changelog / validation — partie 2](procedure/99_changelog_validation_part_2.md)
43. [Changelog / validation — partie 3](procedure/99_changelog_validation_part_3.md)
44. [Changelog / validation — partie 4](procedure/99_changelog_validation_part_4.md)
45. [Changelog / validation — partie 5](procedure/99_changelog_validation_part_5.md)
46. [Changelog / validation — partie 6](procedure/99_changelog_validation_part_6.md)
47. [Changelog / validation — partie 17](procedure/99_changelog_validation_part_17.md)
48. [Changelog / validation — partie 19](procedure/99_changelog_validation_part_19.md)
49. [Changelog / validation — partie 20](procedure/99_changelog_validation_part_20.md)
50. [Changelog / validation — partie 21](procedure/99_changelog_validation_part_21.md)

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
9. [Load Order MO2 panneau gauche — Étape 600](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md)
10. [Load Order MO2 panneau gauche — Étape 578](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md)
11. [Load Order MO2 panneau gauche — Étape 567](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md)
12. [Load Order MO2 panneau gauche — Étape 553](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md)
13. [Load Order MO2 panneau gauche — Étape 530](configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md)

---

## Règle de classement

La numérotation des étapes reste **chronologique et globale**.

Un fichier thématique peut donc contenir une étape plus tardive si elle appartient à son module.

Quand un fichier devient trop lourd, une partie suivante peut être créée afin de garder la lecture fluide.

---

## Règle de mise à jour

Lors de futures sessions d’installation, les nouvelles étapes peuvent être rédigées en vrac dans l’ordre de validation.
Elles seront ensuite reclassées dans les fichiers thématiques correspondants.

Tout mod ou ressource ne provenant ni de Nolvus ni de Nefaram doit être marqué `AJOUT FABIEN / SKYFORGE Custom` et référencé dans `docs/procedure/96_ajouts_personnels_skyforge.md`.

Le registre central de dette technique doit être maintenu à chaque pause GitHub lorsqu’un nouvel élément est marqué `A REINSTALL PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `A COMPLETER PLUS TARD`, `DECOCHE`, `MASTER MANQUANT`, `CHOIX A REVOIR`, ou `LOD / DynDOLOD différé`.

---

## Prochaine reprise

La reprise se fait à partir de :

Étape 601
Module : 05.1 - LIGHTING EFFECTS & PARTICLES
Sous-bloc : ENB Particle Lights / VFX / impacts / effets visuels
État de référence : Étape 600 validée, compteur non-light 131
Snapshot MO2 panneau gauche de référence : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_600.md` — placeholder créé, collage manuel à effectuer
Règles maintenues :
main files d’abord ;
patches complexes différés ;
ne pas lancer LOOT ;
ne pas générer LOD / DynDOLOD ;
ne pas générer BodySlide Output ;
ne pas relancer Pandora sauf ajout animation/comportement nécessitant génération ;
ne pas toucher au panneau droit sauf missing master ou plugin attendu ;
continuer les tests courts SKSE / menu / masters / DLL / Overwrite.

Consignes maintenues :

- Ne pas lancer LOOT.
- Ne pas générer LOD / DynDOLOD maintenant.
- Ne pas générer BodySlide Output maintenant.
- Ne pas relancer Pandora sauf nécessité explicite.
- Ne pas toucher au panneau droit sauf missing master ou plugin attendu.
- Garder les patches complexes différés pour la future phase de patching.
- Continuer les tests courts SKSE / menu / masters / DLL / Overwrite.
