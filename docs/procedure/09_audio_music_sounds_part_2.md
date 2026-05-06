# Audio, musiques et sons — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes **186 à 203** classées dans le module **04 - AUDIO MUSIC SOUNDS**.

---

### 186. Quiet Better Jumping

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter la version audio compatible CGO / AOS / ISC pour Better Jumping.

**Mod ajouté :**

- `Quiet Better Jumping for CGO - Audio Overhaul - Immersive Sounds Integration`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/44041

**Choix :**

- Fichier : `Quiet Better Jumping for CGO - Audio Overhaul - Immersive Sounds Integration`
- Version compatible avec :
  - `Audio Overhaul Skyrim`
  - `Immersive Sounds - Compendium`
  - `Audio Overhaul - Immersive Sounds Integration`

**Note :**  
Incident Visual C++ sur le nouveau PC, corrigé avant validation. Problème non lié au mod.

**Validation :**

- SKSE via MO2 : OK
- Menu principal : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 186 validée.

---

### 187. Phoenix Compendium différé

**Module :** 04 - AUDIO MUSIC SOUNDS / Décisions différées

**Décision :**  
`Phoenix Compendium` est différé / non installé.

**Raison :**

- Contenu vocal anglais non prioritaire pour SKYFORGE FR.
- Pas nécessaire pour Nolvus.
- Pas utile pour Nefaram / SexLab.

**Statut :**  
Étape 187 différée.

---

### 188. Thundering Shouts

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter un remplacement audio plus puissant pour les cris.

**Mod ajouté :**

- `Thundering Shouts`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/14352

**Choix :**

- Fichier : `Thundering Shouts`
- Pas la version `Normal Pitch`
- Pas les versions loose files

**Validation :**

- SKSE via MO2 : OK
- Menu principal : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 188 validée.

---

### 189. Bloc ambiance audio léger

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer un bloc léger d’ambiances et sons de créatures / mort / Blackreach.

**Mods ajoutés :**

- `Authentic Wolf Howls and Aggro`
- `More Painful Death Sounds SE`
- `Update Plugin More Painful Death Sounds SE`
- `50 Percent Chance More Painful Death Sounds SE`
- `Blackreach Eerie Ambience`

**Liens :**

- Authentic Wolf Howls and Aggro  
  https://www.nexusmods.com/skyrimspecialedition/mods/32948
- More Painful Death Sounds SE  
  https://www.nexusmods.com/skyrimspecialedition/mods/25702
- Blackreach Eerie Ambience  
  https://www.nexusmods.com/skyrimspecialedition/mods/112114

**Choix importants :**

- More Painful Death Sounds :
  - `Plugin Update 1.91esl`
  - option `50 Percent Chance`
- Blackreach Eerie Ambience :
  - `Nirnroot Replacer (All)`
  - `Blackreach Water Loop` décoché
  - `Silence Music` décoché

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 189 validée.

---

### 190. Bloc vents / guerre

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des ambiances de vents nordiques et de guerre.

**Mods ajoutés :**

- `Nordic Winds`
- `Ambient Warfare`

**Mod différé :**

- `Whispering Tomes of Apocrypha`

**Liens :**

- Nordic Winds  
  https://www.nexusmods.com/skyrimspecialedition/mods/112370
- Ambient Warfare  
  https://www.nexusmods.com/skyrimspecialedition/mods/113118
- Whispering Tomes of Apocrypha  
  https://www.nexusmods.com/skyrimspecialedition/mods/113423

**Choix importants :**

- Nordic Winds :
  - `Silent Vanilla Wind Gusts` : None
  - `Alternate Marsh Loop` : None
- Ambient Warfare :
  - `Silent Post War`
- Whispering Tomes :
  - différé car sans options cochées il apportait peu, et les options utiles remplaçaient / silenciaient trop de sons.

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 190 validée, avec `Whispering Tomes of Apocrypha` différé.

---

### 191. Bloc météo / villes / Solstheim

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des ambiances météo, urbaines et de Solstheim.

**Mods ajoutés :**

- `Distant Rolling Thunder`
- `The Sounds of Towns and Cities`
- `Solstheim Exterior Soundscapes`

**Liens :**

- Distant Rolling Thunder  
  https://www.nexusmods.com/skyrimspecialedition/mods/127180
- The Sounds of Towns and Cities  
  https://www.nexusmods.com/skyrimspecialedition/mods/127561
