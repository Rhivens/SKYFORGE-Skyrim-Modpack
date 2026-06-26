# Characters, hair, body, skins & BodySlide — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture et validation provisoire du module **08 - Characters / Hair / Body / Skins / BodySlide**.

Périmètre : étapes **656 à 658**.

Important : ces étapes sont des validations courtes sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 656 — Ouverture opérationnelle du bloc 08

### État constaté

Le bloc 08 est déjà installé en grande partie. Le panneau gauche contient trois sous-blocs :

- `[08.1 - CORE CHARACTERS TOOLS]`
- `[08.2 - HAIR-EYES-BROWS-OVERLAYS]`
- `[08.3 - BODY - SKINS - BODYSLIDE]`

Le panneau droit confirme déjà les plugins principaux du bloc 08, notamment :

- `Expressive Facegen Morphs.esl`
- `High Poly Head.esm`
- `High Poly Head Vampire Fix.esp`
- `FlawnsArgonians - Eyes, Replacer Plus.esp`
- `FlawnsArgonians - NPCs, Flawns Edits.esp`
- `Conditional Expressions.esp`
- `RSChildren.esp`
- `RSkyrimChildren.esm`
- `KS Hairdo's.esp`
- `KSHairdosSMP.esp`
- `[dint999] HairPack02.esp`
- `[Dint999] BDOr_Hairstyles.esp`
- `TheEyesOfBeauty.esp`
- `Kala_Eyes.esp`
- `KaliliesBrows.esp`
- `CommunityOverlays1_0T30.esp`
- `CommunityOverlays2_31T50.esp`
- `SFO_SkinFeatureOverlays.esp`
- `FMS_FemaleMakeupSuite.esp`
- `CommunityOverlays3.esp`
- `CBBE.esp`
- `3BBB.esp`
- `RaceMenuMorphsCBBE.esp`
- `TheNewGentleman.esp`
- `BnP - Skinfix.esp`

### Décision

- Étape 656 = ouverture / validation courte du bloc 08.
- Aucun changement MO2.
- Aucun test SKSE requis maintenant.
- Compteur conservé : **138**.
- BodySlide Output toujours non généré.
- Ne pas toucher encore à CBBE / 3BA / The New Gentleman tant que le body final n’est pas repris.

---

## Étape 657 — Validation groupée courte `[08.1]` + `[08.2]`

### Sous-blocs concernés

`[08.1 - CORE CHARACTERS TOOLS]` contient déjà :

- Expressive Facegen Morphs SE
- BodySlide and Outfit Studio
- High Poly Head SE
- High Poly Head UV Stretch Fix

`[08.2 - HAIR-EYES-BROWS-OVERLAYS]` contient déjà les bases cheveux / yeux / brows / overlays :

- Flawn’s Vanilla Argonians Redux
- Vanilla Hair Remake / High Poly Vanilla Hair / Salt and Wind
- Conditional Expressions
- RS Children Overhaul marqué à réinstaller plus tard
- KS Hairdos / KS Hairdos SMP
- Dint999 HairPack / BDOR Hairs
- Expressive Facial Animation
- The Eyes of Beauty / Kala’s Eyes / Kalilies Brows
- Community Overlays / SkFO / Female Makeup Suite / Yyvengar / Sakora / Lyru

### Plugins actifs relevés

- `Expressive Facegen Morphs.esl`
- `High Poly Head.esm`
- `High Poly Head Vampire Fix.esp`
- `FlawnsArgonians - Eyes, Replacer Plus.esp`
- `FlawnsArgonians - NPCs, Flawns Edits.esp`
- `Conditional Expressions.esp`
- `RSChildren.esp`
- `RSkyrimChildren.esm`
- `KS Hairdo's.esp`
- `KSHairdosSMP.esp`
- `KSWigsSMP.esp`
- `[dint999] HairPack02.esp`
- `[Dint999] BDOr_Hairstyles.esp`
- `TheEyesOfBeauty.esp`
- `Kala_Eyes.esp`
- `KaliliesBrows.esp`
- `CommunityOverlays1_0T30.esp`
- `CommunityOverlays2_31T50.esp`
- `SFO_SkinFeatureOverlays.esp`
- `FMS_FemaleMakeupSuite.esp`
- `CommunityOverlays3.esp`
- `Lupine_YyvengarBodypaints.esp`
- `Sakora's Make Over Kit for SKSE64.esp`
- `LyruTat.esp`

