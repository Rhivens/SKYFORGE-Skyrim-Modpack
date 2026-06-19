# SKYFORGE — Vigilances Body / Skins / BodySlide

## Objet du fichier

Ce fichier regroupe les notes techniques différées liées au futur bloc :

```text
[08.3 BODY- SKINS- BODYSLIDE]
```

Il sert de référence pour les décisions à ne pas perdre avant l'ouverture officielle du bloc Body / Outfits / BodySlide.

---

# Note future — PB's Silky Skin SKYFORGE Player Skin Override

## Contexte

Fabien a déjà rencontré dans Nolvus / Nefaram un problème de brillance excessive sur la skin du personnage joueur.

Ce problème peut apparaître lorsque certaines tenues, armures, body replacers ou textures écrasent la skin du PJ avec des textures trop brillantes.

## Symptôme

- skin du personnage joueur anormalement brillante ;
- effet `shiny` excessif ;
- rendu peu naturel sur le corps, les mains ou la tête ;
- problème surtout visible avec certaines tenues / armures ou certains body assets.

## Cause probable

Certaines tenues / armures / body replacers peuvent fournir ou écraser des textures de peau, notamment les textures spéculaires.

Fichiers à surveiller en priorité :

- `*_s.dds`
- specular maps du corps ;
- specular maps des mains ;
- specular maps de la tête.

## Décision SKYFORGE différée

Créer plus tard un mod dédié :

```text
PB's Silky Skin - SKYFORGE PLAYER SKIN OVERRIDE
```

## Rôle du mod futur

Ce mod devra servir d'override final pour la skin du personnage joueur afin d'éviter que des tenues / armures / body replacers installés ensuite n'imposent des specular maps trop brillantes.

## Placement logique futur

À décider lors du futur bloc Body / Outfits / BodySlide.

Principe recommandé :

- placer l'override skin PJ après les textures / bodies susceptibles d'écraser la skin ;
- le garder avant les outputs générés finaux si nécessaire ;
- vérifier l'interaction avec BodySlide Output et les éventuels presets ;
- ne pas l'activer / générer maintenant.

## Règles associées

- Ne pas lancer BodySlide pour l'instant.
- Ne pas générer de BodySlide Output pour l'instant.
- Ne pas imposer ce choix avant ouverture officielle du bloc Body / Outfits / BodySlide.
- Nefaram reste la référence principale pour les futurs blocs tenues, bikini, BodySlide et logique de cohérence des bodies.
- SKYFORGE pourra ajouter d'autres tenues ou variantes, mais la cohérence de base doit rester alignée sur Nefaram tant que Fabien ne décide pas officiellement d'un autre standard.

## Statut

- Décision notée.
- Installation différée.
- À reprendre lors du futur bloc Body / Outfits / BodySlide.
