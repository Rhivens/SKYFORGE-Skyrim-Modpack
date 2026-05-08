# Landscape, grass, trees & water — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Suite du module **06 - LANDSCAPE GRASS TREES WATER**, à partir de l’étape 221.

---

### 221. Contrôle ordre + suite arbres / herbe / eau

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Objectif :**  
Contrôler l’état du module avant de poursuivre la végétation, l’herbe et l’eau.

**Résultat validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL bloquant : OK
- `Overwrite` vide : OK
- Tous les plugins attendus sont cochés
- `Atlantean Landscape.esp` reste non actif

**Statut :**  
Étape 221 validée.

---

### 222. Ancient Trees différé

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Décision :**  
`Ancient Trees Of Skyrim - DIFFÉRÉ BETHESDA`

**Raison :**

- Accès Bethesda temporairement impossible.
- Ticket Bethesda ouvert.
- Aucun miroir douteux utilisé.

**Statut :**  
Étape 222 validée comme décision de différer.

---

### 223. Dilon Vul

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mod installé :**

- `Enhanced Landscapes - Oaks Standalone SSE - Marsh Pines - Dilon Vul`

**Plugin attendu :**

- `Dilon Vul SSE.esp`

**Test validé :**

- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL bloquant : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 223 validée.

---

### 224. Pack flore léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Renthal Nettle SSE`
- `Mari's flora`

**Choix / option :**

- `Mari's flora` : `For ENB`

**Test validé :**  
OK.

**Statut :**  
Étape 224 validée.

---

### 225. Pack herbe Cathedral + Origins

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `DrJacopo's - 3D Pine Grass (Old) / Cathedral - 3D Pine Grass 0.457`
- `Origins Of Forest - 3D Forest Grass 1.4.8`

**Choix validés :**

- Cathedral : fichier principal `Cathedral - 3D Pine Grass`, pas `Full 3D Coverage`
- Origins : version standard, pas variantes `less saturated` / `darker`

**Test validé :**  
OK.

**Statut :**  
Étape 225 validée.

---

### 226. Folkvangr

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mod installé :**

- `Folkvangr - Grass and Landscape Overhaul`

**Test validé :**  
OK.

**Statut :**  
Étape 226 validée.

---

### 227. QW’s Grass Patch 2

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mod installé :**

- `QW's Grass Patch 2 - Origins of Forest - Cathedral - Folkvangr`

**Test validé :**  
OK.

**Statut :**  
Étape 227 validée.

---

### 228. Test visuel herbe

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Test ingame validé :**

- Lancement du jeu : OK
- Création personnage : OK
- Spawn forêt : OK
- Test visuel routes / rochers / arbres / buissons : OK
- Aucun problème particulier observé

**Statut :**  
Étape 228 validée.

---

### 229. Point stable herbe

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Profil créé :**

`SKYFORGE - Stable étape 228 herbe OK`

**État :**

- `Overwrite` vide : OK

**Statut :**  
Étape 229 validée.

---

