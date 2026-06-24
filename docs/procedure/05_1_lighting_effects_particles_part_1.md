# SKYFORGE — Procédure — 05.1 - LIGHTING EFFECTS & PARTICLES — partie 1

Ouverture officielle du sous-bloc **05.1 - LIGHTING EFFECTS & PARTICLES**.

Ce fichier couvre les étapes **582 à 600**, consacrées aux fumées, impacts de sorts, ENB Particle Lights, VFX élémentaires et effets visuels de combat.

---

## Étape 582 — Début Lighting Effects & Particles

### Structure MO2

Création / validation des séparateurs :

- `[05 - VISUAL BASE MESHES TEXTURES]`
- `[05.1 - LIGHTING EFFECTS & PARTICLES]`
- `[05.2 - PARALLAX FRAMEWORK TEXTURES]`

### Mods ajoutés

- **Smoking Torches and Candles**
- **Burnt Corpses 4k Retexture - Mihail's Shards of Immersion**
- **Deadly Spell Impacts**
- **Deadly Spell Impacts Transparency Fix for ENB**

### Plugins ajoutés

- `DeadlySpellImpacts Transparency Fix.esp`
- `DeadlySpellImpacts.esp`
- `Smoking Torches And Candles.esp`

### Résultat

- Compteur ESP + ESM non-light : `129 → 130`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

Étape 582 validée.

---

## Étape 583 — Deadly Spell Impacts : parallax + patchs + poussières

### Mods ajoutés

- **Parallax Spell Impacts**
- **Deadly Spell Impact - Patches**
- **Dust Effects by HHaleyy**

### Choix

- `Parallax Spell Impacts` installé après `Deadly Spell Impacts`.
- `Deadly Spell Impact - Patches` installé avec le patch AIO :
  - AOS
  - ISC
  - PSI
- Note MO2 recommandée : `Deadly Spell Impact - Patches - PATCHES A REVOIR PLUS TARD`

### Plugins ajoutés / concernés

- `DustEffectsSSE.esp`
- `Deadly Spell Impact - AOS ISC PSI - AIO Patch.esp`
- `PSI.esp`
- `DeadlySpellImpacts Transparency Fix.esp`
- `DeadlySpellImpacts.esp`

### Résultat

- Compteur ESP + ESM non-light : `130 → 131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

Étape 583 validée.

---

## Étape 584 — Rudy HQ More Lights : plantes et insectes

### Mods ajoutés

- **Rudy HQ - More Lights for ENB SE - Deathbells and Nirnroots**
- **Rudy HQ - More Lights for ENB SE - Torchbugs and Moths**
- **Rudy HQ - More Lights for ENB SE - Glowing Mushrooms**

### Mod différé

- **A Nirnroot - Particle Light Patch**
  - Requiert `A Nirnroot`, non installé actuellement.
  - Note : `REQUIERT A Nirnroot - A REVOIR PLUS TARD`

### Résultat

- Aucun plugin inattendu
- Compteur ESP + ESM non-light inchangé : `131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

Étape 584 validée.

---

## Étape 585 — Premiers ENB Particle Lights

### Mods ajoutés

- **ENB Particle Lights - Dwemer Lanterns**
- **Particle Lights For ENB SE - Bugs in a Jar**
- **Particle Lights For ENB SE - Undead Creatures**

### Mods différés

- **More Lights for ENB - Blood Splatter Fix**
  - Requiert `ENB Light Inventory Fix (ELIF)`.
  - Note : `REQUIERT ELIF - A REVOIR PLUS TARD`
- **Fluffy Moths**
  - Requiert `Butterfly Improved by zzjay - SE`.
  - Note : `REQUIERT Butterfly Improved by zzjay - A REVOIR PLUS TARD`
- **A Nirnroot - Particle Light Patch**
  - Requiert `A Nirnroot`.
  - Note : `REQUIERT A Nirnroot - A REVOIR PLUS TARD`

### Choix FOMOD

#### Particle Lights For ENB SE - Undead Creatures

- Undead Creature Eyes : `Default`
- Ghosts : `Default`
- Cannibal Draugr : décoché
- Note MO2 : `FOMOD A REVOIR PLUS TARD`

### Snapshot du bloc 05.1 après validation

```txt
[05.1 - LIGHTING EFFECTS & PARTICLES]
Smoking Torches and Candles SSE
Burnt Corpses 4k Retexture- Mihail's Shards of Immersion (SE-AE version)
Deadly Spell Impacts
Deadly Spell Impacts Transparency Fix for ENB
Parallax Spell Impacts
Deadly Spell Impact - AOS ISC PSI - AIO Patch
Dust Effects by HHaleyy
Rudy HQ - More Lights for ENB SE - Deathbells and Nirnroots
Rudy HQ - More Lights for ENB SE - Torchbugs and Moths
Rudy HQ - More Lights for ENB SE - Glowing Mushrooms
ENB Particle Lights - Dwemer Lanterns
Particle Lights For ENB SE - Bugs in a Jar
Particle Lights For ENB SE - Undead Creatures - FOMOD A REVOIR PLUS TARD
```

