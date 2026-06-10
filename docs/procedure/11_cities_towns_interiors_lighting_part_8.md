# Cities, towns, interiors & lighting — partie 8

> Procédure personnelle du projet **SKYFORGE**.
> Sous-bloc documenté : **07.6 - INTERIORS**.
> Étapes couvertes : **347 à 357**.

---

## État de reprise

* **Dernière étape validée avant reprise :** Étape 346 — Contrôle final 07.5 RUINS et profil stable
* **Sous-bloc terminé avant reprise :** 07.5 - RUINS
* **Nouveau sous-bloc ouvert :** 07.6 - INTERIORS
* **Profil stable précédent :** SKYFORGE - Stable étape 346 ruins OK
* **Compteur ESP + ESM non-light :** 79
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **Règle maintenue :** main files d’abord, patches complexes différés

---

# Étape 347 — Ouverture 07.6 INTERIORS

## Objectif

Ouvrir le sous-bloc suivant après `07.5 - RUINS` et préparer le premier pack sans installer tout de suite.

## Source Nolvus

Dans l’export Nolvus, après `[5.12.2 RUINS]`, le bloc suivant est bien `[5.13 INTERIORS]`.

Il commence par :

* Legacy Safehouse Plus ;
* Legacy of the Dragonborn - Follower Room Patches ;
* Underground - A Dungeon Texture Overhaul ;
* Underground - Complex Parallax Addon.

## Décision

Les mods liés à Legacy of the Dragonborn sont différés tant que LOTD n’est pas intégré.

Premier candidat logique pour l’installation suivante :

* Underground - A Dungeon Texture Overhaul ;
* Underground - Complex Parallax Addon.

Règle maintenue :

* textures d’abord ;
* gros mods / patches ensuite ;
* ne pas lancer LOOT ;
* ne pas générer LOD / DynDOLOD.

## Actions

* Créer / vérifier le séparateur MO2 :

  * `07.6 - INTERIORS`
* Ne rien installer encore.
* Noter que les mods Legacy of the Dragonborn sont à différer tant que LOTD n’est pas intégré.

## Résultat attendu

* Aucun changement technique.
* Overwrite vide.
* Compteur ESP + ESM non-light maintenu à 79.
* Prêt pour Étape 348 — INTERIORS pack 1 : Underground.

---

# Étape 348 — INTERIORS pack 1 : Underground

## Objectif

Installer le premier pack `07.6 - INTERIORS` :

* textures de donjons ;
* addon parallax.

## Mods installés

### Underground - a dungeon texture overhaul

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/14365
* Source : CHOIX NOLVUS
* Type : textures de donjons
* Zones couvertes : caves, mines, ruines nordiques, dwemer, forts, Riften, Apocrypha
* Plugin attendu : aucun

### Underground - Complex Parallax Addon

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/82870
* Source : CHOIX NOLVUS
* Type : addon parallax pour Underground
* Plugin attendu : aucun

## Actions

* Installer `Underground - a dungeon texture overhaul`.
* Choisir une option prudente dans le FOMOD :

  * qualité 2K si proposée ;
  * option standard / vanilla ;
  * pas d’option spéciale future.
* Installer ensuite `Underground - Complex Parallax Addon`.
* Placer l’addon parallax après Underground dans le panneau gauche.
* Marquer :

  * `Underground - a dungeon texture overhaul - CHOIX NOLVUS`
  * `Underground - Complex Parallax Addon - CHOIX NOLVUS`

## Fichiers optionnels repérés mais non installés

* Whiterun Tower fix
* Terrain Parallax Blending Fix Patch

## Résultat validé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Aucun fichier optionnel installé
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 79

---

# Étape 349 — INTERIORS pack 2 : CC’s HQ Barset

## Objectif

Installer `CC’s HQ Barset`.

## Mod installé

### CC's HQ Barset

* Lien corrigé utilisé : https://www.nexusmods.com/skyrimspecialedition/mods/7974
* Version retenue : 2K - 1.2
* Source : CHOIX NOLVUS
* Type : textures
* Plugin attendu : aucun

