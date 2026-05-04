# UI, HUD et menus — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes 155 à 168 classées dans le module **03 - UI HUD MENUS**.

---

## État de départ

**Dernière étape précédente validée :**  
`Étape 154 — Vel’dun UI minimal`

**État validé avant reprise :**

- Skyrim SE 1.5.97 Best of Both Worlds : OK
- AE / Creation Club conservé : OK
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK
- Vel’dun UI visible au menu principal : OK

---

### 155. TrueHUD

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter la base HUD moderne utilisée par beaucoup de setups récents.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/62775

**Mod installé :**

- `TrueHUD - HUD Additions`

**Placement MO2 initial :**  
Dans `03 - UI HUD MENUS`, sous :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Placement ajusté plus tard :**  
TrueHUD a ensuite été replacé dans le bloc HUD fonctionnel, entre `SkyHUD` et les widgets STB.

**Choix :**

- Fichier principal.
- Version compatible Skyrim SE 1.5.97 / Pre-AE si choix proposé.
- Pas de preset externe.
- Pas de réinstallation de Vel’dun UI à cette étape.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 155 validée.

---

### 156. STB Widgets + STB Active Effects

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter les widgets HUD modernes compatibles avec la logique Vel’dun UI.

**Liens :**

- STB Widgets  
  https://www.nexusmods.com/skyrimspecialedition/mods/136148
- STB Active Effects  
  https://www.nexusmods.com/skyrimspecialedition/mods/140002

**Mods installés :**

- `STB Widgets`
- `STB Active Effects`

**Choix FOMOD retenus pour STB Widgets :**

- `SkyHUD 16x9` : coché
- `SkyHUD 21x9` : décoché
- `None` : décoché
- Option `TrueHUD 16x9` retenue également quand proposée

**Choix FOMOD retenus pour STB Active Effects :**

- `Survival Mode` : coché
- `Mysticism` : décoché

**Placement MO2 retenu après ajustement :**

Dans `03 - UI HUD MENUS` :

1. `SkyHUD - A REINSTALL PLUS TARD`
2. `TrueHUD - HUD Additions`
3. `STB Widgets`
4. `STB Active Effects`
5. `Vel'dun UI - A REINSTALL PLUS TARD`

**Note :**  
Vel’dun UI reste à réinstaller plus tard pour activer les patches `TrueHUD` / `STB` utiles.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 156 validée.

---

### 157. Dragonborn Reskin pour STB

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Tester les icônes Dragonborn sur les widgets STB.

**Liens :**

- Dragonborn Reskin - STB Widgets  
  https://www.nexusmods.com/skyrimspecialedition/mods/140283
- Dragonborn Reskin - STB Active Effects  
  https://www.nexusmods.com/skyrimspecialedition/mods/149364

**Mods installés :**

- `Dragonborn Reskin - STB Widgets`
- `Dragonborn Reskin - STB Active Effects`

**Placement MO2 retenu :**

Dans `03 - UI HUD MENUS` :

1. `SkyHUD - A REINSTALL PLUS TARD`
2. `TrueHUD - HUD Additions`
3. `STB Widgets`
4. `STB Active Effects`
5. `Vel'dun UI - A REINSTALL PLUS TARD`
6. `Dragonborn Reskin - STB Widgets`
7. `Dragonborn Reskin - STB Active Effects`

**Règle retenue :**  
Les reskins Dragonborn doivent gagner les conflits d’icônes sur Vel’dun UI pour ce test.

**Test de validation :**

- Load order panneau gauche modifié : OK
- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 157 validée.

---

### 158. Wheeler + Dragonborn Wheeler Reskin

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer la roue d’actions rapide puis son reskin Dragonborn.

**Liens :**

- Wheeler - Quick Action Wheel Of Skyrim  
  https://www.nexusmods.com/skyrimspecialedition/mods/97345
- Dragonborn - Wheeler Reskin  
  https://www.nexusmods.com/skyrimspecialedition/mods/100043

**Mods installés :**

- `Wheeler - Quick Action Wheel Of Skyrim`
- `Dragonborn - Wheeler Reskin`

**Placement MO2 retenu :**

Dans `03 - UI HUD MENUS` :

1. `SkyHUD - A REINSTALL PLUS TARD`
2. `TrueHUD - HUD Additions`
3. `STB Widgets`
4. `STB Active Effects`
5. `Wheeler - Quick Action Wheel Of Skyrim`
6. `Vel'dun UI - A REINSTALL PLUS TARD`
7. `Dragonborn Reskin - STB Widgets`
8. `Dragonborn Reskin - STB Active Effects`
9. `Dragonborn - Wheeler Reskin`

**Règle retenue :**

- Les mods fonctionnels chargent d’abord.
- Vel’dun UI fournit l’habillage global.
- Les reskins Dragonborn gagnent les conflits visuels.

**Décision différée associée :**  
`dMenu` et `dMenu NG` sont à installer comme core utilities pour Wheeler.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 158 validée.

---

