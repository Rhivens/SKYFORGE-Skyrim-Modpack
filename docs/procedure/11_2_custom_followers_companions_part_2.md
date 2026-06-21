# Module 11.2 — Custom followers & companions — partie 2

Ce fichier documente les étapes **510 à 526** du projet SKYFORGE.

## Statut du bloc

- **Bloc principal :** `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`
- **Statut :** enrichi et stabilisé après étape 526
- **Compteur final documenté :** 128 ESP + ESM non-light
- **Overwrite :** vide sur les tests documentés
- **LOOT :** non lancé
- **DynDOLOD / LOD :** non générés
- **BodySlide Output :** non généré
- **Pandora :** non relancé ; Output existant conservé depuis l'étape 411
- **Mods `- FR` :** non activés

## Méthode

- Les ajouts sont limités aux followers déjà installés, à leurs patches directs, à leurs replacers visuels ou à des addons légers.
- Les followers disposant de leur propre système ne doivent pas être importés / gérés automatiquement dans NFF.
- Les patches dépendants de quêtes, worlds, DBVO, systèmes spécialisés, traductions `- FR` ou masters absents restent différés.
- Les animations spécifiques à un follower peuvent rester dans ce bloc quand elles ne modifient pas le framework global d'animations.
- Les suffixes MO2 de suivi temporaire restent régis par `docs/procedure/01_regles_mo2_skyforge.md`.

---

# Étape 510 — Serana Dialogue Add-On SE

## Statut

Validée.

## Mod installé

- `Serana Dialogue Add-On SE`

## Choix de fichier

- Version installée : 4.3.2
- Version Legacy 4.3.0 non retenue.

## Décision

Conserver.

La version principale maintenue est privilégiée.  
La version Legacy reste différée malgré certaines compatibilités anciennes, car elle est indiquée comme non supportée.

## Patches différés

- `Serana Dialogue Add-On Patch Hub`
- patches de frameworks spécialisés / anciens frameworks
- patches DBVO
- patches de compatibilité quêtes ou frameworks optionnels

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, Overwrite vide.

## Compteur

128 → 129 ESP + ESM non-light.

---

# Étape 511 — Serana Re-Imagined

## Statut

Validée.

## Mod installé

- `Serana Re-Imagined`

## Décision

Conserver.

Le mod est retenu comme replacer visuel NPC spécifique à Serana.  
Il reste dans `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`, et non dans le bloc body/skins global.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

129 ESP + ESM non-light.  
Pas d'augmentation du compteur.

---

# Étape 512 — Mini-pack visuel Serana

## Statut

Validée.

## Mod installé

- `Hood Plus Hair for Serana Re-Imagined`

## Mod non installé

- `Serana Re-Imagined - Eyes Re-Visited`

## Décision

Conserver `Hood Plus Hair for Serana Re-Imagined`.

Fabien préfère conserver les yeux d'origine de `Serana Re-Imagined`.  
Aucun override d'yeux Serana n'est ajouté à cette étape.

## Placement

```txt
Serana Dialogue Add-On SE
Serana Re-Imagined
Hood Plus Hair for Serana Re-Imagined
```

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 513 — Replacers visuels Inigo, Lucien, Auri et Remiel

## Statut

Validée.

## Mods installés

- `Dovahnique's High Poly Inigo`
- `Dovahnique's High Poly Inigo Replacer - ESPFE`
- `Cosmos Lucien Replacer`
- `Majestic Auri - A visual replacer`
- `Majestic Auri - A Visual Replacer - Human Teeth`
- `BiR's Remiel Replacer`

## Décisions

- `Dovahnique's High Poly Inigo` : main file + option ESPFE installés.
- `Cosmos Lucien Replacer` : FOMOD validé avec l'option `BNP NEW`.
- `Majestic Auri` : main file + option `Human Teeth` installés.
- `BiR's Remiel Replacer` : installé sans patch additionnel.

Les options morphologie masculine globale du replacer Lucien ne sont pas retenues afin de ne pas introduire une logique body masculin globale depuis un replacer isolé.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 514 — Patches banter et compatibilité SDA ciblés