### 230. Pack ENB Complex Grass

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Cathedral - 3D Pine Grass for ENB Complex Grass`
- `Origins of forest for ENB Complex Grass`
- `Folkvangr for ENB Complex Grass`
- `QW Grass 2 for ENB Complex Grass`

**Test validé :**  
OK.

**Statut :**  
Étape 230 validée.

---

### 231. Contrôle plugins herbe

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugins visibles :**

```text
Grass Patch - All CC Mods.esp                         ESPFE / light
Landscape Fixes For Grass Mods.esp                    ESP normal
Complementary Grass Fixes.esp                         ESPFE / light
Cathedral - 3D Pine Grass.esp                         ESP normal
Origins Of Forest - 3D Forest Grass.esp               ESP normal
Folkvangr - Grass and Landscape Overhaul.esp          ESP normal
QW's Grass Patch 2.esp                                ESPFE / light
```

**Plugins non-light à surveiller dans ce bloc :**

- `Landscape Fixes For Grass Mods.esp`
- `Cathedral - 3D Pine Grass.esp`
- `Origins Of Forest - 3D Forest Grass.esp`
- `Folkvangr - Grass and Landscape Overhaul.esp`

**Statut :**  
Étape 231 validée.

---

### 232. Pack eau léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `GKB Waves Reborn`
- `Splashes of Storms`

**Test validé :**  
OK.

**Statut :**  
Étape 232 validée.

---

### 233. Contrôle plugins eau / pluie

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `GKBWavesReborn.esp` : présent / actif
- `Splashes of Storms` : aucun plugin

**Statut :**  
Étape 233 validée.

---

### 234. Point de stabilité court

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Profil actif confirmé :**

`SKYFORGE - Stable étape 228 herbe OK`

**État :**  
Stable avant installation de `Water for ENB`.

**Statut :**  
Étape 234 validée.

---

### 235. Water for ENB

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mod installé :**

- `Water for ENB - No Parallax - A REINSTALL PLUS TARD`

**Choix FOMOD :**

- `Shades of Skyrim for ENB`
- `No Parallax`
- Options avancées : aucune
- `Atlas Map Markers` : coché
- `Folkvangr` : coché
- `Generic Landscape Patch` : coché
- `Landscape Fixes For Grass Mods` : coché
- `Flat World Map` : `None`
- `iNeed` : `No Legacy iNeed Support`

**Test validé :**  
OK.

**Statut :**  
Étape 235 validée.

---

### 236. Contrôle plugins Water for ENB

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugins actifs Water for ENB :**

- `Water for ENB.esm`
- `Water for ENB (Shades of Skyrim).esp`
- `Water for ENB - Patch - Atlas Map Markers.esp`
- `Water for ENB - Patch - Folkvangr.esp`
- `Water for ENB - Patch - Generic Landscape Patch.esp`
- `Water for ENB - Patch - Landscape Fixes for Grass Mods.esp`

**Plugins Landscape and Water Fixes actifs :**

- `Landscape and Water Fixes.esp`
- `Landscape and Water Fixes - CC Fishing patch.esp`
- `Landscape and Water Fixes - Patch - Alternative Armors - Elven Hunter.esp`
- `Landscape and Water Fixes - Patch - Farming.esp`
- `Landscape and Water Fixes - Patch - Hendraheim.esp`
- `Landscape and Water Fixes - Patch - LFfGM - GotT.esp`
- `Landscape and Water Fixes - Patch - Myrwatch.esp`
- `Landscape and Water Fixes - Patch - Navigator ESL.esp`
- `Landscape and Water Fixes - Patch - Tundra Homestead.esp`
- `Landscape and Water Fixes - Patch - USMP.esp`
- `Landscape and Water Fixes - Patch - Vigil Enforcer Armor Set.esp`

**Point à surveiller :**

- `Landscape and Water Fixes - Patch - LFfGM - GotT.esp`

**Décision :**  
Aucun master manquant, donc le plugin est gardé actif.

**Statut :**  
Étape 236 validée.

---

### 237. Test visuel eau en jeu

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Test ingame validé :**

- Jeu lancé correctement : OK
- Création personnage : OK
- Test visuel cascade / eau : OK

**Statut :**  
Étape 237 validée.

---

### 238. Point stable paysage / eau

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Profil dupliqué et renommé :**

`SKYFORGE - Stable étape 237 herbe eau OK`

**État :**

- `Overwrite` vide : OK

**Statut :**  
Étape 238 validée.

---

### 239. Pack effets naturels léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Rudy HQ - Falling Leaves and Needles SE`
- `Snowy Surfaces Sound Collision and Aesthetics - A REINSTALL PLUS TARD`

**Choix Snowy Surfaces :**

- `Vanilla`
- `Vanilla Standard Meshes`
- Aucun patch

**Test validé :**  
OK.

**Statut :**  
Étape 239 validée.

---

### 240. Contrôle plugins effets naturels

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `snowy` : aucun plugin
- `falling` : aucun plugin

**Statut :**  
Étape 240 validée.

---

### 241. Pack petites corrections naturelles

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `WAVY Waterfalls Effect`
- `Storm Lightning for SSE and VR - ESL Flagged`

**Lien WAVY corrigé utilisé :**

https://www.nexusmods.com/skyrimspecialedition/mods/126073

**Choix Storm Lightning :**

- `ESL Flagged`

**Test validé :**  
OK.

**Statut :**  
Étape 241 validée.

---

### 242. Contrôle plugins effets naturels

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugins trouvés :**

- `WAVY Waterfalls Effect.esp`
- `StormLightning.esp`

**Note :**  
`StormLightning.esp` devrait être ESPFE / light grâce au choix `ESL Flagged`.

**Statut :**  
Étape 242 validée.

---

### 243. Pack ciel léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `ETHEREAL CLOUDS - Special Edition`
- `Picta Series - Improved Sky Meshes`

**Choix Ethereal Clouds :**

- `ETHEREAL CLOUDS SE - 2K`

**Test validé :**  
OK.

**Statut :**  
Étape 243 validée.

---

### 244. Contrôle plugins ciel

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `ETHEREAL CLOUDS - Special Edition` : aucun plugin
- `Picta Series - Improved Sky Meshes` : aucun plugin

**Statut :**  
Étape 244 validée.

---

### 245. Pack Canticle Tree / Dawnguard

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `High Poly Canticle Tree`
- `Canticle Tree Retexture - Draw Knife`
- `Canticle Tree Retexture - Bark`
- `Canticle Tree Retexture - Tree`

**Note :**  
Les 3 fichiers de retexture ont été installés séparément.

**Test validé :**  
OK.

**Statut :**  
Étape 245 validée.

---

### 246. Contrôle plugins Canticle

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `canticle` : aucun plugin
- `knife` : aucun plugin

**Statut :**  
Étape 246 validée.

---

### 247. Pack mondes DLC léger, version modifiée

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mod installé :**

- `Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books`

**Mod différé :**

