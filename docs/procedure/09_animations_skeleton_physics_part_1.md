# SKYFORGE — 09 - ANIMATIONS SKELETON PHYSICS — Part 1

## Objet du fichier

Ce fichier documente l’ouverture et la progression du séparateur :

**09 - ANIMATIONS SKELETON PHYSICS**

Il commence à l'étape 401, car CBPC est installé dans le séparateur 09 même si cette étape reste liée techniquement au choix CBBE 3BA effectué dans le bloc 08.3.

Les étapes 402 à 407 poursuivent ensuite la mise en place du skeleton, des fondations animations modernes, de Pandora, de Precision, de True Directional Movement et de la base dodge Nolvus.

L’étape 409 ajoute également **Smooth TK Dodge Attack** dans ce séparateur. La partie combat gameplay de l’étape 409 est documentée dans `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`.

---

# Étape 401 — Ajout CBPC pour 3BA

## Objectif

Installer le moteur physique CBPC, nécessaire à la configuration 3BA choisie en **SMP and CBPC (Lite)**.

## Mod installé

### CBPC - Physics with Collisions for SSE and VR

- Source : Nexus
- Rôle : moteur physique/collisions utilisé par 3BA
- Plugin : aucun plugin non-light ajouté
- Placement : **09 - ANIMATIONS SKELETON PHYSICS**

## Fichier optionnel non installé

- **3B Breast-Butt Bounce Configs for 3BA-BHUNP-COCO** — différé après choix final des presets BodySlide / OBody / tests en jeu.

## Choix FOMOD CBPC

- FPS Selection / Bounce Config : **120 fps** sélectionné si Skyrim est limité/configuré autour de 120 FPS.

## Validation

- SKSE/menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP/ESM non-light : 102

Décision : **Étape 401 validée**.

---

# Étape 402 — Ajout XPMSSE

## Objectif

Installer le skeleton de référence avant de poursuivre les blocs animations, physique avancée, corps, SexLab et combat.

## Mod ajouté

- **XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD**

## Version installée

- 5.06

## Lien de téléchargement

- Nexus Mods : https://www.nexusmods.com/skyrimspecialedition/mods/1988

## Placement panneau gauche MO2

Sous :

- Faster HDT-SMP
- CBPC - Physics with Collisions

Ordre cible :

1. Faster HDT-SMP
2. CBPC - Physics with Collisions
3. XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD

## Choix FOMOD retenus

- Animation Rig Map : XPMS(S)E Latest
- Ingame Customizing : RaceMenu + XPMS(S)E MCM
- Weapon Style Randomizer : None
- Animation Replacers for XPMS(S)E MCM : None partout
- Animation Replacers for First Person : None
- Compatibility Patches : aucun patch coché

## Choix volontairement différés

- Weapon Styles non activé
- Randomizer NSFW non activé
- Replacers Pretty Combat Animations non activés
- Replacers Magic Nipple Animations non activés
- Patch Schlongs of Skyrim non coché
- Patches Joy of Perspective / Deadly Mutilation / Enderal non cochés

## Raison du différé

XPMSSE est installé ici comme base skeleton propre. Les styles d’armes, replacers d’animations et patches spécifiques seront réévalués plus tard lors des blocs animations, combat et modules adultes masculins.

## Plugin ajouté

- XPMSE.esp

## Impact compteur plugins

- Avant étape : 102 ESP + ESM non-light
- Après étape : 103 ESP + ESM non-light
- Variation : +1

## Tests effectués

- SKSE lancé via MO2 : OK
- Menu principal : OK
- Aucun master manquant : OK
- Plugins cochés : OK
- Overwrite : vide ou contenu identifié

## Verdict

Étape 402 validée. XPMSSE est installé proprement comme skeleton de base. Le mod reste marqué **A VERIFIER FOMOD PLUS TARD**.

---

# Étape 403 — Fondations animations OAR / AMR / Payload / Paired Animations

## Objectif

Installer un premier pack cohérent de fondations modernes pour les animations, sans encore installer de packs d’animations, sans générateur Nemesis/FNIS/Pandora, et sans lancer LOOT.

## Mods ajoutés

- Open Animation Replacer
- SKYFORGE - Open Animation Replacer Output
- Animation Motion Revolution
- Payload Interpreter
- Paired Animation Improvements - PATCHES A VOIR PLUS TARD

