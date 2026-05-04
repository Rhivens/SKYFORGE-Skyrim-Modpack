# Audio, musiques et sons

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes classées dans le module **04 - AUDIO MUSIC SOUNDS**.

---

### 179. Base audio technique

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer la base technique permettant une distribution sonore moderne.

**Mod installé :**

- `Sound Record Distributor`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/77815

**Déjà installé ailleurs :**

- `Sound Fix for Large Sector Drives`

**Classement :**  
`Sound Fix for Large Sector Drives` reste classé dans `02 - BUG FIXES & ENGINE PATCHES`.

**Test :**  
Test reporté au pack suivant, puis validé ensuite.

**Statut :**  
Étape 179 validée.

---

### 180. Acoustic Space Improvement Fixes

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer les corrections d’espaces acoustiques via SkyPatcher.

**Mod installé :**

- `Acoustic Space Improvement Fixes - SkyPatcher`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/78992

**Choix :**

- Version `SkyPatcher 1.3.3` prise.
- Version Plugin non installée.
- Patch `Reverb Interior Sounds Expansion` décoché au premier passage, car `RISE` n’était pas encore installé.
- Mod temporairement nommé `A REINSTALL PLUS TARD`.

**Validation initiale :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 180 validée avec réinstallation prévue plus tard.

---

### 181. Préparation AOS / ISC

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Préparer le bloc Audio Overhaul / Immersive Sounds avant installation groupée.

**Mods téléchargés :**

- `Audio Overhaul for Skyrim SE`
- `Immersive Sounds - Compendium`
- `Audio Overhaul - Immersive Sounds Integration`

**Décision :**  
Aucune installation validée à cette étape seule.

**Statut :**  
Étape 181 documentée comme préparation.

---

### 182. Audio Overhaul + Immersive Sounds

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Installer le bloc audio principal autour d’Audio Overhaul et Immersive Sounds, avec intégration dédiée.

**Mods installés :**

- `Audio Overhaul for Skyrim SE - A REINSTALL PLUS TARD`
- `Immersive Sounds - Compendium - A REINSTALL PLUS TARD`
- `Audio Overhaul - Immersive Sounds Integration`
- `Audio Overhaul for Skyrim SE`

**Liens :**

- Audio Overhaul for Skyrim SE  
  https://www.nexusmods.com/skyrimspecialedition/mods/12466
- Immersive Sounds - Compendium  
  https://www.nexusmods.com/skyrimspecialedition/mods/523
- Audio Overhaul - Immersive Sounds Integration  
  https://www.nexusmods.com/skyrimspecialedition/mods/36761

**Choix FOMOD Audio Overhaul / intégration :**

- `Enhanced Blood Textures` : décoché
- `Rumble Additions` : décoché
- `True Storms` : décoché

**Raison du tag Audio Overhaul :**  
`Audio Overhaul for Skyrim SE` reste marqué `A REINSTALL PLUS TARD` si ces mods ou options sont ajoutés plus tard.

**Choix FOMOD Immersive Sounds - Compendium retenus :**

- Weapon Impact Options : `IS Default (Extra Bloody)`
- Unarmed Impact Options : `Swit Fighter Turbo`
- Weapon Draw/Sheathe Options : `IS Default (Stylized Fantasy)`
- Bow Shot Options : `High Fantasy`
- Bow Pull Options : `IS Default`
- Arrow Impact Options : `High Fantasy`
- Soul Trap Options : `Soul Suck`
- Restoration Options : `High Fantasy`
- Firebolt Options : `Swooshy`
- Nirnroot Options : `High Fantasy`

**Options Immersive Sounds laissées décochées :**

- Extra Gory Killmove Sounds
- Smooth Weapon Swings
- Silent Arrow Projectile Loop
- Demonic Draugr
- Well-Mannered Wolves
- Sensible Storm Atronachs
- Brutal Bears
- Oblivion Skillup Sound
- Dungeon Ambiance
- TESO Summoning
- Silent Weapon Enchants
- Silent Left Hand
- Silent Sneak Attack
- Silent World Map
- Silent Player Ragdoll

**Raison du tag Immersive Sounds :**  
`Immersive Sounds - Compendium` reste marqué `A REINSTALL PLUS TARD` si le profil sonore doit être ajusté après tests gameplay.

**Validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 182 validée.

---

### 183. Regional Sounds Expansion

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter des sons régionaux supplémentaires.

**Mod installé :**

- `Regional Sounds Expansion`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/77829

**Constat :**

- Pas de FOMOD.
- Fichiers `.wav` uniquement.
- Installation simple.

**Validation :**  
Test groupé avec l’étape 184.

**Statut :**  
Étape 183 validée avec l’étape 184.

---

### 184. Reverb Interior Sounds Expansion

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Ajouter l’expansion des réverbérations intérieures.

**Mod installé :**

- `Reverb Interior Sounds Expansion`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/77947

**Choix FOMOD :**

- `Reverb, Ambience, Output Models` : coché obligatoire
- `Rain` : coché
- `Thunder` : coché
- `Wind` : coché obligatoire

**Validation groupée avec Regional Sounds Expansion :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 184 validée.

---

### 185. Patch ASIF pour RISE

**Module :** 04 - AUDIO MUSIC SOUNDS

**Objectif :**  
Réinstaller `Acoustic Space Improvement Fixes - SkyPatcher` après installation de `Reverb Interior Sounds Expansion`, afin d’activer le patch correspondant.

**Action effectuée :**  
Réinstallation de :

`Acoustic Space Improvement Fixes - SkyPatcher`

**Choix FOMOD modifié :**

- `Reverb Interior Sounds Expansion` : coché

**Annotation supprimée :**  
`A REINSTALL PLUS TARD`

**Validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 185 validée.

---

## État actuel recommandé du bloc 04

Dans `[04 - AUDIO MUSIC SOUNDS]` :

1. `Sound Record Distributor`
2. `Acoustic Space Improvement Fixes - SkyPatcher`
3. `Audio Overhaul for Skyrim SE - A REINSTALL PLUS TARD`
4. `Immersive Sounds - Compendium - A REINSTALL PLUS TARD`
5. `Audio Overhaul - Immersive Sounds Integration`
6. `Regional Sounds Expansion`
7. `Reverb Interior Sounds Expansion`

---

## Notes audio à retenir

- `AOS` et `ISC` restent marqués `A REINSTALL PLUS TARD` pour choix FOMOD conditionnels ou subjectifs.
- `ASIF` a été réinstallé avec le patch `RISE` activé.
- LOOT n’a pas été lancé.