## Statut

Validée.

## Mods installés

- `Song of the Green Auri Follower Inigo Banter Patch ESLified`
- `Serana Dialogue Add-On Patch Hub - FOMOD A REVOIR PLUS TARD`

## Décisions

### Auri ↔ Inigo

Le patch banter Auri ↔ Inigo est installé et conservé, car Auri et Inigo sont déjà présents et validés.

### Serana Dialogue Add-On Patch Hub

Le patch hub est installé avec le suffixe :

```txt
Serana Dialogue Add-On Patch Hub - FOMOD A REVOIR PLUS TARD
```

De nombreuses options sont différées car leurs masters ou modules ne sont pas encore validés.

## Options explicitement différées

Les options liées à des frameworks spécialisés, quêtes, armures, chevaux, compatibilités vampires, sleep patches, flèches spéciales ou modules optionnels restent différées jusqu'à présence des masters et audit dédié.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 515 — Addons Skyrim's Got Talent pour Inigo, Auri et Xelzaz

## Statut

Validée.

## Mods installés

- `Skyrim's Got Talent - Inigo`
- `Skyrim's Got Talent - Auri`
- `Skyrim's Got Talent - Xelzaz`

## Décision

Conserver.

Ces addons sont cohérents car ils ciblent des followers déjà installés et validés : Inigo, Auri et Xelzaz.

## Mods non installés / différés

- `Free Movement for SGT`
- `Bruma Mini Patch`
- `Player Reactions Addon`
- `Skyrim's Got Talent FR`

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 516 — Xelzaz Wyrmstooth / Sirenroot patches

## Statut

Différée.

## Mods concernés

- `Xelzaz Follower Wyrmstooth Patch - DECOCHE EN ATTENTE DU BLOC QUETES`
- `Xelzaz Sirenroot Patch - DECOCHE EN ATTENTE DU BLOC QUETES`

## Raison

Les deux patches provoquent des masters manquants si activés maintenant.  
Le bloc `[11 - QUESTS WORLDS FOLLOWERS]` est encore vide à ce stade.

## Action retenue

- Ne pas cocher ces deux patches.
- Conserver les suffixes `DECOCHE EN ATTENTE DU BLOC QUETES`.
- Reprendre ces patches après installation et validation des mods quêtes/worlds concernés.

## Compteur

129 ESP + ESM non-light.

---

# Étape 516 bis — Snazzy Items for Inigo et Auri

## Statut

Validée.

## Mods installés

- `Snazzy Items for Inigo`
- `Snazzy Items for Auri (Song of the Green)`

## Décision

Conserver.

Ces deux mods ciblent des objets liés à des followers déjà présents et validés : Inigo et Auri.

## Mods non installés / différés

- `Mr. Dragonfly ENB Particle Light` — finalement repris à l'étape 517 bis
- `Snazzy Items for 3DNPC`
- `Snazzy Items for Kaidan`
- autres patches Snazzy non liés aux followers validés

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 517 — Press E to Heal Followers

## Statut

Différée.

## Raison

Le mod touche aux interactions avec les followers en bleedout.  
Les futurs systèmes de récupération / knocked down / revive pourront aussi intervenir sur ces états.

## Action retenue

- Ne pas installer `Press E to Heal Followers` maintenant.
- Revoir ce mod pendant le futur module dédié aux systèmes de récupération.
- Vérifier alors s'il reste utile, redondant ou conflictuel.

## Compteur

129 ESP + ESM non-light.

---

# Étape 517 bis — Mr. Dragonfly ENB Particle Light

## Statut

Validée.

## Mod installé

- `Mr. Dragonfly ENB Particle Light`

## Choix retenu

- Couleur retenue par Fabien : `Lavender`

## Décision

Conserver.

Le mod est retenu comme addon visuel léger lié à Inigo.

## Placement indicatif

```txt
INIGO
Dovahnique's High Poly Inigo
Dovahnique's High Poly Inigo Replacer - ESPFE
Snazzy Items for Inigo
Mr. Dragonfly ENB Particle Light
```

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, Overwrite vide.

## Compteur

129 ESP + ESM non-light.

