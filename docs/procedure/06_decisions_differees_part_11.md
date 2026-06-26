# SKYFORGE — Décisions différées et points à revoir — partie 11

Période couverte : étapes **656 à 685**.

Ce fichier recense les décisions différées apparues pendant les validations provisoires des blocs 08, 09, 10, 11, 12 et l’installation du noyau SexLab Core 13-A.

---

## Bloc 08 — Characters / Hair / Body / Skins / BodySlide

### Core characters / hair / eyes / overlays

À conserver / reprendre plus tard :

- `RS Children Overhaul - CHOIX NOLVUS - A REINSTALL PLUS TARD`.
- `The Eyes of Beauty - Vampire Eyes SE - PATCHES A VOIR PLUS TARD`.
- `Community Overlays 2` = choix provisoire CBBE + male, à revoir si body final change.
- SkFO et Female Makeup Suite installés plus tôt que prévu, à revoir au bloc skins.
- Traductions `- FR` en attente, pas une erreur.

### Body / skins / BodySlide

À ne pas faire maintenant :

- Ne pas réinstaller CBBE.
- Ne pas réinstaller 3BA.
- Ne pas générer BodySlide.
- Ne pas modifier The New Gentleman.
- Ne pas isoler PB’s Silky Skin maintenant.
- Ne pas toucher aux options SOS collisions maintenant.
- Ne pas lancer Pandora.

Dettes conservées :

- Reprendre CBBE + RaceMenu morphs avec 3BA / OBody / BodySlide.
- Réinstaller / vérifier 3BA plus tard avec options SOS collisions.
- Reprendre The New Gentleman patches.
- Isoler PB’s Silky Skin à terme si skin joueur uniquement retenu.
- Générer BodySlide Output seulement quand le bloc Body / outfits sera stabilisé.
- Garder compatibilité future SexLab / Devious / NSFW.

---

## Bloc 09 — Animations / Skeleton / Physics

### Physics / skeleton

- Revoir le FOMOD XPMSSE plus tard.
- Vérifier que la limite FPS Skyrim correspond bien à la config `CBPC - Generated Config - 120 FPS`.
- Reprendre physics / collisions au moment du vrai bloc Body + outfits + SexLab.
- Refaire BodySlide seulement quand les bodies et outfits seront stabilisés.

### OAR / Pandora

- Ne pas relancer Pandora sans ajout / retrait / modification réel de mods d’animations ou comportements.
- Revoir `Paired Animation Improvements - Patch` plus tard.
- Garder `SKYFORGE - Pandora Output` comme référence actuelle.
- Surveiller Overwrite si Pandora est relancé plus tard.

### Movement / combat animation base

- `TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD`.
- Vérifier plus tard compatibilité Precision / TK Dodge / animations combat.
- Tester esquive + hit detection en jeu quand le bloc combat sera stabilisé.

---

## Bloc 10 — Gameplay / Combat / Races

### Combat core

À tester plus tard :

- stamina / block ;
- esquive TK Dodge ;
- hit detection Precision ;
- killmoves VioLens ;
- comportement des archers ;
- couverture NPCs.

À ne pas faire maintenant :

- Ne pas ajouter Valravn / Valvalis / Sekiro Combat.
- Ne pas mélanger d’autres overhauls combat majeurs.
- Ne pas modifier les MCM.

### Followers / utility gameplay

- Revoir le FOMOD NFF plus tard.
- Reprendre les réglages MCM NFF / Simple Offence Suppression après stabilisation followers.
- Vérifier plus tard interactions avec les followers custom du bloc 11.
- Surveiller compatibilité NFF avec Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore et Serana Dialogue Add-On.

### Horses / bounty / misc gameplay

- Tester plus tard SkyParkour en vraie cellule extérieure.
- Vérifier Take a Peek avec la furtivité / caméra.
- Vérifier Headhunter avec les quêtes de primes.
- Vérifier Simplest Horses avant ajout éventuel de mods chevaux plus lourds.
- Vérifier Skyrim’s Got Talent avec audio / bards / dialogues si conflit.

### Races / werebeasts / vampires

