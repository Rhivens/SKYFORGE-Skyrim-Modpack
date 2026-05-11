# Décisions différées et points à revoir — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie complète `06_decisions_differees.md` à partir des décisions ajoutées pendant les modules **05 - VISUAL BASE MESHES TEXTURES** et **06 - LANDSCAPE GRASS TREES WATER**.

---

## Décisions importantes ajoutées après l’étape 265

- `Assorted Mesh Fixes` reste dans `02 - BUG FIXES & ENGINE PATCHES` : ne pas réinstaller, ne pas déplacer.
- Les patches de `Mesh Patch for Various Mods` sont laissés en fichiers séparés pour une meilleure lisibilité MO2.
- Le patch `Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch` est exclu car il dépend d’une logique ELFX non retenue actuellement.
- `Particle Patch` est installé en format BSA avec plugin `Particle Patch`.
- `AcousticTemplateFixes_ReverbInteriorSounds.esp` a été réactivé après contrôle du module 05.
- `Landscape Fixes For Grass Mods` reste marqué `A REINSTALL PLUS TARD`.
- `Complementary Grass Fixes` reste marqué `A REINSTALL PLUS TARD` car ses patches optionnels sont différés.
- `Skyrim Landscape and Water Fixes` reste marqué `A REINSTALL PLUS TARD` car plusieurs patches dépendront des futurs choix paysage / eau / villes / quêtes.
- `Majestic Mountains` reste marqué `A REINSTALL PLUS TARD`.
- En Skyrim SE 1.5.97 Best of Both Worlds avec contenus AE / Creation Club conservés, le choix `Landscape ESM : AE version` de Majestic Mountains est correct.
- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD` est installé mais décoché à cause du master manquant `Parallax TXST Fixes.esp`.
- `Atlantean Landscape` est différé pour un futur bloc `Parallax / Complex Terrain / ENB / textures paysage avancées`.
- `Happy Little Trees` reste marqué `A REINSTALL PLUS TARD`.
- Les alternatives neige de Happy Little Trees sont différées jusqu’au futur bloc neige / météo / ENB.
- `Tree Billboards - HLT 1.01` n’est pas installé à ce stade.
- `Ancient Trees Of Skyrim` est abandonné / supprimé après réévaluation des sources disponibles.
- `The Omnibus - Terrain Complex Parallax AiO` est différé.
- `Water for ENB - No Parallax - A REINSTALL PLUS TARD` est installé et validé, mais pourra être réinstallé plus tard selon le futur bloc ENB / parallax / météo.
- `Snowy Surfaces Sound Collision and Aesthetics - A REINSTALL PLUS TARD` est installé sans patch et pourra être revu avec le futur bloc neige / météo.
- `Praedy's Soul Cairn - SE` est différé à cause du prérequis `Skeleton Replacer HD - SE`.
- `Remove Hanging Moss From Trees` est installé en version `1.6`, car la version `1.5` n’était pas disponible.
- Le compteur ESP + ESM non-light est confirmé à `42` après clôture temporaire du module 06.
- Le module `06 - LANDSCAPE GRASS TREES WATER` est clôturé temporairement après création du profil stable `SKYFORGE - Stable étape 264 module 06 OK`.

---

### Étape 207 — Mesh Patch for Various Mods

**Décision :**  
Les fichiers de patches sont laissés séparés pour meilleure lisibilité dans MO2.

**Fichiers installés :**

- `SMIM - Quality Addon - Unofficial Material Fix Patch`
- `Unofficial Material Fix - Assorted Mesh Fixes Patch`
- `Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch`
- `SMIM - Assorted Mesh Fixes Patch`

**Fichiers non pris :**

- `Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch`
- `Skyrim Particle Patch for ENB - Assorted Mesh Fixes - Solitude Mesh Fixes Patch`
- `Assorted Mesh Fixes - SMIM - Really Blended Roads Patch`
- `Assorted Mesh Fixes - SMIM - Blended Roads Patch`
- `Dlizzio's Mesh Fixes - Skyrim Landscape and Water Fixes Patch`

