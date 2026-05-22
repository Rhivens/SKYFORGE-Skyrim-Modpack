# Résumé de l’état actuel SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## État validé après l’étape 307

**Objectif :**  
Documenter le bloc villages Darkwater puis le sous-bloc `07.1 - PLAYER HOMES`, incluant les étapes 296 à 306 et la pause GitHub demandée avant de poursuivre le module 07.

**Résultat validé :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun missing master bloquant signalé : OK
- Aucun message DLL bloquant signalé : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- LOD / DynDOLOD non générés : OK
- `Atlantean Landscape -Complete- 2K` décoché : OK

**Dernière étape validée :**

`Étape 307 — Pause GitHub avant suite module 07`

**Dernière étape d’installation validée :**

`Étape 306 — Profil stable Player Homes`

**Module en cours :**

`07 - CITIES TOWNS INTERIORS LIGHTING`

**Sous-bloc validé :**

`07.1 - PLAYER HOMES`

**Profil stable actuel :**

`SKYFORGE - Stable étape 305 player homes OK`

**Compteur confirmé :**

- ESP + ESM non-light : `76`

---

## État du module 07 - Cities / towns / interiors / lighting

**Étapes documentées dans le module :**

- `Étape 266 — Ouverture module 07`
- `Étape 267 — Pack fondations Lux`
- `Étape 268 — The Great Cities Resources`
- `Étape 269 — The Great Town of Shor’s Stone`
- `Étape 270 — The Great Village of Kynesgrove`
- `Étape 271 — The Great Village of Old Hroldan`
- `Étape 272 — The Great Town of Karthwasten`
- `Étape 273 — Profil stable intermédiaire`
- `Étape 274 — The Great Village of Mixwater Mill`
- `Étape 275 — The Great Town of Ivarstead`
- `Étape 276 — Profil stable intermédiaire`
- `Étape 277 — Dragon Bridge différé`
- `Étape 278 — The Great City of Rorikstead`
- `Étape 279 — The Great City of Falkreath`
- `Étape 280 — Dawnstar COTN installé puis corrigé plus tard`
- `Étape 281 — Morthal COTN installé puis décoché plus tard`
- `Étape 282 — Winterhold COTN installé puis remplacé`
- `Étape 283 — Correction Winterhold vers Great City`
- `Étape 284 — Correction Dawnstar vers Great City`
- `Étape 285 — Morthal COTN décoché`
- `Étape 286 — Lainalten`
- `Étape 287 — Half-Moon Mill COTN Addon`
- `Étape 288 — Anga’s Mill COTN Addon`
- `Étape 289 — Environs Hroggar’s House`
- `Étape 290 — Sunthgat`
- `Étape 291 — Oakwood`
- `Étape 292 — Pack Schlitzohr villages 1`
- `Étape 293 — Pack Schlitzohr villages 2`
- `Étape 294 — Pack Schlitzohr villages 3`
- `Étape 295 — Laintar Dale`
- `Étape 296 — The Great Settlement of Darkwater Crossing`
- `Étape 297 — Contrôle de continuité villages`
- `Étape 298 — Profil stable villages Darkwater`
- `Étape 299 — JK’s Riverfall Cottage Family Edition`
- `Étape 300 — Sicarius’ Refuge SSE`
- `Étape 301 — Ruska`
- `Étape 302 — Wind Path SSE`
- `Étape 303 — Hearthfire Multiple Adoptions`
- `Étape 304 — Contrôle Player Homes`
- `Étape 305 — Lakeview Manor - As It Should Be`
- `Étape 306 — Profil stable Player Homes`
- `Étape 307 — Pause GitHub avant suite module 07`

**État validé :**

