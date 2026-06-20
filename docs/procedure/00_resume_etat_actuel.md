# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape documentée :** Étape 509 — Mythos SE Redux exclu définitivement
- **Dernier snapshot MO2 panneau gauche courant :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md`
- **Note snapshot :** le snapshot étape 509 est la référence courante anti-doublon après collage manuel du load order brut par Fabien.
- **Snapshot précédent :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md`, jalon historique post-480
- **Blocs clôturés récemment :**
  - `10 - GAMEPLAY COMBAT MAGIC PERKS` — clôturé provisoirement à l'étape 450
  - `10.1 - RACES WEREBEASTS VAMPIRES` — clôturé provisoirement à l'étape 458
  - `11.1 - FOLLOWERS NPCS DIALOGUES` — clôturé provisoirement à l'étape 490
- **Bloc en cours :** `11.2 - CUSTOM FOLLOWERS COMPANIONS`
- **Prochaine étape attendue :** Étape 510, suite du bloc `11.2 - CUSTOM FOLLOWERS COMPANIONS`, sauf décision contraire de Fabien.

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK sur les tests documentés
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés après les corrections documentées
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur le dernier état explicitement indiqué
- **Compteur ESP + ESM non-light final post-509 :** 128
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445 ; non relancé pendant les étapes 451 à 509
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_16.md`
4. `docs/procedure/11_2_custom_followers_companions_part_1.md`
5. `docs/procedure/11_1_followers_npcs_dialogues_part_2.md`
6. `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
7. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md`
8. `docs/procedure/10_1_races_werebeasts_vampires.md`
9. `docs/configuration/09_regle_vampire_skyforge.md`
10. `docs/procedure/99_changelog_validation_part_15.md`
11. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
12. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md` — jalon historique post-480
13. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md` — jalon historique post-450
14. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md` — jalon historique post-434
15. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md` — jalon historique ancien

## Étapes récentes validées / documentées

### Étapes 451 à 458 — Bloc 10.1 Races, werebeasts & vampires

- **Étape 451 :** ouverture prudente du bloc `10.1`, aucun mod installé, systèmes vampires / werebeasts / créatures différés. Compteur 110.
- **Étape 452 :** `Aetherius - A Race Overhaul` version 2.14.1. FOMOD minimal. Compteur 110.
- **Étape 453 :** `Aetherius - Race Menu Racial Passive Descriptions`. Compteur 110.
- **Étape 454 :** `Mundus - A Standing Stone Overhaul` + patch USSEP. Freyr exclu. Compteur 110.
- **Étape 455 :** `Manbeast - A Werewolf Overhaul`. Growl exclu. Compteur 110.
- **Étape 456 :** `Sacrosanct - Vampires of Skyrim` + `Cover Your Head - Sacrosanct`. Compteur 111.
- **Étape 457 :** `Sun Affects NPC Vampires`, option NPC + PJ. Compteur 111.
- **Étape 458 :** clôture provisoire du bloc `10.1`. `Vampire Lines Expansion` différé vers `11.1`. Compteur 111.

### Étapes 459 à 480 — Bloc 11.1 Followers, NPCs & dialogues — partie 1

- **Étapes 459 à 480 :** installation et stabilisation des lignes de dialogue, NPCs React, Carriages and Stables Dialogue Bundle, Show NPC Disposition, Scared of Shootings, Dialogue Expansion, Guard Dialogue Overhaul, More Dialogue Options, Misc Dialogue Edits, RDO, Cutting Room Floor, AI Overhaul, Run For Your Lives, Realistic Conversations et SPID NPC Trap Safety.
- **Compteur final part 1 :** 119.

### Étapes 481 à 490 — Bloc 11.1 Followers, NPCs & dialogues — partie 2

- **Étapes 481 à 489 :** ajout de nombreux packs `Follower Dialogue Expansion` vanilla / Nefaram / spécifiques SKYFORGE : Olfina, Uthgerd, Ysolda, Jordis, Camilla, Illia, Lydia, Mjoll, Brelyna, Erik, Faendal, Roggi, Marcurio, Sapphire, Rayya, Borgakh, Aranea, Faralda, Jenassa, Eola et Aela.
- **Étape 490 :** `Relationship Dialogue Overhaul - Update and MCM` + `RDO - FDE Compatibility Patch` validés.
- **Statut :** bloc `11.1` clôturé provisoirement après l'étape 490.
- **Compteur final part 2 :** 119.

### Étapes 491 à 509 — Bloc 11.2 Custom followers & companions

- **Étape 491 :** ouverture du séparateur `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`.
- **Étape 492 :** `INIGO` installé ; Inigo ne doit pas être importé / géré dans NFF. Compteur 120.
- **Étape 493 :** patches FDE ↔ Inigo installés. Compteur 120.
- **Étape 494 :** `Lucien - Immersive Fully Voiced Male Follower` installé ; Lucien ne doit pas être importé / géré dans NFF. Compteur 121.
- **Étape 495 :** patches FDE ↔ Lucien installés. Compteur 121.
- **Étape 496 :** `Song of the Green (Auri Follower)` installé ; Auri ne doit pas être importée / gérée dans NFF. Compteur 122.
- **Étape 497 :** patches FDE ↔ Auri installés. Compteur 122.
- **Étape 498 :** Remiel installée avec correctifs génériques ; suffixe `FOMOD A REVOIR PLUS TARD` conservé. Compteur 123.
- **Étape 499 :** patches FDE ↔ Remiel installés. Compteur 123.
- **Étape 500 :** Xelzaz installé avec suffixe `PATCHES A VOIR PLUS TARD`. Compteur 124.
- **Étape 501 :** patches Xelzaz partiels AE + FDE Aela validés. Compteur 125.
- **Étape 502 :** Thogra installée avec suffixe `PATCHES A VOIR PLUS TARD`. Compteur 126.
- **Étape 503 :** patch Remiel ↔ Thogra installé. Compteur 126.
- **Étape 504 :** Gore installé en FOMOD partiel, suffixe `FOMOD & PATCHES A REVOIR PLUS TARD`. Compteur 127.
- **Étape 505 :** Kaidan 2 installé seul, sans Extended ni patches. Compteur 128.
- **Étape 506 :** décision Kaidan : branche sobre et compatible avec futurs modules spécialisés ; extensions et patches avancés différés.
- **Étapes 507 à 509 :** `Katana - Journey in the Shadows`, `Daegon Legacy` et `Mythos SE Redux` exclus définitivement.

## Décisions structurantes actuelles

- **Nolvus Awakening** reste la référence principale pour socle technique, gameplay, UI, confort, dialogues et cohérence générale.
- **Nefaram** reste une référence majeure pour les choix NPC / dialogues / systèmes spécialisés et pour les futurs blocs Body, tenues, BodySlide et cohérence de bodies.
- **Règles MO2 SKYFORGE :** conventions de snapshot, suffixes temporaires, mods `- FR`, séparateurs vides, outils non lancés et règles de reprise sont centralisés dans `docs/procedure/01_regles_mo2_skyforge.md`.
- **Règle vampire SKYFORGE :** Fabien ne prévoit pas de jouer vampire ; ne pas ajouter de mods principalement orientés PJ vampire. Voir `docs/configuration/09_regle_vampire_skyforge.md`.
- **Custom followers :** Inigo, Lucien et Auri ne doivent pas être importés / gérés dans NFF ou un follower framework équivalent.
- **Custom followers exclus :** ne plus proposer `Katana - Journey in the Shadows`, `Daegon Legacy` ou `Mythos SE Redux`.
- **Aetherius** est l'overhaul de races retenu ; ne pas installer Mannaz ou Imperious en parallèle.
- **Mundus** est l'overhaul de Pierres Gardiennes retenu ; ne pas installer Freyr en parallèle.
- **Manbeast** est l'overhaul werewolf retenu ; ne pas installer Growl ou Moonlight Tales en parallèle.
- **Sacrosanct** est la base vampire retenue ; ne pas empiler Scion, Sacrilege, Better Vampires ou addons feeding orientés joueur.
- **GDO / RDO / AI Overhaul / FDE Compatibility** sont désormais installés et patchés selon la route documentée ; ne pas ajouter de patch alternatif sans audit.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n'est pas retenu comme générateur principal.
- Les réglages MCM non urgents seront repris plus tard avec la logique Startup Save / MCM Recorder.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d'installation, vérifier dans GitHub :

- ce résumé d'état actuel ;
- les règles MO2 SKYFORGE ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Le snapshot courant est désormais :

- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md`

