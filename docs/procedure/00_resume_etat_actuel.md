# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 578 — Stockades, dents de spectre, sigils**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md` — placeholder créé, collage manuel du load order complet à effectuer
- Le snapshot 567 devient un jalon historique post-567.
- Prochaine étape attendue : **Étape 579**
- Compteur ESP + ESM non-light post-578 : **129**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 451 à 578**

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
- **Compteur ESP + ESM non-light final post-578 :** 129
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; génération dédiée utilisée pour SkyParkour v3 à l'étape 445 ; non relancé pendant les étapes 451 à 578
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md` — snapshot courant post-578, placeholder créé, collage manuel à effectuer
4. `docs/procedure/99_changelog_validation_part_20.md`
5. `docs/procedure/05_visual_base_meshes_textures_part_2.md`
6. `docs/procedure/06_decisions_differees_part_6.md`
7. `docs/procedure/99_changelog_validation_part_19.md`
8. `docs/procedure/05_visual_base_meshes_textures_part_1.md`
9. `docs/procedure/11_1_followers_npcs_dialogues_part_4.md`
10. `docs/procedure/03_ui_hud_menus_part_1.md`
11. `docs/procedure/04_audio_music_voices_part_2.md`
12. `docs/procedure/06_landscape_grass_trees_water_part_1.md`
13. `docs/procedure/06_decisions_differees_part_4.md`
14. `docs/procedure/06_decisions_differees_part_5.md`
15. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_567.md` — jalon historique post-567
16. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_553.md` — jalon historique post-553
17. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_530.md` — jalon historique post-530
18. `docs/procedure/99_changelog_validation_part_17.md`
19. `docs/procedure/11_1_followers_npcs_dialogues_part_3.md`
20. `docs/procedure/11_2_custom_followers_companions_part_2.md`
21. `docs/procedure/11_2_custom_followers_companions_part_1.md`
22. `docs/procedure/11_1_followers_npcs_dialogues_part_2.md`
23. `docs/procedure/11_1_followers_npcs_dialogues_part_1.md`
24. `docs/configuration/09_regle_vampire_skyforge.md`
25. `docs/configuration/08_body_skins_bodyslide_vigilances.md`
26. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_509.md` — jalon historique post-509
27. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md` — jalon historique post-480
28. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md` — jalon historique post-450

## Étapes récentes validées / documentées

### Étapes 554 à 567 — Audio, clutter, statues, shrines et Dwemer misc models

- Installation et stabilisation des compléments audio ISC / Phoenix Compendium, clutter Ruins Clutter Improved, objets divers, chandelles, livres, ingrédients, objets JS, statues, shrines et base Dwemer.
- Passage du compteur ESP + ESM non-light à **129** lors de l’étape 563.
- Étape 567 validée avec `JS Instruments of Skyrim SE - Uniques.esp`, compteur inchangé à **129**.

### Étapes 568 à 578 — Clutter visuel, tentes animées, objets précieux et petits replacers

- Installation de petits replacers ElSopa, objets de quête, carrioles, marchés animés BOS, tentes animées BOS, objets précieux, potions, gemmes d’âme, bateaux, ateliers, effets visuels légers, architecture Falmer ciblée, coffres, cages, stockades et sigils.
- Plusieurs plugins ESPFE / light ou assimilés ajoutés sans augmentation du compteur non-light.
- Plusieurs options / patches sont différés : FOMOD JS Dragon Claws AE, Unique Skulls HD, MultiLayer Parallax Soul Gems, High Poly Project, More Bloodshed, Stalhrim Source, Jabber's Archery Targets, Legacy of the Dragonborn, ENB Light / particules.
- État final post-578 : SKSE/menu principal OK, aucun master manquant, aucun message DLL, Overwrite vide, compteur ESP + ESM non-light **129**.
- Snapshot MO2 panneau gauche post-578 créé avec placeholder dans `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_578.md`.
