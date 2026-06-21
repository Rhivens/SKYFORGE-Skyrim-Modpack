# Module 03 — UI, HUD & menus — partie 1

Ce fichier regroupe les ajouts UI / HUD / menus documentés après le snapshot étape 530.

Périmètre : étapes **535 à 548**, hors étapes audio classées dans le module 04 et hors décision map différée.

État de référence :
- série post-530 ;
- compteur ESP + ESM non-light maintenu à 128 sur les validations indiquées ;
- aucun lancement de LOOT, DynDOLOD, BodySlide ou Pandora.

---

## Étape 535 — Subtitles

### Objectif
Améliorer l’affichage des sous-titres pour les dialogues multiples, sans ajouter de lignes, sans correction automatique anglophone et sans impact sur les traductions FR personnelles.

### Référence
- Source principale : Nefaram
- Type : UI / dialogues / sous-titres
- Étape précédente validée : 534
- Snapshot MO2 de référence : étape 530 + ajouts étapes 531, 533 et 534
- Étape 532 : différée

### Mod installé
- Subtitles

### Lien
- Subtitles : https://www.nexusmods.com/skyrimspecialedition/mods/113214

### Placement MO2 réel
Bloc utilisé : `[03 - UI HUD MENUS]`.

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 536 — Hotkey Reminder

### Objectif
Ajouter un mémo intégré des raccourcis clavier / manette afin de faciliter le suivi des nombreux systèmes UI, MCM, hotkeys et toggles du profil SKYFORGE.

### Référence
- Source principale : Nefaram
- Type : UI / MCM / hotkeys

### Mod installé
- Hotkey Reminder

### Lien
- Hotkey Reminder : https://www.nexusmods.com/skyrimspecialedition/mods/115853

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 537 — Load Screen Shading Fix + Menu Zoom

### Objectif
Ajouter deux petits conforts UI : correction visuelle des écrans de chargement et zoom / inspection dans certains menus.

### Référence
- Source principale : Nefaram
- Type : UI / menus / loading screens

### Mods installés
- Load Screen Shading Fix
- Menu Zoom

### Liens
- Load Screen Shading Fix : https://www.nexusmods.com/skyrimspecialedition/mods/98647
- Menu Zoom : https://www.nexusmods.com/skyrimspecialedition/mods/117402

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 538 — Notification Log SSE NG + Yes Im Sure NG

### Objectif
Ajouter deux petits conforts UI : historique des notifications affichées et suppression de certaines confirmations répétitives dans les menus.

### Référence
- Source principale : Nefaram
- Type : UI / menus / notifications

### Mods installés
- Notification Log SSE NG
- Yes Im Sure NG

### Liens
- Notification Log SSE NG : https://www.nexusmods.com/skyrimspecialedition/mods/76947
- Yes Im Sure NG : https://www.nexusmods.com/skyrimspecialedition/mods/76892

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 539 — ANNULÉE / DOUBLON

### Décision
Étape annulée : les deux mods proposés sont déjà installés dans SKYFORGE.

### Mods concernés
- Use or Take SKSE
- Read Or Take SKSE

### Conséquence
Aucune installation. Compteur ESP + ESM non-light inchangé : 128. Overwrite : vide.

### Note
Ne pas reproposer `Use or Take SKSE` ni `Read Or Take SKSE` sauf demande explicite d’audit, de réinstallation ou de configuration INI.

---

## Étape 540 — ANNULÉE / DOUBLON

### Décision
Étape annulée : les deux mods proposés sont déjà installés dans SKYFORGE.

### Mods concernés
- Essential Favorites
- Favorite Misc Items

### Emplacement constaté
Bloc MO2 : `[03 - UI HUD MENUS]`.

### Conséquence
Aucune installation. Compteur ESP + ESM non-light inchangé : 128. Overwrite : vide.

---

## Étape 541 — Too many notifications

### Objectif
Ajouter un confort UI léger pour éviter l’accumulation excessive des notifications à l’écran.

### Référence
- Source principale : Nefaram
- Type : UI / notifications

### Mod installé
- Too many notifications

### Lien
- Too many notifications : https://www.nexusmods.com/skyrimspecialedition/mods/69924

### Doublon constaté
`Disable Numpad` était déjà installé dans SKYFORGE.

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 542 — Photo Mode + Skyrim Character Sheet + Name Those Ash Piles

### Objectif
Ajouter trois conforts UI / immersion légers : mode photo intégré, fiche de personnage consultable et identification des tas de cendres.

### Référence
- Source principale : Nefaram
- Type : UI / menus / immersion légère
- Snapshot opérationnel de référence : load order collé post-541
- Compteur ESP + ESM non-light avant étape : 128

### Mods installés
- Photo Mode
- Skyrim Character Sheet
- Name Those Ash Piles

### Liens
- Photo Mode : https://www.nexusmods.com/skyrimspecialedition/mods/91701
- Skyrim Character Sheet : https://www.nexusmods.com/skyrimspecialedition/mods/56069
- Name Those Ash Piles : https://www.nexusmods.com/skyrimspecialedition/mods/24701

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 542 — Correction Overwrite Photo Mode

### Constat
Après l’installation et le test de l’étape 542, l’Overwrite contenait un dossier généré par `Photo Mode` :

```txt
textures/photomode/screenshots/paintings/
```

### Décision
Création d’un mod de sortie dédié :

```txt
[18 - TOOLS OUTPUTS]
SKYFORGE - Photo Mode Output
```

