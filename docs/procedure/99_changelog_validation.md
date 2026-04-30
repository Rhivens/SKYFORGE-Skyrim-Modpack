# Changelog / validation

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 101

**Dernière étape validée :**  
`Étape 101 — Installation de Best In Class`

**Module principal en cours :**  
`02 - BUG FIXES & ENGINE PATCHES`

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé : OK
- `Overwrite` vide : OK

---

## État validé après l’étape 150

**Dernière étape validée :**  
`Étape 150 — Security Overhaul SKSE - Some More Locks / Extra Locks`

**Module récent :**  
`03 - UI HUD MENUS`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/02_skse_core_utilities_part_2.md`
- `docs/procedure/04_bug_fixes_engine_patches_part_3.md`
- `docs/procedure/07_ui_hud_menus.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/procedure/06_decisions_differees.md`
- `docs/procedure/99_changelog_validation.md`

**Prochaine reprise :**  
`Étape 151`

---

## État validé après l’étape 154

**Dernière étape validée :**  
`Étape 154 — Vel’dun UI minimal`

**Module en cours :**  
`03 - UI HUD MENUS`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- Vel’dun UI visible au menu principal : OK

**Étapes ajoutées lors de cette mise à jour :**

- `Étape 152 — A Matter of Time`
- `Étape 153 — SkyHUD minimal`
- `Étape 154 — Vel’dun UI minimal`

**Décisions ajoutées lors de cette mise à jour :**

- `Skyrim Unbound` est retenu comme départ alternatif officiel de SKYFORGE.
- `Edge UI` est abandonné et supprimé.
- `Vel’dun UI` devient l’interface principale actuelle de SKYFORGE.
- Le crosshair vanilla de Skyrim doit être conservé.
- Les icônes Dragonborn Reskin sont différées.
- `SkyHUD` et `Vel’dun UI` sont installés minimalement et renommés `A REINSTALL PLUS TARD`.

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/procedure/06_decisions_differees.md`
- `docs/procedure/07_ui_hud_menus.md`
- `docs/procedure/99_changelog_validation.md`

**Prochaine reprise :**  
`Étape 155`

---

## Rappel méthode

- Avancer prudemment, par petits blocs.
- Tester via SKSE jusqu’au menu après chaque bloc.
- Tester individuellement les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes.
- Ne pas lancer LOOT pour l’instant.
- Ne pas toucher au panneau droit sauf missing master.
- Tant que `Skyrim Unbound` n’est pas installé, limiter les tests au menu principal.
- Ne pas installer de patch si le mod parent n’est pas installé ou officiellement retenu.
- Garder les décisions différées dans `06_decisions_differees.md`.
- Garder la numérotation chronologique globale, même quand les étapes sont reclassées dans des fichiers thématiques.
