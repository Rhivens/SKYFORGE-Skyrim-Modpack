# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

- **Dernière étape validée :** Étape 150 — Security Overhaul SKSE - Some More Locks / Extra Locks
- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club conservé :** oui
- **Gestionnaire :** Mod Organizer 2 portable
- **Module récent :** 03 - UI HUD MENUS
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
10. [UI, HUD et menus](procedure/07_ui_hud_menus.md)
11. [Changelog / validation](procedure/99_changelog_validation.md)

---

## Règle de classement

La numérotation des étapes reste **chronologique et globale**.

Un fichier thématique peut donc contenir une étape plus tardive si elle appartient à son module.

Quand un fichier devient trop lourd, une partie suivante peut être créée afin de garder la lecture fluide.

---

## Règle de mise à jour

Lors de futures sessions d’installation, les nouvelles étapes peuvent être rédigées en vrac dans l’ordre de validation.
Elles seront ensuite reclassées dans les fichiers thématiques correspondants.
