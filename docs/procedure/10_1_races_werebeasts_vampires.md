# Module 10.1 — Races, werebeasts & vampires

Ce fichier documente les étapes 451 à 458 du projet SKYFORGE.

## Statut du bloc

- **Bloc :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Statut :** clôturé provisoirement à l'étape 458
- **Compteur final du bloc :** 111 ESP + ESM non-light
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé
- **Mods `- FR` :** non activés

## Règle vampire appliquée

Fabien ne prévoit pas de jouer vampire.

Conséquences appliquées pendant ce bloc :

- ne pas ajouter de mods principalement orientés PJ vampire ;
- privilégier les mods utiles aux NPC vampires ou utiles à la fois au PJ et aux NPC ;
- éviter les addons de feeding, progression, pouvoirs ou confort vampire purement joueur ;
- garder `Sacrosanct` comme base vampire validée ;
- ne pas empiler d'addons vampire sans bénéfice NPC clair.

Fichier de référence : `docs/configuration/09_regle_vampire_skyforge.md`.

---

# Étape 451 — Ouverture du bloc 10.1 Races Werebeasts Vampires

## Statut

Validée.

## Objectif

Ouvrir prudemment le bloc `[10.1 - RACES WEREBEASTS VAMPIRES]` sans installation immédiate, afin d'éviter tout conflit prématuré avec les futurs systèmes SexLab/Nefaram liés aux créatures.

## Actions réalisées

- Aucun mod installé.
- Bloc ouvert en audit prudent.
- Overhauls races, vampires, werebeasts et créatures différés.
- Aucun mod `- FR` activé.
- Pandora non relancé.
- LOOT non lancé.
- DynDOLOD / LOD non générés.
- BodySlide Output non généré.

## Note de prudence

Avant toute installation future liée aux vampires, loups-garous, vampire lord, werebear ou créatures, vérifier l'impact sur :

- Creature Framework ;
- animations SexLab créatures ;
- skeletons et meshes créatures ;
- compatibilité Pandora / SLAL / SexLab ;
- scripts ;
- plugins ;
- patches nécessaires ;
- cohérence avec la future architecture adulte Nefaram.

## Mods explicitement différés à l'ouverture du bloc

- Growl - Werebeasts of Skyrim
- Manbeast - A Werewolf Overhaul
- Sacrosanct - Vampires of Skyrim
- Scion - A Vampire Overhaul
- Better Vampires
- Mannaz - Integrated Races of Skyrim
- Freyr - Integrated Standing Stones of Skyrim

## Test de validation

- Menu principal OK.
- Aucun message DLL.
- Aucun master manquant.
- Overwrite vide.
- Compteur ESP + ESM non-light : 110.

## Résultat

Étape 451 validée.

---

# Étape 452 — Aetherius - A Race Overhaul

## Statut

Validée.

## Mod installé

### Aetherius - A Race Overhaul

- **Source :** Nolvus Awakening / externe Simonrim
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/26686
- **Version installée :** 2.14.1
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Installation FOMOD :** minimale

## Choix FOMOD

Installé :

- Aetherius - A Race Overhaul

Non installés :

- Aetherius - Racial Starting Spells
- Aetherius - Lower Starting Skills
- Aetherius - NPC Spell Absorption

Note : FOMOD à revoir plus tard si besoin d'ajuster l'équilibrage racial, les sorts de départ, les compétences de départ ou les NPC.

## Décisions

- Aetherius conservé comme overhaul de races actuel.
- Ne pas installer Mannaz, Imperious ou autre overhaul de races en parallèle.
- Vampires, werebeasts et créatures différés.
- Aucun mod `- FR` activé.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 110.

---

# Étape 453 — Aetherius Race Menu Racial Passive Descriptions

## Statut

Validée.

## Mod installé

### Aetherius - Race Menu Racial Passive Descriptions

- **Source :** proposition spécifique pour SKYFORGE
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/116109
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Placement :** juste après `Aetherius - A Race Overhaul`
- **Rôle :** afficher dans RaceMenu les descriptions des passifs raciaux fournis par Aetherius.

## Décisions

- Complément conservé.
- Installation légère, liée uniquement à l'affichage / description.
- Aucun système vampire, werebeast ou créature ajouté.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 110.

## Rappel méthodologique validé

À partir de l'étape 454, chaque proposition de mod doit indiquer clairement une des trois sources :

- Source Nolvus Awakening ;
- Source Nefaram ;
- Proposition spécifique pour SKYFORGE.

---

# Étape 454 — Mundus - A Standing Stone Overhaul

## Statut

Validée.

## Mod installé

### Mundus - A Standing Stone Overhaul

- **Source :** Nefaram
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/33411
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Placement :** après les mods Aetherius
- **Rôle :** remplacer les effets vanilla des Pierres Gardiennes par des bonus passifs plus structurants.

## Choix FOMOD

Installés :

- Mundus - A Standing Stone Overhaul
- USSEP Patch

## Décisions

- Mundus conservé comme overhaul actuel des Pierres Gardiennes.
- Ne pas installer Freyr ou autre overhaul des Standing Stones en parallèle.
- Vampires, werebeasts et créatures différés.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 110.

