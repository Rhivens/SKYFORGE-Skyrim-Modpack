# SKYFORGE — 10 - GAMEPLAY COMBAT MAGIC PERKS — Part 3

## Objet du fichier

Ce fichier poursuit la documentation du séparateur :

**10 - GAMEPLAY COMBAT MAGIC PERKS**

Il couvre les étapes **426 à 434**, centrées sur :

- la validation gameplay ciblée post-ajouts combat / archerie ;
- l’ajout de modules légers issus de **Nolvus Awakening** ;
- des améliorations de comportement NPC, potions, dialogues, collision, caméra et confort de jeu ;
- la poursuite prudente sans relancer LOOT, DynDOLOD, BodySlide ou Pandora.

---

# Étape 426 — Test gameplay ciblé post-ajouts combat / archerie

## Objectif

Valider en jeu les ajouts combat / archerie installés après l’étape 415, avant de continuer l’empilement de mods.

## Type d’étape

- Test en jeu.
- Aucun nouveau mod installé.

## Mods / systèmes couverts

- `Wait Your Turn`
- `NPCs Take Cover`
- `NPC No Block Exhaustion`
- `Block Enchantments`
- `Archery Locational Damage`
- `Bow Charge Plus`
- `VioLens`
- `No BS AI Projectile Dodge`
- `No Spinning Death Animation Merged LITE`
- `Valhalla Combat` / `Precision` / `TDM` / `TK Dodge` déjà présents

## Test effectué

Durée : **15 minutes**

Résultat :

- Aucun CTD
- Aucun reboot Windows
- Combat mains nues : OK
- Combat épée + bouclier : OK
- Combat arc + flèches : OK
- Pas de T-Pose
- Pas de A-Pose
- Tous les menus MCM accessibles
- Test in-world après sortie de la cellule Unbound : OK
- Arrivée à Riverwood : OK
- PNJ : OK
- Inventaire : OK
- Dialogues PNJ : OK
- Cellule Giant Inn de Riverwood : OK
- Cellule du marchand de Rivebois : OK
- Overwrite vide

## Anomalie non bloquante

Dans la cellule Giant Inn de Riverwood :

- objets flottants à l’emplacement de l’ancien comptoir.

Décision :

- anomalie graphique / placement intérieur à corriger plus tard ;
- non bloquant pour le module combat.

## Décision

Étape 426 validée.

## Contraintes respectées

- Aucun nouveau mod installé.
- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.

---

# Étape 427 — NPCs Use Potions

## Objectif

Ajouter un module léger de comportement combat NPC issu de Nolvus Awakening, permettant aux PNJ d’utiliser des potions en combat.

## Mods installés

- `NPCs Use Potions`
- `NPCs Use Potions - SKYFORGE Config`

## Origine

- Nolvus Awakening

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/67489

## Choix FOMOD

Installation prudente limitée au profil actuel :

- `Base Game` : coché
- `Poison Dosage Preset` : coché
- `Reduced Invisibility` : décoché
- New Lands / Dungeon Mods / Overland / Creature / Followers : décochés

Note :

- FOMOD à revoir plus tard si ajout officiel de nouveaux mondes, quêtes, donjons ou créatures compatibles.

## Configuration générée

Un fichier INI SKSE a été généré dans Overwrite.

Action effectuée :

- création du mod `NPCs Use Potions - SKYFORGE Config` ;
- placement sous `NPCs Use Potions` ;
- Overwrite vidé.

## Incident non reproductible

Lors du premier lancement :

- blocage avant arrivée au menu ;
- écran noir.

Après relance :

- incident non reproduit ;
- menu principal atteint normalement.

Décision :

- incident noté comme vigilance mineure ;
- non bloquant pour SKYFORGE à ce stade.

## Test final effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 427 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 428 — Smart Optimal Salves / Optimal Potion Hotkey

## Objectif

Ajouter un petit module de hotkeys potion joueur issu de Nolvus Awakening, sans configurer les touches maintenant.

## Mods installés

- `Smart Optimal Salves - Optimal Potion Hotkey MCM`
- `Optimal Potion Hotkey MCM - Settings Loader`

## Origine

- Nolvus Awakening

## Sources

- Smart Optimal Salves : https://www.nexusmods.com/skyrimspecialedition/mods/42402
- Settings Loader : https://www.nexusmods.com/skyrimspecialedition/mods/59318

## Rôle

Ajoute des raccourcis MCM pour utiliser automatiquement la potion optimale santé / magie / vigueur.

Le Settings Loader ajoute la prise en charge MCM Helper.

## Note

Les hotkeys ne sont pas configurées maintenant.

La configuration sera reprise plus tard avec la logique Startup Save / MCM Recorder.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 428 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 429 — Simple Offence Suppression / Block Friendly Fire

## Objectif

Ajouter un mini-bloc de protection contre l’aggro accidentelle et le friendly fire, issu de Nolvus Awakening.

## Mods installés

- `Simple Offence Suppression`
- `Simple Offence Suppression MCM - Block Friendly Fire`

## Origine

- Nolvus Awakening

## Sources

- Simple Offence Suppression : https://www.nexusmods.com/skyrimspecialedition/mods/41764
- MCM / Block Friendly Fire : https://www.nexusmods.com/skyrimspecialedition/mods/41774

