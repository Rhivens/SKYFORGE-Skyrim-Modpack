# SKYFORGE — Procédure — 05.2 - PARALLAX FRAMEWORK TEXTURES — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture et clôture provisoire du sous-bloc **05.2 - PARALLAX FRAMEWORK TEXTURES**.

Périmètre : étapes **604 à 606**.

---

## Étape 604 — Ouverture du bloc 05.2 Parallax Framework Textures

### Bloc

`[05.2 - PARALLAX FRAMEWORK TEXTURES]`

### Mod ajouté

- **Dlizzio's Mesh Fixes - Parallax Mesh Patch**

### Non installés

- **Assorted Mesh Fixes main file**
  - Raison : déjà installé dans `[02 - BUG FIXES & ENGINE PATCHES]`.
- **Assorted Mesh Fixes - parallax shit (unsupported)**
  - Raison : fichier explicitement unsupported.
  - À revoir plus tard seulement si la pile snow/parallax/landscape/ENB le justifie.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `131`

Étape 604 validée.

---

## Étape 605 — Auto Parallax

### Bloc

`[01 - SKSE PLUGINS & CORE UTILITIES]`

### Mod ajouté

- **Auto Parallax**

### Placement

- Placé dans `[01 - SKSE PLUGINS & CORE UTILITIES]`.
- Position : après `SkyPatcher - SE`.

### Rôle

- Plugin SKSE de gestion automatique du parallax.
- Prépare les futurs ajouts du bloc `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.

### Résultat

- SKSE/menu principal : OK
- Masters manquants : aucun
- Messages DLL : aucun
- Plugins cochés : tous
- Overwrite : vide
- Compteur ESP + ESM non-light : `131`

Étape 605 validée.

---

## Étape 606 — Clôture provisoire du bloc 05.2

### Bloc clôturé

`[05.2 - PARALLAX FRAMEWORK TEXTURES]`

### Contenu validé

- **Dlizzio's Mesh Fixes - Parallax Mesh Patch**

### Vérification

- **Auto Parallax** confirmé dans `[01 - SKSE PLUGINS & CORE UTILITIES]`, après `SkyPatcher - SE`.
- Aucun nouveau mod installé.
- Aucun changement depuis le dernier test propre.

### Non installés / différés

- `Assorted Mesh Fixes - parallax shit (unsupported)`
- `Noble Skyrim`
- `Skyrim 202X`
- `SRP Architecture`
- `The Omnibus`
- `HD Remastered Landscapes`
- `Tomato's Complex Landscapes`
- `Skyrim 202X Complex Terrain Parallax`

### Décision

- Bloc 05.2 clôturé provisoirement.
- Aucun LOOT lancé.
- Aucun DynDOLOD / BodySlide / Pandora lancé.

Étape 606 validée.

---

## État final post-606

- Sous-bloc clôturé provisoirement : `[05.2 - PARALLAX FRAMEWORK TEXTURES]`.
- Contenu validé : `Dlizzio's Mesh Fixes - Parallax Mesh Patch`.
- `Auto Parallax` classé dans `[01 - SKSE PLUGINS & CORE UTILITIES]`.
- Compteur ESP + ESM non-light : **131**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé**.
