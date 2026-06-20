# Module 11.1 — Followers, NPCs & dialogues — partie 1

Ce fichier documente les étapes 459 à 480 du projet SKYFORGE.

## Statut du bloc

- **Bloc :** `[11.1 - FOLLOWERS NPCS DIALOGUES]`
- **Statut :** en cours après étape 480
- **Compteur final documenté :** 119 ESP + ESM non-light
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé
- **Mods `- FR` :** non activés

## Méthode

- Les mods de dialogues NPC sont regroupés dans `[11.1 - FOLLOWERS NPCS DIALOGUES]`.
- Les mods de contenu restauré ou de gestion NPC peuvent être placés hors du pur bloc dialogue si leur portée dépasse les dialogues.
- Les patchs dépendants de mods absents sont installés seulement si leurs masters sont présents.
- Les FOMOD marqués `À REVOIR PLUS TARD` devront être réaudités lors des blocs concernés.

---

# Étape 459 — Ouverture du bloc 11.1 — Pack Lines Expansion

## Statut

Validée.

## Mods installés

- `Bandit Lines Expansion` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/63733
- `Civil War Lines Expansion` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/77566
- `Forsworn and Thalmor Lines Expansion` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/80188
- `Vampire Lines Expansion` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/83484

## Options différées

- Bandit Lines Expansion : `Werebeasts Dont Talk`, `Dark Elf Voices For Bandits`.
- Vampire Lines Expansion : `Orc Addon`.

## Décision

Pack installé en version sobre. `Vampire Lines Expansion` respecte la règle vampire SKYFORGE car il concerne les dialogues des NPC vampires.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 460 — Brawl Lines Expansion and Fixes

## Statut

Validée.

## Mod installé

- `Brawl Lines Expansion and Fixes` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/94070

## Mod différé

- `Dremora Lines Expansion` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/100562

Raison : demande `Additional Dremora Faces`, touche aux Dremora, visages / records NPC et peut nécessiter un audit séparé.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 461 — Pack NPCs React aux actes magiques

## Statut

Validée.

## Mods installés

- `NPCs React To Necromancy (And More)` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/70428
- `NPCs React To Invisibility` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/91480
- `Bow of Shadows (CC) - Invisibility Patch`
- `NPCs React To Frenzy` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/107492

## Option différée

- Patch `Apothecary's Ethereal Potions`, non nécessaire à ce stade.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 462 — Carriages and Stables Dialogue Bundle

## Statut

Validée.

## Mod installé

- `Carriages and Stables Dialogue Bundle` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/79297

## Options différées

- `Carriage and Ferry Travel Overhaul Patch`
- `Wild Horses - Dialogues`, si proposé séparément

## Note CFTO

Fabien confirme que CFTO sera installé plus tard. Le patch CFTO sera revu au moment du bloc transport ou lors d'un audit patches transport.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 463 — Pack petits conforts dialogue NPC

## Statut

Validée.

## Mods installés

- `Show NPC Disposition Relationship Rank` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/99905
- `Dialogue Window Auto Close Exit Begone` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/103140
- `Scared of Shootings - NPCs react to aiming bows` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/105622

## Option non installée

- Variante `Show NPC Disposition Relationship Rank Edit`.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 464 — Pack Dialogue Expansion lieux / caravanes

## Statut

Validée.

## Mods installés

- `Dialogue Expansion - Windhelm` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/112415
- `Dialogue Expansion - Shor's Stone` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/97337
- `Dialogue Expansion - Khajiit Caravans` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/87007

## Différés

- `Immersive Dialogue Expansion - Stormcloaks`, ancienne référence Nexus signalée obsolete / hidden.
- `Immersive Dialogue Expansion - Whiterun`, à auditer séparément.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugins cochés, Overwrite vide.

Compteur : 111.

---

# Étape 465 — Annulation propre / audit Immersive Dialogue Expansion - Whiterun

## Statut

Validée.

## Mod non installé

- `Immersive Dialogue Expansion - Whiterun` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/149724

## Raison

Le mod est caché sur Nexus et signalé comme obsolète. L'auteur propose `Follower Dialogue Expansion - Olfina Gray-Mane` comme remplacement ciblé.

## Décisions

- Ne pas installer `Immersive Dialogue Expansion - Whiterun`.
- Ne pas chercher d'ancienne archive.
- Ne pas forcer une version obsolète.
- Ne pas installer automatiquement `Follower Dialogue Expansion - Olfina Gray-Mane`.
- `Follower Dialogue Expansion - Olfina Gray-Mane` est un candidat à auditer plus tard.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 466 — Pack micro-fixes roleplay gardes / prisonniers / intendants

