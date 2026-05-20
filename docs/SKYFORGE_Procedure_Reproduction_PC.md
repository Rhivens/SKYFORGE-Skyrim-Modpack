# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

- **Dernière étape validée :** Étape 289 — Environs Hroggar’s House
- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club conservé :** oui
- **Gestionnaire :** Mod Organizer 2 portable
- **Module en cours :** 07 - CITIES TOWNS INTERIORS LIGHTING
- **Dernier profil stable :** SKYFORGE - Stable étape 275 villages Ivarstead OK
- **Compteur confirmé :** ESP + ESM non-light : 55
- **Validation :** SKSE via MO2 → menu principal → aucun message DLL bloquant → aucun master manquant → `Overwrite` vide

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
12. [UI, HUD et menus](procedure/07_ui_hud_menus.md)
13. [UI, HUD et menus — partie 2](procedure/07_ui_hud_menus_part_2.md)
14. [UI, HUD et menus — partie 3](procedure/07_ui_hud_menus_part_3.md)
15. [Survival, immersion et roleplay](procedure/08_survival_immersion_roleplay.md)
16. [Audio, musiques et sons](procedure/09_audio_music_sounds.md)
17. [Audio, musiques et sons — partie 2](procedure/09_audio_music_sounds_part_2.md)
18. [Landscape, grass, trees & water](procedure/10_landscape_grass_trees_water.md)
19. [Landscape, grass, trees & water — partie 2](procedure/10_landscape_grass_trees_water_part_2.md)
20. [Landscape, grass, trees & water — partie 3](procedure/10_landscape_grass_trees_water_part_3.md)
21. [Cities, towns, interiors & lighting](procedure/11_cities_towns_interiors_lighting.md)
22. [Changelog / validation](procedure/99_changelog_validation.md)

---

## Documents de configuration

1. [Règles de configuration SKYFORGE](configuration/00_regles_configuration.md)
2. [Configurations moteur / SKSE](configuration/01_engine_skse_ini.md)
3. [Configurations UI / HUD / menus](configuration/02_ui_hud_ini.md)
4. [Configurations audio](configuration/03_audio_ini.md)
5. [Configurations survival / immersion / roleplay](configuration/04_survival_immersion_mcm.md)
6. [Configurations SexLab / Devious / adultes](configuration/05_sexlab_devious_mcm.md)
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

---

## Prochaine reprise

Reprendre à partir de :

`Étape 290`

Sujet prévu :

Suite du module `07 - CITIES TOWNS INTERIORS LIGHTING`.

Consignes maintenues :

- Ne pas lancer LOOT.
- Ne pas générer LOD / DynDOLOD maintenant.
- Ne pas toucher au panneau droit sauf missing master.
- Garder `Atlantean Landscape -Complete- 2K` décoché.
- Garder les patch hubs / patch collections marqués `A COMPLETER PLUS TARD` pour la future phase de patching.
- Continuer les tests courts SKSE / menu / masters / DLL / Overwrite.