### Résultat
Overwrite vidé après déplacement du dossier généré.

---

## Étape 544 — iWant Widgets + iWant Widgets NG + iWant Status Bars

### Objectif
Installer la base `iWant` utilisée par plusieurs widgets / status bars UI, utile pour les futurs systèmes d’interface, de statut et de gameplay.

### Référence
- Source principale : Nefaram
- Type : UI / widgets / status bars

### Mods installés
- iWant Widgets
- iWant Widgets NG
- iWant Status Bars

### Liens
- iWant Widgets : https://www.nexusmods.com/skyrimspecialedition/mods/36457
- iWant Widgets NG : https://www.nexusmods.com/skyrimspecialedition/mods/96410
- iWant Status Bars : https://www.nexusmods.com/skyrimspecialedition/mods/36460

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 545 — Detection Meter + Casting Bar

### Objectif
Ajouter deux éléments HUD utiles en jeu : indicateur de détection pendant la furtivité et barre d’incantation pour les sorts / cris / actions compatibles.

### Référence
- Source principale : Nolvus Awakening
- Source secondaire : Nefaram pour la logique UI / HUD
- Type : UI / HUD / furtivité / magie

### Mods installés
- Detection Meter
- Casting Bar

### Liens
- Detection Meter : https://www.nexusmods.com/skyrimspecialedition/mods/63057
- Casting Bar : https://www.nexusmods.com/skyrimspecialedition/mods/80455

### Mod différé
- Contextual Crosshair

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 546 — The Handy Icon Collection Collective + B.O.O.B.I.E.S + A.S.S. + P.E.N.I.S.

### Objectif
Améliorer les icônes et catégories SkyUI / I4 pour objets, artefacts, nourriture / potions et ingrédients, sans impact BodySlide, Pandora, SexLab ou gameplay.

### Référence
- Source principale : Nolvus Awakening
- Source secondaire : Nefaram
- Type : UI / SkyUI / I4 / icônes

### Mods installés
- The Handy Icon Collection Collective
- B.O.O.B.I.E.S (aka Immersive Icons) - FOMOD A REVOIR PLUS TARD
- Aura's Scrumptious Supplement - A.S.S. for B.O.O.B.I.E.S
- Phenomenally Enriched and Nuanced Ingredients for SkyUI - P.E.N.I.S. for B.O.O.B.I.E.S

### Liens
- The Handy Icon Collection Collective : https://www.nexusmods.com/skyrimspecialedition/mods/90508
- B.O.O.B.I.E.S (aka Immersive Icons) : https://www.nexusmods.com/skyrimspecialedition/mods/89241
- A.S.S. for B.O.O.B.I.E.S : https://www.nexusmods.com/skyrimspecialedition/mods/89823
- P.E.N.I.S. for B.O.O.B.I.E.S : https://www.nexusmods.com/skyrimspecialedition/mods/90526

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 546 — Correction Inventory Interface Information Injector 1.5.97

### Constat
Après l’installation du pack icônes I4 / B.O.O.B.I.E.S, un doute de compatibilité a été relevé concernant `Inventory Interface Information Injector`.

### Problème identifié
Le profil SKYFORGE utilise Skyrim SE 1.5.97. `Inventory Interface Information Injector` nécessite un complément / backport spécifique pour Skyrim 1.5.97.

### Décision
Installation du complément :

```txt
Inventory Interface Information Injector for Skyrim 1.5
```

### Résultat
Correction validée. Aucun changement de compteur non-light signalé.

---

## Étape 547 — Standing Stones I4 + Diseases I4 + Racial Abilities I4 + I4 Shout Icons Overhaul

### Objectif
Compléter la base I4 / B.O.O.B.I.E.S avec des icônes d’effets vanilla utiles : pierres gardiennes, maladies, capacités raciales et cris.

### Référence
- Source principale : Nefaram / Nolvus Awakening pour la logique UI / I4
- Type : UI / SkyUI / I4 / icônes d’effets

### Mods installés
- Standing Stones - I4 icon
- Diseases - I4 icon
- Racial Abilities - I4 icons - FOMOD A REVOIR PLUS TARD
- I4 Shout Icons Overhaul - FOMOD A REVOIR PLUS TARD

### Liens
- Standing Stones - I4 icon : https://www.nexusmods.com/skyrimspecialedition/mods/92780
- Diseases - I4 icon : https://www.nexusmods.com/skyrimspecialedition/mods/94076
- Racial Abilities - I4 icons : https://www.nexusmods.com/skyrimspecialedition/mods/94161
- I4 Shout Icons Overhaul : https://www.nexusmods.com/skyrimspecialedition/mods/111957

### Validation
Étape validée. Compteur non-light inchangé : 128.

---

## Étape 548 — TrueHUD Curated Bosses + Show Mount Carry Weight

### Objectif
Ajouter deux conforts légers : affiner l’affichage des boss bars TrueHUD et afficher le poids transporté par les montures.

### Référence
- Source principale : Nefaram
- Type : UI / HUD / confort montures

### Mods installés
- TrueHUD Curated Bosses
- Show Mount Carry Weight

### Liens
- TrueHUD Curated Bosses : https://www.nexusmods.com/skyrimspecialedition/mods/53406
- Show Mount Carry Weight : https://www.nexusmods.com/skyrimspecialedition/mods/101704

### Mod différé
- Casting Bar HUD Variance

### Validation
Étape validée. Compteur non-light inchangé : 128.
