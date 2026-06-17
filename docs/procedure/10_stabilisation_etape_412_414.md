# SKYFORGE — Stabilisation après génération Pandora — Étapes 412 à 414

## Contexte

Après la première génération Pandora validée à l’étape 411, le jeu démarrait correctement et les fonctions de déplacement / dodge semblaient opérationnelles.

Un crash apparaissait cependant après un court délai en cellule Skyrim Unbound.

## Étape 412 — Diagnostic initial

Le problème n’a pas été attribué directement à :

- Pandora Output ;
- TK Dodge RE ;
- True Directional Movement ;
- RaceMenu.

Un outil de crash logging temporaire a été utilisé afin d’obtenir un rapport exploitable.

Le système de crash logging final a ensuite été corrigé :

- CrashLogger SSE AE VR actif ;
- PDB support 1.5.97 actif ;
- outil temporaire supprimé.

## Étape 413 — Isolation du coupable

Les rapports ont orienté le diagnostic vers une chaîne liée à :

- New Gnisis Cornerclub ;
- JK's New Gnisis Cornerclub ;
- un patch de mobilier Dunmeri ;
- Lux ;
- Distinct Interiors ;
- Snazzy Furniture and Clutter Overhaul ;
- Skyrim Unbound.

Le mod fautif confirmé a été décoché :

```text
Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD
```

## Étape 414 — Nettoyage

Actions finales :

- Overwrite vidé ;
- fichiers de configuration CrashLogger rangés dans un mod local dédié ;
- CrashLogger final actif ;
- outil temporaire supprimé ;
- options EngineFixes restaurées ;
- test après restauration : pas de crash constaté.

Options EngineFixes restaurées :

```ini
bFormCaching = true
bTreeLodReferenceCaching = true
```

## Outils toujours non lancés

- LOOT ;
- DynDOLOD / LOD ;
- BodySlide.

## État final

- Étapes 412 à 414 validées.
- Crash isolé.
- Coupable confirmé : `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`.
- Mod fautif : décoché / différé.
- Profil stable restauré.
- CrashLogger actif.
- Overwrite vide.
- EngineFixes restauré.
- Pandora Output actif.
- Compteur ESP + ESM non-light : **106**.

## Vigilances restantes

- BodySlide Output non généré.
- XPMSSE FOMOD à revoir plus tard avant animations avancées.
- Smooth TK Dodge Attack à confirmer en jeu.
- LeveledList Crash Fix AE + 1.5 à vérifier hors urgence.
- Mods `- FR` toujours décochés volontairement.