### 160. Infinity UI + Compass Navigation Overhaul

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter le framework UI de compas et l’overhaul moderne du compas.

**Liens :**

- Infinity UI  
  https://www.nexusmods.com/skyrimspecialedition/mods/74483
- Compass Navigation Overhaul  
  https://www.nexusmods.com/skyrimspecialedition/mods/74484

**Mods installés :**

- `Infinity UI`
- `Compass Navigation Overhaul`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, après les éléments HUD fonctionnels et avant Vel’dun UI :

1. `Wheeler - Quick Action Wheel Of Skyrim`
2. `Infinity UI`
3. `Compass Navigation Overhaul`
4. `Vel'dun UI - A REINSTALL PLUS TARD`

**Choix :**

- Fichiers principaux.
- Version SE / 1.5.97 / Pre-AE si choix proposé.
- Configuration par défaut.
- Pas de reskin compas.
- Pas de `CoMAP` / `Atlas` / `Local Map` à cette étape.

**Note MO2 :**  
Un log MO2 a été consulté après coup. Les avertissements observés n’étaient pas bloquants :

- update MO2 disponible ;
- avertissements FOMOD / encodage ;
- erreurs d’endorsement Nexus ;
- warnings PNG ;
- aucun impact jeu constaté.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 160 validée.

---

### 161. Better Third Person Selection

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Améliorer la sélection des objets en troisième personne.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/64339

**Mod installé :**

- `Better Third Person Selection - BTPS`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, après :

`Compass Navigation Overhaul`

et avant :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Décision de classement :**  
Même si BTPS est un plugin SKSE/DLL, il reste dans `03 - UI HUD MENUS`, car son rôle principal est l’interface, le HUD et la sélection à l’écran, pas une core utility générale.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 161 validée.

---

### 162. QuickLoot IE différé

**Module :** 03 - UI HUD MENUS

**Objectif initial :**  
Ajouter un menu de loot rapide moderne.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/120075

**Mod concerné :**

- `QuickLoot IE`

**Décision finale :**  
`QuickLoot IE` est différé / non installé.

**Raison :**  
Le futur setup SexLab / Devious / Cursed Loot rend QuickLoot potentiellement contre-productif :

- risque de casser l’immersion ;
- fouille moins manuelle des conteneurs ;
- moins de tension liée aux coffres et pièges ;
- interface trop moderne pour une logique loot dangereux / surprise.

**Non installés :**

- `QuickLoot IE`
- patch Vel’dun UI QuickLoot
- reskins QuickLoot

**Statut :**  
Étape 162 validée comme décision de différer.

---

### 163. Dialogue History / Menu Maid 2

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter un historique de dialogues et un gestionnaire de menus MCM.

**Liens :**

- Dialogue History  
  https://www.nexusmods.com/skyrimspecialedition/mods/114238
- Menu Maid 2 - MCM Manager  
  https://www.nexusmods.com/skyrimspecialedition/mods/67556

**Mods installés :**

- `Dialogue History`
- `Menu Maid 2 - MCM Manager`
- `Menu Maid 2 - Generated INI`

**Note de classement :**  
`ImGui Icons`, validé dans la même étape globale, est classé dans `02_skse_core_utilities_part_2.md`.

**Placement MO2 :**

- `Dialogue History` → `03 - UI HUD MENUS`
- `Menu Maid 2 - MCM Manager` → `03 - UI HUD MENUS`
- `Menu Maid 2 - Generated INI` → juste sous `Menu Maid 2 - MCM Manager`

**Overwrite :**  
`Menu Maid 2` a généré :

`Overwrite\SKSE\Plugins\MenuMaid2.ini`

**Action effectuée :**

- Création du mod dédié `Menu Maid 2 - Generated INI`.
- `Overwrite` vidé.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `MenuMaid2.ini` généré : OK
- Mod dédié créé : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 163 validée pour la partie UI/HUD/Menus.

---

### 164. Oxygen Meter 2

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter l’indicateur d’oxygène moderne.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/64532

**Mod installé :**

- `Oxygen Meter 2`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, dans le bloc HUD, avant :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Choix :**

- Fichier compatible Skyrim SE 1.5.97 / Pre-AE.
- Pas de patch Nordic / Untarnished / Edge.
- Pas de réinstallation Vel’dun UI.

**Décision :**  
`Dragonborn Reskin - Oxygen Meter 2` n’est pas installé.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 164 validée.

---

### Correction associée à l’étape 153. SkyHUD Patch v090B

**Contexte :**  
Le fichier optionnel SkyHUD suivant a été repéré après coup :

`Patch - SkyHUD v090B`

**Action effectuée :**  
Patch installé comme mod séparé :

`Patch - SkyHUD 0.90.1B`

**Placement MO2 :**

1. `SkyHUD - A REINSTALL PLUS TARD`
2. `Patch - SkyHUD 0.90.1B`
3. `TrueHUD - HUD Additions`

**Message MO2 observé :**

