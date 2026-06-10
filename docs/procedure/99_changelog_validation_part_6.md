# Changelog de validation — partie 6

> Suivi chronologique des validations du projet **SKYFORGE**.
> Partie 6 : module **07 - CITIES TOWNS INTERIORS LIGHTING**, sous-bloc **07.6 - INTERIORS**.
> Étapes couvertes : **347 à 357**.

---

## Étape 347 — Ouverture 07.6 INTERIORS

Ouverture du sous-bloc **07.6 - INTERIORS** après clôture de **07.5 - RUINS**.

Décisions :

* création / vérification du séparateur MO2 `07.6 - INTERIORS` ;
* aucun mod installé à cette étape ;
* mods Legacy of the Dragonborn différés tant que LOTD n’est pas intégré ;
* premier candidat logique retenu pour l’étape suivante :

  * `Underground - A Dungeon Texture Overhaul` ;
  * `Underground - Complex Parallax Addon`.

État :

* aucun changement technique ;
* Overwrite vide ;
* compteur ESP + ESM non-light maintenu à **79** ;
* LOOT non lancé ;
* LOD / DynDOLOD non générés.

---

## Étape 348 — INTERIORS pack 1 : Underground

Installation du premier pack **07.6 - INTERIORS** :

* `Underground - a dungeon texture overhaul - CHOIX NOLVUS`
* `Underground - Complex Parallax Addon - CHOIX NOLVUS`

Fichiers optionnels repérés mais non installés :

* Whiterun Tower fix ;
* Terrain Parallax Blending Fix Patch.

Résultat :

* SKSE via MO2 : OK ;
* menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* aucun fichier optionnel installé ;
* Overwrite vide ;
* compteur non-light maintenu à **79**.

---

## Étape 349 — INTERIORS pack 2 : CC’s HQ Barset

Installation de :

* `CC's HQ Barset - 2K - 1.2 - CHOIX NOLVUS`

Lien corrigé utilisé :

* https://www.nexusmods.com/skyrimspecialedition/mods/7974

Résultat :

* aucun plugin ajouté ;
* compteur non-light maintenu à **79**.

---

## Étape 350 — INTERIORS pack 3 : Skyrim Sewers 4

Installation de :

* `Skyrim Sewers 4 - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`

Fichier installé :

* `Skyrim Sewers 415`

Fichier optionnel non installé :

* `Skyrim Sewers Capital Whiterun Expansion compatible esp`

Plugin activé :

* `SkyrimSewers.esp`

Incident :

* premier lancement : fermeture directe avant menu principal ;
* relance immédiate : OK ;
* redémarrage MO2 + relance : OK ;
* incident considéré comme crash ponctuel non reproductible.

Décision :

* surveillance maintenue ;
* pas de réparation MO2 ;
* pas de modification DLL ;
* pas de LOOT.

Résultat :

* SKSE / menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light passé de **79** à **80**.

---

## Étape 351 — INTERIORS pack 4 : Skyrim Sewers patches différés

Traitement des patches liés à Skyrim Sewers.

Décision :

* aucun patch installé maintenant ;
* patches marqués en `PATCHES A VOIR PLUS TARD`.

Patches différés :

* `Skyrim Sewers - Vigilant Patch` : Vigilant pas intégré ;
* `Skyrim Sewers - Undeath Patch` : Undeath pas intégré ;
* `Skyrim Sewers - JS Solitude Sewer Cover Patch` : dépendance non stabilisée ;
* `Skyrim Sewers - GG's Impoverished Whiterun Patch` : système non actif ;
* `Skyrim Sewers - Weapon Replacement` : différé.

Résultat :

* aucun changement technique ;
* LOOT non lancé ;
* LOD / DynDOLOD non générés.

---

## Étape 352 — INTERIORS pack 4 : Distinct Interiors

Installation de :

