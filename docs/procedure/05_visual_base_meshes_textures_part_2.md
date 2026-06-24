# SKYFORGE — Procédure — 05 - VISUAL BASE MESHES TEXTURES — part 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie poursuit le module `05 - VISUAL BASE MESHES TEXTURES` après l’étape 567.

---

## Étape 568 — ElSopa petit clutter visuel sans plugin

### Mods ajoutés

- ElSopa HD - Dirt Blast SE
- ElSopa - HD Keys Redone SE
- ElSopa - HD Giant Mortars Redone SE

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` après les objets JS Dwemer, avec de petits replacers visuels de clutter/effets sans plugin.

### Résultat installation

- Installation MO2 panneau gauche après `JS Instruments of Skyrim SE - 2k`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Aucun script lourd identifié
- Compteur ESP + ESM non-light inchangé : `129`

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 568 validée.
Prochaine étape attendue : 569.

## Étape 569 — ElSopa objets de quête / petit clutter sans plugin

### Mods ajoutés

- Meridia’s Luxon Beacon Replacer
  - https://www.nexusmods.com/skyrimspecialedition/mods/34782
- ElSopa HD - Briar Heart
  - https://www.nexusmods.com/skyrimspecialedition/mods/27983
- ElSopa HD - Skeleton Key SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/21992

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec des replacers visuels légers pour objets de quête / petit clutter.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Placement après les mods ElSopa de l’étape 568
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Aucun script lourd identifié
- Compteur ESP + ESM non-light inchangé : `129`

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 569 validée.
Prochaine étape attendue : 570.

## Étape 570 — Carriages + marchés animés BOS

### Mods ajoutés

- WiZkiD Carriages
  - https://www.nexusmods.com/skyrimspecialedition/mods/39640
- Market Stalls Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/110246
- Vendor Carts Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/110947
- Small Nordic Tent Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/101359

### Choix FOMOD / options

- Small Nordic Tent Animated :
  - option retenue : `JPSteel2’s Version`

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec replacers visuels légers pour carrioles, étals, chariots de vendeurs et petite tente nordique animée via BOS.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Placement après l’étape 569
- Plugins ajoutés :
  - `Small Nordic Tent-Animated.esp`
  - `Vendor Carts - Animated.esp`
  - `Vanilla Market Stalls - Animated.esp`
- Compteur ESP + ESM non-light inchangé : `129`
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

### Statut

Étape 570 validée.
Prochaine étape attendue : 571.

## Étape 571 — Tentes animées BOS

### Mods ajoutés

- Skyland Imperial and Nordic Tents
  - https://www.nexusmods.com/skyrimspecialedition/mods/57002
- Imperial Tents Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/101500
- Large Nordic Tent Replacer for Skyland Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/101373
- Falmer Huts Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/101539
- Hagraven Houses Animated
  - https://www.nexusmods.com/skyrimspecialedition/mods/101952

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec textures de base Skyland pour tentes impériales/nordiques et replacers animés BOS pour tentes, huttes Falmer et maisons de hagraven.

### Placement MO2 retenu

- `Skyland Imperial and Nordic Tents`
- `Imperial Tents Animated`
- `Large Nordic Tent Replacer for Skyland Animated`
- `Falmer Huts Animated`
- `Hagraven Houses Animated`

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Plugins ajoutés :
  - `Hagraven Houses - Animated.esp`
  - `Falmer Huts - Animated.esp`
  - `Skyland Large Nordic Tent - Animated.esp`
  - `Imperial Tents - Animated.esp`
- Compteur ESP + ESM non-light inchangé : `129`
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

### Statut

Étape 571 validée.
Prochaine étape attendue : 572.

## Étape 572 — Objets précieux : septims, griffes, crânes

### Mods ajoutés

- JS Purses and Septims SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/37306
- JS Dragon Claws AE Anniversary Edition
  - https://www.nexusmods.com/skyrimspecialedition/mods/57038
- Unique Skulls HD - SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/52073

### Choix textures

- Petits objets : textures `1K` retenues pour économiser les ressources.

### Choix FOMOD / options

- JS Dragon Claws AE :
  - Legacy of the Dragonborn : `None`
  - Wyrmstooth : `None`
  - Konahrik’s Accoutrements : `None`
  - Helgen Reborn : `None`
  - Skyrim Sewers : `Skyrim Sewers`
  - Note MO2 recommandée : `FOMOD A REVOIR PLUS TARD`

- Unique Skulls HD :
  - Main plugin : `ESPFE`
  - SkullKeys : non coché
  - SkullKeys ENB Light Patch : non coché
  - LOTD Options : non cochées
  - Note MO2 recommandée : `FOMOD A REVOIR PLUS TARD`

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Plugins ajoutés :
  - `PraedysSkulls.esp`
  - `JS Dragon Claws AE - Skyrim Sewers.esp`
- Compteur ESP + ESM non-light inchangé : `129`
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

### Statut

Étape 572 validée.
Prochaine étape attendue : 573.

## Étape 573 — Métaux, masques, potions, gemmes d’âme

### Mods ajoutés

- Metallurgy - Ingots Ore and Veins HD
  - https://www.nexusmods.com/skyrimspecialedition/mods/30738
- Apophysis Dragon Priest Masks SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/5800
- Awesome Potions Simplified by Revoith
  - https://www.nexusmods.com/skyrimspecialedition/mods/57607
- MultiLayer Parallax Soul Gems SSE
  - https://www.nexusmods.com/skyrimspecialedition/mods/25709

### Choix installation

- Metallurgy :
  - version retenue : `1K LOOSE`
  - patch Wyrmstooth : non installé

- Apophysis Dragon Priest Masks :
  - version retenue : `Loose`
  - Extra Apophysis : non installé
  - Konahrik Accoutrements Patch : non installé

- Awesome Potions Simplified :
  - version légère/standard retenue

- MultiLayer Parallax Soul Gems :
  - mod principal installé
  - patch ISC installé
  - patchs ENB Light / ELIF / GIST non installés
  - note MO2 recommandée : `PATCHES A REVOIR PLUS TARD`

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Plugins ajoutés :
  - `MLP + ISC Patch.esp`
  - `MLPSoulGems.esp`
  - `Awesome Potions Simplified by Revoith.esp`
- Compteur ESP + ESM non-light inchangé : `129`
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

### Statut

Étape 573 validée.
Prochaine étape attendue : 574.

## Étape 574 — Bateaux, os de dragon, ateliers

### Mods ajoutés

- DK's Nord Ship Texture Replacers
  - https://www.nexusmods.com/skyrimspecialedition/mods/12817
- Frankly HD Dragon Bones
  - https://www.nexusmods.com/skyrimspecialedition/mods/25099
- Renthal's Workbench
  - https://www.nexusmods.com/skyrimspecialedition/mods/23164
- Renthal's Tanning Rack
  - https://www.nexusmods.com/skyrimspecialedition/mods/23189

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec replacers visuels légers pour bateaux nordiques, os/écailles de dragon, établi et chevalet de tannage.

### Choix installation

- Petits objets / objets utilitaires : versions légères retenues quand disponibles.
- `High Poly Project` volontairement différé pour étape dédiée.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `129`
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 574 validée.
Prochaine étape attendue : 575.

## Étape 575 — Petits objets / effets visuels légers

### Mods ajoutés

- GORECAP
  - https://www.nexusmods.com/skyrimspecialedition/mods/16440
- ElSopa - HD Better Bloody Rags SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/44059
- 4K HQ Puddles
  - https://www.nexusmods.com/skyrimspecialedition/mods/33456
- Salmon Roe model replacer 3D
  - https://www.nexusmods.com/skyrimspecialedition/mods/42074
- RUSTIC MAPS
  - https://www.nexusmods.com/skyrimspecialedition/mods/42614

### Choix installation

- Petits objets / textures secondaires : versions légères retenues quand disponibles.
- `4K HQ Puddles` installé en version `2K`.
- `RUSTIC MAPS` installé en version `2K`.
- `High Poly Project` volontairement différé pour étape dédiée.
- `More Bloodshed` différé pour un bloc sang/effets dédié.
- `Stalhrim Source` différé.
- `Jabber's Archery Targets` différé, URL exacte à vérifier.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `129`
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 575 validée.
Prochaine étape attendue : 576.

