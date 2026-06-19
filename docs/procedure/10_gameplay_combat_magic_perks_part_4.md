# SKYFORGE — 10 - GAMEPLAY COMBAT MAGIC PERKS — Part 4

## Objet du fichier

Ce fichier poursuit la documentation du séparateur :

**10 - GAMEPLAY COMBAT MAGIC PERKS**

Il couvre les étapes **435 à 450**, centrées sur la reprise post-snapshot 434, le bloc **misc gameplay / confort** inspiré de **Nolvus Awakening**, les décisions d'exclusion, l'intégration de `Nether's Follower Framework`, puis la clôture provisoire du bloc.

> Note de cohérence : le lot transmis ne contient pas de bloc détaillé séparé pour l'étape 447. `Headhunter - Bounties Redone` est toutefois listé comme installé / validé dans la clôture de l'étape 450. Cette présence devra être confirmée dans le prochain snapshot MO2 panneau gauche avant d'en faire une référence anti-doublon définitive.

---

# Étape 435 — Reprise contrôlée post-snapshot 434

## Objectif

Valider la reprise du profil SKYFORGE après l'étape 434 avant tout nouvel ajout de mod.

## Décision prise

Aucune installation effectuée.

L'étape 435 sert de contrôle de reprise et d'audit anti-doublon avant de continuer le module `10 - GAMEPLAY COMBAT MAGIC PERKS`.

## Références utilisées

- `docs/procedure/00_resume_etat_actuel.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md`
- `docs/procedure/10_gameplay_combat_magic_perks_part_3.md`

Le snapshot étape 434 reste la référence courante anti-doublon.

Le snapshot étape 409 reste historique uniquement.

## Vérification anti-doublon

Le snapshot étape 434 confirme que plusieurs candidats gameplay / combat sont déjà présents après `A Closer Look SSE`, notamment :

- `NPC No Block Exhaustion`
- `NPC No Block Exhaustion - MCM`
- `3rd Person Camera Stagger Remover`
- `Block Enchantments`
- `Archery Locational Damage`
- `Bow Charge Plus`
- `No BS AI Projectile Dodge`
- `VioLens - A Killmove Mod SE`
- `VioLens - A Killmove Mod SE - Settings Loader`

Aucun de ces mods ne doit être reproposé comme nouvel ajout.

## Test effectué

Type de test : menu atteint via SKSE depuis MO2.

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL bloquant
- Aucun master manquant
- Plugins cochés normalement
- Aucun crash avant menu
- Overwrite vide

## Impact compteur ESP + ESM non-light

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Pandora non relancé.
- Aucun mod `- FR` activé.
- Aucun mod installé.
- Aucun gros overhaul combat ajouté.

## Verdict final

Étape 435 validée comme reprise contrôlée.

Profil stable conservé depuis l'étape 434.

---

# Étape 436 — Simplest Horses

## Objectif

Ajouter une gestion légère et pratique des chevaux / montures, sans ouvrir de bloc animation ni relancer Pandora.

## Mod installé

- `Simplest Horses - Main File`

## Mod différé

- `Simplest Horses - Animated Whistling Patch`

Raison : patch utile uniquement si `Animated Whistling` est installé plus tard.

Statut : différé dans `PATCHES À REVOIR PLUS TARD` à cette étape.

## Référence utilisée

- Nolvus Awakening, section gameplay / misc gameplay.

## Choix importants

- Fichier installé : `Simplest Horses - Main File`
- Fichier optionnel non installé : `Simplest Horses - Animated Whistling Patch`
- Aucun bloc animation ouvert.
- Pandora non relancé.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement conseillé :

- à proximité du bloc misc gameplay récent ;
- après `A Closer Look SSE`.

## Test effectué

Type de test : menu atteint via SKSE depuis MO2.

Résultat :

- Menu principal atteint.
- Aucun master manquant.
- Aucun message DLL bloquant.
- Plugins cochés normalement.
- Aucun crash avant menu.
- Overwrite vide.

## Impact compteur ESP + ESM non-light

- Avant étape : 108
- Après étape : 108
- Variation : 0

Le mod n'a pas augmenté le compteur non-light.

