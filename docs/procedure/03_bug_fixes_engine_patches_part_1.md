# Bug fixes & engine patches — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes **50 à 76**.

---

### 50. Correctifs de quêtes/scripts vanilla

**Objectif :**  
Installer un petit bloc de correctifs simples liés aux quêtes et scripts vanilla.

**Liens :**

- WE05 Script Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/56695

- Ulfric...Tullius...Give Me a Break  
  https://www.nexusmods.com/skyrimspecialedition/mods/35427

- Delphine Skyhaven Bugfix MQ203  
  https://www.nexusmods.com/skyrimspecialedition/mods/62417

**Résultat attendu :**  
Les mods sont installés sous :

`02 - BUG FIXES & ENGINE PATCHES`

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 50 validée.

---

---

### 51. Petit bloc fixes système / confort

**Objectif :**  
Ajouter un petit bloc de correctifs issus du module Bug Fixes / Engine Patches, sans toucher aux réglages custom différés.

**Liens :**

- Better Combat Escape - SSE  
  https://www.nexusmods.com/skyrimspecialedition/mods/43936

- Bethesda.net Mods Manager Menu Disable Hide Remove  
  https://www.nexusmods.com/skyrimspecialedition/mods/56430

- Aurora Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/77834

**Résultat attendu :**  
Les mods sont installés sous :

`Delphine Skyhaven Bugfix MQ203`

Ordre MO2 conseillé :

1. Better Combat Escape - SSE
2. Bethesda.net Mods Manager Menu Disable Hide Remove
3. Aurora Fix

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 51 validée.

---

---

### 52. Correctifs techniques suivants, bloc prudent

**Objectif :**  
Ajouter trois correctifs techniques supplémentaires du module Bug Fixes / Engine Patches.

**Liens corrigés :**

- TrapSwingingWall Script Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/61978

- Southfringe Sanctum Crash Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/98963

- Sky Reflection Fix for ENB  
  https://www.nexusmods.com/skyrimspecialedition/mods/110604

**Résultat attendu :**  
Les mods sont installés sous :

`Aurora Fix`

Ordre MO2 conseillé :

1. TrapSwingingWall Script Fix
2. Southfringe Sanctum Crash Fix
3. Sky Reflection Fix for ENB

**Notes :**

- Le premier lien proposé pour Trap Swinging Wall Script Fix était incorrect.
- Le bon lien est :  
  https://www.nexusmods.com/skyrimspecialedition/mods/61978
- Pour TrapSwingingWall Script Fix, utiliser la version vanilla/simple si un choix est proposé.
- Sky Reflection Fix for ENB est un plugin SKSE : surveiller les messages DLL au lancement.
- Aucun réglage custom ENB/ReShade n’est encore installé à cette étape.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message d’erreur bloquant, `Overwrite` vide.

**Statut :**  
Étape 52 validée.  
Pause du projet à cette étape.  
Reprise prévue à l’étape 53.

---

---

### 53. Installation de Fast Travel Crash Fix

**Objectif :**  
Corriger un crash potentiel lié au fast travel, sans modifier encore l’ordre global des plugins.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/102323

**Résultat attendu :**  
`Fast Travel Crash Fix` est installé et coché.

**Notes :**

- `Actor Limit Fix` n’a pas été réinstallé car il était déjà présent.
- Le modder recommande de placer le plugin de Fast Travel Crash Fix en fin de load order.
- Cette consigne est notée, mais l’ordre de chargement global sera traité plus tard avec LOOT.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 53 validée.

---

---

### 54. Bloc correctifs vanilla légers

**Objectif :**  
Installer un petit bloc de correctifs non sensibles liés à des scripts ou quêtes vanilla.

**Liens :**

- DLC2 Miraak BossFightScript Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/123327

- Source of Stalhrim Quest Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/32329

- Taarie’s Dialogue Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/24406

- Standing Ambusher Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/74492

**Résultat attendu :**  
Les quatre mods sont installés et cochés dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 54 validée.

---

---

### 55. Bloc fixes légers Civil War / Journal

