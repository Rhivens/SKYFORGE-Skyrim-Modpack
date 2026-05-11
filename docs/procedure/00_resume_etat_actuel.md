# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 265

**Objectif :**  
Clôturer temporairement le module `06 - LANDSCAPE GRASS TREES WATER` après contrôle du compteur plugins, vérifications finales et création du profil stable.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- `Atlantean Landscape -Complete- 2K` décoché : OK
- `Ancient Trees Of Skyrim` abandonné / supprimé : OK

**Dernière étape validée :**

`Étape 265 — Profil stable`

**Module clôturé temporairement :**

`06 - LANDSCAPE GRASS TREES WATER`

**Profil stable actuel :**

`SKYFORGE - Stable étape 264 module 06 OK`

**Compteur confirmé :**

- ESP + ESM non-light : `42`

---

## État du module 06 - Landscape / grass / trees / water

**Étapes documentées dans le module :**

- `Étape 211 — Ouverture du module 06`
- `Étape 212 — Terrain Fixes for CC Mods`
- `Étape 213 — Bloc paysage léger`
- `Étape 214 — Contrôle plugins bloc herbe`
- `Étape 215 — Skyrim Landscape and Water Fixes`
- `Étape 216 — Contrôle ordre module 06`
- `Étape 217 — Majestic Mountains`
- `Étape 218 — Contrôle ordre après Majestic Mountains`
- `Étape 219 — Atlantean Landscape suspendu proprement`
- `Étape 220 — Happy Little Trees`
- `Étape 221 — Contrôle ordre + suite arbres / herbe / eau`
- `Étape 222 — Ancient Trees différé`
- `Étape 223 — Dilon Vul`
- `Étape 224 — Pack flore léger`
- `Étape 225 — Pack herbe Cathedral + Origins`
- `Étape 226 — Folkvangr`
- `Étape 227 — QW’s Grass Patch 2`
- `Étape 228 — Test visuel herbe`
- `Étape 229 — Point stable herbe`
- `Étape 230 — Pack ENB Complex Grass`
- `Étape 231 — Contrôle plugins herbe`
- `Étape 232 — Pack eau léger`
- `Étape 233 — Contrôle plugins eau / pluie`
- `Étape 234 — Point de stabilité court`
- `Étape 235 — Water for ENB`
- `Étape 236 — Contrôle plugins Water for ENB`
- `Étape 237 — Test visuel eau en jeu`
- `Étape 238 — Point stable paysage / eau`
- `Étape 239 — Pack effets naturels léger`
- `Étape 240 — Contrôle plugins effets naturels`
- `Étape 241 — Pack petites corrections naturelles`
- `Étape 242 — Contrôle plugins effets naturels`
- `Étape 243 — Pack ciel léger`
- `Étape 244 — Contrôle plugins ciel`
- `Étape 245 — Pack Canticle Tree / Dawnguard`
- `Étape 246 — Contrôle plugins Canticle`
- `Étape 247 — Pack mondes DLC léger, version modifiée`
- `Étape 248 — Contrôle plugins Apocrypha`
- `Étape 249 — Pack petits détails naturels / monde`
- `Étape 250 — Contrôle plugins détails naturels`
- `Étape 251 — Pack léger Sovngarde + Hanging Moss`
- `Étape 252 — Contrôle plugins Sovngarde / Moss`
- `Étape 253 — Pack plantes léger`
- `Étape 254 — Contrôle plugins plantes`
- `Étape 255 — Pack relief léger`
- `Étape 256 — Contrôle plugins relief`
- `Étape 257 — Reprise et compteur plugins`
- `Étape 258 — Bloc Canticle Tree`
- `Étape 259 — Picta Series`
- `Étape 260 — Snowy Surfaces / Omnibus`
- `Étape 261 — Pack ambiance sauvage BOS`
- `Étape 262 — Moulins / cascades`
- `Étape 263 — Ancient Trees Of Skyrim`
- `Étape 264 — Clôture module 06`
- `Étape 265 — Profil stable`

**État validé :**

- Base paysage / relief / montagnes : installée et stable.
- Arbres : `Happy Little Trees` et `Dilon Vul` installés et validés.
- Herbe : Cathedral + Origins + Folkvangr + QW’s Grass Patch 2 installés et test visuel OK.
- Eau : `GKB Waves Reborn`, `Splashes of Storms`, `Water for ENB` installés et test visuel cascade / eau OK.
- Effets naturels / ciel / détails DLC : installés et validés.
- Plantes et relief léger : installés et validés.
- Ambiance sauvage BOS : installée et validée.
- Module 06 clôturé temporairement avec profil stable dédié.

---

## Mods / décisions importants du module 06

- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD` reste installé mais décoché à cause du master manquant `Parallax TXST Fixes.esp`.
- `Ancient Trees Of Skyrim` est abandonné / supprimé après réévaluation des sources Bethesda et Nexus.
- `The Omnibus - Terrain Complex Parallax AiO` est différé.
- `Praedy's Soul Cairn - SE - DIFFERE SKELETON REPLACER` reste différé à cause du prérequis `Skeleton Replacer HD - SE`.
- `Water for ENB - No Parallax - A REINSTALL PLUS TARD` est installé et validé avec les patches retenus.
- `Snowy Surfaces Sound Collision and Aesthetics - A REINSTALL PLUS TARD` est installé avec choix Vanilla / Vanilla Standard Meshes / aucun patch.
- `Remove Hanging Moss From Trees` a été installé en version `1.6`, car la version `1.5` n’était pas disponible.

---

## Décisions importantes retenues

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- Les tests ingame restent courts et ciblés tant que la base globale n’est pas suffisamment avancée.
- Les sauvegardes techniques temporaires créées pour tester `Skyrim Unbound` devront être supprimées avant la vraie partie finale.
- `Atlantean Landscape` reste décoché jusqu’au futur bloc `Parallax / Complex Terrain / ENB / textures paysage avancées`.
- Les patches `Complementary Grass Fixes`, `SLaWF`, `Majestic Mountains`, `Happy Little Trees`, `Water for ENB` et autres éléments paysage pourront être revus selon les futurs modules villes / quêtes / herbes / météo / ENB.
- Textures 2K par défaut si disponibles ; 1K pour petits objets / optimisation ; 4K uniquement pour éléments très visibles si justifié ; 8K exclu par défaut.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 266`

Sujet prévu :

Ouverture du prochain module de construction SKYFORGE.

État de départ :

- Dernière étape validée : Étape 265
- Module 06 clôturé temporairement : OK
- Profil stable actuel : `SKYFORGE - Stable étape 264 module 06 OK`
- ESP + ESM non-light : `42`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- `Atlantean Landscape` décoché : OK
- `Ancient Trees Of Skyrim` abandonné / supprimé : OK

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
