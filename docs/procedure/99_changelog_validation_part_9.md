# Changelog / validation — partie 9

## Périmètre

Cette partie couvre la progression SKYFORGE du module **08 - BODY RACE NPC APPEARANCE**, depuis la fin du sous-bloc overlays RaceMenu jusqu'au début du socle body / skins / physics.

Étapes concernées : **384 à 401**.

---

## État final validé

- **Dernière étape validée :** Étape 401 — Ajout CBPC pour 3BA
- **Module en cours :** 08 - BODY RACE NPC APPEARANCE
- **Sous-bloc en cours :** 08.3 - BODY / SKINS / BODYSLIDE
- **Bloc physique lié :** 09 - ANIMATIONS SKELETON PHYSICS ouvert ponctuellement pour FSMP / CBPC
- **SKSE / menu principal :** OK
- **Masters manquants :** aucun
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 102
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré

---

## Étapes validées

### Étape 384 — Pack overlays RaceMenu 1

Ajout du premier bloc d'overlays RaceMenu :

- Just Blood - Dirt and Blood Lite
- Lamenthia's Marks of Beauty 2k
- Community Overlays 1 main + bugfix + face overlays female / male
- Community Overlays 2 - CBBE and Male
- Skin Feature Overlays - 4K
- Female Makeup Suite - Face - 4K

Décision : Just Blood reste provisoire comme sang visuel léger ; Dirt & Blood complet et Bathing in Skyrim sont différés dans un futur sous-bloc hygiène / bain.

Validation : compteur non-light passé à **99**.

### Étape 385 — Pack overlays RaceMenu 2

Ajout du second bloc overlays / bodypaint :

- Community Overlays 3 - CBBE and Male
- Yyvengar Bodypaint - Female and Male CBBE
- Sakora's Make Over Kit - SKSE64

Correction Sakora : archive imbriquée corrigée via **Set as `<data>` directory** sur le dossier Data.

Validation : compteur non-light passé à **101**.

### Étape 386 — Tattoos utiles, sans tanlines ni pubes

Ajout :

- Lyru's Tattoo pack collection

Exclusions confirmées :

- Sunstarved - Tanlines
- Pubes Forever
- Tout mod dédié tanlines / pubic hair / pubes replacers

Différé : Lyru SlaveTats jusqu'au bloc SexLab / SlaveTats.

Validation : compteur non-light stable à **101**.

### Étape 387 — Clôture overlays NSFW inutiles

Aucune installation.

Décision : exclusion définitive des tanlines / pubic hair overlays / pubes replacers pour SKYFORGE.

### Étape 388 — Ouverture 08.3 BODY / SKINS / BODYSLIDE

Création du séparateur **08.3 BODY- SKINS- BODYSLIDE**.

Aucun BodySlide output généré.

### Étape 389 — CBBE

Installation :

- Caliente's Beautiful Bodies Enhancer CBBE - v2.0.3
- RoughSpun Tunic and Prisoner Bloody Fix

Choix importants : Curvy, Underwear None, Vanilla Outfits coché, Face Pack coché, pas de pubic hair, pas de RaceMenu morphs, pas de morph files Body / Outfits.

Validation : compteur non-light stable à **101**.

### Étape 390 — CBBE 3BA / 3BBB

Installation :

- CBBE 3BA (3BBB) v2.48

Choix importants : Pre-built Body mesh, CBPC Performance Balanced, SMP and CBPC Lite, No SOS, collisions adultes non ajoutées, RaceMenu CBBE 3BA Morph Sliders.

Validation : compteur non-light stable à **101**.

### Étape 391 — The New Gentleman

Installation :

- The New Gentleman v4.2.5

Choix FOMOD : Necessary Files + Main Mesh, HyliosFemaleMannequins décoché, Vigilant décoché.

Décision : TNG retenu en logique Nefaram, mais à surveiller pour éviter le problème de trou mesh sexe vu précédemment ailleurs.

Validation : compteur non-light passé à **102**.

### Étape 392 — TNG : Overwrite, DLL fix et exclusions adultes

Correction : fichier généré `SKSE/Plugins/TheNewGentleman5.ini` sorti de l'Overwrite vers le mod dédié :

