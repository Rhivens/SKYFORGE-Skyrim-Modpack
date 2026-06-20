# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape documentée :** Étape 480 — SPID NPC Trap Safety / audit doublon NPC AI Process Position Fix
- **Dernier snapshot MO2 panneau gauche courant :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md`
- **Note snapshot :** le snapshot étape 480 contient désormais le snapshot brut complet du panneau gauche MO2 et remplace le snapshot étape 450 comme référence courante anti-doublon.
- **Snapshot précédent :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md`, désormais jalon historique post-450
- **Blocs clôturés récemment :**
  - `10 - GAMEPLAY COMBAT MAGIC PERKS` — clôturé provisoirement à l'étape 450
  - `10.1 - RACES WEREBEASTS VAMPIRES` — clôturé provisoirement à l'étape 458
- **Bloc en cours :** `11.1 - FOLLOWERS NPCS DIALOGUES`
- **Prochaine étape attendue :** Étape 481, suite du bloc `11.1 - FOLLOWERS NPCS DIALOGUES`, sauf décision contraire de Fabien.

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
- **Compteur ESP + ESM non-light final post-480 :** 119
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445 ; non relancé pendant les étapes 451 à 480
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_15.md`
4. `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
5. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md`
6. `docs/procedure/10_1_races_werebeasts_vampires.md`
7. `docs/configuration/09_regle_vampire_skyforge.md`
8. `docs/procedure/99_changelog_validation_part_14.md`
9. `docs/procedure/10_gameplay_combat_magic_perks_part_4.md`
10. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md` — jalon historique post-450
12. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md` — jalon historique post-434
13. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md` — jalon historique ancien

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

### Étapes 459 à 480 — Bloc 11.1 Followers, NPCs & dialogues

- **Étape 459 :** ouverture du bloc `11.1` avec Bandit / Civil War / Forsworn and Thalmor / Vampire Lines Expansion. Compteur 111.
- **Étape 460 :** `Brawl Lines Expansion and Fixes`. `Dremora Lines Expansion` différé. Compteur 111.
- **Étape 461 :** pack NPCs React : Necromancy, Invisibility, Bow of Shadows patch, Frenzy. Compteur 111.
- **Étape 462 :** `Carriages and Stables Dialogue Bundle`; patch CFTO différé. Compteur 111.
- **Étape 463 :** `Show NPC Disposition Relationship Rank`, `Dialogue Window Auto Close Exit Begone`, `Scared of Shootings`. Compteur 111.
- **Étape 464 :** Dialogue Expansion Windhelm, Shor's Stone, Khajiit Caravans. Compteur 111.
- **Étape 465 :** annulation propre de `Immersive Dialogue Expansion - Whiterun` car obsolète / caché. Compteur 111.
- **Étape 466 :** `Neutral Whiterun Guards`, `Truly Neutral Prisoners`, `More Sensible Quartermasters` version complète. Compteur 111.
- **Étape 467 :** `Robber's Gorge Fixes`, FOMOD patch `None`; `Longer Jailtime` différé. Compteur 111.
- **Étape 468 :** `Guard Dialogue Overhaul SE` version ESP + `Guard Dialogue Overhaul MCM`. Compteur 111.
- **Étape 469 :** `GuardsTalk`. Compteur 112.
- **Étape 470 :** `More Dialogue Options - FOMOD À REVOIR PLUS TARD`, patches GDO ESP + Riverwood Trader. Compteur 112.
- **Étape 471 :** `Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD`, patch Skyrim Unbound Reborn. Compteur 112.
- **Étape 472 :** `Relationship Dialogue Overhaul - RDO SE`. Compteur 113.
- **Étape 473 :** `Cutting Room Floor` + `RDO - CRF + USSEP Patch.esp`. Compteur 116.
- **Étape 474 :** audit / stabilisation RDO Update and MCM ; route stable RDO base + CRF + patch conservée. Compteur 116.
- **Étape 475 :** patch AI Overhaul / RDO testé puis décoché car `AI Overhaul.esp` absent à cette étape. Compteur 116.
- **Étape 476 :** `AI Overhaul SSE` 1.9.5 + AIO Fishing ; patch AI Overhaul / RDO réactivé. Compteur 117.
- **Étape 477 :** `AI Overhaul - Cutting Room Floor Patch`. Compteur 117.
- **Étape 478 :** `Run For Your Lives`. Compteur 118.
- **Étape 479 :** `Realistic Conversations`. Compteur 119.
- **Étape 480 :** `SPID NPC Trap Safety`; `NPC AI Process Position Fix - NG` déjà présent, non réinstallé. Compteur 119.

