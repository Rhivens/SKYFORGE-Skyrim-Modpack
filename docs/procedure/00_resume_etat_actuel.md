# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape documentée :** Étape 553 — Rainbows Remade + Shooting Stars SE
- **Dernier snapshot MO2 panneau gauche courant validé :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md`
- **Snapshot post-553 préparé :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md`, en attente du collage manuel du brut MO2 complet puis vérification.
- **Snapshot précédent validé :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md`, jalon historique post-509.
- **Blocs enrichis depuis le snapshot 530 :**
  - `11.1 - FOLLOWERS NPCS DIALOGUES`
  - `03 - UI HUD MENUS`
  - `04 - AUDIO MUSIC VOICES`
  - `06 - LANDSCAPE GRASS TREES WATER`
- **Décision différée importante :** bloc map / CoMAP / FWMF / paper map à regrouper plus tard.
- **Prochaine étape attendue :** Étape 554, sauf décision contraire de Fabien.

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK sur les tests documentés
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés après corrections / différés documentés
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur les tests documentés après corrections
- **Compteur ESP + ESM non-light final post-553 :** 128
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445 ; non relancé pendant les étapes 451 à 553
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_18.md`
4. `docs/procedure/11_1_followers_npcs_dialogues_part_4.md`
5. `docs/procedure/03_ui_hud_menus_part_1.md`
6. `docs/procedure/04_audio_music_voices_part_1.md`
7. `docs/procedure/06_landscape_grass_trees_water_part_1.md`
8. `docs/procedure/06_decisions_differees_part_3.md`
9. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md` — snapshot courant validé tant que le snapshot 553 n’est pas collé / vérifié
10. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md` — placeholder préparé, en attente du brut MO2
11. `docs/procedure/99_changelog_validation_part_17.md`
12. `docs/procedure/11_1_followers_npcs_dialogues_part_3.md`
13. `docs/procedure/11_2_custom_followers_companions_part_2.md`
14. `docs/procedure/11_2_custom_followers_companions_part_1.md`
15. `docs/procedure/11_1_followers_npcs_dialogues_part_2.md`
16. `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
17. `docs/configuration/09_regle_vampire_skyforge.md`
18. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
19. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md` — jalon historique post-509
20. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md` — jalon historique post-480
21. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md` — jalon historique post-450

## Étapes récentes validées / documentées

### Étapes 451 à 458 — Bloc 10.1 Races, werebeasts & vampires

- Ouverture prudente puis stabilisation du bloc `10.1`.
- Aetherius, Mundus, Sacrosanct, Cover Your Head - Sacrosanct, Sun Affects NPC Vampires et Manbeast validés.
- Bloc clôturé provisoirement à l'étape 458.

### Étapes 459 à 490 — Bloc 11.1 Followers, NPCs & dialogues — parties 1 et 2

- Installation et stabilisation des lignes de dialogue, NPCs React, Dialogue Expansion, GDO, More Dialogue Options, Misc Dialogue Edits, RDO, Cutting Room Floor, AI Overhaul, Run For Your Lives, Realistic Conversations et SPID NPC Trap Safety.
- Ajout de nombreux packs `Follower Dialogue Expansion` vanilla / Nefaram / spécifiques SKYFORGE.
- Bloc clôturé provisoirement après l'étape 490.

### Étapes 491 à 526 — Bloc 11.2 Custom followers & companions — parties 1 et 2

- Installation et enrichissement d'Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore et Serana Dialogue Add-On.
- Installation de replacers visuels, patches ciblés, addons Skyrim's Got Talent et animations Axarien pour followers retenus.
- `Kaidan 2`, `Katana - Journey in the Shadows`, `Daegon Legacy` et `Mythos SE Redux` exclus définitivement du modpack SKYFORGE.
- Bloc enrichi jusqu'à l'étape 526.

### Étapes 527 à 530 — Retour ponctuel Bloc 11.1 Followers, NPCs & dialogues — partie 3

- `Considerate Followers` + patch Skyrim 1.5.97.
- `Chatty NPCs`, `Collision Dialogue Overhaul`, `Shouts of Stallholders`.
- `Additional Healing Reactions` documenté comme déjà installé.
- `Falmer Servant Lines Expansion`, `Missing Voices in Hearthfire Added Back` et `Cheeky Kids`.

### Étapes 531 à 533 — Bloc 11.1 Followers, NPCs & dialogues — partie 4

- **Étape 531 :** `Additional Dremora Faces - PATCHES A VOIR PLUS TARD` + `Dremora Lines Expansion`.
- **Étape 532 :** `Dynamic Dialogue Replacer - DDR` et `Skyrim Autocorrect - Dialogue Grammar Fixes` différés pour cohérence avec la traduction FR manuelle.
- **Étape 533 :** `More to Say - FOMOD A REVOIR PLUS TARD`.

