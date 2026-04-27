# SKYFORGE — Fichiers de configuration à analyser plus tard

> Document de suivi personnel pour le projet **SKYFORGE**.  
> Ce fichier sert à identifier les fichiers de configuration `.ini`, `.json`, `.toml`, `.yaml` ou équivalents qu’il faudra récupérer, comparer et analyser plus tard depuis Nolvus, Nefaram et l’instance SKYFORGE.
>
> Ne pas stocker dans ce dépôt de fichiers soumis à permissions, d’archives Nexus, de fichiers Bethesda, de fichiers SKSE redistribuables, d’ENB complets ou de ressources propriétaires.  
> Les fichiers de configuration peuvent être documentés ici, mais leur redistribution devra être vérifiée au cas par cas.

---

## Objectif

L’objectif est de préparer une future analyse comparative des réglages techniques entre :

- **Nolvus** ;
- **Nefaram** ;
- **SKYFORGE**.

Ces fichiers seront utilisés pour décider si SKYFORGE doit :

- garder les réglages par défaut ;
- reprendre certains réglages de Nolvus ;
- reprendre certains réglages de Nefaram ;
- créer ses propres réglages ;
- différer certains réglages jusqu’aux modules concernés.

---

## Méthode d’analyse prévue

Pour chaque fichier fourni plus tard, l’analyse devra identifier :

1. le mod concerné ;
2. l’emplacement du fichier dans MO2 ou dans le Stock Game ;
3. la source du fichier : Nolvus, Nefaram, SKYFORGE ou autre ;
4. les options sensibles ;
5. les différences entre Nolvus et Nefaram ;
6. les risques de conflit ;
7. l’impact potentiel sur la stabilité ;
8. l’impact potentiel sur les performances ;
9. l’impact potentiel sur les scripts ;
10. la décision recommandée pour SKYFORGE.

Décisions possibles :

- **Garder par défaut**
- **Reprendre Nolvus**
- **Reprendre Nefaram**
- **Fusionner manuellement**
- **Créer un réglage SKYFORGE**
- **Tester séparément**
- **Différer**
- **Exclure**

---

## 1. SSE Engine Fixes

### Fichier principal à récupérer

```text
EngineFixes.toml
```

**Mod concerné**  
SSE Engine Fixes

**Emplacement probable**  
`SKSE\Plugins\EngineFixes.toml`  
ou dans le mod MO2 correspondant à la partie SKSE de SSE Engine Fixes.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier contient des réglages moteur sensibles liés à la stabilité, aux sauvegardes, aux limites du moteur, aux correctifs mémoire et à plusieurs comportements bas niveau.

**Analyse attendue**

Comparer les options liées :

- aux sauvegardes ;
- au memory manager ;
- aux limites d’objets ;
- aux warnings ;
- aux fixes activés/désactivés ;
- aux options potentiellement incompatibles avec certains mods.

**Statut SKYFORGE**  
À récupérer plus tard

---

## 2. SSE Display Tweaks

### Fichier principal à récupérer

```text
SSEDisplayTweaks.ini
```

**Mod concerné**  
SSE Display Tweaks

**Emplacement probable**  
`SKSE\Plugins\SSEDisplayTweaks.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier contrôle des paramètres liés à l’affichage, au framerate, au borderless fullscreen, au VSync, aux limites FPS et au comportement Havok.

**Analyse attendue**

Comparer les réglages liés :

- au framerate ;
- au mode plein écran / borderless ;
- au VSync ;
- à la limite FPS ;
- à Havok ;
- aux options de latence et de fluidité ;
- à la compatibilité ENB / ReShade.

**Statut SKYFORGE**  
À récupérer plus tard

---

## 3. Scrambled Bugs

### Fichier principal à récupérer

```text
ScrambledBugs.json
```

ou selon version :

```text
ScrambledBugs.ini
```

**Mod concerné**  
Scrambled Bugs

**Emplacement probable**  
`SKSE\Plugins\ScrambledBugs.json`  
ou `SKSE\Plugins\ScrambledBugs.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Scrambled Bugs active ou désactive de nombreux correctifs moteur et gameplay. Certaines options peuvent modifier subtilement le comportement du jeu.

**Analyse attendue**

Comparer :

- les fixes activés ;
- les patches désactivés ;
- les options pouvant entrer en conflit avec des overhauls gameplay ;
- les choix liés à la magie, aux perks, aux projectiles, aux ingrédients et aux enchantements.

**Statut SKYFORGE**  
À récupérer plus tard

---

