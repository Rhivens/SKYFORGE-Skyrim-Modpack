# Changelog / validation — partie 12

## Périmètre

Cette partie couvre la progression SKYFORGE des étapes **416 à 425**.

Elle concerne principalement :

- la reprise du module **10 - GAMEPLAY COMBAT MAGIC PERKS** après stabilisation étape 415 ;
- l’ajout de petits modules gameplay / combat issus de **Nolvus Awakening** ;
- la poursuite prudente sans gros overhaul combat ;
- la documentation de l’incident Windows isolé survenu à l’étape 420 ;
- l’ajout d’un correctif d’animation placé dans le séparateur 09 à l’étape 425.

## État final validé

- **Dernière étape validée :** Étape 425 — No Spinning Death Animation Merged LITE
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **SKSE / menu principal :** OK
- **Masters manquants :** aucun
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 108
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré à l’étape 411, non relancé depuis
- **CrashLogger :** actif avec PDB support 1.5.97

## Étapes validées — résumé synthétique

- **Étape 416 :** installation de `Wait Your Turn - Enemy Circling Behaviour`, issu de Nolvus Awakening. Test menu atteint OK. Compteur : 106.
- **Étape 417 :** installation de `NPCs Take Cover - Smarter Anti-Cheese AI`, issu de Nolvus Awakening. Test menu atteint OK. Compteur : 106.
- **Étape 418 :** installation de `NPC No Block - Exhaustion` et `NPC No Block Exhaustion - MCM`. Test menu atteint OK. Compteur : 106.
- **Étape 419 :** installation de `Stagger Effect Fix NG` dans le bloc `02 - BUG FIXES & ENGINE PATCHES`, sous `OnMagicEffectApply Replacer`. Test menu atteint OK. Compteur : 106.
- **Étape 420 :** mini-bloc `3rd Person Camera Stagger Remover` + `Block Enchantments`. Premier lancement marqué par un redémarrage Windows isolé, puis tests isolés réussis et non-reproduction. Étape validée. Compteur : 106.
- **Étape 421 :** installation de `Archery Locational Damage`, option FOMOD `Simple`. Test menu atteint OK. Compteur : 106.
- **Étape 422 :** installation de `Bow Charge Plus`, fichier principal uniquement, patch complémentaire non installé. Test menu atteint OK. Compteur : 106.
- **Étape 423 :** installation de `VioLens - A Killmove Mod SE` et `VioLens - A Killmove Mod SE - Settings Loader`. FOMOD VioLens en Core Files `Archive`, sans Reaction ni Premade Profiles. Test menu atteint OK. Compteur : 107.
- **Étape 424 :** installation de `No BS AI Projectile Dodge`. Test menu atteint OK. Compteur : 108.
- **Étape 425 :** installation de `No Spinning Death Animation Merged LITE`, placé dans le séparateur 09 sous `SKYFORGE - Pandora Output`. Test menu atteint OK. Compteur : 108.

## Incident Windows isolé — étape 420

Un redémarrage complet Windows est survenu lors du premier test de l’étape 420.

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
- non reproduit après tests séparés et retests ;
- pas de preuve de malware ;
- pas de preuve de mod Skyrim fautif ;
- pas de preuve que MO2 / SKYFORGE soit directement responsable ;
- MSI Center / services bas niveau à surveiller si récidive.

## Décisions structurantes maintenues

- Nolvus Awakening reste la référence principale pour ce bloc gameplay / combat.
- Nefaram reste réservé aux modules body / compatibilité future / systèmes spécialisés ultérieurs.
- Pandora Behaviour Engine Plus reste le générateur retenu.
- Nemesis n’est pas retenu comme générateur principal.
- `Precision - Creatures` reste différé.
- Aucune dépendance aux fichiers locaux de Nolvus Awakening n’est introduite.

## Vigilances restantes

- BodySlide Output non généré.
- XPMSSE FOMOD à revoir plus tard avant animations avancées / styles d’armes.
- LeveledList Crash Fix AE + 1.5 à vérifier hors urgence.
- LOOT non lancé.
- DynDOLOD / LOD non générés.
- Mods `- FR` toujours volontairement décochés.
- Mod fautif CTD étape 413 à garder décoché / différé.
- Incident Windows étape 420 à surveiller uniquement si récidive.

## Références détaillées

Pour le détail complet des étapes :

- `docs/procedure/10_gameplay_combat_magic_perks_part_2.md`
- `docs/procedure/09_animations_skeleton_physics_part_3.md`
- `docs/procedure/99_changelog_validation_part_11.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`