### Étapes 534, 543, 549, 550 et 552 — Bloc 04 Audio, music & voices — partie 1

- `NPC Dialogue Audio Enhancer`.
- `Meridia Revoiced SE` + `The Black Door Revoiced`.
- `Whispering Tomes of Apocrypha - FOMOD A REVOIR PLUS TARD`.
- `MEMOSPORE - UI Sound Effects - FOMOD A REVOIR PLUS TARD`.
- `Whales Off The Coast - FOMOD A REVOIR PLUS TARD` + `Murmurs and Mead - FOMOD A REVOIR PLUS TARD`.

### Étapes 535 à 548 — Bloc 03 UI, HUD & menus — partie 1

- `Subtitles`, `Hotkey Reminder`, `Load Screen Shading Fix`, `Menu Zoom`, `Notification Log SSE NG`, `Yes Im Sure NG`, `Too many notifications`.
- Étapes 539 et 540 annulées / doublons.
- `Photo Mode`, `Skyrim Character Sheet`, `Name Those Ash Piles`.
- Correction Overwrite Photo Mode via `SKYFORGE - Photo Mode Output`.
- `iWant Widgets`, `iWant Widgets NG`, `iWant Status Bars`.
- `Detection Meter`, `Casting Bar`, pack d'icônes I4 / SkyUI, correction Inventory Interface Information Injector 1.5.97.
- `TrueHUD Curated Bosses` et `Show Mount Carry Weight`.

### Étape 551 — Décision différée map

- `CoMAP`, `CoMAP 4 for Skyrim 1.5`, `Flat World Map Framework` et `Skyrim Paper Map by Caro Tuts for FWMF` sont différés.
- Ces éléments devront être repris dans un bloc map dédié.
- Rappel : les plugins FWMF / paper map devront rester très bas dans le load order panneau droit pour éviter le risque de map violette.

### Étape 553 — Bloc 06 Landscape, grass, trees & water — partie 1

- `Rainbows Remade` + hotfix + patch sans notification d'initialisation.
- `Shooting Stars SE`.

## Décisions structurantes actuelles

- **Nolvus Awakening** reste la référence principale pour socle technique, gameplay, UI, confort, dialogues et cohérence générale.
- **Nefaram** reste une référence majeure pour les choix NPC / dialogues / systèmes spécialisés et pour les futurs blocs Body, tenues, BodySlide et cohérence de bodies.
- **Règles MO2 SKYFORGE :** conventions de snapshot, suffixes temporaires, mods `- FR`, séparateurs vides, outils non lancés et règles de reprise sont centralisés dans `docs/procedure/01_regles_mo2_skyforge.md`.
- **Règle vampire SKYFORGE :** Fabien ne prévoit pas de jouer vampire ; ne pas ajouter de mods principalement orientés PJ vampire. Voir `docs/configuration/09_regle_vampire_skyforge.md`.
- **Custom followers :** Inigo, Lucien et Auri ne doivent pas être importés / gérés dans NFF ou un follower framework équivalent.
- **Custom followers exclus :** ne plus proposer `Katana - Journey in the Shadows`, `Daegon Legacy`, `Mythos SE Redux` ou `Kaidan 2`.
- **Aetherius** est l'overhaul de races retenu ; ne pas installer Mannaz ou Imperious en parallèle.
- **Mundus** est l'overhaul de Pierres Gardiennes retenu ; ne pas installer Freyr en parallèle.
- **Manbeast** est l'overhaul werewolf retenu ; ne pas installer Growl ou Moonlight Tales en parallèle.
- **Sacrosanct** est la base vampire retenue ; ne pas empiler Scion, Sacrilege, Better Vampires ou addons feeding orientés joueur.
- **GDO / RDO / AI Overhaul / FDE Compatibility** sont désormais installés et patchés selon la route documentée ; ne pas ajouter de patch alternatif sans audit.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n'est pas retenu comme générateur principal.
- **Flat World Map Framework / CoMAP / paper map :** différés jusqu'à un bloc map dédié.

## Règles de reprise immédiate

- Ne pas proposer de mod déjà visible dans le snapshot 530 tant que le snapshot 553 n'a pas été collé et vérifié.
- Après collage manuel et vérification du snapshot 553, le snapshot 553 deviendra la nouvelle référence anti-doublon.
- Ne pas lancer LOOT, DynDOLOD, BodySlide ou Pandora sans demande explicite.
- Pour les mods `- FR`, ne pas les activer seuls hors phase de traduction / tests dédiés.
- Chaque nouvelle étape doit rester courte, testable et documentée.
