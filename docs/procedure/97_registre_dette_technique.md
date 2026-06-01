# Registre central de dette technique SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## Objectif

Ce fichier centralise les éléments à reprendre plus tard dans SKYFORGE :

- patches différés ;
- FOMOD à réinstaller ;
- mods installés mais décochés ;
- dépendances / masters manquants ;
- patch hubs à compléter ;
- choix à revoir ;
- vérifications ESPFE / ESL / master-flagged ;
- LOD / TexGen / DynDOLOD ;
- réglages `.ini`, `.json`, `.yaml`, `.txt`, MCM ou SKSE différés.

Ce registre ne remplace pas les fichiers détaillés de décisions différées.  
Il sert de **table de pilotage** pour retrouver rapidement les dettes techniques sans relire toute la procédure.

---

## Sources de référence

Les détails complets restent documentés dans :

- `docs/procedure/06_decisions_differees.md`
- `docs/procedure/06_decisions_differees_part_2.md`
- `docs/procedure/06_decisions_differees_part_3.md`
- `docs/procedure/06_decisions_differees_part_4.md`
- les fichiers thématiques des modules concernés.

---

## Légende des types

| Type | Signification |
|---|---|
| `A_REINSTALLER` | Mod installé mais FOMOD / options à reprendre plus tard. |
| `PATCHES_A_REVOIR` | Patches non installés ou différés tant que les mods parents ne sont pas stabilisés. |
| `A_COMPLETER` | Patch hub / collection installé mais options non finalisées. |
| `DECOCHE_RESERVE` | Mod installé mais désactivé volontairement. |
| `MASTER_MANQUANT` | Plugin ou patch désactivé car un master manque. |
| `CHOIX_A_REVOIR` | Choix fonctionnel / technique non tranché. |
| `VERIFICATION` | Contrôle technique à effectuer plus tard. |
| `LOD_DYNDOLOD` | Éléments à reprendre pendant la génération LOD / TexGen / DynDOLOD. |
| `CONFIG_A_REVOIR` | Réglage `.ini`, `.json`, `.yaml`, `.txt`, MCM ou SKSE à appliquer plus tard. |
| `ABANDONNE` | Mod ou option abandonné / supprimé. |
| `RESOLU` | Dette levée. |

---

## Légende des priorités

| Priorité | Sens pratique |
|---|---|
| `Haute` | À traiter avant patching final, LOOT, xEdit, LOD ou gros module dépendant. |
| `Moyenne` | À traiter avant validation complète du module concerné. |
| `Faible` | À revoir seulement si le mod parent ou le besoin apparaît. |
| `Info` | Décision importante à garder en mémoire, sans action immédiate. |

---

## Registre synthétique

