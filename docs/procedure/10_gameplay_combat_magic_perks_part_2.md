# SKYFORGE — 10 - GAMEPLAY COMBAT MAGIC PERKS — Part 2

## Objet du fichier

Ce fichier poursuit la documentation du séparateur :

**10 - GAMEPLAY COMBAT MAGIC PERKS**

Il couvre les étapes **416 à 424**, centrées sur un bloc gameplay / combat léger inspiré de **Nolvus Awakening**, sans ajout de gros overhaul combat et sans relancer Pandora, LOOT, DynDOLOD ou BodySlide.

---

# Étape 416 — Wait Your Turn - Enemy Circling Behaviour

## Objectif

Ajouter un mod léger de comportement de groupe afin de limiter l’effet d’empilement des ennemis autour du joueur, sans remplacer Valhalla Combat, TK Dodge RE, Precision ou True Directional Movement.

## Mod installé

- `Wait Your Turn - Enemy Circling Behaviour`

## Origine

- Nolvus Awakening

## Sources

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/65091
- Fichiers : https://www.nexusmods.com/skyrimspecialedition/mods/65091?tab=files

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 416 validée.

Le compteur reste à 106, donc aucun impact non-light constaté.

---

# Étape 417 — NPCs Take Cover - Smarter Anti-Cheese AI

## Objectif

Ajouter un ajustement léger d’IA de combat afin que les NPC réagissent mieux aux attaques à distance depuis des positions abusives ou difficiles d’accès.

## Mod installé

- `NPCs Take Cover - Smarter Anti-Cheese AI`

## Origine

- Nolvus Awakening

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/111890
- Fichiers : https://www.nexusmods.com/skyrimspecialedition/mods/111890?tab=files

## Vérification anti-doublon

Le mod était absent du snapshot MO2 documenté avant installation.

## Rôle SKYFORGE

Ce mod ne constitue pas un overhaul combat majeur.

Il complète le comportement des NPC contre certains abus à distance. Il repose sur SPID, déjà présent dans SKYFORGE.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 417 validée.

---

# Étape 418 — NPC No Block Exhaustion + MCM

## Objectif

Ajouter un mini-bloc lié à la gestion du blocage NPC et de l’épuisement, cohérent avec Valhalla Combat.

## Mods installés

1. `NPC No Block - Exhaustion`
2. `NPC No Block Exhaustion - MCM`

## Origine

- Nolvus Awakening

## Sources

- NPC No Block - Exhaustion : https://www.nexusmods.com/skyrimspecialedition/mods/118095
- Fichiers : https://www.nexusmods.com/skyrimspecialedition/mods/118095?tab=files
- NPC No Block Exhaustion - MCM : https://www.nexusmods.com/skyrimspecialedition/mods/118359
- Fichiers : https://www.nexusmods.com/skyrimspecialedition/mods/118359?tab=files

## Rôle SKYFORGE

Le mod principal empêche les NPC de continuer à bloquer lorsqu’ils sont en état d’épuisement.

Le second mod ajoute un MCM pour régler les variables du mod principal.

## Vérification anti-doublon

Les deux mods étaient absents du snapshot MO2 documenté avant installation.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 418 validée.

---

# Étape 419 — Stagger Effect Fix NG

## Objectif

Ajouter un correctif SKSE léger lié aux effets de stagger, sans toucher à Pandora.

## Mod installé

- `Stagger Effect Fix NG`

## Origine

- Nolvus Awakening

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/110508
- Fichiers : https://www.nexusmods.com/skyrimspecialedition/mods/110508?tab=files

## Rôle SKYFORGE

Corriger un bug moteur où certains effets magiques ou cris peuvent provoquer un stagger dans une direction incorrecte.

## Placement MO2

- Séparateur : `02 - BUG FIXES & ENGINE PATCHES`
- Placement confirmé : sous `OnMagicEffectApply Replacer`

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 419 validée.

---

# Étape 420 — Mini-bloc combat léger : stagger caméra + block enchantments

## Objectif

Ajouter deux ajustements légers issus de Nolvus Awakening, sans relancer Pandora, LOOT, DynDOLOD ou BodySlide.

## Mods installés

### 1. 3rd Person Camera Stagger Remover

- Source Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/25316
- Origine : Nolvus Awakening
- Rôle : supprime le stagger / tremblement caméra en troisième personne.

### 2. Block Enchantments

- Source Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/60833
- Origine : Nolvus Awakening
- Rôle : permet de bloquer les effets d’enchantement.
- Dépendance logique : SPID déjà présent dans SKYFORGE.
- Plugin actif : `blockenchantments.esl`
- Chargement : FE / ESL-light.

## Incident Windows pendant le premier test

Un redémarrage complet Windows est survenu lors du premier lancement après installation du mini-bloc.

Message Windows :

```text
Votre appareil a rencontré un problème et doit être redémarré.
```

Décision immédiate :

- retour à l’état 419 ;
- désactivation des deux mods de l’étape 420 ;
- test SKSE / menu de contrôle.

