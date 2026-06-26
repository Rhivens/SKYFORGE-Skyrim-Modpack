# Followers, NPCs & dialogues — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Validation provisoire du module **11 - FOLLOWERS / NPCS / DIALOGUES**.

Périmètre : étapes **669 à 672**.

Important : ces étapes sont des validations courtes sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 669 — Dialogue / NPC reactions / lines expansions

### Pack concerné

Passage du bloc `[10.1 - RACES WEREBEASTS VAMPIRES]` vers `[11.1 - FOLLOWERS NPCS DIALOGUES]`.

Le snapshot montre le groupe dialogues / réactions NPC avec notamment :

- Bandit Lines Expansion
- Civil War Lines Expansion
- Forsworn and Thalmor Lines Expansion
- Vampire Lines Expansion
- Brawl Lines Expansion and Fixes
- Dremora Lines Expansion
- NPCs React To Necromancy
- NPCs React To Invisibility
- Bow of Shadows - Invisibility Patch
- NPCs React To Frenzy
- Carriages and Stables Dialogue Bundle
- Show NPC Disposition Relationship Rank
- Dialogue Window Auto Close Exit Begone
- Scared of Shootings
- Dialogue Expansion - Windhelm
- Dialogue Expansion - Shor’s Stone
- Dialogue Expansion - Khajiit Caravans
- Neutral Whiterun Guards
- Truly Neutral Prisoners
- More Sensible Quartermasters
- Guard Dialogue Overhaul
- Misc Dialogue Edits
- More Dialogue Options
- Relationship Dialogue Overhaul
- Cutting Room Floor
- AI Overhaul
- Run For Your Lives
- Realistic Conversations

### Plugins actifs relevés

- `Vampire Lines Expansion.esp`
- `Bandit Lines Expansion.esp`
- `Civil War Lines Expansion.esp`
- `Forsworn and Thalmor Lines Expansion.esp`
- `Brawl Lines Expansion.esp`
- `NPCs React To Necromancy.esp`
- `NPCs React To Invisibility.esp`
- `NPCs React To Invisibility - Bow of Shadows Patch.esp`
- `NPCsReactToFrenzy.esp`
- `CarriageAndStableDialogues.esp`
- `Dialogue window doesnt close on its own.esp`
- `Scared of Shootings.esp`
- `Show Dialog Disposition.esp`
- `WindhelmDialogueExpansion.esp`
- `Shor's Stone Dialogue Expansion.esp`
- `CaravansDialogueExpansion.esp`
- `Neutral Whiterun Guards.esp`
- `TrulyNeutralPrisoners.esp`
- `More Sensible Quartermasters.esp`
- `Robber's Gorge Fixes.esp`
- `Guard Dialogue Overhaul.esp`
- `GDO_MCM.esp`
- `More Dialogue Options.esp`
- `Misc Dialogue Edits.esp`
- `Relationship Dialogue Overhaul.esp`
- `cutting room floor.esp`
- `RDO - CRF + USSEP Patch.esp`
- `RDO - USSEP Patch.esp`
- `AI Overhaul.esp`
- `AI Overhaul - Relationship Dialogue Overhaul Patch.esp`
- `AI Overhaul - Cutting Room Floor Patch.esp`
- `run for your lives.esp`
- `Realistic-Voice.esp`

### Décision

- Garder / validation provisoire.
- Pack cohérent avec l’objectif SKYFORGE : enrichir les dialogues, ajouter des réactions NPC, améliorer gardes / prisonniers / caravanes, conserver RDO / GDO / AI Overhaul comme base sociale.
- Prépare les Follower Dialogue Expansion et followers custom qui suivent.

### Ne pas faire maintenant

- Ne pas réinstaller RDO.
- Ne pas refaire les FOMOD de Misc Dialogue Edits / More Dialogue Options.
- Ne pas réinstaller AI Overhaul.
- Ne pas ajouter More to Say maintenant.
- Ne pas tester en jeu les dialogues maintenant.
- Ne pas lancer LOOT.

### Dettes utiles

- `Robber's Gorge Fixes - FOMOD À REVOIR PLUS TARD`.
- `Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD`.
- `More Dialogue Options - FOMOD À REVOIR PLUS TARD`.
- `Cutting Room Floor - FOMOD À REVOIR PLUS TARD`.
- `AI Overhaul SSE - FOMOD À REVOIR PLUS TARD`.
- `More to Say - FOMOD A REVOIR PLUS TARD`.
- Vérifier plus tard RDO / CRF / AI Overhaul / GDO ensemble.
- Vérifier plus tard les conflits avec followers custom et FDE.

---

## Étape 670 — Follower Dialogue Expansion / compagnons vanilla

### Pack concerné

Pile Follower Dialogue Expansion pour compagnons vanilla, notamment :

