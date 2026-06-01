# Changelog / validation — partie 3

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie poursuit le changelog à partir du sous-bloc **07.4 - LANDS**.

---

## État validé après l’étape 327

**Dernière étape validée :**  
`Étape 327 — Pause technique Nexus`

**Dernière étape d’installation validée :**  
`Étape 326 — Ryn’s Standing Stones`

**Module en cours :**  
`07 - CITIES TOWNS INTERIORS LIGHTING`

**Sous-bloc en cours :**  
`07.4 - LANDS`

**Compteur confirmé :**  
ESP + ESM non-light : `79`

**Résultat validé :**

- SKSE lancé via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- LOOT non lancé : OK
- LOD / DynDOLOD non générés : OK
- Installations suspendues temporairement à cause de l’instabilité Nexus : OK

**Étapes ajoutées / documentées lors de cette mise à jour :**

- `Étape 320 — Lands pack 1`
- `Étape 321 — Lands pack 2`
- `Étape 322 — Contrôle Lands pack 1-2`
- `Étape 323 — Lands pack 3 : WiZkiD Signs`
- `Étape 324 — Lands pack 4 : Temple Frescoes + Sepolcri`
- `Étape 325 — Lands pack 5 : Imperial Forts`
- `Étape 326 — Lands pack 6 : Ryn's Standing Stones`
- `Étape 327 — Pause technique Nexus`

**Décisions ajoutées / confirmées lors de cette mise à jour :**

- `Drinking Fountains of Skyrim` installé selon choix Nolvus, plugin format ESPFE / ESPL.
- `Drinking Fountains - My HD version ESPFE SE` installé.
- `Hold Border Banners` installé, patches différés.
- `Man Those Borders Reborn` installé, patches différés.
- `Road Signs Overhaul` installé, patches différés.
- `My Road Signs are Beautiful - French` installé avec choix 2K-1K et marqué `A REINSTALL PLUS TARD`.
- `WiZkiD Signs` installé en version 2.6, options de base, aucun patch FOMOD coché, marqué `A REINSTALL PLUS TARD`.
- `WiZkiD Specific Signs` installé.
- `Solitude Temple Frescoes` installé en version Complete No Lanterns ESL.
- `Sepolcri` installé en main file uniquement, patches différés.
- `Imperial Forts Parallax Meshes` installé.
- `HD Remastered Imperial Forts - 2K` installé ; versions 4K / 8K non installées.
- `Setting on Sulphur` non installé, à vérifier plus tard dans le bloc parallax / shaders si nécessaire.
- `Ryn's Lady Stone` et `Ryn's Standing Stones` installés, patches différés.
- Patch `Interesting NPCs` pour Ryn's Standing Stones différé jusqu’à éventuelle intégration de `Interesting NPCs / 3DNPC`.
- Patches routes / panneaux / frontières / Sepolcri / Ryn's Standing Stones / Lux / Lux Orbis / Northern Roads / Landscape and Water Fixes / LOD / DynDOLOD / Nolvus différés.
- Pause technique Nexus : installations suspendues temporairement.
- Ne pas modifier MO2, ne pas toucher aux DLL, ne pas lancer LOOT, ne pas générer LOD / DynDOLOD pendant la pause.

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/11_cities_towns_interiors_lighting_part_5.md`
- `docs/procedure/99_changelog_validation_part_3.md`
- `docs/procedure/06_decisions_differees_part_4.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `README.md`

**Prochaine reprise :**  
`Étape 328 — Suite module 07 : Lands / Cities / Towns / Interiors / Lighting`, quand Nexus sera stable.

---

## Rappel méthode

- Avancer prudemment, par petits blocs.
- Tester via SKSE jusqu’au menu après chaque bloc.
- Tester individuellement les DLL / SKSE sensibles, masters, FOMOD complexes ou sources externes.
- Ne pas lancer LOOT pour l’instant.
- Ne pas générer LOD / DynDOLOD tant que les choix villes / paysages / routes / arbres / patches ne sont pas stabilisés.
- Ne pas toucher au panneau droit sauf missing master.
- Ne pas modifier MO2 / DLL pendant la pause Nexus.
- Ne pas installer de patch si le mod parent n’est pas installé ou officiellement retenu.
- Garder les décisions différées dans les fichiers dédiés.
- Garder la numérotation chronologique globale, même quand les étapes sont reclassées dans des fichiers thématiques.
