# Cities, towns, interiors & lighting — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture et audit documentaire du module **07 - CITIES TOWNS INTERIORS LIGHTING**.

Périmètre : étapes **645 à 655**.

Important : ces étapes sont des audits documentaires sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 645 — Ouverture du bloc 07

### Statut

- Bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` ouvert.
- Bloc présent dans le panneau gauche.
- Plugins associés présents dans le panneau droit.
- Aucun changement actif.
- Référence de test conservée : SKSE/menu OK, Overwrite vide, compteur `138`.

---

## Étape 646 — Audit opérationnel Lux / Lux Via / Lux Orbis

### Verdict

Socle Lux présent et cohérent pour continuer, mais pas clôturable définitivement tant que les patch hubs ne sont pas repris.

### Base présente côté MO2

- `Lux Via`
- `Lux Via main plugin update`
- `Updated Lux - Resources plugin`
- `Lux Via meshes update`
- `Lux Orbis - A COMPLETER PLUS TARD`
- `Lux Orbis (patch hub) - A REINSTALLER PLUS TARD`
- `Lux - PATCH HUB A FAIRE PLUS TARD`

### Plugins principaux actifs

- `Lux - Resources.esp`
- `Lux Via - plugin.esp`
- `Lux Via.esp`
- `Lux Orbis - Master plugin.esm`
- `Lux Orbis.esp`
- `Lux - Master plugin.esm`
- `Lux.esp`

### Patches déjà actifs

Base propre de patches Lux Orbis pour le socle CC / USSEP / USMP, notamment :

- `Lux Orbis - USMP Patch.esp`
- `Lux Orbis - USSEP patch.esp`
- `Lux Orbis - Arms of Chaos CC.esp`
- `Lux Orbis - Bow of Shadow CC.esp`
- `Lux Orbis - CC Fish patch.esp`
- `Lux Orbis - Farming CC patch.esp`
- `Lux Orbis - Goblins CC.esp`
- `Lux Orbis - Lord's Mail CC.esp`
- `Lux Orbis - Saints and Seducers patch.esp`
- `Lux Orbis - Saturalia CC.esp`
- `Lux Orbis - Spell Knight Armor CC.esp`
- `Lux Orbis - Tundra Homestead patch.esp`

Lux intérieur a au moins :

- `Lux - SLaWF patch.esp`
- `Lux - USSEP patch.esp`
- `Lux.esp`

### Décision

- Base Lux conservée.
- Plugins principaux actifs.
- Pas de changement à faire maintenant.
- Pas de test SKSE requis, car aucun ajout actif.
- Dette patch hubs maintenue.

### Dettes

- Reprendre `Lux Orbis - A COMPLETER PLUS TARD`.
- Réinstaller ou compléter `Lux Orbis (patch hub)`.
- Reprendre `Lux - PATCH HUB A FAIRE PLUS TARD`.
- Vérifier plus tard les patches Lux Via pour routes, Road Signs, Ryn’s locations, Orc Strongholds et villages ajoutés.
- Vérifier plus tard les patches Lux Orbis pour The Great Cities / Towns / Villages, COTN addons, Environs et villages ajoutés.
- Vérifier plus tard les patches Lux intérieur pour JK’s Interiors, Distinct Interiors, Skyrim Sewers, RedBag / EEK / Ryn interiors.

---

## Étape 647 — Audit groupé The Great Cities / Towns / Villages

### Verdict

Base cohérente et active, mais patching incomplet volontaire. Le sous-bloc peut rester actif, mais sera repris plus tard avec Lux / Lux Orbis / Landscape / Atlas / USSEP.

### Plugins principaux présents

- `Resources - The Great Cities.esp`
- `The Great Town of Shor's Stone.esp`
- `The Great Village of Kynesgrove.esp`
- `The Great Village of Old Hroldan.esp`
- `The Great Town of Karthwasten.esp`
- `The Great Village of Mixwater Mill.esp`
- `The Great Town of Ivarstead.esp`
- `The Great City of Rorikstead.esp`
- `The Great City of Falkreath.esp`
- `The Great City of Winterhold v4.esp`
- `The Great City of Dawnstar.esp`

### Patches déjà actifs

