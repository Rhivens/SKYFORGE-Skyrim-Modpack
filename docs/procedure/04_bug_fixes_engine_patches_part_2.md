# Bug fixes & engine patches — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes **77 à 101**, sauf les étapes reclassées ailleurs par module : **83** dans le fichier visuel, **97** dans les core utilities.

---

### 77. Installation de Soul-Cairn Objects Secured

**Objectif :**  
Installer un petit correctif de sécurité/verrouillage pour certains objets du Cairn de l’Âme.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/59741

**Résultat attendu :**  
`Soul-Cairn Objects Secured` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 77 validée.

---

---

### 78. Petit bloc fixes légers non-DLL

**Objectif :**  
Installer un petit bloc de correctifs légers sans DLL sensible.

**Liens :**

- Bard Instrumentals Mostly - Sing Rarely  
  https://www.nexusmods.com/skyrimspecialedition/mods/10927

- Horns Are Forever (Persistent Argonian Horns)  
  https://www.nexusmods.com/skyrimspecialedition/mods/1139

**Résultat attendu :**  
Les deux mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Notes :**

- `Skyrim Project Optimization SE` est différé, car il touche les intérieurs via occlusion culling.
- Les petits fixes non sensibles peuvent être installés par blocs avec un seul test final.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 78 validée.

---

---

### 79. Installation de Player Eyes Blink Fix

**Objectif :**  
Corriger le clignement des yeux du joueur.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/21713

**Résultat attendu :**  
`Player Eyes Blink Fix` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Notes :**

- `Stay At The System Page - Updated` était déjà installé.
- `Mfg Fix` était déjà installé.
- Seul `Player Eyes Blink Fix` a donc été installé à cette étape.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL bloquant, `Overwrite` vide.

**Statut :**  
Étape 79 validée.

---

---

### 80. Petit bloc fixes meshes / Creation Club

**Objectif :**  
Installer un petit bloc de correctifs de meshes et textures liés au contenu Creation Club.

**Liens :**

- Floating Ash Pile Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/63434

- Divine Crusader Creation Club Sword Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/15089

- Nix-Hound Eyes Fix (Creation Club Nixhound Patch)  
  https://www.nexusmods.com/skyrimspecialedition/mods/22480

- Creation Club Content - Properly Environment Mapped  
  https://www.nexusmods.com/skyrimspecialedition/mods/35298

**Fichiers installés pour Creation Club Content - Properly Environment Mapped :**

- Iron Plate Armor - Properly Environment Mapped
- Orcish Plate Armor - Properly Environment Mapped
- Dwarven Armored Mudcrab - Properly Environment Mapped
- Dead Man's Dread - Properly Environment Mapped

**Résultat attendu :**  
Les mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Notes :**

- Les quatre fichiers optionnels de `Creation Club Content - Properly Environment Mapped` ont été installés comme mods séparés dans MO2.
- `Blacksmith Forge Water Fix xEdit Script` est différé, car il s’agit d’un script xEdit.
- `FloraFixer - Mutagen Patcher and Data` est différé, car il s’agit d’un patcher/data à traiter plus tard.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 80 validée.

---

---

### 81. Bloc mesh fixes vanilla légers

**Objectif :**  
Installer des correctifs de meshes vanilla / zones vanilla.

**Liens :**

- Blackreach Tentacle Mesh Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/43083

- Labyrinthian Shalidor's Maze Fixes  
  https://www.nexusmods.com/skyrimspecialedition/mods/52239

- Assorted Mesh Fixes  
  https://www.nexusmods.com/skyrimspecialedition/mods/32117

**Résultat attendu :**  
Les trois mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Note de priorité MO2 :**  
`Assorted Mesh Fixes` gagne sur `Labyrinthian Shalidor's Maze Fixes`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 81 validée.

---

---

### 82. Bloc mesh fixes complémentaires

**Objectif :**  
Installer deux correctifs complémentaires de meshes / LOD.

**Liens :**

- Dlizzio's Mesh Fixes  
  https://www.nexusmods.com/skyrimspecialedition/mods/39260

- LOD Unloading Bug Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/61251

**Choix retenus pour Dlizzio's Mesh Fixes :**

- Installer uniquement le fichier principal.
- Ne pas installer à ce stade :
  - Parallax Mesh Patch
  - Noble Skyrim Material Fix
  - Solitude Wall Clover Remover
  - HD LODs Textures SE Mesh Fix

**Résultat attendu :**  
Les deux mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Note de priorité MO2 :**  
`Dlizzio's Mesh Fixes` gagne sur `Assorted Mesh Fixes`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 82 validée.

---

---

### 84. Installation de I'm Walkin' Here NG with Pets

**Objectif :**  
Installer un correctif SKSE qui limite les collisions gênantes entre le joueur, les alliés, invocations et familiers.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/122516

**Résultat attendu :**  
`I'm Walkin' Here NG with Pets` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Note :**  
Mod testé seul car il s’agit d’un plugin SKSE / DLL.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 84 validée.

---

---