## Contraintes respectées

- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.
- Aucun ajout animation / comportement effectué.

## Verdict final

Étape 436 validée.

---

# Étape 437 — No Need to Ask... Bounty Is Served

## Objectif

Ajouter un confort léger autour des primes et de leur remise, sans système lourd.

## Mod installé

- `No Need to Ask... Bounty Is Served`

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement :

- après `Simplest Horses - Main File`.

## Test effectué

Type de test : lancement SKSE via MO2 jusqu'au menu principal.

Résultat :

- Menu principal atteint.
- Aucun master manquant.
- Aucun message DLL bloquant.
- Plugins cochés normalement.
- Aucun crash avant menu.
- Overwrite vide.

## Impact compteur ESP + ESM non-light

- Avant étape : 108
- Après étape : 108
- Variation : 0

Le mod n'a pas augmenté le compteur non-light.

## Contraintes respectées

- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.
- Aucun ajout animation / comportement effectué.

## Verdict final

Étape 437 validée.

`No Need to Ask... Bounty Is Served` est installé et stable au menu principal.

---

# Étape 438 — Mini-bloc misc gameplay léger

## Objectif

Ajouter un mini-bloc de confort gameplay léger, sans système lourd, sans relance Pandora, sans BodySlide et sans DynDOLOD.

## Mods installés

- `State Your Claw`
- `Food For The Thirsty`
- `Switch Camera During Dialogue`

## Liens

- State Your Claw : https://www.nexusmods.com/skyrimspecialedition/mods/65150
- Food For The Thirsty : https://www.nexusmods.com/skyrimspecialedition/mods/56330
- Switch Camera During Dialogue : https://www.nexusmods.com/skyrimspecialedition/mods/95269

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Choix FOMOD / options importantes

### Food For The Thirsty

Choix FOMOD :

- `Default`

Options non retenues :

- `Protect-the-children`
- `Immersive Interactions`
- `IE Protect-the-children`

Décision différée :

- `Food For The Thirsty — option FOMOD Immersive Interactions`
  - À noter dans `FOMOD À REVOIR PLUS TARD`.
  - À revoir uniquement si `Immersive Interactions` est installé plus tard.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement :

- à proximité du bloc misc gameplay récent ;
- après `No Need to Ask... Bounty Is Served`.

## Test effectué

Type de test : lancement SKSE via MO2 jusqu'au menu principal.

Résultat :

- Menu principal atteint.
- Aucun master manquant.
- Aucun message DLL bloquant.
- Plugins cochés normalement.
- Aucun crash avant menu.
- Overwrite vide.

## Impact compteur ESP + ESM non-light

- Avant étape : 108
- Après étape : 108
- Variation : 0

Les mods installés n'ont pas augmenté le compteur non-light.

## Contraintes respectées

- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.
- Aucun ajout animation / comportement effectué.
- Option FOMOD liée à `Immersive Interactions` non choisie.

## Verdict final

Étape 438 validée.

---

# Étape 439 — Dragon Claws Auto-Unlock + Take a Peek

## Objectif

Ajouter deux conforts légers liés aux portes, donjons et exploration, sans relancer Pandora, sans BodySlide et sans DynDOLOD.

## Mods installés

- `Dragon Claws Auto-Unlock`
- `Take a Peek - New Stealth Mechanic`

## Liens

- Dragon Claws Auto-Unlock : https://www.nexusmods.com/skyrimspecialedition/mods/47329
- Take a Peek - New Stealth Mechanic : https://www.nexusmods.com/skyrimspecialedition/mods/66908

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Choix FOMOD / options importantes

### Dragon Claws Auto-Unlock

- Fichier principal installé.
- Script-based patcher non installé.

Décision différée :

- `Dragon Claws Auto-Unlock — Script-based Patcher`
  - À noter dans `PATCHES À REVOIR PLUS TARD`.
  - À revoir plus tard si besoin de couvrir des portes à griffes ajoutées par d'autres mods.

### Take a Peek - New Stealth Mechanic

- Fichier principal installé.
- `Simply Knock Mini Patch for Take A Peek` non installé.

Décision différée :

