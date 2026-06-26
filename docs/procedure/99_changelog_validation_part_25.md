# SKYFORGE — Changelog / validation — partie 25

Période couverte : étapes **656 à 685**.

Cette partie documente l’ouverture et les validations provisoires des blocs 08, 09, 10, 11 et 12, puis la préparation et l’installation du noyau **SexLab Core 13-A**.

Important : la majorité des étapes 656 à 681 sont des vérifications / audits documentaires sur des éléments déjà présents dans MO2. Les installations actives commencent réellement à l’étape **682** avec SexLab Core 13-A.

---

## Résumé global

### Étapes 656 à 658 — Bloc 08 Characters / Hair / Body

- Ouverture opérationnelle du bloc `[08]`.
- Validation courte des sous-blocs `[08.1 - CORE CHARACTERS TOOLS]`, `[08.2 - HAIR-EYES-BROWS-OVERLAYS]` et `[08.3 - BODY - SKINS - BODYSLIDE]`.
- Aucun changement actif dans MO2.
- BodySlide Output toujours non généré.
- Compteur ESP + ESM non-light conservé à **138**.

### Étapes 659 à 663 — Bloc 09 Animations / Skeleton / Physics

- Ouverture et validation provisoire du bloc `[09 - ANIMATIONS SKELETON PHYSICS]`.
- Socle physics / skeleton / OAR / Pandora / mouvement déjà présent.
- Pandora Output conservé, Pandora non relancé.
- Clôture provisoire du bloc 09 à l’étape 663.
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
- Clôture provisoire du bloc 11 à l’étape 672.
- Compteur conservé à **138**.

### Étapes 673 à 681 — Survival et préparation SexLab

- Ouverture du bloc `[12 - SURVIVAL IMMERSION ROLEPLAY]`, constaté presque vide.
- Ouverture du bloc `[13 - SEXLAB CORE ADULT FRAMEWORKS]`, constaté presque vide avant installation.
- Préparation du plan SexLab Core 1.5.97.
- Validation des candidats : SexLab Framework SE v163, SLAL 1.6, ZaZ Animation Pack SE, SLSF / SexLab Sexual Fame Framework SE.
- SLO Aroused NG 3.1.7 différé en raison d’une DLL NG à vérifier.
- Aucune installation active jusqu’à l’étape 681.

### Étapes 682 à 685 — SexLab Core 13-A

- Installation active de SexLab Core 13-A : SexLab Framework SE v1.63, SLAL 1.6, ZaZ Animation Pack SE, SLSF Reloaded 3.4.1.
- SLSF Reloaded d’abord installé décoché, puis activé après initialisation SexLab.
- SexLab v1.63 SE initialisé via MCM sur sauvegarde test.
- SLSF Reloaded MCM visible.
- Clôture provisoire SexLab Core 13-A à l’étape 685.
- Compteur ESP + ESM non-light : **138 → 141**.

---

## Étapes validées

### Étape 656 — Ouverture opérationnelle du bloc 08

- Bloc `[08]` déjà installé en grande partie.
- Sous-blocs présents : `[08.1 - CORE CHARACTERS TOOLS]`, `[08.2 - HAIR-EYES-BROWS-OVERLAYS]`, `[08.3 - BODY - SKINS - BODYSLIDE]`.
- Aucun changement MO2.
- Aucun test SKSE requis.
- Compteur conservé : **138**.
- BodySlide Output toujours non généré.

### Étape 657 — Validation groupée courte `[08.1]` + `[08.2]`

- Sous-blocs Core Characters Tools et Hair / Eyes / Brows / Overlays cohérents et déjà actifs.
- Plugins actifs relevés : `Expressive Facegen Morphs.esl`, `High Poly Head.esm`, `High Poly Head Vampire Fix.esp`, `FlawnsArgonians - Eyes, Replacer Plus.esp`, `FlawnsArgonians - NPCs, Flawns Edits.esp`, `Conditional Expressions.esp`, `RSChildren.esp`, `RSkyrimChildren.esm`, `KS Hairdo's.esp`, `KSHairdosSMP.esp`, `KSWigsSMP.esp`, `[dint999] HairPack02.esp`, `[Dint999] BDOr_Hairstyles.esp`, `TheEyesOfBeauty.esp`, `Kala_Eyes.esp`, `KaliliesBrows.esp`, overlays Community / SkFO / Female Makeup / Yyvengar / Sakora / Lyru.
- Aucun changement actif.
- Compteur conservé : **138**.

### Étape 658 — `[08.3 - BODY - SKINS - BODYSLIDE]`

