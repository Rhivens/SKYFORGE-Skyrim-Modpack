# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape documentée :** Étape 450 — Clôture du bloc 7.8 Misc Gameplay
- **Dernière étape validée avant snapshot load order :** Étape 450, sous réserve de confirmation du prochain snapshot MO2 panneau gauche
- **Séparateur clôturé provisoirement :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Prochain séparateur prévu :** 11 - RACES WEREBEASTS VAMPIRES
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module actif terminé :** gameplay / combat léger / misc gameplay inspiré de Nolvus Awakening
- **Prochaine étape attendue :** création / validation du nouveau snapshot load order après réception du panneau gauche MO2 complet, puis reprise en étape 451 ou bloc 11 selon décision de Fabien.

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés, avec correction du master `Taunt Your Enemies.esp` à l'étape 441
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur les derniers états explicitement indiqués
- **Compteur ESP + ESM non-light :** à confirmer avec le prochain snapshot MO2 panneau gauche
- **Dernier compteur explicite dans les notes transmises :** 109 à l'étape 446
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411, Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/99_changelog_validation_part_14.md`
3. `docs/procedure/10_gameplay_combat_magic_perks_part_4.md`
4. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
5. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md` — dernier snapshot courant disponible en attendant le futur snapshot post-450
6. `docs/procedure/99_changelog_validation_part_13.md`
7. `docs/procedure/10_gameplay_combat_magic_perks_part_3.md`
8. `docs/procedure/99_changelog_validation_part_12.md`
9. `docs/procedure/10_gameplay_combat_magic_perks_part_2.md`
10. `docs/procedure/09_animations_skeleton_physics_part_3.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md` — jalon historique, ne plus utiliser comme snapshot courant.

## Étapes récentes validées / documentées

- **Étape 435 :** reprise contrôlée post-snapshot 434. Aucune installation. Test menu OK. Compteur 108.
- **Étape 436 :** `Simplest Horses - Main File`. Patch `Simplest Horses - Animated Whistling Patch` différé à cette étape. Test menu OK. Compteur 108.
- **Étape 437 :** `No Need to Ask... Bounty Is Served`. Test menu OK. Compteur 108.
- **Étape 438 :** `State Your Claw`, `Food For The Thirsty`, `Switch Camera During Dialogue`. Option `Food For The Thirsty - Default`, option `Immersive Interactions` différée. Test menu OK. Compteur 108.
- **Étape 439 :** `Dragon Claws Auto-Unlock` + `Take a Peek - New Stealth Mechanic`. Patcher Dragon Claws et patch Simply Knock différés. Placement / compteur à confirmer avec le prochain snapshot.
- **Étape 440 :** `Classic Sprinting Redone (Latest version for SE)` version 2.2. Version AE non retenue. `Instantly Skip Dialogue NG` non réinstallé car déjà présent.
- **Étape 441 :** `Taunt Your Enemies` + `Remote Interactions`. Correction du master manquant `Taunt Your Enemies.esp` après proposition initiale de `Remote Interactions` seul.
- **Étape 442 :** `Vampire Lords Can Fly` exclu. Fabien ne prévoit pas de jouer vampire. Aucune installation. Compteur 108.
- **Étape 443 :** `Skyrim's Got Talent - Improve As a Bard`. `BA Bard Songs` déjà présent. Patchs optionnels et `Flute Animation Fix` différés. Compteur courant indiqué à 109 avant l'étape 444.
- **Étape 444 :** clôture provisoire du bloc misc gameplay léger. `Sky Parkour`, `Skyrim's Paraglider`, `Gamepad++` et assimilés différés à ce moment. Compteur 109.
- **Étape 445 :** `SkyParkour v3`, patch Pandora / CRC32 Cache et `SkyParkour v3 - SKYFORGE ini`. Fichier INI isolé. Génération Pandora dédiée.
- **Étape 446 :** `Skyrim's Paraglider` exclu. Fichiers associés non installés. Note future ajoutée pour `Dirty Deeds Missives 1.4.2`. Compteur 109.
- **Étape 447 :** non documentée dans le lot transmis. `Headhunter - Bounties Redone` apparaît dans la clôture de l'étape 450 comme installé / validé ; présence et placement à confirmer avec le prochain snapshot MO2.
- **Étape 448 :** `Nether's Follower Framework` 2.8.6b + `Nether's Follower Framework - Settings Loader`. FOMOD à revoir plus tard pour Interesting NPCs / RDO / options SPID / No Team Magic Damage / compatibilités systèmes spécialisés futurs.
- **Étape 449 :** `Animated Whistling` + `Simplest Horses - Animated Whistling Patch`. Patch Simplest Horses précédemment différé désormais installé.
- **Étape 450 :** clôture provisoire du bloc `10 - GAMEPLAY COMBAT MAGIC PERKS` / `7.8 Misc Gameplay`. Nouveau séparateur prévu : `[11 - RACES WEREBEASTS VAMPIRES]`.

