# Décisions différées et points à revoir

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## Décisions importantes retenues après l’étape 150

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
