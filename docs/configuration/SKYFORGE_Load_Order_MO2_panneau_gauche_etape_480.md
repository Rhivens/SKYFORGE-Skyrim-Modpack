# SKYFORGE — Load Order MO2 — panneau gauche — étape 480

Snapshot de référence du panneau gauche MO2 après validation de l'étape 480.

> Note technique : le snapshot brut complet fourni par Fabien contient des séparateurs et noms de mods issus de futurs blocs spécialisés. Pour éviter les blocages d'écriture du connecteur GitHub, ce fichier documente la reprise post-480 sous forme consolidée : les blocs inchangés restent couverts par le snapshot étape 450, et les blocs modifiés depuis l'étape 450 sont reproduits ci-dessous.

## Statut

- **Dernière étape couverte :** Étape 480 — SPID NPC Trap Safety / audit doublon NPC AI Process Position Fix
- **Compteur ESP + ESM non-light communiqué :** 119
- **Rôle du fichier :** référence courante anti-doublon pour les reprises après l'étape 480
- **Remplace comme référence courante :** `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md`
- **Snapshots précédents :** conservés comme jalons historiques uniquement

## Règles de lecture

- Les mods dont le nom se termine par `- FR` sont des traductions personnelles et restent décochés sauf indication contraire explicite.
- Certains séparateurs sont volontairement vides : ils préparent les modules futurs et ne sont pas des anomalies.
- Les mentions `A REINSTALLER PLUS TARD`, `PATCHES A VOIR PLUS TARD`, `A COMPLETER PLUS TARD`, `DECOCHE`, `RESERVE`, `FOMOD A REVOIR PLUS TARD` ou équivalentes font partie de la nomenclature MO2 SKYFORGE.
- Le panneau gauche MO2 ne permet pas de recalculer seul le compteur ESP + ESM non-light : le compteur est celui communiqué par Fabien depuis le panneau droit MO2.

## Blocs inchangés depuis le snapshot 450

Pour les blocs suivants, utiliser le snapshot étape 450 comme base de comparaison :

- `[00 - BASE GAME]`
- `[01 - SKSE PLUGINS & CORE UTILITIES]`
- `[02 - BUG FIXES & ENGINE PATCHES]`
- `[03 - UI HUD MENUS]`
- `[04 - AUDIO MUSIC VOICES]`
- `[05 - VISUAL BASE MESHES TEXTURES]`
- `[05.1 - PARALLAX FRAMEWORK TEXTURES]`
- `[06 - LANDSCAPE GRASS TREES WATER]`
- `[07 - CITIES TOWNS INTERIORS LIGHTING]`
- `[07.1 - PLAYER HOMES]`
- `[07.2 - FARMHOUSES]`
- `[07.3 - OTHER LOCATIONS]`
- `[07.4 - LANDS]`
- `[07.5 - RUINS]`
- `[07.6 - INTERIORS]`
- `[08.1 - CORE CHARACTERS TOOLS]`
- `[08.2 - HAIR-EYES-BROWS-OVERLAYS]`
- `[08.3 - BODY - SKINS - BODYSLIDE]`
- `[09 - ANIMATIONS SKELETON PHYSICS]`
- `[10 - GAMEPLAY COMBAT MAGIC PERKS]`

Référence historique complète : `docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_450.md`.

## Blocs modifiés / nouveaux depuis l'étape 450

```txt
[10.1 - RACES WEREBEASTS VAMPIRES]
Aetherius - A Race Overhaul - FOMOD A REVOIR PLUS TARD
Aetherius - Race Menu Racial Passive Descriptions
Mundus - A Standing Stone Overhaul
Sacrosanct - Vampires of Skyrim
Cover Your Head - Sacrosanct
Sun Affects NPC Vampires
Manbeast - A Werewolf Overhaul

[11 - QUESTS WORLDS FOLLOWERS]

[11.1 - FOLLOWERS NPCS DIALOGUES]
Bandit Lines Expansion
Civil War Lines Expansion
Forsworn and Thalmor Lines Expansion
Vampire Lines Expansion
Brawl Lines Expansion and Fixes
NPCs React To Necromancy (And More)
NPCs React To Invisibility
Bow of Shadows (CC) - Invisibility Patch
NPCs React To Frenzy
Carriages and Stables Dialogue Bundle
Show NPC Disposition Relationship Rank
Dialogue Window Auto Close Exit Begone
Scared of Shootings - NPCs react to aiming bows
Dialogue Expansion - Windhelm
Dialogue Expansion - Shor's Stone
Dialogue Expansion - Khajiit Caravans
Neutral Whiterun Guards
Truly Neutral Prisoners
More Sensible Quartermasters
Robber's Gorge Fixes - FOMOD À REVOIR PLUS TARD
Guard Dialogue Overhaul SE
Guard Dialogue Overhaul MCM
GuardsTalk
Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD
More Dialogue Options - FOMOD À REVOIR PLUS TARD
Relationship Dialogue Overhaul - RDO SE
Cutting Room Floor - FOMOD À REVOIR PLUS TARD
RDO - CRF and USSEP Patches Final
AI Overhaul SSE - FOMOD À REVOIR PLUS TARD
AI Overhaul - Relationship Dialogue Overhaul Patch
AI Overhaul - Cutting Room Floor Patch
Run For Your Lives
Realistic Conversations
SPID NPC Trap Safety
```

## Séparateurs suivants visibles dans le panneau gauche

Ces séparateurs existent déjà dans MO2 et peuvent être vides ou partiellement vides selon l'avancement :

```txt
[12 - SURVIVAL IMMERSION ROLEPLAY]
[13 - CORE SPECIALIZED FRAMEWORKS]
[13.1 - ANIMATION RESOURCES]
[14 - FUTURE SPECIALIZED SYSTEMS]
[15 - ARMORS CLOTHES OUTFITS]
[15.1 - BODYSLIDE OUTPUTS OUTFITS]
[16 - PATCHES CONFLICT RESOLUTION]
[17 - DYNDOLOD OUTPUTS GENERATED FILES]
[18 - TOOLS OUTPUTS]
[19 - TRADUCTIONS FR]
Overwrite
```

## Décisions de placement importantes

- `Aetherius`, `Mundus`, `Sacrosanct`, `Cover Your Head - Sacrosanct`, `Sun Affects NPC Vampires` et `Manbeast` appartiennent au bloc `[10.1 - RACES WEREBEASTS VAMPIRES]`.
- `Vampire Lines Expansion` est placé dans `[11.1 - FOLLOWERS NPCS DIALOGUES]`, pas dans `10.1`, car il concerne les dialogues NPC.
- `Cutting Room Floor` est installé dans le bloc `11.1` dans l'état actuel, car il a été introduit pour résoudre le patch RDO / CRF / USSEP.
- `AI Overhaul SSE`, ses patches RDO / CRF, `Run For Your Lives`, `Realistic Conversations` et `SPID NPC Trap Safety` sont documentés dans le bloc `11.1` / NPC AI & dialogues.

## Dernier état technique associé

- Dernière étape validée : 480
- Compteur ESP + ESM non-light : 119
- Overwrite : vide
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- BodySlide Output : non généré
- Pandora : non relancé pendant les étapes 451 à 480
