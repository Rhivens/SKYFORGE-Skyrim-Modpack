# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.  
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.  
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## Étapes réalisées

### 1. Préparation de Skyrim

**Objectif :**  
Installer Skyrim Anniversary Edition via Steam et lancer le jeu une première fois pour initialiser les fichiers de base et le contenu AE / Creation Club.

**Lien :**  
https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/

**Résultat attendu :**  
Skyrim est installé, initialisé, et le contenu Anniversary Edition est présent.

---

### 2. Verrouillage des mises à jour Steam

**Objectif :**  
Empêcher Steam de mettre à jour Skyrim automatiquement pendant la construction du modpack.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
L’option Steam est réglée sur “Attendre que je lance le jeu” et le fichier `appmanifest_489830.acf` est en lecture seule.

---

### 3. Création du dossier Stock Game SKYFORGE

**Objectif :**  
Créer une copie isolée de Skyrim dans un dossier dédié au projet SKYFORGE.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le dossier `D:\SKYFORGE\Stock Game\` contient une copie complète du dossier Skyrim Steam.

---

### 4. Downgrade vers Skyrim SE 1.5.97

**Objectif :**  
Appliquer le downgrade **Best of Both Worlds** sur le Stock Game afin de conserver le contenu AE tout en utilisant l’exécutable Skyrim SE 1.5.97.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/169962

**Résultat attendu :**  
`SkyrimSE.exe` dans `D:\SKYFORGE\Stock Game\` est en version `1.5.97.0`.

---

### 5. Installation de SKSE 1.5.97

**Objectif :**  
Installer SKSE compatible Skyrim SE 1.5.97 dans le Stock Game.

**Lien :**  
https://skse.silverlock.org/

**Résultat attendu :**  
`skse64_loader.exe`, `skse64_1_5_97.dll` et `skse64_steam_loader.dll` sont présents dans `D:\SKYFORGE\Stock Game\`.

---

### 6. Installation de Mod Organizer 2 portable

**Objectif :**  
Installer MO2 en instance portable dédiée à SKYFORGE.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/6194

**Résultat attendu :**  
MO2 2.4.4 est installé dans `D:\SKYFORGE\MO2\` et pointe vers `D:\SKYFORGE\Stock Game\SkyrimSE.exe`.

---

### 7. Création du profil MO2 de base

**Objectif :**  
Créer un profil isolé pour SKYFORGE.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le profil `00 - SKYFORGE Base` existe avec sauvegardes et fichiers INI spécifiques au profil activés.

---

### 8. Création de l’ossature des séparateurs MO2

**Objectif :**  
Créer une structure visuelle propre dans le panneau gauche de MO2.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Les séparateurs SKYFORGE sont créés, de `00 - BASE GAME` à `18 - TRADUCTIONS FR`, avec `Overwrite` conservé tout en bas.

---

### 9. Installation d’Address Library

**Objectif :**  
Installer la dépendance SKSE nécessaire aux plugins modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/32444

**Résultat attendu :**  
`Address Library for SKSE Plugins` est installé, coché, et placé sous `01 - SKSE PLUGINS & CORE UTILITIES`.

---

### 10. Installation de Backported Extended ESL Support

**Objectif :**  
Permettre à Skyrim SE 1.5.97 de gérer correctement les plugins ESL récents.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/106441

**Résultat attendu :**  
`Backported Extended ESL Support` est installé, coché, et placé sous `01 - SKSE PLUGINS & CORE UTILITIES`.

---

### 11. Premier test de lancement SKSE

**Objectif :**  
Vérifier que la base Stock Game + SKSE + Address Library + BEES démarre correctement.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le jeu atteint le menu principal via SKSE lancé depuis MO2.

---

### 12. Installation de Crash Logger

**Objectif :**  
Ajouter un outil de diagnostic pour les futurs crashs.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/59818

**Résultat attendu :**  
`Crash Logger SSE AE VR - PDB support` version Skyrim SE 1.5.97 est installé, coché, et le jeu démarre correctement.

---

### 13. Installation de SSE Engine Fixes

**Objectif :**  
Installer les correctifs moteur essentiels pour Skyrim SE 1.5.97.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/17230

**Résultat attendu :**  
La partie MO2 et la partie manuelle de SSE Engine Fixes sont installées, et le jeu atteint le menu principal sans crash.

---

### 14. Installation de Bug Fixes SSE

**Objectif :**  
Ajouter des corrections SKSE complémentaires au moteur du jeu.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/33261

**Résultat attendu :**  
`Bug Fixes SSE` est installé, coché, et le jeu démarre correctement.

---

### 15. Installation de Scrambled Bugs

**Objectif :**  
Ajouter des corrections configurables pour plusieurs bugs du moteur et du gameplay vanilla.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/43532

**Résultat attendu :**  
`Scrambled Bugs` est installé, coché, et le jeu démarre correctement.

---

### 16. Installation de PapyrusUtil SE

**Objectif :**  
Ajouter une dépendance Papyrus majeure utilisée par de nombreux mods.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/13048

**Résultat attendu :**  
`PapyrusUtil SE` est installé, coché, et le jeu démarre correctement.

---

### 17. Installation de powerofthree’s Papyrus Extender

**Objectif :**  
Ajouter des fonctions Papyrus étendues utilisées par de nombreux mods modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/22854

**Résultat attendu :**  
`powerofthree's Papyrus Extender` est installé, coché, et le jeu démarre correctement.

