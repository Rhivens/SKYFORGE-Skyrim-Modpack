# Visual base meshes & textures

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes liées au séparateur **05 - VISUAL BASE MESHES TEXTURES**.

---

### 83. Bloc SMIM / Material Fix

**Objectif :**  
Installer le socle meshes vanilla principal et son correctif material.

**Liens :**

- Static Mesh Improvement Mod - SMIM  
  https://www.nexusmods.com/skyrimspecialedition/mods/659

- Static Mesh improvement Mod - SMIM - Quality Addon  
  https://www.nexusmods.com/skyrimspecialedition/mods/44388

- Unofficial Material Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/21027

**Placement MO2 retenu :**

Dans `05 - VISUAL BASE MESHES TEXTURES` :

1. `Static Mesh Improvement Mod`
2. `Static Mesh improvement Mod - SMIM - Quality Addon`
3. `Unofficial Material Fix`

**Notes :**

- SMIM et SMIM Quality Addon sont placés dans le séparateur visuel, pas dans le bloc bug fixes.
- `Unofficial Material Fix` reste aussi dans `05 - VISUAL BASE MESHES TEXTURES`, après SMIM, afin de gagner les conflits nécessaires.
- `SMIM Quality Addon` gagne sur SMIM.
- `Unofficial Material Fix` gagne après SMIM / SMIM Quality Addon si conflit.

**Test de validation :**  
SKSE lancé via MO2, menu principal atteint, `Overwrite` vide.

**Statut :**  
Étape 83 validée.

---

### 204. Vérification du socle SMIM

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Objectif :**  
Vérifier que le socle SMIM / Material Fix déjà installé reste valide avant de poursuivre les meshes et textures.

**Bloc déjà présent et validé :**

- `Static Mesh Improvement Mod`
- `Static Mesh improvement Mod - SMIM - Quality Addon`
- `Unofficial Material Fix`

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 204 validée.

---

### 205. Assorted Mesh Fixes

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Statut :**  
Annulée / déjà couvert.

**Constat :**  
`Assorted Mesh Fixes` était déjà installé dans :

`02 - BUG FIXES & ENGINE PATCHES`

**Décision :**  
Ne pas réinstaller, ne pas déplacer.

**Statut :**  
Étape 205 annulée / déjà couvert.

---

### 206. Vérification des mesh fixes existants

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Objectif :**  
Contrôler les mesh fixes déjà présents avant installation des patches de compatibilité.

**Bloc déjà présent constaté :**

- `Blackreach Tentacle Mesh Fix`
- `Labyrinthian Shalidor's Maze Fixes`
- `Assorted Mesh Fixes`
- `Dlizzio's Mesh Fixes`
- `LOD Unloading Bug Fix`

**Statut :**  
Étape 206 validée sans changement.

---

### 207. Mesh Patch for Various Mods

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Objectif :**  
Installer les patches mesh utiles pour les mods déjà présents dans SKYFORGE.

**Fichiers installés séparément :**

- `SMIM - Quality Addon - Unofficial Material Fix Patch`
- `Unofficial Material Fix - Assorted Mesh Fixes Patch`
- `Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch`
- `SMIM - Assorted Mesh Fixes Patch`

**Décision :**  
Fichiers laissés séparés pour meilleure lisibilité MO2.

**Fichiers non pris :**

- `Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch`
- `Skyrim Particle Patch for ENB - Assorted Mesh Fixes - Solitude Mesh Fixes Patch`
- `Assorted Mesh Fixes - SMIM - Really Blended Roads Patch`
- `Assorted Mesh Fixes - SMIM - Blended Roads Patch`
- `Dlizzio's Mesh Fixes - Skyrim Landscape and Water Fixes Patch`

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 207 validée.

---

### 208. Particle Patch

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Objectif :**  
Installer Particle Patch comme base visuelle / particules compatible avec les futurs choix ENB.

**Mod installé :**

- `Particle Patch`

**Choix FOMOD validés :**

- Installation Format : `BSA`
- Plugin Name : `Particle Patch`
- Light Shafts : `Yes`
- Fake Light Glow : `Particle Light`
- Custom Textures : `Yes`

**Fichiers optionnels non pris :**

- `Glow Maps for ENB`
- `Particle Patch (No FOMOD)`
- `Remove Yellow Glow`
- `Particle Patch Magic Hand FX`
- `Remove Candle Glow`

**Test validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 208 validée.

---

### 209. Patch Particle / Unofficial Material Fix

**Module :** 05 - VISUAL BASE MESHES TEXTURES

**Statut :**  
Annulée / différée.

**Constat :**  
Aucun patch simple correspondant n’était disponible.

**Patch explicitement exclu :**

- `Skyrim Particle Patch for ENB - ELFX - Unofficial Material Fix Patch`

**Raison :**  
Dépend de la logique ELFX, non retenue actuellement pour SKYFORGE.

**Statut :**  
Étape 209 annulée / différée.

---

### 210. Contrôle final module 05 + correction audio

**Module :** 05 - VISUAL BASE MESHES TEXTURES / correction audio transversale

**Objectif :**  
Contrôler le module 05 après installation de Particle Patch et corriger un plugin audio décoché.

**Contrôle effectué :**

- `Particle Patch.esp` actif : OK
- Bloc `[05]` propre : OK

**Correction effectuée dans le panneau droit :**

`AcousticTemplateFixes_ReverbInteriorSounds.esp`

Le plugin était décoché et a été réactivé.

**Test validé après correction :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 210 validée.