## Étape 576 — Hagraven, mammoth bones, ateliers magiques, Falmer

### Mods ajoutés

- WiZkiD Hagraven Clutter and Bones
  - https://www.nexusmods.com/skyrimspecialedition/mods/49277
- Unreal 4K-8K Mammoth Skeleton ReTexture
  - https://www.nexusmods.com/skyrimspecialedition/mods/39356
- WiZkiD Alchemy Table
  - https://www.nexusmods.com/skyrimspecialedition/mods/42874
- Enchanting Stations Candles
  - https://www.nexusmods.com/skyrimspecialedition/mods/30140
- HD Reworked Falmer Architecture 4K
  - https://www.nexusmods.com/skyrimspecialedition/mods/41088

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec replacers visuels pour clutter hagraven, os de mammouth, tables d’alchimie, bougies d’enchantement et architecture Falmer.

### Choix installation

- `Stalhrim Source` différé.
- Mods Legacy of the Dragonborn différés.
- `High Poly Project` toujours différé pour étape dédiée.
- Versions légères retenues quand disponibles.
- `HD Reworked Falmer Architecture` installé malgré 4K, car mod ciblé sur une famille d’architecture spécifique.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `129`
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 576 validée.
Prochaine étape attendue : 577.

## Étape 577 — Coffres, strongboxes et cages

