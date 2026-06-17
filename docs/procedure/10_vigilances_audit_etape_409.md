# Vigilances après audit — Étape 409

## Contexte

Ce document fige les vigilances issues de l’audit croisé effectué après l’étape 409.

L’objectif est de vérifier la cohérence de l’état SKYFORGE avec :

- le snapshot MO2 complet étape 409 ;
- la logique Nolvus Awakening ;
- la logique Nefaram ;
- les instructions officielles SKYFORGE.

## État audité

- **Dernière étape validée :** Étape 409 — Mini-pack combat Nolvus léger
- **Compteur ESP + ESM non-light :** 106
- **SKSE / menu principal :** OK
- **Masters manquants :** aucun
- **Plugins cochés :** OK
- **Overwrite :** vide
- **LOOT :** non lancé
- **Pandora :** installé / configuré, mais non généré
- **BodySlide Output :** non généré
- **DynDOLOD / LOD :** non générés

## Verdict général

L’état étape 409 est globalement cohérent avec la stratégie SKYFORGE.

Aucune erreur certaine n’a été détectée.

Les points relevés sont des vigilances, des vérifications manuelles ou des décisions différées.

## Cohérence stratégique

### Nolvus Awakening

La logique Nolvus Awakening reste la référence pour :

- combat ;
- dodge ;
- gameplay ;
- UI / HUD ;
- graphismes ;
- architecture ;
- villes ;
- lieux extérieurs ;
- quêtes non adultes.

Les modules installés jusqu’à l’étape 409 restent cohérents avec cette orientation.

### Nefaram

La logique Nefaram reste la référence pour :

- body compatible adulte ;
- CBBE ;
- 3BA / 3BBB ;
- compatibilité SexLab future ;
- TNG ;
- physics ;
- ENB Manager futur ;
- systèmes adultes différés.

Les modules body / physics installés jusqu’à l’étape 409 restent cohérents avec cette orientation.

## Vigilances critiques

### Pandora non généré

Pandora Behaviour Engine Plus est installé et configuré, mais aucune génération n’a encore été lancée.

Conséquence :

- les animations ;
- le dodge ;
- les comportements combat ;
- les comportements liés aux futurs mods d’animation ;

ne doivent pas encore être considérés comme validés en jeu.

### BodySlide Output non généré

CBBE et 3BA / 3BBB sont installés, mais aucun output BodySlide n’a encore été généré.

Conséquence :

- le body final n’est pas figé ;
- les presets ne sont pas encore validés ;
- OBody NG reste différé ;
- Unique Player / Unique Character reste différé.

### Precision + TK Dodge RE

Precision est installé avec compatibilité FOMOD conservée sur “None”.

TK Dodge RE est installé, mais la compatibilité Precision / TK Dodge RE reste à revoir.

À vérifier avant validation réelle du bloc combat.

### XPMSSE

XPMSSE est installé avec un FOMOD minimal.

À recontrôler avant :

- SexLab ;
- animations avancées ;
- styles d’armes ;
- modules adultes ;
- comportements physiques avancés.

### LeveledList Crash Fix

Présence à vérifier :

- LeveledList Crash Fix AE ;
- LeveledList Crash Fix for Skyrim 1.5.

Vérifier manuellement l’absence de doublon DLL ou de recouvrement fonctionnel.

## Vigilances simples

### Smooth TK Dodge Attack

Le mod liste Dynamic Animation Replacer comme requirement.

SKYFORGE utilise Open Animation Replacer.

À vérifier en test réel afin de confirmer que l’équivalence OAR couvre correctement le besoin.

### S.L.A.C.K.

Surveiller la stabilité des cosaves.

Aucune erreur détectée à ce stade.

### Composants ENB / lighting avancés

À surveiller car installés tôt :

- KiLoader ;
- Light Placer ;
- Terrain Helper CS-ENB ;
- ENB Terrain Blending Fix.

Ces éléments restent cohérents avec la logique graphique / ENB future, mais devront être revalidés lors du bloc ENB.

### UI / HUD

Plusieurs entrées restent marquées :

- à réinstaller ;
- à configurer ;
- à revoir plus tard.

Le module UI reste fonctionnel au menu, mais non finalisé.

### Compteur plugins

Le compteur actuel est confortable :

- **106 ESP + ESM non-light**

La surveillance doit continuer à chaque ajout de plugin.

## Points à vérifier manuellement par Fabien

Avant de poursuivre trop loin :

- vérifier le FOMOD TK Dodge RE ;
- vérifier le FOMOD Precision après présence de TK Dodge RE ;
- vérifier le FOMOD XPMSSE ;
- contrôler les logs SKSE après prochain test menu ;
- maintenir Overwrite vide hors logs ou fichiers attendus.

## Règles de formulation à conserver

Lors des futures mises à jour GitHub :

- remplacer les mentions structurantes “Nolvus” par **“Nolvus Awakening”** ;
- indiquer clairement que **Nolvus Ascension n’est pas utilisé**, sauf demande explicite ;
- rappeler que les mods terminés par **“- FR”** sont des traductions personnelles volontairement décochées ;
- rappeler que **Pandora est le générateur retenu**, mais que la génération est différée ;
- rappeler que **BodySlide Output est différé**, donc que le body final n’est pas figé.

## Interdits temporaires avant étape 410

Avant reprise de l’installation :

- ne pas lancer LOOT ;
- ne pas générer DynDOLOD / LOD ;
- ne pas activer les traductions “- FR” ;
- ne pas installer SexLab ;
- ne pas installer defeat / défaite ;
- ne pas installer slavery ;
- ne pas installer prostitution ;
- ne pas installer prison ;
- ne pas empiler un autre overhaul combat majeur ;
- ne pas remplacer la base CBBE / 3BA par HIMBO, BHUNP, UBE ou autre logique body ;
- ne pas passer sur Nemesis comme générateur principal.

## Conclusion

L’étape 409 est validée et cohérente.

Les points listés ci-dessus ne sont pas des erreurs bloquantes, mais des vigilances à garder visibles avant l’étape 410.

La suite devra reprendre prudemment à partir de cet état, sans installation massive ni changement de stratégie.