---

# Étape 518 — Axarien's Animations pour followers installés

## Statut

Validée.

## Mods installés

- `Axarien's Animations - Custom Followers - Lucien`
- `Axarien's Animations - Custom Followers - Kaidan 2`
- `Axarien's Animations - Custom Followers - Auri`
- `Axarien's Animations - Custom Followers - Inigo`

## Décision

Conserver les fichiers séparés plutôt que l'AIO.

Fabien a retenu les fichiers séparés pour éviter d'ajouter le module Val Serano alors que Val Serano n'est pas installé dans SKYFORGE.

## Fichiers non installés

- AIO avec Val Serano
- `Lucien - Instant Results`
- `Inigo - Cat Sprint`

## Placement

Conserver dans `[11.2 - CUSTOM FOLLOWERS COMPANIONS]`.

Ces animations sont spécifiques à des followers précis et ne constituent pas un framework global d'animations, skeleton, physics ou comportement Pandora.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Pandora

- Pandora non relancé.
- Le compteur d'animations a augmenté au menu principal, mais cela est attendu pour des animations conditionnelles chargées par le jeu/OAR.
- Aucune génération Pandora n'est nécessaire à cette étape.

## Compteur

129 ESP + ESM non-light.

---

# Étape 519 — Exclusion définitive de Kaidan 2

## Statut

Validée comme exclusion définitive.

## Mods retirés / décochés

- `Kaidan 2 - PATCHES A VOIR PLUS TARD`
- `Axarien's Animations - Custom Followers - Kaidan 2`

## Décision

Exclure définitivement Kaidan 2 du modpack SKYFORGE.

## Raison

Fabien ne considère pas Kaidan 2 comme un follower important pour son modpack.  
L'exclusion réduit les besoins futurs en patches, interactions, replacers, modules romance et compatibilités spécialisées.

## Également exclus

- Kaidan All-In-One Installer
- Kaidan Extended Edition
- Kaidan Immersive Features
- Kaidan Inigo interactions
- Kaidan replacers
- Kaidan SGT patches
- Kaidan patches spécialisés éventuels
- autres patches ou addons Kaidan

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

129 → 128 ESP + ESM non-light.

---

# Étape 520 — Menagerie - An Anniversary Edition Pet Overhaul

## Statut

Validée.

## Mod installé

- `Menagerie - An Anniversary Edition Pet Overhaul`

## Choix FOMOD retenus

- Menagerie - Master File
- Menagerie - Bone Wolf
- Menagerie - Dwarven Armored Mudcrab
- Menagerie - Nix-Hound
- Menagerie - Pets of Skyrim
- Menagerie - Saints and Seducers
- Menagerie - Vanilla Pets

## Options non retenues / différées

- Menagerie - ECSS
- Menagerie - Bone Wolf - Mysticism Addon
- Menagerie - ECSS - Gibberish
- Menagerie - Vanilla Pets - Bring Meeko to Lod
- Menagerie - Vanilla Pets - Vigilance the Husky

## Décision

Conserver.

Le mod améliore les pets AE/CC présents dans SKYFORGE sans ouvrir un nouveau système follower humanoïde.

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

# Étape 521 — Mini-pack visuel Xelzaz

## Statut

Validée.

## Mods installés

- `Xelzaz' Telvanni Spellsword Armor Enhanced`
- `Lulu's Xelzaz - Xelzaz Visual replacer`

## Référence

Proposition SKYFORGE.

## Décision

Conserver.

Ces mods ciblent uniquement Xelzaz : amélioration visuelle de l'équipement et replacer visuel dédié.

## Patches toujours différés

- `Xelzaz Follower Wyrmstooth Patch - DECOCHE EN ATTENTE DU BLOC QUETES`
- `Xelzaz Sirenroot Patch - DECOCHE EN ATTENTE DU BLOC QUETES`

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

# Étape 522 — FDE Aela Patch - Thogra

## Statut

Différée.

## Mod concerné

- `FDE Aela Patch - Thogra`

## Raison

Le patch existe, mais Thogra est encore marqué :

