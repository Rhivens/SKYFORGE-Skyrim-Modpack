# Gameplay, combat, magic & perks — partie 1

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ouverture et validation provisoire du module **10 - GAMEPLAY COMBAT MAGIC PERKS** et du sous-bloc **10.1 - RACES WEREBEASTS VAMPIRES**.

Périmètre : étapes **664 à 668**.

Important : ces étapes sont des validations courtes sur des éléments déjà présents dans MO2. Aucun nouveau fichier actif n’a été installé pendant ce convoi.

---

## Étape 664 — Ouverture du bloc 10

### État constaté

Le bloc suivant est bien :

- `[10 - GAMEPLAY COMBAT MAGIC PERKS]`

Il commence notamment avec :

- Valhalla Combat
- Nether's Follower Framework
- Comprehensive Attack Rate Patch - SKSE
- Wait Your Turn
- NPCs Take Cover
- NPCs Use Potions
- Simple Offence Suppression
- Headhunter
- SkyParkour
- NPC No Block Exhaustion
- Archery Locational Damage
- Bow Charge Plus
- VioLens

Puis il enchaîne sur :

- `[10.1 - RACES WEREBEASTS VAMPIRES]`

avec notamment :

- Aetherius
- Mundus
- Sacrosanct
- Sun Affects NPC Vampires
- Manbeast

### Décision

- Bloc 10 ouvert.
- Bloc plus sensible que les blocs 08 / 09.
- Ne pas tout clôturer d’un coup.
- Avancer par packs cohérents.

---

## Étape 665 — Combat core

### Pack concerné

Présent dans `[10 - GAMEPLAY COMBAT MAGIC PERKS]` :

- Valhalla Combat
- Comprehensive Attack Rate Patch - SKSE
- Wait Your Turn - Enemy Circling Behaviour
- NPCs Take Cover - Smarter Anti-Cheese AI
- NPC No Block Exhaustion
- NPC No Block Exhaustion - MCM
- 3rd Person Camera Stagger Remover
- Block Enchantments
- Archery Locational Damage
- Bow Charge Plus
- No BS AI Projectile Dodge
- VioLens - A Killmove Mod SE
- VioLens - A Killmove Mod SE - Settings Loader

### Plugins actifs relevés

- `ValhallaCombat.esp`
- `WaitYourTurn.esp`
- `NPCs Take Cover.esp`
- `NPC No Block Exhaustion.esp`
- `NPC No Block Exhaustion - MCM.esp`
- `blockenchantments.esl`
- `ArcheryLocationalDamage.esp`
- `Bow Charge Plus.esp`
- `VioLens SE.esp`
- `NoBSAIProjectileDodge.esp`

### Décision

- Garder / validation provisoire.
- Pack cohérent avec la logique combat SKYFORGE.
- Valhalla Combat reste la base combat moderne.
- Wait Your Turn limite l’empilement d’ennemis.
- NPCs Take Cover et No BS AI Projectile Dodge améliorent l’IA défensive.
- NPC No Block Exhaustion limite le blocage infini.
- Archery Locational Damage / Bow Charge Plus renforcent l’arc.
- VioLens gère les killmoves.

### Ne pas faire maintenant

- Ne pas ajouter Valravn / Valvalis / Sekiro Combat maintenant.
- Ne pas mélanger d’autres overhauls combat majeurs.
- Ne pas relancer Pandora.
- Ne pas tester combat réel maintenant.
- Ne pas modifier les MCM.

### Dettes utiles

Tester plus tard :

- stamina / block ;
- esquive TK Dodge ;
- hit detection Precision ;
- killmoves VioLens ;
- comportement des archers ;
- couverture NPCs.

Vérifier plus tard la cohérence Valhalla Combat + Precision + TK Dodge + NPC No Block Exhaustion.

---

## Étape 666 — Followers / interactions / utility gameplay

### Pack concerné

Présent dans `[10 - GAMEPLAY COMBAT MAGIC PERKS]` :

- Nether's Follower Framework - FOMOD À REVOIR PLUS TARD
- Nether's Follower Framework - Legacy Settings Loader
- Simple Offence Suppression
- Simple Offence Suppression MCM - Block Friendly Fire
- I'm Talkin' Here
- Instantly Skip Dialogue NG
- Disable Follower Collision
- I'm Walkin' Here
- No Furniture Camera
- Pick Up Radius
- A Closer Look SSE

### Plugins actifs relevés

- `nwsFollowerFramework.esp`
- `Nether's Follower Framework - Settings Loader.esp`
- `Simple Offence Suppression MCM.esp`
- `ImTalkinHere.esp`
- `Pick Up Radius.esp`
- `ACloserLook.esp`

### Décision

- Garder / validation provisoire.
- Pack aligné avec la logique Nolvus Awakening / SKYFORGE : NFF, friendly fire, confort dialogue / caméra / interactions, collision followers, ramassage, zoom.