- Solstheim Exterior Soundscapes  
  https://www.nexusmods.com/skyrimspecialedition/mods/121361

**Choix Solstheim :**

- `Ash Storms` coché
- `Harbor Sounds` coché
- `Wind Loop` décoché
- `Skaal Village Wall` décoché
- `Fire Craters` décoché
- `Fire Logs` décoché
- `All Maker Stones` décoché
- `Silent Blowing Ash` décoché

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 191 validée.

---

### 192. Bloc Dawnguard / Soul Cairn / pierres

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des ambiances Dawnguard, Soul Cairn et Standing Stones.

**Mods ajoutés :**

- `Volkihar Soundscape Overhaul - A REINSTALL PLUS TARD`
- `Revenant Spirits of the Soul Cairn`
- `The Standing Sound Stones - A REINSTALL PLUS TARD`

**Liens :**

- Volkihar Soundscape Overhaul  
  https://www.nexusmods.com/skyrimspecialedition/mods/118891
- Revenant Spirits of the Soul Cairn  
  https://www.nexusmods.com/skyrimspecialedition/mods/113884
- The Standing Sound Stones  
  https://www.nexusmods.com/skyrimspecialedition/mods/119471

**Choix importants :**

- Volkihar :
  - patch lighting : None
  - `Mute Music` décoché
  - marqué `A REINSTALL PLUS TARD` pour futur Lux
- Revenant Spirits :
  - `No Voices - With Vanilla Sounds`
  - `Storm Call Impact Sounds` coché
  - suppression lightning triggers BOS décochée
  - silence musique décoché
  - quieter dialogue décoché
- Standing Sound Stones :
  - `Ryn's Patch` décoché
  - marqué `A REINSTALL PLUS TARD` pour futur Ryn’s Standing Stones

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 192 validée.

---

### 193. Bloc combat SFX léger

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des sons d’armes et de boucliers plus marqués.

**Mods ajoutés :**

- `Bleeding Edge - Bladed Weapons SFX Overhaul - A REINSTALL PLUS TARD`
- `Skullbreaker - Blunt Weapons SFX`
- `Bulwark - Shield Audio Overhaul`

**Liens :**

- Bleeding Edge  
  https://www.nexusmods.com/skyrimspecialedition/mods/77384
- Skullbreaker  
  https://www.nexusmods.com/skyrimspecialedition/mods/79219
- Bulwark  
  https://www.nexusmods.com/skyrimspecialedition/mods/76137

**Choix importants :**

- Bleeding Edge :
  - `Bleeding Edge 2.0 Revamp WIP`
  - pas l’ancienne version Nolvus 1.3
  - pas `Subdued One-handed Swings`
  - pas le patch daggers SkyPatcher pour l’instant
  - marqué `A REINSTALL PLUS TARD`
- Les 3 mods écrasent volontairement ISC.

**Validation :**

- Conflits contre `Immersive Sounds - Compendium` : attendus / OK.
- Test groupé OK.

**Statut :**  
Étape 193 validée.

---

### 194. Bloc nature léger

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des ambiances naturelles légères.

**Mods ajoutés :**

- `Wildwood Echoes`
- `Murder of Songbirds`

**Liens :**

- Wildwood Echoes  
  https://www.nexusmods.com/skyrimspecialedition/mods/112008
- Murder of Songbirds  
  https://www.nexusmods.com/skyrimspecialedition/mods/111766

**Note :**  
Le premier lien donné pour `Murder of Songbirds` était mauvais. Lien corrigé : `111766`.

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 194 validée.

---

### 195. Combat Music Fix NG Updated

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer le correctif moderne de musique de combat.

**Mod ajouté :**

- `Combat Music Fix NG Updated`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/110459

**Choix :**

- Version NG Updated moderne.
- Test individuel car plugin SKSE / DLL.

**Validation :**

- SKSE via MO2 : OK
- Menu principal : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 195 validée.

---

### 196. New Game Sound on Continue

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer le plugin SKSE remplaçant le son de continuation / nouveau chargement.

**Mod ajouté :**

- `New Game Sound on Continue (SKSE)`

**Lien correct :**  
https://www.nexusmods.com/skyrimspecialedition/mods/47473

**Note :**  
Un mauvais lien avait été donné au départ. Lien corrigé par Fabien. Test individuel car plugin SKSE.

**Validation :**  
Test individuel OK.

**Statut :**  
Étape 196 validée.

---

### 197. Bloc musiques Skyrim-like léger

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des musiques Skyrim-like légères et cohérentes.