```txt
Thogra gra-Mugur - Orc Follower and Quest - PATCHES A VOIR PLUS TARD
```

Le patch sera repris après stabilisation du FOMOD/patches Thogra.

## Action retenue

- Ne pas installer maintenant.
- Conserver le suffixe `PATCHES A VOIR PLUS TARD`.
- Revoir les patches Aela ↔ Thogra lors de l'audit Thogra.

## Compteur

128 ESP + ESM non-light.

---

# Étape 523 — Audit Thogra gra-Mugur

## Statut

Validée comme audit.

## Mod vérifié

- `Thogra gra-Mugur - Orc Follower and Quest - PATCHES A VOIR PLUS TARD`

## Résultat

- Mod ID installé : 120007
- Le mod installé correspond bien à la version moderne `(NEW) Thogra gra-Mugur - Orc Follower and Quest`.

## Décision

Conserver.

Aucun remplacement nécessaire.

## Action retenue

- Ne pas réinstaller Thogra.
- Conserver temporairement le suffixe `PATCHES A VOIR PLUS TARD`.
- Reprendre les patches Thogra dans une étape dédiée.

## Test

Aucun test SKSE requis, car aucune modification MO2 n'a été faite.

## Compteur

128 ESP + ESM non-light.

---

# Étape 524 — FDE Aela Patch - Thogra

## Statut

Validée.

## Mod installé

- `FDE Aela Patch - Thogra`

## Décision

Conserver.

Le patch de dialogue entre Aela et Thogra est installé maintenant que Thogra a été vérifiée comme version moderne Nexus ID 120007.

## Placement indicatif

```txt
FDE Illia Inigo patch
FDE Brelyna Inigo patch
FDE Jenassa Inigo patch
FDE Aela Inigo Patch
FDE Aela Patch - Thogra
```

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugin coché, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

# Étape 525 — Audit Gore - A Companion Mod

## Statut

Validée comme audit.

## Mod vérifié

- `Gore - A Companion Mod - FOMOD & PATCHES A REVOIR PLUS TARD`

## État constaté

- Mod ID : 85298
- Version installée : 1.8.11
- Un seul mod Gore installé dans MO2

## Décision

Audit validé, sans modification.

## Action retenue

- Aucun mod à installer.
- Aucun patch Gore à ajouter maintenant.
- Conserver le suffixe `FOMOD & PATCHES A REVOIR PLUS TARD`.

## Points à revoir plus tard

- Gore - Vigilant patch
- Gore - Saints and Seducers EC
- Press E to Heal éventuel
- GORE - Miscellaneous Patches
- replacers éventuels Gore

## Test

Aucun test SKSE requis, car aucune modification MO2 n'a été faite.

## Compteur

128 ESP + ESM non-light.

---

# Étape 526 — Show Follower Carry Weight

## Statut

Validée.

## Mod installé

- `Show Follower Carry Weight`

## Décision

Conserver.

Le mod ajoute uniquement un affichage pratique du poids porté des followers dans le menu de troc, sans modifier le système follower ni l'équilibrage du poids porté.

## Mods non installés / différés

- `Show Mount Carry Weight`
- `Show Mount and Pet Carry Weight`
- `Unlimited Followers Carry Weight`
- `Unlimited Followers Carry Weight - Redone`
- `Unlimited Followers Carry Weight - Redone for SPID`

## Test

Menu principal OK, aucun master manquant, aucun message DLL bloquant, plugins cochés, Overwrite vide.

## Compteur

128 ESP + ESM non-light.

---

## État final après étape 526

- Le bloc `[11.2 - CUSTOM FOLLOWERS COMPANIONS]` est enrichi avec Serana/SDA, replacers ciblés, addons légers, pets AE/CC, Xelzaz visuel et confort follower.
- Kaidan 2 est exclu définitivement.
- Les patches quêtes/worlds, DBVO, traductions `- FR` et patches dépendant de masters absents restent différés.
- Compteur final : 128 ESP + ESM non-light.
- Prochaine série documentée : retour ponctuel au bloc `[11.1 - FOLLOWERS NPCS DIALOGUES]` pour les étapes 527 à 530.
