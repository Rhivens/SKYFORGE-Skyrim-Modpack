# SexLab core adult frameworks — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB, fichier LoversLab ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture, préparation et installation du premier noyau **SexLab Core 13-A**.

Périmètre : étapes **674 à 685**.

---

## Étape 674 — Ouverture `[13 - SEXLAB CORE ADULT FRAMEWORKS]`

### Verdict

Bloc 13 quasiment vide dans le snapshot initial.

### État constaté

Dans le panneau gauche actuel, le bloc contient seulement :

- `[13 - SEXLAB CORE ADULT FRAMEWORKS]`
- `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB`

Puis on passe directement à :

- `[13.1 - SEXLAB ANIMATIONS ADULT RESOURCES]`
- `[14 - DEVIOUS DEFEAT SLAVERY PROSTITUTION]`
- `[15 - ARMORS CLOTHES OUTFITS NSFW]`

### Décision

- Étape 674 = ouverture / constat uniquement.
- Ne rien installer immédiatement.
- Préparer d’abord un plan SexLab 1.5.97.

---

## Étape 675 — Préparation du plan SexLab Core 1.5.97

### Verdict

Plan préparé, aucune installation.

### Objectif du premier pack SexLab

Installer plus tard un SexLab Core minimal, sans encore toucher à :

- Devious Devices ;
- defeat / slavery / prostitution ;
- créatures / MNC ;
- gros packs d’animations ;
- prison / bondage avancé ;
- patches NSFW lourds.

### Pack 13-A recommandé — Core minimal

À préparer dans cet ordre :

1. SexLab Framework SE compatible Skyrim SE 1.5.97.
2. SexLab Animation Loader / SLAL SE.
3. ZaZ Animation Pack SE.
4. Aroused / SLSF, à décider prudemment.

### Dépendances déjà en place dans SKYFORGE

- SKSE 2.0.20.
- Address Library 1.5.97.
- PapyrusUtil SE.
- JContainers SE.
- XPMSSE.
- CBBE / 3BA direction officielle.
- Faster HDT-SMP / CBPC.
- RaceMenu.
- BodySlide installé mais Output non généré.
- Pandora présent mais non relancé.

---

## Étape 676 — Inventaire SexLab Core depuis Nefaram

### Verdict

Inventaire de départ établi, mais installation différée jusqu’à vérification des archives exactes.

### Référence Nefaram observée

La section SexLab Frameworks de Nefaram contient notamment :

- SexLab Framework.
- SexLab Animation Remover.
- Sexlab Framework Sound Replacer AIO.
- NoOverpenetration.
- Sexlab - Cum Overlays.
- SCOE Texture Set.
- 3BA SexLab SOS Strapon.
- SLWidgets.
- ZaZ Animation Pack.
- Devious Devices for SE-AE-VR.
- SexLab Separate Orgasm.
- SLO Aroused NG.
- Sex Lab - Sexual Fame Framework SE.
- Patched SE SL TOOLS Updated.
- Simple Slavery Plus Plus / Rebuild.
- SLAL.
- BakaFactory’s SLAL Pack.
- Creature Framework.
- MoreNastyCrittersSE.
- Devious Devices NG.
- SLATE_SE.
- SLAnimStageLabels.
- ZAZ NPC Fixer.

### Décision SKYFORGE

- Ne pas reprendre tout le bloc Nefaram d’un coup.
- Premier pack installable recommandé : SexLab Core minimal, sans Devious, sans créatures, sans slavery / defeat.

### Pack 13-A à vérifier

- SexLab Framework.
- SLAL.
- ZaZ Animation Pack.
- SLSF / SexLab Sexual Fame Framework SE.
- Aroused différé ou à vérifier strictement.

---

## Étape 677 — SexLab Framework : archive validée

### Verdict

Archive cible pour SKYFORGE 1.5.97 :

- `SexLabFrameworkSE_v163.7z`

### Décision

- Garder comme candidat installable.
- Refuser les archives AE / GOG / 1.6.x pour SKYFORGE.

### Règle de version

- Skyrim SE 1.5.97 : `SexLabFrameworkSE_v163.7z`.
- Skyrim AE 1.6.1130 : non retenu.
- Skyrim AE 1.6.1170 : non retenu.
- GOG 1.6.1179 : non retenu.

### FNIS / Pandora

- La page SexLab parle de FNIS.
- SKYFORGE utilise Pandora comme générateur principal.
- Décision : ne pas lancer FNIS ; ne pas relancer Pandora maintenant.

### Plugin attendu

- `SexLab.esm`.

Impact compteur prévisionnel : +1 non-light.

---

## Étape 678 — SLAL / SexLab Animation Loader : candidat validé sous réserve

### Verdict

SLAL 1.6 est cohérent pour SKYFORGE, mais son usage dépendra du générateur d’animations.

### Infos utiles

Dépendances utilisateur indiquées :

- SexLab Framework 1.63+.
- JContainers.
- FNIS.

Dans SKYFORGE :

- SexLab cible : SexLabFrameworkSE_v163.7z.
- JContainers déjà présent.
- FNIS non retenu comme générateur principal ; Pandora est retenu.

### Décision

- Garder comme candidat installable.
- SLAL est nécessaire pour enregistrer les animations SexLab via MCM.
- SLAL ne contient pas d’animations par lui-même.
- Ne pas lancer FNIS.
- Ne pas relancer Pandora maintenant.

