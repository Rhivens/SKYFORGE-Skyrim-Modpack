# SKYFORGE — 09 - ANIMATIONS SKELETON PHYSICS — Part 3

## Objet du fichier

Ce fichier poursuit la documentation du séparateur :

**09 - ANIMATIONS SKELETON PHYSICS**

Il documente l’étape **425**, ajoutée pendant le module gameplay / combat mais placée dans le séparateur 09 pour cohérence MO2.

---

# Étape 425 — No Spinning Death Animation Merged LITE

## Objectif

Ajouter un correctif léger d’animation de mort issu de Nolvus Awakening, sans relancer Pandora.

## Mod installé

- `No Spinning Death Animation Merged LITE`

## Origine

- Nolvus Awakening

## Source

- Nexus : https://www.nexusmods.com/skyrimspecialedition/mods/33597

## Fichier installé

- `No Spinning Death Animation Merged LITE`
- Version : 1.311

## Rôle SKYFORGE

Supprime les animations de mort avec rotation excessive.

La version **Merged LITE** inclut aussi la suppression de certaines animations problématiques de mort des dragons et rieklings.

## Placement MO2

- Séparateur : `09 - ANIMATIONS SKELETON PHYSICS`
- Placement : sous `SKYFORGE - Pandora Output`

## Test effectué

Type de test : **Menu atteint**

Résultat :

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL
- Aucun master manquant
- Tous les plugins cochés
- Aucun crash avant menu
- Overwrite vide
- Compteur ESP + ESM non-light : 108

## Impact compteur

- Avant étape : 108
- Après étape : 108
- Variation : 0

## Outils non relancés

- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.
- Pandora : non relancé.
- Mods `- FR` : non activés.

## Verdict

Étape 425 validée.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 425 — No Spinning Death Animation Merged LITE**.
- Séparateur : **09 - ANIMATIONS SKELETON PHYSICS**.
- Pandora Output : actif, non régénéré pendant cette étape.
- Compteur ESP + ESM non-light global : **108**.
- Overwrite : vide.