## Résultat validé

* `CC's HQ Barset - 2K - 1.2 - CHOIX NOLVUS`
* Aucun plugin ajouté
* Compteur ESP + ESM non-light maintenu à 79

---

# Étape 350 — INTERIORS pack 3 : Skyrim Sewers 4

## Objectif

Ajouter `Skyrim Sewers 4`, premier mod d’intérieur avec plugin du bloc `07.6`.

## Mod installé

### Skyrim Sewers 4

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/9320
* Version Nexus visible : 4.15
* Fichier installé : Skyrim Sewers 415
* Source : CHOIX NOLVUS
* Type : ajout de réseaux d’égouts
* Zones concernées : Solitude, Whiterun, Windhelm, Markarth, quelques forts

## Actions

* Installer le main file.
* Ne pas installer les replacers / patches optionnels maintenant.
* Ne pas installer le fichier optionnel :

  * `Skyrim Sewers Capital Whiterun Expansion compatible esp`
* Activer le mod dans le panneau gauche.
* Cocher le plugin :

  * `SkyrimSewers.esp`
* Marquer :

  * `Skyrim Sewers 4 - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`

## Patches différés

* JS Solitude Sewer Cover
* SREX
* patches Nolvus
* patches villes / intérieurs éventuels

## Note incident

Premier lancement : fermeture directe avant menu principal.

Relances suivantes :

* relance immédiate : OK ;
* redémarrage MO2 + relance : OK.

Décision :

* incident considéré comme crash ponctuel non reproductible ;
* surveillance maintenue ;
* pas de réparation MO2 ;
* pas de modification DLL ;
* pas de LOOT.

## Résultat validé

* SKSE / menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Plugin activé : `SkyrimSewers.esp`
* Compteur ESP + ESM non-light passé de 79 à 80

---

# Étape 351 — INTERIORS pack 4 : Skyrim Sewers patches différés

## Objectif

Traiter proprement les patches liés à `Skyrim Sewers 4` avant de passer à `Distinct Interiors`.

## Source Nolvus

Après Skyrim Sewers, Nolvus liste plusieurs fichiers :

* Vigilant Patch
* Undeath Patch
* Weapon Replacement
* JS Solitude Sewer Cover Patch
* GG's Impoverished Whiterun Patch
* puis Distinct Interiors

Les plugins correspondants existent bien dans l’ordre Nolvus.

## Décision

Ne rien installer maintenant dans ce pack.

## Actions

Marquer les patches Skyrim Sewers en `PATCHES A VOIR PLUS TARD`.

Ne pas installer :

* `Skyrim Sewers - Vigilant Patch` : Vigilant pas intégré.
* `Skyrim Sewers - Undeath Patch` : Undeath pas intégré.
* `Skyrim Sewers - JS Solitude Sewer Cover Patch` : dépend d’un mod / patch de couvercle Solitude non stabilisé.
* `Skyrim Sewers - GG's Impoverished Whiterun Patch` : dépend d’un système non actif.
* `Skyrim Sewers - Weapon Replacement` : différé.

## Résultat

* Aucun patch installé.
* Incident précédent conservé comme crash ponctuel non reproductible.
* LOOT non lancé.
* LOD / DynDOLOD non générés.

---

# Étape 352 — INTERIORS pack 4 : Distinct Interiors

## Objectif

Installer `Distinct Interiors` de façon prudente, sans patches complexes pour l’instant.

## Mods installés

### Distinct Interiors

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/6130
* Source : CHOIX NOLVUS
* Version retenue : All-in-One / AiO
* Type : modifications d’intérieurs
* Statut : PATCHES A VOIR PLUS TARD

### Distinct Interiors - Fixes

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/23831
* Source : CHOIX NOLVUS
* Type : correctifs pour Distinct Interiors
* Dépendance : All-in-One main file

## Actions

