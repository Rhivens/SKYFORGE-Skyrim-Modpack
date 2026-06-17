# SKYFORGE — 09 - ANIMATIONS SKELETON PHYSICS — Part 2

## Objet du fichier

Ce fichier poursuit la documentation du séparateur :

**09 - ANIMATIONS SKELETON PHYSICS**

Il couvre les étapes 410 et 411 :

- vérification FOMOD combat / dodge avant Pandora ;
- première génération Pandora contrôlée ;
- levée de la vigilance “Pandora installé mais non généré”.

---

# Étape 410 — Vérification FOMOD combat / dodge avant Pandora

## Objectif

Lever les vigilances principales héritées de l’étape 409 avant toute génération Pandora ou poursuite du module combat.

## Actions effectuées

- Vérification MO2 effectuée.
- Mods combat / dodge présents et cochés.
- Plugins associés cochés.

## TK Dodge RE - Script Free

État vérifié :

- installation minimale ;
- aucune option FOMOD cochée ;
- option standalone non activée.

## Precision - Accurate Melee Collisions

État vérifié :

- option **TK Dodge or Ultimate Combat** sélectionnée ;
- option **TK Dodge RE** grisée ;
- choix accepté car le descriptif FOMOD indique de sélectionner cette option si TK Dodge RE est utilisé.

## Outils non lancés

- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.
- Mods `- FR` : non activés.

## Test effectué

- SKSE lancé jusqu’au menu principal : OK.
- Aucun master manquant : OK.
- Aucun message DLL manquant : OK.
- Overwrite : vide.

## Impact compteur plugins

- Avant étape : 106 ESP + ESM non-light.
- Après étape : 106 ESP + ESM non-light.
- Variation : 0.

## Décision

Aucun nouveau mod installé à l’étape 410.

Ne pas dépendre des fichiers Nolvus Awakening locaux pour les réglages TK Dodge RE.

Créer des réglages SKYFORGE propres, inspirés de la logique Nolvus Awakening mais adaptés au modpack.

La réinstallation de Nolvus Awakening reste différée, uniquement si un besoin de comparaison de paramètres avancés apparaît.

## Verdict

Étape 410 validée.

---

# Étape 411 — Première génération Pandora contrôlée

## Objectif

Générer pour la première fois les comportements via Pandora Behaviour Engine Plus après validation des FOMOD TK Dodge RE et Precision à l’étape 410.

## Lancement initial

Pandora a été lancé depuis MO2.

Premier résultat incorrect :

- Pandora ne détectait que Pandora Base ;
- résultat : 0 animation ajoutée.

## Diagnostic

Le chemin **Skyrim Data** configuré dans Pandora était incorrect.

Pandora ne devait pas pointer vers le Data Steam original si celui-ci n’est pas le Data réellement utilisé par l’instance MO2 portable isolée de SKYFORGE.

## Correction effectuée

- Champ **Skyrim Data** corrigé vers le Data réellement utilisé par l’instance SKYFORGE / MO2 portable isolée.
- Champ **Output Folder** conservé vers le mod dédié :

```text
SKYFORGE - Pandora Output
```

## Relance Pandora après correction

Patchers détectés :

- Payload Interpreter ;
- Precision ;
- TK Dodge RE / Ultimate Combat ;
- True Directional Movement - 360 Horse Archery ;
- True Directional Movement - Headtracking ;
- True Directional Movement - Procedural Leaning ;
- Pandora Base ;
- FNIS_XPMSE_List.

## Génération réussie

Résultat :

- 42 animations ajoutées.

## Vérification du mod Output

Le mod suivant contient désormais les fichiers générés :

```text
SKYFORGE - Pandora Output
```

Fichiers / dossiers présents :

- `meshes` ;
- `Pandora_Engine` ;
- `SKSE` ;
- `animationdatasinglefile.txt` ;
- `animationsetdatasinglefile.txt` ;
- `ActiveMods.json` ;
- `PreviousOutput.txt` ;
- `Engine.log`.

## Test effectué

- SKSE lancé jusqu’au menu principal : OK.
- Aucun message DLL : OK.
- Aucun master manquant : OK.
- Tous les plugins cochés : OK.
- Overwrite : vide.

## Outils non lancés

- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.
- Mods `- FR` : non activés.

## Impact compteur plugins

- Avant étape : 106 ESP + ESM non-light.
- Après étape : 106 ESP + ESM non-light.
- Variation : 0.

## Vigilance levée

La vigilance suivante est levée :

- Pandora installé mais non généré.

## Note importante

Dans l’environnement SKYFORGE actuel, Pandora doit pointer vers le Data réellement utilisé par l’instance MO2 portable isolée.

Le champ **Skyrim Data** doit pointer vers le Data utilisé par SKYFORGE.

Le champ **Output Folder** doit pointer vers :

```text
SKYFORGE - Pandora Output
```

## Vigilances restantes

- BodySlide Output non généré.
- XPMSSE FOMOD à revoir plus tard avant SexLab / animations avancées.
- Smooth TK Dodge Attack à confirmer par test en jeu limité.
- LeveledList Crash Fix AE + 1.5 à vérifier hors urgence.

## Verdict

Étape 411 validée.

La première génération Pandora est réussie et documentée.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 411 — Première génération Pandora contrôlée**.
- Pandora : généré avec succès.
- Pandora Output : actif dans le mod dédié `SKYFORGE - Pandora Output`.
- Compteur ESP + ESM non-light global : **106**.
- Overwrite : vide.
- BodySlide Output : non généré.
- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
