# Procédure de reproduction SKYFORGE sur un autre PC

> Procédure personnelle du projet **SKYFORGE**.  
> Ce dépôt ne doit pas contenir de mods, d’archives Nexus, de fichiers Bethesda, de fichiers Creation Club, de fichiers SKSE, d’ENB, ni aucun fichier soumis à permissions ou redistribution restreinte.  
> Ce document sert uniquement à décrire la procédure de reproduction de l’environnement SKYFORGE.

---

## Étapes réalisées

### 1. Préparation de Skyrim

**Objectif :**  
Installer Skyrim Anniversary Edition via Steam et lancer le jeu une première fois pour initialiser les fichiers de base et le contenu AE / Creation Club.

**Résultat attendu :**  
Skyrim est installé, initialisé, et le contenu Anniversary Edition est présent.

---

### 2. Verrouillage des mises à jour Steam

**Objectif :**  
Empêcher Steam de mettre à jour Skyrim automatiquement pendant la construction du modpack.

**Résultat attendu :**  
L’option Steam est réglée sur “Attendre que je lance le jeu” et le fichier `appmanifest_489830.acf` est en lecture seule.

---

### 3. Création du dossier Stock Game SKYFORGE

**Objectif :**  
Créer une copie isolée de Skyrim dans un dossier dédié au projet SKYFORGE.

**Résultat attendu :**  
Le dossier `D:\SKYFORGE\Stock Game\` contient une copie complète du dossier Skyrim Steam.

---

### 4. Downgrade vers Skyrim SE 1.5.97

**Objectif :**  
Appliquer le downgrade **Best of Both Worlds** sur le Stock Game afin de conserver le contenu AE tout en utilisant l’exécutable Skyrim SE 1.5.97.

**Résultat attendu :**  
`SkyrimSE.exe` dans `D:\SKYFORGE\Stock Game\` est en version `1.5.97.0`.

---

### 5. Installation de SKSE 1.5.97

**Objectif :**  
Installer SKSE compatible Skyrim SE 1.5.97 dans le Stock Game.

**Résultat attendu :**  
`skse64_loader.exe`, `skse64_1_5_97.dll` et `skse64_steam_loader.dll` sont présents dans `D:\SKYFORGE\Stock Game\`.

---

### 6. Installation de Mod Organizer 2 portable

**Objectif :**  
Installer MO2 en instance portable dédiée à SKYFORGE.

**Résultat attendu :**  
MO2 2.4.4 est installé dans `D:\SKYFORGE\MO2\` et pointe vers `D:\SKYFORGE\Stock Game\SkyrimSE.exe`.

---

### 7. Création du profil MO2 de base

**Objectif :**  
Créer un profil isolé pour SKYFORGE.

**Résultat attendu :**  
Le profil `00 - SKYFORGE Base` existe avec sauvegardes et fichiers INI spécifiques au profil activés.

---

### 8. Création de l’ossature des séparateurs MO2

**Objectif :**  
Créer une structure visuelle propre dans le panneau gauche de MO2.

**Résultat attendu :**  
Les séparateurs SKYFORGE sont créés, de `00 - BASE GAME` à `18 - TRADUCTIONS FR`, avec `Overwrite` conservé tout en bas.

---

### 9. Installation d’Address Library

**Objectif :**  
Installer la dépendance SKSE nécessaire aux plugins modernes.

**Résultat attendu :**  
`Address Library for SKSE Plugins` est installé, coché, et placé sous `01 - SKSE PLUGINS & CORE UTILITIES`.

---

### 10. Installation de Backported Extended ESL Support

**Objectif :**  
Permettre à Skyrim SE 1.5.97 de gérer correctement les plugins ESL récents.

**Résultat attendu :**  
`Backported Extended ESL Support` est installé, coché, et placé sous `01 - SKSE PLUGINS & CORE UTILITIES`.

---

### 11. Premier test de lancement SKSE

**Objectif :**  
Vérifier que la base Stock Game + SKSE + Address Library + BEES démarre correctement.

**Résultat attendu :**  
Le jeu atteint le menu principal via SKSE lancé depuis MO2.

---

### 12. Installation de Crash Logger

**Objectif :**  
Ajouter un outil de diagnostic pour les futurs crashs.

**Résultat attendu :**  
`Crash Logger SSE AE VR - PDB support` version Skyrim SE 1.5.97 est installé, coché, et le jeu démarre correctement.

---

### 13. Installation de SSE Engine Fixes

**Objectif :**  
Installer les correctifs moteur essentiels pour Skyrim SE 1.5.97.

**Résultat attendu :**  
La partie MO2 et la partie manuelle de SSE Engine Fixes sont installées, et le jeu atteint le menu principal sans crash.

---

### 14. Installation de Bug Fixes SSE

**Objectif :**  
Ajouter des corrections SKSE complémentaires au moteur du jeu.

**Résultat attendu :**  
`Bug Fixes SSE` est installé, coché, et le jeu démarre correctement.

---

### 15. Installation de Scrambled Bugs

**Objectif :**  
Ajouter des corrections configurables pour plusieurs bugs du moteur et du gameplay vanilla.

**Résultat attendu :**  
`Scrambled Bugs` est installé, coché, et le jeu démarre correctement.

---

### 16. Installation de PapyrusUtil SE

**Objectif :**  
Ajouter une dépendance Papyrus majeure utilisée par de nombreux mods.

**Résultat attendu :**  
`PapyrusUtil SE` est installé, coché, et le jeu démarre correctement.

---

### 17. Installation de powerofthree’s Papyrus Extender

**Objectif :**  
Ajouter des fonctions Papyrus étendues utilisées par de nombreux mods modernes.

**Résultat attendu :**  
`powerofthree's Papyrus Extender` est installé, coché, et le jeu démarre correctement.