## Décisions structurantes actuelles

- **Nolvus Awakening** reste la référence principale pour combat / dodge / animations combat / confort gameplay léger / misc gameplay.
- **Nefaram** reste la référence principale pour les futurs blocs Body, tenues, BodySlide et cohérence de bodies.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n'est pas retenu comme générateur principal.
- Les réglages TK Dodge RE doivent être des réglages SKYFORGE propres, inspirés de Nolvus Awakening mais adaptés au modpack.
- Les réglages MCM non urgents seront repris plus tard avec la logique Startup Save / MCM Recorder.
- Ne pas dépendre des fichiers Nolvus Awakening locaux, sauf besoin futur de comparaison avancée.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d'installation, vérifier dans GitHub :

- ce résumé d'état actuel ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Le snapshot courant disponible reste pour l'instant :

- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md`

Important :

- un nouveau snapshot post-450 doit être créé après réception du nouveau load order complet ;
- le snapshot étape 409 reste conservé comme historique, mais ne doit plus servir de référence principale de comparaison ;
- ne jamais reproposer un mod déjà présent dans le snapshot ou les fichiers de procédure ;
- après réception du load order post-450, le nouveau snapshot devra remplacer le snapshot 434 comme référence pratique courante.

## Règle traductions personnelles FR

Tous les mods dont le nom se termine par `- FR` sont des traductions personnelles de Fabien.

Ces mods `- FR` restent volontairement **décochés pour le moment**, tant que le modpack n'est pas stabilisé.

Ils seront activés plus tard par petits groupes contrôlés, avec test SKSE / menu après chaque groupe.

Leur présence dans le panneau gauche MO2 ne doit pas être interprétée comme une erreur ou un oubli.

## Notes futures importantes

### PB's Silky Skin — SKYFORGE PLAYER SKIN OVERRIDE

Une note dédiée a été créée dans :

- `docs/configuration/08_body_skins_bodyslide_vigilances.md`

Objectif :

- éviter les problèmes de brillance excessive / shiny sur la skin du personnage joueur ;
- surveiller les textures spéculaires `*_s.dds` du corps, des mains et de la tête ;
- prévoir plus tard un mod override dédié pour la skin PJ lors du bloc Body / Outfits / BodySlide.

### Dirty Deeds Missives 1.4.2

À auditer plus tard lors du bloc Missives / patches final :

- compatibilité avec `Headhunter - Bounties Redone` ;
- compatibilité avec `Missives` ;
- compatibilité avec les patchs `Headhunter - Missives` ;
- compatibilité Bruma / Solstheim / Wyrmstooth si utilisés ;
- conflits éventuels sur jobs de primes, notes, quêtes radiant, aliases ou récompenses ;
- nécessité éventuelle d'un patch SKYFORGE dédié.

### Nether's Follower Framework

À revoir plus tard pour :

- options Interesting NPCs / RDO ;
- options SPID / No Team Magic Damage ;
- compatibilités followers, IA, dialogues et systèmes spécialisés différés.

## Incidents / anomalies récents non bloquants

### Étape 420 — Block Enchantments

`Block Enchantments` reste validé malgré le warning MO2 transitoire `Plugin not found: blockenchantments.esl` observé auparavant.

Le plugin était visible et actif dans le panneau droit MO2, chargé en FE / ESL-light, sans master manquant ni crash reproduit.

### Étape 426 — Riverwood Giant Inn

Anomalie graphique non bloquante : objets flottants à l'emplacement de l'ancien comptoir dans la cellule Giant Inn de Riverwood.

Décision : à corriger plus tard, sans bloquer le module combat / gameplay.

### Étape 427 — écran noir non reproductible

Un écran noir / blocage avant menu a été observé au premier lancement après installation de `NPCs Use Potions`.

Après relance, l'incident ne s'est pas reproduit et le menu principal a été atteint normalement.

Décision : vigilance mineure, non bloquante.

### Étape 441 — Remote Interactions

`Remote Interactions` seul a provoqué un master manquant `Taunt Your Enemies.esp`.

Correction : installation de `Taunt Your Enemies`, puis validation du mini-bloc.

## Vigilances restantes

- **Nouveau snapshot post-450 :** à créer après réception du load order complet.
- **Compteur ESP + ESM non-light final post-450 :** à confirmer avec le prochain snapshot.
- **Étape 447 / Headhunter :** bloc détaillé absent du lot transmis ; présence / placement à confirmer avec le prochain snapshot MO2.
- **BodySlide Output :** non généré.
- **XPMSSE :** FOMOD à revoir plus tard avant animations avancées / styles d'armes.
- **LeveledList Crash Fix AE + 1.5 :** à vérifier hors urgence.
- **LOOT :** non lancé.
- **DynDOLOD / LOD :** non générés.
- **Mods `- FR` :** toujours décochés volontairement.
- **Mod fautif CTD étape 413 :** `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD` doit rester décoché / différé.
- **Incident Windows étape 420 :** à surveiller uniquement si récidive.
- **Precision - Creatures :** reste différé.
- **Bug graphique Riverwood Giant Inn :** objets flottants à corriger plus tard.
- **MCM non configurés des étapes 428, 429, 432 et 434 :** à reprendre plus tard avec Startup Save / MCM Recorder.
- **FOMOD NPCs Use Potions :** à revoir plus tard si ajout officiel de nouveaux mondes, quêtes, donjons ou créatures compatibles.
- **Patchs conditionnels du bloc misc gameplay :** à revoir plus tard selon les mods installés.

## Mods explicitement décochés / différés à conserver

- `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`
- `Kris's Papyrus Extender - DECOCHE RESERVE`
- `ENB Extender Skyrim - DECOCHE RESERVE ENB`
- `Magic College Music - Songs for Academy - DECOCHE FORM 43`
- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD`
- `Cities of the North - Morthal - DECOCHE CHOIX A REVOIR`
- `Scarecrows of Skyrim - BOS - SOS Patch - REQUIERT SIMPLICTY OF SNOW`
- `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE`
- tous les mods terminés par `- FR`

## Outils non lancés / non relancés à ce stade

- LOOT
- DynDOLOD / LOD
- BodySlide
- Pandora ne doit pas être relancé sauf demande explicite ou besoin technique d'un mod d'animation / comportement

## Dernier état stable

État documenté après étape 450 :

- Bloc `10 - GAMEPLAY COMBAT MAGIC PERKS` clôturé provisoirement
- Prochain bloc prévu : `[11 - RACES WEREBEASTS VAMPIRES]`
- SKSE / menu principal : OK sur les tests documentés
- Overwrite : vide sur les derniers états explicitement indiqués
- CrashLogger actif
- Pandora Output actif
- Compteur final post-450 : à confirmer avec le prochain snapshot load order