- FDE Olfina
- FDE Uthgerd
- FDE Ysolda
- FDE Jordis
- FDE Camilla
- FDE Illia
- FDE Lydia
- FDE Mjoll
- FDE Brelyna
- FDE Erik
- FDE Faendal
- FDE Roggi
- FDE Marcurio
- FDE Sapphire
- FDE Rayya
- FDE Borgakh
- FDE Aranea
- FDE Faralda
- FDE Jenassa
- FDE Eola
- FDE Aela
- RDO - FDE Compatibility Patch

### Décision

- Garder / validation provisoire.
- Pack logique après RDO, GDO, AI Overhaul, Misc Dialogue Edits, More Dialogue Options, Relationship Dialogue Overhaul et les expansions de lignes NPC.

### Points de vigilance

- Compatibilité FDE avec RDO.
- Compatibilité FDE avec AI Overhaul.
- Compatibilité FDE avec les followers custom qui suivent.
- Patches Inigo / Lucien / Auri / Remiel / Xelzaz présents plus loin à traiter dans le prochain pack.
- Ne pas régler les dialogues ou MCM maintenant.

---

## Étape 671 — Followers custom et patches FDE

### Pack concerné

Le sous-bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` contient notamment :

- INIGO
- Lucien
- Song of the Green / Auri
- Remiel
- Xelzaz
- Thogra
- Gore
- Serana Dialogue Add-On
- Serana Re-Imagined
- Menagerie
- Show Follower Carry Weight / Show Mount Carry Weight
- patches FDE pour Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra
- patches SDA / NFF / RDO / Remiel / Umbra

### Plugins actifs relevés

- `Inigo.esp`
- `Lucien.esp`
- `018Auri.esp`
- `HLIORemi.esp`
- `BPUFXelzazFollower.esp`
- `BPUFXelzazFollowerAE.esp`
- `DK_Thogra.esp`
- `GORE.esp`
- `SeranaDialogAddon.esp`
- `Serana Re-Imagined.esp`
- `SDA NFF Patch.esp`
- `SDA RDO Patch.esp`
- `SDA Remiel Banter Patch.esp`
- `SDA CC Umbra Patch.esp`
- `Menagerie.esp`
- `Show Follower Carryweight.esp`

### Décision

- Garder / validation provisoire.
- Pack logique après RDO / GDO / AI Overhaul, FDE vanilla, NFF, Skyrim’s Got Talent et dialogue expansions.

### Points de vigilance

- `Remiel - FOMOD A REVOIR PLUS TARD`.
- `Thogra - PATCHES A VOIR PLUS TARD`.
- `Gore - FOMOD & PATCHES A REVOIR PLUS TARD`.
- `Serana Dialogue Add-On - PATCHES A VOIR PLUS TARD`.
- `Serana Dialogue Add-On Patch Hub - FOMOD A REVOIR PLUS TARD`.
- Patches Xelzaz Wyrmstooth / Sirenroot décochés en attente du bloc quêtes.

### Ne pas faire maintenant

- Ne pas réinstaller les followers.
- Ne pas refaire les FOMOD Remiel / Gore / SDA maintenant.
- Ne pas activer les patches Xelzaz quêtes avant le bloc quêtes.
- Ne pas régler NFF avec Inigo / Lucien / Auri / Remiel / Xelzaz maintenant.
- Ne pas tester les banters maintenant.

---

## Étape 672 — Clôture provisoire bloc 11 dialogues / followers

### Synthèse courte

Sont en place et conservés :

- expansions de dialogues NPC ;
- réactions NPC contextuelles ;
- Guard Dialogue Overhaul ;
- Relationship Dialogue Overhaul ;
- Cutting Room Floor ;
- AI Overhaul ;
- Follower Dialogue Expansion vanilla ;
- followers custom : Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore ;
- Serana Dialogue Add-On ;
- patches FDE / SDA / NFF / RDO déjà présents.

### Décision

- Clôture provisoire validée.
- Aucun changement actif MO2 pendant les étapes 669 à 672.
- Pas de test SKSE supplémentaire.

### Dettes conservées

FOMOD à revoir :

- RDO / CRF / AI Overhaul si nécessaire ;
- Misc Dialogue Edits ;
- More Dialogue Options ;
- More to Say ;
- Remiel ;
- Gore ;
- Serana Dialogue Add-On / Patch Hub.

Patches followers à reprendre plus tard :

- Xelzaz Wyrmstooth ;
- Xelzaz Sirenroot ;
- SDA patches ;
- Gore patches ;
- Thogra patches.

Compatibilité à vérifier plus tard :

- NFF avec followers custom ;
- RDO / FDE / AI Overhaul ;
- banters followers ;
- quêtes concernées.

### État final bloc 11

- SKSE / menu principal : OK sur dernier test global.
- Masters manquants : aucun.
- Messages DLL : aucun.
- Plugins cochés : oui.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **138**.