- The New Gentleman - Generated INI

TNG dll fix Nefaram : différé, car DLL / PDB non identifiés à vérifier avant toute copie.

Exclusions confirmées :

- The New Gentlewoman
- SL Gender Bender for TNG
- Tout contenu Futanari / Female Schlong / Gender Bender

Validation : Overwrite vide, compteur non-light **102**.

### Étape 393 — Skin féminin PJ

Installation :

- PB's Silky Skin for CBBE

Décision : PB's Silky Skin est le choix pour le PJ féminin à terme. BNP n'est pas installé à cette étape pour le PJ.

Validation : compteur non-light stable à **102**.

### Étape 394 — Skin masculin TNG

Installation :

- Tempered Skins for Males - SOS Full Version

Décision : skin masculin validé avec TNG, sans futa / Gender Bender / patch adulte ajouté.

Validation : compteur non-light stable à **102**.

### Étape 395 — Ressources / patches body différés

Aucune installation.

Différés : CBBE AE-CC Outfits, No Rim Lighting, Normal Map Options, options SOS / collisions 3BA, TNG dll fix.

Exclus : The New Gentlewoman, SL Gender Bender, contenu Futanari / Female Schlong / Gender Bender, tanlines / pubes.

### Étape 396 — Décision OBody NG

Décision Fabien : **OBody NG souhaité plus tard** pour diversité corporelle NPC, mais intégration différée après base body / skins / presets BodySlide stabilisée.

### Étape 397 — Décision skins PJ / NPC

Décision : PB's Silky Skin sera réservé au PJ féminin à terme ; les NPC féminins auront une autre skin dédiée.

Isolation future prévue via Unique Player / Unique Character ou équivalent.

### Étape 398 — Unique Player différé

Décision : ne pas installer Unique Player / Unique Character maintenant.

Raison : attendre choix skin NPC féminine, BodySlide, OBody et stabilisation des fichiers meshes / textures.

### Étape 399 — Skin NPC féminine globale

Installation :

- BnP - Female Skin
- BnP female small update

Décision : BnP Female devient la skin féminine globale / NPC temporaire. PB reste le choix PJ à isoler plus tard.

Validation : compteur non-light stable à **102**.

### Étape 400 — Préparation isolation PJ

Aucune installation.

Décision : documenter la logique PB = PJ à terme, BnP = NPC / globale temporaire, isolation plus tard via Unique Player / Character.

### Étape 401 — CBPC pour 3BA

Installation :

- CBPC - Physics with Collisions for SSE and VR

Placement : **09 - ANIMATIONS SKELETON PHYSICS**, après FSMP.

Choix : main file uniquement, FPS config 120 si Skyrim est limité à 120 FPS. Optional bounce configs différés.

Note : XPMSSE n'est pas encore installé et devra être ajouté avant animations / SexLab / skeleton avancé.

Validation : compteur non-light stable à **102**.

---

## Décisions structurantes

- Le bloc 08.2 overlays / tattoos est provisoirement clôturé.
- Le bloc 08.3 BODY / SKINS / BODYSLIDE est ouvert.
- CBBE + 3BA + TNG forment la base body actuelle.
- PB's Silky Skin est réservé au PJ féminin à terme.
- BnP Female Skin sert de skin féminine globale / NPC temporaire.
- Tempered Skins for Males est validé côté masculin avec TNG.
- OBody NG est souhaité mais différé.
- Unique Player / Character est différé.
- BodySlide Output n'est pas généré.
- CBPC complète FSMP côté physique.
- XPMSSE reste à installer plus tard.

---

## Différés majeurs

- BodySlide Output
- Presets BodySlide
- OBody NG
- Unique Player / Unique Character
- CBBE AE-CC Outfits
- Normal Map Options
- 3BA options SOS / collisions adultes
- TNG dll fix Nefaram
- XPMSSE
- SlaveTats / Lyru SlaveTats
- Bathing / Dirt & Blood complet

---

## Exclusions confirmées

- Futanari
- Female Schlong
- Gender Bender
- The New Gentlewoman
- SL Gender Bender for TNG
- Tanlines
- Pubic hair overlays / pubes replacers