Résultat retour étape 419 :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Aucun reboot
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Tests isolés

### Test 420A — 3rd Person Camera Stagger Remover seul

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Aucun reboot
- Overwrite vide
- Compteur ESP + ESM non-light : 106

Décision : `3rd Person Camera Stagger Remover` validé.

### Test 420B — ajout de Block Enchantments

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Aucun reboot
- Tous les plugins cochés
- Overwrite vide
- Compteur ESP + ESM non-light : 106

MO2 a affiché temporairement :

```text
Plugin not found: blockenchantments.esl
```

Vérification effectuée :

- le plugin est visible et actif dans le panneau droit MO2 ;
- le plugin apparaît dans le load order ;
- `blockenchantments.esl` est chargé en FE ;
- aucun master manquant ;
- aucun crash ou reboot reproduit.

Décision : warning MO2 considéré comme transitoire / non bloquant.

## Note incident Windows

L’incident Windows est noté comme isolé et non bloquant pour SKYFORGE à ce stade.

Éléments observés :

- Kernel-Power 41 ;
- BugCheck `0x00000050 PAGE_FAULT_IN_NONPAGED_AREA` ;
- dump : `C:\WINDOWS\Minidump\061726-8609-01.dmp` ;
- WinDbg :
  - `PROCESS_NAME: SkyrimSE.exe` ;
  - `IMAGE_NAME: ntkrnlmp.exe` ;
  - `FAILURE_BUCKET_ID: AV_nt!MiSystemFault` ;
  - pile incluant `Ntfs!NtfsCommonDirectoryControl`.

Interprétation actuelle :

- pas de preuve de malware ;
- pas de preuve de mod Skyrim fautif ;
- pas de preuve que MO2 / SKYFORGE soit directement responsable ;
- hypothèse actuelle : incident système ponctuel / mémoire noyau / NTFS / service bas niveau ;
- MSI Center à surveiller si récidive.

## Test final étape 420

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Aucun reboot reproduit
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 420 validée.

---

# Étape 421 — Archery Locational Damage

## Objectif

Ajouter un petit module combat / archerie issu de Nolvus Awakening.

## Mod installé

- `Archery Locational Damage`

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/63863

## Choix FOMOD

- Option : `Simple`

## Rôle SKYFORGE

Ajoute une logique de dégâts localisés pour l’archerie avec une configuration prudente.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 421 validée.

---

# Étape 422 — Bow Charge Plus

## Objectif

Ajouter un module léger d’archerie issu de Nolvus Awakening.

## Mod installé

- `Bow Charge Plus`

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/59124

## Installation

- Fichier principal uniquement.
- Patch complémentaire non installé pour l’instant.

## Rôle SKYFORGE

Ajoute une mécanique de tir chargé à l’arc, avec logique de stamina / charge.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 106

## Verdict

Étape 422 validée.

---

# Étape 423 — VioLens Killmove + Settings Loader

## Objectif

Ajouter un contrôle MCM des killmoves, issu de Nolvus Awakening, sans ajouter de gros overhaul combat.

## Mods installés

- `VioLens - A Killmove Mod SE`
- `VioLens - A Killmove Mod SE - Settings Loader`

## Sources

- VioLens : https://www.nexusmods.com/skyrimspecialedition/mods/668
- Settings Loader : https://www.nexusmods.com/skyrimspecialedition/mods/56674

## Choix FOMOD VioLens

- Plugin requis : `VioLens SE`
- Core Files : `Archive`
- Extras :
  - `Reaction` non installé
  - `Premade Profiles` non installé

## Rôle SKYFORGE

Ajoute un MCM pour contrôler les killmoves en mêlée, à distance et en furtivité.

Le Settings Loader ajoute la prise en charge MCM Helper pour sauvegarde / chargement automatique des réglages.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 107

## Impact compteur

- Avant étape : 106
- Après étape : 107
- Variation : +1

## Verdict

Étape 423 validée.

---

# Étape 424 — No BS AI Projectile Dodge

## Objectif

Ajouter un ajustement combat / projectiles issu de Nolvus Awakening.

## Mod installé

- `No BS AI Projectile Dodge`

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/1763

## Rôle SKYFORGE

Empêche les NPC d’esquiver artificiellement les flèches et projectiles magiques comme s’ils anticipaient automatiquement les tirs.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 108

## Impact compteur

- Avant étape : 107
- Après étape : 108
- Variation : +1

## Verdict

Étape 424 validée.

---

# Contraintes respectées sur les étapes 416 à 424

- LOOT non lancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Pandora non relancé.
- Mods `- FR` non activés.
- Aucun système adulte ajouté.
- Aucun retour à Nemesis.
- Aucun gros overhaul combat ajouté.
- `Precision - Creatures` reste différé.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 424 — No BS AI Projectile Dodge**.
- Séparateur actif : **10 - GAMEPLAY COMBAT MAGIC PERKS**.
- Compteur ESP + ESM non-light global : **108**.
- Overwrite : vide.
- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.
- Pandora : non relancé depuis l’étape 411.
