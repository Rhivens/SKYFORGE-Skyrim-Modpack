# État actuel officiel — SKYFORGE

## Situation générale

- Dernière étape validée/documentée : **Étape 685 — Clôture provisoire SexLab Core 13-A**
- Snapshot MO2 panneau gauche courant : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — dernier snapshot complet panneau gauche disponible ; les étapes 656 à 685 sont documentées dans les changelogs / modules thématiques
- Le snapshot 639 reste la référence anti-doublon courante jusqu’à création d’un nouveau snapshot MO2.
- Prochaine étape attendue : **Étape 686**
- Compteur ESP + ESM non-light post-685 : **141**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 656 à 685**
- FNIS : **non lancé**
- SexLab Framework SE v1.63 : **actif et initialisé via MCM**
- SLSF Reloaded 3.4.1 : **actif, MCM visible**

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK sur les tests documentés
- **Menu principal :** OK sur les tests documentés
- **Masters manquants :** aucun sur les tests validés
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK sur les tests documentés
- **Overwrite :** vide sur les tests documentés
- **Compteur ESP + ESM non-light final post-685 :** 141
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès à l'étape 411 ; Output actif ; non relancé pendant les étapes 656 à 685
- **FNIS :** non lancé
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/01_regles_mo2_skyforge.md`
3. `docs/procedure/99_changelog_validation_part_25.md`
4. `docs/procedure/17_sexlab_core_adult_frameworks_part_1.md`
5. `docs/procedure/06_decisions_differees_part_11.md`
6. `docs/procedure/12_characters_body_skins_bodyslide_part_1.md`
7. `docs/procedure/13_animations_skeleton_physics_part_1.md`
8. `docs/procedure/14_gameplay_combat_magic_perks_part_1.md`
9. `docs/procedure/15_followers_npcs_dialogues_part_1.md`
10. `docs/procedure/16_survival_immersion_roleplay_part_1.md`
11. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_639.md` — dernier snapshot panneau gauche disponible
12. `docs/procedure/99_changelog_validation_part_24.md`
13. `docs/procedure/11_cities_towns_interiors_lighting_part_1.md`
14. `docs/procedure/10_landscape_grass_trees_water_part_6.md`
15. `docs/procedure/06_decisions_differees_part_10.md`

## Étapes récentes validées / documentées

### Étapes 640 à 655 — Clôtures provisoires blocs 06 et 07

- Bloc `[06 - LANDSCAPE GRASS TREES WATER]` clôturé provisoirement à l’étape 644.
- Bloc `[07 - CITIES TOWNS INTERIORS LIGHTING]` clôturé provisoirement à l’étape 655.
- Aucun nouveau fichier actif installé pendant ces audits.
- Compteur ESP + ESM non-light conservé à **138**.

### Étapes 656 à 658 — Bloc 08 Characters / Hair / Body

- Ouverture opérationnelle du bloc 08.
- Validation courte des sous-blocs `[08.1 - CORE CHARACTERS TOOLS]`, `[08.2 - HAIR-EYES-BROWS-OVERLAYS]` et `[08.3 - BODY - SKINS - BODYSLIDE]`.
- Aucun changement actif dans MO2.
- BodySlide Output toujours non généré.
- Compteur conservé à **138**.

### Étapes 659 à 663 — Bloc 09 Animations / Skeleton / Physics

- Ouverture et validation provisoire du bloc `[09 - ANIMATIONS SKELETON PHYSICS]`.
- Socle physics / skeleton / OAR / Pandora / mouvement déjà présent.
- Pandora Output conservé, Pandora non relancé.
- Bloc 09 clôturé provisoirement à l’étape 663.
- Compteur conservé à **138**.

### Étapes 664 à 668 — Bloc 10 Gameplay / Combat / Races

- Ouverture du bloc `[10 - GAMEPLAY COMBAT MAGIC PERKS]`.
- Validation provisoire du combat core, followers / interactions / utility gameplay, horses / bounty / misc gameplay.
- Validation provisoire de `[10.1 - RACES WEREBEASTS VAMPIRES]`.
- Aucun changement actif dans MO2.
- Compteur conservé à **138**.

### Étapes 669 à 672 — Bloc 11 Dialogues / Followers

- Validation provisoire des dialogues / réactions NPC / AI Overhaul / RDO / CRF.
- Validation provisoire de Follower Dialogue Expansion vanilla.
- Validation provisoire des followers custom : Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore, Serana Dialogue Add-On.
- Bloc 11 clôturé provisoirement à l’étape 672.
- Aucun changement actif dans MO2.
- Compteur conservé à **138**.

### Étapes 673 à 681 — Survival et préparation SexLab

- Bloc `[12 - SURVIVAL IMMERSION ROLEPLAY]` ouvert et constaté presque vide.
- Bloc `[13 - SEXLAB CORE ADULT FRAMEWORKS]` ouvert et constaté presque vide avant installation.
- Plan SexLab Core 1.5.97 préparé.
- Candidats validés : SexLab Framework SE v163, SLAL 1.6, ZaZ Animation Pack SE, SLSF / SexLab Sexual Fame Framework SE.
- `SLO Aroused NG 3.1.7` différé en raison d’une DLL NG à vérifier.
- Aucune installation active jusqu’à l’étape 681.
- Compteur conservé à **138**.

### Étapes 682 à 685 — SexLab Core 13-A

- Installation active de SexLab Core 13-A : SexLab Framework SE v1.63, SLAL 1.6, ZaZ Animation Pack SE, SLSF Reloaded 3.4.1.
- SLSF Reloaded d’abord installé décoché, puis activé après initialisation SexLab.
- SexLab v1.63 SE initialisé via MCM sur sauvegarde test.
- SLSF Reloaded MCM visible.
- Aucun CTD signalé.
- Aucun message anormal signalé.
- Overwrite conservé vide.
- LOOT non lancé.
- Pandora/FNIS non lancé.
- BodySlide non généré.
- Compteur ESP + ESM non-light : **138 → 141**.
- Bloc SexLab Core 13-A clôturé provisoirement à l’étape 685.

## Surveillance compteur ESP + ESM non-light

- `< 160` non-light : zone confortable.
- `160–190` : vigilance normale.
- `190–220` : vigilance renforcée.
- `220–235` : audit obligatoire avant gros ajout.
- `235+` : mode survie ; ESLification, suppressions ou merges propres à envisager.

État post-685 : **141 non-light**, donc zone confortable.