---

### 18. Installation de JContainers SE

**Objectif :**  
Ajouter une bibliothèque de stockage et manipulation de données utilisée par plusieurs frameworks.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/16495

**Résultat attendu :**  
`JContainers SE` est installé, coché, et le jeu démarre correctement.

---

### 19. Installation de powerofthree’s Tweaks

**Objectif :**  
Ajouter les tweaks SKSE de powerofthree et générer leur configuration.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/51073

**Résultat attendu :**  
`powerofthree's Tweaks` est installé, coché, et son fichier `po3_Tweaks.ini` généré est isolé dans un mod dédié.

---

### 20. Installation de MCM Helper

**Objectif :**  
Ajouter la dépendance moderne nécessaire aux menus MCM de nombreux mods.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/53000

**Résultat attendu :**  
`MCM Helper` est installé et coché, avec ses dépendances satisfaites.

---

### 21. Installation de SkyUI

**Objectif :**  
Installer l’interface de base nécessaire aux menus MCM.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/12604

**Résultat attendu :**  
`SkyUI_5_2_SE` est installé, coché, et le missing master de `MCMHelper.esp` est résolu.

---

### 22. Installation de ConsoleUtilSSE NG

**Objectif :**  
Ajouter une dépendance SKSE utilisée par plusieurs mods modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/76649

**Résultat attendu :**  
`ConsoleUtilSSE NG` est installé, coché, et le jeu démarre correctement.

---

### 23. Installation de Fuz Ro D-oh

**Objectif :**  
Ajouter le support des dialogues silencieux pour les mods de quêtes, roleplay et systèmes adultes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/15109

**Résultat attendu :**  
`Fuz Ro D-oh - Silent Voice` est installé, coché, et son fichier `Fuz Ro D'oh.ini` généré est isolé dans un mod dédié.

---

### 24. Installation de SPID

**Objectif :**  
Ajouter le distributeur de sorts, perks, objets et effets utilisé par les listes modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/36869

**Résultat attendu :**  
`Spell Perk Item Distributor` est installé, coché, et son fichier `po3_SpellPerkItemDistributor.ini` généré est isolé dans un mod dédié.

---

### 25. Installation de KID

**Objectif :**  
Ajouter le distributeur de keywords pour objets et records.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/55728

**Résultat attendu :**  
`Keyword Item Distributor` est installé, coché, et le jeu démarre correctement.

---

### 26. Installation de Base Object Swapper

**Objectif :**  
Ajouter le système de remplacement dynamique d’objets de base.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/60805

**Résultat attendu :**  
`Base Object Swapper` est installé, coché, et le jeu démarre correctement.

---

### 27. Installation de FormList Manipulator

**Objectif :**  
Ajouter la manipulation dynamique de FormLists.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/74037

**Résultat attendu :**  
`FormList Manipulator - FLM` est installé, coché, et le jeu démarre correctement.

---

### 28. Installation d’AnimObject Swapper

**Objectif :**  
Ajouter le système de remplacement dynamique d’objets d’animation.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/75167

**Résultat attendu :**  
`AnimObject Swapper` est installé, coché, et le jeu démarre correctement.

---

### 29. Installation de FISSES

**Objectif :**  
Ajouter l’interface de sauvegarde/chargement de configurations utilisée par certains mods.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/13956

