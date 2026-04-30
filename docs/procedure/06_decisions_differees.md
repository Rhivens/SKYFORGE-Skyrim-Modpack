# Décisions différées et points à revoir

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## Décisions importantes retenues après l’étape 154

- LOOT / ordre de chargement global : différé.
- Documentation : mise à jour groupée, pas étape par étape.
- Les petits fixes non sensibles peuvent être installés par blocs, avec un seul test final.
- Les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes doivent être testés individuellement.
- Indiquer l’emplacement panneau gauche MO2 quand le séparateur ou l’ordre de priorité a une importance.
- Les étapes conservent une numérotation chronologique globale, même si elles sont rangées dans des fichiers thématiques différents.
- Quêtes SFW/NSFW Nolvus/Nefaram : à proposer plus tard, décision manuelle avant installation.
- Patches de quêtes : uniquement si le mod parent est installé ou officiellement retenu.
- SexLab 1.63 est un choix définitif pour SKYFORGE, mais le module SexLab n’est pas encore installé.
- Le patch `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB` reste décoché jusqu’au futur module SexLab.
- Les choix magie, alchimie, besoins, hygiène, survie et immersion seront proposés plus tard sous forme de variantes cohérentes.
- L’interface UI de SKYFORGE ne reprend pas automatiquement celle de Nefaram ; le module UI est commencé mais restera construit par variantes cohérentes.
- SMIM / SMIM Quality Addon / Unofficial Material Fix restent prioritaires sur les conflits Security Overhaul extras pour l’instant.
- `Skyrim Unbound` est retenu comme départ alternatif officiel et devra être installé avant les premiers tests ingame jusqu’à la création de personnage ou spawn joueur.
- `Alternate Start` / `Alternate Perspective` ne seront pas utilisés comme départ principal.
- `Edge UI` est abandonné et supprimé.
- `Vel’dun UI` devient l’interface principale actuelle de SKYFORGE.
- Le crosshair vanilla de Skyrim doit être conservé ; `Contextual Crosshair` n’est pas installé.

---

## Étapes / décisions différées documentées

### 41. Ajout de Kris’s Papyrus Extender en réserve

**Objectif :**  
Préparer une dépendance potentielle sans l’activer dans la base actuelle.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/115164

**Résultat attendu :**  
`Kris's Papyrus Extender - DECOCHE / RESERVE` est installé mais décoché.

---

### 45. Mise en réserve de Object Categorization Framework

**Objectif :**  
Préparer Object Categorization Framework pour la future interface / catégorisation d’objets, sans l’intégrer définitivement à ce stade.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/81469

**Résultat attendu :**  
Le mod est présent dans MO2 mais renommé :

`A REINSTALL PLUS TARD - Object Categorization Framework`

**Note :**  
OCF est différé volontairement. Il sera réinstallé proprement plus tard avec le bloc UI / icônes / inventaire, afin d’éviter une intégration prématurée.

---

### 46. Mise en réserve de Keyword Patch Collection

**Objectif :**  
Préparer Keyword Patch Collection pour les futurs systèmes de mots-clés, inventaire, armures, armes et patches de catégorisation.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/92534

**Résultat attendu :**  
Le mod est présent dans MO2 mais renommé :

`A REINSTALL PLUS TARD - Keyword Patch Collection`

**Note :**  
Keyword Patch Collection est différé volontairement. Il sera réinstallé plus tard quand les mods dépendants seront présents.

---

### 47. Mise en attente de NPC AI Process Position Fix - NG

**Objectif :**  
Préparer un correctif lié au positionnement des processus IA des NPC, sans l’activer trop tôt.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/69326

**Résultat attendu :**  
Le mod n’est pas intégré définitivement à ce stade.

**Note :**  
NPC AI Process Position Fix - NG est à réinstaller plus tard, après l’installation de AI Overhaul, afin de mieux contrôler les dépendances et conflits potentiels.

---

### 48. Réglages SKSE différés

**Objectif :**  
Consigner les réglages volontairement différés pour éviter de modifier trop tôt le comportement moteur.

**Réglages différés :**

- Scrambled Bugs custom settings.
- powerofthree’s Tweaks custom settings.
- SSE Display Tweaks custom settings.
- SSE Engine Fixes custom settings.
- Papyrus Tweaks NG custom settings.

**Résultat attendu :**  
Aucun réglage custom supplémentaire n’est appliqué à ce stade.

**Note :**  
Les mods concernés peuvent être installés, mais leurs réglages personnalisés SKYFORGE seront appliqués plus tard, après stabilisation du socle.

---

### 70. Décision de différer Myrwatch - Editable Home Cells

**Objectif :**  
Éviter d’installer prématurément un workaround de cellule qui pourrait devenir conflictuel plus tard.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/64108