- `Praedy's Soul Cairn - SE - DIFFERE SKELETON REPLACER`

**Raison :**

- `Praedy’s Soul Cairn - SE` signale `Skeleton Replacer HD - SE` dans les requirements.
- Décision prudente : ne pas introduire ce prérequis maintenant.
- À reprendre plus tard dans un mini-bloc dédié.

**Test validé :**  
OK.

**Statut :**  
Étape 247 validée.

---

### 248. Contrôle plugins Apocrypha

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `Detailing the Eldrich` : aucun plugin

**Statut :**  
Étape 248 validée.

---

### 249. Pack petits détails naturels / monde

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Diverse Windmill Sails - Base Object Swapper`
- `Giant Crab Shells - Mihail's Shards of Immersion`

**Test validé :**  
OK.

**Statut :**  
Étape 249 validée.

---

### 250. Contrôle plugins détails naturels

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugins ajoutés :**

- `Diverse Windmill Sails.esp`
- `mihailcrabshell.esp`

**À vérifier plus tard :**

- ESPFE / light ou ESP normal

**Statut :**  
Étape 250 validée.

---

### 251. Pack léger Sovngarde + Hanging Moss

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Sovngarde HD`
- `Remove Hanging Moss From Trees 1.6`

**Correction :**  
La version 1.5 n’était pas disponible. La version installée est donc la `1.6`.

**Test validé :**  
OK.

**Statut :**  
Étape 251 validée.

---

### 252. Contrôle plugins Sovngarde / Moss

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugin trouvé :**

- `Remove Hanging Moss From Trees.esp`

**Compteur relevé après cette étape :**

- ESP + ESM non-light : `40`

**Statut :**  
Étape 252 validée.

---

### 253. Pack plantes léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Edmond's Official Unique Flowers and Plants SSE`
- `Waterplants for Skyrim 1.8`

**Choix Unique Flowers :**

- `Unique Flowers and Plants for Skyrim SE DLC Compatible ESM Version`

**Choix Waterplants :**

- `Waterplants for Skyrim 1.8`

**Non installés :**

- `Waterplants - lily only`
- `Waterplants grass only`
- `Patch for Waterplants and Folkvangr V1.3`
- Autres patches

**Test validé :**  
OK.

**Statut :**  
Étape 253 validée.

---

### 254. Contrôle plugins plantes

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Plugins trouvés :**

- `Unique Flowers & Plants.esp`
- `waterplants.esp`

**Note :**  
Malgré le choix `ESM Version`, le plugin visible est `Unique Flowers & Plants.esp`.

**À vérifier plus tard :**

- Master-flagged ou ESP normal

**Statut :**  
Étape 254 validée.

---

### 255. Pack relief léger

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Mods installés :**

- `Better Dirt Cliffs and Alphas`
- `the Pebbles SE`

**Choix :**

- `Better Dirt Cliffs and Alphas 2K`

**Test validé :**  
OK.

**Statut :**  
Étape 255 validée.

---

### 256. Contrôle plugins relief

**Module :** 06 - LANDSCAPE GRASS TREES WATER

**Résultat :**

- `Better Dirt Cliffs and Alphas` : aucun plugin
- `the Pebbles SE` : aucun plugin

**Statut :**  
Étape 256 validée.

---

## État de pause après l’étape 256

**Dernière étape validée :**  
`Étape 256 — Contrôle plugins relief`

**Module en cours :**  
`06 - LANDSCAPE GRASS TREES WATER`

**Profil stable actuel :**

`SKYFORGE - Stable étape 237 herbe eau OK`

**Compteur connu :**

- ESP + ESM non-light : `40` à l’étape 252
- À redemander après les ajouts 253–256

**Mods différés / réservés dans ce bloc :**

- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD`
- `Ancient Trees Of Skyrim - DIFFÉRÉ BETHESDA`
- `Praedy's Soul Cairn - SE - DIFFERE SKELETON REPLACER`
- `Water for ENB - No Parallax - A REINSTALL PLUS TARD`
- `Snowy Surfaces Sound Collision and Aesthetics - A REINSTALL PLUS TARD`

**À vérifier lors de la prochaine reprise :**

- Mettre à jour le compteur ESP + ESM après les étapes 253–256.
- Vérifier si les plugins suivants sont ESPFE / light ou ESP normal :
  - `Diverse Windmill Sails.esp`
  - `mihailcrabshell.esp`
  - `Remove Hanging Moss From Trees.esp`
  - `Unique Flowers & Plants.esp`
  - `waterplants.esp`
  - `WAVY Waterfalls Effect.esp`
  - `StormLightning.esp`

**Reprise prévue :**  
`Étape 257`

**Consignes maintenues :**

- Ne pas lancer LOOT.
- Ne pas toucher au panneau droit sauf master manquant.
- Garder `Atlantean Landscape` décoché.
- Garder `Ancient Trees Of Skyrim` différé jusqu’à résolution Bethesda.
- Continuer les tests courts SKSE / menu / masters / DLL / Overwrite.