- `Take a Peek — Simply Knock Mini Patch`
  - À noter dans `PATCHES À REVOIR PLUS TARD`.
  - À revoir si `Simply Knock / Simply Knock SKSE` est installé plus tard.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement indiqué :

```text
Switch Camera During Dialogue
Dragon Claws Auto-Unlock
Take a Peek - New Stealth Mechanic
```

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 439 documentée comme ajout validé dans le bloc misc gameplay.

---

# Étape 440 — Classic Sprinting Redone

## Objectif

Ajouter un confort léger de contrôle du sprint, compatible avec Skyrim SE 1.5.97 Best of Both Worlds.

## Mod installé

- `Classic Sprinting Redone (Latest version for SE)`

## Mod non installé

- `Instantly Skip Dialogue NG`

Raison : déjà installé dans le profil SKYFORGE.

## Lien

- Classic Sprinting Redone : https://www.nexusmods.com/skyrimspecialedition/mods/20166

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Choix de fichier

Fichier installé :

- `Classic Sprinting Redone (Latest version for SE)` — version 2.2

Fichier non retenu :

- `Classic Sprinting Redone (Anniversary Edition)` — version 2.3.1

Raison : le fichier Anniversary Edition ne convient pas au runtime Skyrim SE 1.5.97.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement indiqué :

```text
Dragon Claws Auto-Unlock
Take a Peek - New Stealth Mechanic
Classic Sprinting Redone (Latest version for SE)
```

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 440 documentée comme ajout validé dans le bloc misc gameplay.

---

# Étape 441 — Taunt Your Enemies + Remote Interactions

## Objectif

Ajouter un mini-bloc d'interactions à distance et de provocation légère, issu du bloc misc gameplay, sans ouvrir de génération Pandora ni ajouter de système lourd.

## Mods installés

- `Taunt Your Enemies`
- `Remote Interactions`

## Liens

- Taunt Your Enemies : https://www.nexusmods.com/skyrimspecialedition/mods/72023
- Remote Interactions : https://www.nexusmods.com/skyrimspecialedition/mods/89676

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Correction effectuée

La proposition initiale prévoyait `Remote Interactions` seul.

MO2 a signalé un master manquant :

- `Taunt Your Enemies.esp`

Décision corrective :

- installation de `Taunt Your Enemies`
- conservation de `Remote Interactions`
- validation du mini-bloc complet après test

## Choix importants

- Aucun patch optionnel installé.
- Aucun mod `- FR` activé.
- Aucun générateur d'animations lancé.

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement indiqué :

```text
Classic Sprinting Redone (Latest version for SE)
Taunt Your Enemies
Remote Interactions
NPC No Block Exhaustion
```

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 441 documentée comme ajout validé après correction du master manquant.

---

# Étape 442 — Vampire Lords Can Fly exclu

## Objectif

Évaluer l'intérêt de `Vampire Lords Can Fly` dans le bloc misc gameplay.

## Décision prise

Mod non installé.

## Mod concerné

- `Vampire Lords Can Fly`

## Lien

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/46023

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Raison de l'exclusion

Fabien indique qu'il ne jouera jamais de personnage vampire.

Le mod est donc jugé non prioritaire et inutile pour l'expérience SKYFORGE prévue.

## Test effectué

Aucun test nécessaire.

## Impact compteur ESP + ESM non-light

- Avant étape : 108
- Après étape : 108
- Variation : 0

## État Overwrite

- Overwrite inchangé : vide

## Contraintes respectées

- Aucun mod installé.
- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.

## Verdict final

Étape 442 validée comme décision d'exclusion.

`Vampire Lords Can Fly` ne sera pas intégré à SKYFORGE sauf décision future contraire.

---

# Étape 443 — Skyrim's Got Talent

## Objectif

Ajouter un système bardique léger permettant au joueur de jouer des instruments, de progresser comme barde et d'obtenir des réactions des PNJ.

## Mod installé

- `Skyrim's Got Talent - Improve As a Bard`

## Lien

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/50357

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Prérequis vérifié

Le mod demande :

- `BA Bard Songs`

État SKYFORGE :