### 85. Petit bloc fixes gameplay légers

**Objectif :**  
Installer deux correctifs légers sans choisir encore les futurs overhauls gameplay.

**Liens :**

- Sensible Sleepwalking - Wake up at nearest All-Maker Stone  
  https://www.nexusmods.com/skyrimspecialedition/mods/64680

- Sprint Sneak Movement Speed Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/86631

**Résultat attendu :**  
Les deux mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Décision importante :**  
Les systèmes magie, alchimie, besoins, hygiène, survie et immersion seront choisis plus tard par variantes cohérentes.  
Aucun overhaul alchimie / magie / besoins n’est installé automatiquement à cette étape.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 85 validée.

---

---

### 86. Petit bloc fixes vanilla légers

**Objectif :**  
Installer deux correctifs vanilla légers.

**Liens :**

- Motionless Rocks Killing People Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/87111

- Universal Cured Serana Eye Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/74759

**Résultat attendu :**  
Les deux mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Notes :**

- `Mu Joint Fix` est différé à l’étape suivante car il s’agit d’une DLL SKSE.
- `Dual Casting Fix` est traité séparément plus tard.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 86 validée.

---

---

### 87. Installation de Mu Joint Fix

**Objectif :**  
Installer un correctif SKSE / DLL pour les problèmes de genoux et joints liés à certaines animations.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/61479

**Résultat attendu :**  
`MuJointFix` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Patch installé en réserve :**

`MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB`

**Placement du patch de réserve :**

`13 - SEXLAB CORE ADULT FRAMEWORKS`

**Notes :**

- Le patch SexLab / OStim est installé mais décoché.
- SexLab 1.63 est un choix définitif pour SKYFORGE, mais le framework n’est pas encore installé à cette étape.
- Le patch ne doit pas être activé avant le futur module SexLab.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 87 validée.

---

---

### 88. Installation de Dual Casting Fix

**Objectif :**  
Installer un correctif lié au dual casting.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/92454

**Résultat attendu :**  
`Dual Casting Fix` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 88 validée.

---

---

### 89. Installation de Sound Fix for Large Sector Drives

**Objectif :**  
Installer un correctif SKSE audio/moteur pour certains disques modernes avec taille de secteur différente de 512 bytes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/71567

**Résultat attendu :**  
`Sound Fix for Large Sector Drives` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Note :**  
Même si le correctif concerne l’audio, il reste placé en `02 - BUG FIXES & ENGINE PATCHES`, car il s’agit d’un plugin SKSE / correctif moteur, pas d’un mod audio ou musique.

**Décision UI :**  
L’interface de SKYFORGE ne reprendra pas automatiquement celle de Nefaram.  
Le module UI sera choisi plus tard par variantes cohérentes.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 89 validée.

---

---

### 90. Installation de Adoption Spouse and Moving Fixes

**Objectif :**  
Installer un correctif pour les systèmes vanilla d’adoption, conjoint et déménagement.

**Lien retenu :**  
https://www.nexusmods.com/skyrimspecialedition/mods/92845

**Lien rejeté :**  
https://www.nexusmods.com/skyrimspecialedition/mods/118660

**Raison du rejet :**  
Le premier lien proposé était masqué sur Nexus pour possible problème de permissions.  
Il n’a pas été utilisé.

**Résultat attendu :**  
`Adoption Spouse and Moving Fixes` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Note :**  
`Horse Save Load Fix` a été proposé temporairement comme remplacement, mais n’a pas été installé à cette étape.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 90 validée.

---

---

### 91. Petit bloc fixes vanilla légers

**Objectif :**  
Installer deux petits correctifs vanilla.

**Liens :**

- World Encounter Noble Riding Horse Fix - WERoad02  
  https://www.nexusmods.com/skyrimspecialedition/mods/150951

- Stuck on Sleeper Fix - Exit Noble Bed Double 02  
  https://www.nexusmods.com/skyrimspecialedition/mods/131173

**Résultat attendu :**  
Les deux mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun missing master, `Overwrite` vide.

**Statut :**  
Étape 91 validée.

---

---

### 92. Installation de Horse Save Load Fix

**Objectif :**  
Installer le correctif chevaux / sauvegarde / chargement mis de côté à l’étape 90.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/132110

**Résultat attendu :**  
`Horse Save Load Fix` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message bloquant, `Overwrite` vide.

**Statut :**  
Étape 92 validée.

---

---

### 93. Installation de Script Effect Archetype Crash Fix

**Objectif :**  
Installer un correctif de crash optionnel issu de la page `Scrambled Bugs`.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/43532?tab=files

**Fichier retenu :**  
`Script Effect Archetype Crash Fix`

**Placement MO2 conseillé :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, juste après `Scrambled Bugs`.

**Résultat attendu :**  
`Script Effect Archetype Crash Fix` est installé comme mod séparé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 93 validée.

---

---

### 94. Installation de Better AltTab

**Objectif :**  
Installer un correctif SKSE de confort/stabilité pour le Alt-Tab.

