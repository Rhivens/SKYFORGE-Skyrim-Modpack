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

---

### 605. Auto Parallax

**Module :** 01 - SKSE PLUGINS & CORE UTILITIES

**Objectif :**  
Installer `Auto Parallax`, plugin SKSE de gestion automatique du parallax, en préparation du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.

**Placement :**

- `Auto Parallax` → `[01 - SKSE PLUGINS & CORE UTILITIES]`
- Position : après `SkyPatcher - SE`

**Rôle :**

- Gestion automatique du parallax.
- Préparation des futurs ajouts du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.

**Test de validation :**

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `131`

**Statut :**  
Étape 605 validée.
