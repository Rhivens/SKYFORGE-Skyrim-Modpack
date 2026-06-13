# 12 - BODY RACE NPC APPEARANCE — partie 2

Suite du module **08 - BODY RACE NPC APPEARANCE**.

Ce fichier documente les étapes **384 à 401**, correspondant à la fin du sous-bloc overlays RaceMenu, au démarrage du bloc **08.3 BODY / SKINS / BODYSLIDE**, à la mise en place CBBE / 3BA / TNG / skins, puis à l'ajout de CBPC côté physique.

État de départ avant cette partie :

- Dernière étape précédente validée : **Étape 383 — 08.2 pack yeux / sourcils**
- Compteur ESP + ESM non-light : **95**
- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- LOOT : non lancé
- DynDOLOD / LOD : non générés

---

## Étape 384 — 08.2 HAIR / EYES / BROWS / OVERLAYS — Pack overlays RaceMenu

### Objectif

Ajouter un premier bloc d'overlays RaceMenu et de visuels légers sans engager le choix final body / skins, sans BodySlide, sans LOOT et sans LOD.

### Mods installés

- **Just Blood - Dirt and Blood Lite**
  - Ajout léger inspiré Nolvus / logique SKYFORGE.
  - Rôle : sang visuel léger uniquement.
  - Décision : gardé provisoirement.
  - Note MO2 : `PROVISOIRE - sang léger uniquement - choix hygiène Bathing vs Dirt&Blood à reprendre plus tard`
- **Lamenthia's Marks of Beauty 2k**
  - Marques de beauté / overlays RaceMenu.
  - Décision : gardé.
- **Community Overlays 1 - Main - CBBE 2K**
  - Overlays RaceMenu corps / visage.
  - Décision : gardé.
- **Community Overlays 1 - Bugfix Patch**
  - Correctif du pack Community Overlays 1.
  - Décision : gardé.
- **Community Overlays 1 - Female Face Overlays**
  - Face paints féminins RaceMenu.
  - Décision : gardé.
- **Community Overlays 1 - Male Face Overlays**
  - Face paints masculins RaceMenu.
  - Décision : gardé.
- **Community Overlays 2 - Main - CBBE and Male**
  - Overlays RaceMenu CBBE + masculin.
  - Décision : gardé.
  - Note MO2 : `CHOIX PROVISOIRE CBBE+MALE - COHERENT 3BA/HIMBO - A REVOIR SI BODY FINAL CHANGE`
- **Skin Feature Overlays - 4K**
  - Détails de peau / overlays RaceMenu.
  - Décision : gardé, installé plus tôt que prévu.
  - Note : `INSTALLE PLUS TOT QUE PREVU - OK SI TEST MENU PROPRE - A REVOIR AU BLOC SKINS`
- **Female Makeup Suite - Face - 4K**
  - Maquillages / face overlays RaceMenu.
  - Décision : gardé, installé plus tôt que prévu.
  - Note : `INSTALLE PLUS TOT QUE PREVU - OK SI TEST MENU PROPRE - A REVOIR AU BLOC SKINS`

### Choix techniques validés

- Priorité donnée aux versions **CBBE / 3BA / 3BBB** quand disponibles.
- Versions **UNP / UUNP / BHUNP / SAM** évitées.
- Fichiers masculins acceptés seulement quand ils sont génériques RaceMenu ou compatibles sans replacer body / feet risqué.
- Aucun replacer body / feet / skin installé à cette étape.
- Aucun système complet d'hygiène installé maintenant.

### Système hygiène / bain — décision différée

Comparaison faite avant installation de Just Blood :

- **Just Blood - Dirt and Blood Lite** : retenu maintenant car léger, visuel, faible risque.
- **Dirt & Blood complet** : option future possible, plus proche Nolvus, mais pas nécessaire à cette étape.
- **Bathing in Skyrim - Renewed + addons** : différé, système plus lourd / scripté avec compatibilité 1.5.97 à vérifier.

Sous-bloc futur prévu :

- **08.X / IMMERSION HYGIENE - Dirt, Blood, Bathing**