---

### 18. Installation de JContainers SE

**Objectif :**  
Ajouter une bibliothèque de stockage et manipulation de données utilisée par plusieurs frameworks.

**Résultat attendu :**  
`JContainers SE` est installé, coché, et le jeu démarre correctement.

---

### 19. Installation de powerofthree’s Tweaks

**Objectif :**  
Ajouter les tweaks SKSE de powerofthree et générer leur configuration.

**Résultat attendu :**  
`powerofthree's Tweaks` est installé, coché, et son fichier `po3_Tweaks.ini` généré est isolé dans un mod dédié.

---

### 20. Installation de MCM Helper

**Objectif :**  
Ajouter la dépendance moderne nécessaire aux menus MCM de nombreux mods.

**Résultat attendu :**  
`MCM Helper` est installé et coché, avec ses dépendances satisfaites.

---

### 21. Installation de SkyUI

**Objectif :**  
Installer l’interface de base nécessaire aux menus MCM.

**Résultat attendu :**  
`SkyUI_5_2_SE` est installé, coché, et le missing master de `MCMHelper.esp` est résolu.

---

### 22. Installation de ConsoleUtilSSE NG

**Objectif :**  
Ajouter une dépendance SKSE utilisée par plusieurs mods modernes.

**Résultat attendu :**  
`ConsoleUtilSSE NG` est installé, coché, et le jeu démarre correctement.

---

### 23. Installation de Fuz Ro D-oh

**Objectif :**  
Ajouter le support des dialogues silencieux pour les mods de quêtes, roleplay et systèmes adultes.

**Résultat attendu :**  
`Fuz Ro D-oh - Silent Voice` est installé, coché, et son fichier `Fuz Ro D'oh.ini` généré est isolé dans un mod dédié.

---

### 24. Installation de SPID

**Objectif :**  
Ajouter le distributeur de sorts, perks, objets et effets utilisé par les listes modernes.

**Résultat attendu :**  
`Spell Perk Item Distributor` est installé, coché, et son fichier `po3_SpellPerkItemDistributor.ini` généré est isolé dans un mod dédié.

---

### 25. Installation de KID

**Objectif :**  
Ajouter le distributeur de keywords pour objets et records.

**Résultat attendu :**  
`Keyword Item Distributor` est installé, coché, et le jeu démarre correctement.

---

### 26. Installation de Base Object Swapper

**Objectif :**  
Ajouter le système de remplacement dynamique d’objets de base.

**Résultat attendu :**  
`Base Object Swapper` est installé, coché, et le jeu démarre correctement.

---

### 27. Installation de FormList Manipulator

**Objectif :**  
Ajouter la manipulation dynamique de FormLists.

**Résultat attendu :**  
`FormList Manipulator - FLM` est installé, coché, et le jeu démarre correctement.

---

### 28. Installation d’AnimObject Swapper

**Objectif :**  
Ajouter le système de remplacement dynamique d’objets d’animation.

**Résultat attendu :**  
`AnimObject Swapper` est installé, coché, et le jeu démarre correctement.

---

### 29. Installation de FISSES

**Objectif :**  
Ajouter l’interface de sauvegarde/chargement de configurations utilisée par certains mods.

**Résultat attendu :**  
`FileAccess Interface for Skyrim SE Scripts - FISSES` est installé, coché, et le jeu démarre correctement.

