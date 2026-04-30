# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 150

**Objectif :**  
Confirmer que la base technique SKYFORGE reste stable après l’ajout des correctifs Bug Fixes / Engine Patches, des compléments SKSE/Core Utilities et du début du module UI/HUD/Menus jusqu’à l’étape 150.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé sur les derniers tests : OK
- `Overwrite` vide : OK

**Dernière étape validée :**

`Étape 150 — Security Overhaul SKSE - Some More Locks / Extra Locks`

**Module récent :**

`03 - UI HUD MENUS`

**Modules touchés depuis l’étape 101 :**

- `01 - SKSE PLUGINS & CORE UTILITIES` : SKSE Menu Framework, Execute Hotkeys, Container Item Distributor, Andrealphus' Papyrus Functions, MergeMapper, Perk Entry Point Extender, Dynamic String Distributor, KiLoader, Media Keys Fix SKSE, DPI Scaling Fix.
- `02 - BUG FIXES & ENGINE PATCHES` : ENB Terrain Blending Fix, Dangerous Trap Fixes, EPW4NPCs, Lightened Skyrim BOS, bc036's Tweaks, Andrealletius' Exploit Fixes, HearthFires Customizable Fertile Soil, Mum's the Word NG, Magic Fixes and Tweaks SKSE, Thalmor Don't Report Crimes To Stormcloaks, Persistent Favorites, To Your Face.
- `03 - UI HUD MENUS` : Regional Save Names, Notification Log SSE, Yes Im Sure, Copy and Paste in Console, Essential Favorites, Favorite Misc Items, Better Container Controls for SkyUI, Better MessageBox Controls, Better Dialogue Controls, Read Or Take SKSE, Use Or Take SKSE, Improved Help Command, Disable Numpad, Notification Filter, Security Overhaul SKSE.
- `05 - VISUAL BASE MESHES TEXTURES` : SMIM / SMIM Quality Addon / Unofficial Material Fix restent prioritaires sur les conflits Security Overhaul extras.

**Décisions importantes retenues :**

- LOOT / ordre de chargement global : toujours différé.
- Documentation : mise à jour groupée et reclassée par fichiers thématiques.
- Les petits fixes non sensibles peuvent être installés par blocs, avec un seul test final.
- Les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes doivent être testés individuellement.
- Les étapes conservent une numérotation chronologique globale même si elles sont rangées dans des fichiers thématiques différents.
- Les fichiers trop longs peuvent être prolongés avec une partie suivante.
- `ENB Extender Skyrim - DECOCHE RESERVE ENB` reste désactivé jusqu’à installation d’un ENB binaire actif avec `d3d11.dll`.
- `Notification Filter` est installé, mais sa configuration INI est différée.
- `Security Overhaul SKSE - Some More Locks` est installé en base, mais ses patches optionnels seront revus plus tard selon les modules clutter / strongboxes / meshes.
- `Magic Fixes and Tweaks SKSE` est installé en base ; les options `Revamped Costs` et `Spell Binding` sont différées.
- `Andrealletius' Exploit Fixes` est installé avec une sélection prudente ; ses options FOMOD seront revues plus tard selon magie / alchimie / perks / lieux.
- Le futur module carte sera construit autour de `Flat World Map Framework` et `Skyrim Paper Map by Caro Tuts for FWMF`. `Atlas Map Markers` reste différé.
- PC principal : RTX 4070 12 Go. Prévoir plus tard un module performance avec Skyrim Upscaler DLSS / DLAA, ENB Manager, ENB retenu, ReShade éventuel et réglages SSE Display Tweaks.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 151`

État de départ :

- Dernière étape validée : Étape 150
- Module récent : `03 - UI HUD MENUS`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

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
