# SKYFORGE — Changelog / validation — partie 21

Période couverte : étapes **579 à 600**.

Cette partie documente la fin du complément `05 - VISUAL BASE MESHES TEXTURES` puis l’ouverture officielle du bloc `[05.1 - LIGHTING EFFECTS & PARTICLES]`.

---

## Résumé global

### Étapes 579 à 581 — Fin complément Visual Base / meshes

- Ajout de meshes FYX pour cabanes, docks, toits, charbon, barques.
- Ajout de collisions FYX, correction de piège mural en bois et amélioration des coffres.
- Ajout de `Detailed Carriages 2.0`, `College of Winterhold - Glowing Symbols`, `SUDs - Skyrim's Unique Drinks` et `Wood Chopping Camera Glitch Fix`.
- Compteur ESP + ESM non-light conservé à **129**.

### Étapes 582 à 600 — Ouverture Lighting Effects & Particles

- Création / validation des séparateurs :
  - `[05 - VISUAL BASE MESHES TEXTURES]`
  - `[05.1 - LIGHTING EFFECTS & PARTICLES]`
  - `[05.2 - PARALLAX FRAMEWORK TEXTURES]`
- Ajout de `Smoking Torches and Candles`, `Deadly Spell Impacts`, `Parallax Spell Impacts`, `Dust Effects`, nombreux ENB Particle Lights, Rudy HQ More Lights, VFX Kittytail, VFX élémentaires, FleshFX, MIF et `Separated Slash Effects X - MIF`.
- Passage du compteur ESP + ESM non-light :
  - **129 → 130** à l’étape 582.
  - **130 → 131** à l’étape 583.
  - Stable à **131** jusqu’à l’étape 600.

---

## Étapes validées

### Étape 579 — FYX meshes : cabanes, docks, charbon, barques

- Mods ajoutés : FYX shack kit walls, dock ramp, shack kit roofs, coal in the shovel, rowboat.
- Aucun plugin ajouté.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur inchangé : **129**.

### Étape 580 — Collisions FYX + coffres

- Mods ajoutés : FYX Nordic Doors and Traps Collisions, FYX Hrothgar Steps Collisions, Wood Wall Trap Mesh and UV Fix, Better Chests.
- Aucun plugin ajouté.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur inchangé : **129**.

### Étape 581 — Carrioles détaillées + Collège + boissons

- Mods ajoutés : Detailed Carriages 2.0, College of Winterhold - Glowing Symbols, SUDs - Skyrim's Unique Drinks, Wood Chopping Camera Glitch Fix.
- Plugins ajoutés :
  - `JKEEKBanneredMare - Skyrim Unique Drinks Patch.esp`
  - `Ryn's Sleeping Giant Inn - Skyrim Unique Drinks Patch.esp`
  - `SUDs.esp`
  - `DetailedCarriages 2.0.esp`
  - `DetailedCarriages 2.0 - SMIM Patch.esp`
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur inchangé : **129**.

### Étape 582 — Début Lighting Effects & Particles

- Mods ajoutés : Smoking Torches and Candles, Burnt Corpses 4k Retexture, Deadly Spell Impacts, Deadly Spell Impacts Transparency Fix for ENB.
- Plugins ajoutés :
  - `DeadlySpellImpacts Transparency Fix.esp`
  - `DeadlySpellImpacts.esp`
  - `Smoking Torches And Candles.esp`
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur : **129 → 130**.

### Étape 583 — Deadly Spell Impacts : parallax + patchs + poussières

- Mods ajoutés : Parallax Spell Impacts, Deadly Spell Impact - Patches, Dust Effects by HHaleyy.
- Patch AIO retenu : AOS / ISC / PSI.
- Plugins ajoutés / concernés : `DustEffectsSSE.esp`, `Deadly Spell Impact - AOS ISC PSI - AIO Patch.esp`, `PSI.esp`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur : **130 → 131**.

### Étape 584 — Rudy HQ More Lights : plantes et insectes

- Mods ajoutés : Deathbells and Nirnroots, Torchbugs and Moths, Glowing Mushrooms.
- `A Nirnroot - Particle Light Patch` différé.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 585 — Premiers ENB Particle Lights

- Mods ajoutés : Dwemer Lanterns, Bugs in a Jar, Undead Creatures.
- FOMOD Undead Creatures : options Default pour Undead Creature Eyes et Ghosts ; Cannibal Draugr décoché.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 586 — ENB Particle Lights : staff, ruines, shaders