* `Distinct Interiors - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `Distinct Interiors - Fixes - CHOIX NOLVUS`

Décisions :

* version All-in-One / AiO retenue ;
* modules séparés non installés ;
* patches Cities of the North / Great Cities / JK / Lux différés.

Résultat :

* SKSE via MO2 : OK ;
* menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light passé de **80** à **81**.

---

## Étape 353 — INTERIORS pack 5 : Dragonsreach

Installation du trio Dragonsreach :

* `JK's Dragonsreach - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `RedBag's Dragonsreach - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's and Redbag's Dragonsreach Patch - CHOIX NOLVUS`

Éléments différés :

* Distinct Interiors Patch Collection ;
* The Distinct Cities of the North Interiors ;
* The Distinct Great Old Hroldan Inn ;
* The Distinct Great Kynesgrove Interiors ;
* patches Lux / Lux Orbis / Lux Via ;
* patches Distinct / COTN / Great Cities si nécessaire.

Résultat :

* SKSE via MO2 : OK ;
* menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light maintenu à **81**.

---

## Étape 354 — INTERIORS pack 6 : Winking Skeever + boutiques Solitude

Installation de :

* `JK's The Winking Skeever - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's Angeline's Aromatics - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's Bits and Pieces - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`

Patches différés :

* USSEP éventuels ;
* 3DNPC ;
* Immersion / Cheesemod ;
* Undeath / Skyrim Sewers ;
* Lux / Lux Orbis / Lux Via ;
* Distinct Interiors ;
* patches Nolvus éventuels.

Résultat :

* SKSE via MO2 : OK ;
* menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light maintenu à **81**.

---

## Étape 355 — INTERIORS pack 7 : Radiant Raiment + début Riverwood

Installation de :

* `JK's Radiant Raiment - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `Ryn's Sleeping Giant Inn - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `Ryn's Hod and Gerdur's House - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `Ryn's Sven's and Hilde's House - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`

Éléments différés :

* The Distinct JK's Radiant Raiment ;
* The Distinct JK's Bits and Pieces ;
* patches LOTD / 3DNPC / Cheesemod / Lux.

Résultat :

* SKSE via MO2 : OK ;
* menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light maintenu à **81**.

---

## Étape 356 — INTERIORS pack 8 : fin Riverwood

Installation de :

* `Ryn's Faendal's House - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `Ryn's Alvor and Sigrid's House - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`

Liens corrigés utilisés :

* https://www.nexusmods.com/skyrimspecialedition/mods/89222
* https://www.nexusmods.com/skyrimspecialedition/mods/89187

Élément non installé :

* `Ryn's Riverwood Patch Collection`

Résultat :

* SKSE / menu principal : OK ;
* aucun master manquant ;
* aucun message DLL ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light maintenu à **81**.

---

## Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK

Installation du groupe Whiterun Interiors :

* `EEKs Whiterun Interiors SSE - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's The Bannered Mare - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's Arcadia's Cauldron - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's Warmaiden's - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's Belethor's General Goods - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `JK's The Drunken Huntsman - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD`
* `The JK's Interiors of EEK's Whiterun - CHOIX NOLVUS - A REINSTALL PLUS TARD`

Note FOMOD :

* options cochées uniquement si déjà actives :

  * Creation Club / Bow of Shadows ;
  * Distinct Interiors.
* FOMOD à reprendre plus tard quand lighting / LOTD / patches intérieurs seront stabilisés.

Résultat :

* SKSE / menu principal : OK ;
* aucun master manquant ;
* tous les plugins cochés ;
* Overwrite vide ;
* compteur non-light passé de **81** à **82**.

---

## État final de la partie 6

* **Dernière étape validée :** Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
* **Dernière étape d’installation validée :** Étape 357 — INTERIORS pack 9 : Whiterun EEK + JK
* **Module en cours :** 07 - CITIES TOWNS INTERIORS LIGHTING
* **Sous-bloc en cours :** 07.6 - INTERIORS
* **Dernier fichier thématique mis à jour :** `docs/procedure/11_cities_towns_interiors_lighting_part_8.md`
* **Compteur ESP + ESM non-light :** 82
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **Prochaine étape attendue :** Étape 358
