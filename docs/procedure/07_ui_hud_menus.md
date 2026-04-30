# UI, HUD et menus

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes classées dans le module **03 - UI HUD MENUS**.

---

### 139. Regional Save Names

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Afficher des noms de sauvegarde plus lisibles selon la région / cellule.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/49698

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `SkyUI 5.2 SE`.

**Résultat :**  
Mod installé et validé.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 139 validée.

---

### 140. Notification Log SSE

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter un historique consultable des notifications.

**Lien corrigé :**  
https://www.nexusmods.com/skyrimspecialedition/mods/27707

**Résultat :**  
Mod installé dans `03 - UI HUD MENUS`, sous `Regional Save Names`.

**Validation :**  
Validé avec le bloc suivant.

**Statut :**  
Étape 140 validée avec l’étape 141.

---

### 141. Bloc UI/QoL — confirmations, console et favoris

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer plusieurs utilitaires UI/QoL.

**Liens :**

- Yes Im Sure  
  https://www.nexusmods.com/skyrimspecialedition/mods/24898
- Copy and Paste in Console  
  https://www.nexusmods.com/skyrimspecialedition/mods/30928
- Essential Favorites  
  https://www.nexusmods.com/skyrimspecialedition/mods/42997
- Favorite Misc Items  
  https://www.nexusmods.com/skyrimspecialedition/mods/42750

**Choix retenus :**

- `Copy and Paste in Console v1.0.1 for Skyrim SE`
- `Essential Favorites` version `2.3.0`, FOMOD avec variante compatible SE 1.5.97
- `Favorite Misc Items` version SSE / 1.5.97

**Placement :**  
Sous `Notification Log SSE`, dans `03 - UI HUD MENUS`.

**Mods installés :**

- `Yes Im Sure`
- `Copy and Paste in Console`
- `Essential Favorites`
- `Favorite Misc Items`

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 141 validée.

---

### 142. Better Container Controls for SkyUI

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Améliorer les contrôles dans les menus de conteneurs SkyUI.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/25271

**Choix retenu :**  
`BCC-SkyUI-ESL-v31`

**Note :**  
La version ESL a été retenue pour économiser la limite des plugins non-light. Le main file ESP classique n’a pas été installé.

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `Favorite Misc Items`.

**Validation :**  
Validé avec l’étape 143.

**Statut :**  
Étape 142 validée.

---

### 143. Better MessageBox Controls

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Améliorer la navigation clavier/souris dans les messages et boîtes de confirmation.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/1428

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `Better Container Controls for SkyUI`.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étapes 142 et 143 validées ensemble.

---

### 144. Better Dialogue Controls

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Améliorer la sélection clavier/souris dans les dialogues.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/1429

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `Better MessageBox Controls`.

**Validation :**  
Validé avec l’étape 145.

**Statut :**  
Étape 144 validée.

---

### 145. Read Or Take SKSE + Use Or Take SKSE

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter des actions alternatives pour lire/prendre ou utiliser/prendre certains objets.

**Liens :**

- Read Or Take SKSE  
  https://www.nexusmods.com/skyrimspecialedition/mods/69588
- Use Or Take SKSE  
  https://www.nexusmods.com/skyrimspecialedition/mods/70868

**Mods installés :**

- `Read Or Take SKSE`
- `Use Or Take SKSE`

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `Better Dialogue Controls`.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étapes 144 et 145 validées ensemble.

---

### 146. Improved Help Command + Disable Numpad

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer deux petits mods de confort console / clavier.

**Liens :**

- Improved Help Command - SE - AE  
  https://www.nexusmods.com/skyrimspecialedition/mods/79692
- Disable Numpad - Skyrim Special Edition  
  https://www.nexusmods.com/skyrimspecialedition/mods/51972

**Mods installés :**

- `Improved Help Command - SE - AE`
- `Disable Numpad - Skyrim Special Edition`

**Note :**  
`Disable Numpad` est installé volontairement pour réserver le pavé numérique aux futures touches SexLab.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 146 validée.

---

### 148. Notification Filter

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer un filtre de notifications configurable, à régler plus tard.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/67925

**Nom MO2 retenu :**  
`Notification Filter - BASE - CONFIG INI A FAIRE PLUS TARD`

**Décision :**  
Le mod est installé, mais l’INI n’est pas encore configuré.

**Note à retenir :**  
`Notification Filter — configuration INI à faire plus tard selon les notifications générées par les futurs modules`

**Validation :**  
Validé avec l’étape 149.

**Statut :**  
Étape 148 validée.

---

### 149. Security Overhaul SKSE - socle

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer le socle de variantes visuelles de serrures.

**Liens :**

- Security Overhaul SKSE - Lock Variations  
  https://www.nexusmods.com/skyrimspecialedition/mods/58224
- Security Overhaul SKSE - Add-ons  
  https://www.nexusmods.com/skyrimspecialedition/mods/59529