À vérifier plus tard : compatibilité 1.5.97, scripts SKSE / Papyrus, widgets, doublons avec Dirt & Blood / Just Blood, plugins ESP / ESL, impact immersion NSFW / Nefaram.

### Ordre MO2 validé

1. Just Blood - Dirt and Blood Lite
2. Lamenthia's Marks of Beauty 2k
3. Community Overlays 1 - Main - CBBE 2K
4. Community Overlays 1 - Bugfix Patch
5. Community Overlays 1 - Female Face Overlays
6. Community Overlays 1 - Male Face Overlays
7. Community Overlays 2 - Main - CBBE and Male
8. Skin Feature Overlays - 4K
9. Female Makeup Suite - Face - 4K

Note globale recommandée sur le séparateur 08.2 :

`PRIORITE CBBE/3BA/3BBB - EVITER UNP/UUNP/BHUNP/SAM - MALE GENERIQUE OK`

### Mods / options non installés

- Community Overlays replacers UNP / UUNP
- Community Overlays male replacers liés à SAM / body / feet
- Bathing in Skyrim - Renewed et addons
- Dirt & Blood complet
- OBody NG
- Dynamic Vampire Appearance
- Kala's Vampire Eyes
- More High Poly Head Eyebrow Patch Hub
- Reflective ENB Eyebrows Fix

### Validation

- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **99**

Décision : **Étape 384 validée**.

---

## Étape 385 — 08.2 HAIR / EYES / BROWS / OVERLAYS — Pack overlays RaceMenu 2

### Objectif

Compléter le bloc overlays RaceMenu avec un second petit pack orienté bodypaint / makeup, cohérent CBBE / 3BA / 3BBB, sans installer de replacer body / skin.

### Mods installés

- **Community Overlays 3 - Main - CBBE and Male**
  - Lien SE confirmé : https://www.nexusmods.com/skyrimspecialedition/mods/35339
  - Rôle : overlays RaceMenu supplémentaires corps / visage.
  - Choix : version CBBE and Male.
  - Note : `CHOIX CBBE/MALE - EVITER UNP/UUNP/BHUNP/SAM`
- **Yyvengar Bodypaint - Designs of the Lupine**
  - Lien SE confirmé : https://www.nexusmods.com/skyrimspecialedition/mods/37384
  - Rôle : bodypaints / overlays RaceMenu.
  - Choix : version Female and Male CBBE.
  - Note : `BODYPAINT RACEMENU - CHOIX CBBE/MALE - EVITER UNP/UUNP/BHUNP/SAM`
- **Sakora's Make Over Kit - SKSE64**
  - Rôle : kit makeup / overlays RaceMenu.
  - Plugin ajouté : `Sakora's Make Over Kit for SKSE64.esp`
  - Note : `STRUCTURE MANUELLE - SET AS DATA SUR DOSSIER DATA`

### Correction d'installation Sakora

MO2 indiquait : `The content of <data> does not look valid`.

Cause : archive imbriquée ainsi :

`Sakora's Make Over Kit SKSE64 > Data > Scripts / Source / Textures / ESP`

Correction appliquée : clic droit sur le dossier **Data**, puis **Set as <data> directory**.

Contenu racine après correction :

- Scripts
- Source
- Textures
- Sakora's Make Over Kit for SKSE64.esp

### Validation

- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **101**

Décision : **Étape 385 validée**.

---

## Étape 386 — Tattoos / bodypaints utiles, sans tanlines ni pubes

### Objectif

Ajouter uniquement des overlays utiles de type tattoos / bodypaints, en excluant ce que Fabien n'utilisera pas.

### Mod installé

- **Lyru's Tattoo pack collection**
  - Lien : https://www.nexusmods.com/skyrimspecialedition/mods/75222
  - Choix : version CBBE si proposée.
  - Note : `TATTOOS RACEMENU - CHOIX CBBE - TANLINES/PUBES EXCLUS PAR CHOIX FABIEN`

### Mods exclus volontairement

- Sunstarved - Tanlines
- Pubes Forever
- Tout mod dédié aux tanlines / pubic hair overlays / pubes replacers

### Différé

