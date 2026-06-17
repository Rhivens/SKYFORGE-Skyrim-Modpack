# Changelog / validation — partie 11

## Périmètre

Cette partie couvre la progression SKYFORGE des étapes **410 à 415**.

Elle concerne principalement :

- la vérification FOMOD combat / dodge avant Pandora ;
- la première génération Pandora contrôlée ;
- le diagnostic du crash apparu après génération Pandora ;
- l’isolation du mod fautif ;
- le nettoyage d’état et le retour à un profil stable ;
- la validation gameplay post-CTD et la levée de la vigilance Smooth TK Dodge Attack.

## État final validé

- **Dernière étape validée :** Étape 415 — Validation gameplay post-CTD
- **Séparateur actuellement ouvert :** 10 - GAMEPLAY COMBAT MAGIC PERKS
- **Séparateur précédent actif :** 09 - ANIMATIONS SKELETON PHYSICS
- **SKSE / menu principal :** OK
- **Test gameplay post-CTD :** OK, pas de crash reproduit lors du test limité
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

## Étapes validées — résumé synthétique

- **Étape 410 :** vérification FOMOD combat / dodge avant Pandora. TK Dodge RE confirmé en installation minimale. Precision revalidé avec option **TK Dodge or Ultimate Combat** sélectionnée, option TK Dodge RE grisée. Aucun nouveau mod installé. Compteur : 106.
- **Étape 411 :** première génération Pandora contrôlée. Correction du chemin Skyrim Data vers le Data utilisé par l’instance MO2 portable SKYFORGE. Génération réussie avec 42 animations ajoutées. Pandora Output actif. Compteur : 106.
- **Étape 412 :** diagnostic initial du crash après génération Pandora. Le problème n’est pas attribué directement à Pandora Output, TK Dodge RE, TDM ou RaceMenu. CrashLogger final corrigé / activé.
- **Étape 413 :** isolation du coupable. Le problème est lié à la chaîne New Gnisis Cornerclub / patch mobilier Dunmeri / Lux / Distinct Interiors / Snazzy / Skyrim Unbound. Le mod fautif confirmé est décoché.
- **Étape 414 :** nettoyage d’état. Overwrite vidé, CrashLogger actif, outil temporaire supprimé, EngineFixes restauré, profil stable restauré.
- **Étape 415 :** validation gameplay post-CTD. Aucun nouveau mod installé. Test limité OK. Vigilance **Smooth TK Dodge Attack à confirmer en jeu** levée. Compteur : 106.

## Décisions structurantes

- Pandora Behaviour Engine Plus reste le générateur retenu pour SKYFORGE.
- Nemesis n’est pas retenu comme générateur principal.
- Les réglages TK Dodge RE doivent être des réglages SKYFORGE propres, inspirés de la logique Nolvus Awakening mais adaptés au modpack.
- Ne pas dépendre des fichiers Nolvus Awakening locaux pour les réglages, sauf besoin ultérieur de comparaison avancée.
- CrashLogger SSE AE VR complet + PDB support 1.5.97 est le système de crash logging retenu.
- Trainwreck n’est plus actif après diagnostic.

## Mod fautif confirmé

Le crash post-Pandora a été isolé.

Mod à garder décoché / différé :

```text
Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD
```

## EngineFixes

Les options temporairement désactivées ont été restaurées :

```ini
bFormCaching = true
bTreeLodReferenceCaching = true
```

Le test après restauration n’a pas reproduit le crash.

## Vigilances levées

- Pandora installé mais non généré : levée à l’étape 411.
- Smooth TK Dodge Attack à confirmer en jeu : levée à l’étape 415.

## Vigilances restantes

- BodySlide Output non généré.
- XPMSSE FOMOD à revoir plus tard avant SexLab / animations avancées.
- LeveledList Crash Fix AE + 1.5 à vérifier hors urgence.
- LOOT non lancé.
- DynDOLOD / LOD non générés.
- Mods `- FR` toujours volontairement décochés.

## Références détaillées

Pour le détail complet des étapes :

- `docs/procedure/10_validation_gameplay_post_ctd_etape_415.md`
- `docs/procedure/09_animations_skeleton_physics_part_2.md`
- `docs/procedure/10_stabilisation_etape_412_414.md`
- `docs/procedure/09_animations_skeleton_physics_part_1.md`
- `docs/procedure/10_gameplay_combat_magic_perks_part_1.md`
- `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_409.md`