---

### 30. Installation de Console Commands Extender

**Objectif :**  
Étendre les commandes console disponibles pour les mods et le diagnostic.

**Résultat attendu :**  
`Console Commands Extender` est installé, coché, et le jeu démarre correctement.

---

### 31. Installation de More Informative Console

**Objectif :**  
Améliorer les informations affichées dans la console de Skyrim.

**Résultat attendu :**  
`More Informative Console` est installé, coché, et le jeu démarre correctement.

---

### 32. Installation de ConsolePlusPlus

**Objectif :**  
Améliorer l’utilisation de la console et générer sa configuration.

**Résultat attendu :**  
`ConsolePlusPlus` est installé, coché, et son fichier `po3_ConsolePlusPlus.ini` généré est isolé dans un mod dédié.

---

### 33. Installation de Scaleform Translation Plus Plus NG

**Objectif :**  
Ajouter un utilitaire d’interface utile aux traductions et menus Scaleform.

**Résultat attendu :**  
`Scaleform Translation Plus Plus NG` est installé, coché, et le jeu démarre correctement.

---

### 34. Installation d’Auto Input Switch

**Objectif :**  
Permettre une meilleure gestion automatique clavier/manette.

**Résultat attendu :**  
`Auto Input Switch` est installé, coché, et le jeu démarre correctement.

---

### 35. Installation de dTry’s Key Utils

**Objectif :**  
Ajouter une dépendance de gestion avancée des touches pour certains mods.

**Résultat attendu :**  
`dTry’s Key Utils` est installé, coché, et le jeu démarre correctement.

---

### 36. Installation d’ENB Helper SE

**Objectif :**  
Ajouter le prérequis SKSE nécessaire aux futurs systèmes ENB/météo/éclairage.

**Résultat attendu :**  
`ENB Helper SE` est installé, coché, et le jeu démarre correctement.

---

### 37. Installation de Better Jumping SE

**Objectif :**  
Ajouter un plugin SKSE de confort pour le saut.

**Résultat attendu :**  
`Better Jumping SE` est installé, coché, et le jeu démarre correctement.

---

### 38. Installation de Dynamic Activation Key

**Objectif :**  
Ajouter un utilitaire d’activation moderne pour les futurs systèmes d’interaction.

**Résultat attendu :**  
`Dynamic Activation Key` est installé, coché, et le jeu démarre correctement.

---

### 39. Installation de Behavior Data Injector

**Objectif :**  
Ajouter une dépendance moderne pour certains systèmes d’animations et comportements.

**Résultat attendu :**  
`Behavior Data Injector` est installé, coché, et le jeu démarre correctement.

---

### 40. Installation de SkyPatcher

**Objectif :**  
Ajouter un système de patching dynamique sans multiplier les plugins `.esp`.

**Résultat attendu :**  
`SkyPatcher` est installé, coché, et le jeu démarre correctement.

---

### 41. Ajout de Kris’s Papyrus Extender en réserve

**Objectif :**  
Préparer une dépendance potentielle sans l’activer dans la base actuelle.

**Résultat attendu :**  
`Kris's Papyrus Extender - DECOCHE / RESERVE` est installé mais décoché.

---

### 42. Installation de Vanilla Script MicroOptimizations

**Objectif :**  
Optimiser certains scripts vanilla sans modifier la logique globale du jeu.

**Résultat attendu :**  
`Vanilla Script MicroOptimizations` est installé, coché, et placé juste après USSEP une fois celui-ci installé.

---

### 43. Installation de USSEP 4.2.5b

**Objectif :**  
Installer le patch communautaire principal compatible Skyrim SE 1.5.97.

**Résultat attendu :**  
`Unofficial Skyrim Special Edition Patch - USSEP 4.2.5b` est installé, coché, et `Unofficial Skyrim Special Edition Patch.esp` est actif.

---

### 44. Installation de Unofficial Skyrim Creation Club Content Patch

**Objectif :**  
Corriger le contenu Creation Club / AE conservé avec le downgrade Best of Both Worlds.

**Résultat attendu :**  
`Unofficial Skyrim Creation Club Content Patch` est installé en option **Merged**, coché, sans missing master.

---

## État validé à ce stade

**Objectif :**  
Confirmer que la base technique SKYFORGE est stable avant d’ajouter les modules lourds.

**Résultat attendu :**  
Le jeu démarre via SKSE depuis MO2, atteint le menu principal, ne génère aucun fichier dans `Overwrite`, et ne présente aucun missing master.

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