Important :

- le snapshot étape 509 est la référence pratique courante anti-doublon ;
- le snapshot étape 480 devient un jalon historique ;
- ne jamais reproposer un mod déjà présent dans le snapshot courant ou les fichiers de procédure ;
- le panneau gauche MO2 ne permet pas de confirmer seul le compteur ESP + ESM non-light : ce compteur doit être donné par Fabien depuis le panneau droit MO2.

## Règle traductions personnelles FR

Tous les mods dont le nom se termine par `- FR` sont des traductions personnelles de Fabien.

Ces mods `- FR` restent volontairement **décochés pour le moment**, tant que le modpack n'est pas stabilisé.

Ils seront activés plus tard par petits groupes contrôlés, avec test SKSE / menu après chaque groupe.

Voir aussi : `docs/procedure/01_regles_mo2_skyforge.md`.

## Notes futures importantes

### PB's Silky Skin — SKYFORGE PLAYER SKIN OVERRIDE

Note dédiée : `docs/configuration/08_body_skins_bodyslide_vigilances.md`.

Objectif : éviter les problèmes de brillance excessive / shiny sur la skin du personnage joueur et prévoir plus tard un mod override dédié pour la skin PJ.

### RDO / FDE / AI Overhaul

Route actuelle validée :

```txt
Relationship Dialogue Overhaul - RDO SE
Relationship Dialogue Overhaul - Update and MCM
Cutting Room Floor
RDO - CRF + USSEP Patch
RDO - FDE Compatibility Patch
AI Overhaul SSE
AI Overhaul - Relationship Dialogue Overhaul Patch
AI Overhaul - Cutting Room Floor Patch
```