- Mods ajoutés : Staff Enchanter, Nordic Ruins Candles, ENB Lights For Effect Shaders.
- `Mr. Dragonfly ENB Particle Light` non réinstallé car déjà présent dans le bloc followers.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 587 — ENB Particle Lights : orbes, wisps, moon crests

- Mods ajoutés : Light Orbs - Motes, Wisps - Witchlight, Moon Crests.
- ENB Particle Lights - Lava différé.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 588 — ENB Particle Lights : Dwarven/Falmer/Fire traps

- Mods ajoutés : Dwarven Spiders, Falmer Drips HIGH POLY, Fire Traps.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 589 — ENB particle lights légers

- Mods ajoutés : Spectral Warhound Eyes, ENB Particle Lights for Gemstones.
- Gemstones : Default + Rubies and Garnets.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 590 — Rudy HQ More Lights - Chaurus Eggs and Sacs

- Mod ajouté : Chaurus Eggs and Sacs.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 591 — Pack ENB lights léger

- Mods ajoutés : Ayleid Ruins - ENB Light, Hot Lava - Heat Distortion, Hot Lava - Heat Distortion - ENB Light.
- Option PraedyXVI non retenue faute de dépendance validée.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 592 — Pack ENB lights objets/armes

- Mods ajoutés : Falmer Things, Rudy HQ More Lights Arrows, Rudy HQ More Lights Daedric Weapons and Armor.
- FOMOD Daedric : LeanWolf's Better Shaped Weapons ; armures, bouclier et armor light non cochés.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 593 — Pack ENB Light Solstheim / Apocrypha

- Mods ajoutés : Dark Elf Lantern ENB Light, patch Particle Patch for ENB, Apocrypha ENB Light Community Shader Light Limit Fix Light.
- Aucun basculement vers Community Shaders.
- Dovahnique's Diverse Dark Elf Lanterns différé.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 594 — Pack ENB Light effets + potions

- Mods ajoutés : Misc Effects ENB Light, Awesome Potions Simplified - ENB Lights.
- Update 1.6.1 de Misc Effects fusionné via `Merge` MO2.
- Elytra and Bliss Bug ENB Light et Vibrant Weapons Lite différés.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 595 — Pack ENB Light SPID léger

- Mods ajoutés : Sprites or Specters - ENB Light, Elytra and Bliss Bug - ENB Light.
- Versions Scrambled Bugs retenues quand proposées.
- Réglage Scrambled Bugs : `attachHitEffectArt = true`.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 596 — Pack VFX élémentaires frost + shock

- Mods ajoutés : Arctic - Frost Effects Redux, ELECTRIFY S.E.
- Arctic : Frost Meshes Patch ESL-Tagged installé.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 597 — Pack Kittytail VFX frost + lightning + dragon breath

- Mods ajoutés : Frost VFX Edit, Lightning VFX Edit, Dragon Breath VFX Edit.
- Option Ultimate Dragons non installée.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 598 — Pack feu léger : Fire VFX + Better Flame + forge water

- Mods ajoutés : Flame VFX Edit, Better Flame Spell FX - Mesh replacer, Animated Forge Water.
- Better Flame : Mesh replacer uniquement.
- Animated Forge Water : option Vanilla retenue ; options Embers/ElSopa différées.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 599 — Dust piles + FleshFX

- Mods ajoutés : ElSopa HD - Remade Better Dust Piles SE - 2K, FleshFX.
- Improved Dust Particles non installé car TB's Improved Dust Particles est déjà présent.
- Embers XD et Burning Orbit Near-Blind Repair différés.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

### Étape 600 — Banner fix + MIF + Separated Slash Effects X

- Mods ajoutés : Summerset Shadows Banner Fix, MIF - Mu Impact Framework, Separated Slash Effects X - MIF.
- Separated Slash Effects X installé en Custom Install.
- Slash SFX et Arrow SFX non cochés pour éviter une couche audio redondante.
- Test SKSE/menu principal OK.
- Overwrite vide.
- Compteur stable : **131**.

---

## État final post-600

- Dernière étape validée/documentée : **Étape 600 — Banner fix + MIF + Separated Slash Effects X**
- Prochaine étape attendue : **Étape 601**
- Compteur ESP + ESM non-light : **131**
- Overwrite : **vide**
- LOOT : **non lancé**
- DynDOLOD / LOD : **non générés**
- BodySlide Output : **non généré**
- Pandora : **non relancé**
