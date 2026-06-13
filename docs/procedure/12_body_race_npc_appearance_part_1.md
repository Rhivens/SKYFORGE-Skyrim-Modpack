# 08 - BODY RACE NPC APPEARANCE - Partie 1

## Note de priorite - Module 08 BODY / RACE / NPC

### Objectif
Basculer la priorite du module 08 vers la logique Nefaram, tout en conservant la stabilite SKYFORGE.

### Decision
Pour le module 08 - BODY RACE NPC APPEARANCE, Nefaram devient la reference principale pour :

- corps / body ;
- RaceMenu / presets ;
- skins ;
- cheveux / yeux / brows ;
- visual NPC ;
- body physics ;
- overlays / tattoos si necessaires ;
- bases compatibles SexLab.

### Regle SKYFORGE

- Nefaram prioritaire pour tout ce qui touche au corps, au visuel NPC, au NSFW-ready et au SexLab-ready.
- Nolvus reste consulte pour ne pas perdre des ameliorations utiles ou des patches coherents.
- Aucun bloc adulte complet maintenant : preparation de la base corporelle/visuelle uniquement.
- Installation progressive, petits packs, test SKSE/menu apres chaque groupe.
- Etat de depart module 08 : 85 ESP + ESM non-light.

---

## Etape 376 - Audit module 08 BODY / RACE / NPC

### Objectif
Preparer le module 08 avec Nefaram comme reference principale pour corps, visuels NPC et base SexLab-ready.

### Verdict general
Ne pas installer tout le bloc d'un coup. Nefaram contient un ensemble coherent mais sensible : NPC overhauls, High Poly Head, cheveux, yeux, overlays, CBBE 3BA, HIMBO/TNG, OBody, BodySlide et skins.

### Decoupage retenu

- 08.1 Core character tools : RaceMenu / High Poly Head / Expressive Facegen / BodySlide.
- 08.2 Hair, eyes, brows, overlays : KS Hairdos, yeux, sourcils, maquillages, overlays.
- 08.3 Body base : CBBE 3BA, CBPC, HIMBO / The New Gentleman, textures homme/femme.
- 08.4 OBody + presets : OBody NG, presets BodySlide, sortie BodySlide plus tard.
- 08.5 NPC visual overhauls : Botox, High Poly NPC Overhaul, Pandorable, Bijin, Kalilies, Interesting NPCs, Citizens, etc.

### Risques principaux

- Black face bug si ordre NPC / facegen / patches incorrect.
- Conflits de corps si CBBE 3BA, HIMBO, TNG ou textures sont melanges trop vite.
- BodySlide Output a ne pas generer trop tot.
- OBody a differer apres base corps stable.
- Presets et overlays nombreux : utiles, mais pas prioritaires pour la stabilite.

---

## Etape 377 - 08.1 CORE CHARACTER TOOLS pack 1

### Objectif
Installer le socle leger Nefaram/Nolvus pour tetes, morphs et BodySlide, sans toucher aux corps complets ni aux NPC overhauls.

### Mods installes

- Expressive Facegen Morphs SE - CHOIX NEFARAM/NOLVUS.
- BodySlide and Outfit Studio - CHOIX NEFARAM/NOLVUS.
- High Poly Head SE - CHOIX NEFARAM.
- High Poly Head UV Stretch Fix - CHOIX NEFARAM.

### Actions validees

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 87.

### Notes conservees

- BodySlide v5.8.1 installe.
- BodySlide ajoute comme executable MO2.
- BodySlide Output non cree, generation differee.
- Outfit Studio executable differe, a ajouter en fin de modpack si besoin.
- High Poly Head SE : FOMOD Nolvus valide.
- High Poly Head UV Stretch Fix installe apres High Poly Head.

---

## Etape 378 - 08.1 CORE CHARACTER TOOLS pack 2 : base cheveux vanilla

### Objectif
Completer le socle personnage avec les cheveux vanilla ameliores et FSMP, sans installer les gros packs KS/Dint/SMP NPC.

### Mods installes

- Flawn's Vanilla Argonians Redux - CHOIX NEFARAM, source Nexus retenue.
- Vanilla Hair Remake - version SMP.
- FSMP - Faster HDT-SMP.
- High Poly Vanilla Hair.
- Vanilla Hair - Salt and Wind.

### FSMP - configuration validee

- Skyrim version : 1.5.97.
- CUDA : NOT CUDA.
- AVX : AVX2.
- MCM : FSMPM installe.
- CPU i9-14900K : AVX2 valide.

### Actions validees

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 89.

### Notes conservees

- Flawn's Vanilla Argonians Redux : main file installe, options body differees.
- FSMP place dans 09 - ANIMATIONS SKELETON PHYSICS.
- Vanilla Hair Remake SMP retenu pour PJ avec cheveux SMP.
- SMP NPC crash fix non installe, sauf besoin futur si version SMP NPC utilisee.

---

## Etape 379 - 08.2 debut HAIR / EYES / BROWS / OVERLAYS et incident Children

### Objectif
Tester le debut du sous-bloc 08.2 avec priorite Nefaram, mais remplacer Children par Nolvus suite a blocage.

### Mods valides dans le pack

- Conditional Expressions - Subtle Face Animations.
- Conditional Expressions Extended.
- Les elements de l'etape 378 restent valides.

### Incident Children

Bloc teste puis supprime de MO2 :

- TK Children SE.
- Simple Children.
- Simple Children - Updated Textures.
- Simple Children Patch Collection.

### Constat

