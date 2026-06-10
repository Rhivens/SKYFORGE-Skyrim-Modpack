# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

Dernière étape validée : Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
Dernière étape d’installation validée : Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
Module en cours : 07 - CITIES TOWNS INTERIORS LIGHTING
Sous-bloc en cours : 07.6 - INTERIORS
Dernier fichier thématique mis à jour : docs/procedure/11_cities_towns_interiors_lighting_part_8.md
Dernier changelog de validation : docs/procedure/99_changelog_validation_part_6.md
Prochaine étape attendue : Étape 358
Profil stable de référence : SKYFORGE - Stable étape 346 ruins OK
Runtime : Skyrim SE 1.5.97 Best of Both Worlds
AE / Creation Club : conservé
MO2 : portable
Compteur ESP + ESM non-light : 82
LOOT : non lancé
LOD / DynDOLOD : non générés

---

## État technique validé

SKSE via MO2 : OK
Menu principal : OK
Aucun master manquant
Tous les plugins cochés
Overwrite vide
Dernier incident noté : crash ponctuel non reproductible à l’Étape 350 lors du premier lancement après Skyrim Sewers 4
Décision sur l’incident : surveillance uniquement, pas de réparation MO2, pas de modification DLL, pas de LOOT

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
9. [Décisions différées et points à revoir](procedure/06_decisions_differees.md)
10. [Décisions différées et points à revoir — partie 2](procedure/06_decisions_differees_part_2.md)
11. [Décisions différées et points à revoir — partie 3](procedure/06_decisions_differees_part_3.md)
12. [Décisions différées et points à revoir — partie 4](procedure/06_decisions_differees_part_4.md)
13. [Décisions différées et points à revoir — partie 5](procedure/06_decisions_differees_part_5.md)
14. [UI, HUD et menus](procedure/07_ui_hud_menus.md)
15. [UI, HUD et menus — partie 2](procedure/07_ui_hud_menus_part_2.md)
16. [UI, HUD et menus — partie 3](procedure/07_ui_hud_menus_part_3.md)
17. [Survival, immersion et roleplay](procedure/08_survival_immersion_roleplay.md)
18. [Audio, musiques et sons](procedure/09_audio_music_sounds.md)
19. [Audio, musiques et sons — partie 2](procedure/09_audio_music_sounds_part_2.md)
20. [Landscape, grass, trees & water](procedure/10_landscape_grass_trees_water.md)
21. [Landscape, grass, trees & water — partie 2](procedure/10_landscape_grass_trees_water_part_2.md)
22. [Landscape, grass, trees & water — partie 3](procedure/10_landscape_grass_trees_water_part_3.md)
23. [Cities, towns, interiors & lighting](procedure/11_cities_towns_interiors_lighting.md)
24. [Cities, towns, interiors & lighting — partie 2](procedure/11_cities_towns_interiors_lighting_part_2.md)
25. [Cities, towns, interiors & lighting — partie 3](procedure/11_cities_towns_interiors_lighting_part_3.md)
26. [Cities, towns, interiors & lighting — partie 4](procedure/11_cities_towns_interiors_lighting_part_4.md)
27. [Cities, towns, interiors & lighting — partie 5](procedure/11_cities_towns_interiors_lighting_part_5.md)
28. [Cities, towns, interiors & lighting — partie 6](procedure/11_cities_towns_interiors_lighting_part_6.md)
29. [Cities, towns, interiors & lighting — partie 7](procedure/11_cities_towns_interiors_lighting_part_7.md)
30. docs/procedure/11_cities_towns_interiors_lighting_part_8.md — étapes 347 à 357, ouverture et avancement 07.6 INTERIORS
31. [Ajouts personnels SKYFORGE](procedure/96_ajouts_personnels_skyforge.md)
32. [Registre central de dette technique](procedure/97_registre_dette_technique.md)
33. [Registre central de dette technique — partie 2](procedure/97_registre_dette_technique_part_2.md)
34. [Audit de continuité des étapes](procedure/98_audit_continuite_etapes.md)
35. [Changelog / validation](procedure/99_changelog_validation.md)
36. [Changelog / validation — partie 2](procedure/99_changelog_validation_part_2.md)
37. [Changelog / validation — partie 3](procedure/99_changelog_validation_part_3.md)
38. [Changelog / validation — partie 4](procedure/99_changelog_validation_part_4.md)
39. [Changelog / validation — partie 5](procedure/99_changelog_validation_part_5.md)
40. docs/procedure/99_changelog_validation_part_6.md — changelog étapes 347 à 357

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

Étape 358
Module : 07 - CITIES TOWNS INTERIORS LIGHTING
Sous-bloc : 07.6 - INTERIORS
État de référence : Étape 357 validée, compteur non-light 82
Règles maintenues :
main files d’abord ;
patches complexes différés ;
ne pas lancer LOOT ;
ne pas générer LOD / DynDOLOD ;
ne pas toucher au panneau droit sauf missing master ;
garder Atlantean Landscape -Complete- 2K décoché ;
garder le patch Scarecrows of Skyrim - BOS - SOS Patch décoché tant que Simplicity of Snow.esp est absent ;
continuer les tests courts SKSE / menu / masters / DLL / Overwrite.

Consignes maintenues :

- Ne pas lancer LOOT.
- Ne pas générer LOD / DynDOLOD maintenant.
- Ne pas toucher au panneau droit sauf missing master.
- Garder `Atlantean Landscape -Complete- 2K` décoché.
- Garder le patch `Scarecrows of Skyrim - BOS - SOS Patch` décoché tant que `Simplicity of Snow.esp` est absent.
- Garder les patches Jorrvaskr / Dawnguard / Volkihar différés pour la future phase de patching.
- Garder les patch hubs / patch collections marqués `A COMPLETER PLUS TARD` pour la future phase de patching.
- Garder les patches Lands / Ruins complexes différés : Lux / Lux Orbis / Lux Via / Northern Roads / eFPS / LOD / DynDOLOD / Nolvus.
- Continuer les tests courts SKSE / menu / masters / DLL / Overwrite.