- Sous-bloc Body / Skins / BodySlide conservé sans modification.
- Base conservée : CBBE, 3BA / 3BBB, The New Gentleman, BnP female skin, Tempered Skins for Males.
- Plugins actifs relevés : `CBBE.esp`, `3BBB.esp`, `RaceMenuMorphsCBBE.esp`, `SOSPhysicsManager.esp`, `TheNewGentleman.esp`, `BnP - Skinfix.esp`.
- Ne pas générer BodySlide maintenant.
- Compteur conservé : **138**.

### Étape 659 — Ouverture du bloc 09

- Bloc `[09 - ANIMATIONS SKELETON PHYSICS]` ouvert.
- Socle déjà présent : FSMP, CBPC, XPMSSE, OAR, AMR, Payload Interpreter, Paired Animation Improvements, Pandora, TDM, Precision, TK Dodge.
- Bloc sensible, validation courte uniquement.
- Pandora non relancé.
- Compteur conservé : **138**.

### Étape 660 — Validation courte physics / skeleton

- Pack concerné : Faster HDT-SMP, FSMPM, CBPC, XPMSSE, Auto Skeleton Patch.
- Plugins relevés : `FSMPM - The FSMP MCM.esp`, `XPMSE.esp`.
- Garder / validation provisoire.
- Ne pas modifier XPMSSE, CBPC, FSMP, BodySlide ou Pandora maintenant.

### Étape 661 — Validation courte OAR / Pandora / animation framework

- Pack concerné : Open Animation Replacer, IED Conditions, SKYFORGE OAR Output, AMR, Payload Interpreter, Paired Animation Improvements, Pandora Behaviour Engine, SKYFORGE Pandora Output.
- Garder / validation provisoire.
- Ne pas relancer Pandora tant qu’aucun mod d’animation ou comportement n’a changé.

### Étape 662 — Validation courte mouvement / combat animation base

- Pack concerné : No Spinning Death Animation, True Directional Movement, Precision, TK Dodge SE / RE, Sound For TK Dodge SE, Smooth TK Dodge Attack.
- Garder / validation provisoire.
- Tester esquive / hit detection plus tard, quand le bloc combat sera stabilisé.

### Étape 663 — Clôture provisoire du bloc 09

- Bloc `[09 - ANIMATIONS SKELETON PHYSICS]` stable pour continuer.
- Non finalisé définitivement.
- Aucune action active dans MO2 pendant les étapes 659 à 663.
- Pandora non relancé.
- BodySlide Output non généré.
- Compteur conservé : **138**.

### Étape 664 — Ouverture du bloc 10

- Bloc `[10 - GAMEPLAY COMBAT MAGIC PERKS]` ouvert.
- Le bloc est plus sensible que les audits précédents : combat, followers, IA, potions NPC, bounty, parkour, vampires, werebeasts, races.
- Décision : ne pas tout clôturer d’un coup.

### Étape 665 — Combat core

- Pack déjà présent : Valhalla Combat, Comprehensive Attack Rate Patch, Wait Your Turn, NPCs Take Cover, NPC No Block Exhaustion, Archery Locational Damage, Bow Charge Plus, No BS AI Projectile Dodge, VioLens.
- Plugins actifs : `ValhallaCombat.esp`, `WaitYourTurn.esp`, `NPCs Take Cover.esp`, `NPC No Block Exhaustion.esp`, `NPC No Block Exhaustion - MCM.esp`, `blockenchantments.esl`, `ArcheryLocationalDamage.esp`, `Bow Charge Plus.esp`, `VioLens SE.esp`, `NoBSAIProjectileDodge.esp`.
- Garder / validation provisoire.
- Ne pas ajouter d’autre overhaul combat majeur maintenant.

### Étape 666 — Followers / interactions / utility gameplay

- Pack déjà présent : Nether’s Follower Framework, Simple Offence Suppression, confort dialogue / caméra / interactions / followers.
- Plugins actifs : `nwsFollowerFramework.esp`, `Nether's Follower Framework - Settings Loader.esp`, `Simple Offence Suppression MCM.esp`, `ImTalkinHere.esp`, `Pick Up Radius.esp`, `ACloserLook.esp`.
- Garder / validation provisoire.
- Revoir NFF et ses réglages plus tard.

### Étape 667 — Horses / bounty / misc gameplay