Patches USSEP, Landscape and Water Fixes, Atlas Map Markers, Redguard Elite Armaments ou CC Fishing présents sur plusieurs lieux, notamment Shor’s Stone, Kynesgrove, Old Hroldan, Karthwasten, Mixwater Mill et Ivarstead.

### Décision

- Garder / continuer.
- Plugins principaux présents.
- Patches essentiels partiellement présents.
- Dernier test SKSE/menu global OK.
- Aucun master manquant.
- Aucun message DLL.
- Overwrite vide.
- Compteur non-light : `138`.

### Dettes

- Reprendre les patch collections The Great Cities / Towns / Villages.
- Reprendre Rob’s Bug Fixes marqués à réinstaller.
- Reprendre Lux Orbis patches pour les lieux The Great.
- Vérifier Atlas Map Markers manquants.
- Vérifier Landscape and Water Fixes manquants.
- Reporter toute décision finale à la passe globale Lux / villes / navmesh.

---

## Étape 648 — Audit COTN addons / Environs / villages ajoutés

### Verdict

Sous-bloc cohérent et actif, mais patching incomplet volontaire.

### Groupes conservés

- `Half-Moon Mill - Cities of the North Addon`.
- `Anga's Mill - Cities of the North Addon`.
- `Environs - Hroggar's House`.
- Villages ajoutés : Lainalten, Sunthgat, Oakwood, Reich Corigate, Granite Hill, Amber Guard, Dunpar Wall, Vernim Wood, Stonehills, Dunmer Settlements Solstheim, Amol Village, Laintar Dale, Darkwater Crossing.

### Décision spécifique

- `Cities of the North - Morthal` reste décoché / choix à revoir.
- Ne pas le traiter comme actif.
- Ne pas installer ses patches maintenant.

### Plugins principaux actifs

- `Lainalten.esp`
- `Half-Moon Mill - COTNed.esp`
- `COTN Addon - Anga's Mill.esp`
- `Environs Master Plugin.esp`
- `Environs - Hroggars House.esp`
- `Sunthgat.esp`
- `AnotherOakwood.esp`
- `Reich Corigate.esp`
- `Granite Hill.esp`
- `Amber Guard.esp`
- `Dunpar Wall.esp`
- `Vernim Wood.esp`
- `Stonehills.esp`
- `Dunmer Settlements Solstheim.esp`
- `Amol Village.esp`
- `Laintar Dale.esp`
- `Darkwater Crossing - TGC Addon.esp`

### Patches déjà actifs utiles

- `Half-Moon Mill COTNed - Lux Orbis patch.esp`
- `COTN Angas Mill Addon - LFFGM patch.esp`
- `COTN Angas Mill Addon - Lux Orbis patch.esp`
- `Vernim Wood USSEP Patch.esp`
- `TGV Darkwater Crossing - Landscape and Grass Patch.esp`

### Dettes

- Patch collections Half-Moon Mill / Anga’s Mill / Environs / villages ajoutés.
- Lux Orbis manquant sur plusieurs villages.
- Grass / landscape / navmesh à reprendre.
- Ne pas activer COTN Morthal tant que le choix n’est pas tranché.

---

## Étape 649 — Audit groupé `[07.1 - PLAYER HOMES]`

### Verdict

Sous-bloc actif et cohérent, conservé en validation provisoire.

### Plugins actifs

- `JK's Riverfall Cottage.esp`
- `Eli_Sicarius' Refuge.esp`
- `Eli_Ruska.esp`
- `WindPath.esp`
- `HearthfireMultiKid.esp`
- `HearthfireMultiKid_LastName.esp`
- `LKVM Cellar and Exterior.esp`
- `LKVM Main House.esp`
- `LKVM_LT02.esp`
- `LKVM_NOGrass.esp`
- `LKVMII_LT01.esp`
- `LKVM CC Fishing Patch.esp`

### Décision

- Garder / continuer.
- Sous-bloc stable pour l’instant.
- Pas d’installation maintenant.
- Pas de test SKSE requis, car aucun changement actif.

### Dettes

- Patches maisons à revoir.
- Lux Orbis pour Riverfall / Sicarius / Wind Path.
- Compatibilité adoption / enfants / maisons custom à surveiller.

---

## Étape 650 — Audit groupé `[07.2 - FARMHOUSES]`

### Verdict