**Décision :**  
`Myrwatch - Editable Home Cells (Cell Bug Workaround)` n’est pas installé à cette étape.

**Note :**  
Le mod sera reconsidéré uniquement si un futur mod Myrwatch ou une refonte de maison le demande explicitement.

**Statut :**  
Étape 70 validée comme décision de différer.

---

### 73. RemoveAllItems Freeze Fix déjà installé

**Objectif :**  
Vérifier l’état de `RemoveAllItems Freeze Fix`.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/90734

**Décision :**  
`RemoveAllItems Freeze Fix` n’est pas réinstallé car il était déjà présent.

**Note :**  
Aucun changement effectué à cette étape.

**Statut :**  
Étape 73 annulée / sautée car le mod était déjà installé.

---

### 119. lilebonymace's patches and xEdit scripts

**Décision :**  
Différé.

**Raison :**  
Compilation de patches conditionnels et scripts xEdit à traiter plus tard selon les mods réellement installés.

**Note à retenir :**  
`lilebonymace's patches and xEdit scripts — à revoir pendant les modules patches / xEdit, selon mods réellement installés`

**Statut :**  
Étape 119 différée.

---

### 120. Happy Little Tweaks

**Décision :**  
Différé.

**Raison :**  
Dépend logiquement du choix futur des arbres / végétation, notamment `Happy Little Trees`.

**Note à retenir :**  
`Happy Little Tweaks — à revoir avec le module arbres / végétation, seulement si Happy Little Trees est retenu`

**Statut :**  
Étape 120 différée.

---

### 122. Alchemy Plus / Alchemy Plus SE

**Décision :**  
Différé.

**Correction :**  
`Alchemy Plus` et `Alchemy Plus SE` sont considérés comme un seul et même mod / une même entrée, pas comme deux mods distincts.

**Lien correct identifié :**  
https://www.nexusmods.com/skyrimspecialedition/mods/80882

**Note à retenir :**  
`Alchemy Plus / Alchemy Plus SE — à traiter comme un seul mod, différé pour le futur module alchimie / économie / survie`

**Statut :**  
Étape 122 différée.

---

### 127. Dynamic Dialogue Replacer / Skyrim Autocorrect

**Décision :**  
Différés.

**Raison :**  
`Dynamic Dialogue Replacer` sera revu plus tard. `Skyrim Autocorrect - Dialogue Grammar Fixes` est surtout orienté corrections anglaises et dépend de DDR.

**Statut :**  
Décision associée à l’étape 127.

---

### 130. ENB Extender Skyrim - réserve ENB

**Objectif :**  
Tester l’installation d’`ENB Extender Skyrim`.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/99406

**Fichier installé :**  
`ENB Extender Skyrim` version `1.3.2`, depuis les anciens fichiers.

**Résultat :**  
Au lancement, erreur détectée :

`KiENBExtender.dll - Import dependency missing from: d3d11.dll`

**Décision :**  
Le mod dépend de la présence d’un ENB binaire actif. Comme ENB n’est pas encore installé, le mod a été désactivé.

**Nom MO2 retenu :**  
`ENB Extender Skyrim - DECOCHE RESERVE ENB`

**Validation après désactivation :**  
Erreur disparue. SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 130 validée en réserve — mod installé mais décoché.

---

### 131. Auto Resolution

**Décision :**  
Différé.

**Raison :**  
`Auto Resolution` sera revu plus tard avec la configuration graphique complète :

- SSE Display Tweaks
- ENB Manager
- ENB retenu
- ReShade éventuel
- Skyrim Upscaler DLSS / DLAA
- réglages fullscreen / borderless

**Note matérielle :**  
Le PC principal de jeu dispose d’une RTX 4070 12 Go. Prévoir plus tard un module performance autour de DLSS / DLAA, compatible avec ENB et ReShade si retenus.

**Note à retenir :**  
`Auto Resolution — à revoir lors de la configuration graphique avec SSE Display Tweaks / ENB / ReShade / DLSS-DLAA`

**Statut :**  
Étape 131 différée.

---

### 134. Dynamic Armor Variants

**État réel :**  
Le mod n’est pas installé.

**Décision :**  
Différé.

**Raison :**  
À traiter plus tard avec les modules : armures, vêtements, corps / BodySlide, outfits NSFW, leveled lists / distribution, patches visuels.

**Note à retenir :**  
`Dynamic Armor Variants — à installer/analyser plus tard avec le module armures / outfits / distribution`

**Statut :**  
Étape 134 différée.

---

### 136. Item Equip Restrictor

**Lien corrigé :**  
https://www.nexusmods.com/skyrimspecialedition/mods/108665

**Décision :**  
Différé.