- `BA Bard Songs` déjà présent dans le profil.
- Plugin associé attendu : `BA_BardSongs_AIO.esp`.

## Choix FOMOD / options importantes

Fichier principal installé :

- `Skyrim's Got Talent - Improve As a Bard`

Non installés :

- patchs optionnels compagnons ;
- patch Bruma ;
- patchs affichage / équipement ;
- `Flute Animation Fix`.

Décisions différées :

```text
- Skyrim's Got Talent — Flute Animation Fix
  - Non installé à l'étape 443.
  - À revoir seulement si le placement de la flûte est problématique en jeu avec XPMSSE.

- Skyrim's Got Talent — Bruma Mini Patch / followers reaction patches
  - Non installés à l'étape 443.
  - À revoir plus tard selon les compagnons, Bruma et le bloc patches final.
```

## Test / compteur

Le fichier transmis indique que l'étape 444 commence avec un compteur à 109. L'étape 443 est donc considérée comme validée avant clôture provisoire du bloc, avec compteur courant 109.

## Verdict final

Étape 443 validée.

---

# Étape 444 — Clôture provisoire du bloc misc gameplay léger

## Objectif

Clôturer provisoirement le mini-bloc misc gameplay léger validé jusqu'à l'étape 443 avant de basculer vers des systèmes plus sensibles de mouvement, animations ou comportement.

## Décision prise

Aucune installation effectuée.

`Sky Parkour`, `Skyrim's Paraglider`, `Gamepad++` et les systèmes apparentés ne sont pas installés à cette étape.

## Mods différés

- `Sky Parkour`
- `Sky Parkour - Nolvus Settings`
- `Skyrim's Paraglider`
- `Skyrim's Paraglider - Fix`
- `Skyrim's Paraglider - Vampire And Werewolf Patch`
- `Gamepad++`
- `Complete Controller Setup`

## Raison du report

Ces mods ouvrent des sujets plus sensibles :

- mouvements avancés ;
- animations / comportements ;
- compatibilité Pandora ;
- patchs spécifiques ;
- configuration manette éventuelle.

Ils seront traités dans un bloc dédié si Fabien décide de les intégrer.

## Note Pandora

Fabien indique que la génération Pandora est très rapide sur son PC.

Décision méthodologique :

- Pandora pourra être demandé si nécessaire pour un mod d'animation, comportement ou mouvement.
- Pandora ne sera pas lancé automatiquement.
- Après toute génération Pandora, un test SKSE / menu principal sera requis.

## Test effectué

Aucun test nécessaire.

Aucune installation effectuée.

## Impact compteur ESP + ESM non-light

- Avant étape : 109
- Après étape : 109
- Variation : 0

## État Overwrite

- Overwrite inchangé : vide

## Contraintes respectées

- Aucun mod installé.
- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.

## Verdict final

Étape 444 validée comme clôture provisoire du bloc misc gameplay léger.

---

# Étape 445 — SkyParkour v3

## Objectif

Installer et valider `SkyParkour v3` comme framework de parkour / escalade procédurale, avec génération Pandora dédiée.

## Mods installés

- `SkyParkour v3 - Procedural Parkour and Climbing Framework (SPPF)`
- `SkyParkour v3 - Additional Pandora Patch For CRC32 Cache`
- `SkyParkour v3 - SKYFORGE ini`

## Lien

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/132292

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.
- Information complémentaire Fabien : mod déjà testé auparavant en version V3 sans problème.

## Prérequis vérifiés

Déjà présents dans SKYFORGE :

- `Animation Motion Revolution`
- `Pandora Behaviour Engine v4.3.1-beta`

## Choix importants

Fichiers installés :

- fichier principal `SkyParkour v3`
- patch Pandora / CRC32 Cache
- fichier INI généré isolé dans un mod séparé SKYFORGE

Décision de gestion INI :

- le fichier généré `SkyParkourNG.ini` n'a pas été laissé dans `Overwrite`
- création d'un mod séparé :
  - `SkyParkour v3 - SKYFORGE ini`

## Placement MO2

Séparateur :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

Placement validé :

