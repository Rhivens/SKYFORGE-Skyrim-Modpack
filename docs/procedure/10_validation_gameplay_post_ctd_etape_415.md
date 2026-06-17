# Étape 415 — Validation gameplay post-CTD

## Objectif

Documenter officiellement le test gameplay effectué après la stabilisation des étapes 412 à 414, sans ajouter de nouveau mod et sans lancer d’outil externe.

Cette étape sert à confirmer que le profil SKYFORGE reste stable après :

- la génération Pandora réussie ;
- l’isolation du mod fautif du crash post-Pandora ;
- le nettoyage d’état ;
- la restauration des options EngineFixes ;
- l’activation correcte de CrashLogger SSE AE VR avec PDB support 1.5.97.

## Actions effectuées

- Test gameplay post-stabilisation effectué.
- Profil lancé via SKSE / MO2.
- Aucun nouveau mod installé.
- Aucun outil de tri ou de génération lancé.
- Mods `- FR` laissés décochés volontairement.
- Mod fautif du CTD étape 413 conservé décoché / différé.

## Résultat du test gameplay

Le test gameplay post-stabilisation est validé.

Points confirmés :

- pas de crash reproduit pendant le test ;
- Pandora Output actif ;
- TK Dodge fonctionnel ;
- True Directional Movement fonctionnel ;
- mouvements et caméra cohérents ;
- pas de T-pose / A-pose constatée ;
- Overwrite vide.

## Vigilance levée

La vigilance suivante est levée :

- **Smooth TK Dodge Attack :** confirmé en jeu dans le cadre du test limité post-stabilisation.

## Vigilances restantes

Les vigilances suivantes restent ouvertes :

- **BodySlide Output :** non généré.
- **XPMSSE :** FOMOD à revoir plus tard avant SexLab / animations avancées / styles d’armes.
- **LeveledList Crash Fix AE + 1.5 :** à vérifier hors urgence.
- **LOOT :** non lancé.
- **DynDOLOD / LOD :** non générés.
- **Mods `- FR` :** toujours décochés volontairement.
- **Mod fautif CTD étape 413 :** à garder décoché / différé.

## Outils non lancés

- LOOT : non lancé.
- DynDOLOD / LOD : non générés.
- BodySlide : non lancé.

## Impact compteur plugins

- Avant étape : 106 ESP + ESM non-light.
- Après étape : 106 ESP + ESM non-light.
- Variation : 0.

## Décision

Aucune installation n’a été effectuée à l’étape 415.

Cette étape est uniquement documentaire et valide le comportement gameplay post-CTD avant reprise de l’installation par petits blocs.

## Verdict

Étape 415 validée.

Le profil SKYFORGE reste stable après le diagnostic CTD et la génération Pandora.