- Pack déjà présent : Headhunter, Simplest Horses, Skyrim’s Got Talent, dialogue camera, Dragon Claws Auto-Unlock, Take a Peek, Remote Interactions, Taunt Your Enemies, SkyParkour.
- Plugins actifs : `Headhunter - Bounties Redone.esp`, `SimplestHorses.esp`, `NoNeedToAsk.esp`, `FoodForTheThirsty.esp`, `SkyrimsGotTalent-Bards.esp`, `CameraSwitchDuringDialogue.esp`, `Dragon Claws Auto-Unlock.esp`, `Take A Peek - New Stealth Mechanic.esp`, `Remote Interactions.esp`, `Taunt Your Enemies.esp`, `SkyParkour.esp`.
- Garder / validation provisoire.

### Étape 668 — Races / werebeasts / vampires

- Pack déjà présent : Aetherius, Mundus, Sacrosanct, Cover Your Head, Sun Affects NPC Vampires, Manbeast.
- Plugins actifs : `Aetherius.esp`, `Aetherius - Race Menu Racial Passive Descriptions.esp`, `Mundus.esp`, `MundusUSSEP.esp`, `Manbeast.esp`, `Sacrosanct - Vampires of Skyrim.esp`, `CoverYourHead - Sacrosanct.esp`, `SunAffectsNPCVampires - ExcludeFriendlies.esp`, `SunAffectsNPCVampires.esp`.
- Garder / validation provisoire.
- Ne pas ajouter Better Vampires ou Growl en parallèle.

### Étape 669 — Dialogue / NPC reactions / lines expansions

- Passage vers `[11.1 - FOLLOWERS NPCS DIALOGUES]`.
- Pack déjà présent : expansions de lignes NPC, NPCs React, GDO, RDO, CRF, AI Overhaul, Run For Your Lives, Realistic Conversations.
- Plugins actifs relevés : Bandit / Civil War / Forsworn / Vampire / Brawl Lines, NPCs React, Carriage and Stable Dialogues, Dialogue Expansions, Guard Dialogue Overhaul, More Dialogue Options, Misc Dialogue Edits, RDO, CRF, AI Overhaul, Run For Your Lives, Realistic-Voice.
- Garder / validation provisoire.

### Étape 670 — Follower Dialogue Expansion / compagnons vanilla

- Pack FDE vanilla déjà présent : Olfina, Uthgerd, Ysolda, Jordis, Camilla, Illia, Lydia, Mjoll, Brelyna, Erik, Faendal, Roggi, Marcurio, Sapphire, Rayya, Borgakh, Aranea, Faralda, Jenassa, Eola, Aela.
- RDO - FDE Compatibility Patch présent.
- Garder / validation provisoire.

### Étape 671 — Followers custom et patches FDE

- Pack déjà présent : Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore, Serana Dialogue Add-On, Serana Re-Imagined, Menagerie, Show Follower Carry Weight.
- Plugins actifs : `Inigo.esp`, `Lucien.esp`, `018Auri.esp`, `HLIORemi.esp`, `BPUFXelzazFollower.esp`, `BPUFXelzazFollowerAE.esp`, `DK_Thogra.esp`, `GORE.esp`, `SeranaDialogAddon.esp`, `Serana Re-Imagined.esp`, `SDA NFF Patch.esp`, `SDA RDO Patch.esp`, `SDA Remiel Banter Patch.esp`, `SDA CC Umbra Patch.esp`, `Menagerie.esp`, `Show Follower Carryweight.esp`.
- Garder / validation provisoire.

### Étape 672 — Clôture provisoire bloc 11 dialogues / followers

- Bloc dialogues / followers stable pour continuer.
- Non finalisé définitivement.
- Aucun changement actif MO2 pendant les étapes 669 à 672.
- Compteur conservé : **138**.

### Étape 673 — Ouverture `[12 - SURVIVAL IMMERSION ROLEPLAY]`

- Bloc 12 quasiment vide dans le snapshot actuel.
- Présence uniquement de `Skyrim Unbound Reborn - ALTERNATE START - A REINSTALLER PLUS TARD`.
- Décision : ne rien installer maintenant.
- Compteur conservé : **138**.

### Étape 674 — Ouverture `[13 - SEXLAB CORE ADULT FRAMEWORKS]`

- Bloc 13 quasiment vide avant installation.
- Présence de `MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB`.
- Décision : ouverture / constat uniquement, pas encore d’installation SexLab.

### Étape 675 — Préparation du plan SexLab Core 1.5.97

- Plan préparé, aucune installation.
- Objectif : premier pack SexLab Core minimal, sans Devious, sans créatures, sans slavery / defeat / prostitution, sans gros packs d’animations.
- Candidats à vérifier : SexLab Framework SE 1.63, SLAL, ZaZ, Aroused / SLSF.
- Compteur conservé : **138**.

