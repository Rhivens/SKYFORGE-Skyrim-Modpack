# Changelog / validation — partie 4

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie poursuit le changelog à partir de la reprise Nexus et clôture le sous-bloc **07.4 - LANDS**.

---

## État validé après l’étape 341

**Dernière étape validée :**  
`Étape 341 — Contrôle final 07.4 LANDS et profil stable`

**Dernière étape d’installation validée :**  
`Étape 339 — Lands pack 9 : Orc Strongholds`

**Module en cours :**  
`07 - CITIES TOWNS INTERIORS LIGHTING`

**Sous-bloc terminé :**  
`07.4 - LANDS`

**Profil stable créé :**  
`SKYFORGE - Stable étape 341 lands installation terminée`

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
- Sous-bloc `07.4 - LANDS` clôturé : OK

**Étapes ajoutées / documentées lors de cette mise à jour :**

- `Étape 328 — Reprise Nexus / 07.4 LANDS`
- `Étape 329 — Ryn’s Anise’s Cabin`
- `Étape 330 — Lands pack 4 : petit groupe Ryn’s`
- `Étape 331 — Lands pack 5 : Ryn’s suite courte`
- `Étape 332 — Validation Lands pack 5`
- `Étape 333 — Lands pack 6 : Valtheim / Bleak Falls / Farms`
- `Étape 334 — Validation Lands pack 6`
- `Étape 335 — Lands pack 7 : Ustengrav / Mistwatch / Karthspire / Western Watchtower`
- `Étape 336 — Validation Lands pack 7 + note Mistwatch`
- `Étape 337 — Lands pack 8 : Snow-Shod Farm + Robber’s Gorge`
- `Étape 338 — Validation Lands pack 8`
- `Étape 339 — Lands pack 9 : Orc Strongholds`
- `Étape 340 — Validation Lands pack 9`
- `Étape 341 — Contrôle final 07.4 LANDS et profil stable`

**Décisions ajoutées / confirmées lors de cette mise à jour :**

- Reprise Nexus validée après la pause technique.
- Reprise du bloc Lands uniquement, sans LOOT ni LOD.
- `Ryn's Anise's Cabin` installé, main file uniquement, patches différés.
- Suite Ryn’s installée en petits groupes cohérents.
- `Ryn's Bleakwind Basin USSEP Patch` installé avec `Ryn's Bleakwind Basin`.
- Patches Lux / Lux Orbis / Lux Via / Northern Roads / eFPS / DynDOLOD / Nolvus non installés à ce stade.
- `Ryn's Mistwatch Folly` : patch optionnel `Missing Tower Base Fix` identifié, mais différé sauf bug constaté via `coc Mistwatchexterior03`.
- `Ryn's Snow-Shod Farm` et `Ryn's Robber's Gorge` installés en main files uniquement.
- Orc Strongholds installés en modules séparés : Narzulbur, Largashbur, Mor Khazgur, Dushnikh Yal.
- Version AIO Orc Strongholds non installée.
- Patches Orc Strongholds Lux Orbis / Lux Via / eFPS / Folkvangr / Northern Roads / Nolvus différés.
- Sous-bloc `07.4 - LANDS` marqué comme installation principale terminée.
- Profil stable créé : `SKYFORGE - Stable étape 341 lands installation terminée`.

**Fichiers ajoutés lors de cette mise à jour :**

- `docs/procedure/11_cities_towns_interiors_lighting_part_6.md`
- `docs/procedure/99_changelog_validation_part_4.md`
- `docs/procedure/06_decisions_differees_part_5.md`

**Fichiers mis à jour lors de cette mise à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`
- `docs/procedure/00_resume_etat_actuel.md`
- `README.md`

**Prochaine reprise :**  
`Étape 342`

---

## Rappel méthode

- Avancer prudemment, par petits blocs.
- Tester via SKSE jusqu’au menu après chaque bloc important.
- Ne pas lancer LOOT pour l’instant.
- Ne pas générer LOD / DynDOLOD tant que les choix villes / paysages / routes / arbres / patches ne sont pas stabilisés.
- Ne pas toucher au panneau droit sauf missing master.
- Ne pas installer de patch si le mod parent n’est pas installé ou officiellement retenu.
- Garder les décisions différées dans les fichiers dédiés.
- Garder la numérotation chronologique globale, même quand les étapes sont reclassées dans des fichiers thématiques.
