# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 203

**Objectif :**  
Confirmer que SKYFORGE reste stable après la clôture provisoire du module `04 - AUDIO MUSIC SOUNDS`.

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

`Étape 203 — Clôture provisoire audio`

**Module clos provisoirement :**

`04 - AUDIO MUSIC SOUNDS`

---

## État UI/HUD/Menus

Le module `03 - UI HUD MENUS` est provisoirement clos après l’étape 178.

**Décisions UI importantes :**

- `Vel’dun UI` reste l’interface principale actuelle de SKYFORGE.
- `Edge UI` est abandonné et supprimé.
- Le crosshair vanilla de Skyrim doit être conservé.
- `QuickLoot IE` est différé / non installé.
- Les patches Vel’dun UI restent différés jusqu’à confirmation / installation des mods parents concernés.

---

## Départ alternatif

- `Skyrim Unbound Reborn - A REINSTALL PLUS TARD` est installé et validé.
- `Skyrim Unbound` est le départ alternatif officiel de SKYFORGE.
- Les tests ingame restent limités à la salle de départ.
- Les sauvegardes de test / autosaves devront être supprimées avant la partie finale.

---

## Bloc audio final actif après étape 203

- `Sound Record Distributor`
- `Acoustic Space Improvement Fixes - SkyPatcher`
- `Audio Overhaul for Skyrim (4.1.3) - A REINSTALL PLUS TARD`
- `Immersive Sounds - Compendium - A REINSTALL PLUS TARD`
- `Audio Overhaul - Immersive Sounds Integration (AOS - ISC Compatibility Patch)`
- `Regional Sounds Expansion (SRD - Wilds Dungeons Towns Ambience Birds - Fixes)`
- `Reverb Interior Sounds Expansion`
- `Quiet Better Jumping for CGO - Audio Overhaul - Immersive Sounds Integration`
- `Thundering Shouts`
- `Authentic Wolf Howls and Aggro`
- `More Painful Death Sounds SE`
- `Update Plugin More Painful Death Sounds SE`
- `50 Percent Chance More Painful Death Sounds SE`
- `Blackreach Eerie Ambience`
- `Nordic Winds`
- `Ambient Warfare`
- `Distant Rolling Thunder`
- `The Sounds of Towns and Cities`
- `Solstheim Exterior Soundscapes`
- `Volkihar Soundscape Overhaul - A REINSTALL PLUS TARD`
- `Revenant Spirits of the Soul Cairn`
- `The Standing Sound Stones - A REINSTALL PLUS TARD`
- `Bleeding Edge - Bladed Weapons SFX Overhaul - A REINSTALL PLUS TARD`
- `Skullbreaker - Blunt Weapons SFX`
- `Bulwark - Shield Audio Overhaul`
- `Wildwood Echoes`
- `Murder of Songbirds`
- `Combat Music Fix NG Updated`
- `New Game Sound on Continue (SKSE)`
- `Still - Skyrim Inspired Music`
- `Chapter II - Jeremy Soule Inspired Music`
- `Melodies of Civilization - Skyrim Fan-Made Music`
- `Hun Lovaas - Skyrim Fan-Made combat music`
- `The Northerner Diaries - Immersive Edition (music by Jeremy Soule)`
- `The Elder Songs - Complete - A REINSTALL PLUS TARD`
- `Songs to Play Skyrim to - A Music Mod All in One`
- `The Southerner Diaries - A Soundtrack Expansion`
- `Symphonic Soundtrack - Extension HIGH QUALITY`
- `Ragnarok - Viking Battle Music`
- `BA Bard Songs`

**Mods présents mais non actifs / différés :**

- `Magic College Music - Songs for Academy - DECOCHE FORM 43`
- `Phoenix Compendium - DIFFÉRÉ`
- `Whispering Tomes of Apocrypha - DIFFÉRÉ`
- `Nyghtfall - DIFFÉRÉ`
- `Dark Era - DIFFÉRÉ`
- `Music Mods Merged SSE Edition - EXCLU POUR L’INSTANT`

---

## Décisions importantes retenues

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- Les tests ingame restent limités à la salle de départ Skyrim Unbound tant que la base globale n’est pas suffisamment avancée.
- Les sauvegardes techniques temporaires créées pour tester `Skyrim Unbound` devront être supprimées avant la vraie partie finale.
- `AOS`, `ISC`, `Volkihar Soundscape Overhaul`, `The Standing Sound Stones`, `Bleeding Edge` et `The Elder Songs` gardent une logique de réinstallation future.
- `Combat Music Fix NG Updated` et `New Game Sound on Continue (SKSE)` ont été testés individuellement car plugins SKSE / DLL.
- `Magic College Music` est désactivé à cause du warning Form 43.
- Les erreurs de liens corrigées pendant le module audio sont documentées dans les étapes correspondantes.
- Corrections de nommage à faire dans MO2 : supprimer les doubles tirets sur `Audio Overhaul for Skyrim (4.1.3)` et `Bleeding Edge - Bladed Weapons SFX Overhaul`.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 204`

État de départ :

- Dernière étape validée : Étape 203
- Module audio provisoirement clos : `04 - AUDIO MUSIC SOUNDS`
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