- Socle Lux installé : `Lux Via`, `Lux Orbis`, `Lux`.
- The Great Cities Resources installé.
- Plusieurs villages / villes Great Cities installés et testés.
- Corrections Winterhold / Dawnstar alignées vers les choix Great City / Nolvus Awakening.
- `Cities of the North - Morthal` décoché, choix final Morthal à revoir.
- `Environs - Hroggar's House` installé, patch collection sans option activée pour l’instant.
- Sunthgat, Oakwood, packs Schlitzohr villages, Laintar Dale et Darkwater Crossing installés selon logique Nolvus.
- Sous-bloc `07.1 - PLAYER HOMES` validé avec profil stable dédié.

---

## Mods / décisions importants du module 07

- `Lux Orbis - Patch Hub - A REINSTALL PLUS TARD` installé mais à compléter / réinstaller plus tard.
- Les patch collections `The Great Town / Village / City` sont marquées `A COMPLETER PLUS TARD` et devront être reprises pendant la phase de patching.
- `Dragon Bridge` est différé, à traiter plus tard avec routes / ponts / Lux / villes.
- `The Great City Of Falkreath SSE Edition` est retenu en choix Nolvus ; éviter le mélange COTN / JK / patches complexes pour Falkreath.
- `Cities of the North - Dawnstar` et son update sont décochés / remplacés par `The Great City Of Dawnstar`.
- `Cities of the North - Winterhold` est décoché / remplacé par `The Great City Of Winterhold`.
- `Cities of the North - Morthal` est décoché, choix à revoir.
- `The Great Cities - CC Fishing Patch` est identifié mais différé.
- Patches des nouveaux villages / settlements différés.
- Version ESL de `Dunmer Settlements of Solstheim` retenue pour limiter l’impact sur le compteur non-light.
- Patches Solstheim / Raven Rock / Tel Mithryn différés.
- `Settings Loader Hearthfire Multiple Adoptions` annulé / introuvable.
- Patch Verdant Sicarius zappé tant que `Verdant` n’est pas présent dans SKYFORGE.
- `Lakeview Manor - As It Should Be` est un ajout externe Fabien, installé et validé.
- Traduction FR du patch CC Fishing de Lakeview Manor non installée, jugée inutile.
- LOD / DynDOLOD : à faire plus tard, pas maintenant.

---

## Décisions importantes retenues

- LOOT / ordre de chargement global : toujours différé.
- Ne pas toucher au panneau droit sauf missing master.
- Les tests ingame restent courts et ciblés tant que la base globale n’est pas suffisamment avancée.
- Les sauvegardes techniques temporaires créées pour tester `Skyrim Unbound` devront être supprimées avant la vraie partie finale.
- `Atlantean Landscape` reste décoché jusqu’au futur bloc `Parallax / Complex Terrain / ENB / textures paysage avancées`.
- Les patch hubs / patch collections sont conservés pour la future phase de patching, pas finalisés maintenant.
- Textures 2K par défaut si disponibles ; 1K pour petits objets / optimisation ; 4K uniquement pour éléments très visibles si justifié ; 8K exclu par défaut.

---

## Prochaine reprise

Reprendre à partir de :

`Étape 308`

Sujet prévu :

Suite du module `07 - CITIES TOWNS INTERIORS LIGHTING`.

État de départ :

- Dernière étape validée : Étape 307
- Dernière étape d’installation validée : Étape 306
- Module en cours : `07 - CITIES TOWNS INTERIORS LIGHTING`
- Sous-bloc Player Homes validé : OK
- Profil stable actuel : `SKYFORGE - Stable étape 305 player homes OK`
- ESP + ESM non-light : `76`
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- LOD / DynDOLOD non générés : OK

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
11. Frameworks spécifiques.
12. Défaite, slavery, prostitution et systèmes Nefaram.
13. Armures, vêtements, outfits et NSFW.
14. Patches de compatibilité.
15. Conflict resolution final.
16. Génération BodySlide.
17. Nemesis / Pandora / FNIS selon décision finale.
18. LOD, TexGen et DynDOLOD.
19. Tests de stabilité prolongés.
20. Préparation éventuelle Wabbajack.