### Dialogue / NPC / followers différés

À revoir plus tard selon les blocs concernés :

- Dremora Lines Expansion
- patches CFTO / transport
- Longer Jailtime, uniquement lors d'un futur bloc prison / systèmes associés
- patches custom followers dépendants de masters absents
- patches DBVO
- traductions `- FR`

## Incidents / anomalies non bloquants à conserver

- **Étape 426 — Riverwood Giant Inn :** objets flottants à l'emplacement de l'ancien comptoir.
- **Étape 427 — écran noir non reproductible :** non bloquant.
- **Étape 441 — Remote Interactions :** master manquant corrigé par installation de Taunt Your Enemies.
- **Étape 473 — RDO CRF / USSEP :** master manquant corrigé par installation de Cutting Room Floor.
- **Étape 475 — patch AI Overhaul / RDO :** patch décoché puis réactivé à l'étape 476 après installation de AI Overhaul.

## Mods explicitement décochés / différés à conserver

- tous les mods terminés par `- FR`
- `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`
- `Kris's Papyrus Extender - DECOCHE RESERVE`
- `ENB Extender Skyrim - DECOCHE RESERVE ENB`
- `Magic College Music - Songs for Academy - DECOCHE - FORM 43`
- `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB`
- patches ou options FOMOD marqués `A REVOIR PLUS TARD`
- patches custom followers dépendants de masters absents

Les suffixes de suivi temporaires sont définis dans `docs/procedure/01_regles_mo2_skyforge.md`.

## Outils non lancés / non relancés à ce stade

- LOOT
- DynDOLOD / LOD
- BodySlide
- Pandora ne doit pas être relancé sauf demande explicite ou besoin technique d'un mod d'animation / comportement

## Dernier état stable

État documenté après étape 509 :

- Bloc `11.1 - FOLLOWERS NPCS DIALOGUES` clôturé provisoirement
- Bloc `11.2 - CUSTOM FOLLOWERS COMPANIONS` en cours
- Dernier snapshot courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md`
- Compteur non-light : 128
- Overwrite vide
- Menu principal OK
- Aucun master manquant
- Prochaine étape attendue : 510