| Module | Étape | Élément | Type | Raison | Dépend de | Moment de reprise | Priorité | Statut |
|---|---:|---|---|---|---|---|---|---|
| 02 - Core / Réserve | 41 | Kris's Papyrus Extender | `DECOCHE_RESERVE` | Dépendance potentielle préparée sans activation. | Futurs mods qui le requièrent. | Quand un mod parent le demande. | Faible | Ouvert |
| 02 - Core / UI futur | 45 | Object Categorization Framework | `A_REINSTALLER` | Intégration prématurée évitée. | Bloc UI / icônes / inventaire. | Module UI avancé / catégorisation. | Moyenne | Ouvert |
| 02 - Core / Keywords | 46 | Keyword Patch Collection | `A_REINSTALLER` | Patch collection dépendante des mods réellement installés. | Inventaire, armures, armes, mots-clés. | Modules armures / inventaire / patches. | Moyenne | Ouvert |
| 02 - Core / AI | 47 | NPC AI Process Position Fix - NG | `A_REINSTALLER` | À installer après stabilisation de l’IA NPC. | AI Overhaul. | Module NPC / AI Overhaul. | Moyenne | Ouvert |
| 02 - Core / SKSE | 48 | Réglages SKSE custom | `CONFIG_A_REVOIR` | Réglages moteur différés volontairement. | Scrambled Bugs, PO3 Tweaks, Display Tweaks, Engine Fixes, Papyrus Tweaks NG. | Après stabilisation du socle technique. | Haute | Ouvert |
| 02 - Core / SexLab futur | 203 | MuJointFix - Sexlab Ostim Patch | `DECOCHE_RESERVE` | Patch réservé au futur module SexLab. | SexLab 1.63 / futurs systèmes animation. | Module SexLab / animations. | Moyenne | Ouvert |
| 03 - UI HUD MENUS | 45 | Object Categorization Framework | `A_REINSTALLER` | À reprendre avec la logique UI / inventaire. | UI, icônes, inventaire, catégorisation. | Module UI avancé. | Moyenne | Ouvert |
| 03 - UI HUD MENUS | 46 | Keyword Patch Collection | `A_REINSTALLER` | Dépend des mods équipables et mots-clés finaux. | Armures, armes, inventaire, UI. | Modules armures / inventaire. | Moyenne | Ouvert |
| 03 - UI HUD MENUS | 151 | Vel’dun UI patches | `PATCHES_A_REVOIR` | Patches dépendants des mods parents non encore tous installés. | Mods UI / gameplay futurs. | Après stabilisation UI / HUD. | Moyenne | Ouvert |
| 03 - UI HUD MENUS | 151 | QuickLoot IE | `CHOIX_A_REVOIR` | Différé pour préserver la logique future SexLab / Devious / Cursed Loot et fouille manuelle. | Systèmes Devious / Cursed Loot / gameplay immersion. | Module gameplay / Devious. | Moyenne | Ouvert |
| 03 - UI HUD MENUS | 151 | HideUI | `CHOIX_A_REVOIR` | Différé. | Futurs besoins screenshots / immersion. | Tests ingame / screenshots. | Faible | Ouvert |
| 03 - UI HUD MENUS | 151 | Photo Mode | `CHOIX_A_REVOIR` | Différé jusqu’aux futurs tests ingame / screenshots. | Besoins captures / présentation. | Tests ingame / screenshots. | Faible | Ouvert |
| 03 - UI HUD MENUS | 151 | Better AltTab | `VERIFICATION` | À installer plus tard avec test individuel ALT+TAB. | Tests ingame en vraie session. | Phase confort / stabilité. | Faible | Ouvert |
| 04 - Audio | 185 | AOS / ISC / Volkihar Soundscape / Standing Sound Stones / Bleeding Edge / Elder Songs | `A_REINSTALLER` | Logique de réinstallation future conservée. | Choix audio finaux, patches audio, mods parents. | Audit audio final. | Moyenne | Ouvert |
| 04 - Audio | 185 | Magic College Music | `DECOCHE_RESERVE` | Désactivé à cause du warning Form 43. | Conversion éventuelle / alternative audio. | Audit audio / CK si nécessaire. | Faible | Ouvert |
| 04 - Audio | 185 | Phoenix Compendium / Whispering Tomes / Nyghtfall / Dark Era / Music Mods Merged | `CHOIX_A_REVOIR` | Non actifs à ce stade. | Choix musique finale. | Module audio final. | Faible | Ouvert |
| 05 - Visual Base | 207 | Mesh Patch for Various Mods | `PATCHES_A_REVOIR` | Certains patches non pris car dépendants de mods non retenus. | ELFX, Blended Roads, Landscape and Water Fixes, Solitude Mesh Fixes. | Patching meshes / routes / lighting final. | Moyenne | Ouvert |
| 05 - Visual Base | 209 | Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch | `PATCHES_A_REVOIR` | Exclu car dépend d’une logique ELFX non retenue. | ELFX éventuel. | Uniquement si ELFX revient. | Faible | Ouvert |
| 05 - Visual Base | 309 | `[05.1 - PARALLAX FRAMEWORK TEXTURES]` | `CHOIX_A_REVOIR` | Séparateur créé pour futurs frameworks / textures / patches Parallax globaux. | Parallax TXST Fixes, ENB, Complex Terrain, shaders. | Bloc Parallax avancé. | Haute | Ouvert |
| 05 - Visual Base / ENB | 130 | ENB Extender Skyrim | `DECOCHE_RESERVE` | Dépend de `d3d11.dll`, donc d’un ENB binaire actif. | ENB binaire actif. | Bloc ENB. | Moyenne | Décoché |
| 06 - Landscape | 213 | Complementary Grass Fixes | `A_REINSTALLER` | Core installé, patches optionnels différés. | JK’s, Great Cities, Ryn, CRF, Verdant, autres villes / quêtes. | Après stabilisation villes / herbes / paysages. | Haute | Ouvert |
| 06 - Landscape | 215 | Skyrim Landscape and Water Fixes | `A_REINSTALLER` | Options et patches dépendants des futurs choix paysage / eau / villes / quêtes. | Water for ENB, Majestic Mountains, Lanterns, Helgen, No Snow, etc. | Avant patching final paysages / villes. | Haute | Ouvert |
| 06 - Landscape | 217 | Majestic Mountains | `A_REINSTALLER` | Options non prises et réinstallation future possible. | Moss Rocks, effect meshes, sun direction, paysages avancés. | Bloc montagne / parallax / ENB. | Moyenne | Ouvert |
| 06 - Landscape | 219 | Atlantean Landscape | `MASTER_MANQUANT` | `Atlantean Landscape.esp` requiert `Parallax TXST Fixes.esp`. | Parallax TXST Fixes, Complex Terrain, ENB. | Bloc Parallax / Complex Terrain / ENB. | Haute | Décoché |
| 06 - Landscape | 220 | Happy Little Trees | `A_REINSTALLER` | Alternatives neige et billboards non finalisés. | Bloc neige / météo / ENB / DynDOLOD. | Avant DynDOLOD arbres. | Haute | Ouvert |
| 06 - Landscape | 220 | Tree Billboards - HLT 1.01 | `LOD_DYNDOLOD` | Non installé à ce stade. | Choix final arbres / DynDOLOD. | Phase LOD / DynDOLOD. | Haute | Ouvert |
| 06 - Landscape | 235 | Water for ENB - No Parallax | `A_REINSTALLER` | Peut dépendre des futurs choix ENB / parallax / météo / carte finale. | ENB, météo, parallax, carte, iNeed éventuel. | Bloc eau / ENB final. | Haute | Ouvert |
| 06 - Landscape | 239 | Snowy Surfaces Sound Collision and Aesthetics | `A_REINSTALLER` | Installé sans patch, à revoir avec neige / météo. | Bloc snow / météo / ENB. | Module neige / météo. | Moyenne | Ouvert |
| 06 - Landscape | 247 | Praedy's Soul Cairn - SE | `CHOIX_A_REVOIR` | Différé à cause du prérequis `Skeleton Replacer HD - SE`. | Skeleton Replacer HD - SE. | Mini-bloc Soul Cairn / skeleton replacer. | Faible | Différé |
| 06 - Landscape | 250 | Plugins paysage récents | `VERIFICATION` | Statut ESPFE / light ou ESP normal à confirmer. | MO2 / xEdit. | Audit plugin count / xEdit. | Moyenne | Ouvert |
| 06 - Landscape | 254 | Unique Flowers & Plants.esp | `VERIFICATION` | Vérifier master-flagged ou ESP normal. | MO2 / xEdit. | Audit plugin count / xEdit. | Faible | Ouvert |
| 06 - Landscape | 260 | The Omnibus - Terrain Complex Parallax AiO | `CHOIX_A_REVOIR` | Différé pour logique Parallax / Complex Terrain / ENB. | Atlantean, Parallax TXST, ENB. | Bloc Parallax avancé. | Haute | Différé |
| 06 - Landscape | 263 | Ancient Trees Of Skyrim | `ABANDONNE` | Source Bethesda Xbox only / Nexus désactivée ou non maintenue. | Aucun. | Ne pas reprendre sauf nouvelle source fiable. | Info | Abandonné |
| 07 - Cities | 267 | Lux Orbis Patch Hub | `A_COMPLETER` | Patch hub installé mais non finalisé. | Villes, villages, routes, intérieurs, météo, patches retenus. | Après stabilisation module 07. | Haute | Ouvert |
| 07 - Cities | 269-298 | Patch collections Great Cities / COTN / Environs / villages | `A_COMPLETER` | Patches dépendants des mods réellement installés. | Lux, Lux Orbis, routes, AI Overhaul, Embers, Lanterns, Ryn, Solstheim, etc. | Phase patching module 07. | Haute | Ouvert |
| 07 - Cities | 274 | 3DNPC-TGCoMM Patch by WiZkiD | `PATCHES_A_REVOIR` | `3DNPC` non installé. | Interesting NPCs / 3DNPC. | Si 3DNPC est intégré. | Faible | Différé |
| 07 - Cities | 277 | Dragon Bridge | `CHOIX_A_REVOIR` | Zone complexe à patcher avec routes / ponts / Lux / villes. | Routes, ponts, Lux, villes. | Bloc routes / ponts / villes. | Moyenne | Différé |
| 07 - Cities | 279 | Falkreath patches | `PATCHES_A_REVOIR` | Éviter mélange COTN / JK / patches complexes. | Choix Falkreath final. | Patching villes. | Moyenne | Ouvert |
| 07 - Cities | 280/284 | Dawnstar CC Fishing Patch | `PATCHES_A_REVOIR` | Patch identifié mais différé. | The Great City of Dawnstar / CC Fishing. | Patching Great Cities. | Moyenne | Ouvert |
| 07 - Cities | 281/285 | Cities of the North - Morthal | `CHOIX_A_REVOIR` | Décoché, choix final Morthal à revoir. | Choix Morthal final. | Module villes / Morthal. | Haute | Décoché |
| 07 - Cities | 282/283 | Cities of the North - Winterhold | `RESOLU` | Remplacé par The Great City of Winterhold. | Aucun. | Aucun sauf changement d’orientation. | Info | Résolu |
| 07 - Cities | 287 | Half-Moon Mill COTN Addon patches | `PATCHES_A_REVOIR` | Patches Ryn / AI Overhaul non installés. | Ryn’s Lumber Mills, AI Overhaul. | Si mods parents retenus. | Faible | Ouvert |
| 07 - Cities | 288 | Anga’s Mill COTN Addon patches | `PATCHES_A_REVOIR` | Plusieurs patches non cochés faute de mods parents. | AI Overhaul, Embers, LoS II, Ryn, NSUTR, etc. | Si mods parents retenus. | Faible | Ouvert |
| 07 - Cities | 289 | Environs Hroggar’s House Patch Collection | `PATCHES_A_REVOIR` | Tout laissé décoché car Morthal COTN est décoché. | Choix final Morthal, Lux / Lux Orbis. | Après décision Morthal. | Moyenne | Ouvert |
| 07 - Cities | 290-298 | Villages / settlements Nolvus | `PATCHES_A_REVOIR` | Patches différés sauf Vernim Wood USSEP. | Lux, Lux Orbis, routes, Solstheim, Raven Rock, Tel Mithryn, etc. | Patching villages. | Haute | Ouvert |
| 07 - Cities | 294 | Dunmer Settlements of Solstheim ESL | `PATCHES_A_REVOIR` | Patches Solstheim / Raven Rock / Tel Mithryn différés. | Solstheim, Raven Rock, Tel Mithryn. | Patching Solstheim. | Moyenne | Ouvert |
| 07.1 - Player Homes | 299-306 | Player Homes patches | `PATCHES_A_REVOIR` | Patches maisons différés. | Mods parents, Lux / Lux Orbis, CACO, Skald’s Mail, Verdant. | Patching Player Homes. | Moyenne | Ouvert |
| 07.1 - Player Homes | 299 | JK’s Riverfall Cottage patches | `PATCHES_A_REVOIR` | Dépendent de Skald’s Mail et CACO. | Skald’s Mail, CACO. | Si mods parents retenus. | Faible | Ouvert |
| 07.1 - Player Homes | 300 | Sicarius’ Refuge Verdant / Lux / Lux Orbis | `PATCHES_A_REVOIR` | Verdant absent, Lux / Lux Orbis différés. | Verdant, Lux, Lux Orbis. | Après choix grass / lighting. | Moyenne | Ouvert |
| 07.1 - Player Homes | 303 | Settings Loader Hearthfire Multiple Adoptions | `CHOIX_A_REVOIR` | Introuvable / non confirmé. | Source fiable éventuelle. | Uniquement si retrouvé. | Faible | Annulé / introuvable |
| 07.1 - Player Homes | 305 | Lakeview Manor - As It Should Be | `PATCHES_A_REVOIR` | Ajout externe Fabien, patching complémentaire différé. | CC Fishing, autres patches éventuels. | Patching Player Homes. | Moyenne | Ouvert |
| 07.2 - Farmhouses | 308-314 | Farmhouses patches / LOD | `PATCHES_A_REVOIR` | Patches / LOD / DynDOLOD différés. | Parallax, snow, LOD, DynDOLOD. | Avant LOD / DynDOLOD. | Haute | Ouvert |
| 07.2 - Farmhouses | 312 | Scarecrows of Skyrim - BOS - SOS Patch | `MASTER_MANQUANT` | Requiert `Simplicity of Snow.esp`. | Simplicity of Snow.esp. | Bloc neige / snow. | Moyenne | Décoché |
| 07.3 - Other Locations | 315 | This Is Jorrvaskr - KASA | `CHOIX_A_REVOIR` | Non installé. | Choix Jorrvaskr final. | Patching Other Locations. | Faible | Non installé |
| 07.3 - Other Locations | 315 | This Is Jorrvaskr patches | `PATCHES_A_REVOIR` | Aucun patch optionnel installé. | Lux / lighting / mods parents. | Patching Other Locations. | Moyenne | Ouvert |
| 07.3 - Other Locations | 316 | JK's Fort Dawnguard / JK's Castle Volkihar patches | `PATCHES_A_REVOIR` | Aucun patch installé. | Lux, Lux Orbis, lighting, navmesh, Nolvus. | Patching Dawnguard / Volkihar. | Moyenne | Ouvert |
| 07.4 - Lands | 320 | Drinking Fountains patches | `PATCHES_A_REVOIR` | Patches Midwood Isle / Great Towns / autres différés. | Midwood Isle, Great Towns, autres contenus futurs. | Patching Lands / nouveaux mondes. | Moyenne | Ouvert |
| 07.4 - Lands | 321 | My Road Signs are Beautiful - French | `A_REINSTALLER` | FOMOD à reprendre avec routes / villages / nouveaux mondes stabilisés. | Routes, villages, nouveaux mondes, snow. | Avant LOD / DynDOLOD. | Haute | Ouvert |
| 07.4 - Lands | 321 | Man Those Borders / Road Signs patches | `PATCHES_A_REVOIR` | Patches Lux / Northern Roads / DynDOLOD / Nolvus différés. | Lux, Northern Roads, DynDOLOD, routes. | Patching Lands. | Haute | Ouvert |
| 07.4 - Lands | 323 | WiZkiD Signs | `A_REINSTALLER` | Patches panneaux à reprendre plus tard. | Oakwood, LOTD, villages, snow, routes. | Avant LOD / DynDOLOD. | Haute | Ouvert |
| 07.4 - Lands | 324 | Sepolcri patches | `PATCHES_A_REVOIR` | Main file uniquement, patches différés. | CRF, JK’s Skyrim, Great Cities, Enhanced Solitude, Dawn of Skyrim, DynDOLOD. | Patching Lands / burial sites. | Moyenne | Ouvert |
| 07.4 - Lands | 325 | Setting on Sulphur | `CHOIX_A_REVOIR` | Non installé, à vérifier plus tard. | Bloc parallax / shaders. | Audit parallax / shaders. | Faible | Non installé |
| 07.4 - Lands | 326 | Ryn's Standing Stones patches | `PATCHES_A_REVOIR` | Patches multiples différés. | 3DNPC, Lux, Lux Orbis, Northern Roads, SLaWF, LOD / DynDOLOD, Nolvus. | Patching Lands / Ryn. | Haute | Ouvert |
| 07.4 - Lands | 327 | Pause technique Nexus | `CHOIX_A_REVOIR` | Installations suspendues à cause de l’instabilité Nexus. | Nexus stable. | Reprise étape 328. | Haute | En pause |
| Global | Toutes | LOOT | `CHOIX_A_REVOIR` | LOOT non lancé volontairement. | Base modpack plus avancée. | Phase ordre de chargement / patching. | Haute | Différé |
| Global | Toutes | LOD / TexGen / DynDOLOD | `LOD_DYNDOLOD` | Génération différée tant que paysages / villes / routes / arbres / patches ne sont pas stabilisés. | Villes, routes, arbres, paysages, patches finaux. | Phase LOD finale. | Haute | Différé |
| Global | Toutes | Patches non installés sans mod parent | `PATCHES_A_REVOIR` | Règle de prudence : ne pas installer de patch si parent absent. | Mods parents. | Quand parent installé ou officiellement retenu. | Haute | Règle active |