- Blocage au chargement avant menu principal.
- Pas de crash.
- Patch Collection non responsable.
- Conditional Expressions non responsable.
- FSMP / cheveux SMP non responsables.
- Responsable confirme : Simple Children.
- Test avec TKChildren.esp et TKChildren.esm decoches : blocage toujours present.

### Decision conservee

- Simple Children - EXCLU.
- Motif : bloque au chargement avant menu.
- Bloc supprime de MO2.
- Remplacement valide : RS Children Overhaul, reference Nolvus.

### Validation apres nettoyage

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 89.

---

## Etape 379B - Remplacement Children : RS Children Overhaul

### Objectif
Remplacer la base enfants Nefaram instable par RS Children Overhaul cote Nolvus, teste seul sans patches.

### Mod installe

- RS Children Overhaul - CHOIX NOLVUS.

### Actions validees

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 91.
- FOMOD RS Children : aucune case cochee.

### Notes conservees

- RS Children Overhaul - CHOIX NOLVUS - A REINSTALL PLUS TARD.
- Installe seul, sans patches : pas USSEP, pas BS Bruma, pas Playable, pas ECE, pas Vampire Script Fix.
- Simple Children - EXCLU, remplace par RS Children Overhaul.

---

## Etape 380 - 08.2 pack 3 : KS Hairdos

### Objectif
Ajouter la base cheveux KS Hairdos cote Nefaram, maintenant que FSMP est valide.

### Mods installes

- KS Hairdos SSE.
- Hair Suppression Fix.
- KS Hairdos - HDT SMP Physics.
- Chooey's KS Hairdos and Vanilla Hair Retexture.
- Chooey's KS Hairdos Retexture - HDT-SMP Addon.

### Actions validees

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 92.

### Notes conservees

- KS Hairdos SSE installe.
- KS Hairdos - HDT SMP Physics installe.
- Hair Suppression Fix installe.
- Chooey Retexture : Vanilla Match choisi.
- FSMP deja valide : 1.5.97 / NOT CUDA / AVX2 / FSMP MCM installe.

---

## Etape 381 - 08.2 pack 4 : Dint Hair + BDOR Hairs

### Objectif
Continuer avec les gros packs cheveux SMP utilises par Nefaram.

### Mods installes

- [Dint999] HairPack02 SSE 1.11 - CHOIX NEFARAM.
- [Dint999] BDOR Hairs SSE 0.24 - CHOIX NEFARAM.

### Actions validees

- SKSE/menu principal : OK.
- Masters manquants : aucun.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 94.

### Notes conservees

- HairPack02 source : lien manuel GitHub Nefaram.
- BDOR Hairs source : fichiers Dint999.
- Autres fichiers Dint non installes : DemonArmor, FacePartMod, Magic Nails, Meridas Outfit, RedguardHairs, SSE First CBBE Body Physics, Animated Animal Tails.

---

## Etape 382 - 08.2 pack 5 : Citizens Visual + EFA

### Objectif
Finaliser la partie expressions / visages apres les packs Dint.

### Mods installes

- Expressive Facial Animation - Male Edition.
- Expressive Facial Animation - Female Edition.

### Actions validees

- SKSE/menu principal : OK.
- Aucun master manquant : OK.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 94.

### Notes conservees

- EFA Female : option Fair Skin Complexion reperee mais differee jusqu'au bloc skins.
- Citizens of Tamriel Visual Overhaul - DIFFERE.
- Source officielle reperee : Craftian itch.io / citizens-of-tamriel.
- Citizens a reprendre plus tard apres choix Citizens standalone vs ezPG.
- Le visual overhaul doit etre installe apres le mod original.

---

## Etape 383 - 08.2 pack yeux / sourcils

### Objectif
Installer le premier pack yeux / sourcils du sous-bloc 08.2, avec correction des liens et options differees.

### Mods installes

- The Eyes Of Beauty SSE - CHOIX NEFARAM / NOLVUS.
- Kala's Eyes - CHOIX NEFARAM / NOLVUS.
- The Eyes of Beauty - Vampire Eyes SE - CHOIX NEFARAM / NOLVUS - PATCHES A VOIR PLUS TARD.
- Kalilies Brows - CHOIX NEFARAM / NOLVUS.

### Corrections de liens conservees

- Kala's Eyes : https://www.nexusmods.com/skyrimspecialedition/mods/29895
- Kalilies Brows : https://www.nexusmods.com/skyrimspecialedition/mods/40595

### Details d'installation

- Kala's Eyes : main file + update 1.2 + ESL Plugin.
- The Eyes of Beauty - Vampire Eyes SE : main file seulement.
- Kalilies Brows : pas de patch HPH / COTR / UBE maintenant.

### Differes / non installes

- OBody NG : differe jusqu'au bloc body / 3BA / HIMBO.
- Dynamic Vampire Appearance : differe.
- Kala's Vampire Eyes : differe.
- HN66s Long Eye Lashes : differe.
- More High Poly Head Eyebrow Patch Hub : differe.
- Reflective ENB Eyebrows Fix : differe.
- Patches sourcils HPH / COTR / UBE : differes.

### Actions validees

- SKSE/menu principal : OK.
- Aucun master manquant : OK.
- Plugins coches : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : 95.

---

## Etat final de cette partie

- Derniere etape validee : Etape 383.
- Module en cours : 08 - BODY RACE NPC APPEARANCE.
- Sous-bloc en cours : 08.2 - HAIR / EYES / BROWS / OVERLAYS.
- Compteur ESP + ESM non-light : 95.
- SKSE/menu principal : OK.
- Aucun master manquant.
- Plugins coches.
- Overwrite vide.
- LOOT non lance.
- DynDOLOD / LOD non generes.
