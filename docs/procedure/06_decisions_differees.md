# Décisions différées et points à revoir

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## Décisions importantes retenues après l’étape 101

- LOOT / ordre de chargement global : différé.
- Documentation : mise à jour groupée, pas étape par étape.
- Les petits fixes non sensibles peuvent être installés par blocs, avec un seul test final.
- Les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes doivent être testés individuellement.
- Indiquer l’emplacement panneau gauche MO2 quand le séparateur ou l’ordre de priorité a une importance.
- Quêtes SFW/NSFW Nolvus/Nefaram : à proposer plus tard, décision manuelle avant installation.
- Patches de quêtes : uniquement si le mod parent est installé ou officiellement retenu.
- SexLab 1.63 est un choix définitif pour SKYFORGE, mais le module SexLab n’est pas encore installé.
- Le patch `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB` reste décoché jusqu’au futur module SexLab.
- Les choix magie, alchimie, besoins, hygiène, survie et immersion seront proposés plus tard sous forme de variantes cohérentes.
- L’interface UI de SKYFORGE ne reprendra pas automatiquement celle de Nefaram ; le module UI sera choisi plus tard par variantes cohérentes.
- `OnMagicEffectApply Replacer` doit gagner ses conflits contre `Optimized USSEP Valdr Quest` et `Vanilla Scripting Enhancements Loose version`.
- `Navigator - Navmesh Fixes` est à revoir si VIGILANT, Interesting NPCs, Skyrim Sewers ou Wraithguard Vault Fixer sont installés.
- `Wordkeys` est à revoir si des mods de magie comme Mysticism, Odin, Apocalypse ou Triumvirate sont installés.
- `Rock Traps Trigger Fixes` est à revoir si Lawbringer, Skyrim Realistic Conquering ou des lieux associés sont installés.
- `Myrwatch - Editable Home Cells` reste différé sauf besoin explicite.
- `Enchantable Special Item Fix - Patches` reste différé.
- `Dragon Mounds CTD Fix / WoW Dragon Mounds CTD Fix` reste différé car `Wonders of Weather` n’est pas installé.
- `Thalmor Don’t Report Crimes To Stormcloaks` reste différé pour analyse.
- `RemoveAllItems Freeze Fix` était déjà installé et n’a pas été réinstallé.
- `OCF` et `Keyword Patch Collection` restent installés mais renommés `A REINSTALL PLUS TARD`.
- `NPC AI Process Position Fix - NG` reste à réinstaller plus tard après AI Overhaul.
- Les mauvais liens repérés pendant les étapes 90, 94, 95 et 98 ont été rejetés ; seuls les liens corrigés retenus sont documentés.



## Étapes / décisions différées documentées

### 41. Ajout de Kris’s Papyrus Extender en réserve

**Objectif :**  
Préparer une dépendance potentielle sans l’activer dans la base actuelle.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/115164

**Résultat attendu :**  
`Kris's Papyrus Extender - DECOCHE / RESERVE` est installé mais décoché.

---

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

---

### 48. Réglages SKSE différés

**Objectif :**  
Consigner les réglages volontairement différés pour éviter de modifier trop tôt le comportement moteur.

**Lien :**  
Aucun téléchargement requis.

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