### Résultat

- Aucun nouveau plugin ajouté
- Compteur ESP + ESM non-light inchangé : `131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins attendus cochés uniquement
- Overwrite vide

Étape 585 validée.

---

## Étape 586 — ENB Particle Lights : staff, ruines, shaders

### Mods ajoutés

- **Particle Lights for ENB - Staff Enchanter**
- **Particle Lights for ENB - Nordic Ruins Candles**
- **ENB Lights For Effect Shaders**

### Mod non réinstallé

- **Mr. Dragonfly ENB Particle Light**
  - Déjà installé dans `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`.

### Résultat

- Installation MO2 dans `[05.1 - LIGHTING EFFECTS & PARTICLES]`
- Aucun nouveau plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

Étape 586 validée.

---

## Étape 587 — ENB Particle Lights : orbes, wisps, moon crests

### Mods ajoutés

- **Particle Lights for ENB - Light Orbs - Motes**
- **Particle Lights for ENB - Wisps - Witchlight**
- **Particle Lights for ENB - Moon Crests**

### Mod différé

- **ENB Particle Lights - Lava**
  - Impact FPS / logique Light Placer à traiter séparément.

### Résultat

- Aucun nouveau plugin ajouté
- Compteur ESP + ESM non-light inchangé : `131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Overwrite vide

Étape 587 validée.

---

## Étape 588 — ENB Particle Lights : Dwarven/Falmer/Fire traps

### Mods ajoutés

- **ENB Particle Lights - Dwarven Spiders**
- **Particle Lights for ENB - Falmer Drips - HIGH POLY**
- **ENB Particle Lights - Fire Traps**

### Résultat

- Installation MO2 dans `[05.1 - LIGHTING EFFECTS & PARTICLES]`
- Aucun nouveau plugin ajouté
- Aucun master ajouté
- Aucun DLL ajouté
- Compteur ESP + ESM non-light inchangé : `131`
- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Aucun nouveau plugin
- Overwrite vide

Étape 588 validée.

---

## Étape 589 — ENB particle lights légers

### Mods ajoutés

- **Particle Lights for ENB - Spectral Warhound Eyes**
- **ENB Particle Lights for Gemstones**

### Choix FOMOD / options

#### ENB Particle Lights for Gemstones

- ENB Particle Lights : `Default`
- Optional : `Default - Rubies and Garnets`

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 589 validée.

---

## Étape 590 — Rudy HQ More Lights - Chaurus Eggs and Sacs

### Mod ajouté

- **Rudy HQ - More Lights for ENB SE - Chaurus Eggs and Sacs**

### Rôle

Ajout de lumières ENB Particle aux œufs et sacs de chaurus.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 590 validée.

---

## Étape 591 — Pack ENB lights léger

### Mods ajoutés

- **Ayleid Ruins - ENB Light**
- **Hot Lava - Heat Distortion**
- **Hot Lava - Heat Distortion - ENB Light**

### Choix

- Fichier optionnel retenu : `Hot Lava - Heat Distortion - ENB Light`
- Fichier optionnel non retenu : `Hot Lava - Heat Distortion - PraedyXVI - ENB Light`
- Raison : dépendance à Praedy's lava textures non installée/validée.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 591 validée.

---

## Étape 592 — Pack ENB lights objets/armes

### Mods ajoutés

- **Particle Lights for ENB - Falmer Things**
- **Rudy HQ - More Lights for ENB SE - Arrows**
- **Rudy HQ - More Lights for ENB SE - Daedric Weapons and Armor**
  - Note MO2 : `FOMOD ARMOR A REVOIR PLUS TARD`

### Choix FOMOD

#### Rudy HQ - More Lights for ENB SE - Daedric Weapons and Armor

- Weapon models : `LeanWolf's Better Shaped Weapons`
- Optional Armor tweaks :
  - Daedric armor : non coché
  - Daedric Shield : non coché
- Daedric Armor light :
  - Armor light : non coché
- Note : options armure/bouclier/armor light à revoir plus tard lors du module armures daedriques.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 592 validée.

---

## Étape 593 — Pack ENB Light Solstheim / Apocrypha

### Mods ajoutés

- **Dark Elf Lantern - ENB Light - Animated Glow**
- **Dark Elf Lantern ENB Light - Particle Patch for ENB - Patch**
- **Apocrypha - ENB Light - Community Shader Light Limit Fix Light**

### Prérequis / vérifications

- `Particle Patch for ENB` déjà installé dans SKYFORGE.
- Aucun besoin de réinstaller `Particle Patch for ENB`.
- Aucun basculement vers Community Shaders.

### Différé

- **Dovahnique's Diverse Dark Elf Lanterns**
  - Replacer plus structurant / variantes visuelles, à revoir plus tard.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 593 validée.

---

## Étape 594 — Pack ENB Light effets + potions