- **Lyru's Tattoo pack collection for SlaveTats** : différé jusqu'au bloc SexLab / SlaveTats.

Note recommandée :

`LYRU RACEMENU OK - VERSION SLAVETATS DIFFEREE JUSQU'AU BLOC SEXLAB / SLAVETATS`

### Validation

- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **101**

Décision : **Étape 386 validée**.

---

## Étape 387 — Clôture overlays NSFW inutiles / passage brows-beards

### Objectif

Finir proprement 08.2 sans ajouter de mods inutiles, puis préparer la suite logique.

### Décision

Aucun mod installé à cette étape.

Exclusions définitives pour SKYFORGE :

- Sunstarved - Tanlines
- Pubes Forever
- Tout mod dédié pubes / pubic hair / tanlines

Note : **pas de tanlines, pas de pubic hair overlays / replacers**.

### Différé confirmé

- Lyru's Tattoo pack collection for SlaveTats — différé jusqu'au bloc SexLab / SlaveTats.

État inchangé : SKSE / menu OK, Overwrite vide, compteur non-light **101**.

---

## Étape 388 — Ouverture 08.3 BODY / SKINS / BODYSLIDE

### Objectif

Préparer le bloc corps / skins avant CBBE / 3BA / TNG et textures de peau.

### Actions

- Séparateur **08.3 BODY- SKINS- BODYSLIDE** créé.
- Placé juste après le bloc 08.2.
- BodySlide peut rester dans Core Tools pour l'instant.
- Aucun BodySlide output généré.
- LOOT non lancé.

### Ordre de préparation prévu

1. CBBE
2. CBBE 3BA / 3BBB
3. TNG selon logique Nefaram
4. Skins féminins / masculins
5. Presets BodySlide
6. OBody NG plus tard seulement

État inchangé : compteur non-light **101**, Overwrite vide.

---

## Étape 389 — CBBE

### Objectif

Installer uniquement la base CBBE, sans CC outfits ni patchs BodySlide.

### Mods installés

- **Caliente's Beautiful Bodies Enhancer CBBE - v2.0.3**
- **RoughSpun Tunic and Prisoner Bloody Fix**

### Fichiers non installés maintenant

- CBBE AE-CC Outfits
- CBBE Outfits - No Rim Lighting
- Normal Map Options
- PSD Resources
- High Heels Resources
- Sleeves Patch

### Choix FOMOD retenus

- Body Shape : Curvy
- Underwear : None
- Vanilla Outfits : coché
- Face Pack : coché
- Dirt to Beauty Marks : décoché
- Eyebrows : None
- Pubic Hair : décoché
- RaceMenu Morphs : décoché
- Morph Files Body / Outfits : décoché

Notes :

- `BASE BODY FEMININ - CBBE v2.0.3 - AE/CC OUTFITS ET BODYSLIDE DIFFÉRÉS`
- `HOTFIX CBBE - ROUGHSPUN/PRISONER BLOODY - LAISSER ECRASER CBBE`

### Validation

- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **101**

Décision : **Étape 389 validée**.

---

## Étape 390 — CBBE 3BA / 3BBB

### Objectif

Installer CBBE 3BA / 3BBB au-dessus de CBBE.

### Mod validé

- **CBBE 3BA (3BBB) - v2.48**

### Choix FOMOD importants

- Base 3BA installée
- Pre-built Body mesh coché
- Nevernude décoché
- Underwear décoché
- CBPC Performance Balanced
- Physique : SMP and CBPC (Lite)
- No SOS
- Vagina collision : don't change
- Anal collision : don't add
- Patches FlowerGirls / VRIK : décochés
- RaceMenu : CBBE 3BA v1.6.x Morph Sliders

Note : `A REINSTALL PLUS TARD - options SOS/collisions adultes à revoir après body masculin + SexLab`

### Validation

- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **101**

Décision : **Étape 390 validée**.

---

## Étape 391 — The New Gentleman / TNG

### Objectif

Installer le body masculin TNG en logique Nefaram, en évitant de reproduire le problème du “trou vide” vu sur Nolvus.

### Décision

TNG est retenu, mais en mode prudent :