### Ne pas faire maintenant

- Ne pas réinstaller NFF.
- Ne pas refaire le FOMOD NFF maintenant.
- Ne pas régler les MCM maintenant.
- Ne pas ajouter de framework follower concurrent.
- Ne pas tester en jeu avec followers maintenant.

### Dettes utiles

- Revoir le FOMOD NFF plus tard.
- Reprendre les réglages MCM NFF / Simple Offence Suppression après stabilisation followers.
- Vérifier plus tard interactions avec les followers custom du bloc 11.
- Surveiller compatibilité NFF avec Inigo, Lucien, Auri, Remiel, Xelzaz, Thogra, Gore et Serana Dialogue Add-On.

---

## Étape 667 — Horses / bounty / misc gameplay

### Pack concerné

Présent dans `[10 - GAMEPLAY COMBAT MAGIC PERKS]` :

- Headhunter - Bounties Redone
- Simplest Horses
- Animated Whistling
- No Need to Ask
- State Your Claw
- Food For The Thirsty
- Skyrim's Got Talent - Improve as a Bard
- Switch Camera During Dialogue
- Dragon Claws Auto-Unlock
- Take a Peek - New Stealth Mechanic
- Classic Sprinting Redone
- Taunt Your Enemies
- Remote Interactions
- SkyParkour

### Plugins actifs relevés

- `Headhunter - Bounties Redone.esp`
- `SimplestHorses.esp`
- `NoNeedToAsk.esp`
- `FoodForTheThirsty.esp`
- `SkyrimsGotTalent-Bards.esp`
- `CameraSwitchDuringDialogue.esp`
- `Dragon Claws Auto-Unlock.esp`
- `Take A Peek - New Stealth Mechanic.esp`
- `Remote Interactions.esp`
- `Taunt Your Enemies.esp`
- `SkyParkour.esp`

### Décision

- Garder / validation provisoire.
- Pack de confort et gameplay léger : primes, chevaux, dialogue / caméra, griffes, furtivité, interactions à distance, parkour, barde.

### Ne pas faire maintenant

- Ne pas régler les MCM maintenant.
- Ne pas tester SkyParkour en jeu maintenant.
- Ne pas ajouter d’autre overhaul chevaux.
- Ne pas ajouter de gros système bounty concurrent.
- Ne pas relancer Pandora.

### Dettes utiles

- Tester plus tard SkyParkour en vraie cellule extérieure.
- Vérifier Take a Peek avec la furtivité / caméra.
- Vérifier Headhunter avec les quêtes de primes.
- Vérifier Simplest Horses avant ajout éventuel de mods chevaux plus lourds.
- Vérifier Skyrim’s Got Talent avec audio / bards / dialogues si conflit.

---

## Étape 668 — Races / werebeasts / vampires

### Pack concerné

Présent dans `[10.1 - RACES WEREBEASTS VAMPIRES]` :

- Aetherius - A Race Overhaul
- Mundus - A Standing Stone Overhaul
- Sacrosanct - Vampires of Skyrim
- Cover Your Head
- Sun Affects NPC Vampires
- Manbeast - A Werewolf Overhaul

### Plugins actifs relevés

- `Aetherius.esp`
- `Aetherius - Race Menu Racial Passive Descriptions.esp`
- `Mundus.esp`
- `MundusUSSEP.esp`
- `Manbeast.esp`
- `Sacrosanct - Vampires of Skyrim.esp`
- `CoverYourHead - Sacrosanct.esp`
- `SunAffectsNPCVampires - ExcludeFriendlies.esp`
- `SunAffectsNPCVampires.esp`

### Décision

- Garder / validation provisoire.
- Pack cohérent : Aetherius pour les races, Mundus pour les pierres dressées, Sacrosanct pour les vampires, Manbeast pour les loups-garous, Sun Affects NPC Vampires + Cover Your Head pour la logique vampire / soleil.

### Ne pas faire maintenant

- Ne pas ajouter d’autre overhaul races.
- Ne pas ajouter Growl en parallèle de Manbeast.
- Ne pas ajouter Better Vampires en parallèle de Sacrosanct.
- Ne pas modifier les MCM maintenant.
- Ne pas tester transformation / vampirisme maintenant.

### Dettes utiles

- Vérifier plus tard la cohérence Sacrosanct avec la future pile SexLab / vampire / NPC.
- Vérifier Manbeast quand les animations créatures / werewolf seront traitées.
- Vérifier les descriptions RaceMenu d’Aetherius.
- Vérifier Mundus avec les futurs mods perks / magie.

### État final post-668

- Aucun changement actif.
- SKSE/menu : OK sur le dernier test global.
- Masters manquants : aucun.
- Messages DLL : aucun.
- Plugins cochés : oui.
- Overwrite : vide.
- Compteur ESP + ESM non-light : **138**.