## Liens de téléchargement

- Open Animation Replacer : https://www.nexusmods.com/skyrimspecialedition/mods/92109
- Animation Motion Revolution : https://www.nexusmods.com/skyrimspecialedition/mods/50258
- Payload Interpreter : https://www.nexusmods.com/skyrimspecialedition/mods/65089
- Paired Animation Improvements : https://www.nexusmods.com/skyrimspecialedition/mods/99621

## Placement panneau gauche MO2

Ordre retenu dans le séparateur 09 :

1. Faster HDT-SMP
2. CBPC - Physics with Collisions
3. XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD
4. Open Animation Replacer
5. SKYFORGE - Open Animation Replacer Output
6. Animation Motion Revolution
7. Payload Interpreter
8. Paired Animation Improvements - PATCHES A VOIR PLUS TARD

## Choix d’installation

- Open Animation Replacer : fichier principal installé
- Animation Motion Revolution : fichier principal installé
- Payload Interpreter : fichier principal installé
- Paired Animation Improvements : fichier principal installé uniquement

## Fichiers optionnels non installés pour Paired Animation Improvements

- Horse Mount and Dismount Double Sound Fix
- Paired Animation Resources by NickNak

## Raison du différé

Les fichiers optionnels de Paired Animation Improvements ne sont pas nécessaires pour l’étape 403. Ils seront réévalués uniquement si un mod futur les demande explicitement ou si un problème d’animation montée/descente cheval apparaît.

## Overwrite

Open Animation Replacer a généré dans Overwrite :

- SKSE/Plugins/OpenAnimationReplacer.ini
- SKSE/Plugins/OpenAnimationReplacer_Imgui.ini

Ces fichiers ont été déplacés dans un mod dédié :

- SKYFORGE - Open Animation Replacer Output

## Plugins ajoutés

Aucun plugin ESP/ESM non-light ajouté.

## Impact compteur plugins

- Avant étape : 103 ESP + ESM non-light
- Après étape : 103 ESP + ESM non-light
- Variation : 0

## Verdict

Étape 403 validée. Les fondations animations modernes sont installées proprement. OAR dispose d’un Output dédié et Overwrite est vide.

---

# Étape 404 — Préparation Pandora Behaviour Engine Plus

## Objectif

Installer et préparer Pandora comme générateur de comportements/animations pour SKYFORGE, sans lancer de génération pour l’instant.

## Décision

Nemesis n’est pas retenu pour SKYFORGE. Le générateur choisi est :

- Pandora Behaviour Engine Plus

## Mods ajoutés

- Universal Behaviour Runtime - Auto Skeleton Patch
- Pandora Behaviour Engine Plus - NE PAS GENERER POUR L’INSTANT
- SKYFORGE - Pandora Output

## Liens de téléchargement

- Pandora Behaviour Engine Plus : https://www.nexusmods.com/skyrimspecialedition/mods/133232
- Universal Behaviour Runtime - Auto Skeleton Patch : https://www.nexusmods.com/skyrimspecialedition/mods/176724

## Dépendance Pandora vérifiée

La page de Pandora indique :

- Universal Behaviour Runtime - Auto Skeleton Patch est requis si XPMSSE ou un autre skeleton mod est utilisé.
- A-Pose Bug Fix - Universal Behavior Runtime est requis uniquement pour la rétrocompatibilité avec des animations/behaviors LE.

## Mod différé

- A-Pose Bug Fix - Universal Behavior Runtime

## Raison du différé

Aucune animation ou behavior LE n’est installé à cette étape. Le correctif A-Pose sera réévalué uniquement si un futur mod en a besoin ou si un problème A-pose apparaît.

## Placement panneau gauche MO2

Ordre retenu dans le séparateur 09 :

1. Faster HDT-SMP
2. CBPC - Physics with Collisions
3. XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD
4. Universal Behaviour Runtime - Auto Skeleton Patch
5. Open Animation Replacer
6. SKYFORGE - Open Animation Replacer Output
7. Animation Motion Revolution
8. Payload Interpreter
9. Paired Animation Improvements - PATCHES A VOIR PLUS TARD
10. Pandora Behaviour Engine Plus - NE PAS GENERER POUR L’INSTANT
11. SKYFORGE - Pandora Output

