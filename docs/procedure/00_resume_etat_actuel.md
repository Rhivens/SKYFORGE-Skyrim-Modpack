# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape validée :** Étape 434 — A Closer Look SSE
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module actif :** gameplay / combat léger et confort issu de Nolvus Awakening
- **Dernier profil stable :** étape 434
- **Prochaine étape attendue :** étape 435, reprise prudente par petit bloc après lecture GitHub.

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK
- **Menu principal :** OK
- **Masters manquants :** aucun
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 108
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l’étape 411, Output actif, non relancé depuis
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/99_changelog_validation_part_13.md`
3. `docs/procedure/10_gameplay_combat_magic_perks_part_3.md`
4. `docs/procedure/99_changelog_validation_part_12.md`
5. `docs/procedure/10_gameplay_combat_magic_perks_part_2.md`
6. `docs/procedure/09_animations_skeleton_physics_part_3.md`
7. `docs/procedure/99_changelog_validation_part_11.md`
8. `docs/procedure/10_validation_gameplay_post_ctd_etape_415.md`
9. `docs/procedure/09_animations_skeleton_physics_part_2.md`
10. `docs/procedure/10_stabilisation_etape_412_414.md`
11. `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
12. `docs/procedure/09_animations_skeleton_physics_part_1.md`
13. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`

## Étapes récentes validées

- **Étape 426 :** test gameplay ciblé post-ajouts combat / archerie, 15 minutes. Aucun CTD, aucun reboot, combats et MCM OK. Anomalie graphique non bloquante dans Giant Inn de Riverwood. Compteur 108.
- **Étape 427 :** `NPCs Use Potions` + `NPCs Use Potions - SKYFORGE Config`. FOMOD limité au profil actuel. Incident écran noir non reproduit, non bloquant. Test menu atteint OK. Compteur 108.
- **Étape 428 :** `Smart Optimal Salves - Optimal Potion Hotkey MCM` + `Optimal Potion Hotkey MCM - Settings Loader`. Hotkeys non configurées maintenant. Test menu atteint OK. Compteur 108.
- **Étape 429 :** `Simple Offence Suppression` + `Simple Offence Suppression MCM - Block Friendly Fire`. MCM non configuré maintenant. Test menu atteint OK. Compteur 108.
- **Étape 430 :** `I’m Talkin’ Here` + `Instantly Skip Dialogue NG`. Aucun patch follower ajouté pour l’instant. Test menu atteint OK. Compteur 108.
- **Étape 431 :** `Disable Follower Collision` + `I’m Walkin’ Here` version `1.5.0` compatible Skyrim `1.5.50 - 1.5.97`. Test menu atteint OK. Compteur 108.
- **Étape 432 :** `No Furniture Camera` + `Pick Up Radius`. MCM non configuré maintenant. Test menu atteint OK. Compteur 108.
- **Étape 433 :** annulée pour doublons déjà installés : `Use Or Take SKSE`, `Read Or Take SKSE`, `Favorite Misc Items`. Aucune installation. Compteur inchangé.
- **Étape 434 :** `A Closer Look SSE`, version SSE. Version NG non installée par prudence avec Skyrim SE 1.5.97. Test menu atteint OK. Compteur 108.

## Décisions structurantes actuelles

- **Nolvus Awakening** est la référence principale pour combat / dodge / animations combat / confort gameplay léger.
- **Nefaram** reste la référence principale pour Body compatible adulte / compatibilité future / systèmes spécialisés différés.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n’est pas retenu comme générateur principal.
- Les réglages TK Dodge RE doivent être des réglages SKYFORGE propres, inspirés de Nolvus Awakening mais adaptés au modpack.
- Ne pas dépendre des fichiers Nolvus Awakening locaux, sauf besoin futur de comparaison avancée.
- Les réglages MCM non urgents seront repris plus tard avec la logique Startup Save / MCM Recorder.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d’installation, vérifier dans GitHub :

- ce résumé d’état actuel ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Ne jamais reproposer un mod déjà présent dans le snapshot ou les fichiers de procédure.

L’étape 433 documente explicitement les doublons suivants comme déjà installés :

- `Use Or Take SKSE`
- `Read Or Take SKSE`
- `Favorite Misc Items`

## Règle traductions personnelles FR

Tous les mods dont le nom se termine par `- FR` sont des traductions personnelles de Fabien.

Ces mods `- FR` restent volontairement **décochés pour le moment**, tant que le modpack n’est pas stabilisé.

Ils seront activés plus tard par petits groupes contrôlés, avec test SKSE / menu après chaque groupe.

Leur présence dans le panneau gauche MO2 ne doit pas être interprétée comme une erreur ou un oubli.

## Incident Windows isolé — étape 420

Un redémarrage complet Windows est survenu au premier lancement de l’étape 420.

Éléments observés :

- Kernel-Power 41 ;
- BugCheck `0x00000050 PAGE_FAULT_IN_NONPAGED_AREA` ;
- dump : `C:\WINDOWS\Minidump\061726-8609-01.dmp` ;
- WinDbg :
  - `PROCESS_NAME: SkyrimSE.exe` ;
  - `IMAGE_NAME: ntkrnlmp.exe` ;
  - `FAILURE_BUCKET_ID: AV_nt!MiSystemFault` ;
  - pile incluant `Ntfs!NtfsCommonDirectoryControl`.

Conclusion actuelle :

- incident isolé ;
- non reproduit après retour état 419, tests isolés 420A / 420B et retests ;
- aucune récidive signalée sur les étapes 426 à 434 ;
- pas de preuve de malware ;
- pas de preuve de mod Skyrim fautif ;
- pas de preuve que MO2 / SKYFORGE soit directement responsable ;
- MSI Center / services bas niveau à surveiller uniquement si récidive.

## Incidents / anomalies récents non bloquants

### Étape 420 — Block Enchantments

`Block Enchantments` reste validé malgré le warning MO2 transitoire `Plugin not found: blockenchantments.esl` observé auparavant.

Le plugin était visible et actif dans le panneau droit MO2, chargé en FE / ESL-light, sans master manquant ni crash reproduit.

### Étape 426 — Riverwood Giant Inn

Anomalie graphique non bloquante : objets flottants à l’emplacement de l’ancien comptoir dans la cellule Giant Inn de Riverwood.

Décision : à corriger plus tard, sans bloquer le module combat / gameplay.

### Étape 427 — écran noir non reproductible

Un écran noir / blocage avant menu a été observé au premier lancement après installation de `NPCs Use Potions`.

Après relance, l’incident ne s’est pas reproduit et le menu principal a été atteint normalement.

Décision : vigilance mineure, non bloquante.

## Vigilances levées récemment

- **Pandora installé mais non généré :** levée à l’étape 411.
- **Smooth TK Dodge Attack à confirmer en jeu :** levée à l’étape 415 dans le cadre du test gameplay limité post-CTD.

## Vigilances restantes

- **BodySlide Output :** non généré.
- **XPMSSE :** FOMOD à revoir plus tard avant animations avancées / styles d’armes.
- **LeveledList Crash Fix AE + 1.5 :** à vérifier hors urgence.
- **LOOT :** non lancé.
- **DynDOLOD / LOD :** non générés.
- **Mods `- FR` :** toujours décochés volontairement.
- **Mod fautif CTD étape 413 :** `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD` doit rester décoché / différé.
- **Incident Windows étape 420 :** à surveiller uniquement si récidive.
- **Precision - Creatures :** reste différé.
- **Bug graphique Riverwood Giant Inn :** objets flottants à corriger plus tard.
- **MCM non configurés des étapes 428, 429, 432 et 434 :** à reprendre plus tard avec Startup Save / MCM Recorder.
- **FOMOD NPCs Use Potions :** à revoir plus tard si ajout officiel de nouveaux mondes, quêtes, donjons ou créatures compatibles.

## Mods explicitement décochés / différés à conserver

- `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`
- `Kris's Papyrus Extender - DECOCHE RESERVE`
- `ENB Extender Skyrim - DECOCHE RESERVE ENB`
- `Magic College Music - Songs for Academy - DECOCHE FORM 43`
- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD`
- `Cities of the North - Morthal - DECOCHE CHOIX A REVOIR`
- `Scarecrows of Skyrim - BOS - SOS Patch - REQUIERT SIMPLICTY OF SNOW`
- `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE`
- tous les mods terminés par `- FR`

## Outils non lancés / non relancés à ce stade

- LOOT
- DynDOLOD / LOD
- BodySlide
- Pandora non relancé depuis l’étape 411

## Dernier état stable

Profil stable étape 434 :

- SKSE / menu principal : OK
- Aucun master manquant
- Aucun message DLL bloquant
- Plugins cochés
- Overwrite vide
- CrashLogger actif
- Pandora Output actif
- Compteur ESP + ESM non-light : 108
