# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape d’installation validée :** Étape 409 — Mini-pack combat Nolvus léger
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module parent lié :** 09 / 10 — animations, skeleton, physics et début combat gameplay
- **Dernier bloc technique consolidé :** 09 - ANIMATIONS SKELETON PHYSICS, fondations installées jusqu’à TK Dodge / OAR / Pandora préparé
- **Prochaine étape attendue :** Étape 410 — à déterminer après audit du bloc combat / animations, sans doublon avec les mods déjà installés

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
- **Compteur ESP + ESM non-light :** 106
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** installé et configuré, mais non lancé / non généré

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/99_changelog_validation_part_10.md`
3. `docs/procedure/09_animations_skeleton_physics_part_1.md`
4. `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
5. `docs/configuration/SKYFORGE_Load_Order_MO2_blocs_09_10_etape_409.md`

## Note de transition importante — Étapes 401 à 409

L’étape 401 a ouvert officiellement le séparateur **09 - ANIMATIONS SKELETON PHYSICS** avec CBPC.

Les étapes 402 à 407 ont ensuite installé les fondations skeleton / animations / dodge :

- XPMSSE ;
- Open Animation Replacer ;
- Animation Motion Revolution ;
- Payload Interpreter ;
- Paired Animation Improvements ;
- Universal Behaviour Runtime - Auto Skeleton Patch ;
- Pandora Behaviour Engine Plus ;
- Precision ;
- True Directional Movement ;
- TK Dodge SE / Sound For TK Dodge SE / TK Dodge RE.

L’étape 408 a ouvert le séparateur **10 - GAMEPLAY COMBAT MAGIC PERKS** avec Valhalla Combat.

L’étape 409 a ajouté un mini-pack combat Nolvus léger réparti entre :

- le bloc 09 pour **Smooth TK Dodge Attack** ;
- le bloc 10 pour **Comprehensive Attack Rate Patch - SKSE**.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d’installation, vérifier dans GitHub :

- ce résumé d’état actuel ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Ne jamais reproposer un mod déjà présent dans le snapshot ou les fichiers de procédure.

## Étapes récentes validées

- Étape 401 — CBPC installé dans le séparateur 09 pour compléter la configuration 3BA SMP + CBPC Lite.
- Étape 402 — XPMSSE 5.06 installé comme skeleton de référence ; plugin `XPMSE.esp` ajouté ; compteur 103.
- Étape 403 — Fondations animations modernes : Open Animation Replacer, OAR Output, AMR, Payload Interpreter, Paired Animation Improvements ; compteur 103.
- Étape 404 — Pandora Behaviour Engine Plus préparé avec Auto Skeleton Patch et Output dédié ; Pandora non généré ; compteur 104.
- Étape 405 — Precision installé avec FOMOD `None`, Precision Creatures différé ; compteur 104.
- Étape 406 — True Directional Movement installé ; compteur 104.
- Étape 407 — Base dodge Nolvus : TK Dodge SE, Sound For TK Dodge SE, TK Dodge RE ; compteur 105.
- Étape 408 — Valhalla Combat installé dans le bloc 10 ; compteur 106.
- Étape 409 — Smooth TK Dodge Attack + Comprehensive Attack Rate Patch - SKSE ; compteur 106.

## Décisions et différés importants

### Module 08.3 — Body / skins / BodySlide

- **CBBE :** installé, morphs et BodySlide output différés.
- **CBBE 3BA :** installé, options SOS / collisions adultes à revoir plus tard.
- **TNG :** installé en logique Nefaram ; à surveiller pour éviter le problème de trou mesh sexe vu ailleurs.
- **TNG dll fix Nefaram :** différé jusqu’à vérification de version / compatibilité.
- **PB's Silky Skin :** choix skin PJ féminin à terme, actuellement écrasé probablement par BnP tant que l’isolation PJ n’est pas faite.
- **BnP Female Skin :** skin féminine globale / NPC temporaire.
- **Tempered Skins for Males :** skin masculin validé avec TNG.
- **OBody NG :** souhaité pour diversité NPC, mais différé après presets BodySlide et base stabilisée.
- **Unique Player / Unique Character :** différé après choix skin NPC / BodySlide / OBody.
- **BodySlide Output :** non généré.

### Module 09 — Animations / skeleton / physics

- **FSMP :** déjà validé, Skyrim 1.5.97 / NOT CUDA / AVX2 / FSMP MCM installé.
- **CBPC :** installé comme moteur physique complémentaire requis par 3BA SMP + CBPC Lite.
- **XPMSSE :** installé étape 402, FOMOD à vérifier plus tard pour Weapon Styles / patches spécifiques.
- **Open Animation Replacer :** installé, INI isolés dans `SKYFORGE - Open Animation Replacer Output`.
- **Pandora Behaviour Engine Plus :** générateur retenu à la place de Nemesis ; installé mais non lancé.
- **Precision :** installé, option TK Dodge RE à vérifier plus tard.
- **TK Dodge RE :** installé avec FOMOD minimal ; base dodge Nolvus présente.
- **Smooth TK Dodge Attack :** installé, requirement DAR considéré couvert par OAR ; à vérifier après génération Pandora / test dodge en jeu.

### Module 10 — Gameplay / combat / magic / perks

- **Valhalla Combat :** installé comme premier overhaul combat majeur issu de la logique Nolvus.
- **Comprehensive Attack Rate Patch - SKSE :** installé sous Valhalla Combat.
- Le bloc 10 est désormais ouvert.

### Différés / points à revoir

- **BodySlide Output :** non généré.
- **Pandora :** non lancé / non généré.
- **LOOT :** non lancé.
- **DynDOLOD / LOD :** non générés.
- **XPMSSE :** FOMOD à vérifier plus tard.
- **Paired Animation Improvements :** optionnels à revoir seulement si besoin.
- **A-Pose Bug Fix - Universal Behavior Runtime :** différé.
- **Precision Creatures :** différé, compatibilité Pandora / requirements Nemesis à vérifier.
- **Precision / TK Dodge RE :** compatibilité à vérifier après génération Pandora / bloc combat.
- **TK Dodge RE :** FOMOD à revoir plus tard.

### Exclusions adultes confirmées

- Aucun contenu Futanari.
- Aucun Female Schlong.
- Aucun Gender Bender.
- The New Gentlewoman exclu.
- SL Gender Bender for TNG exclu.
- Tanlines / pubes / pubic hair overlays exclus.

## Vigilances conservées

- **Nolvus Awakening :** référence principale pour combat / dodge / animations combat.
- **Nefaram :** référence principale pour NSFW / SexLab / defeat / slavery / prostitution.
- **Breezehome :** version Nefaram à vérifier / privilégier lors du bloc maisons.
- **Temple de Dibella :** contrôle futur avec quêtes adultes, PNJ, scènes, marqueurs, navmesh et lighting.
- **Snazzy Furniture and Clutter Overhaul :** aucun addon de maison joueur coché.
- **Simple Children :** exclu, bloquait au chargement avant menu ; remplacé par RS Children Overhaul.

## Dernier état stable

Profil stable étape 409 :

- SKSE / menu principal : OK
- Aucun master manquant
- Plugins cochés
- Overwrite vide
- Compteur ESP + ESM non-light : 106
