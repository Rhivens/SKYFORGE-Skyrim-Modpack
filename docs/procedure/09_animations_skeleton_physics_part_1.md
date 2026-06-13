# SKYFORGE — 09 - ANIMATIONS SKELETON PHYSICS — Part 1

## Objet du fichier

Ce fichier ouvre officiellement le séparateur :

**09 - ANIMATIONS SKELETON PHYSICS**

Il commence à l'étape 401, car CBPC est installé dans le séparateur 09 même si cette étape reste liée techniquement au choix CBBE 3BA effectué dans le bloc 08.3.

Cette séparation est volontaire afin d'éviter toute ambiguïté pour les reprises futures et pour l'intendant SKYFORGE.

---

# Étape 401 — Ajout CBPC pour 3BA

## Objectif

Installer le moteur physique CBPC, nécessaire à la configuration 3BA choisie en **SMP and CBPC (Lite)**.

## Contexte

Lors de l'étape 390, **CBBE 3BA (3BBB)** a été installé avec une configuration combinant :

- FSMP / HDT-SMP pour la physique SMP ;
- CBPC pour une partie des collisions et physiques corporelles.

À ce moment-là, seul **FSMP** était déjà présent dans le séparateur 09. Il fallait donc ajouter CBPC pour que la base body/physics soit cohérente.

## Mod installé

### CBPC - Physics with Collisions for SSE and VR

- Source : Nexus
- Rôle : moteur physique/collisions utilisé par 3BA
- Plugin : aucun plugin non-light ajouté
- Placement : **09 - ANIMATIONS SKELETON PHYSICS**

Note MO2 recommandée :

```text
MOTEUR PHYSIQUE CBPC - requis par 3BA SMP+CBPC Lite - SE 1.5.97
```

## Fichier optionnel non installé

Non installé :

- **3B Breast-Butt Bounce Configs for 3BA-BHUNP-COCO**

Décision : différé.

Raison : ce fichier modifie les configurations de bounce selon les formes de corps. Il vaut mieux attendre :

- choix final des presets BodySlide ;
- génération BodySlide ;
- intégration OBody NG ;
- tests en jeu.

Note MO2 recommandée :

```text
MAIN FILE ONLY - optional bounce configs différés après BodySlide/OBody
```

## Choix FOMOD CBPC

Choix observé/validé :

- FPS Selection / Bounce Config : **120 fps** sélectionné si Skyrim est limité/configuré autour de 120 FPS.

Note recommandée :

```text
CBPC MAIN FILE ONLY - FPS CONFIG 120 SI SKYRIM LIMITE A 120 - BOUNCE CONFIGS DIFFERES
```

## Ordre dans le séparateur 09

État actuel recommandé du séparateur :

```text
09 - ANIMATIONS SKELETON PHYSICS

FSMP / Faster HDT-SMP
CBPC - Physics with Collisions
```

## Précision importante

**XPMSSE n'est pas encore installé.**

C'est normal à ce stade, mais il devra être intégré plus tard avant les blocs :

- animations ;
- skeleton avancé ;
- SexLab ;
- systèmes corporels avancés.

Note recommandée sur le séparateur 09 :

```text
XPMSSE NON ENCORE INSTALLE - à intégrer avant animations/SexLab
```

## Validation test

Résultat communiqué :

- SKSE/menu : OK
- Masters manquants : aucun
- Plugins cochés : OK
- Overwrite : vide
- Compteur ESP/ESM non-light : 102

## Décision finale étape 401

Étape 401 validée.

CBPC est maintenant installé proprement comme moteur physique complémentaire à FSMP pour la configuration 3BA. Aucun fichier optionnel de bounce n'a été ajouté, aucun BodySlide n'a été généré, et le compteur non-light reste stable à 102.

---

# État final du fichier

- Dernière étape documentée ici : **Étape 401**
- Séparateur officiellement ouvert : **09 - ANIMATIONS SKELETON PHYSICS**
- Compteur ESP + ESM non-light : **102**
- Overwrite : vide
- BodySlide Output : non généré
- LOOT : non lancé
- DynDOLOD / LOD : non générés