Sous-bloc cohérent, majoritairement visuel / architecture extérieure.

### Plugins actifs

- `Unique NVFH - Falkreath - Walkways.esp`
- `Unique NVFH - Non Snowy Regions.esp`
- `UNVFH - Falkreath - clipping patch.esp`
- `Scarecrows_of_Skyrim.esp`

### Décision

- Garder / continuer.
- Sous-bloc stable pour avancer.
- Patch `Scarecrows of Skyrim - BOS - SOS Patch` laissé décoché car il requiert `Simplicity of Snow`.
- Pas d’installation maintenant.
- Pas de LOOT.
- Pas de DynDOLOD / LOD.
- Pas de test SKSE requis, car aucun changement actif.

### Dettes

- LOD / DynDOLOD.
- Parallax.
- Cohérence snow stack.
- `Northern Vanilla Farmhouses - Lods` et `R's Windmill - DynDOLOD patch` à revoir pendant la passe LOD globale, pas maintenant.

---

## Étape 651 — Audit groupé `[07.3 - OTHER LOCATIONS]`

### Verdict

Sous-bloc court, cohérent, mais patches à reprendre plus tard.

### Plugins actifs

- `This Is Jorrvaskr.esp`
- `JK's Fort Dawnguard.esp`
- `JK's Castle Volkihar.esp`

### Décision

- Garder / continuer.
- Sous-bloc stable pour avancer.
- Patches JK / Lux / navmesh à reprendre plus tard.

### Dettes

- Patches JK à reprendre.
- Patches Lux intérieur à vérifier plus tard.
- Risque navmesh sur Jorrvaskr / Fort Dawnguard / Castle Volkihar.
- Traductions `- FR` à garder en attente selon la méthode SKYFORGE.

---

## Étape 652 — Audit groupé `[07.4 - LANDS]`

### Verdict

Sous-bloc très chargé, globalement cohérent, mais à garder en validation provisoire.

### Familles concernées

- Fontaines / routes / frontières.
- Solitude Temple Frescoes / Sepolcri / Imperial Forts.
- Ryn’s locations.
- Orc Strongholds.

### Plugins actifs principaux

- `Drinking Fountains of Skyrim for SSE.esp`
- `Drinking Fountains of Skyrim - HD patch.esp`
- `HoldBorderBanners.esp`
- `Man Those Borders!.esp`
- `RoadsignsOverhaul.esp`
- `WiZkiD Specific Signs.esp`
- `SolitudeTempleFrescoes.esp`
- `Sepolcri.esp`
- `LadyStoneReCovered.esp`
- `Ryn's Standing Stones.esp`
- `Ryn's Anise's Cabin.esp`
- `Ryn's Saarthal.esp`
- `Ryn's White River Watch.esp`
- `Ryn's Halted Stream Camp.esp`
- `Ryn's Secunda's Kiss.esp`
- `Ryn's Bleakwind Basin.esp`
- `Ryn's Bleakwind Basin _USSEP_Patch.esp`
- `Ryn's GoldenGlow Estate.esp`
- `Ryn's Bleakfalls Tower.esp`
- `Ryn's Crabber's Shanty.esp`
- `ValtheimKeepRecovered.esp`
- `BleakFallsReCovered.esp`
- `Ryn's Loreius Farm.esp`
- `Ryn's Sarethi Farm.esp`
- `Ryn's Ustengrav.esp`
- `Ryn's Mistwatch Folly.esp`
- `Ryn's Karthspire.esp`
- `Ryn's Western Watchtower.esp`
- `Ryn's Snow-Shod Farm.esp`
- `Ryn's Robber's Gorge.esp`
- `Orc Strongholds - Narzulbur.esp`
- `Orc Strongholds - Largashbur.esp`
- `Orc Strongholds - Mor Khazgur.esp`
- `Orc Strongholds - Dushnikh Yal.esp`

### Décision

- Sous-bloc conservé.
- Aucun nouveau fichier actif installé.
- Pas de LOOT.
- Pas de DynDOLOD / LOD.
- Pas de BodySlide.
- Pandora non relancé.
- Pas de test SKSE requis, car aucun changement actif.

### Dettes

- Navmesh.
- Lux Orbis.
- Grass clipping.
- LOD / DynDOLOD.
- Patches extérieurs différés.
- Traductions `- FR` en attente.

