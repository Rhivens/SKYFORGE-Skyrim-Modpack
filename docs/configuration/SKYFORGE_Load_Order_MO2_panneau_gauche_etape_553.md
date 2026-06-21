# SKYFORGE — Load Order MO2 panneau gauche — Étape 553

Snapshot du panneau gauche MO2 après validation de l’étape 553.

Ce fichier deviendra la référence de contrôle du panneau gauche MO2 une fois que le texte brut complet du load order aura été collé manuellement dans le bloc prévu à cet effet.

## Règles de lecture

- Ce fichier remplacera le snapshot étape 530 comme référence courante anti-doublon après collage manuel du brut MO2 complet et vérification.
- Le snapshot étape 530 deviendra alors un jalon historique post-530.
- Les mods se terminant par `- FR` sont présents mais décochés, sauf indication contraire.
- Les séparateurs vides sont normaux : ils préparent les futurs blocs SKYFORGE.
- Les suffixes de suivi temporaires (`FOMOD A REVOIR`, `PATCHES A VOIR`, `A REINSTALLER`, `DECOCHE`, `RESERVE`, etc.) sont des marqueurs de suivi et ne signifient pas forcément que le mod est invalide.
- Ce snapshot concerne le panneau gauche MO2, pas le compteur ESP/ESM non-light du panneau droit.

## État associé

- Dernière étape validée : 553
- Prochaine étape attendue : 554
- Blocs enrichis depuis le snapshot 530 :
  - `[11.1 - FOLLOWERS NPCS DIALOGUES]`
  - `[03 - UI HUD MENUS]`
  - `[04 - AUDIO MUSIC VOICES]`
  - `[06 - LANDSCAPE GRASS TREES WATER]`
- Compteur ESP + ESM non-light : 128
- Overwrite : vide sur les tests documentés après corrections
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- BodySlide Output : non généré
- Pandora : généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 531 à 553

## Changements principaux depuis le snapshot étape 530

### Bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]`

Ajouts / décisions principales :

- Additional Dremora Faces - PATCHES A VOIR PLUS TARD
- Dremora Lines Expansion
- Dynamic Dialogue Replacer - DDR : différé
- Skyrim Autocorrect - Dialogue Grammar Fixes : différé
- More to Say - FOMOD A REVOIR PLUS TARD

### Bloc `[03 - UI HUD MENUS]`

Ajouts / décisions principales :

- Subtitles
- Hotkey Reminder
- Load Screen Shading Fix
- Menu Zoom
- Notification Log SSE NG
- Yes Im Sure NG
- Too many notifications
- Photo Mode
- Skyrim Character Sheet
- Name Those Ash Piles
- SKYFORGE - Photo Mode Output
- iWant Widgets
- iWant Widgets NG
- iWant Status Bars
- Detection Meter
- Casting Bar
- The Handy Icon Collection Collective
- B.O.O.B.I.E.S (aka Immersive Icons) - FOMOD A REVOIR PLUS TARD
- Aura's Scrumptious Supplement - A.S.S. for B.O.O.B.I.E.S
- Phenomenally Enriched and Nuanced Ingredients for SkyUI - P.E.N.I.S. for B.O.O.B.I.E.S
- Inventory Interface Information Injector for Skyrim 1.5
- Standing Stones - I4 icon
- Diseases - I4 icon
- Racial Abilities - I4 icons - FOMOD A REVOIR PLUS TARD
- I4 Shout Icons Overhaul - FOMOD A REVOIR PLUS TARD
- TrueHUD Curated Bosses
- Show Mount Carry Weight

### Bloc `[04 - AUDIO MUSIC VOICES]`

Ajouts principaux :

- NPC Dialogue Audio Enhancer
- Meridia Revoiced SE
- The Black Door Revoiced
- Whispering Tomes of Apocrypha - FOMOD A REVOIR PLUS TARD
- MEMOSPORE - UI Sound Effects - FOMOD A REVOIR PLUS TARD
- Whales Off The Coast - FOMOD A REVOIR PLUS TARD
- Murmurs and Mead - FOMOD A REVOIR PLUS TARD

### Bloc map différé

- CoMAP / CoMAP 4 pour Skyrim 1.5 différés.
- Flat World Map Framework et Skyrim Paper Map par Caro Tuts pour FWMF seront regroupés plus tard dans un bloc map dédié.
- Rappel : les plugins FWMF / paper map devront rester très bas dans le load order panneau droit.

### Bloc `[06 - LANDSCAPE GRASS TREES WATER]`

Ajouts principaux :

- Rainbows Remade
- Rainbows Remade - Hotfix Patch
- Rainbows Remade - No Initialization Notification Patch
- Shooting Stars SE

## Snapshot complet du panneau gauche MO2

```txt
COPIER LE TEXTE BRUT DU LOAD ORDER MO2 ICI
```

---

## Notes post-snapshot

- Snapshot créé avec emplacement manuel réservé pour éviter les blocages du connecteur GitHub.
- Après collage manuel du brut MO2 complet, ce fichier devra être vérifié puis déclaré comme nouvelle référence courante dans `docs/procedure/00_resume_etat_actuel.md`.
- Le README devra être ajusté manuellement si le connecteur GitHub continue de bloquer sa mise à jour automatique.
