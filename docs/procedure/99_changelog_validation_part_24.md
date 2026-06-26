# SKYFORGE — Changelog / validation — partie 24

Période couverte : étapes **640 à 655**.

Cette partie documente la fin documentaire du bloc `[06 - LANDSCAPE GRASS TREES WATER]`, puis l’ouverture, les audits groupés et la clôture provisoire du bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]`.

Important : les étapes 640 à 655 sont principalement des **vérifications / audits documentaires / clôtures provisoires** sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Résumé global

### Étapes 640 à 644 — Fin et clôture provisoire du bloc 06

- Vérification groupée météo / ciel : `Picta Series - Improved Sky Meshes`, `Obsidian Mountain Fogs`, `Morning Fogs SSE - Thin Fog`, `Rainbows Remade`, `Shooting Stars SE`.
- Vérification de `High Poly Canticle Tree` et des retouches Canticle Tree.
- Vérification de `Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books`.
- Vérification groupée des derniers visuels / flore / objets / paysages du bloc 06.
- Clôture provisoire du bloc `[06 - LANDSCAPE GRASS TREES WATER]` à l’étape 644.
- Compteur ESP + ESM non-light conservé à **138**.

### Étapes 645 à 655 — Bloc 07 Cities / Towns / Interiors / Lighting

- Ouverture du bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` à l’étape 645.
- Audit groupé du socle `Lux`, `Lux Via`, `Lux Orbis`.
- Audit groupé de `The Great Cities / Towns / Villages`.
- Audit groupé des addons COTN, `Environs` et villages ajoutés.
- Audit des sous-blocs `[07.1]` à `[07.6]` : Player Homes, Farmhouses, Other Locations, Lands, Ruins, Interiors.
- Clôture provisoire du bloc 07 à l’étape 655.
- Le bloc 07 est jugé stable pour continuer, mais non finalisé : les dettes Lux / Lux Orbis / Lux Via, patch hubs, navmesh, intérieurs et LOD restent à reprendre plus tard.
- Compteur ESP + ESM non-light conservé à **138**.

---

## Étapes validées

### Étape 640 — Météo / ciel vérifiés

- Mods concernés : `Picta Series - Improved Sky Meshes`, `Obsidian Mountain Fogs`, `Morning Fogs SSE - Thin Fog`, `Vanilla And Morning Fogs SSE - Easy Seam Fixer`, `Rainbows Remade - 4K Version`, hotfix / no notification patch, `Shooting Stars SE`.
- Plugins relevés : `Obsidian Mountain Fogs.esm`, `Morning Fogs SSE.esp`, `Rainbows over Waterfalls.esp`, `Rainbows over Waterfalls - Natural Waterfalls patch.esp`, `Rainbows Remade.esp`, `ShootingStars.esp`.
- Étape de vérification uniquement.
- Test SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide.
- Compteur stable : **138**.
- Vigilance conservée sur la coexistence `Rainbows over Waterfalls` / `Rainbows Remade`.

### Étape 641 — High Poly Canticle Tree + retouches Canticle Tree

- Mods concernés : `High Poly Canticle Tree`, `Canticle Tree Retexture - Bark`, `Canticle Tree Retexture - Tree`, `Canticle Tree Retexture - Draw Knife`.
- Aucun plugin relevé pour ce pack.
- Étape de vérification uniquement, sans nouvelle installation.
- Compteur stable : **138**.

### Étape 642 — Detailing the Eldrich / Apocrypha

- Mod concerné : `Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books`.
- Aucun plugin relevé.
- Mod considéré comme visuel / textures / meshes Apocrypha.
- Compteur stable : **138**.

### Étape 643 — Vérification groupée fin du bloc 06

- Validation groupée des derniers mods déjà présents du bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Groupes concernés : Canticle Tree / Apocrypha, objets, paysages, flore, BOS, Mihail / Xtudo.
- Plugins relevés : `Diverse Windmill Sails.esp`, `mihailcrabshell.esp`, `Remove Hanging Moss From Trees.esp`, `Unique Flowers & Plants.esp`, `waterplants.esp`, `ManEaterGiants.esp`, `mihailbloodymammothbones.esp`.
- Validation par continuité du dernier test global propre.
- Aucun test SKSE mod par mod demandé.
- Compteur stable : **138**.

### Étape 644 — Clôture provisoire du bloc 06

- Bloc `[06 - LANDSCAPE GRASS TREES WATER]` clôturé provisoirement.
- Le bloc est considéré stable pour continuer vers le bloc suivant.
- Les dettes FOMOD, LOD / DynDOLOD, Seasons, parallax, complex grass, snow stack et traductions FR restent différées.
- Aucune génération LOD / DynDOLOD ne doit être faite tant que les blocs villes, lieux, architecture et worldspaces ne sont pas stabilisés.
- Compteur final bloc 06 : **138**.

### Étape 645 — Ouverture du bloc 07

- Bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` ouvert.
- Bloc présent dans le panneau gauche et plugins associés présents dans le panneau droit.
- Aucun changement actif.
- Référence conservée : SKSE/menu OK, Overwrite vide, compteur **138**.

### Étape 646 — Audit opérationnel Lux / Lux Via / Lux Orbis

- Socle Lux présent et cohérent pour continuer.
- Plugins principaux actifs : `Lux - Resources.esp`, `Lux Via - plugin.esp`, `Lux Via.esp`, `Lux Orbis - Master plugin.esm`, `Lux Orbis.esp`, `Lux - Master plugin.esm`, `Lux.esp`.
- Base Lux / Lux Via / Lux Orbis conservée.
- Dette forte : patch hubs `Lux Orbis` et `Lux` à reprendre après stabilisation des villes, villages, lieux et intérieurs.
- Étape validée comme audit, non clôturée définitivement.

### Étape 647 — Audit groupé The Great Cities / Towns / Villages

- Base `The Great Cities / Towns / Villages` active et cohérente.
- Plugins principaux présents pour Shor's Stone, Kynesgrove, Old Hroldan, Karthwasten, Mixwater Mill, Ivarstead, Rorikstead, Falkreath, Winterhold et Dawnstar.
- Patches essentiels partiels déjà présents : USSEP, Landscape and Water Fixes, Atlas Map Markers, CC Fishing selon les lieux.
- Dette forte : patch collections, Rob's Bug Fixes, Lux Orbis, Atlas Map Markers et Landscape and Water Fixes à reprendre selon les lieux.

### Étape 648 — Audit COTN addons / Environs / villages ajoutés

- Sous-bloc cohérent et actif, mais patching incomplet volontaire.
- `Cities of the North - Morthal` reste décoché / choix à revoir.
- `Half-Moon Mill`, `Anga's Mill`, `Environs - Hroggar's House`, villages Schlitzohr / assimilés et `Darkwater Crossing` conservés en validation provisoire.
- Dettes : patch collections, Lux Orbis, grass / landscape / navmesh.

### Étape 649 — Audit groupé `[07.1 - PLAYER HOMES]`

- Sous-bloc actif et cohérent.
- Maisons concernées : Hearthfire Multiple Adoptions, JK's Riverfall Cottage, Sicarius' Refuge, Ruska, Wind Path, Lakeview Manor.
- Dettes : patches maisons, Lux Orbis Riverfall / Sicarius / Wind Path, compatibilité adoption / enfants / maisons custom.

### Étape 650 — Audit groupé `[07.2 - FARMHOUSES]`

- Sous-bloc cohérent, majoritairement visuel / architecture extérieure.
- Plugins relevés : `Unique NVFH - Falkreath - Walkways.esp`, `Unique NVFH - Non Snowy Regions.esp`, `UNVFH - Falkreath - clipping patch.esp`, `Scarecrows_of_Skyrim.esp`.
- Patch `Scarecrows of Skyrim - BOS - SOS Patch` laissé décoché car dépendant de `Simplicity of Snow`.
- Dettes : LOD / DynDOLOD, parallax, cohérence snow stack.

### Étape 651 — Audit groupé `[07.3 - OTHER LOCATIONS]`

- Sous-bloc court, cohérent, mais patches à reprendre plus tard.
- Plugins actifs : `This Is Jorrvaskr.esp`, `JK's Fort Dawnguard.esp`, `JK's Castle Volkihar.esp`.
- Dettes : patches JK, Lux intérieur, navmesh, quêtes / schedules Dawnguard et Companions.

### Étape 652 — Audit groupé `[07.4 - LANDS]`

- Sous-bloc très chargé, validation provisoire uniquement.
- Groupes concernés : fontaines, frontières, routes, Sepolcri, Ryn's locations, Orc Strongholds.
- Risques principaux : navmesh, Lux Orbis incomplet, grass clipping, LOD / DynDOLOD, patch collections différées.
- Le sous-bloc est conservé, sans ajout actif.

### Étape 653 — Audit groupé `[07.5 - RUINS]`

- Sous-bloc propre et faible risque, principalement textures / parallax / replacers visuels.
- Mods concernés : `RUSTIC RELIEFS`, `RUSTIC RELIEFS - Parallax`, `CleverCharff's Nordic Ruins`, `Gorgeous Ruin Door SE 2K`, `Tower Ruins 2k Texture Replacer`.
- Aucun plugin clairement associé relevé.
- Dette : cohérence parallax / ENB à surveiller.

### Étape 654 — Audit groupé `[07.6 - INTERIORS]`

- Sous-bloc très riche et sensible, validation provisoire uniquement.
- Groupes concernés : Underground, Skyrim Sewers, Distinct Interiors, JK / RedBag Dragonsreach, EEK Whiterun, Ryn interiors, JK's interiors, Blue Palace, guildes, temples, College.
- Dettes fortes : Lux intérieur / patch hub, Distinct Interiors patch collection, JK / EEK / Ryn / RedBag patches, Skyrim Sewers patches, navmesh, quêtes / schedules NPC, parallax interiors.
- Alerte CTD : `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD - PROVOQUE DES CTD`.
- Alerte future SexLab : `JK's Temple of Dibella - PATCHES A VOIR PLUS TARD - VERIFIER SEXLAB DIBELLA SISTERHOOD`.

### Étape 655 — Clôture provisoire du bloc 07

- Bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` clôturé provisoirement.
- Le bloc est stable pour continuer, mais non clôturé définitivement.
- Dettes majeures conservées : Lux / Lux Orbis / Lux Via, patch hubs, navmesh, intérieurs JK / Distinct / EEK / Ryn, futur LOD / DynDOLOD.
- Aucun nouveau fichier actif installé.
- Aucun test SKSE supplémentaire requis.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.
- Compteur non-light conservé : **138**.
- Overwrite conservé vide.

---

## État final post-655

- Dernière étape validée/documentée : **Étape 655 — Clôture provisoire du bloc 07**.
- Prochaine étape attendue : **Étape 656**.
- Bloc 06 : **clôturé provisoirement**.
- Bloc 07 : **clôturé provisoirement**.
- Compteur ESP + ESM non-light : **138**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé pendant les étapes 640 à 655**.
- Snapshot MO2 courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md`.
