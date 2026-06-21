# SKYFORGE — Procédure — 04 - AUDIO MUSIC VOICES — part 2

## Étape 554 — Immersive Sounds Creation Club Armours + Phoenix Compendium

### Objectif
Compléter prudemment le bloc audio avec deux ajouts issus de la logique **Nolvus Awakening**, sans toucher aux systèmes lourds.  
Aucun lancement de LOOT, Pandora, BodySlide, DynDOLOD ou LOD.

### Source
- **Nolvus Awakening**
- Immersive Sounds - Creation Club Armours : https://www.nexusmods.com/skyrimspecialedition/mods/59044
- Phoenix Compendium : https://www.nexusmods.com/skyrimspecialedition/mods/55221

### Mods installés
- **Immersive Sounds - Creation Club Armours**
  - Fichier choisi : `1. Creation Club Armours`
  - Variante retenue : ESL flagged
  - Variante exclue : `Creation Club Armours - esp version`
  - Rôle : patch audio Immersive Sounds - Compendium pour les armures Creation Club / Anniversary Edition.

- **Phoenix Compendium**
  - Version : `2.5.5`
  - Installation : FOMOD partiel prudent
  - Nom MO2 recommandé : `Phoenix Compendium - FOMOD PARTIEL A REVOIR PLUS TARD`
  - Rôle : reworks audio SFX / voix / créatures / ambiances.

### Choix importants
- Phoenix Compendium installé en sélection manuelle, sans `Auto Select and install`.
- Modules retenus : créatures vanilla/Dawnguard, animaux vanilla, géants, chevaux, animunculi Dwemer, quelques ambiances légères.
- Modules différés : magie `Airgetlam/Castigate`, armes/combat `Eviscerate`, joueur/voix, musique/UI `Phoenix Legacy`, patches ISC liés aux modules différés.
- Raison : éviter de toucher trop tôt aux blocs magie, combat, voix joueur et UI/musique avant stabilisation des modules dédiés.

### Placement
- Panneau gauche : bloc `[04 - AUDIO MUSIC VOICES]`, proche de `Audio Overhaul for Skyrim`, `Immersive Sounds - Compendium` et des ambiances audio.
- Panneau droit : plugin ajouté et coché :
  - `CC complete ISC patch.esp`

### Tests
- SKSE menu : OK
- Masters manquants : aucun
- Overwrite : vide
- Plugins ajoutés cochés : oui
- Compteur ESP+ESM non-light : `128 → 128`
- Variation compteur : `+0`

### Décision finale
Étape validée.

`554 — Immersive Sounds - Creation Club Armours + Phoenix Compendium installés. Phoenix Compendium marqué “FOMOD PARTIEL A REVOIR PLUS TARD”. Test SKSE/menu OK, aucun master manquant, Overwrite vide. Plugin ajouté : CC complete ISC patch.esp. Compteur ESP+ESM non-light inchangé : 128.`
