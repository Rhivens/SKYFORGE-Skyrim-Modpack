# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 655 — Clôture provisoire du bloc 07**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — snapshot complet post-639, toujours référence courante car aucune nouvelle installation active n’a modifié MO2 pendant les étapes 640 à 655
- Le snapshot 639 reste la référence anti-doublon courante.
- Prochaine étape attendue : **Étape 656**
- Compteur ESP + ESM non-light post-655 : **138**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 640 à 655**

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK sur les tests documentés
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur les tests documentés
- **Compteur ESP + ESM non-light final post-655 :** 138
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; non relancé pendant les étapes 640 à 655
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_24.md`
4. `docs/procedure/10_landscape_grass_trees_water_part_6.md`
5. `docs/procedure/11_cities_towns_interiors_lighting_part_1.md`
6. `docs/procedure/06_decisions_differees_part_10.md`
7. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — snapshot courant post-639, toujours référence car aucune nouvelle installation active n’a modifié MO2 pendant 640 à 655
8. `docs/procedure/99_changelog_validation_part_23.md`
9. `docs/procedure/10_landscape_grass_trees_water_part_5.md`
10. `docs/procedure/06_decisions_differees_part_9.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_618.md` — jalon historique post-618

## Étapes récentes validées / documentées

### Étapes 607 à 618 — Reprise Landscape / Grass / Trees / Water

- Clarification administrative de plusieurs FOMOD / notes MO2 dans `[06 - LANDSCAPE GRASS TREES WATER]`.
- Ajouts atmosphériques : `Obsidian Mountain Fogs`, `Morning Fogs SSE`, `Vanilla And Morning Fogs SSE - Easy Seam Fixer`.
- Ajout du fix ENB `Splashes of Storms - ENB Fix`.
- Compteur ESP + ESM non-light : **131 → 132** à l’étape 615, puis **132 → 133** à l’étape 616.
- Étape 618 validée avec SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide, compteur **133**.

### Étapes 619 à 639 — Eau, cascades, Footprints, ash et vérifications météo

- Nettoyage administratif de noms MO2 dans le bloc `[06 - LANDSCAPE GRASS TREES WATER]`.
- Ajout de la pile eau / cascades : `Water in Wash Basins`, `Water in Wells`, `Water Effects Brightness and Reflection Fix`, `Loki's Wade In Water`, `Wade In Water Redone`, `Splashes Of Skyrim`, `Natural Waterfalls`, `FYX - Water Mesh Optimization C 128`, `Rainbows over Waterfalls`, `TMD The Rift Leaves`, `Animated Ice Floes`.
- Ajout de `Better Dynamic Ash SE`.
- Ajout de la pile Footprints active : `Footprints`, `Footprints - ENB`, `SPID for Footprints`, `SPID for Footprints fix`, `SPID for Footprints - Player Footprints Fix`.
- `Ultimate fix - SPID for Footprints` conservé décoché en réserve avec FOMOD / MCM `Reset counts` à reprendre plus tard.
- Vérifications finales : `Snowy Surfaces`, `Storm Lightning`, `ETHEREAL CLOUDS`.
- Compteur ESP + ESM non-light : **133 → 134** à l’étape 621, **134 → 135** à l’étape 623, **135 → 137** à l’étape 629, **137 → 138** à l’étape 630.
- Étape 639 validée ; Overwrite vide ; LOOT non lancé ; DynDOLOD / LOD non générés ; BodySlide non généré ; Pandora non relancé.
- Snapshot MO2 panneau gauche post-639 disponible dans `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md`.

### Étapes 640 à 644 — Fin documentaire du bloc 06

- Vérification groupée météo / ciel : Picta, Obsidian Mountain Fogs, Morning Fogs, Rainbows Remade, Shooting Stars.
- Vérification de Canticle Tree et Detailing the Eldrich / Apocrypha.
- Vérification groupée des derniers visuels / flore / objets / paysages du bloc 06.
- Bloc `[06 - LANDSCAPE GRASS TREES WATER]` clôturé provisoirement à l’étape 644.
- Aucun nouveau fichier actif installé pendant ces étapes.
- Compteur ESP + ESM non-light conservé à **138**.

### Étapes 645 à 655 — Bloc 07 Cities / Towns / Interiors / Lighting

- Ouverture du bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` à l’étape 645.
- Audit groupé Lux / Lux Via / Lux Orbis.
- Audit groupé The Great Cities / Towns / Villages.
- Audit groupé COTN addons / Environs / villages ajoutés.
- Audit des sous-blocs `[07.1]` Player Homes, `[07.2]` Farmhouses, `[07.3]` Other Locations, `[07.4]` Lands, `[07.5]` Ruins et `[07.6]` Interiors.
- Bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` clôturé provisoirement à l’étape 655.
- Aucun nouveau fichier actif installé pendant ces audits.
- Dettes majeures conservées : Lux / Lux Orbis / Lux Via, patch hubs, navmesh, intérieurs JK / Distinct / EEK / Ryn, Skyrim Sewers, futur LOD / DynDOLOD.
- Alertes conservées : Dunmeri Furniture in Gray Quarter CTD connu ; Temple de Dibella à revoir avec future pile SexLab / Dibella Sisterhood.
- Compteur ESP + ESM non-light conservé à **138**.

## Surveillance compteur ESP + ESM non-light

- `< 160` non-light : zone confortable.
- `160–190` : vigilance normale.
- `190–220` : vigilance renforcée.
- `220–235` : audit obligatoire avant gros ajout.
- `235+` : mode survie ; ESLification, suppressions ou merges propres à envisager.

État post-655 : **138 non-light**, donc zone confortable.