### Décision

- Garder / validation groupée courte.
- Aucun changement actif.
- Aucun test SKSE requis maintenant.
- Dernier SKSE/menu déjà OK.
- Aucun master manquant.
- Aucun message DLL.
- Overwrite vide.
- Compteur non-light toujours **138**.

### Dettes à conserver

- `RS Children Overhaul - CHOIX NOLVUS - A REINSTALL PLUS TARD`.
- `The Eyes of Beauty - Vampire Eyes SE - PATCHES A VOIR PLUS TARD`.
- `Community Overlays 2` = choix provisoire CBBE + male, à revoir si body final change.
- SkFO et Female Makeup Suite installés plus tôt que prévu, à revoir au bloc skins.
- Traductions `- FR` en attente, pas une erreur.

---

## Étape 658 — `[08.3 - BODY - SKINS - BODYSLIDE]`

### État constaté

Le sous-bloc 08.3 est déjà en place avec :

- `Caliente's Beautiful Bodies Enhancer - CBBE - MORPHS RACEMENU NON INSTALLES - A REVOIR AVEC 3BA OBODY BODYSLIDE`
- `RoughSpun Tunic and Prisoner Bloody Fix`
- `CBBE 3BA (3BBB) - A REINSTALL PLUS TARD - OPTIONS SOS COLLISIONS`
- `The New Gentleman - PATCHES A VOIR PLUS TARD`
- `The New Gentleman - Generated INI`
- `PB's Silky Skin - SKIN PJ UNIQUEMENT A TERME - ACTUELLEMENT ECRASEE PAR BNP - A ISOLER PLUS TARD`
- `Tempered Skins for Males - SOS Full Version`
- `BnP female skin (Replacer+Player version)`
- `BnP female small update`

### Plugins actifs relevés

- `CBBE.esp`
- `3BBB.esp`
- `RaceMenuMorphsCBBE.esp`
- `SOSPhysicsManager.esp`
- `TheNewGentleman.esp`
- `BnP - Skinfix.esp`

### Décision

- Validation provisoire.
- Ne rien réinstaller maintenant.
- Le bloc Body touche à la future base Body / SexLab et doit être repris proprement plus tard.
- CBBE conservé comme base.
- 3BA / 3BBB conservé comme direction officielle.
- The New Gentleman conservé comme corps masculin retenu.
- BnP female skin actuellement actif.
- Tempered Skins for Males présent côté gauche.
- BodySlide Output toujours non généré.

### Ne pas faire maintenant

- Ne pas réinstaller CBBE.
- Ne pas réinstaller 3BA.
- Ne pas générer BodySlide.
- Ne pas modifier The New Gentleman.
- Ne pas isoler PB’s Silky Skin maintenant.
- Ne pas toucher aux options SOS collisions maintenant.
- Ne pas lancer Pandora.

### Dettes

- Reprendre CBBE + RaceMenu morphs avec 3BA / OBody / BodySlide.
- Réinstaller / vérifier 3BA plus tard avec options SOS collisions.
- Reprendre The New Gentleman patches.
- Isoler PB’s Silky Skin à terme si skin joueur uniquement retenu.
- Générer BodySlide Output seulement quand le bloc Body / outfits sera stabilisé.
- Garder compatibilité future SexLab / Devious / NSFW.

### État final bloc 08

- Bloc 08 validé provisoirement.
- Aucun changement actif dans MO2.
- SKSE/menu : OK sur le dernier test global.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **138**.
- BodySlide Output : **non généré**.