## Statut

Validée.

## Mods installés

- `Neutral Whiterun Guards` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/70197
- `Truly Neutral Prisoners` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/73873
- `More Sensible Quartermasters` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/73887

## Choix

- `More Sensible Quartermasters` : version complète installée.
- Version Lite non installée car elle n'inclut pas les edits de stock.

## Différés

- `Guard Dialogue Overhaul SE`
- `Relationship Dialogue Overhaul`

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugins cochés, Overwrite vide.

Compteur : 111.

---

# Étape 467 — Robber's Gorge Fixes

## Statut

Validée.

## Mod installé

- `Robber's Gorge Fixes` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/81495

## Choix FOMOD

- Patch sélectionné : `None`.
- Patchs non installés : OBIS, Requiem.

## Mod différé / probablement exclu

- `Longer Jailtime` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/52682

Raison : intérêt limité pour SKYFORGE et risque d'interaction négative avec les systèmes de survie et de prison futurs.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché, Overwrite vide.

Compteur : 111.

---

# Étape 468 — Guard Dialogue Overhaul SE + Guard Dialogue Overhaul MCM

## Statut

Validée.

## Mods installés

- `Guard Dialogue Overhaul SE` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/22075
- `Guard Dialogue Overhaul MCM` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/50853

## Choix

- GDO version ESP installée.
- GDO version ESL non installée.
- MCM : choix `ESP GDO` + `Only the MCM`.
- `MCM and tweaked conditions` non retenu.

## Décision

SKYFORGE retient GDO en version ESP par prudence avec Skyrim SE 1.5.97 et compatibilité patches historiques.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugins cochés, Overwrite vide.

Compteur : 111.

---

# Étape 469 — GuardsTalk

## Statut

Validée.

## Mod installé

- `GuardsTalk` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/104494

## Rôle

Distribuer via KID des mots-clés GDO à des armures et armes moddés afin d'améliorer les réactions des gardes à l'équipement.

## Différés

- `More Dialogue Options`
- `Relationship Dialogue Overhaul`
- `Extended Guard Dialogue`

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché si présent, Overwrite vide.

Compteur : 112.

---

# Étape 470 — More Dialogue Options

## Statut

Validée.

## Mod installé

- `More Dialogue Options - FOMOD À REVOIR PLUS TARD` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/28905

## Choix FOMOD

Patches installés :

- Guard Dialogue Overhaul - ESP version
- Riverwood Trader Is A Mess

Patches non installés :

- Guard Dialogue Overhaul - ESL version
- Aela Restored - Companions Tweaks
- At Your Own Pace - Thieves Guild
- How Hard Is This Persuasion Check
- Immersive Citizens
- Immersive World Encounters
- Silence is Golden
- Thieves Guild For Good Guys
- Thieves Guild Requirements
- female Cicero
- autres patches pour mods non présents ou non validés

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugins cochés, Overwrite vide.

Compteur : 112.

---

# Étape 471 — Misc Dialogue Edits

## Statut

Validée.

## Mod installé

- `Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD` — Source Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/28904

## Choix FOMOD

Patch installé :

- Skyrim Unbound Reborn

Patchs non installés :

- Alternate Perspective
- Alternate Start - Live Another Life
- At Your Own Pace - Misc
- Bring Meeko to Lod
- Economy Overhaul and Speechcraft Improvements
- Narrative Gameplay Consistent Dialogue Tweaks
- Save the Icerunner
- Sensible Greetings
- Sofia

## Correction importante

SKYFORGE utilise Skyrim Unbound Reborn, pas Alternate Perspective.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché, Overwrite vide.

Compteur : 112.

---

# Étape 472 — Relationship Dialogue Overhaul - RDO SE

## Statut

Validée.

## Mod installé

- `Relationship Dialogue Overhaul - RDO SE` — Source Nefaram + Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/1187

## Différés

- `RDO - CRF and USSEP Patches Final`, à revoir rapidement.
- `Relationship Dialogue Overhaul - Update and MCM`.
- `Relationship Dialogue Overhaul - Update and MCM - Settings Loader`.
- Patches AFT / iAFT / EFF, non installés.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché, Overwrite vide.

Compteur : 113.

---

# Étape 473 — Cutting Room Floor + patch RDO CRF / USSEP

## Statut

Validée.

## Diagnostic initial

- Master manquant : `Cutting Room Floor.esp`
- Requis par : `RDO - CRF + USSEP Patch.esp`

## Mod installé

- `Cutting Room Floor - FOMOD À REVOIR PLUS TARD` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/276

## Choix FOMOD

Patchs non installés :

