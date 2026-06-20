# SKYFORGE — Load Order MO2 panneau gauche — Étape 509

Snapshot complet du panneau gauche MO2 après validation de l'étape 509.

Ce fichier est destiné à devenir la référence courante anti-doublon après insertion manuelle du texte brut du panneau gauche MO2 par Fabien.

## Règles de lecture

- Ce fichier remplace le snapshot étape 480 comme référence courante anti-doublon une fois le texte brut MO2 collé manuellement.
- Le snapshot étape 480 devient alors un jalon historique.
- Les mods se terminant par `- FR` sont présents mais décochés, sauf indication contraire.
- Les suffixes de suivi temporaires dans les noms MO2, comme `FOMOD A REVOIR PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `A REINSTALLER PLUS TARD`, `DECOCHE`, `RESERVE`, etc., sont des marqueurs de suivi documentés dans `docs/procedure/01_regles_mo2_skyforge.md`.
- Les séparateurs vides sont normaux : ils préparent les futurs blocs SKYFORGE.
- Ce snapshot concerne le panneau gauche MO2, pas le compteur ESP/ESM non-light du panneau droit.

## État associé

- Dernière étape validée : 509 — Mythos SE Redux exclu définitivement
- Prochaine étape attendue : 510
- Module en cours : `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`
- Compteur ESP + ESM non-light : 128
- Overwrite : vide
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- BodySlide Output : non généré
- Pandora : généré depuis l'étape 411, Output actif ; non relancé sauf indication contraire

## Notes de changement depuis le snapshot étape 480

Changements principaux attendus dans ce snapshot :

- enrichissement du bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` avec les étapes 481 à 490 ;
- ouverture et remplissage initial du bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` avec les étapes 491 à 509 ;
- ajout des followers personnalisés et patches associés validés jusqu'à l'exclusion définitive de Mythos SE Redux ;
- maintien du reste du load order globalement stable par rapport au snapshot étape 480.

## Snapshot complet du panneau gauche MO2

```txt
COPIER LE TEXTE BRUT DU LOAD ORDER MO2 ICI
```

---

## Décisions de placement / notes post-snapshot

- Snapshot créé avec emplacement manuel réservé pour le texte brut du load order MO2, conformément à la règle SKYFORGE visant à éviter les blocages du connecteur GitHub sur les noms techniques de mods.
- Après collage manuel du texte brut par Fabien, ce fichier deviendra la référence courante anti-doublon pour la suite du projet.
- Le fichier `docs/procedure/00_resume_etat_actuel.md` devra ensuite être mis à jour pour déclarer ce snapshot comme référence courante.