### Mods ajoutés

- ElSopa - Safe And Strongbox Redone
  - https://www.nexusmods.com/skyrimspecialedition/mods/109535
- East Empire Strongbox Logo SSE
  - https://www.nexusmods.com/skyrimspecialedition/mods/70396
- JS Common Cages SE
  - https://www.nexusmods.com/skyrimspecialedition/mods/68236

### Objectif

Poursuite du module `05 - VISUAL BASE MESHES TEXTURES` avec replacers visuels pour coffres forts, strongboxes East Empire Company et cages communes.

### Choix installation

- `ElSopa - Safe And Strongbox Redone` installé en version légère / 1K.
- `JS Common Cages SE` installé en version visuelle raisonnable.
- Aucun patch additionnel installé.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Plugin ajouté :
  - `East Empire Strongbox Logo.esp`
- Compteur ESP + ESM non-light inchangé : `129`
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

### Statut

Étape 577 validée.
Prochaine étape attendue : 578.

## Étape 578 — Stockades, dents de spectre, sigils

### Mods ajoutés

- Icy Wraith Teeth
  - https://www.nexusmods.com/skyrimspecialedition/mods/64356
- Stockades of Skyrim 3D
  - https://www.nexusmods.com/skyrimspecialedition/mods/43227
- FYX - 3D Stockades
  - https://www.nexusmods.com/skyrimspecialedition/mods/65104
- FYX - 3D Stockades - Walls and Gate
  - https://www.nexusmods.com/skyrimspecialedition/mods/66037
- Beautiful Sigils of Shalidor - 8k 4k 2k
  - https://www.nexusmods.com/skyrimspecialedition/mods/66598

### Choix installation

- `Beautiful Sigils of Shalidor` installé en version `2K`.
- Pour `FYX - 3D Stockades`, archive retenue :
  - `FYX - 3D Stockades - SoS 3D - Parallax`
- `FYX - 3D Stockades` standard non retenu séparément.
- `FYX - 3D Stockades - SoS 3D` non-parallax non retenu.
- Mods ENB Light / particules différés.

### Résultat installation

- Installation MO2 dans `05 - VISUAL BASE MESHES TEXTURES`
- Aucun plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `129`
- Overwrite vide

### Test validation

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

### Statut

Étape 578 validée.
Prochaine étape attendue : 579.