## Fichier Pandora choisi

- Main files : Pandora Behaviour Engine v4.3.1-beta

## Fichier Pandora non choisi

- Optional files : Pandora Behaviour Engine Preview
- Old files : non installés

## Exécutable MO2 créé

Titre :

- Pandora Behaviour Engine+

Configuration :

- Binary : Pandora Behaviour Engine+.exe
- Start in : dossier du mod Pandora
- Arguments : vide
- Create files in mod instead of overwrite : SKYFORGE - Pandora Output

## Correction effectuée

Les anciens arguments suivants ont été retirés :

- `-o;`
- `-tesv`

Raison : ces arguments sont indiqués comme dépréciés sur la page de Pandora. La configuration des chemins doit désormais se faire directement dans Pandora.

## Génération Pandora

- Pandora installé : oui
- Exécutable créé : oui
- Output dédié créé : oui
- Génération Pandora lancée : non

## Impact compteur plugins

- Avant étape : 103 ESP + ESM non-light
- Après étape : 104 ESP + ESM non-light
- Variation : +1

## Verdict

Étape 404 validée. Pandora Behaviour Engine Plus est installé et préparé. Aucune génération Pandora n’a encore été lancée.

---

# Étape 405 — Precision / collisions de mêlée

## Objectif

Installer la base des collisions de combat modernes avec Precision, sans encore installer les modules créatures ni lancer Pandora.

## Mod ajouté

- Precision - Accurate Melee Collisions - FOMOD A REVOIR PLUS TARD (TK DODGE)

## Lien de téléchargement

- Precision - Accurate Melee Collisions : https://www.nexusmods.com/skyrimspecialedition/mods/72347

## Placement panneau gauche MO2

Dans le séparateur 09, après Pandora / Output :

1. Pandora Behaviour Engine Plus - NE PAS GENERER POUR L’INSTANT
2. SKYFORGE - Pandora Output
3. Precision - Accurate Melee Collisions - FOMOD A REVOIR PLUS TARD (TK DODGE)

## Choix FOMOD retenu

Compatibility :

- None

## Options non cochées

- TK Dodge or Ultimate Combat
- TK Dodge RE

## Raison du choix

TK Dodge / TK Dodge RE n’est pas encore installé dans SKYFORGE. Aucun patch de compatibilité n’est activé pour un mod absent. Le FOMOD devra être réévalué si TK Dodge RE est intégré plus tard dans le bloc combat / dodge.

## Mods différés

- Precision Creatures — DIFFERE / PANDORA COMPATIBILITE A VERIFIER
- A-Pose Bug Fix - Universal Behavior Runtime — différé

## Raison du différé Precision Creatures

La page de Precision Creatures liste encore comme requirements :

- Nemesis Creature Behaviour Compatibility
- Precision - Accurate Melee Collisions
- Project New Reign - Nemesis Unlimited Behavior Engine

Comme SKYFORGE utilise Pandora et non Nemesis, Precision Creatures n’est pas installé à cette étape. Il sera réévalué plus tard après validation de la première génération Pandora et avant l’intégration d’animations créatures.

## Impact compteur plugins

- Avant étape : 104 ESP + ESM non-light
- Après étape : 104 ESP + ESM non-light
- Variation : 0

## Verdict

Étape 405 validée. Precision est installé avec le choix FOMOD **None**.

---

# Étape 406 — True Directional Movement

## Objectif

Installer la base du déplacement moderne en 3e personne.

## Mod ajouté

- True Directional Movement - Modernized Third Person Gameplay

## Lien

- https://www.nexusmods.com/skyrimspecialedition/mods/51614

## Placement

Dans le séparateur :

- 09 - ANIMATIONS SKELETON PHYSICS

Ordre final validé du bloc 09 après étape 406 :

1. Faster HDT-SMP
2. CBPC - Physics with Collisions - - FPS CONFIG 120 SI SKYRIM LIMITE A 120
3. XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD
4. Auto Skeleton Patch - Universal Behaviour Runtime
5. Open Animation Replacer
6. SKYFORGE - Open Animation Replacer Output
7. Animation Motion Revolution
8. Payload Interpreter
9. Paired Animation Improvements - PATCHES A VOIR PLUS TARD
10. Pandora Behaviour Engine v4.3.1-beta
11. SKYFORGE - Pandora Output
12. Precision - Accurate Melee Collisions - FOMOD A REVOIR PLUS TARD (TK DODGE)
13. True Directional Movement - Modernized Third Person Gameplay

