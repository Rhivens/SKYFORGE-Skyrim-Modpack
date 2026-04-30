# Changelog / validation

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

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