```text
Taunt Your Enemies
Remote Interactions
SkyParkour v3 - Procedural Parkour and Climbing Framework (SPPF)
SkyParkour v3 - Additional Pandora Patch For CRC32 Cache
SkyParkour v3 - SKYFORGE ini
NPC No Block Exhaustion
NPC No Block Exhaustion - MCM
3rd Person Camera Stagger Remover
```

## Pandora

Contrairement aux étapes précédentes, cette étape utilise une génération Pandora dédiée.

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 445 documentée comme ajout validé.

---

# Étape 446 — Skyrim's Paraglider exclu

## Objectif

Évaluer l'intérêt de `Skyrim's Paraglider` pour SKYFORGE avant installation.

## Décision prise

Mod non installé.

## Mod concerné

- `Skyrim's Paraglider`

## Lien

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/53256

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.
- Présent aussi dans Nefaram selon retour Fabien.

## Raison de l'exclusion

Fabien indique qu'il ne s'est jamais servi de `Skyrim's Paraglider` et ne compte pas s'en servir.

Le mod est donc jugé non utile pour l'expérience SKYFORGE prévue.

Décision cohérente avec la règle SKYFORGE :

- stabilité avant quantité ;
- ne pas installer un mod uniquement parce qu'il existe dans Nolvus Awakening ou Nefaram ;
- éviter les systèmes inutilisés, surtout lorsqu'ils touchent aux mouvements, animations, DLL, fixes et patchs.

## Mods / fichiers associés non installés

- `Skyrim's Paraglider`
- `Skyrim's Paraglider - Fix`
- `Skyrim's Paraglider - Vampire And Werewolf Patch`
- `Skyrim's Paraglider Anniversary Edition Update`

## Test effectué

Aucun test nécessaire.

Aucune installation effectuée.

## Impact compteur ESP + ESM non-light

- Avant étape : 109
- Après étape : 109
- Variation : 0

## État Overwrite

- Overwrite inchangé : vide

## Contraintes respectées

- Aucun mod installé.
- LOOT non lancé.
- Pandora non relancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Aucun mod `- FR` activé.
- Aucun système de mouvement complexe ajouté.

## Verdict final

Étape 446 validée comme décision d'exclusion.

`Skyrim's Paraglider` ne sera pas intégré à SKYFORGE sauf décision future contraire.

## Note future — Compatibilité SL Dirty Deeds Missives

À prendre en compte lors du futur bloc SexLab et du bloc patches final :

- `SL Dirty Deeds Missives 1.4.2`
- Source : LoversLab
- Statut : demande spécifique SKYFORGE de Fabien
- Référence : externe, non issue de Nolvus Awakening ni de Nefaram

Points à vérifier plus tard :

- compatibilité avec `Headhunter - Bounties Redone`
- compatibilité avec `Missives`
- compatibilité avec les patchs `Headhunter - Missives`
- compatibilité avec les patchs Bruma / Solstheim / Wyrmstooth si utilisés
- conflits éventuels sur les jobs de primes, notes, quêtes radiant, aliases ou récompenses
- nécessité ou non d'un patch SKYFORGE dédié

Décision actuelle :

- ne pas installer maintenant ;
- ne pas patcher maintenant ;
- noter pour audit obligatoire lors du bloc SexLab / Missives / patches final.

---

# Étape 447 — Non documentée dans le lot transmis

## Statut

Le lot transmis ne contient pas de bloc détaillé `Étape 447`.

## Point de vigilance

`Headhunter - Bounties Redone` apparaît dans la liste des mods installés / validés à l'étape 450.

## Décision documentaire provisoire

- Ne pas inventer de détail d'installation absent du lot transmis.
- Confirmer la présence exacte et le placement de `Headhunter - Bounties Redone` avec le prochain snapshot MO2.
- Conserver les patchs / FOMOD conditionnels `Headhunter - Bounties Redone` en différé tant qu'ils ne sont pas explicitement validés.

---

# Étape 448 — Nether's Follower Framework

## Objectif

Installer `Nether's Follower Framework` comme framework principal de gestion des compagnons pour SKYFORGE, en suivant la logique Nolvus Awakening plutôt que l'ancienne version Nefaram.

