# Module 11.1 — Followers, NPCs & dialogues — partie 3

Ce fichier documente les étapes **527 à 530** du projet SKYFORGE.

## Statut du bloc

- **Bloc :** `[11.1 - FOLLOWERS NPCS DIALOGUES]`
- **Statut :** rouvert ponctuellement après la série custom followers 510 à 526
- **Compteur final documenté :** 128 ESP + ESM non-light
- **Overwrite :** vide sur les tests documentés
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé ; Output existant conservé depuis l'étape 411
- **Mods `- FR` :** non activés

## Méthode

- Les ajouts restent des dialogues, réactions ou comportements légers liés aux NPC/followers.
- Les variantes ou patches générant des risques de répétition, dépendances absentes ou systèmes spécialisés restent différés.
- Les suffixes MO2 de suivi temporaire sont régis par `docs/procedure/01_regles_mo2_skyforge.md`.

---

# Étape 527 — Considerate Followers pour Skyrim 1.5.97

## Statut

Validée.

## Mods installés

- `Considerate Followers - Followers are Silent During Dialogue`
- `Considerate Followers for Skyrim 1.5`

## Référence

Nefaram.

## Décision

Conserver.

Le mod principal est installé avec son port/patch dédié Skyrim 1.5.97, cohérent avec la base SKYFORGE SE 1.5.97 Best of Both Worlds.

## Placement

Installé dans `[11.1 - FOLLOWERS NPCS DIALOGUES]`, car il s'agit d'un comportement global de dialogue followers/NPCs, et non d'un addon lié à un custom follower précis.

## Mods non installés / différés

- `Considerate Followers NG`
- `FECKOFF`
- autres variantes / ports

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

# Étape 528 — Mini-pack dialogues NPC/followers neutres

## Statut

Validée.

## Mods installés

- `Chatty NPCs`
- `Collision Dialogue Overhaul - NSFW Adult Version`
- `Shouts of Stallholders`

## Référence

Nefaram.

## Décisions

### Chatty NPCs

- Main file installé.
- `Chatty NPCs Follower Patch` non installé.

### Collision Dialogue Overhaul

- Version retenue par Fabien : `NSFW Adult Version`.
- La version SFW initialement envisagée n'est pas retenue.

### Shouts of Stallholders

- Mod installé.

## Mod différé

- `Additional Healing Reactions` — finalement identifié comme déjà présent à l'étape 529.

## Options non installées / différées

- `Chatty NPCs Follower Patch - DIFFERE RISQUE REPETITION`
- `Collision Dialogue Overhaul - Settings Loader`
- `Collision Dialogue Overhaul - SFW Version`
- traductions `- FR`
- autres fichiers du pack JaySerpa 97490

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

# Étape 529 — Additional Healing Reactions

## Statut

Validée comme déjà installé.

## Mod concerné

- `Additional Healing Reactions`

## Référence

Nefaram.

## Décision

Conserver.

Le snapshot fourni montre déjà le mod actif dans le bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]`, entre `Collision Dialogue Overhaul` et `Shouts of Stallholders`.

## Extrait de placement constaté

```txt
Considerate Followers - Followers are Silent During Dialogue
Considerate Followers for Skyrim 1.5
Chatty NPCs and Followers
Collision Dialogue Overhaul
Additional Healing Reactions
Shouts of Stallholders
SPID NPC Trap Safety
```

## Action retenue

- Aucun ajout nécessaire.
- Ne pas réinstaller.
- Ne pas dupliquer.

## Compteur

128 ESP + ESM non-light.

---

# Étape 530 — Mini-pack dialogues NPC/followers Nefaram

## Statut

Validée.

## Mods installés

- `Falmer Servant Lines Expansion`
- `Missing Voices in Hearthfire Added Back`
- `Cheeky Kids`

## Référence

Nefaram.

## Objectif

Compléter le bloc dialogues NPC/followers avec un petit pack de réactions et lignes vocales neutres, sans nouveau follower, sans framework, sans animation, sans système spécialisé et sans relancer Pandora.

## Choix retenus

### Falmer Servant Lines Expansion

- Main file installé.
- Objectif : ajouter des lignes vocales dédiées aux serviteurs Falmer.

### Missing Voices in Hearthfire Added Back

- Mod installé.
- Objectif : restaurer / ajouter des voice types Hearthfire manquants.

### Cheeky Kids

- Mod installé.
- Objectif : ajouter des interactions / scènes légères impliquant les enfants.

## Options non installées / différées

- `FSLE - Unique Abilities`
- `FSLE - More Locations`
- `Stormcloaks Fight With Thalmor`
- `Fight Against Ysgramor - Voice Acted`
- `The Cost of a Mistake - Increased Guild Fines`
- `Spouse Wears Wedding Dress`

## Raison du différé

Les options FSLE non retenues modifient davantage les capacités ou les placements.  
Les autres mods touchent à des événements, factions, économie ou mariage, et seront plus adaptés à une passe roleplay dédiée.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

## État final après étape 530

- Le bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` est renforcé avec plusieurs ajouts de dialogues / réactions issus de la logique Nefaram.
- `Additional Healing Reactions` est documenté comme déjà présent, sans doublon.
- Les options ou variants risquant répétition, dépendances absentes ou changements roleplay plus larges restent différés.
- Compteur final : 128 ESP + ESM non-light.
- Prochaine étape attendue : 531.
