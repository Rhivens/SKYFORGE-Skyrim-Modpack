# Changelog / validation — partie 18

## Périmètre

Ce changelog couvre les étapes **531 à 553** du projet SKYFORGE.

## État final documenté

- **Dernière étape validée :** Étape 553 — Rainbows Remade + Shooting Stars SE
- **Blocs repris / enrichis :**
  - `11.1 - FOLLOWERS NPCS DIALOGUES`
  - `03 - UI HUD MENUS`
  - `04 - AUDIO MUSIC VOICES`
  - `06 - LANDSCAPE GRASS TREES WATER`
- **Décision différée importante :** bloc map / CoMAP / FWMF à regrouper plus tard
- **Compteur ESP + ESM non-light :** 128
- **Overwrite :** vide sur les tests documentés après corrections
- **Menu principal :** OK sur les tests documentés
- **Messages DLL :** aucun message bloquant signalé
- **Masters manquants :** aucun sur les tests validés
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé pendant cette série
- **Mods `- FR` :** non activés
- **Snapshot panneau gauche courant avant collage post-553 :** étape 530

---

## Résumé des étapes

### Étapes 531 à 533 — Dialogues NPC / bloc 11.1

- **Étape 531 :** installation de `Additional Dremora Faces - PATCHES A VOIR PLUS TARD` et `Dremora Lines Expansion`.
- **Étape 532 :** `Dynamic Dialogue Replacer - DDR` et `Skyrim Autocorrect - Dialogue Grammar Fixes` différés pour cohérence avec la stratégie de traduction FR manuelle.
- **Étape 533 :** installation de `More to Say - FOMOD A REVOIR PLUS TARD`.

### Étapes 534, 543, 549, 550 et 552 — Audio / voices / ambiances

- **Étape 534 :** installation de `NPC Dialogue Audio Enhancer`.
- **Étape 543 :** installation de `Meridia Revoiced SE` et `The Black Door Revoiced`.
- **Étape 549 :** installation de `Whispering Tomes of Apocrypha - FOMOD A REVOIR PLUS TARD`.
- **Étape 550 :** installation de `MEMOSPORE - UI Sound Effects - FOMOD A REVOIR PLUS TARD`.
- **Étape 552 :** installation de `Whales Off The Coast - FOMOD A REVOIR PLUS TARD` et `Murmurs and Mead - FOMOD A REVOIR PLUS TARD`.

### Étapes 535 à 548 — UI / HUD / menus

- **Étape 535 :** installation de `Subtitles`.
- **Étape 536 :** installation de `Hotkey Reminder`.
- **Étape 537 :** installation de `Load Screen Shading Fix` et `Menu Zoom`.
- **Étape 538 :** installation de `Notification Log SSE NG` et `Yes Im Sure NG`.
- **Étape 539 :** annulée / doublon — `Use or Take SKSE` et `Read Or Take SKSE` déjà installés.
- **Étape 540 :** annulée / doublon — `Essential Favorites` et `Favorite Misc Items` déjà installés.
- **Étape 541 :** installation de `Too many notifications`.
- **Étape 542 :** installation de `Photo Mode`, `Skyrim Character Sheet` et `Name Those Ash Piles`.
- **Étape 542 correction :** création du mod de sortie `SKYFORGE - Photo Mode Output` pour vider l'Overwrite.
- **Étape 544 :** installation de `iWant Widgets`, `iWant Widgets NG` et `iWant Status Bars`.
- **Étape 545 :** installation de `Detection Meter` et `Casting Bar`; `Contextual Crosshair` différé.
- **Étape 546 :** installation du pack d'icônes I4 / SkyUI :
  - `The Handy Icon Collection Collective`
  - `B.O.O.B.I.E.S (aka Immersive Icons) - FOMOD A REVOIR PLUS TARD`
  - `Aura's Scrumptious Supplement - A.S.S. for B.O.O.B.I.E.S`
  - `Phenomenally Enriched and Nuanced Ingredients for SkyUI - P.E.N.I.S. for B.O.O.B.I.E.S`
- **Étape 546 correction :** installation du complément `Inventory Interface Information Injector for Skyrim 1.5`.
- **Étape 547 :** installation des icônes I4 pour standing stones, diseases, racial abilities et shouts.
- **Étape 548 :** installation de `TrueHUD Curated Bosses` et `Show Mount Carry Weight`; `Casting Bar HUD Variance` différé.

### Étape 551 — Décision différée map

- `CoMAP`, `CoMAP 4 for Skyrim 1.5`, `Flat World Map Framework` et `Skyrim Paper Map by Caro Tuts for FWMF` sont à regrouper plus tard dans un bloc map dédié.
- Rappel : les plugins FWMF / paper map devront rester très bas dans le load order panneau droit pour éviter le risque de map violette.

### Étape 553 — Ciel / météo / effets atmosphériques

- Installation de `Rainbows Remade`, son hotfix, son patch sans notification d'initialisation, et `Shooting Stars SE`.

---

## Notes de validation

- Aucune génération LOOT / DynDOLOD / BodySlide / Pandora pendant cette série.
- Les marqueurs `FOMOD A REVOIR PLUS TARD` et `PATCHES A VOIR PLUS TARD` restent volontaires.
- Le snapshot post-553 doit être créé avec placeholder puis rempli manuellement par Fabien selon la procédure SKYFORGE.