**Statut :**  
Décision validée.

---

### Étape 209 — Patch Particle / Unofficial Material Fix

**Décision :**  
Aucun patch simple correspondant n’est installé.

**Patch explicitement exclu :**

- `Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch`

**Raison :**  
Dépend de la logique ELFX, non retenue actuellement pour SKYFORGE.

**Statut :**  
Annulé / différé.

---

### Étape 210 — Correction audio transversale

**Décision / correction :**  
`AcousticTemplateFixes_ReverbInteriorSounds.esp` était décoché dans le panneau droit et a été réactivé.

**Raison :**  
Le patch ASIF pour `Reverb Interior Sounds Expansion` doit rester actif après l’étape 185.

**Statut :**  
Correction validée.

---

### Étape 213 — Complementary Grass Fixes

**Décision :**  
`Complementary Grass Fixes` est installé en core uniquement et marqué `A REINSTALL PLUS TARD`.

**Patches différés selon futurs choix :**

- JK’s Skyrim
- The Great Cities and Towns
- Arthmoor towns
- Helgen Reborn
- Moon and Star
- Expanded Towns and Cities
- Holds
- Verdant ou autre grass mod
- Ryn’s modules
- Cutting Room Floor
- JK’s Whiterun Outskirts
- Riften Extension

**Statut :**  
Base installée, patches différés.

---

### Étape 215 — Skyrim Landscape and Water Fixes

**Décision :**  
`Skyrim Landscape and Water Fixes - A REINSTALL PLUS TARD` est placé après les fixes précédents et peut écraser certains fichiers SMIM / Assorted / Dlizzio.

**Options non prises à revoir plus tard si besoin :**

- Parallax SLaWF meshes
- Free Crops
- Missing Lights Fixes
- v1.5.97.esm-s and USSEP
- Helgen Light Sources
- Water for ENB
- Majestic Mountains
- Lanterns of Skyrim II
- No Snow Under the Roof
- Helgen Reborn
- The Hunt for the Spectre
- Alternate Start
- Big combo Water for ENB

**Statut :**  
Base installée, patches différés.

---

### Étape 217 — Majestic Mountains

**Décision :**  
`Majestic Mountains - A REINSTALL PLUS TARD` est placé après `Skyrim Landscape and Water Fixes`.

**Choix confirmé :**  
`Landscape ESM : AE version`

**Raison :**  
Même avec le runtime Skyrim SE 1.5.97, le contenu AE / Creation Club est conservé dans SKYFORGE.

**Options non prises :**

- Moss Rocks ESL Version
- Effect Meshes
- Sun Direction autre que `None`

**Statut :**  
Installé, réinstallation future possible.

---

### Étape 219 — Atlantean Landscape

**Décision :**  
`Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD` est installé mais décoché.

**Problème :**  
`Atlantean Landscape.esp` requiert le master :

`Parallax TXST Fixes.esp`

**Décision associée :**  
Atlantean est différé pour un futur bloc :

`Parallax / Complex Terrain / ENB / textures paysage avancées`

**Règle textures ajoutée :**

- 2K par défaut si disponible
- 1K pour petits objets / optimisation
- 4K uniquement pour éléments très visibles si justifié
- 8K exclu par défaut

**Statut :**  
Suspendu proprement / décoché.

---

### Étape 220 — Happy Little Trees

**Décision :**  
`Happy Little Trees - A REINSTALL PLUS TARD` est installé avec le choix FOMOD `Default`.

**Ajout installé :**

- `Happy Little Trees - HLT Patch`

**Fichier non pris :**

- `Tree Billboards - HLT 1.01`

**Options Alternate non prises :**

- Alternate 1
- Alternate 2
- Alternate 3

**Raison :**  
Les alternatives neige seront revues plus tard avec le bloc neige / météo / ENB.

**Statut :**  
Installé, réinstallation future possible.

---

### Étape 235 — Water for ENB

**Décision :**  
`Water for ENB - No Parallax - A REINSTALL PLUS TARD` est installé et validé avec une sélection prudente.

**Choix retenus :**

