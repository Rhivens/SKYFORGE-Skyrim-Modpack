# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.  
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.  
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## État actuel validé

- **Dernière étape validée :** Étape 101 — Installation de Best In Class
- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club conservé :** oui
- **Gestionnaire :** Mod Organizer 2 portable
- **Module principal en cours :** 02 - BUG FIXES & ENGINE PATCHES
- **Validation :** SKSE via MO2 → menu principal → aucun message DLL bloquant → aucun master manquant → `Overwrite` vide

---

## Documents de procédure

1. [Résumé de l’état actuel](procedure/00_resume_etat_actuel.md)
2. [Préparation base Skyrim / MO2](procedure/01_preparation_base_skyrim_mo2.md)
3. [SKSE, dépendances et core utilities](procedure/02_skse_core_utilities.md)
4. [Bug fixes & engine patches — partie 1](procedure/03_bug_fixes_engine_patches_part_1.md)
5. [Bug fixes & engine patches — partie 2](procedure/04_bug_fixes_engine_patches_part_2.md)
6. [Visual base meshes & textures](procedure/05_visual_base_meshes_textures.md)
7. [Décisions différées et points à revoir](procedure/06_decisions_differees.md)
8. [Changelog / validation](procedure/99_changelog_validation.md)

---

## Règle de classement

La numérotation des étapes reste **chronologique et globale**.

Un fichier thématique peut donc contenir une étape plus tardive si elle appartient à son module.  
Exemple : l’étape 97, liée à `NL_MCM`, est classée dans le fichier des core utilities même si elle a été validée après des correctifs du module 02.

---

## Règle de mise à jour

Lors de futures sessions d’installation, les nouvelles étapes peuvent être rédigées en vrac dans l’ordre de validation.  
Elles seront ensuite reclassées dans les fichiers thématiques correspondants.

Format recommandé pour les nouvelles étapes :

```md
### 102. Nom du mod ou de la décision

**Module :** 02 - BUG FIXES & ENGINE PATCHES

**Objectif :**  
...

**Lien :**  
...

**Résultat attendu :**  
...

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 102 validée.
```
