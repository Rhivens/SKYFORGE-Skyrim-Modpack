# Animations, skeleton & physics — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture et validation provisoire du module **09 - ANIMATIONS SKELETON PHYSICS**.

Périmètre : étapes **659 à 663**.

Important : ces étapes sont des validations courtes sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 659 — Ouverture du bloc 09

### État constaté

Le bloc 09 contient déjà :

- `Faster HDT-SMP`
- `CBPC - Physics with Collisions`
- `XP32 Maximum Skeleton Special Extended - XPMSSE`
- `Auto Skeleton Patch - Universal Behaviour Runtime`
- `Open Animation Replacer`
- `SKYFORGE - Open Animation Replacer Output`
- `Animation Motion Revolution`
- `Payload Interpreter`
- `Paired Animation Improvements`
- `Pandora Behaviour Engine v4.3.1-beta`
- `SKYFORGE - Pandora Output`
- `No Spinning Death Animation Merged LITE`
- `True Directional Movement`
- `Precision`
- `TK Dodge SE`
- `TK Dodge RE - Script Free`
- `Sound For TK Dodge SE`
- `Smooth TK Dodge Attack`

### Décision

- Garder / ouverture validée provisoirement.
- Pas d’action MO2 immédiate.
- Pandora Output déjà présent.
- Pandora non relancé.
- Bloc délicat : skeleton / physics / animations / Pandora doivent rester sous contrôle strict.

### Points de vigilance

- XPMSSE : FOMOD à vérifier plus tard.
- CBPC : configuration FPS 120 seulement si Skyrim est bien limité à 120 FPS.
- Paired Animation Improvements : patches à revoir.
- Precision : lien avec TK Dodge RE à vérifier plus tard.
- TK Dodge RE : FOMOD à revoir plus tard.

---

## Étape 660 — Validation courte du socle physics / skeleton

### Pack concerné

- `Faster HDT-SMP`
- `Faster HDT-SMP - Generated Config`
- `FSMPM - The FSMP MCM`
- `CBPC - Physics with Collisions for SSE and VR`
- `CBPC - Generated Config - 120 FPS`
- `XP32 Maximum Skeleton Special Extended - XPMSSE - FOMOD A REVOIR PLUS TARD`
- `Auto Skeleton Patch - Universal Behaviour Runtime`

### Plugins / éléments actifs relevés

- `FSMPM - The FSMP MCM.esp`
- `XPMSE.esp`

### Décision

- Garder / validation provisoire.
- Le socle est cohérent avec la méthode SKYFORGE Body / SexLab future : CBBE / 3BA, physics CBPC + Faster HDT-SMP, skeleton XPMSSE, compatibilité BodySlide / RaceMenu morphs future.

### Ne pas faire maintenant

- Ne pas relancer Pandora.
- Ne pas générer BodySlide.
- Ne pas réinstaller XPMSSE.
- Ne pas toucher aux configs CBPC / FSMP.
- Ne pas modifier l’ordre du skeleton.

### Dettes utiles

- Revoir le FOMOD XPMSSE plus tard.
- Vérifier que la limite FPS Skyrim correspond bien à la config CBPC - Generated Config - 120 FPS.
- Reprendre physics / collisions au moment du vrai bloc Body + outfits + SexLab.
- Refaire BodySlide seulement quand les bodies et outfits seront stabilisés.

---

## Étape 661 — Validation courte OAR / Pandora / animation framework

### Pack concerné

- `Open Animation Replacer`
- `Open Animation Replacer - IED Conditions`
- `SKYFORGE - Open Animation Replacer Output`
- `Animation Motion Revolution`
- `Payload Interpreter`
- `Paired Animation Improvements`
- `Paired Animation Improvements - Patch A REVOIR PLUS TARD`
- `Pandora Behaviour Engine v4.3.1-beta`
- `SKYFORGE - Pandora Output`

### Décision

- Garder / validation provisoire.
- OAR reste le framework d’animations moderne.
- AMR / Payload Interpreter restent les dépendances animation.
- Pandora reste le générateur principal.
- SKYFORGE - Pandora Output reste la référence actuelle.
- Aucun relancement nécessaire tant qu’on ne change pas les animations.

### Ne pas faire maintenant

- Ne pas relancer Pandora.
- Ne pas supprimer `SKYFORGE - Pandora Output`.
- Ne pas régénérer OAR Output.
- Ne pas revoir les patches Paired Animation Improvements maintenant.
- Ne pas ajouter de packs d’animations tant que le socle n’est pas clôturé.

### Dette utile

- Revoir `Paired Animation Improvements - Patch` plus tard.
- Relancer Pandora uniquement après ajout / retrait / modification de mods d’animations ou comportements.
- Surveiller Overwrite si Pandora est relancé plus tard.

---

## Étape 662 — Validation courte mouvement / combat animation base

### Pack concerné

- `No Spinning Death Animation Merged LITE`
- `True Directional Movement`
- `Precision`
- `TK Dodge SE`
- `TK Dodge RE - Script Free`
- `Sound For TK Dodge SE`
- `Smooth TK Dodge Attack`

### Décision

- Garder / validation provisoire.
- Le pack est cohérent avec la logique combat / mouvement SKYFORGE : TDM, Precision, TK Dodge RE, Sound / Smooth TK Dodge, No Spinning Death Animation.

### Ne pas faire maintenant

- Ne pas relancer Pandora.
- Ne pas réinstaller TK Dodge RE.
- Ne pas toucher au FOMOD.
- Ne pas modifier Precision maintenant.
- Ne pas tester en combat réel tant qu’on est encore en validation de blocs.

### Dettes utiles

- `TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD`.
- Vérifier plus tard compatibilité Precision / TK Dodge / animations combat.
- Tester esquive + hit detection en jeu seulement quand le bloc combat sera stabilisé.
- Relancer Pandora uniquement si animations / comportements changent.

---

## Étape 663 — Clôture provisoire du bloc 09

### Synthèse

Le bloc 09 est en place avec les familles principales :

- physics : Faster HDT-SMP, FSMPM, CBPC ;
- skeleton : XPMSSE, Auto Skeleton Patch ;
- animation framework : Open Animation Replacer, AMR, Payload Interpreter, Paired Animation Improvements ;
- génération : Pandora Behaviour Engine + SKYFORGE - Pandora Output ;
- mouvement / combat base : No Spinning Death Animation, True Directional Movement, Precision, TK Dodge SE / RE.

### Décision

- Clôture provisoire validée.
- Aucune action active faite dans MO2 pendant les étapes 659 à 663.
- Ne rien relancer maintenant.

### Ne pas faire maintenant

- Ne pas relancer Pandora.
- Ne pas générer BodySlide.
- Ne pas modifier XPMSSE.
- Ne pas réinstaller TK Dodge RE.
- Ne pas toucher aux configs CBPC / FSMP.
- Ne pas lancer LOOT.
- Ne pas lancer DynDOLOD / LOD.

### État final bloc 09

- SKSE / menu principal : OK sur dernier test global.
- Masters manquants : aucun.
- Messages DLL : aucun.
- Plugins cochés : oui.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **138**.
- BodySlide Output : non généré.
- Pandora : non relancé.