## Décisions structurantes actuelles

- **Nolvus Awakening** reste la référence principale pour socle technique, gameplay, UI, confort, dialogues et cohérence générale.
- **Nefaram** reste une référence majeure pour les choix NPC / dialogues / systèmes spécialisés et pour les futurs blocs Body, tenues, BodySlide et cohérence de bodies.
- **Règles MO2 SKYFORGE :** conventions de snapshot, suffixes temporaires, mods `- FR`, séparateurs vides, outils non lancés et règles de reprise sont centralisés dans `docs/procedure/01_regles_mo2_skyforge.md`.
- **Règle vampire SKYFORGE :** Fabien ne prévoit pas de jouer vampire ; ne pas ajouter de mods principalement orientés PJ vampire. Voir `docs/configuration/09_regle_vampire_skyforge.md`.
- **Aetherius** est l'overhaul de races retenu ; ne pas installer Mannaz ou Imperious en parallèle.
- **Mundus** est l'overhaul de Pierres Gardiennes retenu ; ne pas installer Freyr en parallèle.
- **Manbeast** est l'overhaul werewolf retenu ; ne pas installer Growl ou Moonlight Tales en parallèle.
- **Sacrosanct** est la base vampire retenue ; ne pas empiler Scion, Sacrilege, Better Vampires ou addons feeding orientés joueur.
- **GDO / RDO / AI Overhaul** sont désormais installés et patchés selon la route documentée ; ne pas ajouter de patch alternatif sans audit.
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

- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md`

Important :

- le snapshot étape 480 est la référence pratique courante ;
- le snapshot étape 450 reste conservé comme jalon historique post-450 ;
- le snapshot étape 434 reste conservé comme jalon historique post-434 ;
- le snapshot étape 409 reste conservé comme jalon historique ancien ;
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

### RDO Update and MCM

Différé.

À auditer plus tard uniquement si SKYFORGE décide de remplacer ou compléter la route stable actuelle :

```txt
Relationship Dialogue Overhaul - RDO SE
Cutting Room Floor
RDO - CRF + USSEP Patch
```

### AI Overhaul patches

Actuellement validés :

- AI Overhaul - Relationship Dialogue Overhaul Patch
- AI Overhaul - Cutting Room Floor Patch

Différés / non installés :

- AI Overhaul - RDO Updated Patch
- patchs Denizens of Morthal / Distinct Interiors, selon futures décisions.

### Dialogue / NPC différés

À revoir plus tard :

- Dremora Lines Expansion
- Follower Dialogue Expansion - Olfina Gray-Mane
- Immersive Dialogue Expansion - Stormcloaks
- patches CFTO / transport
- Longer Jailtime, uniquement lors d'un futur bloc prison / systèmes associés

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

Les suffixes de suivi temporaires sont définis dans `docs/procedure/01_regles_mo2_skyforge.md`.

## Outils non lancés / non relancés à ce stade

- LOOT
- DynDOLOD / LOD
- BodySlide
- Pandora ne doit pas être relancé sauf demande explicite ou besoin technique d'un mod d'animation / comportement

## Dernier état stable

État documenté après étape 480 :

- Bloc `10.1 - RACES WEREBEASTS VAMPIRES` clôturé provisoirement
- Bloc `11.1 - FOLLOWERS NPCS DIALOGUES` en cours
- Dernier snapshot courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md`
- Compteur non-light : 119
- Overwrite vide
- Menu principal OK
- Aucun master manquant
- Prochaine étape attendue : 481