### Mods ajoutés

- **Misc Effects ENB Light**
  - Main file installé.
  - Update file `1.6.1` fusionné avec le main file via `Merge` MO2.
- **Awesome Potions Simplified - ENB Lights**

### Choix / méthode

- `Misc Effects ENB Light - UPDATE` installé avec le même nom MO2 que le main file.
- MO2 : `Merge` choisi, pas `Replace`.
- Pas de ligne séparée conservée pour l’update.

### Différés

- **Elytra and Bliss Bug - ENB Light**
  - SPID / ESL / réglage Scrambled Bugs à vérifier.
- **Vibrant Weapons Lite**
  - Système d’effets d’enchantements d’armes plus structurant, à traiter séparément.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 594 validée.

---

## Étape 595 — Pack ENB Light SPID léger

### Mods ajoutés

- **Sprites or Specters - ENB Light**
- **Elytra and Bliss Bug - ENB Light**

### Choix

- Versions Scrambled Bugs retenues quand proposées.
- Réglage Scrambled Bugs vérifié/modifié :
  - `attachHitEffectArt`: `true`

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 595 validée.

---

## Étape 596 — Pack VFX élémentaires frost + shock

### Mods ajoutés

- **Arctic - Frost Effects Redux**
- **ELECTRIFY S.E.**

### Choix FOMOD

#### Arctic - Frost Effects Redux

- Frost Meshes Patch `ESL-Tagged` installé.
- Raison : requis pour les nouveaux meshes 3D des sorts `Frostbite` et `Ice Storm`.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 596 validée.

---

## Étape 597 — Pack Kittytail VFX frost + lightning + dragon breath

### Mods ajoutés

- **Frost VFX Edit**
- **Lightning VFX Edit**
- **Dragon Breath VFX Edit**

### Choix

#### Dragon Breath VFX Edit

- Main file uniquement.
- Option Ultimate Dragons non installée.
- Raison : `Ultimate Dragons` non installé/validé dans SKYFORGE à ce stade.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 597 validée.

---

## Étape 598 — Pack feu léger : Fire VFX + Better Flame + forge water

### Mods ajoutés

- **Flame VFX Edit**
- **Better Flame Spell FX - Mesh replacer**
- **Animated Forge Water**
  - Note MO2 : `PATCH EMBERS XD A REVOIR PLUS TARD`

### Choix

#### Better Flame Spell FX

- Fichier retenu : `Mesh replacer`.
- Main file ESP flagged ESL non installé.
- Option `Keep non casting effect` non installée.

#### Animated Forge Water

- Option FOMOD : `Vanilla`.
- Options non retenues :
  - Embers HD
  - Embers XD
  - Elsopa
  - Elsopa and Embers HD
  - Elsopa and Embers XD
- Raison : Embers XD/HD et ElSopa forge/anvil non installés/validés à ce stade.
- À revoir plus tard si Embers XD est installé avec option forges.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 598 validée.

---

## Étape 599 — Dust piles + FleshFX

### Mods ajoutés

- **ElSopa HD - Remade Better Dust Piles SE - 2K**
- **FleshFX**

### Non installés

- **Improved Dust Particles**
  - Déjà installé dans SKYFORGE sous `TB's Improved Dust Particles`.
- **Embers XD**
  - Mod structurant à traiter en étape dédiée.
- **Burning Orbit Near-Blind Repair**
  - À revoir avec ENB Manager / choix Kauz-Cabbage.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 599 validée.

---

## Étape 600 — Banner fix + MIF + Separated Slash Effects X

### Mods ajoutés

- **Summerset Shadows Banner Fix**
- **MIF - Mu Impact Framework**
- **Separated Slash Effects X - MIF**

### Choix FOMOD — Separated Slash Effects X

- Installation : `Custom Install`
- Special Slash : `Special Slash (without blunt)`
- Sparks Slash : `Sparks Slash (without blunt)`
- Standard Slash : `None`
- Arrow VFX : `Standard Slash`
- Color 1 : `Red`
- Color 2 : `Orange`
- Color 3 : `White`
- Hit Impact : `Simple`
- Hit Sparks : `small emit`
- Hit ROF : `ROF`
- Hit Refraction : `Refraction`
- Hit Glow : `Glow`
- Slash SFX : non coché
- Arrow SFX : non coché

### Notes

- Les SFX du mod ne sont pas installés pour éviter une couche audio redondante.
- Les sons vanilla / Audio Overhaul / Immersive Sounds restent actifs.

### Résultat

- SKSE/menu principal OK
- Aucun master manquant
- Aucun message DLL
- Plugins cochés : tous
- Overwrite vide
- Compteur ESP + ESM non-light : `131`

Étape 600 validée.

---

## État final post-600

- Dernière étape validée/documentée : **600**
- Module enrichi : `[05.1 - LIGHTING EFFECTS & PARTICLES]`
- Compteur ESP + ESM non-light : **131**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **non relancé**

Prochaine étape attendue : **601**.
