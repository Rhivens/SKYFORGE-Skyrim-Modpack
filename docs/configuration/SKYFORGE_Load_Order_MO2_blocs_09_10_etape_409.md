# SKYFORGE - État MO2 ciblé - Blocs 09 / 10 - Étape 409

## Statut du document

- Type : état ciblé du panneau gauche MO2 pour les blocs 09 et 10.
- Dernière étape couverte : Étape 409 — Mini-pack combat Nolvus léger.
- Ce fichier ne remplace pas le snapshot complet étape 401.
- Il documente uniquement les blocs modifiés depuis l’étape 401, faute de nouveau copier/coller complet du panneau gauche MO2.

## État technique au moment de l’étape 409

- SKSE / menu principal : OK
- Aucun master manquant : OK
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : 106
- LOOT : non lancé
- BodySlide Output : non généré
- DynDOLOD / LOD : non générés
- Pandora : installé et configuré, mais non lancé / non généré

## Limites importantes

Le copier/coller du panneau gauche ne garantit pas automatiquement l’état coché / décoché de chaque mod.

Convention de lecture :

- Les annotations déjà présentes dans les noms de mods sont conservées telles quelles : `A REINSTALL PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `FOMOD A REVOIR PLUS TARD`, etc.
- En absence d’annotation explicite, le statut exact coché / décoché doit être vérifié dans MO2.
- Ce fichier n’est pas un load order plugin.
- L’ordre plugin sera traité plus tard, après lancement de LOOT et stabilisation des blocs concernés.

## Bloc 09 — ANIMATIONS SKELETON PHYSICS

```text
[09 - ANIMATIONS SKELETON PHYSICS]
Faster HDT-SMP
CBPC - Physics with Collisions - - FPS CONFIG 120 SI SKYRIM LIMITE A 120
XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD
Auto Skeleton Patch - Universal Behaviour Runtime
Open Animation Replacer
SKYFORGE - Open Animation Replacer Output
Animation Motion Revolution
Payload Interpreter
Paired Animation Improvements - PATCHES A VOIR PLUS TARD
Pandora Behaviour Engine v4.3.1-beta
SKYFORGE - Pandora Output
Precision - Accurate Melee Collisions - TK DODGE RE A VERIFIER
True Directional Movement - Modernized Third Person Gameplay
TK Dodge SE
Sound For TK Dodge SE
TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD
Smooth TK Dodge Attack - DAR REQUIREMENT COUVERT PAR OAR
```

## Bloc 10 — GAMEPLAY COMBAT MAGIC PERKS

```text
[10 - GAMEPLAY COMBAT MAGIC PERKS]
Valhalla Combat
Comprehensive Attack Rate Patch - SKSE
```

## Mods ajoutés depuis le snapshot complet étape 401

### Étape 402

- XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD

### Étape 403

- Open Animation Replacer
- SKYFORGE - Open Animation Replacer Output
- Animation Motion Revolution
- Payload Interpreter
- Paired Animation Improvements - PATCHES A VOIR PLUS TARD

### Étape 404

- Auto Skeleton Patch - Universal Behaviour Runtime
- Pandora Behaviour Engine v4.3.1-beta
- SKYFORGE - Pandora Output

### Étape 405

- Precision - Accurate Melee Collisions - TK DODGE RE A VERIFIER

### Étape 406

- True Directional Movement - Modernized Third Person Gameplay

### Étape 407

- TK Dodge SE
- Sound For TK Dodge SE
- TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD

### Étape 408

- Valhalla Combat

### Étape 409

- Smooth TK Dodge Attack - DAR REQUIREMENT COUVERT PAR OAR
- Comprehensive Attack Rate Patch - SKSE

## Notes anti-doublon pour reprise

Avant toute proposition d’installation future, vérifier que le mod n’est pas déjà présent dans :

- ce fichier ciblé blocs 09 / 10 étape 409 ;
- `docs/procedure/09_animations_skeleton_physics_part_1.md` ;
- `docs/procedure/10_gameplay_combat_magic_perks_part_1.md` ;
- `docs/procedure/99_changelog_validation_part_10.md` ;
- le dernier snapshot complet MO2 disponible.

Ne pas reproposer les mods listés ci-dessus.

## Points à revoir plus tard

- XPMSSE : FOMOD à vérifier plus tard pour Weapon Styles / patches spécifiques.
- Paired Animation Improvements : fichiers optionnels différés.
- Pandora : génération non lancée.
- A-Pose Bug Fix - Universal Behavior Runtime : différé.
- Precision Creatures : différé, compatibilité Pandora / requirements Nemesis à vérifier.
- Precision : compatibilité TK Dodge RE à revoir.
- TK Dodge RE : FOMOD à revoir plus tard.
- Smooth TK Dodge Attack : requirement DAR considéré couvert par OAR, à vérifier après génération Pandora / test dodge en jeu.