- Vérifier plus tard la cohérence Sacrosanct avec la future pile SexLab / vampire / NPC.
- Vérifier Manbeast quand les animations créatures / werewolf seront traitées.
- Vérifier les descriptions RaceMenu d’Aetherius.
- Vérifier Mundus avec les futurs mods perks / magie.
- Ne pas ajouter Growl en parallèle de Manbeast.
- Ne pas ajouter Better Vampires en parallèle de Sacrosanct.

---

## Bloc 11 — Dialogues / Followers

### Dialogues / NPC reactions

FOMOD / choix à revoir :

- `Robber's Gorge Fixes - FOMOD À REVOIR PLUS TARD`.
- `Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD`.
- `More Dialogue Options - FOMOD À REVOIR PLUS TARD`.
- `Cutting Room Floor - FOMOD À REVOIR PLUS TARD`.
- `AI Overhaul SSE - FOMOD À REVOIR PLUS TARD`.
- `More to Say - FOMOD A REVOIR PLUS TARD`.

Compatibilités à vérifier :

- RDO / CRF / AI Overhaul / GDO ensemble.
- Dialogues avec followers custom et FDE.

### Follower Dialogue Expansion / followers custom

FOMOD / patches à reprendre plus tard :

- Remiel.
- Gore.
- Serana Dialogue Add-On / Patch Hub.
- Thogra patches.
- Xelzaz Wyrmstooth.
- Xelzaz Sirenroot.
- SDA patches.
- Gore patches.

Compatibilités à vérifier :

- NFF avec followers custom.
- RDO / FDE / AI Overhaul.
- Banters followers.
- Quêtes concernées.

---

## Bloc 12 — Survival / Immersion / Roleplay

- `Skyrim Unbound Reborn - ALTERNATE START - A REINSTALLER PLUS TARD`.
- Ne pas installer SunHelm / Campfire / besoins / froid / camping maintenant.
- Décider plus tard la philosophie survival : léger, complet ou simple compatibilité future.

---

## Bloc 13 — SexLab Core Adult Frameworks

### SexLab Core 13-A installé / actif

- SexLab Framework SE v1.63.
- SexLab Animation Loader 1.6.
- ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023.
- SLSF Reloaded 3.4.1.

### Dettes post-installation

- Animations SLAL non chargées.
- Génération animations non faite.
- MCM SexLab / SLSF non configurés.
- BodySlide Output non généré.
- Devious / defeat / prostitution / slavery non installés.
- Pandora/FNIS non lancé.

### SLO Aroused NG différé

- SLO Aroused NG 3.1.7 contient une DLL : `SKSE/Plugins/SexlabArousedNG.dll`.
- Plugins observés : `SexLabAroused.esm`, `OSLAroused.esp`, `OAroused.esp`.
- Différé tant que la compatibilité Skyrim SE 1.5.97 / SKSE 2.0.20 / SexLab 1.63 n’est pas confirmée.

### Devious / defeat / slavery / prostitution

À ne pas installer maintenant dans le pack 13-A :

- Devious Devices.
- Devious Devices NG.
- Creature Framework.
- More Nasty Critters.
- SLATE.
- SLAnimStageLabels.
- Simple Slavery.
- BakaFactory / Billyy / Leito / Anub / autres gros packs SLAL.
- Defeat / slavery / prostitution.

---

## Rappels méthode

- Ne pas lancer LOOT.
- Ne pas lancer DynDOLOD / LOD.
- Ne pas générer BodySlide.
- Ne pas relancer Pandora sans changement réel d’animations / comportements.
- Ne pas lancer FNIS.
- Les mods `- FR` restent volontairement en attente selon la méthode SKYFORGE.
- Les réglages MCM sont reportés à la phase finale ou à un bloc dédié.

---

## Surveillance compteur ESP + ESM non-light

- `< 160` non-light : zone confortable.
- `160–190` : vigilance normale.
- `190–220` : vigilance renforcée.
- `220–235` : audit obligatoire avant gros ajout.
- `235+` : mode survie ; ESLification, suppressions ou merges propres à envisager.

État post-685 : **141 non-light**, donc zone confortable.
