# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 168

**Objectif :**  
Confirmer que la base technique SKYFORGE reste stable après l’ajout du bloc UI/HUD/Menus avancé : TrueHUD, STB, Wheeler, Infinity UI, Compass Navigation Overhaul, BTPS, gestion MCM, carte locale, menu d’attente et confort HUD léger.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé sur les derniers tests : OK
- `Overwrite` vide : OK

**Dernière étape validée :**

`Étape 168 — Bloc HUD confort léger`

**Module en cours :**

`03 - UI HUD MENUS`

**Mods UI importants actifs à ce stade :**

- `UIExtensions`
- `SkyUI - Ghost Item Bug Fix`
- `moreHUD SE - Light Master - Pre AE`
- `moreHUD Inventory Edition - Loose Version - Pre AE`
- `A Matter of Time - A HUD clock widget`
- `A Matter Of Time - Legacy Settings Loader`
- `SkyHUD - A REINSTALL PLUS TARD`
- `Patch - SkyHUD 0.90.1B`
- `TrueHUD - HUD Additions`
- `STB Widgets`
- `STB Active Effects`
- `Wheeler - Quick Action Wheel Of Skyrim`
- `Infinity UI`
- `Compass Navigation Overhaul`
- `Better Third Person Selection`
- `Dialogue History`
- `Menu Maid 2 - MCM Manager`
- `Menu Maid 2 - Generated INI`
- `Oxygen Meter 2`
- `Show Player In Menus`
- `HD Local Map`
- `Local Map Upgrade`
- `Modern Wait Menu`
- `Horse Stamina HUD - Script-Free`
- `Floating Damage`
- `Vel'dun UI - A REINSTALL PLUS TARD`
- `Dragonborn Reskin - STB Widgets`
- `Dragonborn Reskin - STB Active Effects`
- `Dragonborn - Wheeler Reskin`
- `Dragonborn Reskin - SkyUI Category and Fav Icons`

**Core utilities ajoutées pendant ce bloc :**

- `dMenu`
- `dMenu NG`
- `ImGui Icons`

**Décisions importantes retenues :**

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- Tests limités au menu principal tant que `Skyrim Unbound` n’est pas installé.
- `Skyrim Unbound` est retenu comme départ alternatif officiel de SKYFORGE.
- `Alternate Start` / `Alternate Perspective` ne seront pas utilisés comme départ principal.
- Avant les premiers tests ingame jusqu’à la création de personnage ou spawn joueur, `Skyrim Unbound` devra être installé.
- Le crosshair vanilla de Skyrim doit être conservé.
- `Contextual Crosshair` n’est pas installé.
- `Edge UI` est abandonné et supprimé.
- `Vel’dun UI` reste l’interface principale actuelle de SKYFORGE.
- `SkyHUD` et `Vel’dun UI` sont installés en version minimale et renommés `A REINSTALL PLUS TARD` afin de permettre une réinstallation propre quand les patches utiles seront nécessaires.
- Les patches Vel’dun UI pour `TrueHUD`, `STB Widgets`, `STB Active Effects`, `BTPS`, `Compass Navigation Overhaul`, `MoreHUD`, `Local Map Upgrade` et autres modules parents restent différés.
- `QuickLoot IE` est différé / non installé afin de préserver la logique future SexLab / Devious / Cursed Loot et une fouille plus manuelle des conteneurs.
- `Toggle Compass Hotkey` n’est pas retenu.
- `HideUI` est différé.
- `Photo Mode` est différé jusqu’aux futurs tests ingame / screenshots avec `Skyrim Unbound`.
- Les blocs de mods légers, visuels ou non sensibles peuvent être installés de façon groupée avec un test final.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 169`

État de départ :

- Dernière étape validée : Étape 168
- Module en cours : `03 - UI HUD MENUS`
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