**Objectif :**  
Installer deux correctifs légers sans dépendance à des quêtes externes Nolvus/Nefaram.

**Liens :**

- Excuse Me  
  https://www.nexusmods.com/skyrimspecialedition/mods/67219

- Quest Journal Limit Bug Fixer  
  https://www.nexusmods.com/skyrimspecialedition/mods/56130

**Résultat attendu :**  
Les deux mods sont installés et cochés.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 55 validée.

---

---

### 56. Bloc Creation Club léger

**Objectif :**  
Installer deux correctifs légers liés au contenu AE / Creation Club et à Survival Mode.

**Liens :**

- Bone Wolf Shutdown Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/87339

- Survival Mode Prompt Removed  
  https://www.nexusmods.com/skyrimspecialedition/mods/59049

**Choix retenu :**

- Pour `Survival Mode Prompt Removed`, utiliser l’option :  
  `Survival Mode disabled by default`

**Note :**  
`Disable Auto Vanity Mode - Stops Camera Spinning Around Player Character` n’a pas été réinstallé car il était déjà présent.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 56 validée.

---

---

### 57. Installation de Optimized USSEP Valdr Quest

**Objectif :**  
Optimiser/corriger le script ajouté par USSEP autour de la quête de Valdr.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/69346

**Résultat attendu :**  
`Optimized USSEP Valdr Quest` est installé et coché.

**Note :**  
`Stuck on Screen Load Door Prompt Fix` n’a pas été réinstallé car il était déjà présent.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 57 validée.

---

---

### 58. Installation de OnMagicEffectApply Replacer

**Objectif :**  
Installer un correctif sensible lié à l’événement Papyrus `OnMagicEffectApply`.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/67968

**Résultat attendu :**  
`OnMagicEffectApply Replacer` est installé et coché.

**Notes :**

- Installer uniquement le fichier principal.
- Ne pas installer les addons pour Ordinator, Skyrim Extended Cut Saints and Seducers ou autres mods non présents.
- `OnMagicEffectApply Replacer` doit gagner ses conflits contre :
  - `Optimized USSEP Valdr Quest`
  - `Vanilla Scripting Enhancements Loose version`

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 58 validée.

---

---

### 59. Installation de Equip Enchantment Fix

**Objectif :**  
Installer un correctif SKSE pour les enchantements d’objets équipés.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/42839

**Résultat attendu :**  
`Equip Enchantment Fix` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun conflit MO2 signalé, `Overwrite` vide.

**Statut :**  
Étape 59 validée.

---

---

### 60. Installation de Unequip Quiver SE

**Objectif :**  
Installer un plugin SKSE de confort visuel pour masquer le carquois lorsque l’arc/arbalète n’est pas équipé.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/44031

**Fichier retenu :**

`Unequip Quiver SE`

**Résultat attendu :**  
`Unequip Quiver SE` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL signalé, `Overwrite` vide.

**Statut :**  
Étape 60 validée.

---

---

### 61. Bloc CTD fixes légers

**Objectif :**  
Installer trois correctifs légers liés à des crashs ou scripts vanilla.

**Liens :**

- WIDeadBodyCleanupScript Crash Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/62413

- Chillwind Depths CTD Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/44249

- Halldir’s Cairn CTD Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/29149

**Résultat attendu :**  
Les trois mods sont installés et cochés.

**Note :**  
`Dragon Mounds CTD Fix / WoW Dragon Mounds CTD Fix` est différé, car il dépend de `Wonders of Weather`, non installé actuellement.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 61 validée.

---

---

### 62. Bloc fixes Papyrus / pièges légers

**Objectif :**  
Installer trois petits correctifs non sensibles, sans DLL.

**Liens :**

- Nchuanthumz Papyrus Load Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/73820

- Magic Student (WIChangeLocation04) Quest Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/80676

- Rock Traps Trigger Fixes  
  https://www.nexusmods.com/skyrimspecialedition/mods/81587

**Choix FOMOD pour Rock Traps Trigger Fixes :**

Aucun patch coché.

**Nom MO2 retenu :**

