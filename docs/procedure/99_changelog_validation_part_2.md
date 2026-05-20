# Changelog / validation — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie poursuit le changelog principal à partir du module **07 - CITIES TOWNS INTERIORS LIGHTING**.

---

## État validé après l’étape 289

**Dernière étape validée :**  
`Étape 289 — Environs Hroggar’s House`

**Module en cours :**  
`07 - CITIES TOWNS INTERIORS LIGHTING`

**Dernier profil stable créé :**  
`SKYFORGE - Stable étape 275 villages Ivarstead OK`

**Compteur confirmé :**  
ESP + ESM non-light : `55`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- LOD / DynDOLOD non générés : OK

**Étapes ajoutées / documentées lors de cette mise à jour :**

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

**Décisions ajoutées / confirmées lors de cette mise à jour :**

- Ouverture officielle du module `07 - CITIES TOWNS INTERIORS LIGHTING`.
- Socle Lux installé : `Lux Via`, `Lux Orbis`, `Lux`.
- `Lux Orbis - Patch Hub - A REINSTALL PLUS TARD` installé mais à compléter / réinstaller plus tard.
- `The Great Cities - Resources` installé.
- Les patch collections Great Cities / COTN / Environs sont marquées `A COMPLETER PLUS TARD` pour la future phase de patching.
- `Dragon Bridge` est différé.
- `The Great City Of Falkreath SSE Edition` est retenu en choix Nolvus, sans mélange COTN / JK / patches complexes.
- `Cities of the North - Dawnstar` et son update sont décochés / remplacés par `The Great City Of Dawnstar`.
- `Cities of the North - Winterhold` est décoché / remplacé par `The Great City Of Winterhold`.
- `Cities of the North - Morthal` est décoché, choix à revoir.
- `The Great Cities - CC Fishing Patch` est identifié mais différé.
- `3DNPC-TGCoMM Patch by WiZkiD` est différé jusqu’à installation éventuelle de `3DNPC`.
- LOD / DynDOLOD ne sont pas générés à ce stade.
- LOOT n’a pas été lancé.

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/11_cities_towns_interiors_lighting.md`
- `docs/procedure/06_decisions_differees_part_3.md`
- `docs/procedure/99_changelog_validation_part_2.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`

**Prochaine reprise :**  
`Étape 290 — Suite module 07 : Cities / Towns / Interiors / Lighting`

---

## Rappel méthode

- Avancer prudemment, par petits blocs.
- Tester via SKSE jusqu’au menu après chaque bloc.
- Tester individuellement les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes.
- Ne pas lancer LOOT pour l’instant.
- Ne pas générer LOD / DynDOLOD tant que les choix villes / paysages / routes / arbres / patches ne sont pas stabilisés.
- Ne pas toucher au panneau droit sauf missing master.
- Ne pas installer de patch si le mod parent n’est pas installé ou officiellement retenu.
- Garder les décisions différées dans les fichiers dédiés.
- Garder la numérotation chronologique globale, même quand les étapes sont reclassées dans des fichiers thématiques.