## Mods installés

- `Nether's Follower Framework - FOMOD À REVOIR PLUS TARD`
- `Nether's Follower Framework - Settings Loader`

## Lien

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/55653

## Référence utilisée

- Référence principale : Nolvus Awakening.
- Nefaram utilise aussi NFF, mais avec une version plus ancienne.
- Décision SKYFORGE : utiliser la version Nolvus / Nexus récente, jugée plus adaptée et performante.

## Version installée

- `Nether's Follower Framework` : 2.8.6b
- `Nether's Follower Framework - Settings Loader` : compatible v2.7.9 à v2.8.6

## Choix FOMOD / options importantes

### Core Options

Choix effectués :

- `Followers Avoid Traps` : coché
- `Replace Base Dialogue Scripts` : décoché
- `Follower Leveling BAT File` : décoché
- `Follower Class BAT Files` : décoché
- `Source Scripts (SSE)` : décoché
- `Source Scripts (LE)` : décoché

### Removed Scripts

Choix effectué :

- `Install Dummy Scripts` : décoché

Raison : installation neuve SKYFORGE, pas de sauvegarde existante à nettoyer.

### Core 3rd Party Support

Choix effectués :

- `Interesting NPCs` : décoché
- `Relationship Dialogue Overhaul (RDO)` : décoché
- `RDO Comments` : décoché

Décision différée :

- `Nether's Follower Framework — FOMOD Interesting NPCs / RDO`
  - Choix étape 448 : non cochés.
  - Interesting NPCs non installé à cette étape.
  - RDO non installé à cette étape.
  - À revoir plus tard lors du bloc Interesting NPCs / SexLab / followers.
  - Vérifier compatibilité avec les patchs SexLab pour Interesting NPCs.

### Spell Perk Item Distributor Options

Choix effectués :

- `Friendly Fire` : décoché
- `Skill Boosts` : décoché
- `Spell Magnitude Mod` : décoché

### No Team Magic Damage SSE

Choix effectués :

- `ESP for Skyrim Special Edition` : décoché
- `Apocalypse for SSE` : décoché
- `Elemental Destruction Magic for SSE` : décoché

Décision différée :

- `Nether's Follower Framework — FOMOD SPID / No Team Magic Damage`
  - Choix étape 448 : tout décoché.
  - Friendly Fire non installé.
  - Skill Boosts non installé.
  - Spell Magnitude Mod non installé.
  - No Team Magic Damage SSE non installé.
  - Patchs Apocalypse / Elemental Destruction non installés.
  - À revoir plus tard selon équilibrage followers, magie, SexLab / followers et bloc patches final.

## Note future SexLab / followers

À auditer plus tard lors du bloc SexLab / followers / prostitution / slavery :

- compatibilité avec les systèmes SexLab ;
- compatibilité avec prostitution / slavery ;
- compatibilité avec les followers forcés ;
- compatibilité avec les packages IA et dialogues ;
- interactions éventuelles avec les systèmes adultes différés.

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 448 documentée comme installation validée de NFF, avec FOMOD à revoir plus tard pour les options conditionnelles.

---

# Étape 449 — Animated Whistling + patch Simplest Horses

## Objectif

Ajouter l'animation de sifflement et réactiver le patch précédemment différé pour `Simplest Horses`, maintenant que les prérequis utiles sont en place.

## Mods installés

- `Animated Whistling`
- `Simplest Horses - Animated Whistling Patch`

## Liens

- Animated Whistling : https://www.nexusmods.com/skyrimspecialedition/mods/76733
- Simplest Horses : https://www.nexusmods.com/skyrimspecialedition/mods/54225

## Référence utilisée

- Nolvus Awakening, section `7.8 Misc Gameplay`.

## Prérequis / contexte

Déjà présents dans SKYFORGE :

- `Simplest Horses`
- `Nether's Follower Framework`
- `Pandora Behaviour Engine v4.3.1-beta`
- `Mfg Fix`

## Choix importants

Fichiers installés :

- fichier principal `Animated Whistling`
- patch `Simplest Horses - Animated Whistling Patch`

Décision mise à jour :