- Installer TNG seul.
- Ne pas installer de patch SOS / Nolvus maintenant.
- Ne pas installer HIMBO.
- Vérifier les conflits plus tard.

Lien retenu :

- **The New Gentleman** : https://www.nexusmods.com/skyrimspecialedition/mods/104215

### Choix FOMOD retenus

- Necessary Files
- Main Mesh
- HyliosFemaleMannequins : décoché
- Vigilant : décoché

Note :

`BASE BODY MASCULIN - TNG ADULT - LOGIQUE NEFARAM - PATCHES FUTURS NON COCHES - A SURVEILLER TROU MESH SEXE`

### Validation

- SKSE / menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **102**

Décision : **Étape 391 validée**.

---

## Étape 392 — TNG : Overwrite, DLL fix et exclusions adultes

### Objectif

Nettoyer l'installation TNG, clarifier le cas du TNG dll fix repéré dans Nefaram, et acter les exclusions avant skins.

### Correction Overwrite

Fichier apparu dans Overwrite :

`SKSE/Plugins/TheNewGentleman5.ini`

Action effectuée : création du mod dédié :

- **The New Gentleman - Generated INI**
  - Contenu : `SKSE/Plugins/TheNewGentleman5.ini`
  - Placé juste sous The New Gentleman.
  - Note : `INI GENERE PAR TNG - SORTI DE OVERWRITE`

### TNG dll fix Nefaram

Dans Nefaram, un mod **TNG dll fix** contient :

- TheNewGentleman.dll
- TheNewGentleman.pdb

Décision : **différé**.

Raison : ne pas copier une DLL non identifiée avant vérification de version, compatibilité TNG, compatibilité Skyrim 1.5.97 et utilité réelle.

Note :

`TNG DLL FIX NEFARAM PRESENT - DLL/PDB uniquement - à vérifier version avant copie`

### Exclusions adultes validées

Exclus :

- The New Gentlewoman - Add-Ons for T.N.G.
- SL Gender Bender for The New Gentleman
- Tout contenu Futanari / Female Schlong / Gender Bender
- Options FOMOD liées Female SOS / futa
- Patches SexLab dédiés à ces systèmes

Note :

`EXCLUSION FABIEN - aucun contenu Futanari / Female Schlong / Gender Bender`

### État final

- The New Gentleman reste installé.
- The New Gentleman - Generated INI créé.
- Overwrite vidé.
- Compteur non-light : **102**

Décision : **Étape 392 validée**.

---

## Étape 393 — Skin féminin PJ

### Objectif

Installer le skin féminin choisi par Fabien pour le personnage joueur.

### Décision

La proposition initiale BNP Female Skin est remplacée pour le PJ par :

- **PB's Silky Skin for CBBE**
  - Lien : https://www.nexusmods.com/skyrimspecialedition/mods/95818

BNP Female Skin n'est pas installé à ce stade pour le PJ.

Note :

`SKIN PJ FEMININ - PB SILKY SKIN CBBE - BNP DIFFERE POUR NPC OU NON RETENU`

### Validation

- SKSE / menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur non-light : **102**

Décision : **Étape 393 validée**.

---

## Étape 394 — Skin masculin TNG

### Objectif

Installer un skin masculin compatible avec la logique Nefaram / TNG, sans SOS additionnel, futa, Gender Bender ou patchs adultes.

### Mod validé

- **Tempered Skins for Males - SOS Full Version**
  - Lien : https://www.nexusmods.com/skyrimspecialedition/mods/7902

Note :

`SKIN MASCULIN - TEMPERED SOS FULL - UTILISE AVEC TNG - PAS DE FUTA/GENDER BENDER`

### Ordre 08.3 validé à ce stade

1. Caliente's Beautiful Bodies Enhancer - CBBE
2. RoughSpun Tunic and Prisoner Bloody Fix
3. CBBE 3BA (3BBB) - A REINSTALL PLUS TARD - options SOS / collisions
4. The New Gentleman - PATCHES A VOIR PLUS TARD
5. The New Gentleman - Generated INI
6. PB's Silky Skin
7. Tempered Skins for Males - SOS Full Version

### Validation

- SKSE / menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur non-light : **102**

