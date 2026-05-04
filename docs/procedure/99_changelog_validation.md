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

- `Étape 151 — Bloc UIExtensions / SkyUI fix / moreHUD`
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

## Correction documentaire après coup

L’étape 151 avait été oubliée lors de la première mise à jour 152–154. Elle a été retrouvée et intégrée proprement dans `docs/procedure/07_ui_hud_menus.md`.

---

## État validé après l’étape 168

**Dernière étape validée :**  
`Étape 168 — Bloc HUD confort léger`

**Module en cours :**  
`03 - UI HUD MENUS`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Étapes ajoutées / documentées lors de cette mise à jour :**

- `Étape 155 — TrueHUD`
- `Étape 156 — STB Widgets + STB Active Effects`
- `Étape 157 — Dragonborn Reskin pour STB`
- `Étape 158 — Wheeler + Dragonborn Wheeler Reskin`
- `Étape 159 — dMenu + dMenu NG`
- `Étape 160 — Infinity UI + Compass Navigation Overhaul`
- `Étape 161 — Better Third Person Selection`
- `Étape 162 — QuickLoot IE différé`
- `Étape 163 — ImGui Icons / Dialogue History / Menu Maid 2`
- `Étape 164 — Oxygen Meter 2`
- `Correction associée à l’étape 153 — Patch - SkyHUD 0.90.1B`
- `Étape 165 — Show Player In Menus`
- `Étape 166 — Dragonborn SkyUI Category and Fav Icons`
- `Étape 167 — Bloc carte / wait menu`
- `Étape 168 — Bloc HUD confort léger`

**Décisions ajoutées / confirmées lors de cette mise à jour :**

- `QuickLoot IE` est différé / non installé pour préserver l’immersion future SexLab / Devious / Cursed Loot.
- Les patches Vel’dun UI restent différés jusqu’à confirmation des mods parents utiles.
- `Dragonborn Reskin - Oxygen Meter 2` n’est pas installé.
- `Dragonborn Reskin - Compass and Weather` n’est pas installé.
- `Toggle Compass Hotkey` n’est pas retenu.
- `HideUI` est différé.
- `Photo Mode` est différé jusqu’aux futurs tests ingame / screenshots avec `Skyrim Unbound`.
- Les blocs de mods légers, visuels ou non sensibles peuvent être installés de façon groupée avec un test final.

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/07_ui_hud_menus_part_2.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/procedure/02_skse_core_utilities_part_2.md`
- `docs/procedure/06_decisions_differees.md`
- `docs/procedure/99_changelog_validation.md`

**Prochaine reprise :**  
`Étape 169`

---

## État validé après l’étape 185

**Dernière étape validée :**  
`Étape 185 — Patch ASIF pour RISE`

**Module en cours :**  
`04 - AUDIO MUSIC SOUNDS`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Test ingame limité à la salle de départ Skyrim Unbound : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Note de numérotation :**  
Le bloc fourni documente les étapes 170 à 185. L’étape 169 n’a pas été fournie dans ce bloc de mise à jour et reste absente de cette passe documentaire.

**Étapes ajoutées / documentées lors de cette mise à jour :**

- `Étape 170 — Atlas Map Markers`
- `Étape 171 — Contrôle placement Map UI`
- `Étape 172 — RaceMenu / création personnage`
- `Étape 173 — Pause sécurité avant départ alternatif`
- `Étape 174 — Skyrim Unbound Reborn`
- `Étape 175 — Sauvegarde test Unbound`
- `Étape 176 — Hotkeys UI légers`
- `Étape 177 — Audit anti-doublon UI`
- `Étape 178 — Fin provisoire du bloc UI`
- `Étape 179 — Base audio technique`
- `Étape 180 — Acoustic Space Improvement Fixes`
- `Étape 181 — Préparation AOS / ISC`
- `Étape 182 — Audio Overhaul + Immersive Sounds`
- `Étape 183 — Regional Sounds Expansion`
- `Étape 184 — Reverb Interior Sounds Expansion`
- `Étape 185 — Patch ASIF pour RISE`

**Décisions ajoutées / confirmées lors de cette mise à jour :**

- `Skyrim Unbound` est installé et validé comme départ alternatif officiel.
- Les tests ingame restent limités à la salle de départ.
- Les sauvegardes de test / autosaves devront être supprimées avant la partie finale.
- `RaceMenu Undress` affiche `$Undress slider` : correction ou acceptation à vérifier plus tard.
- `Better AltTab` est à installer plus tard avec test individuel ALT+TAB.
- `Show Follower Carry Weight` / `Show Mount Carry Weight` sont différés à cause de `Rogue’s Gallery`.
- `Too many notifications` est différé pour éviter doublon avec `Notification Log SSE` + `Notification Filter`.
- `AOS` et `ISC` restent marqués `A REINSTALL PLUS TARD` pour choix FOMOD conditionnels ou subjectifs.
- `ASIF` a été réinstallé avec le patch `RISE` activé.
- LOOT n’a pas été lancé.

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/07_ui_hud_menus_part_3.md`
- `docs/procedure/08_survival_immersion_roleplay.md`
- `docs/procedure/09_audio_music_sounds.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/procedure/06_decisions_differees.md`
- `docs/procedure/99_changelog_validation.md`

**Prochaine reprise :**  
`Étape 186`

---

## Rappel méthode

- Avancer prudemment, par petits blocs.
- Tester via SKSE jusqu’au menu après chaque bloc.
- Tester individuellement les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes.
- Ne pas lancer LOOT pour l’instant.
- Ne pas toucher au panneau droit sauf missing master.
- Les tests ingame restent limités à la salle de départ Skyrim Unbound tant que la base globale n’est pas suffisamment avancée.
- Ne pas installer de patch si le mod parent n’est pas installé ou officiellement retenu.
- Garder les décisions différées dans `06_decisions_differees.md`.
- Garder la numérotation chronologique globale, même quand les étapes sont reclassées dans des fichiers thématiques.