---

## Vues rapides par type

### `A_REINSTALLER`

- Object Categorization Framework.
- Keyword Patch Collection.
- NPC AI Process Position Fix - NG.
- AOS / ISC / modules audio à logique de réinstallation future.
- Complementary Grass Fixes.
- Skyrim Landscape and Water Fixes.
- Majestic Mountains.
- Happy Little Trees.
- Water for ENB.
- Snowy Surfaces Sound Collision and Aesthetics.
- My Road Signs are Beautiful - French.
- WiZkiD Signs.

### `MASTER_MANQUANT`

- Atlantean Landscape → `Parallax TXST Fixes.esp`.
- Scarecrows of Skyrim - BOS - SOS Patch → `Simplicity of Snow.esp`.

### `DECOCHE_RESERVE`

- Kris's Papyrus Extender.
- MuJointFix - Sexlab Ostim Patch.
- ENB Extender Skyrim.
- Magic College Music.
- Cities of the North - Morthal.

### `PATCHES_A_REVOIR`

- Vel’dun UI patches.
- Mesh Patch for Various Mods non retenus.
- Complementary Grass Fixes patches.
- Skyrim Landscape and Water Fixes patches.
- Lux Orbis / Great Cities / COTN / Environs / village patch collections.
- Villages Nolvus / Schlitzohr patches.
- Player Homes patches.
- Farmhouses patches.
- Jorrvaskr / Dawnguard / Volkihar patches.
- Drinking Fountains / Road Signs / Sepolcri / Ryn’s Standing Stones patches.

