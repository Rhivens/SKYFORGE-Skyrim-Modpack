# Module 11.1 — Followers, NPCs & dialogues — partie 2

Ce fichier documente les étapes 481 à 490 du projet SKYFORGE.

## Statut du bloc

- **Bloc :** `[11.1 - FOLLOWERS NPCS DIALOGUES]`
- **Statut :** clôturé provisoirement après l'étape 490, avant ouverture du bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`
- **Compteur final documenté :** 119 ESP + ESM non-light
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé
- **Mods `- FR` :** non activés

## Méthode

- Les packs Follower Dialogue Expansion ont été ajoutés par groupes prudents, avec test SKSE / menu après chaque groupe.
- Les plugins FDE ajoutés dans ce bloc sont considérés comme ESL-flagged / ESPFE ou non comptabilisés comme non-light, car le compteur reste stable à 119 jusqu'à l'étape 490.
- Les patches dépendants de followers non encore installés ont été différés, puis repris dans le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` lorsque leurs masters sont devenus disponibles.
- Les suffixes MO2 de suivi temporaire doivent être nettoyés selon `docs/procedure/01_regles_mo2_skyforge.md`.

---

# Étape 481 — Follower Dialogue Expansion - Olfina Gray-Mane

## Statut

Validée.

## Mod installé

- `Follower Dialogue Expansion - Olfina Gray-Mane`

## Source

- Proposition spécifique SKYFORGE

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Plugin

- `FDE Olfina.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light inchangé : 119.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 482 — Pack dialogues Whiterun / Guerre civile léger

## Statut

Validée.

## Mods installés

- `REBEL NORTH - Immersive Dialogue Expansion - Stormcloaks`
- `Follower Dialogue Expansion - Uthgerd the Unbroken`
- `Follower Dialogue Expansion - Ysolda`

## Sources

- `REBEL NORTH - Immersive Dialogue Expansion - Stormcloaks` : remplacement spécifique SKYFORGE d'un candidat historiquement issu de Nolvus Awakening, l'ancienne page étant cachée / obsolète.
- `Follower Dialogue Expansion - Uthgerd the Unbroken` : proposition spécifique SKYFORGE.
- `Follower Dialogue Expansion - Ysolda` : proposition spécifique SKYFORGE.

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 483 — Pack FDE followers vanilla léger/moyen

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Jordis the Sword-Maiden`
- `Follower Dialogue Expansion - Camilla Valerius`
- `Follower Dialogue Expansion - Illia - PATCHES A VOIR PLUS TARD`

## Source

- Proposition spécifique SKYFORGE

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Patches différés

- `Riverside Lodge patch` pour Jordis : différé, car `Riverside Lodge` n'est pas installé.
- `FDE Illia Inigo patch` : différé, car `Inigo` n'est pas encore installé.

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 484 — Pack FDE followers vanilla safe — Lydia / Mjoll / Brelyna

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Lydia`
- `Follower Dialogue Expansion - Mjoll the Lioness - PATCHES A VOIR PLUS TARD`
- `Follower Dialogue Expansion - Brelyna Maryon - PATCHES A VOIR PLUS TARD`

## Source

- Proposition spécifique SKYFORGE

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Patches différés

- patch Remiel pour Lydia / Mjoll selon disponibilité future ;
- `FDE Mjoll Auri patch` ;
- `FDE Brelyna Lucien patch` ;
- `FDE Brelyna Inigo patch` ;
- `FDE Brelyna Auri Patch`.

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 485 — Pack FDE vanilla Riverwood / Rorikstead / Kynesgrove

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Erik the Slayer`
- `Follower Dialogue Expansion - Faendal`
- `Follower Dialogue Expansion - Roggi Knot-Beard`

## Source

- Proposition spécifique SKYFORGE

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 486 — Pack FDE Riften / Thieves Guild / Hearthfire

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Marcurio`
- `Follower Dialogue Expansion - Sapphire`
- `Follower Dialogue Expansion - Rayya`

## Sources

- `Follower Dialogue Expansion - Marcurio` : proposition spécifique SKYFORGE, sauf vérification contraire ultérieure.
- `Follower Dialogue Expansion - Sapphire` : source Nefaram.
- `Follower Dialogue Expansion - Rayya` : source Nefaram.

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 487 — Pack FDE Nefaram Orc / Azura / Collège

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Borgakh the Steel Heart`
- `Follower Dialogue Expansion - Aranea Ienith`
- `Follower Dialogue Expansion - Faralda`

## Source

- Source Nefaram

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

## Note de méthode

Pour les futures étapes, indiquer clairement si un mod vient de Nolvus Awakening, Nefaram, des deux, ou d'une proposition spécifique SKYFORGE.

---

# Étape 488 — Pack FDE Nefaram Jenassa / Eola

## Statut

Validée.

## Mods installés

- `Follower Dialogue Expansion - Jenassa - PATCHES A VOIR PLUS TARD`
- `Follower Dialogue Expansion - Eola`

## Source

- Source Nefaram

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Patches différés

- Patches Jenassa dépendants d'Inigo, Auri ou autres followers non encore installés à cette étape.

## Test

Plugins visibles et cochés, menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 489 — FDE Aela seule, avec patches différés

## Statut

Validée.

## Mod installé

- `Follower Dialogue Expansion - Aela the Huntress - PATCHES A VOIR PLUS TARD`

## Source

- Source Nefaram

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Plugin

- `FDE Aela.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light inchangé : 119.

## Patches différés

- `FDE Aela Auri patch`
- `FDE Aela Inigo patch`
- `FDE Aela Lucien patch`
- `FDE Aela Remiel patch`
- `FDE Aela Xelzaz patch`
- éventuel patch Thogra

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

Compteur : 119.

## Décision

Conserver.

---

# Étape 490 — RDO - FDE Compatibility Patch

## Statut

Validée.

## Mods installés / activés

- `Relationship Dialogue Overhaul - Update and MCM`
- `RDO - FDE Compatibility Patch`

## Source

- Complément de la route RDO / FDE dans le bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]`.

## Emplacement MO2

- `[11.1 - FOLLOWERS NPCS DIALOGUES]`

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, plugins visibles/cochés, Overwrite vide.

Compteur : 119.

## Décision

Conserver la route RDO + FDE Compatibility Patch validée à l'étape 490.

## Note de transition

Le bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` est clôturé provisoirement après cette étape. Le bloc suivant `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` peut être ouvert.
