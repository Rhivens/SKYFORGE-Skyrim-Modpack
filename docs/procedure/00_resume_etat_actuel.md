# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 567 — JS Attunement Sphere / Lexicons / Instruments**
- Snapshot MO2 panneau gauche courant : **`docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md`**
- Le snapshot 553 devient un jalon historique post-553.
- Prochaine étape attendue : **Étape 568**
- Compteur ESP + ESM non-light post-567 : **129**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 451 à 567**

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
- **Compteur ESP + ESM non-light final post-567 :** 129
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445 ; non relancé pendant les étapes 451 à 567
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_19.md`
4. `docs/procedure/11_1_followers_npcs_dialogues_part_4.md`
5. `docs/procedure/03_ui_hud_menus_part_1.md`
6. `docs/procedure/04_audio_music_voices_part_2.md`
7. `docs/procedure/05_visual_base_meshes_textures_part_1.md`
8. `docs/procedure/06_landscape_grass_trees_water_part_1.md`
9. `docs/procedure/06_decisions_differees_part_4.md`
10. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md` — jalon courant post-567
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md` — jalon historique post-553
12. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md` — jalon historique post-530
13. `docs/procedure/99_changelog_validation_part_17.md`
14. `docs/procedure/11_1_followers_npcs_dialogues_part_3.md`
15. `docs/procedure/11_2_custom_followers_companions_part_2.md`
16. `docs/procedure/11_2_custom_followers_companions_part_1.md`
17. `docs/procedure/11_1_followers_npcs_dialogues_part_2.md`
18. `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
19. `docs/configuration/09_regle_vampire_skyforge.md`
20. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
21. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md` — jalon historique post-509
22. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md` — jalon historique post-480
23. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md` — jalon historique post-450

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
