# État actuel officiel — SKYFORGE

## Situation générale

- **Dernière étape validée :** Étape 414 — Nettoyage d’état après diagnostic stabilité
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **Module actif :** animations / dodge / combat léger Nolvus Awakening
- **Dernier profil stable :** étape 414
- **Prochaine étape attendue :** à déterminer après reprise depuis GitHub, sans nouvelle installation massive.

## État technique validé

- **Runtime :** Skyrim SE 1.5.97 Best of Both Worlds
- **AE / Creation Club :** conservé
- **MO2 :** portable
- **SKSE via MO2 :** OK
- **Menu principal :** OK
- **Test en jeu limité après restauration :** OK, pas de crash constaté
- **Masters manquants :** aucun
- **Messages DLL bloquants :** aucun signalé
- **Plugins cochés :** OK
- **Overwrite :** vide
- **Compteur ESP + ESM non-light :** 106
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** généré avec succès, Output actif
- **CrashLogger :** actif avec PDB support 1.5.97

## Fichiers de reprise prioritaires

À lire en priorité pour reprendre sans confusion :

1. `docs/procedure/00_resume_etat_actuel.md`
2. `docs/procedure/99_changelog_validation_part_11.md`
3. `docs/procedure/09_animations_skeleton_physics_part_2.md`
4. `docs/procedure/10_stabilisation_etape_412_414.md`
5. `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
6. `docs/procedure/09_animations_skeleton_physics_part_1.md`
7. `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`

## Étapes récentes validées

- **Étape 410 :** vérification FOMOD combat / dodge avant Pandora. TK Dodge RE confirmé en installation minimale. Precision revalidé avec option TK Dodge / Ultimate Combat. Aucun nouveau mod installé. Compteur 106.
- **Étape 411 :** première génération Pandora contrôlée. Chemin Skyrim Data corrigé vers le Data utilisé par l’instance MO2 portable SKYFORGE. Génération réussie avec 42 animations ajoutées. Pandora Output actif. Compteur 106.
- **Étape 412 :** diagnostic initial du crash post-Pandora. Crash logging corrigé avec CrashLogger complet + PDB support 1.5.97.
- **Étape 413 :** isolation du coupable. Mod fautif confirmé : `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`, à garder décoché / différé.
- **Étape 414 :** nettoyage d’état. Overwrite vidé, CrashLogger actif, outil temporaire supprimé, EngineFixes restauré, profil stable restauré.

## Décisions structurantes actuelles

- **Nolvus Awakening** est la référence principale pour combat / dodge / animations combat.
- **Nefaram** reste la référence principale pour Body compatible adulte / SexLab futur / systèmes adultes différés.
- **Pandora Behaviour Engine Plus** est le générateur retenu.
- **Nemesis** n’est pas retenu comme générateur principal.
- Les réglages TK Dodge RE doivent être des réglages SKYFORGE propres, inspirés de Nolvus Awakening mais adaptés au modpack.
- Ne pas dépendre des fichiers Nolvus Awakening locaux, sauf besoin futur de comparaison avancée.

## Règle anti-doublon SKYFORGE

Avant toute nouvelle proposition d’installation, vérifier dans GitHub :

- ce résumé d’état actuel ;
- le fichier thématique du module en cours ;
- le dernier changelog de validation ;
- le dernier snapshot / état MO2 documenté.

Ne jamais reproposer un mod déjà présent dans le snapshot ou les fichiers de procédure.

## Règle traductions personnelles FR

Tous les mods dont le nom se termine par `- FR` sont des traductions personnelles de Fabien.

Ces mods `- FR` restent volontairement **décochés pour le moment**, tant que le modpack n’est pas stabilisé.

Ils seront activés plus tard par petits groupes contrôlés, avec test SKSE / menu après chaque groupe.

Leur présence dans le panneau gauche MO2 ne doit pas être interprétée comme une erreur ou un oubli.

## Vigilances restantes

- **BodySlide Output :** non généré.
- **XPMSSE :** FOMOD à revoir plus tard avant SexLab / animations avancées / styles d’armes.
- **Smooth TK Dodge Attack :** à confirmer par test en jeu limité.
- **LeveledList Crash Fix AE + 1.5 :** à vérifier hors urgence.
- **LOOT :** non lancé.
- **DynDOLOD / LOD :** non générés.
- **Mods `- FR` :** toujours décochés volontairement.
- **Mod fautif CTD étape 413 :** `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD` doit rester décoché / différé.

## Mods explicitement décochés / différés à conserver

- `Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD`
- `Kris's Papyrus Extender - DECOCHE RESERVE`
- `ENB Extender Skyrim - DECOCHE RESERVE ENB`
- `Magic College Music - Songs for Academy - DECOCHE FORM 43`
- `Atlantean Landscape -Complete- 2K - A REINSTALL PLUS TARD`
- `Cities of the North - Morthal - DECOCHE CHOIX A REVOIR`
- `Scarecrows of Skyrim - BOS - SOS Patch - REQUIERT SIMPLICTY OF SNOW`
- `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB`
- tous les mods terminés par `- FR`

## Outils non lancés à ce stade

- LOOT
- DynDOLOD / LOD
- BodySlide

## Dernier état stable

Profil stable étape 414 :

- SKSE / menu principal : OK
- Test en jeu limité : OK
- Aucun master manquant
- Aucun message DLL bloquant
- Plugins cochés
- Overwrite vide
- EngineFixes restauré
- CrashLogger actif
- Pandora Output actif
- Compteur ESP + ESM non-light : 106
