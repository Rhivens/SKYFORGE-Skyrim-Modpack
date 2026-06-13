# Changelog / validation — partie 9

## Périmètre

Cette partie couvre la progression SKYFORGE des étapes **384 à 401**.

Elle concerne principalement :

- la fin du sous-bloc **08.2 - HAIR / EYES / BROWS / OVERLAYS** ;
- l'ouverture du sous-bloc **08.3 - BODY / SKINS / BODYSLIDE** ;
- l'ouverture officielle du séparateur **09 - ANIMATIONS SKELETON PHYSICS** à l'étape 401.

## Note importante de structure

L'étape 401 est une étape de transition :

- elle complète techniquement le choix **CBBE 3BA / SMP + CBPC Lite** fait dans le bloc 08.3 ;
- mais le mod installé, **CBPC - Physics with Collisions**, appartient bien au séparateur **09 - ANIMATIONS SKELETON PHYSICS**.

Pour éviter toute ambiguïté lors des reprises futures, l'étape 401 est donc aussi documentée dans :

```text
docs/procedure/09_animations_skeleton_physics_part_1.md
```

## État final validé

- **Dernière étape validée :** Étape 401 — Ajout CBPC pour 3BA
- **Séparateur actuellement ouvert :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module parent lié :** 08 - BODY RACE NPC APPEARANCE
- **Sous-bloc parent lié :** 08.3 - BODY / SKINS / BODYSLIDE
- **SKSE / menu principal :** OK
- **Masters manquants :** aucun
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 102
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré

## Étapes validées — résumé synthétique

- **Étape 384 :** overlays RaceMenu pack 1 — Just Blood Lite, Lamenthia, Community Overlays 1/2, Skin Feature Overlays, Female Makeup Suite. Compteur : 99.
- **Étape 385 :** overlays RaceMenu pack 2 — Community Overlays 3, Yyvengar Bodypaint, Sakora's Make Over Kit. Correction Sakora via `Set as <data> directory`. Compteur : 101.
- **Étape 386 :** Lyru's Tattoo pack collection validé ; tanlines / pubes exclus ; version SlaveTats différée.
- **Étape 387 :** clôture des overlays NSFW inutiles ; aucune installation.
- **Étape 388 :** ouverture du séparateur **08.3 BODY / SKINS / BODYSLIDE**.
- **Étape 389 :** CBBE v2.0.3 + RoughSpun / Prisoner Bloody Fix validés.
- **Étape 390 :** CBBE 3BA / 3BBB v2.48 validé ; BodySlide Output non généré.
- **Étape 391 :** The New Gentleman v4.2.5 validé ; patches futurs non cochés ; compteur : 102.
- **Étape 392 :** INI généré TNG sorti de l'Overwrite ; TNG dll fix différé ; contenus Futanari / Female Schlong / Gender Bender exclus.
- **Étape 393 :** PB's Silky Skin for CBBE validé comme skin PJ féminin à terme.
- **Étape 394 :** Tempered Skins for Males - SOS Full Version validé avec TNG.
- **Étape 395 :** ressources et patches body différés ; aucune installation.
- **Étape 396 :** décision Fabien — OBody NG souhaité plus tard pour diversité corporelle NPC.
- **Étape 397 :** décision skins PJ / NPC — PB pour PJ à terme, NPC féminins avec skin dédiée.
- **Étape 398 :** Unique Player / Unique Character différé.
- **Étape 399 :** BnP Female Skin + small update validés comme skin féminine globale / NPC temporaire.
- **Étape 400 :** préparation isolation PJ sans installation.
- **Étape 401 :** CBPC installé dans le séparateur **09 - ANIMATIONS SKELETON PHYSICS** pour compléter la configuration 3BA SMP + CBPC Lite.

## Décisions structurantes

- Le bloc 08.2 overlays / tattoos est provisoirement clôturé.
- Le bloc 08.3 BODY / SKINS / BODYSLIDE est ouvert depuis l'étape 388.
- Le séparateur 09 ANIMATIONS SKELETON PHYSICS est officiellement ouvert depuis l'étape 401.
- CBBE + 3BA + TNG forment la base body actuelle.
- PB's Silky Skin est réservé au PJ féminin à terme.
- BnP Female Skin sert de skin féminine globale / NPC temporaire.
- Tempered Skins for Males est validé côté masculin avec TNG.
- OBody NG est souhaité mais différé.
- Unique Player / Character est différé.
- BodySlide Output n'est pas généré.
- CBPC complète FSMP côté physique.
- XPMSSE reste à installer plus tard.

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

## Exclusions confirmées

- Futanari
- Female Schlong
- Gender Bender
- The New Gentlewoman
- SL Gender Bender for TNG
- Tanlines
- Pubic hair overlays / pubes replacers

## Références détaillées

Pour le détail complet des étapes :

- `docs/procedure/12_body_race_npc_appearance_part_2.md`
- `docs/procedure/09_animations_skeleton_physics_part_1.md`