**Raison :**  
Le mod touche aux restrictions d’équipement, aux outfits, au roleplay et potentiellement à Devious Devices. Il sera plus pertinent dans les modules futurs liés aux tenues, restrictions et systèmes adultes.

**Note à retenir :**  
`Item Equip Restrictor — à revoir avec modules outfits / Devious Devices / restrictions roleplay`

**Statut :**  
Étape 136 différée.

---

### 147. Atlas Map Markers SE - Updated with MCM

**Décision :**  
Différé.

**Raison :**  
Le module carte sera construit plus tard autour de :

- `Flat World Map Framework (FWMF)`
- `Skyrim Paper Map by Caro Tuts for FWMF`

**Note à retenir :**  
`Module carte retenu : FWMF + Skyrim Paper Map by Caro Tuts. Revoir Atlas Map Markers uniquement si compatible et utile avec ce setup.`

**Statut :**  
Étape 147 différée.

---

### 148. Notification Filter — configuration différée

**Décision :**  
Le mod est installé, mais l’INI n’est pas encore configuré.

**Note à retenir :**  
`Notification Filter — configuration INI à faire plus tard selon les notifications générées par les futurs modules`

**Statut :**  
Configuration différée.

---

### 150. Security Overhaul SKSE - Some More Locks — patches optionnels

**Décision :**  
Patches optionnels à revoir plus tard selon les mods clutter / strongboxes / meshes retenus.

**Note :**  
Conflits acceptés pour l’instant : les mods Security Overhaul extras perdent face à SMIM, SMIM Quality Addon et Unofficial Material Fix.

**Statut :**  
Patches différés.

---

### 153. SkyHUD minimal — réinstallation future

**Décision :**  
`SkyHUD` est installé en version minimale et renommé :

`SkyHUD - A REINSTALL PLUS TARD`

**Raison :**  
Il pourra être réinstallé plus tard si une configuration HUD finale ou un preset spécifique est retenu.

**Décision associée :**  
Le crosshair vanilla de Skyrim doit être conservé. `Contextual Crosshair` n’est pas installé.

**Statut :**  
Réinstallation / configuration HUD différée.

---

### 154. Vel’dun UI minimal — réinstallation future

**Décision :**  
`Vel’dun UI` est retenu comme interface principale actuelle de SKYFORGE, mais installé en configuration minimale et renommé :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Raison :**  
Vel’dun UI devra être réinstallé plus tard pour activer les patches utiles quand les mods parents seront installés ou confirmés.

**Patches différés :**

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

**Statut :**  
Réinstallation / patches UI différés.

---

### Décision UI — Edge UI abandonné

**Choix initial envisagé :**

- `Edge UI`
- patch `Dragonborn Bestiary` pour Edge UI

**Décision finale :**

- `Edge UI` est abandonné.
- `Vel’dun UI` devient l’interface principale actuelle de SKYFORGE.

**Raisons :**

- Identité visuelle forte.
- Moins dépendant d’une pile de patches lourde.
- Modder actif sur Discord Nolvus.
- Requirements principaux compatibles avec la base actuelle : SkyUI + SkyHUD.

**Mods supprimés :**

- `Edge UI Dragonborn Bestiary Patch`
- `Edge UI - DECOCHE REMPLACE PAR VELDUN UI`

**Statut :**  
Décision ferme.

---

### Décision différée — Dragonborn Reskin icons

**Icônes Dragonborn à tester plus tard :**

- Dragonborn Reskin - Wheeler  
  https://www.nexusmods.com/skyrimspecialedition/mods/100043
- Dragonborn Reskin - STB Widgets  
  https://www.nexusmods.com/skyrimspecialedition/mods/140283
- Dragonborn Reskin - SkyUI Inventory Category and Favorites Icons  
  https://www.nexusmods.com/skyrimspecialedition/mods/132019

**Conditions :**

- `Dragonborn Reskin - Wheeler` : à tester uniquement quand Wheeler sera installé.
- `Dragonborn Reskin - STB Widgets` : à tester uniquement quand STB Widgets sera installé.
- `Dragonborn Reskin - SkyUI Inventory Category and Favorites Icons` : à tester plus tard avec le travail sur l’inventaire / favoris / icônes SkyUI.

**Statut :**  
Décision différée. Aucun de ces trois mods n’est installé maintenant.

---

### Décision ferme — Skyrim Unbound

**Décision définitive :**  
`Skyrim Unbound` est retenu comme départ alternatif officiel de SKYFORGE.

**Conséquences :**

- `Alternate Start` / `Alternate Perspective` ne seront pas utilisés comme départ principal.
- Avant les premiers tests ingame jusqu’à la création de personnage ou spawn joueur, `Skyrim Unbound` devra être installé.
- Les tests actuels restent limités au menu principal.
- Cette décision est ferme et ne sera pas remise en question plus tard.

**Statut :**  
Décision ferme.