## Impact plugins

- Avant étape : 104 ESP + ESM non-light
- Après étape : 104 ESP + ESM non-light
- Variation : 0

## Verdict

Étape 406 validée. True Directional Movement est installé proprement.

---

# Étape 407 — TK Dodge / base dodge Nolvus

## Objectif

Installer la base dodge inspirée de la logique combat Nolvus, avec TK Dodge SE, Sound For TK Dodge SE et TK Dodge RE, sans lancer Pandora.

## Référence de décision

- Combat / dodge / animations combat : référence Nolvus
- NSFW / SexLab / defeat / slavery / prostitution : référence Nefaram

## Mods ajoutés

- TK Dodge SE
- Sound For TK Dodge SE
- TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD

## Liens

- TK Dodge SE : https://www.nexusmods.com/skyrimspecialedition/mods/15309
- Sound For TK Dodge SE : https://www.nexusmods.com/skyrimspecialedition/mods/39689
- TK Dodge RE - Script Free : https://www.nexusmods.com/skyrimspecialedition/mods/56956

## Choix TK Dodge SE

- Fichier principal TK Dodge SE installé
- Le fichier optionnel “TK Dodge For RE” n’a pas été retenu seul, car la logique combat suivie est celle de Nolvus.

## Choix TK Dodge RE FOMOD

Options non cochées :

- Enable Sheathed Dodge
- Cancel concentration spell when dodging
- Remove Blocking Cancel Attack
- Old version dll plugin
- Forward dodge scurry fix
- Allow dodging when stagger
- TK dodge standalone

## Precision réinstallé

Precision a été réinstallé après ajout de TK Dodge RE.

Résultat :

- Option TK Dodge RE visible mais non sélectionnable dans le FOMOD
- Choix conservé : None

Note :

- Precision - Accurate Melee Collisions - TK DODGE RE A VERIFIER
- À vérifier plus tard après première génération Pandora / bloc combat Nolvus.

## Placement panneau gauche MO2

Dans le séparateur 09, après True Directional Movement :

1. Precision - Accurate Melee Collisions - TK DODGE RE A VERIFIER
2. True Directional Movement - Modernized Third Person Gameplay
3. TK Dodge SE
4. Sound For TK Dodge SE
5. TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD

## Impact plugins

- Avant étape : 104 ESP + ESM non-light
- Après étape : 105 ESP + ESM non-light
- Variation : +1

## Verdict

Étape 407 validée. La base dodge Nolvus est installée. TK Dodge RE est installé avec FOMOD minimal. Precision reste en compatibilité None.

---

# Étape 409 — Smooth TK Dodge Attack côté animations

## Objectif

Ajouter la partie animation du mini-pack combat Nolvus léger, sans lancer Pandora.

## Mod ajouté dans le séparateur 09

- Smooth TK Dodge Attack — DAR REQUIREMENT COUVERT PAR OAR

## Lien

- Smooth TK Dodge Attack : https://www.nexusmods.com/skyrimspecialedition/mods/63215

## Placement

- Smooth TK Dodge Attack : bloc 09, sous TK Dodge RE

## Note

Smooth TK Dodge Attack liste Dynamic Animation Replacer comme requirement Nexus. SKYFORGE utilise Open Animation Replacer à la place. À vérifier après génération Pandora / test dodge en jeu.

## Impact plugins

- Avant étape 409 : 106 ESP + ESM non-light
- Après étape 409 : 106 ESP + ESM non-light
- Variation : 0

## Verdict

Étape 409 validée côté animations. Smooth TK Dodge Attack est installé dans le bloc 09.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 409**, partiellement côté animations
- Dernière étape complète du séparateur 09 : **Étape 407 — TK Dodge / base dodge Nolvus**
- Séparateur 09 : fondations skeleton / animations / physics / dodge installées
- Pandora : installé et configuré, mais **non lancé / non généré**
- Compteur ESP + ESM non-light global après étape 409 : **106**
- Overwrite : vide
- BodySlide Output : non généré
- LOOT : non lancé
- DynDOLOD / LOD : non générés
