# Module 11.2 — Custom followers & companions — partie 1

Ce fichier documente les étapes 491 à 509 du projet SKYFORGE.

## Statut du bloc

- **Bloc :** `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`
- **Statut :** en cours après étape 509
- **Compteur final documenté :** 128 ESP + ESM non-light
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé
- **Mods `- FR` :** non activés

## Méthode

- Les custom followers sont installés un par un ou par petits groupes de patches ciblés.
- Les followers disposant de leur propre système de suivi / IA ne doivent pas être importés automatiquement dans NFF ou dans un follower framework équivalent.
- Les patches dépendants de quêtes, lieux, DBVO, systèmes spécialisés, traductions `- FR` ou masters absents restent différés.
- Les suffixes MO2 de suivi temporaire sont à nettoyer selon `docs/procedure/01_regles_mo2_skyforge.md`.

---

# Étape 491 — Ouverture du bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Statut

Validée définitivement.

## Action effectuée

Création du séparateur MO2 :

```txt
[11.2 - CUSTOM FOLLOWERS COMPANIONS]
```

## Décision

Le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` est désormais le bloc courant pour les custom followers et leurs patches directs.

---

# Étape 492 — INIGO seul, sans patches différés

## Statut

Validée.

## Mod installé

- `INIGO`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

- `Inigo.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light : 119 → 120.

## Règle de gestion follower

Inigo ne doit pas être importé / géré dans NFF ou un follower framework équivalent.

## Patches différés

- `Inigo - Cleaned Esp`
- `Inigo - Map Marker Quests`
- `Inigo - Immersive Start`
- `Inigo - Artifact Immersion Patch`
- `Inigo - At Your Own Pace Patch`
- `Inigo - Bloodchill Manor Patch`
- `Inigo - BloodChill Manor Patch - Navmesh Fix`
- `Snazzy Items for Inigo`
- patches FDE Inigo
- patches DBVO
- traduction `- FR`

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 493 — Patches FDE ↔ Inigo

## Statut

Validée.

## Patches installés

- `FDE Illia Inigo patch`
- `FDE Brelyna Inigo patch`
- `FDE Jenassa Inigo patch`
- `FDE Aela Inigo Patch`

## Source

- Patches FDE dans le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`, maintenant que `Inigo.esp` est disponible.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, patches visibles/cochés, Overwrite vide.

Compteur : 120.

## Décision

Conserver.

---

# Étape 494 — Lucien seul, sans patches

## Statut

Validée.

## Mod installé

- `Lucien - Immersive Fully Voiced Male Follower`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

- `Lucien.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light : 120 → 121.

## Règle de gestion follower

Lucien ne doit pas être importé / géré dans NFF ou un follower framework équivalent.

## Patches différés

- patches Creation Club / Bruma / Moonpath / Dumzbthar / Dwemer Ruin Redux ;
- patches d'immersion et distribution ;
- `FDE Brelyna Lucien patch` ;
- `FDE Aela Lucien patch`.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 495 — Patches FDE ↔ Lucien

## Statut

Validée.

## Patches installés

- `FDE Brelyna Lucien patch`
- `FDE Aela Lucien patch`

## Source

- Patches FDE dans le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`, maintenant que `Lucien.esp` est disponible.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, patches visibles/cochés, Overwrite vide.

Compteur : 121.

## Décision

Conserver.

---

# Étape 496 — Auri seule, sans patches

## Statut

Validée.

## Mod installé

- `Song of the Green (Auri Follower)`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

- `018Auri.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light : 121 → 122.

## Règle de gestion follower

Auri ne doit pas être importée / gérée dans NFF ou un follower framework équivalent.

## Patches différés

- `Auri - Inigo Banter Patch`
- `Auri - 3DNPC Banter Patch`
- `Auri - Vigilant Commentary`
- patches FDE Mjoll / Brelyna / Jenassa / Aela
- patches Cities of the North / Snazzy Items

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 497 — Patches FDE ↔ Auri

## Statut

Validée.

## Patches installés

- `FDE Mjoll Auri patch`
- `FDE Brelyna Auri Patch`
- `FDE Jenassa Auri patch`
- `FDE Aela Auri patch`

## Source

- Patches FDE dans le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`, maintenant que `018Auri.esp` est disponible.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, patches visibles/cochés, Overwrite vide.

Compteur : 122.

## Décision

Conserver.

---

# Étape 498 — Remiel seule, avec correctifs génériques

## Statut

Validée.

## Mods installés

- `Remiel - Custom Voiced Dwemer Specialist and Companion - FOMOD A REVOIR PLUS TARD`
- `Remiel - Missing Voice Lines`
- `Remiel - 1.7.6 HotFix`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

- `HLIORemi.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light : 122 → 123.

## Options / patches différés

Les options FOMOD liées à des quêtes, mods absents, Vanilla Assets, options visuelles ou addons spécifiques restent différées selon la convention des suffixes de suivi temporaires.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 499 — Patches FDE ↔ Remiel

## Statut

Validée.

## Patches installés

- `FDE Mjoll Remiel patch`
- `FDE Aela Remiel patch`

## Source

- Patches FDE dans le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`, maintenant que `HLIORemi.esp` est disponible.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, patches visibles/cochés, Overwrite vide.

Compteur : 123.

## Décision

Conserver.

---

# Étape 500 — Xelzaz seul, sans patches

## Statut

Validée.

## Mod installé

- `Xelzaz - Custom Fully Voiced Argonian Telvanni Follower - PATCHES A VOIR PLUS TARD`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

- `Xelzaz.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light : 123 → 124.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 501 — Patches Xelzaz partiels : AE + FDE Aela

