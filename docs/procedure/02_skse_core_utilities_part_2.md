# SKSE, dépendances et core utilities — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes postérieures à l’étape 101 classées dans le module **01 - SKSE PLUGINS & CORE UTILITIES**.

---

### 113. SKSE Menu Framework + Execute Hotkeys

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer `SKSE Menu Framework` et l’addon `Execute Hotkeys`.

**Liens :**

- SKSE Menu Framework  
  https://www.nexusmods.com/skyrimspecialedition/mods/120352
- Execute Hotkeys - Without Keyboard Through UI - SKSE Menu Framework  
  https://www.nexusmods.com/skyrimspecialedition/mods/170318

**Choix retenu :**

- `Execute Hotkeys 1.3.0` : main file uniquement
- Traduction optionnelle anglaise : non installée

**Placement :**  
Dans `01 - SKSE PLUGINS & CORE UTILITIES`.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 113 validée.

---

### 123. Container Item Distributor / Andrealphus' Papyrus Functions

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer les frameworks SKSE utiles au futur setup.

**Liens :**

- Container Item Distributor  
  https://www.nexusmods.com/skyrimspecialedition/mods/99486
- Andrealphus' Papyrus Functions  
  https://www.nexusmods.com/skyrimspecialedition/mods/85252

**Placement :**

- `Container Item Distributor` → `01 - SKSE PLUGINS & CORE UTILITIES`
- `Andrealphus' Papyrus Functions` → `01 - SKSE PLUGINS & CORE UTILITIES`

**Note :**  
`Mum's the Word NG`, validé dans la même étape globale, est classé dans le fichier Bug Fixes & Engine Patches partie 3.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 123 validée.

---

### 125. MergeMapper

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer `MergeMapper`, dépendance SKSE utile pour certains mods utilisant des plugins fusionnés ou remappés.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/74689

**Résultat :**  
`MergeMapper` installé et validé.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 125 validée.

---

### 126. Perk Entry Point Extender

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer une dépendance SKSE / modder resource pour les perk entry points.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/91192

**Version installée :**  
`2.2.4.6`

**Décision :**  
La version expérimentale `2.3.4.0` n’a pas été installée.

**Raison :**  
La version `2.3.4.0` ajoute des dépendances souples et de nouvelles fonctions expérimentales. La version `2.2.4.6` est retenue comme version stable prudente.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 126 validée.

---

### 127. Dynamic String Distributor

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer le framework requis par certaines futures traductions FR dynamiques.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/107676

**Résultat :**  
`Dynamic String Distributor` installé dans `01 - SKSE PLUGINS & CORE UTILITIES`.

**Décisions associées :**

- `Dynamic Dialogue Replacer` : différé
- `Skyrim Autocorrect - Dialogue Grammar Fixes` : différé

**Note :**  
Les traductions FR utilisant DSD seront placées plus tard dans `18 - TRADUCTIONS FR`, tandis que DSD reste dans les core utilities.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 127 validée.

---

### 129. KiLoader for Skyrim

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer `KiLoader`, framework technique requis par certains composants Ki / ENB.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/99404

**Résultat :**

- `KiLoader for Skyrim` installé
- Des dossiers vides ont été générés dans `Overwrite`
- Un mod dédié a été créé : `KiLoader - Generated Empty Folders`
- Ce mod est placé sous `KiLoader for Skyrim`
- `Overwrite` est redevenu vide

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` nettoyé et vide.

**Statut :**  
Étape 129 validée.

---

### 133. Bloc SKSE confort — Media Keys Fix SKSE + DPI Scaling Fix

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer deux petits utilitaires de confort côté SKSE / affichage.

**Liens :**

- Media Keys Fix SKSE  
  https://www.nexusmods.com/skyrimspecialedition/mods/92948
- DPI Scaling Fix  
  https://www.nexusmods.com/skyrimspecialedition/mods/95740

**Mods installés :**

- `Media Keys Fix SKSE`
- `DPI Scaling Fix`

**Placement :**

- `Media Keys Fix SKSE` → `01 - SKSE PLUGINS & CORE UTILITIES`
- `DPI Scaling Fix` → `01 - SKSE PLUGINS & CORE UTILITIES`

**Note :**  
`Persistent Favorites`, validé dans la même étape globale, est classé dans le fichier Bug Fixes & Engine Patches partie 3.

**Test de validation :**  
SKSE via MO2, menu principal atteint, aucun message DLL, aucun master manquant, `Overwrite` vide.

**Statut :**  
Étape 133 validée.

---

### 135. dTry’s Key Utils

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Résultat :**  
Étape sautée car le mod était déjà installé :

- `dTry's Key Utils SE`

**Statut :**  
Étape 135 sautée — déjà installé.

---

### 137. Face Discoloration Fix

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Résultat :**  
Étape sautée car le mod était déjà installé :

- `Face Discoloration Fix SE (1.5.97)`

**Statut :**  
Étape 137 sautée — déjà installé.
