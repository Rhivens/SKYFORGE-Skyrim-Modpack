# SKYFORGE — Changelog de validation — Part 14

## Objet du fichier

Ce fichier synthétise les validations des étapes **435 à 450**.

Période couverte :

- reprise post-snapshot 434 ;
- bloc misc gameplay / confort inspiré de Nolvus Awakening ;
- exclusions volontaires ;
- ajout de `Nether's Follower Framework` ;
- clôture provisoire du bloc `10 - GAMEPLAY COMBAT MAGIC PERKS`.

---

# Résumé des étapes

## Étape 435 — Reprise contrôlée post-snapshot 434

- Aucune installation.
- Vérification du snapshot officiel `SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md`.
- Confirmation que le snapshot 409 est historique uniquement.
- Test menu via SKSE OK.
- Compteur : 108.
- Overwrite vide.

## Étape 436 — Simplest Horses

- Installation de `Simplest Horses - Main File`.
- Patch `Simplest Horses - Animated Whistling Patch` différé à cette étape.
- Test menu OK.
- Compteur : 108.
- Overwrite vide.

## Étape 437 — No Need to Ask... Bounty Is Served

- Installation de `No Need to Ask... Bounty Is Served`.
- Ajout léger de confort autour des primes.
- Test menu OK.
- Compteur : 108.
- Overwrite vide.

## Étape 438 — Mini-bloc misc gameplay léger

Mods installés :

- `State Your Claw`
- `Food For The Thirsty`
- `Switch Camera During Dialogue`

Choix important :

- `Food For The Thirsty` installé en option `Default`.
- Option `Immersive Interactions` différée.

Test menu OK.

Compteur : 108.

## Étape 439 — Dragon Claws Auto-Unlock + Take a Peek

Mods installés :

- `Dragon Claws Auto-Unlock`
- `Take a Peek - New Stealth Mechanic`

Différés :

- `Dragon Claws Auto-Unlock — Script-based Patcher`
- `Take a Peek — Simply Knock Mini Patch`

Présence / placement à confirmer dans le prochain snapshot MO2.

## Étape 440 — Classic Sprinting Redone

- Installation de `Classic Sprinting Redone (Latest version for SE)` version 2.2.
- Version Anniversary Edition non retenue car non adaptée au runtime Skyrim SE 1.5.97.
- `Instantly Skip Dialogue NG` non réinstallé car déjà présent.

## Étape 441 — Taunt Your Enemies + Remote Interactions

Mods installés :

- `Taunt Your Enemies`
- `Remote Interactions`

Correction effectuée :

- `Remote Interactions` seul provoquait un master manquant `Taunt Your Enemies.esp`.
- Ajout de `Taunt Your Enemies`, puis validation du mini-bloc.

## Étape 442 — Vampire Lords Can Fly exclu

- Mod non installé.
- Raison : Fabien ne prévoit pas de jouer vampire.
- Décision cohérente avec la règle SKYFORGE : ne pas installer un système inutile uniquement parce qu'il existe dans Nolvus / Nefaram.
- Compteur inchangé : 108.
- Overwrite vide.

## Étape 443 — Skyrim's Got Talent

- Installation de `Skyrim's Got Talent - Improve As a Bard`.
- Prérequis `BA Bard Songs` déjà présent.
- Patchs optionnels non installés.
- `Flute Animation Fix` différé.
- L'étape 444 indique un compteur courant à 109 après ce bloc.

## Étape 444 — Clôture provisoire du bloc misc gameplay léger

- Aucune installation.
- `Sky Parkour`, `Skyrim's Paraglider`, `Gamepad++` et systèmes apparentés différés à ce moment.
- Pandora pourra être demandé si nécessaire pour les mods de mouvement / comportement, mais ne doit pas être lancé automatiquement.
- Compteur : 109.
- Overwrite vide.

## Étape 445 — SkyParkour v3

Mods installés :