**Résultat attendu :**  
`FileAccess Interface for Skyrim SE Scripts - FISSES` est installé, coché, et le jeu démarre correctement.

---

### 30. Installation de Console Commands Extender

**Objectif :**  
Étendre les commandes console disponibles pour les mods et le diagnostic.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/28210

**Résultat attendu :**  
`Console Commands Extender` est installé, coché, et le jeu démarre correctement.

---

### 31. Installation de More Informative Console

**Objectif :**  
Améliorer les informations affichées dans la console de Skyrim.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/19250

**Résultat attendu :**  
`More Informative Console` est installé, coché, et le jeu démarre correctement.

---

### 32. Installation de ConsolePlusPlus

**Objectif :**  
Améliorer l’utilisation de la console et générer sa configuration.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/79975

**Résultat attendu :**  
`ConsolePlusPlus` est installé, coché, et son fichier `po3_ConsolePlusPlus.ini` généré est isolé dans un mod dédié.

---

### 33. Installation de Scaleform Translation Plus Plus NG

**Objectif :**  
Ajouter un utilitaire d’interface utile aux traductions et menus Scaleform.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/77359

**Résultat attendu :**  
`Scaleform Translation Plus Plus NG` est installé, coché, et le jeu démarre correctement.

---

### 34. Installation d’Auto Input Switch

**Objectif :**  
Permettre une meilleure gestion automatique clavier/manette.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/54309

**Résultat attendu :**  
`Auto Input Switch` est installé, coché, et le jeu démarre correctement.

---

### 35. Installation de dTry’s Key Utils

**Objectif :**  
Ajouter une dépendance de gestion avancée des touches pour certains mods.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/69944

**Résultat attendu :**  
`dTry’s Key Utils` est installé, coché, et le jeu démarre correctement.

---

### 36. Installation d’ENB Helper SE

**Objectif :**  
Ajouter le prérequis SKSE nécessaire aux futurs systèmes ENB/météo/éclairage.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/23174

**Résultat attendu :**  
`ENB Helper SE` est installé, coché, et le jeu démarre correctement.

---

### 37. Installation de Better Jumping SE

**Objectif :**  
Ajouter un plugin SKSE de confort pour le saut.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/18967

**Résultat attendu :**  
`Better Jumping SE` est installé, coché, et le jeu démarre correctement.

---

### 38. Installation de Dynamic Activation Key

**Objectif :**  
Ajouter un utilitaire d’activation moderne pour les futurs systèmes d’interaction.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/96273

**Résultat attendu :**  
`Dynamic Activation Key` est installé, coché, et le jeu démarre correctement.

---

### 39. Installation de Behavior Data Injector

**Objectif :**  
Ajouter une dépendance moderne pour certains systèmes d’animations et comportements.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/78146

**Résultat attendu :**  
`Behavior Data Injector` est installé, coché, et le jeu démarre correctement.

---

### 40. Installation de SkyPatcher

**Objectif :**  
Ajouter un système de patching dynamique sans multiplier les plugins `.esp`.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/106659

**Résultat attendu :**  
`SkyPatcher` est installé, coché, et le jeu démarre correctement.

---

### 41. Ajout de Kris’s Papyrus Extender en réserve

**Objectif :**  
Préparer une dépendance potentielle sans l’activer dans la base actuelle.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/115164

**Résultat attendu :**  
`Kris's Papyrus Extender - DECOCHE / RESERVE` est installé mais décoché.

---

### 42. Installation de Vanilla Script MicroOptimizations

**Objectif :**  
Optimiser certains scripts vanilla sans modifier la logique globale du jeu.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/54061

**Résultat attendu :**  
`Vanilla Script MicroOptimizations` est installé, coché, et placé juste après USSEP une fois celui-ci installé.

---

### 43. Installation de USSEP 4.2.5b

**Objectif :**  
Installer le patch communautaire principal compatible Skyrim SE 1.5.97.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/266?tab=files&file_id=209150

**Résultat attendu :**  
`Unofficial Skyrim Special Edition Patch - USSEP 4.2.5b` est installé, coché, et `Unofficial Skyrim Special Edition Patch.esp` est actif.

---

### 44. Installation de Unofficial Skyrim Creation Club Content Patch

**Objectif :**  
Corriger le contenu Creation Club / AE conservé avec le downgrade Best of Both Worlds.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/18975