- `Simplest Horses — Animated Whistling Patch`
  - Ancien statut : `PATCHES À REVOIR PLUS TARD`.
  - Nouveau statut étape 449 : installé.

## Test / compteur

Le fichier transmis ne contient pas le bloc final complet de test pour cette étape. À confirmer avec le prochain snapshot MO2.

## Verdict final

Étape 449 documentée comme ajout validé.

---

# Étape 450 — Clôture du bloc 7.8 Misc Gameplay

## Objectif

Clôturer proprement le bloc misc gameplay avant de passer au bloc suivant consacré aux races, werebeasts et vampires.

## Décision prise

Aucune installation effectuée.

Le bloc `10 - GAMEPLAY COMBAT MAGIC PERKS` est considéré comme clôturé provisoirement après l'étape 449.

## Bloc clôturé

Séparateur actuel :

- `10 - GAMEPLAY COMBAT MAGIC PERKS`

## Statut du bloc

Installés / validés :

- `Nether's Follower Framework`
- `A Closer Look SSE`
- `Headhunter - Bounties Redone` — présence à confirmer dans le prochain snapshot MO2, faute de bloc détaillé étape 447 dans le lot transmis.
- `Simplest Horses`
- `Animated Whistling`
- `Simplest Horses - Animated Whistling Patch`
- `No Need to Ask... Bounty Is Served`
- `State Your Claw`
- `Food For The Thirsty`
- `Skyrim's Got Talent - Improve As a Bard`
- `Taunt Your Enemies`
- `Remote Interactions`
- `Switch Camera During Dialogue`
- `SkyParkour v3`
- `Take a Peek - New Stealth Mechanic`
- `Dragon Claws Auto-Unlock`
- `Classic Sprinting Redone`

Déjà présents avant reprise / confirmés dans le bloc :

- `No Furniture Camera`
- `Pick Up Radius`
- `Instantly Skip Dialogue NG`
- `Disable Follower Collision`
- `I'm Walkin' Here`
- `I'm Talkin' Here`
- `Simple Offence Suppression`
- `Smart Optimal Salves`

Exclus :

- `Vampire Lords Can Fly`
- `Skyrim's Paraglider`

Différés / à revoir plus tard :

- `Dragon Claws Auto-Unlock — Script-based Patcher`
- `Take a Peek — Simply Knock Mini Patch`
- `Food For The Thirsty — option FOMOD Immersive Interactions`
- `Skyrim's Got Talent — patchs et fixes`
- `Headhunter - Bounties Redone — FOMOD & patchs conditionnels`
- `Nether's Follower Framework — FOMOD Interesting NPCs / RDO / SexLab followers`
- `Nether's Follower Framework — compatibilités SexLab / followers / slavery / prostitution`
- compatibilité future `SL Dirty Deeds Missives 1.4.2`

## Nouveau séparateur prévu

Créer / ouvrir ensuite un nouveau séparateur MO2 :

```text
[11 - RACES WEREBEASTS VAMPIRES]
```

## Impact compteur / snapshot

Le compteur final après l'étape 450 et le placement définitif des mods doivent être confirmés par le prochain snapshot MO2 panneau gauche.

## Verdict final

Étape 450 documentée comme clôture provisoire du bloc `7.8 Misc Gameplay` / `10 - GAMEPLAY COMBAT MAGIC PERKS`.

La suite attendue se fera dans le séparateur :

```text
[11 - RACES WEREBEASTS VAMPIRES]
```

---

# Contraintes globales respectées sur les étapes 435 à 450

- LOOT non lancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Mods `- FR` non activés.
- Pandora non relancé automatiquement.
- Pandora utilisé uniquement pour `SkyParkour v3`, étape nécessitant une génération comportementale dédiée.
- Les patchs conditionnels restent différés.
- Les systèmes inutiles pour l'expérience SKYFORGE prévue ne sont pas installés par principe de prudence.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 450 — Clôture du bloc 7.8 Misc Gameplay**
- Prochain bloc attendu : **11 - RACES WEREBEASTS VAMPIRES**
- Snapshot MO2 final à créer après réception du nouveau load order complet.
