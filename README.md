<p align="center">
  <img src="assets/branding/Logo Skyforge NSFW.png" alt="SKYFORGE" width="900">
</p>

# SKYFORGE

Projet personnel de création d’un modpack **Skyrim Special Edition 1.5.97** basé sur une fusion raisonnée entre les références **Nolvus Awakening** et **Nefaram**.

SKYFORGE vise une installation Skyrim stable, cohérente et documentée étape par étape, avec une approche prudente : installation progressive, tests réguliers, décisions différées quand un choix dépend de modules futurs, et validation explicite avant toute mise à jour structurelle.

---

## Suivre l’avancement du projet

### ➜ [Lire le dernier changelog / résumé de validation](docs/procedure/99_changelog_validation_part_15.md)

C’est le meilleur point d’entrée pour suivre l’évolution récente du modpack : dernières étapes validées, modules terminés ou en cours, décisions importantes, état de stabilité et prochaine reprise.

> Le changelog précédent reste disponible ici : [Changelog / validation — partie 14](docs/procedure/99_changelog_validation_part_14.md).  
> Le changelog historique principal reste disponible ici : [Changelog / validation — partie 1](docs/procedure/99_changelog_validation.md).

### Liens de reprise prioritaires

* [Résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md)
* [Changelog / validation — partie 15](docs/procedure/99_changelog_validation_part_15.md)
* [Module 11.1 — Followers, NPCs & dialogues — partie 1](docs/procedure/11_1_followers_npcs_dialogues_part_1.md)
* [Module 10.1 — Races, werebeasts & vampires](docs/procedure/10_1_races_werebeasts_vampires.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 450](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md)
* [Règle vampire SKYFORGE](docs/configuration/09_regle_vampire_skyforge.md)
* [Vigilances Body / Skins / BodySlide](docs/configuration/08_body_skins_bodyslide_vigilances.md)
* [Procédure principale de reproduction](docs/SKYFORGE_Procedure_Reproduction_PC.md)

### Snapshots historiques utiles

* [Snapshot Load Order MO2 — panneau gauche — étape 434](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 409](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md)
* [État MO2 ciblé — blocs 09 / 10 — étape 409](docs/configuration/SKYFORGE_Load_Order_MO2_blocs_09_10_etape_409.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 401](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_401.md)

Ces snapshots plus anciens sont conservés comme jalons historiques. Le snapshot courant de comparaison anti-doublon reste celui de l’**étape 450** tant qu’un nouveau panneau gauche complet post-480 n’est pas fourni.

### Autres fichiers de suivi

* [Ajouts personnels SKYFORGE](docs/procedure/96_ajouts_personnels_skyforge.md)
* [Registre central de dette technique](docs/procedure/97_registre_dette_technique.md)
* [Registre central de dette technique — partie 2](docs/procedure/97_registre_dette_technique_part_2.md)
* [Audit de continuité des étapes](docs/procedure/98_audit_continuite_etapes.md)
* [Décisions différées et points à revoir](docs/procedure/06_decisions_differees.md)
* [Décisions différées — partie 2](docs/procedure/06_decisions_differees_part_2.md)
* [Décisions différées — partie 3](docs/procedure/06_decisions_differees_part_3.md)
* [Décisions différées — partie 4](docs/procedure/06_decisions_differees_part_4.md)
* [Décisions différées — partie 5](docs/procedure/06_decisions_differees_part_5.md)

---

## État actuel

* **Dernière étape documentée :** Étape 480 — SPID NPC Trap Safety / audit doublon NPC AI Process Position Fix
* **Prochaine étape attendue :** Étape 481 — suite du bloc `11.1 - FOLLOWERS NPCS DIALOGUES`, sauf décision contraire de Fabien
* **Bloc en cours :** `11.1 - FOLLOWERS NPCS DIALOGUES`
* **Bloc récemment clôturé :** `10.1 - RACES WEREBEASTS VAMPIRES`, clôturé provisoirement à l’étape 458
* **Snapshot MO2 courant :** [panneau gauche étape 450](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md)
* **Note snapshot :** aucun nouveau snapshot panneau gauche complet post-480 n’a encore été fourni
* **Compteur ESP + ESM non-light post-480 :** 119
* **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
* **AE / Creation Club :** conservé
* **MO2 :** portable
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **BodySlide Output :** non généré
* **Pandora :** généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 451 à 480
* **Mods `- FR` personnels :** présents dans le panneau gauche mais décochés sauf indication contraire explicite

L’état exact le plus récent est toujours consigné dans le [résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md), le [dernier changelog](docs/procedure/99_changelog_validation_part_15.md) et les fichiers thématiques du module en cours.

---

## Règles de lecture importantes

* Le snapshot **étape 450** reste la référence courante pour vérifier si un mod est déjà installé, tant qu’un snapshot post-480 n’a pas été créé.
* Les snapshots **401**, **409** et **434** sont des jalons historiques, pas des références courantes anti-doublon.
* Les mods dont le nom se termine par `- FR` sont des traductions personnelles et restent décochés tant que le modpack n’est pas stabilisé.
* Certains séparateurs sont volontairement vides : ils préparent les modules futurs et ne doivent pas être interprétés comme des erreurs.
* Les mentions `A REINSTALLER PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `A COMPLETER PLUS TARD`, `DECOCHE`, `RESERVE` ou équivalentes font partie de la nomenclature MO2 SKYFORGE.
* Les mises à jour GitHub sont effectuées uniquement quand Fabien le décide.

---

## Objectif

Construire une installation Skyrim stable, cohérente et patchée proprement :

- **Nolvus Awakening** sert de référence principale pour le socle technique, graphique, gameplay, UI, monde, villes, quêtes, combat, magie, dialogues et confort gameplay léger.
- **Nefaram** sert de référence majeure pour les systèmes spécialisés, la cohérence Body / tenues / BodySlide, les bases corporelles, les dialogues et les compatibilités différées.

Le but n’est pas de copier deux modlists complètes aveuglément, mais d’en extraire les idées, les méthodes et les systèmes utiles pour bâtir un modpack personnel maîtrisé.

---

## Règle principale

Ne jamais fusionner deux modlists complètes aveuglément.

Extraire, tester et intégrer les systèmes progressivement.

Chaque ajout doit pouvoir être justifié, testé et documenté. En cas de doute, la décision est différée plutôt que forcée.

---

## Utilisation du dépôt

Ce dépôt sert uniquement à stocker des fichiers légers liés au projet :

- documentation technique ;
- décisions importantes ;
- checklists ;
- fichiers de configuration ;
- correctifs personnels éventuels ;
- scripts éventuels.

Il ne contient pas et ne doit pas contenir :

- archives de mods ;
- textures ;
- meshes ;
- dossiers complets MO2 ;
- backups Skyrim ;
- fichiers Bethesda / Creation Club ;
- fichiers SKSE ;
- fichiers provenant directement de mods soumis à permissions.

---

## Notes importantes

SKYFORGE est un projet personnel en construction. Les étapes documentées reflètent l’état validé au moment des tests, pas une recommandation universelle prête à l’emploi.

Les choix techniques peuvent évoluer au fur et à mesure de l’installation des modules suivants : dialogues, quêtes, followers, survie, systèmes spécialisés, tenues, BodySlide, patches finaux, LOD et DynDOLOD.
