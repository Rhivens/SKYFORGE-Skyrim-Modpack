# Changelog / validation — partie 15

## Périmètre

Ce changelog couvre les étapes **451 à 480** du projet SKYFORGE.

## État final documenté

- **Dernière étape validée :** Étape 480 — SPID NPC Trap Safety / audit doublon NPC AI Process Position Fix
- **Compteur ESP + ESM non-light :** 119
- **Overwrite :** vide
- **Menu principal :** OK sur les tests documentés
- **Messages DLL :** aucun message bloquant signalé
- **Masters manquants :** aucun après corrections documentées
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé pendant cette série
- **Mods `- FR` :** non activés
- **Dernier snapshot panneau gauche courant :** étape 450, en attente d'un nouveau snapshot post-480 si Fabien fournit le panneau gauche complet

---

## Étapes 451 à 458 — Bloc 10.1 Races, werebeasts & vampires

### Étape 451

Ouverture prudente du bloc `[10.1 - RACES WEREBEASTS VAMPIRES]` sans installation immédiate.

Décision : différer les overhauls vampires, werebeasts, vampire lord, werebear et créatures tant qu'un audit dédié n'est pas effectué.

Compteur : 110.

### Étape 452

Installation de `Aetherius - A Race Overhaul` version 2.14.1.

Choix FOMOD minimal :

- Aetherius installé ;
- Racial Starting Spells non installé ;
- Lower Starting Skills non installé ;
- NPC Spell Absorption non installé.

Compteur : 110.

### Étape 453

Installation de `Aetherius - Race Menu Racial Passive Descriptions`, complément léger pour afficher les passifs raciaux dans RaceMenu.

Compteur : 110.

### Étape 454

Installation de `Mundus - A Standing Stone Overhaul` avec patch USSEP.

Décision : Mundus devient l'overhaul actuel des Pierres Gardiennes. Freyr est exclu pour éviter le doublon de système.

Compteur : 110.

### Étape 455

Installation de `Manbeast - A Werewolf Overhaul`.

Décision : Manbeast devient l'overhaul werewolf retenu. Growl est exclu pour éviter un doublon de système.

Compteur : 110.

### Étape 456

Installation du sous-bloc vampire :

- `Sacrosanct - Vampires of Skyrim`
- `Cover Your Head - Sacrosanct`

Décision : Sacrosanct est conservé comme base vampire validée. Scion, Sacrilege, Better Vampires et Vampire Lords Can Fly restent exclus / différés.

Compteur : 111.

### Étape 457

Installation de `Sun Affects NPC Vampires`, option **NPC + PJ**.

Décision : conforme à la règle vampire SKYFORGE, car le mod bénéficie aux NPC vampires.

Compteur : 111.

### Étape 458

Clôture provisoire du bloc `[10.1 - RACES WEREBEASTS VAMPIRES]`.

Bloc 10.1 validé avec :

- Aetherius - A Race Overhaul
- Aetherius - Race Menu Racial Passive Descriptions
- Mundus - A Standing Stone Overhaul
- Manbeast - A Werewolf Overhaul
- Sacrosanct - Vampires of Skyrim
- Cover Your Head - Sacrosanct
- Sun Affects NPC Vampires

`Vampire Lines Expansion` est différé vers `[11.1 - FOLLOWERS NPCS DIALOGUES]`.

Compteur : 111.

---

## Étapes 459 à 480 — Bloc 11.1 Followers, NPCs & dialogues

### Étape 459

Ouverture du bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` avec un pack Lines Expansion :

- Bandit Lines Expansion
- Civil War Lines Expansion
- Forsworn and Thalmor Lines Expansion
- Vampire Lines Expansion

Options sensibles différées : Werebeasts Dont Talk, Dark Elf Voices For Bandits, Orc Addon.

Compteur : 111.

### Étape 460

Installation de `Brawl Lines Expansion and Fixes`.

`Dremora Lines Expansion` différé pour audit séparé.

Compteur : 111.

### Étape 461

Installation du pack NPCs React aux actes magiques :

- NPCs React To Necromancy (And More)
- NPCs React To Invisibility
- Bow of Shadows (CC) - Invisibility Patch
- NPCs React To Frenzy

Compteur : 111.

### Étape 462

Installation de `Carriages and Stables Dialogue Bundle`.

Patch CFTO différé jusqu'à installation réelle de CFTO.

Compteur : 111.

### Étape 463

Installation d'un pack de petits conforts dialogue NPC :

- Show NPC Disposition Relationship Rank
- Dialogue Window Auto Close Exit Begone
- Scared of Shootings - NPCs react to aiming bows

Compteur : 111.

### Étape 464

Installation du pack Dialogue Expansion lieux / caravanes :

- Dialogue Expansion - Windhelm
- Dialogue Expansion - Shor's Stone
- Dialogue Expansion - Khajiit Caravans

`Immersive Dialogue Expansion - Stormcloaks` et `Immersive Dialogue Expansion - Whiterun` différés.

Compteur : 111.

### Étape 465

Annulation propre de `Immersive Dialogue Expansion - Whiterun`.

Raison : mod caché sur Nexus, signalé comme obsolète.

`Follower Dialogue Expansion - Olfina Gray-Mane` noté comme candidat futur, mais non installé automatiquement.

Compteur : 111.

### Étape 466

Installation de trois micro-fixes roleplay :

- Neutral Whiterun Guards
- Truly Neutral Prisoners
- More Sensible Quartermasters, version complète

Compteur : 111.

### Étape 467

Installation de `Robber's Gorge Fixes`, choix FOMOD `None`.