---

# Étape 455 — Manbeast - A Werewolf Overhaul

## Statut

Validée.

## Mod installé

### Manbeast - A Werewolf Overhaul

- **Source :** Nefaram
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/44746
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Placement :** après Aetherius et Mundus
- **Rôle :** overhaul du système loup-garou.

## Décisions

- Manbeast conservé comme overhaul werewolf actuel.
- Ne pas installer Growl, Moonlight Tales ou autre overhaul werewolf en parallèle.
- Growl reste une référence Nolvus Awakening mais est exclu pour éviter un doublon de systèmes.
- Créatures SexLab/Nefaram différées.

## Note de prudence

Manbeast est accepté ici comme overhaul werewolf gameplay, mais tout ajout ultérieur touchant aux formes bêtes, animations ou créatures devra être audité séparément.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 110.

---

# Étape 456 — Sacrosanct + Cover Your Head - Sacrosanct

## Statut

Validée.

## Mods installés

### Sacrosanct - Vampires of Skyrim

- **Source :** Nefaram + Nolvus Awakening
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/3928
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Rôle :** overhaul vampire / vampire lord.

### Cover Your Head - Sacrosanct

- **Source :** Nefaram
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/53466
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Placement :** après Sacrosanct
- **Rôle :** permettre la protection solaire avec casque / capuche pour Sacrosanct.

## Note FOMOD / requirements

Pour `Cover your head - Sacrosanct or Sacrilege or Scion`, la mention Nexus “Obviously” signifie “évidemment”, pas “obligatoire”.

Choix retenu :

- Sacrosanct requis et installé.
- Version Cover Your Head - Sacrosanct installée.
- Scion non installé.
- Sacrilege non installé.

## Décisions

- Sacrosanct conservé comme overhaul vampire actuel.
- Cover Your Head - Sacrosanct conservé comme complément.
- Ne pas installer Scion, Sacrilege, Better Vampires ou Vampire Lords Can Fly en parallèle.
- Ne pas installer d'animations ou systèmes créatures SexLab à cette étape.

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 457 — Sun Affects NPC Vampires

## Statut

Validée.

## Mod installé

### Sun Affects NPC Vampires

- **Source :** proposition spécifique pour SKYFORGE
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/47277
- **Emplacement MO2 :** `[10.1 - RACES WEREBEASTS VAMPIRES]`
- **Placement :** après `Cover Your Head - Sacrosanct`, proche du sous-bloc vampire
- **Rôle :** appliquer les effets du soleil aux vampires NPC, avec option compatible PJ + NPC.

## Choix FOMOD

- Option **NPC + PJ** sélectionnée.

## Décision

Choix validé : le mod respecte la règle SKYFORGE car il reste utile aux NPC vampires et couvre aussi le PJ si jamais le cas se présente.

## Différés maintenus

- Vampire Feeding Tweaks
- Better Vampires
- Scion
- Sacrilege
- Addons feeding orientés joueur

## Test

Menu principal OK, aucun message DLL, aucun master manquant, Overwrite vide.

Compteur : 111.

---

# Étape 458 — Audit / clôture provisoire du bloc 10.1

## Statut

Validée.

## Objectif

Clôturer provisoirement le bloc `[10.1 - RACES WEREBEASTS VAMPIRES]` après audit, sans ajouter de mod de dialogue ou de contenu relevant plutôt d'un futur bloc NPC / dialogues.

## Décision principale

`Vampire Lines Expansion` n'a pas été installé dans ce bloc.

- **Source :** Nolvus Awakening + Nefaram
- **URL :** https://www.nexusmods.com/skyrimspecialedition/mods/83484
- **Statut :** différé
- **Destination recommandée :** `[11.1 - FOLLOWERS NPCS DIALOGUES]`
- **Raison :** le mod ajoute des lignes de dialogue aux vampires NPC ; il relève davantage du bloc dialogues / NPC que du bloc gameplay races / vampires / werebeasts.

## Bloc 10.1 validé provisoirement avec

- Aetherius - A Race Overhaul
- Aetherius - Race Menu Racial Passive Descriptions
- Mundus - A Standing Stone Overhaul
- Manbeast - A Werewolf Overhaul
- Sacrosanct - Vampires of Skyrim
- Cover Your Head - Sacrosanct
- Sun Affects NPC Vampires

## Mods différés / exclus pour l'instant

- Vampire Feeding Tweaks
- Better Vampires
- Scion
- Sacrilege
- Vampire Lords Can Fly
- Vampire Lines Expansion, différé vers `[11.1 - FOLLOWERS NPCS DIALOGUES]`
- Growl, exclu car Manbeast est retenu
- Freyr, exclu car Mundus est retenu
- Mannaz, exclu car Aetherius est retenu

## Test de validation

- Menu principal OK.
- Aucun message DLL.
- Aucun master manquant.
- Overwrite vide.
- Compteur ESP + ESM non-light : 111.

## Résultat

Étape 458 validée.

Bloc `[10.1 - RACES WEREBEASTS VAMPIRES]` clôturé provisoirement.

Prochaine étape : 459.
