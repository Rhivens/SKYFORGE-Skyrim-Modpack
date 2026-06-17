# Changelog / validation — partie 10

## Périmètre

Cette partie couvre la progression SKYFORGE des étapes **402 à 409**.

Elle concerne principalement :

- la consolidation du séparateur **09 - ANIMATIONS SKELETON PHYSICS** ;
- l’installation de XPMSSE ;
- les fondations animations modernes OAR / AMR / Payload / Paired Animations ;
- la préparation de Pandora Behaviour Engine Plus ;
- l’installation de Precision, True Directional Movement et TK Dodge ;
- l’ouverture du séparateur **10 - GAMEPLAY COMBAT MAGIC PERKS** avec Valhalla Combat ;
- l’ajout d’un mini-pack combat Nolvus léger.

## État final validé

- **Dernière étape validée :** Étape 409 — Mini-pack combat Nolvus léger
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **SKSE / menu principal :** OK
- **Masters manquants :** aucun
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 106
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** installé et configuré, mais non lancé / non généré

## Étapes validées — résumé synthétique

- **Étape 402 :** XPMSSE 5.06 installé comme skeleton de référence. FOMOD minimal, Weapon Styles / patches spécifiques différés. Plugin ajouté : `XPMSE.esp`. Compteur : 103.
- **Étape 403 :** Open Animation Replacer, OAR Output, Animation Motion Revolution, Payload Interpreter et Paired Animation Improvements installés. OAR a généré deux INI isolés dans un mod Output dédié. Compteur : 103.
- **Étape 404 :** Pandora Behaviour Engine Plus préparé avec Universal Behaviour Runtime - Auto Skeleton Patch et `SKYFORGE - Pandora Output`. Exécutable MO2 créé. Arguments dépréciés retirés. Pandora non généré. Compteur : 104.
- **Étape 405 :** Precision installé avec FOMOD `None`. Precision Creatures différé pour vérification compatibilité Pandora / requirements Nemesis. Compteur : 104.
- **Étape 406 :** True Directional Movement installé dans le séparateur 09. Compteur : 104.
- **Étape 407 :** TK Dodge SE, Sound For TK Dodge SE et TK Dodge RE installés comme base dodge Nolvus. Precision réinstallé mais compatibilité TK Dodge RE restée sur `None`, option visible mais non sélectionnable. Compteur : 105.
- **Étape 408 :** Valhalla Combat installé dans le séparateur 10 - GAMEPLAY COMBAT MAGIC PERKS. Compteur : 106.
- **Étape 409 :** Smooth TK Dodge Attack installé dans le bloc 09 et Comprehensive Attack Rate Patch - SKSE installé dans le bloc 10. Compteur : 106.

## Décisions structurantes

- Nemesis n’est pas retenu pour SKYFORGE à ce stade.
- Pandora Behaviour Engine Plus est le générateur choisi.
- Pandora est installé, configuré et dispose d’un output dédié, mais aucune génération n’a encore été lancée.
- Open Animation Replacer remplace Dynamic Animation Replacer dans la logique SKYFORGE.
- Smooth TK Dodge Attack liste DAR comme requirement Nexus, mais SKYFORGE considère ce requirement couvert par OAR ; vérification future après génération Pandora / test dodge en jeu.
- Combat / dodge / animations combat : référence Nolvus.
- NSFW / SexLab / defeat / slavery / prostitution : référence Nefaram.
- Le séparateur 10 est officiellement ouvert depuis l’étape 408.

## Différés majeurs

- XPMSSE : FOMOD à vérifier plus tard pour Weapon Styles / patches spécifiques.
- Paired Animation Improvements : optionnels à revoir seulement si un mod futur les demande ou si un problème cheval apparaît.
- A-Pose Bug Fix - Universal Behavior Runtime : différé tant qu’aucun comportement LE ne l’exige.
- Precision Creatures : différé, compatibilité Pandora / requirements Nemesis à vérifier.
- Precision : compatibilité TK Dodge RE à revoir après première génération Pandora / bloc combat.
- TK Dodge RE : FOMOD à revoir plus tard.
- Pandora : génération non lancée.
- LOOT : non lancé.
- BodySlide Output : non généré.
- DynDOLOD / LOD : non générés.

## Références détaillées

Pour le détail complet des étapes :

- `docs/procedure/09_animations_skeleton_physics_part_1.md`
- `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_blocs_09_10_etape_409.md`