`Rock Traps Trigger Fixes - BASE - PATCHES A VOIR PLUS TARD`

**Notes :**

Les patches suivants sont différés car les mods parents ne sont pas installés :

- Falkreath Bandit's Downfall
- Lawbringer - Pinefall Bridge
- Pinewatch Pass Reclaimed
- Skyrim Realistic Conquering - All In One
- Skyrim Realistic Conquering - Peak's Shade Tower and Pinewatch Checkpoint

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 62 validée.

---

---

### 63. Installation de Mannequin Management

**Objectif :**  
Installer un correctif léger pour stabiliser les mannequins.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/38221

**Résultat attendu :**  
`Mannequin Management` est installé et coché.

**Note :**  
Le réglage console `SET MMDELAY TO #` reste à sa valeur par défaut.  
Il sera revu plus tard uniquement si des problèmes de mannequins apparaissent dans un load order lourd.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 63 validée.

---

---

### 64. Bibliothèque Papyrus et collision dynamique

**Objectif :**  
Installer une bibliothèque Papyrus et un correctif de collision dynamique.

**Liens :**

- Rogue’s Gallery - Papyrus Library  
  https://www.nexusmods.com/skyrimspecialedition/mods/99482

- Dynamic Collision Adjustment  
  https://www.nexusmods.com/skyrimspecialedition/mods/76783

**Résultat attendu :**  
Les deux mods sont installés et cochés.

**Note :**  
Aucun patch optionnel n’est installé à cette étape.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 64 validée.

---

---

### 65. Installation de Disk Cache Enabler

**Objectif :**  
Installer un plugin SKSE de performance lié au cache disque.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/100975

**Fichier retenu :**

`DiskCacheEnabler-1.2`

**Résultat attendu :**  
`Disk Cache Enabler` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL signalé, `Overwrite` vide.

**Statut :**  
Étape 65 validée.

---

---

### 66. Installation de A0D789 Patch

**Objectif :**  
Installer un correctif SKSE ciblé contre un crash connu `SkyrimSE.exe+A0D789`.

**Lien :**  
https://www.patreon.com/posts/se-ae-69951525

**Résultat attendu :**  
`A0D789 Patch` est installé et coché.

**Note :**  
Mod installé seul car il s’agit d’un plugin SKSE provenant d’une source hors Nexus.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL signalé, `Overwrite` vide.

**Statut :**  
Étape 66 validée.

---

---

### 67. Installation de Skyrim Freeze Fix NG

**Objectif :**  
Installer un correctif SKSE contre certains freezes moteur.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/160704

**Résultat attendu :**  
`Skyrim Freeze Fix NG` est installé et coché.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun message DLL signalé, `Overwrite` vide.

**Statut :**  
Étape 67 validée.

---

---

### 68. Installation de Navigator - Navmesh Fixes

**Objectif :**  
Installer un correctif de navmeshes vanilla / Creation Club.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/52641

**Choix FOMOD retenus :**

- Main file : `.esl`
- Sunder and Wraithguard CC : OUI
- Interesting NPCs : NON
- Skyrim Sewers : NON
- VIGILANT : NON
- Editable Vault Cell : NON

**Nom MO2 retenu :**

`Navigator - Navmesh Fixes - BASE CC - PATCHES A VOIR PLUS TARD`

**Notes :**

Navigator sera à revoir/réinstaller plus tard si on installe :

- VIGILANT
- Interesting NPCs
- Skyrim Sewers
- Wraithguard Vault Fixer / Editable Vault Cell

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 68 validée.

---

---

### 69. Installation de Wordkeys

**Objectif :**  
Installer un framework léger de keywords pour futurs mods de magie.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/65023

**Choix FOMOD retenu :**

Aucun patch magie coché.

**Nom MO2 retenu :**

`Wordkeys - BASE - PATCHES MAGIE A VOIR PLUS TARD`

**Notes :**

Wordkeys sera à revoir/réinstaller plus tard si on installe des mods de magie comme :

