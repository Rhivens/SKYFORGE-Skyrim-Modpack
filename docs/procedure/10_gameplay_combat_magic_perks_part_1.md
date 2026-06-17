# SKYFORGE — 10 - GAMEPLAY COMBAT MAGIC PERKS — Part 1

## Objet du fichier

Ce fichier ouvre officiellement le séparateur :

**10 - GAMEPLAY COMBAT MAGIC PERKS**

Il commence à l’étape 408 avec l’installation de **Valhalla Combat**, puis documente la partie gameplay/combat de l’étape 409 avec **Comprehensive Attack Rate Patch - SKSE**.

Référence de décision :

- Combat / dodge / animations combat : référence **Nolvus**.
- NSFW / SexLab / defeat / slavery / prostitution : référence **Nefaram**.

---

# Étape 408 — Valhalla Combat

## Objectif

Installer un premier overhaul combat majeur issu de la logique combat Nolvus.

## Mod ajouté

- Valhalla Combat

## Lien

- https://www.nexusmods.com/skyrimspecialedition/mods/64741

## Placement

Valhalla Combat a été déplacé dans le bon séparateur :

- 10 - GAMEPLAY COMBAT MAGIC PERKS

Ordre validé autour de la transition 09 / 10 :

1. [09 - ANIMATIONS SKELETON PHYSICS]
2. TK Dodge SE
3. Sound For TK Dodge SE
4. TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD
5. [10 - GAMEPLAY COMBAT MAGIC PERKS]
6. Valhalla Combat

## Impact plugins

- Avant étape : 105 ESP + ESM non-light
- Après étape : 106 ESP + ESM non-light
- Variation : +1

## Tests

- SKSE / menu principal : OK
- Aucun master manquant : OK
- Plugins cochés : OK
- Overwrite : vide

## État inchangé

- LOOT : non lancé
- BodySlide Output : non généré
- DynDOLOD / LOD : non générés
- Pandora : non lancé

## Verdict

Étape 408 validée. Valhalla Combat est installé dans le bloc 10. Compteur ESP + ESM non-light : 106.

---

# Étape 409 — Mini-pack combat Nolvus léger côté gameplay

## Objectif

Ajouter la partie gameplay/combat du mini-pack combat Nolvus léger après TK Dodge / Valhalla, sans lancer Pandora.

## Mod ajouté dans le séparateur 10

- Comprehensive Attack Rate Patch - SKSE

## Lien

- Comprehensive Attack Rate Patch - SKSE : https://www.nexusmods.com/skyrimspecialedition/mods/89042

## Placement

- Comprehensive Attack Rate Patch - SKSE : bloc 10, sous Valhalla Combat

## Note liée à l’étape 409

L’autre mod ajouté à l’étape 409, **Smooth TK Dodge Attack**, appartient au séparateur 09 et est documenté dans :

```text
docs/procedure/09_animations_skeleton_physics_part_1.md
```

## Impact plugins

- Avant étape : 106 ESP + ESM non-light
- Après étape : 106 ESP + ESM non-light
- Variation : 0

## Tests

- SKSE / menu principal : OK
- Aucun master manquant : OK
- Plugins cochés : OK
- Overwrite : vide

## État inchangé

- LOOT : non lancé
- BodySlide Output : non généré
- DynDOLOD / LOD : non générés
- Pandora : non lancé

## Verdict

Étape 409 validée. Comprehensive Attack Rate Patch - SKSE est installé dans le bloc 10 sous Valhalla Combat. Compteur ESP + ESM non-light : 106.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 409**
- Séparateur officiellement ouvert : **10 - GAMEPLAY COMBAT MAGIC PERKS**
- Mods installés dans ce séparateur :
  - Valhalla Combat
  - Comprehensive Attack Rate Patch - SKSE
- Compteur ESP + ESM non-light global : **106**
- Overwrite : vide
- BodySlide Output : non généré
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- Pandora : non lancé
