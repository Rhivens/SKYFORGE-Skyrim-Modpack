# Visual base meshes & textures

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes liées au séparateur **05 - VISUAL BASE MESHES TEXTURES**. À ce stade, l’étape **83** y est classée.

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