**Résultat attendu :**  
`Unofficial Skyrim Creation Club Content Patch` est installé en option **Merged**, coché, sans missing master.

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

### 49. Préparation du bloc Bug Fixes vanilla

**Objectif :**  
Préparer le passage du socle SKSE / core utilities vers le bloc de correctifs vanilla simples.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le profil `00 - SKYFORGE Base` reste stable avant l’installation des correctifs de quêtes et scripts vanilla.

**Test de validation :**  
Le jeu démarre via SKSE depuis MO2, atteint le menu principal, et `Overwrite` reste vide.

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

### 83. Bloc SMIM / Material Fix

**Objectif :**  
Installer le socle meshes vanilla principal et son correctif material.

**Liens :**

- Static Mesh Improvement Mod - SMIM  
  https://www.nexusmods.com/skyrimspecialedition/mods/659

- Static Mesh improvement Mod - SMIM - Quality Addon  
  https://www.nexusmods.com/skyrimspecialedition/mods/44388

- Unofficial Material Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/21027

**Placement MO2 retenu :**

Dans `05 - VISUAL BASE MESHES TEXTURES` :

1. `Static Mesh Improvement Mod`
2. `Static Mesh improvement Mod - SMIM - Quality Addon`
3. `Unofficial Material Fix`

**Notes :**

- SMIM et SMIM Quality Addon sont placés dans le séparateur visuel, pas dans le bloc bug fixes.
- `Unofficial Material Fix` reste aussi dans `05 - VISUAL BASE MESHES TEXTURES`, après SMIM, afin de gagner les conflits nécessaires.
- `SMIM Quality Addon` gagne sur SMIM.
- `Unofficial Material Fix` gagne après SMIM / SMIM Quality Addon si conflit.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 83 validée.

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

### 97. Installation de NL_MCM - A Modular MCM Framework

**Objectif :**  
Installer une dépendance MCM modulaire utilisée par certains mods modernes.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/49127

**Placement MO2 :**  
Dans `01 - SKSE PLUGINS & CORE UTILITIES`, juste après `MCM Helper SE`.

**Résultat attendu :**  
`NL_MCM - A Modular MCM Framework` est installé et coché.

**Note :**  
Ce mod est une dépendance MCM.  
Il ne détermine pas encore le choix final de l’interface UI SKYFORGE.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, aucun missing master, `Overwrite` vide.

**Statut :**  
Étape 97 validée.

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

## État validé après l’étape 101

**Objectif :**  
Confirmer que la base technique SKYFORGE reste stable après l’ajout des correctifs Bug Fixes / Engine Patches jusqu’à l’étape 101.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé sur les derniers tests : OK
- `Overwrite` vide : OK

**Dernière étape validée :**

`Étape 101 — Installation de Best In Class`

**Module principal en cours :**

`02 - BUG FIXES & ENGINE PATCHES`

**Modules déjà touchés ponctuellement :**

- `01 - SKSE PLUGINS & CORE UTILITIES` : ajout de `NL_MCM - A Modular MCM Framework`.
- `05 - VISUAL BASE MESHES TEXTURES` : ajout de SMIM, SMIM Quality Addon et Unofficial Material Fix.
- `13 - SEXLAB CORE ADULT FRAMEWORKS` : ajout en réserve décochée du patch `MuJointFix - Sexlab Ostim Patch`.

**Décisions importantes retenues :**

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

---

## À compléter plus tard

Les sections suivantes seront documentées au fur et à mesure de la construction du modpack :

1. UI avancée et HUD.
2. Audio, musiques et voix.
3. Base graphique, meshes et textures.
4. Paysages, herbes, arbres et eau.
5. Villes, villages, intérieurs et éclairage.
6. Corps, races, NPC appearance.
7. Skeleton, physics et animations.
8. Gameplay, combat, magie et perks.
9. Quêtes, mondes, followers et extensions.
10. Survie, immersion et roleplay.
11. SexLab core et frameworks adultes.
12. Défaite, slavery, prostitution et systèmes Nefaram.
13. Armures, vêtements, outfits et NSFW.
14. Patches de compatibilité.
15. Conflict resolution final.
16. Génération BodySlide.
17. Nemesis / Pandora / FNIS selon décision finale.
18. LOD, TexGen et DynDOLOD.
19. Tests de stabilité prolongés.
20. Préparation éventuelle Wabbajack.
