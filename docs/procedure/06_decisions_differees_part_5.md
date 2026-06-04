# Décisions différées et points à revoir — partie 5

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie complète les décisions différées après la reprise Nexus et la clôture du sous-bloc **07.4 - LANDS**.

---

## Décisions importantes ajoutées après l’étape 341

- Le sous-bloc `07.4 - LANDS` est marqué comme installation principale terminée.
- Les patches complexes du bloc Lands restent différés.
- LOOT reste différé.
- LOD / DynDOLOD restent différés.
- Le profil stable `SKYFORGE - Stable étape 341 lands installation terminée` sert de référence de reprise.

---

### Étape 329 — Ryn's Anise's Cabin

**Décision :**  
`Ryn's Anise's Cabin` est installé selon la logique Nolvus.

**Choix :**

- Main file uniquement.
- Aucun patch séparé installé.

**Patches différés :**

- Tous patches optionnels ou de compatibilité.

**Statut :**  
Installé, patches différés.

---

### Étape 330 — Ryn's Saarthal / White River Watch / Halted Stream Camp / Secunda's Kiss

**Décision :**  
Petit groupe Ryn’s installé selon la logique Nolvus.

**Mods concernés :**

- `Ryn's Saarthal`
- `Ryn's White River Watch`
- `Ryn's Halted Stream Camp`
- `Ryn's Secunda's Kiss`

**Choix :**

- Main files uniquement.
- Aucun patch optionnel installé.

**Patches différés :**

- Lux.
- Lux Orbis.
- Northern Roads.
- eFPS.
- Occlusion.
- LOD / DynDOLOD.
- Patches Nolvus éventuels.

**Statut :**  
Installés, patches différés.

---

### Étape 331 — Ryn's Bleakwind Basin / Goldenglow / Bleak Falls Tower / Crabber's Shanty

**Décision :**  
Suite courte Ryn’s installée selon la logique Nolvus.

**Mods concernés :**

- `Ryn's Bleakwind Basin`
- `Ryn's Bleakwind Basin USSEP Patch`
- `Ryn's Goldenglow Estate`
- `Ryn's Bleak Falls Tower`
- `Ryn's Crabber's Shanty and Titanclaw Lair`

**Choix :**

- Main files uniquement.
- Patch USSEP de Ryn’s Bleakwind Basin installé.

**Patches différés :**

- Lux.
- Lux Orbis.
- Northern Roads.
- DynDOLOD.
- Patches Nolvus.

**Statut :**  
Installés, patches différés.

---

### Étape 333 — Ryn's Valtheim Towers / Bleak Falls Barrow / Loreius Farm / Sarethi Farm

**Décision :**  
Suite Ryn’s installée selon la logique Nolvus.

**Mods concernés :**

- `Ryn's Valtheim Towers`
- `Ryn's Bleak Falls Barrow`
- `Ryn's Loreius Farm`
- `Ryn's Sarethi Farm`

**Choix :**

- Main files uniquement.
- Aucun patch optionnel installé.

**Patches différés :**

- eFPS.
- Lux Orbis.
- Northern Roads.
- Water for ENB.
- Autres patches de compatibilité éventuels.

**Statut :**  
Installés, patches différés.

---

### Étape 335 — Ryn's Ustengrav / Mistwatch Folly / Karthspire / Western Watchtower

**Décision :**  
Suite Ryn’s installée selon la logique Nolvus.

**Mods concernés :**

- `Ryn's Ustengrav`
- `Ryn's Mistwatch Folly`
- `Ryn's Karthspire`
- `Ryn's Western Watchtower`

**Choix :**

- Main files uniquement.
- Aucun patch optionnel installé.

**Note spécifique Mistwatch :**

- Patch optionnel `Missing Tower Base Fix` disponible pour `Ryn's Mistwatch Folly`.
- À installer uniquement si le bug de base de tour désactivée est constaté.
- Test possible plus tard via `coc Mistwatchexterior03`.

**Patches différés :**

- Lux.
- Lux Orbis.
- Northern Roads.
- eFPS.
- Occlusion.
- `Missing Tower Base Fix`, sauf bug confirmé.

**Statut :**  
Installés, patches différés.

---

### Étape 337 — Ryn's Snow-Shod Farm / Robber's Gorge

**Décision :**  
Mini-pack Ryn’s installé selon la logique Nolvus.

**Mods concernés :**

- `Ryn's Snow-Shod Farm`
- `Ryn's Robber's Gorge`

**Choix :**

- Main files uniquement.
- Aucun patch optionnel installé.

**Patches différés :**

- Lux Via.
- Northern Roads.
- Lawbringer.
- Lainalten.
- Fixes optionnels éventuels.

**Statut :**  
Installés, patches différés.

---

### Étape 339 — Orc Strongholds

**Décision :**  
Les forteresses orques sont installées en modules séparés, selon la logique Nolvus.

**Mods concernés :**

- `Orc Strongholds - Narzulbur`
- `Orc Strongholds - Largashbur`
- `Orc Strongholds - Mor Khazgur`
- `Orc Strongholds - Dushnikh Yal`

**Choix :**

- Modules séparés installés.
- Version AIO non installée.
- Main files uniquement.
- Aucun patch optionnel installé pour l’instant.

**Patches différés :**

- Lux Orbis.
- Lux Via.
- eFPS.
- Folkvangr.
- Northern Roads.
- Patches Nolvus éventuels.

**Statut :**  
Installés, patches différés.

---

### Étape 341 — Clôture 07.4 LANDS

**Décision :**  
Le sous-bloc `07.4 - LANDS` est clôturé côté installation principale.

**Profil stable :**  
`SKYFORGE - Stable étape 341 lands installation terminée`

**Différés globaux conservés :**

- Patches Lux / Lux Orbis / Lux Via.
- Patches Northern Roads.
- Patches eFPS.
- Patches DynDOLOD / LOD.
- Patches Nolvus.
- Patches optionnels signalés pendant les installations.

**Statut :**  
Sous-bloc Lands terminé, patching global différé.

---

### LOD / DynDOLOD — clôture 07.4 LANDS

**Décision :**  
LOD / DynDOLOD ne sont toujours pas générés après la clôture du sous-bloc Lands.

**Raison :**  
Les patches routes / paysages / villes / éclairage / arbres / occlusion ne sont pas encore finalisés.

**Statut :**  
Différé.