Décision : **Étape 394 validée**.

---

## Étape 395 — Ressources / patches body à ne pas installer maintenant

### Objectif

Nettoyer les choix autour de CBBE / 3BA / TNG avant d'ajouter d'autres couches.

### Différés

- CBBE AE-CC Outfits
- CBBE Outfits - No Rim Lighting
- Normal Map Options
- 3BA options SOS / collisions
- TNG dll fix

### Exclus

- The New Gentlewoman
- SL Gender Bender for TNG
- Tout contenu Futanari / Female Schlong / Gender Bender
- Mods dédiés tanlines / pubes

Aucune installation. État inchangé : SKSE / menu OK, Overwrite vide, compteur non-light **102**.

---

## Étape 396 — Décision OBody NG / presets BodySlide

### Objectif

Décider la logique des formes de corps avant OBody NG ou presets BodySlide.

### Décision Fabien

Option B validée : **OBody NG**, mais **pas maintenant**.

Raison : OBody NG est intéressant pour la diversité corporelle NPC, mais doit venir après :

- CBBE / 3BA validé
- TNG validé
- Skins validés
- Presets BodySlide choisis
- BodySlide Output préparé
- Configs OBody contrôlées

Note GitHub :

`Décision Fabien : utiliser OBody NG pour diversité corporelle NPC, mais intégration différée après presets BodySlide.`

Aucune installation. État inchangé : compteur non-light **102**.

---

## Étape 397 — Décision skins PJ / NPC

### Objectif

Clarifier si PB's Silky Skin doit rester global ou devenir skin PJ uniquement.

### Décision validée

- PB's Silky Skin sera utilisé uniquement pour le PJ féminin à terme.
- Les NPC féminins auront une autre skin dédiée à choisir plus tard.
- Séparation future via système type Unique Player / Unique Character.

État actuel : PB agit probablement encore comme skin féminine globale tant qu'un système d'isolation PJ n'est pas installé.

Note MO2 :

`SKIN PJ UNIQUEMENT A TERME - actuellement globale - isoler plus tard via Unique Player/Character`

Aucune installation. État inchangé : compteur non-light **102**.

---

## Étape 398 — Isolation skin PJ : différer Unique Player

### Objectif

Préparer la séparation future skin PJ / skin NPC sans casser CBBE / 3BA / TNG.

### Décision

Différer Unique Player / Unique Character.

Raison : il faudra copier proprement les textures body / hand / face, voire les meshes 3BA, après stabilisation BodySlide / OBody et après choix skin NPC féminine.

Note GitHub :

`Séparation skin PJ/NPC validée, mais Unique Player/Character différé après choix skin NPC féminine et BodySlide.`

Aucune installation. État inchangé : compteur non-light **102**.

---

## Étape 399 — Skin NPC féminine globale

### Objectif

Installer une skin féminine globale / NPC temporaire, en attendant l'isolation future du PJ.

### Mods validés

- **BnP - Female Skin**
  - Lien : https://www.nexusmods.com/skyrimspecialedition/mods/65274
- **BnP female small update**

### Choix importants

- CBBE
- Résolution raisonnable, éviter 8K
- Pas de pubic hair
- Pas d'options UNP / BHUNP
- ESP fix installé, ESL-flagged, donc pas d'impact sur compteur non-light
- BnP SK fix : non installé
- BnP female extra options fixes : non installé

### Rôle actuel

BnP Female devient la skin féminine globale temporaire, destinée à terme aux NPC féminins.

PB's Silky Skin reste le choix PJ féminin, mais sera isolé plus tard via Unique Player / Unique Character. Pour l'instant, BnP écrase probablement PB tant que l'isolation PJ n'est pas faite.

Notes :

- PB : `SKIN PJ UNIQUEMENT A TERME - écrasée temporairement par BNP jusqu'à isolation Unique Player`
- BnP : `SKIN FEMININ NPC/GLOBALE TEMPORAIRE - CBBE - à conserver pour NPC après isolation PJ`

### Validation

- SKSE / menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur non-light : **102**

Décision : **Étape 399 validée**.

---

## Étape 400 — Préparation isolation PJ, sans installer encore