### `LOD_DYNDOLOD`

- Tree Billboards - HLT.
- Water / snow / trees / farms / roads / signs / Sepolcri / Ryn / cities.
- Global TexGen / DynDOLOD final.

### `CONFIG_A_REVOIR`

- Scrambled Bugs custom settings.
- powerofthree’s Tweaks custom settings.
- SSE Display Tweaks custom settings.
- SSE Engine Fixes custom settings.
- Papyrus Tweaks NG custom settings.

---

## Règle de maintenance du registre

À chaque pause GitHub, vérifier si de nouvelles entrées doivent être ajoutées ici.

Pour chaque nouvelle dette technique, ajouter au minimum :

- module ;
- étape ;
- élément ;
- type ;
- raison ;
- dépendance ;
- moment de reprise ;
- priorité ;
- statut.

Quand une dette est levée, ne pas supprimer l’entrée : passer son statut à `RESOLU` et ajouter une courte note dans la colonne raison ou dans une section dédiée si nécessaire.

---

## État initial du registre

Première version créée après l’audit de cohérence GitHub effectué à l’étape 327.

**État de référence :**

- Dernière étape validée : `Étape 327 — Pause technique Nexus`
- Dernière étape d’installation validée : `Étape 326 — Ryn’s Standing Stones`
- Module en cours : `07 - CITIES TOWNS INTERIORS LIGHTING`
- Sous-bloc en cours : `07.4 - LANDS`
- Compteur ESP + ESM non-light : `79`
- Reprise prévue : `Étape 328`