`Longer Jailtime` non installé / différé.

Compteur : 111.

### Étape 468

Installation de `Guard Dialogue Overhaul SE` version ESP et de `Guard Dialogue Overhaul MCM`.

Choix MCM : `ESP GDO` + `Only the MCM`.

Compteur : 111.

### Étape 469

Installation de `GuardsTalk`.

Compteur : 112.

### Étape 470

Installation de `More Dialogue Options - FOMOD À REVOIR PLUS TARD`.

Patches installés :

- Guard Dialogue Overhaul - ESP version
- Riverwood Trader Is A Mess

Compteur : 112.

### Étape 471

Installation de `Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD`.

Patch installé : Skyrim Unbound Reborn.

Compteur : 112.

### Étape 472

Installation de `Relationship Dialogue Overhaul - RDO SE`.

Patches RDO optionnels différés à cette étape.

Compteur : 113.

### Étape 473

Installation de `Cutting Room Floor - FOMOD À REVOIR PLUS TARD` pour résoudre le master manquant du patch RDO CRF / USSEP.

Activation de `RDO - CRF + USSEP Patch.esp`.

Compteur : 116.

### Étape 474

Audit / stabilisation RDO Update and MCM.

Décision : conserver la route stable actuelle :

```txt
Relationship Dialogue Overhaul - RDO SE
Cutting Room Floor
RDO - CRF + USSEP Patch
```

Compteur : 116.

### Étape 475

Test puis différé de `AI Overhaul - Relationship Dialogue Overhaul Patch` à cause du master manquant `AI Overhaul.esp`.

Patch décoché.

Compteur : 116.

### Étape 476

Installation de `AI Overhaul SSE - FOMOD À REVOIR PLUS TARD`, version 1.9.5.

Choix FOMOD : Main File 1.9.5 + AIO Fishing ; AIO Scripted Beta exclu.

Réactivation de `AI Overhaul - Relationship Dialogue Overhaul Patch`.

Compteur : 117.

### Étape 477

Installation de `AI Overhaul - Cutting Room Floor Patch`.

Compteur : 117.

### Étape 478

Installation de `Run For Your Lives`.

Compteur : 118.

### Étape 479

Installation de `Realistic Conversations`.

Compteur : 119.

### Étape 480

Audit doublon : `NPC AI Process Position Fix - NG` déjà présent dans `[02 - BUG FIXES & ENGINE PATCHES]`, donc non réinstallé.

Installation de `SPID NPC Trap Safety`.

Compteur : 119.

---

## Décisions et différés importants

- `Growl` exclu car Manbeast est retenu.
- `Freyr` exclu car Mundus est retenu.
- `Mannaz` exclu car Aetherius est retenu.
- `Scion`, `Sacrilege`, `Better Vampires`, `Vampire Lords Can Fly` et addons feeding orientés joueur restent exclus / différés.
- `Vampire Lines Expansion` est traité comme mod de dialogue NPC, pas comme mod gameplay vampire.
- `Dremora Lines Expansion` différé pour audit séparé.
- Patch CFTO du bundle cochers / écuries différé jusqu'à installation de CFTO.
- `Immersive Dialogue Expansion - Whiterun` non installé, car obsolète / caché.
- `Longer Jailtime` non installé / différé.
- `Relationship Dialogue Overhaul - Update and MCM` différé.
- `AI Overhaul - RDO Updated Patch` non installé, car SKYFORGE n'utilise pas RDO Update and MCM.
- `NPC AI Process Position Fix - NG` déjà installé : ne pas réinstaller.

## Prochaine étape

Étape 481.

La reprise doit s'appuyer sur :

- `docs/procedure/00_resume_etat_actuel.md`
- `docs/procedure/99_changelog_validation_part_15.md`
- `docs/procedure/10_1_races_werebeasts_vampires.md`
- `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md`

Important : le snapshot panneau gauche courant reste celui de l'étape 450 tant qu'un nouveau load order complet post-480 n'est pas fourni.
