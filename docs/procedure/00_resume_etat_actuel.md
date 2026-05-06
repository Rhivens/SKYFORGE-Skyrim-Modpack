# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 220

**Objectif :**  
Confirmer que SKYFORGE reste stable après le contrôle du module `05 - VISUAL BASE MESHES TEXTURES` et l’ouverture du module `06 - LANDSCAPE GRASS TREES WATER` jusqu’à l’installation de `Happy Little Trees`.

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

`Étape 220 — Happy Little Trees`

**Module en cours :**

`06 - LANDSCAPE GRASS TREES WATER`

---

## État du module 05 - Visual base meshes & textures

**Étapes documentées :**

- `Étape 204 — Vérification du socle SMIM`
- `Étape 205 — Assorted Mesh Fixes déjà couvert`
- `Étape 206 — Vérification des mesh fixes existants`
- `Étape 207 — Mesh Patch for Various Mods`
- `Étape 208 — Particle Patch`
- `Étape 209 — Patch Particle / Unofficial Material Fix annulé / différé`
- `Étape 210 — Contrôle final module 05 + correction audio`

**État validé :**

- `Static Mesh Improvement Mod` : OK
- `Static Mesh improvement Mod - SMIM - Quality Addon` : OK
- `Unofficial Material Fix` : OK
- `Particle Patch.esp` actif : OK
- Patches meshes utiles installés séparément : OK
- `AcousticTemplateFixes_ReverbInteriorSounds.esp` réactivé : OK

---

## État du module 06 - Landscape / grass / trees / water

**Ordre actuel confirmé :**

```text
[06 - LANDSCAPE GRASS TREES WATER]
Terrain Fixes for CC Mods
Landscape Fixes For Grass Mods
Complementary Grass Fixes - A REINSTALL PLUS TARD
Skyrim Landscape and Water Fixes - A REINSTALL PLUS TARD
Majestic Mountains - A REINSTALL PLUS TARD
Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD (décoché)
Happy Little Trees - A REINSTALL PLUS TARD
Happy Little Trees - HLT Patch
```

**Mods / décisions importants :**

- `Terrain Fixes for CC Mods` installé avec option `All CC Mods`.
- `Landscape Fixes For Grass Mods` installé et marqué `A REINSTALL PLUS TARD`.
- `Complementary Grass Fixes` installé en core uniquement, patches optionnels différés.
- `Skyrim Landscape and Water Fixes` installé et marqué `A REINSTALL PLUS TARD`.
- `Majestic Mountains` installé avec `Landscape ESM : AE version`, malgré le runtime 1.5.97, car le contenu AE / CC est conservé.
- `Atlantean Landscape -Complete- 2K` est installé mais décoché à cause du master manquant `Parallax TXST Fixes.esp`.
- `Happy Little Trees` installé en option `Default`, alternatives neige différées.

---

## Décisions importantes retenues

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- Les tests ingame restent limités à la salle de départ Skyrim Unbound tant que la base globale n’est pas suffisamment avancée.
- Les sauvegardes techniques temporaires créées pour tester `Skyrim Unbound` devront être supprimées avant la vraie partie finale.
- `AOS`, `ISC`, `Volkihar Soundscape Overhaul`, `The Standing Sound Stones`, `Bleeding Edge` et `The Elder Songs` gardent une logique de réinstallation future.
- `Magic College Music` est désactivé à cause du warning Form 43.
- `Atlantean Landscape` reste décoché jusqu’au futur bloc `Parallax / Complex Terrain / ENB / textures paysage avancées`.
- Textures 2K par défaut si disponibles ; 1K pour petits objets / optimisation ; 4K uniquement pour éléments très visibles si justifié ; 8K exclu par défaut.
- Les patches `Complementary Grass Fixes`, `SLaWF`, `Majestic Mountains`, `Happy Little Trees` et autres éléments paysage seront revus selon les futurs modules villes / quêtes / herbes / météo / ENB.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 221`

Sujet prévu :

`Contrôle ordre + suite arbres / herbe / eau`

État de départ :

- Dernière étape validée : Étape 220
- Module en cours : `06 - LANDSCAPE GRASS TREES WATER`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Tests ingame limités à la salle de départ Skyrim Unbound : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- `Atlantean Landscape` décoché : OK

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