- RS Children Overhaul
- Skyrim Bridges

## Patch activé

- `RDO - CRF + USSEP Patch.esp`

## Test

Menu principal OK, aucun message DLL, aucun master manquant, `Cutting Room Floor.esp` et `RDO - CRF + USSEP Patch.esp` cochés, Overwrite vide.

Compteur : 116.

---

# Étape 474 — Audit / stabilisation RDO Update and MCM

## Statut

Validée.

## Actions réalisées

- Aucun mod installé.
- Aucun plugin ajouté.
- RDO base conservé.
- Cutting Room Floor conservé et coché.
- RDO - CRF + USSEP Patch conservé et coché.
- Relationship Dialogue Overhaul - Update and MCM non installé.
- Settings Loader RDO non installé.

## Route stable retenue

```txt
Relationship Dialogue Overhaul - RDO SE
Cutting Room Floor
RDO - CRF + USSEP Patch
```

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 116.

---

# Étape 475 — AI Overhaul - Relationship Dialogue Overhaul Patch différé

## Statut

Validée comme correction / différé.

## Diagnostic

Le patch testé demande `AI Overhaul.esp`, absent à cette étape.

## Patch testé puis désactivé

- `AI Overhaul - Relationship Dialogue Overhaul Patch` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/35823

## Décisions

- Patch décoché.
- AI Overhaul sera traité juste après.
- Patch à réactiver après validation de `AI Overhaul.esp`.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, patch décoché, Overwrite vide.

Compteur : 116.

---

# Étape 476 — AI Overhaul SSE + patch RDO

## Statut

Validée.

## Mod installé

- `AI Overhaul SSE - FOMOD À REVOIR PLUS TARD` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/21654
- Version installée : 1.9.5

## Choix FOMOD

Installés :

- Main File 1.9.5
- AIO Fishing

Non installé :

- AIO Scripted Beta

## Patch réactivé

- `AI Overhaul - Relationship Dialogue Overhaul Patch`

## Décisions

- `AI Overhaul.esp` coché.
- Patch RDO coché.
- AI Overhaul - RDO Updated Patch non installé, car SKYFORGE n'utilise pas RDO Update and MCM.
- Patch Cutting Room Floor différé à cette étape.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, AI Overhaul et patch RDO cochés, Overwrite vide.

Compteur : 117.

---

# Étape 477 — AI Overhaul - Cutting Room Floor Patch

## Statut

Validée.

## Patch installé

- `AI Overhaul - Cutting Room Floor Patch` — Source Nolvus Awakening + Nefaram — https://www.nexusmods.com/skyrimspecialedition/mods/35823

## Masters requis validés

- `AI Overhaul.esp`
- `Cutting Room Floor.esp`

## Décisions

- Patch AI Overhaul - Cutting Room Floor conservé et coché.
- Patch AI Overhaul - Relationship Dialogue Overhaul reste coché.
- Patch AI Overhaul - RDO Updated Patch non installé.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, AI Overhaul / CRF / patch cochés, Overwrite vide.

Compteur : 117.

---

# Étape 478 — Run For Your Lives

## Statut

Validée.

## Mod installé

- `Run For Your Lives` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/2272

## Rôle

Faire fuir les citoyens vers un intérieur pendant les attaques de dragon ou de vampire afin d'éviter qu'ils soient tués inutilement.

## Décision

Mod conservé. Utile pour protéger les NPC civils sans les rendre essentiels. Cohérent avec AI Overhaul SSE.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché, Overwrite vide.

Compteur : 118.

---

# Étape 479 — Realistic Conversations

## Statut

Validée.

## Mod installé

- `Realistic Conversations` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/1717

## Rôle

Rendre les conversations NPC plus naturelles, réduire les pauses trop longues et améliorer la logique sociale des échanges.

## Décision

Mod conservé. Cohérent avec Relationship Dialogue Overhaul.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, plugin coché, Overwrite vide.

Compteur : 119.

---

# Étape 480 — SPID NPC Trap Safety / audit doublon NPC AI Process Position Fix

## Statut

Validée.

## Mod déjà présent

- `NPC AI Process Position Fix - NG` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/69326
- Statut : déjà installé dans `[02 - BUG FIXES & ENGINE PATCHES]`
- Décision : ne pas réinstaller / ne pas déplacer maintenant.

## Mod installé

- `SPID NPC Trap Safety` — Source Nolvus Awakening — https://www.nexusmods.com/skyrimspecialedition/mods/55321

## Décisions

- Aucun doublon installé.
- SPID NPC Trap Safety conservé.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 119.

## Résultat

Étape 480 validée.

Prochaine étape : 481.
