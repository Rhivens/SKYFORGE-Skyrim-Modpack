<p align="center">
  <img src="assets/branding/Logo Skyforge NSFW.png" alt="SKYFORGE" width="900">
</p>

# SKYFORGE

Projet personnel de création d’un modpack **Skyrim Special Edition 1.5.97** basé sur une fusion raisonnée entre les références **Nolvus** et **Nefaram**.

SKYFORGE vise une installation Skyrim stable, cohérente, documentée étape par étape, avec une approche prudente : installation progressive, tests réguliers, décisions différées quand un choix dépend de modules futurs.

---

## Suivre l’avancement du projet

### ➜ [Lire le dernier changelog / résumé de validation](docs/procedure/99_changelog_validation_part_9.md)

C’est le meilleur point d’entrée pour suivre l’évolution actuelle du modpack : dernières étapes validées, modules terminés ou en cours, décisions importantes, état de stabilité et prochaine reprise.

> Le changelog précédent reste disponible ici : [Changelog / validation — partie 8](docs/procedure/99_changelog_validation_part_8.md).
> Le changelog historique principal reste disponible ici : [Changelog / validation — partie 1](docs/procedure/99_changelog_validation.md).

### Liens utiles

* [Résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md)
* [Procédure principale de reproduction](docs/SKYFORGE_Procedure_Reproduction_PC.md)
* [Ajouts personnels SKYFORGE](docs/procedure/96_ajouts_personnels_skyforge.md)
* [Registre central de dette technique](docs/procedure/97_registre_dette_technique.md)
* [Registre central de dette technique — partie 2](docs/procedure/97_registre_dette_technique_part_2.md)
* [Module 07 — Cities, towns, interiors & lighting](docs/procedure/11_cities_towns_interiors_lighting.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 2](docs/procedure/11_cities_towns_interiors_lighting_part_2.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 3](docs/procedure/11_cities_towns_interiors_lighting_part_3.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 4](docs/procedure/11_cities_towns_interiors_lighting_part_4.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 5](docs/procedure/11_cities_towns_interiors_lighting_part_5.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 6](docs/procedure/11_cities_towns_interiors_lighting_part_6.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 7](docs/procedure/11_cities_towns_interiors_lighting_part_7.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 8](docs/procedure/11_cities_towns_interiors_lighting_part_8.md)
* [Module 07 — Cities, towns, interiors & lighting — partie 9](docs/procedure/11_cities_towns_interiors_lighting_part_9.md)
* [Module 08 — Body, race & NPC appearance — partie 1](docs/procedure/12_body_race_npc_appearance_part_1.md)
* [Module 08 — Body, race & NPC appearance — partie 2](docs/procedure/12_body_race_npc_appearance_part_2.md)
* [Décisions différées et points à revoir](docs/procedure/06_decisions_differees.md)
* [Décisions différées — partie 2](docs/procedure/06_decisions_differees_part_2.md)
* [Décisions différées — partie 3](docs/procedure/06_decisions_differees_part_3.md)
* [Décisions différées — partie 4](docs/procedure/06_decisions_differees_part_4.md)
* [Décisions différées — partie 5](docs/procedure/06_decisions_differees_part_5.md)
* [Changelog / validation — partie 6](docs/procedure/99_changelog_validation_part_6.md)
* [Changelog / validation — partie 7](docs/procedure/99_changelog_validation_part_7.md)
* [Changelog / validation — partie 8](docs/procedure/99_changelog_validation_part_8.md)
* [Changelog / validation — partie 9](docs/procedure/99_changelog_validation_part_9.md)
* [Audit de continuité des étapes](docs/procedure/98_audit_continuite_etapes.md)

---

## État actuel

* **Dernière étape validée :** Étape 401 — Ajout CBPC pour 3BA
* **Dernière étape d’installation validée :** Étape 401 — Ajout CBPC pour 3BA
* **Module en cours :** 08 - BODY RACE NPC APPEARANCE
* **Sous-bloc en cours :** 08.3 - BODY / SKINS / BODYSLIDE
* **Bloc physique lié :** 09 - ANIMATIONS SKELETON PHYSICS ouvert ponctuellement pour FSMP / CBPC
* **Prochaine étape attendue :** suite du bloc 08.3 ou préparation contrôlée BodySlide / presets / OBody / isolation skin PJ
* **Compteur ESP + ESM non-light :** 102
* **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
* **AE / Creation Club :** conservé
* **LOOT :** non lancé
* **LOD / DynDOLOD :** non générés
* **BodySlide Output :** non généré

L’état exact le plus récent est toujours consigné dans le [dernier changelog](docs/procedure/99_changelog_validation_part_9.md) et dans le [résumé de l’état actuel](docs/procedure/00_resume_etat_actuel.md).

Le suivi des ajouts personnels est centralisé dans le [catalogue des ajouts personnels SKYFORGE](docs/procedure/96_ajouts_personnels_skyforge.md).
Le suivi des éléments à reprendre plus tard est centralisé dans le [registre de dette technique](docs/procedure/97_registre_dette_technique.md) et sa [partie 2 dédiée aux ajouts personnels / tenues](docs/procedure/97_registre_dette_technique_part_2.md).

---

## Objectif

Construire une installation Skyrim stable, cohérente et patchée proprement :

- **Nolvus** sert de référence principale pour le socle technique, graphique, gameplay, UI, monde, villes, quêtes, combat et magie.
- **Nefaram** sert de référence majeure pour les systèmes avancés, immersion, roleplay, outfits, contraintes de compatibilité et les bases corporelles / visuelles compatibles SexLab-ready du module 08.

Le but n’est pas de copier deux modlists complètes, mais d’en extraire les idées, les méthodes et les systèmes utiles pour bâtir un modpack personnel maîtrisé.

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

Les choix techniques peuvent évoluer au fur et à mesure de l’installation des modules suivants : villes, éclairage, météo, ENB, animations, gameplay, quêtes, patches finaux, BodySlide, Pandora / Nemesis, LOD et DynDOLOD.