**Mods ajoutés :**

- `Still - Skyrim Inspired Music`
- `Chapter II - Jeremy Soule Inspired Music`
- `Melodies of Civilization - Skyrim Fan-Made Music`

**Liens :**

- Still  
  https://www.nexusmods.com/skyrimspecialedition/mods/19401
- Chapter II  
  https://www.nexusmods.com/skyrimspecialedition/mods/37792
- Melodies of Civilization  
  https://www.nexusmods.com/skyrimspecialedition/mods/30014

**Choix importants :**

- Still :
  - `Still - ESP flagged as ESL`
  - pas replacer
  - pas Personalized Music
  - pas patch Chapter II à ce stade

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 197 validée.

---

### 198. Bloc musiques additionnelles 2

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des musiques additionnelles cohérentes, sans surcharger l’ambiance.

**Mods ajoutés :**

- `Hun Lovaas - Skyrim Fan-Made combat music`
- `The Northerner Diaries - Immersive Edition`

**Mod différé :**

- `Nyghtfall - Dark Fantasy Music`

**Liens :**

- Hun Lovaas  
  https://www.nexusmods.com/skyrimspecialedition/mods/16123
- The Northerner Diaries  
  https://www.nexusmods.com/skyrimspecialedition/mods/28108
- Nyghtfall  
  https://www.nexusmods.com/skyrimspecialedition/mods/39011

**Choix importants :**

- Hun Lovaas :
  - `Hun - Lovaas - ESP flagged as ESL`
  - pas replacer
  - pas Personalized Music
- Nyghtfall :
  - différé car trop dominant
  - à rappeler plus tard : choisir probablement `With Vanilla Music - Nyghtfall`

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 198 validée, avec `Nyghtfall` différé.

---

### 199. Bloc musiques additionnelles 3

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter de nouvelles musiques modulaires et un pack all-in-one léger.

**Mods ajoutés :**

- `The Elder Songs - Complete - A REINSTALL PLUS TARD`
- `Songs to Play Skyrim to - A Music Mod All in One`

**Liens :**

- The Elder Songs  
  https://www.nexusmods.com/skyrimspecialedition/mods/27504
- Songs to Play Skyrim To  
  https://www.nexusmods.com/skyrimspecialedition/mods/69889

**Choix importants :**

- The Elder Songs :
  - modules cochés :
    - `Explore Module`
    - `Town Module`
    - `Castle Module`
    - `Dungeon Atmospheric`
  - modules décochés :
    - `Combat Module`
    - `Tavern Module`
    - `Dungeon Melodic`
  - patches compatibilité : rien coché
  - marqué `A REINSTALL PLUS TARD`
- Songs to Play Skyrim To :
  - `Songs to Play Skyrim 1.1 ESPFE`

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 199 validée.

---

### 200. Bloc musiques additionnelles 4

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des extensions musicales supplémentaires.

**Mods ajoutés :**

- `The Southerner Diaries - A Soundtrack Expansion`
- `Symphonic Soundtrack - Extension HIGH QUALITY`

**Liens :**

- The Southerner Diaries  
  https://www.nexusmods.com/skyrimspecialedition/mods/30138
- Symphonic Soundtrack  
  https://www.nexusmods.com/skyrimspecialedition/mods/38272

**Choix importants :**

- Symphonic Soundtrack :
  - `Extension HIGH QUALITY`
  - pas replacer

**Validation :**  
Test groupé OK.

**Statut :**  
Étape 200 validée.

---

### 201. Ragnarok / Dark Era

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter une musique de combat viking, tout en différant les packs incompatibles avec la stratégie actuelle.

**Mod ajouté :**

- `Ragnarok - Viking Battle Music`

**Lien correct :**  
https://www.nexusmods.com/skyrimspecialedition/mods/44340

**Différés / exclus :**

- `Dark Era` différé car version trouvée dépend de `Personalized Music`.
- `Music Mods Merged SSE Edition` exclu pour l’instant.

**Note :**  
Le premier lien Ragnarok était mauvais, corrigé ensuite.

**Validation :**  
Test individuel léger OK.

**Statut :**  
Étape 201 validée.

---

### 202. Bardes / Collège

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter les chants de bardes, tout en désactivant un mod de musique de collège problématique.

**Mod ajouté :**

- `BA Bard Songs`

**Mod désactivé / différé :**

- `Magic College Music - Songs for Academy - DECOCHE FORM 43`