- Security Overhaul SKSE - Regional Locks  
  https://www.nexusmods.com/skyrimspecialedition/mods/62781

**Mods installés :**

- `Security Overhaul SKSE - Lock Variations`
- `Security Overhaul SKSE - Add-ons`
- `Security Overhaul SKSE - Regional Locks`

**Pré-requis confirmés pour Lock Variations :**

- `Address Library for SKSE Plugins`
- `powerofthree's Tweaks`

**Placement :**  
Dans `03 - UI HUD MENUS`, sous `Notification Filter`.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étapes 148 et 149 validées ensemble.

---

### 150. Security Overhaul SKSE - Some More Locks + Extra Locks

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Compléter le socle Security Overhaul avec deux packs supplémentaires de serrures.

**Liens :**

- Security Overhaul SKSE - Some More Locks  
  https://www.nexusmods.com/skyrimspecialedition/mods/59961
- Security Overhaul SKSE - Extra Locks  
  https://www.nexusmods.com/skyrimspecialedition/mods/126119

**Mods installés :**

- `Security Overhaul SKSE - Some More Locks - BASE - PATCHES A REVOIR PLUS TARD`
- `Security Overhaul SKSE - Extra Locks`

**FOMOD Some More Locks retenu :**

- `Snazzy Strongboxes` : `None`
- `SMIM Jail Door With Handle` : coché
- `Smaller Locks` : décoché
- Patches pour mods non installés : décochés

**Note :**  
`Some More Locks` a été renommé :

`Security Overhaul SKSE - Some More Locks - BASE - PATCHES A REVOIR PLUS TARD`

car certains patches pourront être revus plus tard selon les mods clutter / meshes / strongboxes retenus.

**Conflits MO2 :**  
Les mods Security Overhaul extras perdent face à :

- `Static Mesh Improvement Mod`
- `SMIM Quality Addon`
- `Unofficial Material Fix`

**Décision :**  
Conflits acceptés pour l’instant. SMIM / Quality Addon / Unofficial Material Fix restent prioritaires dans le socle meshes.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 150 validée.

---

### 152. A Matter of Time

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer une horloge HUD configurable et son système de chargement de paramètres.

**Liens :**

- A Matter of Time - A HUD clock widget  
  https://www.nexusmods.com/skyrimspecialedition/mods/12937
- A Matter Of Time - Legacy Settings Loader  
  https://www.nexusmods.com/skyrimspecialedition/mods/55365

**Mods installés :**

- `A Matter of Time - A HUD clock widget`
- `A Matter Of Time - Legacy Settings Loader`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, sous le bloc `moreHUD`.

**Choix :**

- Fichier principal pour les deux mods.
- Pas de traduction.
- Pas de test ingame/MCM pour l’instant.
- Test limité au menu principal.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 152 validée.

---

### 153. SkyHUD minimal

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer SkyHUD comme base technique HUD, sans appliquer encore de preset complet.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/463

**Mod installé :**

- `SkyHUD`

**Choix FOMOD retenus :**

- Package : `Loose Files`
- Preset : `None`
- iHUD compatibility patch : décoché
- Extra presets : décoché

**Décision UI associée :**

- Le crosshair vanilla de Skyrim doit être conservé.
- `Contextual Crosshair` n’est pas installé.
- Aucun remplacement par point blanc alternatif.

**Renommage MO2 :**

`SkyHUD - A REINSTALL PLUS TARD`

**Raison :**  
SkyHUD est installé en version minimale. Il pourra être réinstallé plus tard si une configuration HUD finale ou un preset spécifique est retenu.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 153 validée.

---

### 154. Vel’dun UI minimal

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer Vel’dun UI comme nouvelle interface principale SKYFORGE, en configuration minimale.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/176230

**Mod installé :**

- `Vel'dun UI`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, sous :

`SkyHUD - A REINSTALL PLUS TARD`

**Choix FOMOD retenus :**

- Main Files
- Main Bulk : coché
- Main Menu : `Skip - Default`
- General Patches : tous les patches laissés décochés / skip
- Dialogue : `Skip/Default`
- Patches Page 1 : tout laissé en `Skip / Default`

**Patches explicitement laissés décochés / skip :**

- BTPS Patch
- CoMAP
- Experience Patch
- ImGUI Icons Patch
- Oblivion Interaction Icons Patch
- Scribes of Skyrim Patch
- STB Active Effects
- STB Widgets
- TrueHUD Patch
- Inventory Bars
- COCKS
- Compass Navigation Overhaul
- Favorites Menu
- Local Map Upgrade
- MoreHUD Inventory Edition
- MoreHUD
- QuickLoot

**Renommage MO2 :**

`Vel'dun UI - A REINSTALL PLUS TARD`

**Raison :**  
Installation volontairement minimale. Vel’dun UI devra être réinstallé plus tard pour activer les patches utiles quand les mods parents seront installés ou confirmés.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK
- Nouvelle interface visible au menu Skyrim : OK

**Statut :**  
Étape 154 validée.