### Plugin attendu

- `SexLab Animation Loader.esp` ou nom proche selon archive.

---

## Étape 679 — ZaZ Animation Pack SE : validation par référence Nefaram 1.5.97

### Verdict

Archive candidate acceptée avec prudence :

- `ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023.7z`

### Décision

- Garder comme archive cible pour ZaZ.
- Source : référence locale Nefaram / lien utilisé par Nefaram 1.5.97.
- Compatibilité plausible SE 1.5.97 par usage Nefaram 1.5.97.
- Ne pas confondre avec une validation Nefaram 17 / AE.

### Plugin attendu

- `ZaZAnimationPack.esm`.

Impact compteur prévisionnel : +1 non-light.

---

## Étape 680 — SLO Aroused NG : lien identifié, mais différé

### Verdict

Différer pour l’instant.

### Raison

SLO Aroused NG 3.1.7 contient une DLL :

- `SKSE/Plugins/SexlabArousedNG.dll`

et les plugins :

- `SexLabAroused.esm`
- `OSLAroused.esp`
- `OAroused.esp`

### Décision SKYFORGE

- Ne pas l’installer dans le premier pack SexLab Core.
- Vérifier explicitement compatibilité Skyrim SE 1.5.97 / SKSE 2.0.20 avant intégration.
- Vérifier rôle exact de `OSLAroused.esp` et `OAroused.esp` car la pile semble aussi toucher OStim / OAroused.

---

## Étape 681 — SLSF / SexLab Sexual Fame Framework SE vérifié

### Mod vérifié

- Sex Lab - Sexual Fame Framework SE.

### Résultat

- Plugin relevé : `SexLab - Sexual Fame [SLSF].esm`.
- Aucune DLL `SKSE/Plugins` relevée.
- Contenu principal : scripts, interface, traductions, plugin `.esm`.

### Décision

- Garder comme candidat pour le pack SexLab Core 13-A.
- Peut être installé avec SexLab Framework SE v163, SLAL et ZaZ.
- Différer `SLO Aroused NG 3.1.7` à cause de sa DLL NG.

---

## Étape 682 — Installation SexLab Core 13-A

### Mods installés

- SexLab Framework SE v163.
- SexLab Animation Loader 1.6.
- ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023.
- SLSF Reloaded 3.4.1 - décoché volontairement au départ.

### Décision

- SexLab Framework, SLAL et ZaZ installés / actifs.
- SLSF Reloaded 3.4.1 installé mais laissé décoché volontairement.
- SLSF Reloaded sera activé seulement après installation / initialisation de SexLab via MCM.

### Test de validation

- SKSE / menu principal : OK.
- Masters manquants : aucun.
- Messages DLL : aucun.
- Plugins cochés : oui.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.

### État

- Compteur précédent : **138**.
- Nouveau compteur : **141**.
- Variation : **+3 non-light**.
- LOOT non lancé.
- Pandora non relancé.
- FNIS non lancé.
- BodySlide non généré.

---

## Étape 683 — Initialisation SexLab MCM

### Résultat

- SexLab v1.63 SE initialisé via MCM.
- Sauvegarde test créée avec succès.
- Aucun CTD.
- Aucun message anormal.

### Vérifications

- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.
- SLSF Reloaded 3.4.1 : toujours décoché.

### Décision

- Garder SexLab Core actif.
- Ne pas régler les MCM maintenant.
- Utiliser cette sauvegarde test comme base pour tester SLSF Reloaded.

---

## Étape 684 — Activation SLSF Reloaded 3.4.1

### Résultat

- SLSF Reloaded 3.4.1 activé après initialisation SexLab.
- MCM SLSF Reloaded visible.
- Plugin SLSF Reloaded coché.
- Aucun CTD signalé.
- Aucun message anormal signalé.

### Vérifications

- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.
- Variation compteur : **+0**.

### Décision

- Garder SLSF Reloaded actif.
- Ne pas régler ses options maintenant.
- Reporter les réglages MCM à la phase finale.

---

## Étape 685 — Clôture provisoire SexLab Core 13-A

### Mods actifs

- SexLab Framework SE v1.63.
- SexLab Animation Loader 1.6.
- ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023.
- SLSF Reloaded 3.4.1.

### Résultat

- SexLab initialisé via MCM sur sauvegarde test.
- SLSF Reloaded activé après initialisation SexLab.
- MCM SLSF Reloaded visible.
- Aucun CTD signalé.
- Aucun message anormal signalé.

### Vérifications

- SKSE / menu principal : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.
- Plugin SLSF Reloaded : coché.
- LOOT non lancé.
- Pandora/FNIS non lancé.
- BodySlide non généré.

### Décision

- Garder le noyau SexLab Core 13-A.
- Ne pas régler les MCM maintenant.
- Reporter les réglages SexLab / SLSF à la phase finale du modpack.

### Dettes

- Animations SLAL non chargées.
- Génération animations non faite.
- MCM non configurés.
- BodySlide Output non généré.
- Devious / defeat / prostitution / slavery non installés.

### État final post-685

- SexLab Framework actif et initialisé.
- SLAL actif.
- ZaZ actif.
- SLSF Reloaded actif.
- Compteur ESP + ESM non-light : **141**.
- Overwrite : vide.
- LOOT : non lancé.
- Pandora/FNIS : non lancé.
- BodySlide : non généré.