`failed to write D:/SKYFORGE/MO2/mods/Patch - SkyHUD 0.90.1B/meta.ini: error 1`

**Vérification :**

- `meta.ini` existe bien.
- Il contient des informations.
- Aucun impact constaté sur le lancement du jeu.

**Statut :**  
Correction validée, documentée comme correction associée à l’étape 153.

---

### 165. Show Player In Menus

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Afficher le personnage dans certains menus, utile pour l’immersion et les futurs modules outfits / armures / NSFW.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/81291

**Mod installé :**

- `Show Player In Menus`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, après :

`Menu Maid 2 - Generated INI`

et avant :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Choix :**

- Fichier principal.
- Pas de preset / patch optionnel.
- Pas de réinstallation Vel’dun UI.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 165 validée.

---

### 166. Dragonborn SkyUI Category and Fav Icons

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer uniquement les icônes Dragonborn pour les catégories SkyUI et les favoris.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/132019

**Mod installé :**

- `Dragonborn Reskin - SkyUI Category and Fav Icons`

**Choix retenu :**

- Installer uniquement la version `Dragonborn Reskin - SkyUI Category and Fav Icons`.
- Ne pas installer la version avec description.

**Raison :**

- On veut seulement les icônes de catégories SkyUI et favoris.
- On évite d’ajouter des descriptions / textes supplémentaires.
- Moins de risques avec Vel’dun UI, les traductions FR futures ou les mods d’inventaire.

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, sous les autres reskins Dragonborn :

1. `Dragonborn Reskin - STB Widgets`
2. `Dragonborn Reskin - STB Active Effects`
3. `Dragonborn - Wheeler Reskin`
4. `Dragonborn Reskin - SkyUI Category and Fav Icons`

**Mods non installés :**

- `Dragonborn Reskin - Compass and Weather`
- autres reskins UI Dragonborn non souhaités

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 166 validée.

---

### 167. Bloc carte / wait menu

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter un bloc UI autour de la carte locale et du menu d’attente.

**Liens :**

- HD Local Map  
  https://www.nexusmods.com/skyrimspecialedition/mods/74722
- Local Map Upgrade  
  https://www.nexusmods.com/skyrimspecialedition/mods/129756
- Modern Wait Menu  
  https://www.nexusmods.com/skyrimspecialedition/mods/117661

**Mods installés :**

- `HD Local Map`
- `Local Map Upgrade`
- `Modern Wait Menu`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, avant :

`Dialogue History` / `Menu Maid 2` / `Vel'dun UI`

**Ordre retenu :**

1. `HD Local Map`
2. `Local Map Upgrade`
3. `Modern Wait Menu`

**Choix :**

- Fichiers principaux.
- Pas de patch widescreen Modern Wait Menu car écran 16:9.
- Pas de traduction FR.
- Pas de patch Vel’dun UI maintenant.

**Test groupé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 167 validée.

---

### 168. Bloc HUD confort léger

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter deux éléments HUD / QoL légers.

**Liens :**

- Horse Stamina HUD - Script-Free  
  https://www.nexusmods.com/skyrimspecialedition/mods/47076
- Floating Damage  
  https://www.nexusmods.com/skyrimspecialedition/mods/14332

**Mods installés :**

- `Horse Stamina HUD - Script-Free`
- `Floating Damage`

**Placement MO2 :**  
Dans `03 - UI HUD MENUS`, après :

`Show Player In Menus`

et avant :

`Vel'dun UI - A REINSTALL PLUS TARD`

**Mods non installés / différés :**

- `Toggle Compass Hotkey` : non retenu
- `HideUI` : différé
- `Photo Mode` : à installer plus tard, avant les vrais tests ingame / screenshots avec `Skyrim Unbound`

**Décision Photo Mode :**  
Aucun mod déjà installé ne remplace vraiment un vrai photomode global :

- `TrueHUD` peut gérer certains éléments HUD, mais pas un photomode complet.
- `Infinity UI` est un framework.
- `moreHUD` ajoute des infos de ciblage.
- `Photo Mode` sera plus adapté que `HideUI` pour les screenshots avancés.

**Test groupé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL/master : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 168 validée.

---

## État final après l’étape 168

**Dernière étape validée :**  
`Étape 168 — Bloc HUD confort léger`

**Module en cours :**  
`03 - UI HUD MENUS`

**État validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun message DLL : OK
- Aucun master manquant : OK
- `Overwrite` vide : OK

**Règles confirmées :**

- Pas de LOOT pour l’instant.
- Ne pas toucher au panneau droit sauf missing master.
- Tests limités au menu principal tant que `Skyrim Unbound` n’est pas installé.
- `Skyrim Unbound` reste le départ alternatif officiel et définitif.
- Le crosshair vanilla est conservé.
- `QuickLoot IE` est différé pour préserver l’immersion future avec `Cursed Loot`.
- `Photo Mode` est différé jusqu’aux futurs tests ingame / screenshots.
- Les blocs de mods pourront être plus groupés à l’avenir quand les mods sont légers / visuels / non sensibles.