## Statut

Validée.

## Patches installés / conservés

- `Xelzaz Anniversary Edition Plugin`
- `FDE Aela Xelzaz patch`

## Source

- Patches directs du bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`.

## Plugins

- `FDE Aela Xelzaz.esp` visible et coché.
- Compteur ESP + ESM non-light : 124 → 125.

## Patches décochés / différés

- patches Wyrmstooth / Sirenroot / autres masters absents ;
- autres patches dépendants de contenus non encore validés.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver les deux patches validés et maintenir les autres patches différés.

---

# Étape 502 — Thogra seule, sans patches

## Statut

Validée.

## Mod installé

- `Thogra gra-Mugur - Orc Follower and Quest - PATCHES A VOIR PLUS TARD`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

Plugin visible et coché.

Compteur ESP + ESM non-light : 125 → 126.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 503 — Patch Remiel ↔ Thogra

## Statut

Validée.

## Patch installé

- `Remiel / Thogra banter patch`

## Source

- Patch direct du bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`.

## Plugin

- `dkma_RemiThograBanter.esp`
- Plugin visible et coché.
- Compteur ESP + ESM non-light inchangé : 126.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 504 — Gore seul, FOMOD partiel

## Statut

Validée.

## Mod installé

- `Gore - A Companion Mod - FOMOD & PATCHES A REVOIR PLUS TARD`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

Plugin visible et coché.

Compteur ESP + ESM non-light : 126 → 127.

## Options / patches différés

Options et patches liés à des contenus absents ou à réauditer restent différés, notamment `Gore - Vigilant` et `Press E to heal Gore`.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver.

---

# Étape 505 — Kaidan 2 seul, sans Extended ni patches

## Statut

Validée.

## Mod installé

- `Kaidan 2 - PATCHES A VOIR PLUS TARD`

## Source

- Source Nolvus Awakening + Nefaram

## Emplacement MO2

- `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`

## Plugin

Plugin visible et coché.

Compteur ESP + ESM non-light : 127 → 128.

## Patches / addons différés

- `Kaidan 2 Extended Edition ADDON`
- `Immersive Kaidan Start`
- autres patches dépendants de contenus, systèmes ou choix futurs.

## Test

Menu principal OK, aucun message DLL bloquant, aucun master manquant, Overwrite vide.

## Décision

Conserver Kaidan 2 seul, sans Extended ni patches pour l'instant.

---

# Étape 506 — Décision Kaidan : branche compatible SexLab

## Statut

Décision validée.

## Mod concerné

- `Kaidan 2 - PATCHES A VOIR PLUS TARD`

## Décision SKYFORGE

Conserver pour l'instant une branche Kaidan sobre et compatible avec les futurs modules spécialisés, sans installer immédiatement les extensions ou patches non indispensables.

## Note de prudence

Les addons et patches Kaidan touchant aux interactions spécialisées, quêtes, dialogues avancés, DBVO ou frameworks sensibles restent différés jusqu'à audit dédié.

---

# Étape 507 — Katana - Journey in the Shadows

## Statut

Exclu définitivement.

## Mod concerné

- `Katana - Journey in the Shadows`

## Source

- Source Nefaram pour le candidat historique.

## Décision Fabien

Ne pas installer Katana.

## Raison

Mod jugé trop risqué / incertain pour SKYFORGE à ce stade : custom follower framework, contenu hybride follower + quête, risques de conflits et stabilité insuffisamment fiable pour l'intégration.

## Installation

Aucun fichier installé.

## Test

Aucun test SKSE requis.

## Décision

Exclure Katana du modpack SKYFORGE.

---

# Étape 508 — Daegon Legacy

## Statut

Exclu définitivement.

## Mod concerné

- `Daegon Legacy`

## Source

- Source Nefaram pour le candidat historique.

## Décision Fabien

Ne pas installer Daegon Legacy.

## Raison

Mod jugé trop risqué / incertain pour SKYFORGE à ce stade : contenu hybride follower + quête, dépendances et compatibilités trop lourdes, stabilité insuffisamment fiable pour l'intégration.

## Installation

Aucun fichier installé.

## Test

Aucun test SKSE requis.

## Décision

Exclure Daegon Legacy du modpack SKYFORGE.

---

# Étape 509 — Mythos SE Redux

## Statut

Exclu définitivement.

## Mod concerné

- `Mythos SE Redux`

## Source

- Source Nefaram pour le candidat historique.
- Source externe disponible : reupload RPGHQ.

## Décision Fabien

Ne pas installer Mythos SE Redux.

## Raison

Le mod présente trop d'incertitudes pour SKYFORGE : source hors Nexus / reupload, maintenance et permissions non vérifiées, custom follower framework, contenu hybride follower + quêtes, risques de conflits avec lieux et overhauls, stabilité insuffisamment fiable pour l'intégration.

## Installation

Aucun fichier installé.

## Test

Aucun test SKSE requis.

## Décision

Exclure définitivement Mythos SE Redux du modpack SKYFORGE.

## Note pour la suite

Ne plus proposer les custom followers exclus à ce stade :

- `Katana - Journey in the Shadows`
- `Daegon Legacy`
- `Mythos SE Redux`
