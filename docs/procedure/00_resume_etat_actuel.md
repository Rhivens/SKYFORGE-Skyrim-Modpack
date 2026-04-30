# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 154

**Objectif :**  
Confirmer que la base technique SKYFORGE reste stable après l’ajout des correctifs Bug Fixes / Engine Patches, des compléments SKSE/Core Utilities et du module UI/HUD/Menus jusqu’à l’installation minimale de Vel’dun UI.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé sur les derniers tests : OK
- `Overwrite` vide : OK
- Vel’dun UI visible au menu principal : OK

**Dernière étape validée :**

`Étape 154 — Vel’dun UI minimal`

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
- `Vel'dun UI - A REINSTALL PLUS TARD`

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
- `Vel’dun UI` devient l’interface principale actuelle de SKYFORGE.
- `SkyHUD` et `Vel’dun UI` sont installés en version minimale et renommés `A REINSTALL PLUS TARD` afin de permettre une réinstallation propre quand les patches utiles seront nécessaires.
- Les icônes `Dragonborn Reskin` sont différées et seront testées plus tard avec Wheeler, STB Widgets et le travail inventaire / favoris / icônes SkyUI.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 155`

État de départ :

- Dernière étape validée : Étape 154
- Module en cours : `03 - UI HUD MENUS`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- Vel’dun UI visible au menu principal : OK

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