**Lien retenu :**  
https://www.nexusmods.com/skyrimspecialedition/mods/121342

**Lien incorrect rejeté :**  
https://www.nexusmods.com/skyrimspecialedition/mods/126536

**Résultat attendu :**  
`Better AltTab` est installé et coché dans `02 - BUG FIXES & ENGINE PATCHES`.

**Placement MO2 retenu :**  
En fin du petit bloc de fixes récents, après `Horse Save Load Fix`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 94 validée.

---

---

### 95. Installation de Terrain Helper

**Objectif :**  
Installer un plugin SKSE utile plus tard pour le rendu terrain avec ENB ou Community Shaders.

**Lien retenu :**  
https://www.nexusmods.com/skyrimspecialedition/mods/143149

**Lien incorrect rejeté :**  
https://www.nexusmods.com/skyrimspecialedition/mods/142510

**Nom MO2 retenu :**  
`Terrain Helper CS-ENB`

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, après `Better AltTab`.

**Résultat attendu :**  
`Terrain Helper CS-ENB` est installé et coché.

**Note :**  
Le mod servira surtout plus tard, selon le choix final ENB / Community Shaders / terrain / parallax.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 95 validée.

---

---

### 96. Installation de Light Placer

**Objectif :**  
Installer un framework SKSE de placement de lumières, utile pour certains setups lighting modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/127557

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, après `Terrain Helper CS-ENB`.

**Résultat attendu :**  
`Light Placer` est installé et coché.

**Note :**  
Ce mod est surtout utile dans un futur contexte Community Shaders / lighting moderne.  
Il est néanmoins installé dans le bloc SKSE / engine car il s’agit d’un plugin SKSE.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 96 validée.

---

---

### 98. Installation de PapyrusUtil TFC Fix

**Objectif :**  
Installer un correctif lié à PapyrusUtil et à la commande caméra libre `tfc`.

**Lien retenu :**  
https://www.nexusmods.com/skyrimspecialedition/mods/162625

**Lien incorrect rejeté :**  
https://www.nexusmods.com/skyrimspecialedition/mods/114623

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, près de `Papyrus Tweaks NG` / correctifs Papyrus.

**Résultat attendu :**  
`PapyrusUtil TFC Fix` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message bloquant, `Overwrite` vide.

**Statut :**  
Étape 98 validée.

---

---

### 99. Installation de Explosion Collision Fix

**Objectif :**  
Installer un correctif SKSE évitant certains dégâts d’explosion appliqués plusieurs fois à cause des trigger boxes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/154076

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, après `Dual Casting Fix`.

**Résultat attendu :**  
`Explosion Collision Fix` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, `Overwrite` vide.

**Statut :**  
Étape 99 validée.

---

---

### 100. Installation de FenixFixes et CrosshairRefEventsFix

**Objectif :**  
Installer deux correctifs SKSE, dont un utile pour éviter certains blocages de scripts avec des systèmes adultes.

**Liens :**

- FenixFixes  
  https://www.patreon.com/posts/mod-release-109841577

- CrosshairRefEventsFix  
  https://github.com/yeahhowaboutnooo/CrosshairRefEventsFix
  https://www.loverslab.com/topic/204052-crosshairrefevents-script-hang-fix/

**Source / note CrosshairRefEventsFix :**  
Le mod a été trouvé sur LoversLab sous le nom `CrosshairRefEvents script hang fix 0.0.1`, par `yeahhowaboutnooo`, avec code source public GitHub.  
Il cible notamment des cas comme `Naked Defeat` et `Deviously Cursed Loot`.

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`, après `Explosion Collision Fix`.

**Ordre MO2 retenu :**

1. `Explosion Collision Fix`
2. `FenixFixes`
3. `CrosshairRefEventsFix 0.0.1`
4. `Sound Fix for Large Sector Drives`

**Résultat attendu :**  
`FenixFixes` et `CrosshairRefEventsFix 0.0.1` sont installés et cochés.

**Notes :**

- `FenixFixes` est configurable et touche plusieurs comportements ; il sera revu plus tard si nécessaire.
- `CrosshairRefEventsFix` est très pertinent pour la future intégration SexLab / Devious / Defeat, mais reste un plugin SKSE jeune.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 100 validée.

---

---

### 101. Installation de Best In Class

**Objectif :**  
Installer le système `Best In Class` et son port compatible Skyrim SE 1.5.97.

**Liens :**

- Best In Class - SKSE Remake  
  https://www.nexusmods.com/skyrimspecialedition/mods/147942

- Best in Class for Skyrim 1.5  
  https://www.nexusmods.com/skyrimspecialedition/mods/148087

**Placement MO2 :**  
Dans `02 - BUG FIXES & ENGINE PATCHES`.

**Ordre MO2 retenu :**

1. `Best In Class - SKSE Remake`
2. `Best in Class for Skyrim 1.5`

**Note de priorité :**  
`Best in Class for Skyrim 1.5` doit rester sous le mod original et gagner les conflits éventuels.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 101 validée.


---
