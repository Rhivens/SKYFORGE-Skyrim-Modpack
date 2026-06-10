# Cities, towns, interiors & lighting — partie 7

> Procédure personnelle du projet **SKYFORGE**.
> Sous-bloc documenté : **07.5 - RUINS**.
> Étapes couvertes : **342 à 346**.

---

## État de reprise

* **Dernière étape validée avant reprise :** Étape 341 — Contrôle final 07.4 LANDS et profil stable
* **Sous-bloc terminé avant reprise :** 07.4 - LANDS
* **Nouveau sous-bloc ouvert :** 07.5 - RUINS
* **Profil stable précédent :** SKYFORGE - Stable étape 341 lands installation terminée
* **Compteur ESP + ESM non-light :** 79
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **Règle maintenue :** main files d’abord, patches complexes différés

---

# Étape 342 — Reprise SKYFORGE et ouverture de 07.5 - RUINS

## Objectif

Reprendre proprement après la pause et ouvrir le sous-bloc :

`07.5 - RUINS`

## Actions

* Ouvrir Mod Organizer 2.
* Charger le profil de travail SKYFORGE.
* Ne pas utiliser le profil stable de sauvegarde pour l’installation.
* Vérifier l’état technique avant toute nouvelle installation.

## Contrôle avant installation

État confirmé :

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 79

## Résultat

Le sous-bloc `07.5 - RUINS` peut être ouvert.

Aucune installation effectuée pendant cette étape.

---

# Étape 343 — RUINS pack 1 : Rustic Relief

## Objectif

Démarrer le sous-bloc `07.5 - RUINS` avec le petit pack de base Nolvus :

* textures de reliefs nordiques ;
* complément parallax.

## Source Nolvus

Dans l’export Nolvus local, le sous-bloc `5.12.2 RUINS` contient seulement :

* Rustic Relief
* Rustic Relief - Parallax

La page Nolvus actuelle liste aussi :

* CleverCharff’s Nordic Ruins
* Gorgeous Ruin Door
* Tower Ruins Retexture

Ces compléments seront traités dans une étape séparée.

## Mods installés

### Rustic Relief

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/34684
* Source : CHOIX NOLVUS
* Type : textures / meshes
* Plugin attendu : aucun

### Rustic Relief - Parallax

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/34684
* Source : CHOIX NOLVUS
* Version Nolvus indiquée : 1.3
* Type : optionnel parallax
* Plugin attendu : aucun

## Actions

* Installer `RUSTIC RELIEFS` main file.
* Installer ensuite `Rustic Relief - Parallax`.
* Placer `Rustic Relief - Parallax` après `Rustic Relief` dans MO2.
* Ne pas lancer LOOT.
* Ne pas générer LOD / DynDOLOD.

## Résultat

Mods ajoutés :

* Rustic Relief - CHOIX NOLVUS
* Rustic Relief - Parallax - CHOIX NOLVUS

Aucun plugin ajouté.

---

# Étape 344 — Validation RUINS pack 1

## Objectif

Enregistrer la validation de Rustic Relief + Parallax sans créer d’installation supplémentaire.

## État confirmé

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 79
* Aucun plugin ajouté

## Résultat

Étape 343 validée.

Mods validés :

* Rustic Relief - CHOIX NOLVUS
* Rustic Relief - Parallax - CHOIX NOLVUS

LOOT non lancé.
LOD / DynDOLOD non générés.

---

# Étape 345 — RUINS pack 2 : compléments Nolvus actuels

## Objectif

Compléter le sous-bloc `07.5 - RUINS` avec les mods présents sur la page Nolvus actuelle, mais absents de l’export local.

Nolvus liste bien ces trois compléments dans `5.12.2 Ruins` :

* CleverCharff’s Nordic Ruins
* Gorgeous Ruin Door
* Tower Ruins Retexture

## Mods installés

### CleverCharff’s Nordic Ruins [2K]

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/36701
* Source : CHOIX NOLVUS
* Version retenue : 2K
* Type : textures de ruines nordiques
* Plugin attendu : aucun

### Gorgeous Ruin Door [2K]

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/29140
* Source : CHOIX NOLVUS
* Version retenue : 2K
* Type : textures de portes de ruines
* Plugin attendu : aucun

### Tower Ruins Retexture

* Lien : https://www.nexusmods.com/skyrimspecialedition/mods/43559
* Source : CHOIX NOLVUS
* Type : retexture de ruines / tours
* Plugin attendu : aucun

## Actions

* Installer les trois mods.
* Retenir uniquement les main files / versions 2K quand applicable.
* Placer `CleverCharff's Nordic Ruins [2K]` avant `Rustic Relief` si MO2 demande un ordre logique textures générales → détails.
* Garder `Rustic Relief - Parallax` après `Rustic Relief`.
* Ne pas installer de patch maintenant.
* Ne pas lancer LOOT.
* Ne pas générer LOD / DynDOLOD.

## Résultat

Mods ajoutés :

* CleverCharff's Nordic Ruins [2K] - CHOIX NOLVUS
* Gorgeous Ruin Door [2K] - CHOIX NOLVUS
* Tower Ruins Retexture - CHOIX NOLVUS

Aucun plugin ajouté.

---

# Étape 346 — Contrôle final 07.5 RUINS et profil stable

## Objectif

Clôturer proprement le sous-bloc `07.5 - RUINS`.

## Mods RUINS présents et cochés

Les cinq mods du sous-bloc sont cochés :

* Rustic Relief
* Rustic Relief - Parallax
* CleverCharff's Nordic Ruins [2K]
* Gorgeous Ruin Door [2K]
* Tower Ruins Retexture

## Contrôle technique

État confirmé :

* SKSE via MO2 : OK
* Menu principal : OK
* Aucun master manquant : OK
* Aucun message DLL : OK
* Tous les plugins cochés : OK
* Overwrite vide : OK
* Compteur ESP + ESM non-light : 79
* Aucun plugin ajouté par le sous-bloc RUINS
* LOOT non lancé
* LOD / DynDOLOD non générés

## Profil stable

Profil stable créé :

`SKYFORGE - Stable étape 346 ruins OK`

## Résultat

Sous-bloc terminé :

`07.5 - RUINS`

État final :

* Étape 346 validée
* Sous-bloc RUINS terminé
* Aucun plugin ajouté
* Compteur non-light maintenu à 79
* Profil stable créé
* LOOT toujours non lancé
* LOD / DynDOLOD toujours différés

---

## État de sortie

* **Dernière étape validée :** Étape 346 — Contrôle final 07.5 RUINS et profil stable
* **Dernière étape d’installation validée :** Étape 345 — RUINS pack 2
* **Sous-bloc terminé :** 07.5 - RUINS
* **Profil stable :** SKYFORGE - Stable étape 346 ruins OK
* **Compteur ESP + ESM non-light :** 79
* **Prochaine étape attendue :** Étape 347