**Liens :**

- BA Bard Songs  
  https://www.nexusmods.com/skyrimspecialedition/mods/47202
- Magic College Music  
  https://www.nexusmods.com/skyrimspecialedition/mods/1893

**Choix importants :**

- BA Bard Songs :
  - FOMOD : AIO
  - installe un ESPFE
- Magic College Music :
  - installé puis warning Form 43 détecté sur `MagiCollege.esp`
  - désactivé et renommé : `Magic College Music - Songs for Academy - DECOCHE FORM 43`
  - à remplacer plus tard par une alternative SE propre ou conversion CK si vraiment nécessaire

**Validation avec Magic College désactivé :**

- SKSE via MO2 : OK
- Menu principal : OK
- Plus d’avertissement Form 43 : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 202 validée.

---

### 203. Clôture provisoire audio

**Module :** 04 - AUDIO MUSIC SOUNDS

**Décision :**  
Module `04 - AUDIO MUSIC SOUNDS` clos provisoirement.

**Mods actifs finaux du bloc :**

- `Sound Record Distributor`
- `Acoustic Space Improvement Fixes - SkyPatcher`
- `Audio Overhaul for Skyrim (4.1.3) - A REINSTALL PLUS TARD`
- `Immersive Sounds - Compendium - A REINSTALL PLUS TARD`
- `Audio Overhaul - Immersive Sounds Integration (AOS - ISC Compatibility Patch)`
- `Regional Sounds Expansion (SRD - Wilds Dungeons Towns Ambience Birds - Fixes)`
- `Reverb Interior Sounds Expansion`
- `Quiet Better Jumping for CGO - Audio Overhaul - Immersive Sounds Integration`
- `Thundering Shouts`
- `Authentic Wolf Howls and Aggro`
- `More Painful Death Sounds SE`
- `Update Plugin More Painful Death Sounds SE`
- `50 Percent Chance More Painful Death Sounds SE`
- `Blackreach Eerie Ambience`
- `Nordic Winds`
- `Ambient Warfare`
- `Distant Rolling Thunder`
- `The Sounds of Towns and Cities`
- `Solstheim Exterior Soundscapes`
- `Volkihar Soundscape Overhaul - A REINSTALL PLUS TARD`
- `Revenant Spirits of the Soul Cairn`
- `The Standing Sound Stones - A REINSTALL PLUS TARD`
- `Bleeding Edge - Bladed Weapons SFX Overhaul - A REINSTALL PLUS TARD`
- `Skullbreaker - Blunt Weapons SFX`
- `Bulwark - Shield Audio Overhaul`
- `Wildwood Echoes`
- `Murder of Songbirds`
- `Combat Music Fix NG Updated`
- `New Game Sound on Continue (SKSE)`
- `Still - Skyrim Inspired Music`
- `Chapter II - Jeremy Soule Inspired Music`
- `Melodies of Civilization - Skyrim Fan-Made Music`
- `Hun Lovaas - Skyrim Fan-Made combat music`
- `The Northerner Diaries - Immersive Edition (music by Jeremy Soule)`
- `The Elder Songs - Complete - A REINSTALL PLUS TARD`
- `Songs to Play Skyrim to - A Music Mod All in One`
- `The Southerner Diaries - A Soundtrack Expansion`
- `Symphonic Soundtrack - Extension HIGH QUALITY`
- `Ragnarok - Viking Battle Music`
- `BA Bard Songs`

**Mods présents mais non actifs / différés :**

- `Magic College Music - Songs for Academy - DECOCHE FORM 43`
- `Phoenix Compendium - DIFFÉRÉ`
- `Whispering Tomes of Apocrypha - DIFFÉRÉ`
- `Nyghtfall - DIFFÉRÉ`
- `Dark Era - DIFFÉRÉ`
- `Music Mods Merged SSE Edition - EXCLU POUR L’INSTANT`

**Corrections de nommage à faire dans MO2 :**

- `Audio Overhaul for Skyrim (4.1.3) - - A REINSTALL PLUS TARD`  
  → `Audio Overhaul for Skyrim (4.1.3) - A REINSTALL PLUS TARD`
- `Bleeding Edge - Bladed Weapons SFX Overhaul - - A REINSTALL PLUS TARD`  
  → `Bleeding Edge - Bladed Weapons SFX Overhaul - A REINSTALL PLUS TARD`

**Validation finale audio :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 203 validée. Module audio clos provisoirement.