- `SkyParkour v3 - Procedural Parkour and Climbing Framework (SPPF)`
- `SkyParkour v3 - Additional Pandora Patch For CRC32 Cache`
- `SkyParkour v3 - SKYFORGE ini`

Décision :

- fichier `SkyParkourNG.ini` isolé dans un mod séparé SKYFORGE ;
- génération Pandora dédiée à cette étape.

Placement et compteur final à confirmer avec le prochain snapshot MO2.

## Étape 446 — Skyrim's Paraglider exclu

- Mod non installé.
- Raison : Fabien ne l'utilise pas et ne compte pas s'en servir.
- Fichiers associés exclus également.
- Note future ajoutée pour `SL Dirty Deeds Missives 1.4.2`.
- Compteur : 109.
- Overwrite vide.

## Étape 447 — Non documentée dans le lot transmis

- Aucun bloc détaillé `Étape 447` dans le lot reçu.
- `Headhunter - Bounties Redone` apparaît dans la clôture de l'étape 450 comme installé / validé.
- Présence et placement à confirmer avec le prochain snapshot MO2 avant référence anti-doublon définitive.

## Étape 448 — Nether's Follower Framework

Mods installés :

- `Nether's Follower Framework - FOMOD À REVOIR PLUS TARD`
- `Nether's Follower Framework - Settings Loader`

Version :

- NFF 2.8.6b.
- Settings Loader compatible v2.7.9 à v2.8.6.

Choix FOMOD principaux :

- `Followers Avoid Traps` coché.
- `Replace Base Dialogue Scripts` décoché.
- `Install Dummy Scripts` décoché.
- `Interesting NPCs`, `RDO`, `RDO Comments` décochés.
- Options SPID / No Team Magic Damage décochées.

Décisions différées :

- compatibilité Interesting NPCs / RDO ;
- compatibilité SexLab / followers / slavery / prostitution ;
- options SPID / No Team Magic Damage.

## Étape 449 — Animated Whistling + patch Simplest Horses

Mods installés :

- `Animated Whistling`
- `Simplest Horses - Animated Whistling Patch`

Décision :

- le patch `Simplest Horses - Animated Whistling Patch`, précédemment différé à l'étape 436, est désormais installé.

## Étape 450 — Clôture du bloc 7.8 Misc Gameplay

- Aucune installation.
- Clôture provisoire du bloc `10 - GAMEPLAY COMBAT MAGIC PERKS`.
- Nouveau séparateur prévu : `[11 - RACES WEREBEASTS VAMPIRES]`.
- Snapshot MO2 final à créer après réception du nouveau load order complet.

---

# Notes et vigilances ajoutées

## SL Dirty Deeds Missives

À auditer plus tard lors du bloc SexLab / Missives / patches final :

- compatibilité avec `Headhunter - Bounties Redone` ;
- compatibilité avec `Missives` ;
- compatibilité avec les patchs `Headhunter - Missives` ;
- compatibilité Bruma / Solstheim / Wyrmstooth si utilisés ;
- conflits éventuels sur jobs de primes, notes, quêtes radiant, aliases ou récompenses ;
- nécessité éventuelle d'un patch SKYFORGE dédié.

## PB's Silky Skin — SKYFORGE PLAYER SKIN OVERRIDE

Note future créée dans :

- `docs/configuration/08_body_skins_bodyslide_vigilances.md`

Objectif :

- éviter les problèmes de brillance excessive / shiny sur la skin du personnage joueur ;
- prévoir plus tard un mod override dédié en fin de bloc body / outfits / BodySlide.

---

# État après ce changelog

- Dernière étape documentée : **Étape 450 — Clôture du bloc 7.8 Misc Gameplay**
- Bloc `10 - GAMEPLAY COMBAT MAGIC PERKS` : clôturé provisoirement.
- Prochain bloc attendu : **11 - RACES WEREBEASTS VAMPIRES**
- Nouveau snapshot load order à créer après réception du load order complet.
