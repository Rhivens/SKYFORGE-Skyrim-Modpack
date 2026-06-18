# Changelog / validation — partie 13

## Périmètre

Cette partie couvre la progression SKYFORGE des étapes **426 à 434**.

Elle concerne principalement :

- la validation gameplay ciblée post-ajouts combat / archerie ;
- l’ajout de modules légers issus de **Nolvus Awakening** ;
- la poursuite du séparateur **10 - GAMEPLAY COMBAT MAGIC PERKS** ;
- l’ajout de confort NPC, potions, dialogues, collision, caméra et interaction ;
- la documentation d’une étape annulée pour doublons déjà présents ;
- le maintien strict des outils différés : LOOT, DynDOLOD, BodySlide et Pandora.

## État final validé

- **Dernière étape validée :** Étape 434 — A Closer Look SSE
- **Profil :** stable
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
- **Mods `- FR` :** toujours non activés

## Étapes validées — résumé synthétique

- **Étape 426 :** test gameplay ciblé post-ajouts combat / archerie, durée 15 minutes. Aucun CTD, aucun reboot Windows, combats mains nues / épée-bouclier / arc OK, MCM accessibles, sortie Unbound et Riverwood OK. Anomalie graphique non bloquante dans Giant Inn : objets flottants à corriger plus tard. Aucun nouveau mod installé. Compteur : 108.
- **Étape 427 :** installation de `NPCs Use Potions` + `NPCs Use Potions - SKYFORGE Config`. FOMOD limité au profil actuel : Base Game et Poison Dosage Preset cochés, modules New Lands / Dungeon Mods / Overland / Creature / Followers décochés. FOMOD à revoir plus tard si nouveaux mondes / quêtes / donjons / créatures. Incident écran noir non reproduit, non bloquant. Test menu atteint OK. Compteur : 108.
- **Étape 428 :** installation de `Smart Optimal Salves - Optimal Potion Hotkey MCM` + `Optimal Potion Hotkey MCM - Settings Loader`. Hotkeys non configurées maintenant, à reprendre plus tard avec Startup Save / MCM Recorder. Test menu atteint OK. Compteur : 108.
- **Étape 429 :** installation de `Simple Offence Suppression` + `Simple Offence Suppression MCM - Block Friendly Fire`. MCM non configuré maintenant, à reprendre plus tard avec Startup Save / MCM Recorder. Test menu atteint OK. Compteur : 108.
- **Étape 430 :** installation de `I’m Talkin’ Here` + `Instantly Skip Dialogue NG`. Aucun patch follower ajouté pour l’instant. Test menu atteint OK. Compteur : 108.
- **Étape 431 :** installation de `Disable Follower Collision` + `I’m Walkin’ Here` version `1.5.0`, compatible Skyrim `1.5.50 - 1.5.97`. Version `1.7.0` non installée car prévue pour Skyrim `1.6.640+`. Test menu atteint OK. Compteur : 108.
- **Étape 432 :** installation de `No Furniture Camera` + `Pick Up Radius`. MCM de `Pick Up Radius` non configuré maintenant, à reprendre plus tard avec Startup Save / MCM Recorder. Test menu atteint OK. Compteur : 108.
- **Étape 433 :** étape annulée après vérification anti-doublon. `Use Or Take SKSE`, `Read Or Take SKSE` et `Favorite Misc Items` étaient déjà installés. Aucune installation effectuée, aucun compteur modifié.
- **Étape 434 :** installation de `A Closer Look SSE`. Version SSE installée, version NG non installée par prudence avec Skyrim SE 1.5.97. MCM non configuré maintenant, à reprendre plus tard avec Startup Save / MCM Recorder. Test menu atteint OK. Compteur : 108.

## Incidents / anomalies maintenus

### Étape 420 — incident Windows isolé

L’incident Windows / BSOD de l’étape 420 reste considéré comme isolé et non bloquant.

Aucune récidive signalée sur les étapes 426 à 434.

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

## Décisions structurantes maintenues

- Nolvus Awakening reste la référence principale pour ce bloc gameplay / combat.
- Nefaram reste réservé aux modules body / compatibilité future / systèmes spécialisés ultérieurs.
- Pandora Behaviour Engine Plus reste le générateur retenu.
- Nemesis n’est pas retenu comme générateur principal.
- `Precision - Creatures` reste différé.
- Aucune dépendance aux fichiers locaux de Nolvus Awakening n’est introduite.
- Les réglages MCM non urgents seront repris plus tard avec la logique Startup Save / MCM Recorder.

## Vigilances restantes

- BodySlide Output non généré.
- XPMSSE FOMOD à revoir plus tard avant animations avancées / styles d’armes.
- LeveledList Crash Fix AE + 1.5 à vérifier hors urgence.
- LOOT non lancé.
- DynDOLOD / LOD non générés.
- Mods `- FR` toujours volontairement décochés.
- Mod fautif CTD étape 413 à garder décoché / différé.
- Incident Windows étape 420 à surveiller uniquement si récidive.
- `Precision - Creatures` reste différé.
- Bug graphique Riverwood Giant Inn : objets flottants à corriger plus tard.

## Références détaillées

Pour le détail complet des étapes :

- `docs/procedure/10_gameplay_combat_magic_perks_part_3.md`
- `docs/procedure/10_gameplay_combat_magic_perks_part_2.md`
- `docs/procedure/09_animations_skeleton_physics_part_3.md`
- `docs/procedure/99_changelog_validation_part_12.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`
