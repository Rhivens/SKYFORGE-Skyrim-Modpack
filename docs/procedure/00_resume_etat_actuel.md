# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 185

**Objectif :**  
Confirmer que SKYFORGE reste stable après la clôture provisoire du module UI/HUD/Menus, l’installation de `Skyrim Unbound Reborn` comme départ alternatif officiel, puis l’entrée dans le module Audio / Music / Sounds jusqu’au patch ASIF pour RISE.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Tests ingame limités à la salle de départ Skyrim Unbound : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé sur les derniers tests : OK
- `Overwrite` vide : OK

**Dernière étape validée :**

`Étape 185 — Patch ASIF pour RISE`

**Module en cours :**

`04 - AUDIO MUSIC SOUNDS`

**État UI/HUD/Menus :**  
Le module `03 - UI HUD MENUS` est provisoirement clos après l’étape 178.

**Départ alternatif :**

- `Skyrim Unbound Reborn - A REINSTALL PLUS TARD` est installé et validé.
- Les tests ingame restent limités à la salle de départ.
- Les sauvegardes de test / autosaves devront être supprimées avant la partie finale.

**Bloc audio actuel recommandé :**

- `Sound Record Distributor`
- `Acoustic Space Improvement Fixes - SkyPatcher`
- `Audio Overhaul for Skyrim SE - A REINSTALL PLUS TARD`
- `Immersive Sounds - Compendium - A REINSTALL PLUS TARD`
- `Audio Overhaul - Immersive Sounds Integration`
- `Regional Sounds Expansion`
- `Reverb Interior Sounds Expansion`

**Décisions importantes retenues :**

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- `Skyrim Unbound` est retenu comme départ alternatif officiel de SKYFORGE.
- `Alternate Start` / `Alternate Perspective` ne seront pas utilisés comme départ principal.
- Les tests ingame restent limités à la salle de départ tant que la base globale n’est pas suffisamment avancée.
- Les sauvegardes techniques temporaires créées pour tester `Skyrim Unbound` devront être supprimées avant la vraie partie finale.
- Le crosshair vanilla de Skyrim doit être conservé.
- `Contextual Crosshair` n’est pas installé.
- `Edge UI` est abandonné et supprimé.
- `Vel’dun UI` reste l’interface principale actuelle de SKYFORGE.
- `SkyHUD`, `Vel’dun UI`, `Atlas Map Markers`, `Skyrim Unbound Reborn`, `Audio Overhaul for Skyrim SE` et `Immersive Sounds - Compendium` gardent une logique de réinstallation future si les patches ou choix FOMOD doivent être revus.
- `RaceMenu Undress` affiche `$Undress slider` : correction ou acceptation à vérifier plus tard.
- `Better AltTab` est à installer plus tard avec test individuel ALT+TAB.
- `Show Follower Carry Weight` / `Show Mount Carry Weight` sont différés à cause de `Rogue’s Gallery`.
- `Too many notifications` est différé pour éviter doublon avec `Notification Log SSE` + `Notification Filter`.
- `Photo Mode`, `HideUI` et les ajouts cosmétiques de menu principal sont différés.
- `AOS` et `ISC` restent marqués `A REINSTALL PLUS TARD` pour choix FOMOD conditionnels ou subjectifs.
- `ASIF` a été réinstallé avec le patch `RISE` activé.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 186`

État de départ :

- Dernière étape validée : Étape 185
- Module en cours : `04 - AUDIO MUSIC SOUNDS`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Tests ingame limités à la salle de départ Skyrim Unbound : OK
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