- `Shades of Skyrim for ENB`
- `No Parallax`
- `Atlas Map Markers`
- `Folkvangr`
- `Generic Landscape Patch`
- `Landscape Fixes For Grass Mods`
- `Flat World Map : None`
- `No Legacy iNeed Support`

**Décision associée :**  
Le mod pourra être réinstallé plus tard selon les choix ENB / parallax / météo / carte finale.

**Statut :**  
Installé, réinstallation future possible.

---

### Étape 239 — Snowy Surfaces Sound Collision and Aesthetics

**Décision :**  
`Snowy Surfaces Sound Collision and Aesthetics - A REINSTALL PLUS TARD` est installé sans patch.

**Choix retenus :**

- `Vanilla`
- `Vanilla Standard Meshes`
- Aucun patch

**Décision associée :**  
À revoir plus tard avec le futur bloc neige / météo / ENB.

**Statut :**  
Installé, réinstallation future possible.

---

### Étape 247 — Praedy's Soul Cairn - SE

**Décision :**  
`Praedy's Soul Cairn - SE - DIFFERE SKELETON REPLACER`

**Raison :**  
Le mod signale `Skeleton Replacer HD - SE` dans les requirements. Décision prudente : ne pas introduire ce prérequis maintenant.

**Action future :**  
Reprendre plus tard dans un mini-bloc dédié.

**Statut :**  
Différé.

---

### Étape 250 / 252 / 254 — Contrôle statut ESPFE des plugins paysage récents

**Plugins à vérifier plus tard :**

- `Diverse Windmill Sails.esp`
- `mihailcrabshell.esp`
- `Remove Hanging Moss From Trees.esp`
- `Unique Flowers & Plants.esp`
- `waterplants.esp`
- `WAVY Waterfalls Effect.esp`
- `StormLightning.esp`

**Raison :**  
Le statut ESPFE / light ou ESP normal doit être confirmé proprement dans MO2 / xEdit si nécessaire.

**Statut :**  
Vérification différée.

---

### Étape 252 / 257 / 265 — Compteur ESP + ESM

**État initial :**  
ESP + ESM non-light : `40` à l’étape 252.

**État confirmé après reprise :**  
ESP + ESM non-light : `42` à partir de l’étape 257.

**Cohérence :**  
Passage de `40` à `42` cohérent après ajout de :

- `Unique Flowers & Plants.esp`
- `waterplants.esp`

**Statut :**  
Vérification levée / compteur confirmé.

---

### Étape 254 — Unique Flowers & Plants

**Constat :**  
Malgré le choix `Unique Flowers and Plants for Skyrim SE DLC Compatible ESM Version`, le plugin visible est :

`Unique Flowers & Plants.esp`

**Action future :**  
Vérifier plus tard si le plugin est master-flagged ou ESP normal si nécessaire.

**Statut :**  
Vérification différée.

---

### Étape 260 — The Omnibus - Terrain Complex Parallax AiO

**Décision :**  
`The Omnibus - Terrain Complex Parallax AiO` est différé.

**Raison :**  
À traiter plus tard dans une logique `Parallax / Complex Terrain / ENB / textures paysage avancées`, avec `Atlantean Landscape` et les choix graphiques avancés.

**Statut :**  
Différé.

---

### Étape 263 — Ancient Trees Of Skyrim

**Décision finale :**  
`Ancient Trees Of Skyrim` est abandonné et supprimé.

**Constats :**

- Source Bethesda constatée comme `Xbox only` côté interface.
- Source Nexus trouvée mais page désactivée / archive non maintenue.

**Raison :**  
Ne pas utiliser de source douteuse ou non maintenue pour SKYFORGE.

**Statut :**  
Abandonné / supprimé.

---

### Étape 264 / 265 — Clôture temporaire du module 06

**Décision :**  
Le module `06 - LANDSCAPE GRASS TREES WATER` est clôturé temporairement.

**Profil stable créé :**

`SKYFORGE - Stable étape 264 module 06 OK`

**État validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK
- ESP + ESM non-light : `42`

**Statut :**  
Module fermé temporairement.