## 4. powerofthree’s Tweaks

### Fichier principal à récupérer

```text
po3_Tweaks.ini
```

**Mod concerné**  
powerofthree's Tweaks

**Emplacement probable**  
`SKSE\Plugins\po3_Tweaks.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier regroupe plusieurs tweaks SKSE utilisés par de nombreux mods modernes. Certaines options peuvent influencer les performances, les logs, les corrections de records et certains comportements gameplay.

**Analyse attendue**

Comparer :

- les options de debug ;
- les options de performance ;
- les tweaks activés ;
- les tweaks désactivés ;
- les éventuelles options nécessaires à certains mods Nolvus ou Nefaram.

**Statut SKYFORGE**  
Déjà généré dans SKYFORGE, à comparer plus tard

---

## 5. Papyrus Tweaks NG

### Fichier principal à récupérer

```text
PapyrusTweaks.ini
```

**Mod concerné**  
Papyrus Tweaks NG

**Emplacement probable**  
`SKSE\Plugins\PapyrusTweaks.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier touche aux performances Papyrus, aux limites de scripts, aux budgets et à certains comportements pouvant impacter la stabilité d’une grosse liste.

**Analyse attendue**

Comparer :

- les budgets Papyrus ;
- les paramètres de performance ;
- les réglages de logs ;
- les choix agressifs ou conservateurs ;
- la compatibilité avec une liste lourde et scriptée, notamment avec SexLab et les systèmes adultes.

**Statut SKYFORGE**  
Déjà généré dans SKYFORGE, à comparer plus tard

---

## 6. Fuz Ro D-oh

### Fichier principal à récupérer

```text
Fuz Ro D'oh.ini
```

**Mod concerné**  
Fuz Ro D-oh - Silent Voice

**Emplacement probable**  
`SKSE\Plugins\Fuz Ro D'oh.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier contrôle le comportement des dialogues silencieux. Il peut influencer la durée d’affichage des dialogues non doublés.

**Analyse attendue**

Comparer :

- la durée des lignes silencieuses ;
- les réglages de fallback ;
- les choix de confort pour les mods de quêtes et les mods adultes.

**Statut SKYFORGE**  
Déjà généré dans SKYFORGE, à comparer plus tard

---

## 7. Spell Perk Item Distributor

### Fichier principal à récupérer

```text
po3_SpellPerkItemDistributor.ini
```

**Mod concerné**  
Spell Perk Item Distributor

**Emplacement probable**  
`SKSE\Plugins\po3_SpellPerkItemDistributor.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

SPID est central pour la distribution dynamique de sorts, perks, objets et effets. Son fichier `.ini` général peut contenir des réglages de logs ou de comportement.

**Analyse attendue**

Comparer :

- les options de debug ;
- les options de logging ;
- les réglages de performance ;
- les paramètres utiles pour diagnostiquer les distributions.

**Statut SKYFORGE**  
Déjà généré dans SKYFORGE, à comparer plus tard

---

## 8. ConsolePlusPlus

### Fichier principal à récupérer

```text
po3_ConsolePlusPlus.ini
```

**Mod concerné**  
ConsolePlusPlus

**Emplacement probable**  
`SKSE\Plugins\po3_ConsolePlusPlus.ini`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ce fichier est important**

Ce fichier concerne l’ergonomie et les fonctionnalités avancées de la console, utile pour le diagnostic et le développement de la liste.

**Analyse attendue**

Comparer :

- les raccourcis ;
- les options d’affichage ;
- les options de confort ;
- les paramètres de debug.

**Statut SKYFORGE**  
Déjà généré dans SKYFORGE, à comparer plus tard

---

## 9. MCM Helper

### Fichiers à récupérer

```text
MCMHelper.ini
MCM\Config\
MCM\Settings\
```

**Mod concerné**  
MCM Helper

