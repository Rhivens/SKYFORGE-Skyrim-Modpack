# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape d’installation validée :** Étape 383 — 08.2 pack yeux / sourcils
- **Module en cours :** 08 - BODY RACE NPC APPEARANCE
- **Sous-bloc en cours :** 08.2 - HAIR / EYES / BROWS / OVERLAYS
- **Dernier module clôturé :** 07 - CITIES TOWNS INTERIORS LIGHTING
- **Dernier sous-bloc clôturé :** 07.6 - INTERIORS
- **Prochaine étape attendue :** suite du sous-bloc 08.2 ou préparation progressive du bloc body/skins selon validation

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
- **Compteur ESP + ESM non-light :** 95
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés

## Règle de priorité module 08

Pour le module 08 - BODY RACE NPC APPEARANCE :

- Nefaram devient la référence principale pour corps, RaceMenu, presets, skins, cheveux, yeux, brows, visual NPC, body physics, overlays/tattoos et bases compatibles SexLab.
- Nolvus reste consulté pour conserver les améliorations utiles ou les patches cohérents.
- Aucun bloc adulte complet maintenant : on prépare seulement la base corporelle/visuelle.
- Installation progressive, petits packs, test SKSE/menu après chaque groupe.

## Étapes récentes validées

- Étape 376 — Audit module 08 BODY / RACE / NPC.
- Étape 377 — 08.1 CORE CHARACTER TOOLS pack 1 : Expressive Facegen, BodySlide, High Poly Head, UV Stretch Fix.
- Étape 378 — 08.1 CORE CHARACTER TOOLS pack 2 : base cheveux vanilla, Flawn Argonians, Vanilla Hair Remake SMP, FSMP, High Poly Vanilla Hair, Salt and Wind.
- Étape 379 — début 08.2 avec Conditional Expressions et incident Children.
- Étape 379B — remplacement Children par RS Children Overhaul.
- Étape 380 — KS Hairdos / Hair Suppression Fix / KS Hairdos SMP / Chooey retextures.
- Étape 381 — Dint HairPack02 + BDOR Hairs.
- Étape 382 — Expressive Facial Animation Male/Female ; Citizens différé.
- Étape 383 — The Eyes Of Beauty, Kala’s Eyes, Vampire Eyes, Kalilies Brows.

## Décisions et différés importants

### Module 08

- **Simple Children :** EXCLU, bloque au chargement avant menu.
- **RS Children Overhaul :** installé seul, sans patches, marqué A REINSTALL PLUS TARD.
- **OBody NG :** différé jusqu’au bloc body / 3BA / HIMBO.
- **BodySlide Output :** non généré pour l’instant.
- **Outfit Studio executable :** différé, à ajouter en fin de modpack si besoin.
- **Citizens of Tamriel Visual Overhaul :** différé jusqu’au choix Citizens standalone vs ezPG.
- **Citizens of Tamriel :** source officielle repérée chez Craftian itch.io, à traiter plus tard dans un bloc quêtes/NPC contenu.
- **EFA Female option Fair Skin Complexion :** différée jusqu’au bloc skins.
- **HN66s Long Eye Lashes / Dynamic Vampire Appearance / Kala’s Vampire Eyes / patches sourcils HPH-COTR-UBE :** différés.

### Module 07.6 INTERIORS

Les gros patchers du bloc INTERIORS restent différés :

- JK’s Interiors Patch Collection
- JK’s Guild HQ Interiors Patch Collection
- GG’s Thieves Guild HQ Patch Collection
- Lux / Lux Orbis / Lux Via patches
- eFPS / Northern Roads / LOTD patches

Comparaison future prévue :

- Nolvus reste prioritaire.
- Nefaram pourra être vérifié en complément si un patch ou choix d’intérieur est plus cohérent.
- Les patches ne seront installés que si tous les masters sont actifs et si la logique SKYFORGE reste propre.

## Vigilances conservées

- **Breezehome :** version Nefaram à vérifier / privilégier lors du bloc maisons.
- **Temple de Dibella :** contrôle futur avec quêtes adultes, PNJ, scènes, marqueurs, navmesh et lighting.
- **Snazzy Furniture and Clutter Overhaul :** aucun addon de maison joueur coché.
- **Paintings for the College of Winterhold :** exclu / différé, requirement Ultimate College of Winterhold non retenu actuellement.
- **FSMP :** configuration validée Skyrim 1.5.97 / NOT CUDA / AVX2 / FSMP MCM installé.

## Dernier état stable

Profil stable étape 383 :

- SKSE/menu principal : OK
- Aucun master manquant
- Plugins cochés
- Overwrite vide
- Compteur ESP + ESM non-light : 95