* Installer `Distinct Interiors` depuis le lien 6130.
* Choisir la version All-in-One / AiO.
* Ne pas installer les modules séparés.
* Installer `Distinct Interiors - Fixes`.
* Ne pas installer les patches Cities of the North / Great Cities / JK / Lux maintenant.
* Marquer :

  * `Distinct Interiors - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
  * `Distinct Interiors - Fixes - CHOIX NOLVUS`

## Résultat validé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Tous les patches complexes restent différés
* Compteur ESP + ESM non-light passé de 80 à 81

---

# Étape 353 — INTERIORS pack 5 : Dragonsreach

## Objectif

Installer le trio Nolvus pour Dragonsreach, sans patches complexes.

## Source Nolvus

Après Distinct Interiors, Nolvus liste notamment :

* Distinct Interiors Patch Collection
* The Distinct Cities of the North Interiors
* JK's Dragonsreach
* RedBag's Dragonsreach
* Redbag's Dragonsreach - JK's Patch

Les éléments Distinct / COTN sont différés car beaucoup dépendent de systèmes non stabilisés.

## Mods installés

### JK’s Dragonsreach

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/34000
* Source : CHOIX NOLVUS
* Plugin signalé ESL-flagged sur Nexus
* Statut : PATCHES A VOIR PLUS TARD

### RedBag’s Dragonsreach - SE

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/41870
* Version visible : 1.5
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s and Redbag’s Dragonsreach Patch

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/45686
* Source : CHOIX NOLVUS
* Patch ESL-flagged

## Éléments différés

* Distinct Interiors Patch Collection
* The Distinct Cities of the North Interiors
* The Distinct Great Old Hroldan Inn
* The Distinct Great Kynesgrove Interiors

## Plugins attendus

* `JK's Dragonsreach.esp`
* `RedBag's Dragonsreach.esp`
* patch JK / RedBag, nom exact selon archive

## Résultat validé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Patches Lux / Orbis / Via / Distinct / COTN / Great Cities différés
* Compteur ESP + ESM non-light : 81

---

# Étape 354 — INTERIORS pack 6 : Winking Skeever + boutiques Solitude

## Objectif

Installer le petit groupe suivant après Dragonsreach, en suivant l’ordre Nolvus :

* Winking Skeever ;
* Angeline’s Aromatics ;
* Bits and Pieces.

## Mods installés

### JK’s The Winking Skeever

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/43991
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s Angeline’s Aromatics

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/44482
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s Bits and Pieces

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/44642
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

## Actions

* Installer les 3 mods, main file uniquement.
* Ne pas installer les patches optionnels maintenant.
* Activer les 3 mods dans le panneau gauche.
* Cocher les plugins :

  * `JK's The Winking Skeever.esp`
  * `JK's Angelines Aromatics.esp`
  * `JK's Bits and Pieces.esp`

## Patches différés

* USSEP éventuels
* 3DNPC
* Immersion / Cheesemod
* Undeath / Skyrim Sewers
* Lux / Lux Orbis / Lux Via
* Distinct Interiors
* patches Nolvus éventuels

## Résultat validé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 81

---

# Étape 355 — INTERIORS pack 7 : Radiant Raiment + début Riverwood

## Objectif

Continuer le bloc `07.6 - INTERIORS` avec un petit groupe cohérent :

* fin Solitude ;
* début Riverwood.

## Source Nolvus

Après `JK's Bits and Pieces`, Nolvus liste :

* The Distinct JK's Bits and Pieces ;
* JK's Radiant Raiment ;
* The Distinct JK's Radiant Raiment ;
* les maisons Ryn’s de Riverwood.

Les modules Distinct JK’s sont différés pour éviter les patches en cascade.

## Mods installés

### JK’s Radiant Raiment

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/44858
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### Ryn’s Sleeping Giant Inn

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/89519
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### Ryn’s Hod and Gerdur’s House

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/89297
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### Ryn’s Sven’s and Hilde’s House

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/89236
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

## Actions

* Installer les 4 mods, main file uniquement.
* Ne pas installer :

  * The Distinct JK's Radiant Raiment
  * The Distinct JK's Bits and Pieces
  * patches LOTD / 3DNPC / Cheesemod / Lux