**Emplacement probable**  
`SKSE\Plugins\`  
ou `MCM\` selon les mods utilisant MCM Helper.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

MCM Helper peut charger ou sauvegarder des réglages MCM. Les grosses listes utilisent souvent des presets MCM pour éviter une configuration manuelle longue.

**Analyse attendue**

Identifier :

- quels mods disposent de presets MCM ;
- quels réglages doivent être intégrés à SKYFORGE ;
- quels réglages doivent rester manuels ;
- quels fichiers sont redistribuables ou non.

**Statut SKYFORGE**  
À compléter plus tard

---

## 10. SkyUI

### Fichiers à récupérer

```text
SkyUI.ini
Interface\
MCM\
```

**Mod concerné**  
SkyUI

**Emplacement probable**  
`Data\Interface\`  
ou via les mods de configuration MCM.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

SkyUI est la base de l’interface et des menus MCM. Certains réglages peuvent influencer l’affichage, les favoris, les icônes et la compatibilité avec les UI overhauls.

**Analyse attendue**

Comparer :

- les paramètres MCM ;
- les réglages de colonnes/inventaire ;
- les compatibilités avec Dear Diary, Untarnished UI, Edge UI ou autres UI futures.

**Statut SKYFORGE**  
À compléter plus tard

---

## 11. ENB Helper SE

### Fichiers à récupérer

```text
ENBHelper.ini
```

ou fichiers équivalents si présents.

**Mod concerné**  
ENB Helper SE

**Emplacement probable**  
`SKSE\Plugins\`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

ENB Helper sert de pont entre SKSE, météo, imagespaces et ENB. Il sera important lors de l’intégration des ENB prévus.

**Analyse attendue**

Vérifier :

- présence de fichiers de configuration ;
- compatibilité météo ;
- besoins spécifiques pour Cabbage ENB ;
- besoins spécifiques pour Kauz ENB.

**Statut SKYFORGE**  
À compléter lors du module ENB

---

## 12. ENB Manager

### Fichiers à récupérer

```text
Configuration ENB Manager
```

ou fichiers propres à l’outil utilisé.

**Mod / outil concerné**  
ENB Manager

**Emplacement probable**  
À déterminer selon l’outil choisi.

**Sources à comparer**

- SKYFORGE principalement
- éventuellement Nolvus si gestion ENB documentée
- éventuellement Nefaram si gestion ENB documentée

**Pourquoi ces fichiers sont importants**

SKYFORGE prévoit de gérer plusieurs options ENB sans écraser manuellement les fichiers du Stock Game.

**ENB prévus**

- Cabbage ENB
- Kauz ENB

**Analyse attendue**

Définir :

- comment stocker les presets ENB ;
- comment basculer entre Cabbage et Kauz ;
- quels fichiers restent manuels ;
- quels fichiers peuvent être documentés ;
- quels fichiers ne doivent pas être redistribués.

**Statut SKYFORGE**  
À créer plus tard

---

## 13. ReShade

### Fichiers à récupérer

```text
ReShade.ini
ReShadePreset.ini
```

ou fichiers propres au preset utilisé.

**Mod / outil concerné**  
ReShade

**Emplacement probable**  
`D:\SKYFORGE\Stock Game\`  
ou dossier dédié selon installation.

**Sources à comparer**

- SKYFORGE principalement
- éventuellement presets externes retenus

**Pourquoi ces fichiers sont importants**

ReShade pourra servir de couche post-processing optionnelle en complément ou alternative selon le rendu final.

**Analyse attendue**

Vérifier :

- compatibilité avec ENB ;
- compatibilité avec overlays ;
- impact performances ;
- ordre d’installation ;
- fichiers manuels à documenter ;
- fichiers à exclure du dépôt.

**Statut SKYFORGE**  
À créer plus tard

---

## 14. Crash Logger

### Fichiers à récupérer

```text
CrashLogger.ini
```

ou fichiers équivalents selon version.

**Mod concerné**  
Crash Logger SSE AE VR - PDB support

**Emplacement probable**  
`SKSE\Plugins\`  
et logs générés dans `Documents\My Games\Skyrim Special Edition\SKSE\` ou dossier équivalent selon version.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Crash Logger est essentiel pour diagnostiquer les crashs de SKYFORGE. Les réglages peuvent influencer le niveau de détail des logs.

**Analyse attendue**

Comparer :

- niveau de logging ;
- emplacement des logs ;
- options de symboles ;
- lisibilité des rapports.

**Statut SKYFORGE**  
À récupérer plus tard si un fichier de configuration existe

---

## 15. DynDOLOD / TexGen

### Fichiers à récupérer

```text
DynDOLOD_SSE.ini
TexGen_SSE.ini
DynDOLOD settings
```

ou presets équivalents.

**Mods / outils concernés**

- DynDOLOD
- TexGen
- DynDOLOD Resources

**Emplacement probable**  
Dans les dossiers des outils externes DynDOLOD/TexGen.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Les réglages DynDOLOD influencent fortement les performances, la stabilité visuelle, les LODs, les arbres, les villes et les mondes ajoutés.

**Analyse attendue**

Comparer :

- presets low/medium/high/ultra ;
- options grass LOD ;
- tree LOD ;
- object LOD ;
- occlusion ;
- sorties générées ;
- compatibilité avec les worldspaces ajoutés.

**Statut SKYFORGE**  
À compléter lors du module LOD

---

## 16. BodySlide / Outfit Studio

### Fichiers à récupérer

```text
SliderPresets\
BodySlide output settings
GroupFiles\
```

**Mods / outils concernés**

- BodySlide
- Outfit Studio
- CBBE / 3BA / HIMBO / TBD selon décision future

**Emplacement probable**  
`CalienteTools\BodySlide\`

**Sources à comparer**

- Nefaram principalement
- Nolvus si applicable
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Les presets BodySlide détermineront le corps, les armures, les vêtements et les outfits NSFW. Ils auront un impact majeur sur la cohérence visuelle.

**Analyse attendue**

Comparer :

- corps utilisé ;
- preset corps ;
- output folders ;
- groupes d’outfits ;
- compatibilité physics ;
- cohérence avec les systèmes adultes.

**Statut SKYFORGE**  
À compléter lors du module corps/outfits

---

## 17. Nemesis / Pandora / FNIS

### Fichiers à récupérer

```text
Nemesis_Engine settings
Pandora settings
FNIS output
```

ou fichiers équivalents selon décision finale.

**Mods / outils concernés**

- Nemesis
- Pandora
- FNIS
- FNIS Creature Pack

**Emplacement probable**  
Dossiers des outils externes et outputs MO2.

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

La gestion des animations est critique pour une fusion Nolvus/Nefaram, notamment à cause des animations de combat, OAR/DAR, SexLab, créatures et systèmes adultes.

**Analyse attendue**

Déterminer :

- outil principal retenu ;
- compatibilité SexLab ;
- compatibilité créatures ;
- compatibilité combat moderne ;
- gestion des outputs ;
- ordre de génération ;
- risques de conflit.

**Statut SKYFORGE**  
À décider plus tard

---

## 18. Open Animation Replacer / Dynamic Animation Replacer

### Fichiers à récupérer

```text
OpenAnimationReplacer.ini
```

ou fichiers équivalents.

**Mods concernés**

- Open Animation Replacer
- Dynamic Animation Replacer

**Emplacement probable**  
`SKSE\Plugins\`  
ou dossiers d’animations : `meshes\actors\`

**Sources à comparer**

- Nolvus
- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Les règles d’animations conditionnelles peuvent être nombreuses et complexes. Elles influencent combat, locomotion, idle, SexLab et animations roleplay.

**Analyse attendue**

Comparer :

- limites d’animations ;
- priorités ;
- conditions ;
- logs ;
- performances ;
- compatibilité SexLab/OAR.

**Statut SKYFORGE**  
À compléter lors du module animations

---

## 19. SexLab Framework

### Fichiers à récupérer

```text
SexLab.ini
SexLab MCM settings
SexLab Animation Registry
```

ou fichiers équivalents.

**Mods concernés**

- SexLab Framework
- SexLab Aroused
- SexLab Utility Plus
- SexLab P+ selon décision finale

**Emplacement probable**  
À déterminer selon versions et outils utilisés.

**Sources à comparer**

- Nefaram principalement
- SKYFORGE

**Pourquoi ces fichiers sont importants**

SexLab sera un pilier des systèmes adultes de SKYFORGE. Ses réglages influencent animations, acteurs, scènes, timers, consentement, créatures, tags et performances scripts.

**Analyse attendue**

Comparer :

- version SexLab ;
- réglages MCM ;
- animations enregistrées ;
- délais ;
- options créatures ;
- options expressions ;
- intégration avec défaite, slavery, prostitution et adult roleplay.

**Statut SKYFORGE**  
À compléter lors du module SexLab

---

## 20. Devious Devices

### Fichiers à récupérer

```text
Devious Devices MCM settings
DD configuration files
```

ou fichiers équivalents.

**Mods concernés**

- Devious Devices Assets
- Devious Devices Integration
- Devious Devices Expansion
- Devious Devices Contraptions

**Emplacement probable**  
À déterminer selon version retenue.

**Sources à comparer**

- Nefaram
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Devious Devices est central pour plusieurs systèmes NSFW, defeat, slavery et roleplay adulte.

**Analyse attendue**

Comparer :

- versions ;
- patches ;
- réglages MCM ;
- intégration avec SexLab ;
- impacts scripts ;
- compatibilité outfits ;
- compatibilité animations.

**Statut SKYFORGE**  
À compléter lors du module Devious / slavery

---

## 21. Defeat / Acheron / Slavery / Prostitution

### Fichiers à récupérer

```text
Acheron settings
Defeat settings
Simple Slavery settings
Public Whore settings
Radiant Prostitution settings
```

ou fichiers équivalents.

**Mods concernés**

À déterminer selon choix final, notamment :

- Acheron
- Simple Slavery
- Public Whore
- Radiant Prostitution
- Paradise Halls
- Diary of Mine

**Sources à comparer**

- Nefaram principalement
- SKYFORGE

**Pourquoi ces fichiers sont importants**

Ces systèmes sont très scriptés et peuvent fortement influencer la stabilité, la progression du joueur, les transitions de scènes et les conséquences roleplay.

**Analyse attendue**

Comparer :

- réglages MCM ;
- conditions de déclenchement ;
- compatibilité prison ;
- compatibilité slavery ;
- compatibilité prostitution ;
- intégration avec SexLab ;
- risques de boucles ou conflits ;
- charge Papyrus.

**Statut SKYFORGE**  
À compléter lors du module adult roleplay

---

## 22. UI Overhaul / HUD

### Fichiers à récupérer

```text
Dear Diary settings
Untarnished UI settings
Edge UI settings
SkyHUD.txt
TrueHUD.ini
moreHUD settings
Compass Navigation Overhaul settings
```

ou fichiers équivalents.

**Mods concernés**

À déterminer selon choix SKYFORGE final :

- Dear Diary
- Untarnished UI
- Edge UI
- SkyHUD
- TrueHUD
- moreHUD
- Compass Navigation Overhaul
- QuickLoot IE
- MCM Helper presets

**Sources à comparer**

- Nolvus principalement
- Nefaram si applicable
- SKYFORGE

**Pourquoi ces fichiers sont importants**

L’UI est sensible aux conflits de fichiers Interface, SWF, traductions, MCM et presets. Elle doit être cohérente dès le début du module interface.

**Analyse attendue**

Comparer :

- style UI retenu ;
- compatibilité SkyUI ;
- compatibilité MCM ;
- compatibilité traductions FR ;
- conflits SWF ;
- ordre d’écrasement MO2.

**Statut SKYFORGE**  
À compléter lors du module UI

---

## 23. Traductions FR

### Fichiers à récupérer

```text
Interface\Translations\
*.txt
*.strings
*.dlstrings
*.ilstrings
```

**Mods concernés**  
Tous les mods traduits.

**Emplacement probable**  
`Interface\Translations\`  
et fichiers strings selon les mods.

**Sources à comparer**

- SKYFORGE principalement
- traductions FR Nexus
- traductions personnelles autorisées

**Pourquoi ces fichiers sont importants**

Les traductions doivent rester séparées pour faciliter les mises à jour, les tests et la résolution des conflits.

**Analyse attendue**

Vérifier :

- compatibilité avec la version exacte du mod ;
- ordre d’écrasement ;
- conflits avec fichiers MCM ;
- fichiers autorisés à être redistribués ou non ;
- cohérence avec le séparateur `18 - TRADUCTIONS FR`.

**Statut SKYFORGE**  
À compléter tout au long du projet

---

## 24. Fichiers de configuration SKYFORGE à créer plus tard

Ces fichiers n’existent pas encore forcément, mais pourront être créés pour centraliser les réglages propres au modpack.

### Fichiers / mods de configuration prévus

```text
SKYFORGE - Engine Fixes Settings
SKYFORGE - Scrambled Bugs Settings
SKYFORGE - powerofthree's Tweaks Settings
SKYFORGE - SSE Display Tweaks Settings
SKYFORGE - Papyrus Tweaks Settings
SKYFORGE - MCM Presets
SKYFORGE - ENB Manager Config
SKYFORGE - ReShade Config
```

**Objectif**

Créer des petits mods MO2 dédiés aux réglages SKYFORGE, au lieu de modifier directement les mods sources.

**Résultat attendu**

Les réglages SKYFORGE seront :

- isolés ;
- faciles à désactiver ;
- faciles à comparer ;
- faciles à mettre à jour ;
- compatibles avec une future procédure Wabbajack si les permissions le permettent.

**Statut SKYFORGE**  
À créer plus tard

---

## Section à compléter

Ajouter ici les futurs fichiers de configuration identifiés pendant la construction du modpack :

```text
Nom du fichier :
Mod concerné :
Emplacement probable :
Source :
Pourquoi il est important :
Analyse attendue :
Statut :
```
