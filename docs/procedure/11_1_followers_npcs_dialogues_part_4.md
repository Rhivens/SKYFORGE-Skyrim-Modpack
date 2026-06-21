# Module 11.1 — Followers, NPCs & dialogues — partie 4

Ce fichier documente la reprise ponctuelle du bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` après le snapshot étape 530.

Périmètre : étapes **531 à 533**.

État de référence :
- étape précédente validée : 530 ;
- snapshot MO2 panneau gauche de référence : étape 530 ;
- compteur ESP + ESM non-light au début du bloc : 128.

---

## Étape 531 — Dremora Lines Expansion

### Objectif
Ajouter les lignes de dialogue Dremora issues de la logique Nolvus Awakening, sans toucher aux systèmes créatures, animations, Pandora, BodySlide ou SexLab.

### Référence
- Source principale : Nolvus Awakening
- Type : dialogues NPC / Dremora
- Étape précédente : 530
- Snapshot MO2 de référence : étape 530

### Mods installés
- Additional Dremora Faces - PATCHES A VOIR PLUS TARD
- Dremora Lines Expansion

### Liens
- Additional Dremora Faces : https://www.nexusmods.com/skyrimspecialedition/mods/97946
- Dremora Lines Expansion : https://www.nexusmods.com/skyrimspecialedition/mods/100562

### Décision patches
Les fichiers principaux ont été installés uniquement.

Les patches optionnels de `Additional Dremora Faces` sont différés :
- Finding Velehk Sain Patch
- The Cause Reduced Cut Patch
- DERP Patch
- CC The Cause Patch
- Zim Dremora Patch
- anciens patches VIGILANT / Odin / VNR

Raison : masters et pertinence à revoir plus tard selon l’état réel des blocs quêtes, Daedra, CC et overhauls Dremora.

### Actions réalisées
- Installation de `Additional Dremora Faces`.
- Installation de `Dremora Lines Expansion`.
- Marqueur ajouté sur `Additional Dremora Faces` : `PATCHES A VOIR PLUS TARD`.
- Aucun lancement de LOOT.
- Aucun lancement de DynDOLOD.
- Aucun lancement de BodySlide.
- Aucun lancement de Pandora.

### Plugins
Plugins cochés.
Aucun master manquant.

### Résultat test
- Menu principal : OK.
- Aucun master manquant.
- Aucun message DLL.
- Tous les plugins cochés.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 128.

### Validation
Étape 531 validée.
Compteur non-light inchangé : 128.

## Étape 532 — DIFFÉRÉE

### Décision
Étape différée : `Dynamic Dialogue Replacer - DDR` et `Skyrim Autocorrect - Dialogue Grammar Fixes` ne sont pas installés maintenant.

### Raison
SKYFORGE suit une stratégie de traduction FR manuelle via ESP-ESM Translator. Les corrections automatiques de dialogue orientées anglais sont peu prioritaires et peuvent compliquer la cohérence VF.

### Décision technique
- `Dynamic Dialogue Replacer - DDR` : différé, à réévaluer seulement si un mod utile en dépend.
- `Skyrim Autocorrect - Dialogue Grammar Fixes` : différé / non prioritaire pour un setup FR.
- `Skyrim Autocorrect - Aesthetics Addon` : exclu pour l’instant.

### Conséquence
Aucune installation.
Aucun plugin ajouté.
Compteur ESP + ESM non-light inchangé : 128.
Overwrite inchangé : vide.

## Étape 533 — More to Say

### Objectif
Ajouter un pack de dialogues vanilla-friendly pour plusieurs zones et NPC existants, compatible avec une future traduction FR personnelle via ESP-ESM Translator.

### Référence
- Source principale : Nefaram
- Type : dialogues NPC / dialogues vanilla-friendly
- Étape précédente validée : 531
- Étape 532 : différée
- Snapshot MO2 de référence : étape 530 + ajout étape 531

### Mod installé
- More to Say - FOMOD A REVOIR PLUS TARD

### Lien
- More to Say : https://www.nexusmods.com/skyrimspecialedition/mods/22622

### Choix FOMOD
Tous les modules disponibles ont été cochés :
- Whiterun
- Riverwood
- Shor's Stone and Ivarstead
- Karthwasten and Dragon Bridge
- Rorikstead
- Falkreath
- Morthal
- Winterhold
- Castle Volkihar
- Solstheim
- Dawnguard
- Dark Brotherhood
- Miscellaneous
- Optional plugin si proposé par le FOMOD et cohérent avec les masters présents

### Marqueur conservé
`FOMOD A REVOIR PLUS TARD`

Raison : More to Say est volumineux, modulaire et fortement lié aux dialogues. Une revue ultérieure reste nécessaire pour patches, modules additionnels, traduction FR et cohérence avec les blocs quêtes / villes / factions.

### Actions réalisées
- Installation de `More to Say`.
- Tous les modules du FOMOD ont été cochés.
- Marqueur MO2 conservé : `FOMOD A REVOIR PLUS TARD`.
- Aucun lancement de LOOT.
- Aucun lancement de DynDOLOD.
- Aucun lancement de BodySlide.
- Aucun lancement de Pandora.

### Plugins
Plugins cochés.
Aucun master manquant.

### Résultat test
- Menu principal : OK.
- Aucun master manquant.
- Aucun message DLL.
- Tous les plugins cochés.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 128.

### Validation
Étape 533 validée.
Compteur non-light inchangé : 128.