---

## Étape 653 — Audit groupé `[07.5 - RUINS]`

### Verdict

Sous-bloc propre, faible risque, principalement textures / parallax / replacers visuels.

### Mods concernés

- `RUSTIC RELIEFS`
- `RUSTIC RELIEFS - Parallax`
- `CleverCharff's Nordic Ruins`
- `Gorgeous Ruin Door SE 2K`
- `Tower Ruins 2k Texture Replacer`

### Plugins actifs

- Aucun plugin clairement associé à ce sous-bloc n’est relevé.

### Décision

- Sous-bloc conservé.
- Aucun nouveau fichier actif installé.
- Aucun plugin ajouté.
- Aucun ajout au compteur non-light.

### Dette

- Cohérence parallax / ENB à surveiller plus tard.

---

## Étape 654 — Audit groupé `[07.6 - INTERIORS]`

### Verdict

Sous-bloc très riche et très sensible. Cohérent avec la logique Nolvus Awakening, mais validation provisoire uniquement.

### Groupes concernés

- Underground / parallax / sewers.
- Distinct Interiors.
- Dragonsreach JK + RedBag.
- Whiterun interiors Ryn / EEK / JK.
- Solitude / Windhelm / Riften / Markarth / temples / guildes / College.

### Plugins actifs principaux

- `SkyrimSewers.esp`
- `Distinct Interiors.esp`
- `JK's Dragonsreach.esp`
- `RedBag's Dragonsreach.esp`
- `JK's & Redbag's Dragonsreach Patch.esp`
- `EEKs Whiterun Interiors.esp`
- nombreux plugins JK’s Interiors
- `Blue Palace Frescoes.esp`
- `GG's Thieves Guild Headquarters.esp`
- `Snazzy Furniture and Clutter Overhaul.esp`

### Alertes spécifiques

- `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD - PROVOQUE DES CTD`
  - Ne pas activer / ne pas réintroduire sans audit dédié.
- `JK's Temple of Dibella - PATCHES A VOIR PLUS TARD - VERIFIER SEXLAB DIBELLA SISTERHOOD`
  - Ne pas finaliser avant la future pile SexLab / Dibella Sisterhood.

### Dettes fortes

- Lux intérieur / patch hub.
- Distinct Interiors patch collection.
- JK / EEK / Ryn / RedBag patches.
- Skyrim Sewers patches.
- Navmesh.
- Quêtes / schedules NPC.
- Parallax interiors.
- Traductions `- FR` en attente.

### Décision

- Sous-bloc `[07.6 - INTERIORS]` conservé.
- Validation provisoire uniquement.
- Aucun nouveau fichier actif installé.
- Pas de LOOT.
- Pas de DynDOLOD / LOD.
- Pas de BodySlide.
- Pandora non relancé.
- Pas de test SKSE requis, car aucun changement actif.

---

## Étape 655 — Clôture provisoire du bloc 07

### Verdict

Bloc 07 stable pour continuer, mais non clôturé définitivement.

La structure générale est en place ; les dettes principales concernent Lux / Lux Orbis / Lux Via, les patch hubs, les navmesh, les intérieurs JK / Distinct / EEK / Ryn, et le futur LOD / DynDOLOD.

### Blocs audités

- `[07 - CITIES TOWNS INTERIORS LIGHTING]`
- `[07.1 - PLAYER HOMES]`
- `[07.2 - FARMHOUSES]`
- `[07.3 - OTHER LOCATIONS]`
- `[07.4 - LANDS]`
- `[07.5 - RUINS]`
- `[07.6 - INTERIORS]`

### Référence de test conservée

- SKSE / menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : oui
- Overwrite : vide
- Compteur ESP + ESM non-light : `138`

Aucun changement actif n’a été fait pendant les audits. Aucun nouveau test SKSE n’est donc requis pour cette clôture provisoire.

### Décision finale

- Bloc 07 clôturé provisoirement.
- Stable pour continuer.
- Aucun nouveau fichier actif installé.
- Aucun test SKSE supplémentaire requis.
- Aucun LOOT lancé.
- Aucun DynDOLOD / LOD généré.
- Aucun BodySlide généré.
- Pandora non relancé.
- Compteur non-light conservé : **138**.
- Overwrite conservé vide.
