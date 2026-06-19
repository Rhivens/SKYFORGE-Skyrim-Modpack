<p align="center">
  <img src="assets/branding/Logo Skyforge NSFW.png" alt="SKYFORGE" width="900">
</p>

# SKYFORGE

Projet personnel de création d’un modpack **Skyrim Special Edition 1.5.97** basé sur une fusion raisonnée entre les références **Nolvus Awakening** et **Nefaram**.

SKYFORGE vise une installation Skyrim stable, cohérente et documentée étape par étape, avec une approche prudente : installation progressive, tests réguliers, décisions différées quand un choix dépend de modules futurs, et validation explicite avant toute mise à jour structurelle.

---

## Suivre l’avancement du projet

### ➜ [Lire le dernier changelog / résumé de validation](docs/procedure/99_changelog_validation_part_14.md)

C’est le meilleur point d’entrée pour suivre l’évolution récente du modpack : dernières étapes validées, modules terminés ou en cours, décisions importantes, état de stabilité et prochaine reprise.

> Le changelog précédent reste disponible ici : [Changelog / validation — partie 13](docs/procedure/99_changelog_validation_part_13.md).  
> Le changelog historique principal reste disponible ici : [Changelog / validation — partie 1](docs/procedure/99_changelog_validation.md).

### Liens de reprise prioritaires

* [Résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 450](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md)
* [Module 10 — Gameplay, combat, magic & perks — partie 4](docs/procedure/10_gameplay_combat_magic_perks_part_4.md)
* [Vigilances Body / Skins / BodySlide](docs/configuration/08_body_skins_bodyslide_vigilances.md)
* [Procédure principale de reproduction](docs/SKYFORGE_Procedure_Reproduction_PC.md)

### Snapshots historiques utiles

* [Snapshot Load Order MO2 — panneau gauche — étape 434](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_434.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 409](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md)
* [État MO2 ciblé — blocs 09 / 10 — étape 409](docs/configuration/SKYFORGE_Load_Order_MO2_blocs_09_10_etape_409.md)
* [Snapshot Load Order MO2 — panneau gauche — étape 401](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_401.md)

Ces snapshots plus anciens sont conservés comme jalons historiques. Le snapshot courant de comparaison anti-doublon est celui de l’**étape 450**.

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

* **Dernière étape documentée :** Étape 450 — clôture provisoire du bloc `10 - GAMEPLAY COMBAT MAGIC PERKS`
* **Prochaine étape attendue :** Étape 451 — ouverture / audit du bloc `10.1 - RACES WEREBEASTS VAMPIRES`
* **Snapshot MO2 courant :** [panneau gauche étape 450](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md)
* **Compteur ESP + ESM non-light post-450 :** 110
* **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
* **AE / Creation Club :** conservé
* **MO2 :** portable
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **BodySlide Output :** non généré
* **Pandora :** généré depuis l’étape 411, Output actif ; ne pas relancer sauf demande explicite ou besoin technique
* **Mods `- FR` personnels :** présents dans le panneau gauche mais décochés sauf indication contraire explicite

L’état exact le plus récent est toujours consigné dans le [résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md), le [dernier changelog](docs/procedure/99_changelog_validation_part_14.md) et le [snapshot MO2 courant](docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md).

---

## Règles de lecture importantes

* Le snapshot **étape 450** est la référence courante pour vérifier si un mod est déjà installé.
* Les snapshots **401**, **409** et **434** sont des jalons historiques, pas des références courantes anti-doublon.
* Les mods dont le nom se termine par `- FR` sont des traductions personnelles et restent décochés tant que le modpack n’est pas stabilisé.
* Certains séparateurs sont volontairement vides : ils préparent les modules futurs et ne doivent pas être interprétés comme des erreurs.
* Les mentions `A REINSTALLER PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `A COMPLETER PLUS TARD`, `DECOCHE`, `RESERVE` ou équivalentes font partie de la nomenclature MO2 SKYFORGE.
* Les mises à jour GitHub sont effectuées uniquement quand Fabien le décide.

---

## Objectif

Construire une installation Skyrim stable, cohérente et patchée proprement :

- **Nolvus Awakening** sert de référence principale pour le socle technique, graphique, gameplay, UI, monde, villes, quêtes, combat, magie et confort gameplay léger.
- **Nefaram** sert de référence majeure pour les futurs systèmes spécialisés, la cohérence Body / tenues / BodySlide, les bases corporelles et les compatibilités adultes différées.

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

Les choix techniques peuvent évoluer au fur et à mesure de l’installation des modules suivants : races, lycanthropie, vampires, quêtes, followers, survie, systèmes spécialisés, tenues, BodySlide, patches finaux, LOD et DynDOLOD.
