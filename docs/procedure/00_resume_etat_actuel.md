# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape d’installation validée :** Étape 401 — Ajout CBPC pour 3BA
- **Séparateur actuellement ouvert :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module parent lié :** 08 - BODY RACE NPC APPEARANCE
- **Sous-bloc parent lié :** 08.3 - BODY / SKINS / BODYSLIDE
- **Raison de transition :** l’étape 401 installe CBPC dans le séparateur 09, même si elle complète techniquement la configuration 3BA installée dans 08.3.
- **Dernier module clôturé :** 07 - CITIES TOWNS INTERIORS LIGHTING
- **Dernier sous-bloc clôturé :** 08.2 - HAIR / EYES / BROWS / OVERLAYS terminé provisoirement après overlays / tattoos / eyes / brows
- **Prochaine étape attendue :** Étape 402 — à déterminer selon reprise : poursuite 09 physics / skeleton ou retour contrôlé 08.3 BodySlide / presets / OBody / isolation skin PJ

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK
- **Menu principal :** OK
- **Masters manquants :** aucun
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 102
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/99_changelog_validation_part_9.md`
3. `docs/procedure/12_body_race_npc_appearance_part_2.md`
4. `docs/procedure/09_animations_skeleton_physics_part_1.md`

## Note de transition importante — Étape 401

L’étape 401 doit être comprise comme une **étape de transition entre deux séparateurs** :

- elle reste liée à **08.3 BODY / SKINS / BODYSLIDE**, car CBPC complète le choix CBBE 3BA / SMP + CBPC Lite ;
- mais le mod installé, **CBPC - Physics with Collisions**, appartient bien au séparateur **09 - ANIMATIONS SKELETON PHYSICS**.

Pour éviter toute ambiguïté lors des reprises, le séparateur 09 est donc considéré comme officiellement ouvert à partir de l’étape 401.

## Règle de priorité module 08

Pour le module 08 - BODY RACE NPC APPEARANCE :

- Nefaram reste la référence principale pour corps, RaceMenu, presets, skins, cheveux, yeux, brows, visual NPC, body physics, overlays / tattoos et bases compatibles SexLab.
- Nolvus reste consulté pour conserver les améliorations utiles ou les patches cohérents.
- Aucun bloc adulte complet maintenant : on prépare seulement la base corporelle / visuelle.
- Installation progressive, petits packs, test SKSE / menu après chaque groupe.

## Étapes récentes validées

- Étape 384 — Pack overlays RaceMenu 1 : Just Blood Lite, Lamenthia, Community Overlays 1/2, Skin Feature Overlays, Female Makeup Suite.
- Étape 385 — Pack overlays RaceMenu 2 : Community Overlays 3, Yyvengar Bodypaint, Sakora's Make Over Kit.
- Étape 386 — Lyru's Tattoo Pack Collection, tanlines / pubes exclus.
- Étape 387 — Clôture overlays NSFW inutiles, exclusions confirmées.
- Étape 388 — Ouverture 08.3 BODY / SKINS / BODYSLIDE.
- Étape 389 — CBBE v2.0.3 + RoughSpun / Prisoner Bloody Fix.
- Étape 390 — CBBE 3BA / 3BBB v2.48.
- Étape 391 — The New Gentleman v4.2.5 validé.
- Étape 392 — TNG Generated INI sorti de l'Overwrite ; TNG dll fix Nefaram différé ; futanari / female schlong / gender bender exclus.
- Étape 393 — PB's Silky Skin for CBBE validé comme skin PJ féminin à terme.
- Étape 394 — Tempered Skins for Males - SOS Full Version validé comme skin masculin avec TNG.
- Étape 395 — Ressources / patches body différés ou exclus.
- Étape 396 — Décision Fabien : OBody NG souhaité plus tard pour diversité corporelle NPC.
- Étape 397 — Décision skins PJ / NPC : PB pour PJ à terme, NPC féminins avec skin dédiée.
- Étape 398 — Unique Player / Unique Character différé.
- Étape 399 — BnP Female Skin + small update validés comme skin féminine globale / NPC temporaire.
- Étape 400 — Préparation isolation PJ sans installation.
- Étape 401 — CBPC installé dans le séparateur 09 pour compléter la configuration 3BA SMP + CBPC Lite.

## Décisions et différés importants

### Module 08.2 — Overlays / tattoos / hygiène

- **Just Blood - Dirt and Blood Lite :** gardé provisoirement comme sang visuel léger.
- **Dirt & Blood complet / Bathing in Skyrim Renewed :** différés dans un futur sous-bloc hygiène / bain.
- **Lyru's Tattoo Pack Collection :** installé ; version SlaveTats différée jusqu'au bloc SexLab / SlaveTats.
- **Tanlines / pubes / pubic hair overlays :** exclus par choix Fabien.

### Module 08.3 — Body / skins / BodySlide

- **CBBE :** installé, morphs et BodySlide output différés.
- **CBBE 3BA :** installé, options SOS / collisions adultes à revoir plus tard.
- **TNG :** installé en logique Nefaram ; à surveiller pour éviter le problème de trou mesh sexe vu ailleurs.
- **TNG dll fix Nefaram :** différé jusqu'à vérification de version / compatibilité.
- **PB's Silky Skin :** choix skin PJ féminin à terme, actuellement écrasé probablement par BnP tant que l'isolation PJ n'est pas faite.
- **BnP Female Skin :** skin féminine globale / NPC temporaire.
- **Tempered Skins for Males :** skin masculin validé avec TNG.
- **OBody NG :** souhaité pour diversité NPC, mais différé après presets BodySlide et base stabilisée.
- **Unique Player / Unique Character :** différé après choix skin NPC / BodySlide / OBody.
- **BodySlide Output :** non généré.

### Module 09 — Animations / skeleton / physics

- **Séparateur 09 :** officiellement ouvert à partir de l’étape 401.
- **FSMP :** déjà validé, Skyrim 1.5.97 / NOT CUDA / AVX2 / FSMP MCM installé.
- **CBPC :** installé comme moteur physique complémentaire requis par 3BA SMP + CBPC Lite.
- **XPMSSE :** non encore installé, à intégrer avant animations / SexLab / skeleton avancé.

### Exclusions adultes confirmées

- Aucun contenu Futanari.
- Aucun Female Schlong.
- Aucun Gender Bender.
- The New Gentlewoman exclu.
- SL Gender Bender for TNG exclu.
- Tanlines / pubes / pubic hair overlays exclus.

### Module 07.6 INTERIORS

Les gros patchers du bloc INTERIORS restent différés :

- JK’s Interiors Patch Collection
- JK’s Guild HQ Interiors Patch Collection
- GG’s Thieves Guild HQ Patch Collection
- Lux / Lux Orbis / Lux Via patches
- eFPS / Northern Roads / LOTD patches

## Vigilances conservées

- **Breezehome :** version Nefaram à vérifier / privilégier lors du bloc maisons.
- **Temple de Dibella :** contrôle futur avec quêtes adultes, PNJ, scènes, marqueurs, navmesh et lighting.
- **Snazzy Furniture and Clutter Overhaul :** aucun addon de maison joueur coché.
- **Paintings for the College of Winterhold :** exclu / différé, requirement Ultimate College of Winterhold non retenu actuellement.
- **Simple Children :** exclu, bloquait au chargement avant menu ; remplacé par RS Children Overhaul.

## Dernier état stable

Profil stable étape 401 :

- SKSE / menu principal : OK
- Aucun master manquant
- Plugins cochés
- Overwrite vide
- Compteur ESP + ESM non-light : 102