* Activer les 4 mods dans le panneau gauche.
* Cocher les plugins :

  * `JK's Radiant Raiment.esp`
  * `Ryn's Sleeping Giant Inn.esp`
  * `Ryn's Gerdur's House.esp`
  * `Ryn's Sven's House.esp`

## Résultat validé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 81

---

# Étape 356 — INTERIORS pack 8 : fin Riverwood

## Objectif

Terminer le mini-groupe Riverwood / Ryn’s interiors avant de passer à Whiterun.

## Source Nolvus

Après `Ryn's Sven's and Hilde's House`, Nolvus liste :

* Ryn's Faendal's House ;
* Ryn's Alvor and Sigrid's House ;
* Ryn's Riverwood Patch Collection.

## Liens corrigés vérifiés

### Ryn’s Faendal’s House

* Lien corrigé : https://www.nexusmods.com/skyrimspecialedition/mods/89222
* Version visible : 1.1
* Plugin : FLAGGED AS ESL
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### Ryn’s Alvor and Sigrid’s House

* Lien corrigé : https://www.nexusmods.com/skyrimspecialedition/mods/89187
* Version visible : 1.0
* Plugin : FLAGGED AS ESL
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

## Actions

* Installer les 2 mods, main file uniquement.
* Ne pas installer les patches Cheesemod / LOTD / Lux maintenant.
* Ne pas installer `Ryn's Riverwood Patch Collection` pour l’instant.
* Activer les 2 mods dans le panneau gauche.
* Cocher les plugins :

  * `Ryn's Faendal's House.esp`
  * `Ryn's Alvor's House.esp`

## Résultat validé

* SKSE / menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* `Ryn's Riverwood Patch Collection` non installé pour l’instant
* Compteur ESP + ESM non-light : 81

---

# Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK

## Objectif

Installer le groupe Whiterun Interiors dans l’ordre Nolvus :

* EEKs Whiterun Interiors ;
* les 5 intérieurs JK ;
* le patch EEK / JK.

## Source Nolvus

Nolvus liste cette séquence après Riverwood.

## Mods installés

### EEKs Whiterun Interiors SSE

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/10463
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s The Bannered Mare

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/33845
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s Arcadia’s Cauldron

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/33565
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s Warmaiden’s

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/33685
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s Belethor’s General Goods

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/33636
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### JK’s The Drunken Huntsman

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/33783
* Source : CHOIX NOLVUS
* Statut : PATCHES A VOIR PLUS TARD

### The JK’s Interiors of EEK’s Whiterun

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/46769
* Source : CHOIX NOLVUS
* Statut : A REINSTALL PLUS TARD

## Actions

* Installer les 7 mods ci-dessus, main file uniquement.
* Ne pas installer les patches additionnels :

  * LOTD
  * Cheesemod
  * 3DNPC
  * Citizens of Tamriel
  * Skyrim Unique Drinks
  * Lux / Embers XD
  * Distinct Interiors
* Activer tous les mods dans le panneau gauche.
* Cocher les plugins attendus :

  * `EEKs Whiterun Interiors.esp`
  * `JK's The Bannered Mare.esp`
  * `JK's Arcadia's Cauldron.esp`
  * `JK's Warmaiden's.esp`
  * `JK's Belethor's General Goods.esp`
  * `JKs The Drunken Huntsman.esp`
  * les plugins `The JK's Interior of EEK's...` si fournis par le patch

## Note FOMOD

Options cochées uniquement si déjà actives :

* Creation Club / Bow of Shadows ;
* Distinct Interiors.

FOMOD à reprendre plus tard quand lighting / LOTD / patches intérieurs seront stabilisés.

## Résultat validé

* SKSE / menu principal : OK
* Aucun master manquant : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 82

---

## État de sortie

* **Dernière étape validée :** Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
* **Dernière étape d’installation validée :** Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
* **Module en cours :** 07 - CITIES TOWNS INTERIORS LIGHTING
* **Sous-bloc en cours :** 07.6 - INTERIORS
* **Profil stable précédent :** SKYFORGE - Stable étape 346 ruins OK
* **Compteur ESP + ESM non-light :** 82
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **Prochaine étape attendue :** Étape 358
