# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape validée :** Étape 425 — No Spinning Death Animation Merged LITE
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module actif :** gameplay / combat léger Nolvus Awakening, avec ajout ponctuel documenté en animations à l’étape 425
- **Dernier profil stable :** étape 425
- **Prochaine étape attendue :** étape 426, reprise prudente par petit bloc après lecture GitHub.

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
2. `docs/procedure/99_changelog_validation_part_12.md`
3. `docs/procedure/10_gameplay_combat_magic_perks_part_2.md`
4. `docs/procedure/09_animations_skeleton_physics_part_3.md`
5. `docs/procedure/99_changelog_validation_part_11.md`
6. `docs/procedure/10_validation_gameplay_post_ctd_etape_415.md`
7. `docs/procedure/09_animations_skeleton_physics_part_2.md`
8. `docs/procedure/10_stabilisation_etape_412_414.md`
9. `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
10. `docs/procedure/09_animations_skeleton_physics_part_1.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`

## Étapes récentes validées

- **Étape 416 :** `Wait Your Turn - Enemy Circling Behaviour`, issu de Nolvus Awakening. Test menu atteint OK. Compteur 106.
- **Étape 417 :** `NPCs Take Cover - Smarter Anti-Cheese AI`, issu de Nolvus Awakening. Test menu atteint OK. Compteur 106.
- **Étape 418 :** `NPC No Block - Exhaustion` + `NPC No Block Exhaustion - MCM`. Test menu atteint OK. Compteur 106.
- **Étape 419 :** `Stagger Effect Fix NG`, placé dans `02 - BUG FIXES & ENGINE PATCHES` sous `OnMagicEffectApply Replacer`. Test menu atteint OK. Compteur 106.
- **Étape 420 :** `3rd Person Camera Stagger Remover` + `Block Enchantments`. Incident Windows isolé au premier lancement, puis tests isolés réussis et non-reproduction. Étape validée. Compteur 106.
- **Étape 421 :** `Archery Locational Damage`, option FOMOD `Simple`. Test menu atteint OK. Compteur 106.
- **Étape 422 :** `Bow Charge Plus`, fichier principal uniquement, patch complémentaire non installé. Test menu atteint OK. Compteur 106.
- **Étape 423 :** `VioLens - A Killmove Mod SE` + `VioLens - A Killmove Mod SE - Settings Loader`. Test menu atteint OK. Compteur 107.
- **Étape 424 :** `No BS AI Projectile Dodge`. Test menu atteint OK. Compteur 108.
- **Étape 425 :** `No Spinning Death Animation Merged LITE`, placé dans `09 - ANIMATIONS SKELETON PHYSICS` sous `SKYFORGE - Pandora Output`. Test menu atteint OK. Compteur 108.

## Décisions structurantes actuelles

- **Nolvus Awakening** est la référence principale pour combat / dodge / animations combat.
- **Nefaram** reste la référence principale pour Body compatible adulte / compatibilité future / systèmes spécialisés différés.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n’est pas retenu comme générateur principal.
- Les réglages TK Dodge RE doivent être des réglages SKYFORGE propres, inspirés de Nolvus Awakening mais adaptés au modpack.
- Ne pas dépendre des fichiers Nolvus Awakening locaux, sauf besoin futur de comparaison avancée.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d’installation, vérifier dans GitHub :

- ce résumé d’état actuel ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Ne jamais reproposer un mod déjà présent dans le snapshot ou les fichiers de procédure.

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
- pas de preuve de malware ;
- pas de preuve de mod Skyrim fautif ;
- pas de preuve que MO2 / SKYFORGE soit directement responsable ;
- MSI Center / services bas niveau à surveiller uniquement si récidive.

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

Profil stable étape 425 :

- SKSE / menu principal : OK
- Aucun master manquant
- Aucun message DLL bloquant
- Plugins cochés
- Overwrite vide
- CrashLogger actif
- Pandora Output actif
- Compteur ESP + ESM non-light : 108