- Mysticism
- Odin
- Apocalypse
- Triumvirate
- autres packs listés dans le FOMOD

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 69 validée.

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

### 71. Bloc hostilité / crimes vanilla

**Objectif :**  
Installer deux petits correctifs gameplay vanilla liés à l’hostilité et aux crimes.

**Liens :**

- World Encounter Hostility Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/91403

- Zero Bounty Hostility Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/95989

**Choix retenu :**

Pour `World Encounter Hostility Fix`, installer :

`World Encounter Hostility Fix - Performance Version`

**Note :**  
`Thalmor Don’t Report Crimes To Stormcloaks` est différé pour analyse plus tard.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 71 validée.

---

---

### 72. Enchantable Special Item Fix pour Skyrim 1.5.97

**Objectif :**  
Corriger l’affichage des enchantements ajoutés par le joueur sur certains objets spéciaux, avec compatibilité Skyrim SE 1.5.97.

**Liens :**

- Enchantable Special Item Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/65154

- Enchantable Special Item Fix for Skyrim 1.5  
  https://www.nexusmods.com/skyrimspecialedition/mods/101420

**Choix FOMOD retenus pour le mod original :**

- Creation Club Fearsome Fists : OUI
- Unofficial Skyrim Special Edition Patch : OUI

**Résultat attendu :**  
Les deux mods sont installés dans cet ordre :

1. `Enchantable Special Item Fix`
2. `Enchantable Special Item Fix for Skyrim 1.5`

**Note :**  
`Enchantable Special Item Fix for Skyrim 1.5` doit rester sous le mod original et gagner ses conflits éventuels.  
`Enchantable Special Item Fix - Patches` reste différé.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 72 validée.

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

---

### 74. Bloc petits fixes inventaire / Dwemer

**Objectif :**  
Installer trois correctifs légers liés à l’inventaire, au pickpocket et aux portes Dwemer / vanilla.

**Liens :**

- Hide Quest Items in Container Menu  
  https://www.nexusmods.com/skyrimspecialedition/mods/51243

- Pickpocket Reset  
  https://www.nexusmods.com/skyrimspecialedition/mods/13838

- Dwemer Gates Don’t Reset  
  https://www.nexusmods.com/skyrimspecialedition/mods/26331

**Choix FOMOD retenu pour Dwemer Gates Don’t Reset :**

- Version : `1.4.0`
- Option : `Complete - Base Object Swapper`

**Nom MO2 retenu :**

`Dwemer Gates Don't Reset - BOS Complete`

**Note :**  
Le choix BOS Complete est retenu pour éviter un plugin supplémentaire et rester cohérent avec `Base Object Swapper`, déjà installé.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 74 validée.

---

---

### 75. Bloc scripts / immersion légère

**Objectif :**  
Installer trois correctifs légers, sans DLL critique.

**Liens :**

- Sharpen Other Swords II - AnimObject Swapper  
  https://www.nexusmods.com/skyrimspecialedition/mods/75237

- dunPOISoldiersRaidOnStart Script Tweak  
  https://www.nexusmods.com/skyrimspecialedition/mods/62925

- Nifty AI Tweaks AIO - SSE  
  https://www.nexusmods.com/skyrimspecialedition/mods/52035

**Choix retenu pour Nifty AI Tweaks :**

`Nifty AI Tweaks AIO - SSE ESL`, version `3-ESL`

**Note :**  
L’ancienne version Nefaram `2A` n’est pas retenue.  
SKYFORGE part de zéro et privilégie la version récente ESL compatible.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 75 validée.

---

---

### 76. Bloc Creation Club / Fishing léger

**Objectif :**  
Installer deux correctifs légers liés au contenu Creation Club Fishing.

**Liens :**

- Power of Creation - Fishing  
  https://www.nexusmods.com/skyrimspecialedition/mods/58354

- Fish Anywhere With Water  
  https://www.nexusmods.com/skyrimspecialedition/mods/60915

**Résultat attendu :**  
Les deux mods sont installés et cochés.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 76 validée.  
Pause de déploiement de mods à cette étape.


---