## Rôle

Réduit les problèmes d’hostilité accidentelle après un coup ou tir involontaire.

Le module MCM permet de gérer le blocage du friendly fire.

## Note

Le MCM n’est pas configuré maintenant.

La configuration sera reprise plus tard avec la logique Startup Save / MCM Recorder.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 429 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 430 — I’m Talkin’ Here / Instantly Skip Dialogue NG

## Objectif

Ajouter un mini-bloc de confort dialogue issu de Nolvus Awakening.

## Mods installés

- `I’m Talkin’ Here`
- `Instantly Skip Dialogue NG`

## Origine

- Nolvus Awakening

## Sources

- I’m Talkin’ Here : https://www.nexusmods.com/skyrimspecialedition/mods/93694
- Instantly Skip Dialogue NG : https://www.nexusmods.com/skyrimspecialedition/mods/89163

## Rôle

- `I’m Talkin’ Here` empêche les followers de lancer des commentaires pendant que le joueur est déjà en dialogue.
- `Instantly Skip Dialogue NG` supprime le délai vanilla avant de pouvoir passer une ligne de dialogue.

## Choix d’installation

- Fichiers principaux installés.
- Aucun patch follower ajouté pour l’instant.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 430 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 431 — Disable Follower Collision / I’m Walkin’ Here

## Objectif

Ajouter un mini-bloc de confort déplacement / collision issu de Nolvus Awakening.

## Mods installés

- `Disable Follower Collision`
- `I’m Walkin’ Here`

## Origine

- Nolvus Awakening

## Sources

- Disable Follower Collision : https://www.nexusmods.com/skyrimspecialedition/mods/35925
- I’m Walkin’ Here : https://www.nexusmods.com/skyrimspecialedition/mods/27742

## Choix d’installation

- `Disable Follower Collision` : fichier principal.
- `I’m Walkin’ Here` : version `1.5.0`, compatible Skyrim `1.5.50 - 1.5.97`.
- Version `1.7.0` non installée car prévue pour Skyrim `1.6.640+`.

## Rôle

- `Disable Follower Collision` désactive la collision entre le joueur et les followers / alliés.
- `I’m Walkin’ Here` évite que les NPC bloquent ou poussent le joueur pendant les déplacements.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 431 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 432 — No Furniture Camera / Pick Up Radius

## Objectif

Ajouter un mini-bloc de confort caméra et ramassage d’objets issu de Nolvus Awakening.

## Mods installés

- `No Furniture Camera`
- `Pick Up Radius`

## Origine

- Nolvus Awakening

## Sources

- No Furniture Camera : https://www.nexusmods.com/skyrimspecialedition/mods/100515
- Pick Up Radius : https://www.nexusmods.com/skyrimspecialedition/mods/69750

## Rôle

- `No Furniture Camera` empêche le passage forcé à la caméra spéciale des meubles.
- `Pick Up Radius` ajoute un système de ramassage dans un rayon configurable via MCM.

## Note

Le MCM de `Pick Up Radius` n’est pas configuré maintenant.

La configuration sera reprise plus tard avec la logique Startup Save / MCM Recorder.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 432 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Étape 433 — Annulée : doublons déjà installés

## Objectif initial

Vérifier l’opportunité d’ajouter plusieurs modules de confort d’interaction.

## Mods concernés

- `Use Or Take SKSE`
- `Read Or Take SKSE`
- `Favorite Misc Items`

## Vérification

Les mods concernés étaient déjà installés dans SKYFORGE.

## Décision

Étape 433 annulée.

Aucune installation effectuée.

Aucun compteur modifié.

Cette étape sert de trace anti-doublon pour éviter de reproposer ces mods plus tard.

---

# Étape 434 — A Closer Look SSE

## Objectif

Ajouter un petit module de zoom caméra issu de Nolvus Awakening.

## Mod installé

- `A Closer Look SSE`

## Origine

- Nolvus Awakening

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/27737

## Choix d’installation

- Version SSE installée.
- Version NG non installée pour rester prudent avec Skyrim SE 1.5.97.

## Rôle

Ajoute une touche de zoom caméra configurable via MCM.

## Note

Le MCM n’est pas configuré maintenant.

La configuration sera reprise plus tard avec la logique Startup Save / MCM Recorder.

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESM / ESP non-light : 108

## Décision

Étape 434 validée.

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Contraintes respectées

- LOOT non lancé.
- DynDOLOD non lancé.
- BodySlide non lancé.
- Pandora non lancé.
- Aucun mod `- FR` activé.
- Aucun gros overhaul combat ajouté.

---

# Contraintes respectées sur les étapes 426 à 434

- LOOT non lancé.
- DynDOLOD / LOD non générés.
- BodySlide non lancé.
- Pandora non relancé.
- Mods `- FR` non activés.
- Aucun système adulte ajouté.
- Aucun retour à Nemesis.
- Aucun gros overhaul combat ajouté.
- `Precision - Creatures` reste différé.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 434 — A Closer Look SSE**.
- Séparateur actif : **10 - GAMEPLAY COMBAT MAGIC PERKS**.
- Profil : stable.
- Compteur ESP + ESM non-light global : **108**.
- Overwrite : vide.
- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.
- Pandora : non relancé depuis l’étape 411.