### Objectif

Préparer proprement la future séparation skin PJ / skin NPC, sans ajouter de système fragile maintenant.

### Décision

Ne pas installer Unique Player / Unique Character maintenant.

La base body / skins est suffisante pour avancer :

- CBBE installé
- 3BA installé
- TNG installé
- Skin PJ choisie : PB's Silky Skin
- Skin NPC féminine globale : BnP Female Skin
- Skin masculin : Tempered Skins for Males

### Notes MO2 recommandées

Sur PB's Silky Skin :

`SKIN PJ UNIQUEMENT A TERME - actuellement écrasée par BnP - isoler plus tard`

Sur BnP Female Skin :

`SKIN NPC FEMININE GLOBALE - doit rester après PB tant que l'isolation PJ n'est pas faite`

Aucune installation. État inchangé : compteur non-light **102**.

---

## Étape 401 — Ajout CBPC pour 3BA

### Objectif

Installer le moteur physique CBPC, nécessaire à la configuration 3BA choisie en SMP and CBPC Lite.

### Pourquoi cette étape était nécessaire

Lors de l'étape 390, CBBE 3BA a été installé avec une configuration combinant :

- FSMP / HDT-SMP pour la physique SMP
- CBPC pour une partie des collisions / physiques corporelles

Seul FSMP était déjà installé dans **09 - ANIMATIONS SKELETON PHYSICS**. Il fallait donc ajouter CBPC avant de considérer la base body / physics comme cohérente.

### Mod installé

- **CBPC - Physics with Collisions for SSE and VR**
  - Rôle : moteur physique / collisions utilisé par 3BA.
  - Plugin : aucun plugin non-light ajouté.
  - Placement : 09 - ANIMATIONS SKELETON PHYSICS.

Note :

`MOTEUR PHYSIQUE CBPC - requis par 3BA SMP+CBPC Lite - SE 1.5.97`

### Fichier optionnel non installé

- **3B Breast-Butt Bounce Configs for 3BA-BHUNP-COCO**

Décision : différé après presets BodySlide, BodySlide Output, OBody NG et tests en jeu.

Note :

`MAIN FILE ONLY - optional bounce configs différés après BodySlide/OBody`

### Choix FOMOD CBPC

Choix visible : **120 fps** sélectionné.

Note :

`CBPC MAIN FILE ONLY - FPS CONFIG 120 SI SKYRIM LIMITE A 120 - BOUNCE CONFIGS DIFFERES`

### Ordre dans le bloc 09

Ordre validé provisoire :

1. FSMP / Faster HDT-SMP
2. CBPC - Physics with Collisions

Précision : **XPMSSE n'est pas encore installé**. Il devra être intégré plus tard avant les blocs animations / SexLab / skeleton avancé.

Note sur séparateur 09 :

`XPMSSE NON ENCORE INSTALLE - à intégrer avant animations/SexLab`

### Validation

- SKSE / menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **102**

Décision : **Étape 401 validée**.

---

## État final après étape 401

- Dernière étape validée : **Étape 401 — Ajout CBPC pour 3BA**
- Module en cours : **08 - BODY RACE NPC APPEARANCE**
- Sous-bloc en cours : **08.3 BODY / SKINS / BODYSLIDE**
- Bloc physique lié : **09 - ANIMATIONS SKELETON PHYSICS** ouvert ponctuellement pour FSMP / CBPC
- SKSE / menu principal : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP + ESM non-light : **102**
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- BodySlide Output : non généré

## Différés majeurs conservés

- BodySlide Output
- Presets BodySlide
- OBody NG, validé en intention mais différé
- Unique Player / Unique Character pour isolation skin PJ
- Skin PJ PB's Silky Skin à isoler plus tard
- BnP Female à conserver comme skin NPC / globale temporaire
- CBBE AE-CC Outfits
- Normal Map Options
- 3BA options SOS / collisions adultes
- TNG dll fix Nefaram
- XPMSSE
- SlaveTats / Lyru SlaveTats
- Système hygiène complet Bathing / Dirt & Blood
- Tout contenu Futanari / Female Schlong / Gender Bender exclu