### Étape 676 — Inventaire SexLab Core depuis Nefaram

- Inventaire de référence établi depuis Nefaram 1.5.97.
- Décision : ne pas reprendre tout le bloc Nefaram d’un coup.
- Premier pack recommandé : SexLab Framework, SLAL, ZaZ, SLSF ; SLO Aroused NG à vérifier.

### Étape 677 — SexLab Framework : archive validée

- Archive cible validée : `SexLabFrameworkSE_v163.7z`.
- Refus des archives AE / GOG / 1.6.x pour SKYFORGE 1.5.97.
- Plugin attendu : `SexLab.esm`.
- Impact compteur prévisionnel : +1 non-light.
- Pas d’installation encore.

### Étape 678 — SLAL / SexLab Animation Loader : candidat validé sous réserve

- SLAL 1.6 cohérent avec SexLab Framework 1.63+ et JContainers.
- FNIS mentionné par la page, mais SKYFORGE retient Pandora.
- Plugin attendu : `SexLab Animation Loader.esp` ou nom proche.
- Pas d’installation encore.

### Étape 679 — ZaZ Animation Pack SE : validation par référence Nefaram 1.5.97

- Archive candidate : `ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023.7z`.
- Acceptée comme référence locale Nefaram 1.5.97, avec prudence.
- Plugin attendu : `ZaZAnimationPack.esm`.
- Pas d’installation encore.

### Étape 680 — SLO Aroused NG : différé

- SLO Aroused NG 3.1.7 identifié dans Nefaram, mais différé.
- Raison : présence de `SKSE/Plugins/SexlabArousedNG.dll` et plugins `SexLabAroused.esm`, `OSLAroused.esp`, `OAroused.esp`.
- Nécessite vérification stricte SE 1.5.97 / SKSE 2.0.20 avant intégration.

### Étape 681 — SLSF / SexLab Sexual Fame Framework SE vérifié

- Mod vérifié : Sex Lab - Sexual Fame Framework SE.
- Plugin relevé : `SexLab - Sexual Fame [SLSF].esm`.
- Aucune DLL `SKSE/Plugins` relevée.
- Garder comme candidat installable pour SexLab Core 13-A.
- Pas d’installation encore.

### Étape 682 — Installation SexLab Core 13-A

- Mods installés : SexLab Framework SE v163, SexLab Animation Loader 1.6, ZaZ Animation Pack+ CBBE HDT V.8.0+SE2023, SLSF Reloaded 3.4.1.
- SLSF Reloaded installé mais laissé décoché volontairement.
- SKSE / menu principal : OK.
- Masters manquants : aucun.
- Messages DLL : aucun.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.
- Variation : **138 → 141**.
- LOOT non lancé, Pandora/FNIS non lancé, BodySlide non généré.

### Étape 683 — Initialisation SexLab MCM

- SexLab v1.63 SE initialisé via MCM.
- Sauvegarde test créée avec succès.
- Aucun CTD.
- Aucun message anormal.
- Overwrite vide.
- Compteur : **141**.
- SLSF Reloaded toujours décoché.

### Étape 684 — Activation SLSF Reloaded 3.4.1

- SLSF Reloaded activé après initialisation SexLab.
- MCM SLSF Reloaded visible.
- Plugin SLSF Reloaded coché.
- Aucun CTD signalé.
- Aucun message anormal signalé.
- Overwrite vide.
- Compteur conservé : **141**.

### Étape 685 — Clôture provisoire SexLab Core 13-A

- Mods actifs : SexLab Framework SE v1.63, SexLab Animation Loader 1.6, ZaZ Animation Pack SE, SLSF Reloaded 3.4.1.
- SexLab initialisé via MCM sur sauvegarde test.
- SLSF Reloaded activé après initialisation SexLab.
- MCM SLSF Reloaded visible.
- Aucun CTD signalé.
- Aucun message anormal signalé.
- SKSE / menu principal : OK.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **141**.
- LOOT non lancé.
- Pandora/FNIS non lancé.
- BodySlide non généré.

---

## État final post-685

- Dernière étape validée/documentée : **Étape 685 — Clôture provisoire SexLab Core 13-A**.
- Prochaine étape attendue : **Étape 686**.
- Compteur ESP + ESM non-light : **141**.
- Overwrite : **vide**.
- LOOT : **non lancé**.
- DynDOLOD / LOD : **non générés**.
- BodySlide Output : **non généré**.
- Pandora : **non relancé**.
- FNIS : **non lancé**.
- SexLab Framework SE v1.63 : **actif et initialisé**.
- SLSF Reloaded 3.4.1 : **actif, MCM visible**.
