# UI, HUD et menus — partie 3

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes 170 à 173 puis 176 à 178 classées dans le module **03 - UI HUD MENUS**.

---

### 170. Atlas Map Markers

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer Atlas Map Markers avec MCM et son loader de paramètres, en conservant une configuration prudente.

**Mods installés :**

- `Atlas Map Markers - Updated with MCM - A REINSTALL PLUS TARD`
- `Atlas Map Markers SE - Updated with MCM - Settings Loader`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/24104

**Choix FOMOD :**

- Aucun patch coché.
- Patch `Delphine’s Map Reveals Dragon Mounds` : décoché.
- Patch `Obscure’s College` : décoché.
- Patch `Ultimate College` : décoché.

**Raison du tag :**  
`Atlas Map Markers` est marqué `A REINSTALL PLUS TARD` car ses patches pourront être revus selon les futurs choix de quêtes, guildes et refontes de lieux.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 170 validée.

---

### 171. Contrôle placement Map UI

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Contrôler la cohérence du placement des éléments de carte locale, menu d’attente, marqueurs de carte et historique de dialogue.

**Placement / bloc validé :**

- `HD Local Map`
- `Local Map Upgrade`
- `Modern Wait Menu`
- `Atlas Map Markers - Updated with MCM - A REINSTALL PLUS TARD`
- `Atlas Map Markers SE - Updated with MCM - Settings Loader`
- `Dialogue History`

**Décision :**  
Placement validé. Aucun test supplémentaire nécessaire.

**Statut :**  
Étape 171 validée.

---

### 172. RaceMenu / création personnage

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Installer la base de création de personnage, les corrections RaceMenu et les ajouts de confort associés.

**Mods installés :**

- `RaceMenu Special Edition v0-4-16`
- `RaceMenu 0.4.16 Memory Leak Hotfix (SE)`
- `RaceMenu Undress`
- `Player Rotation in ShowRaceMenu`

**Liens :**

- RaceMenu  
  https://www.nexusmods.com/skyrimspecialedition/mods/19080
- RaceMenu Undress  
  https://www.nexusmods.com/skyrimspecialedition/mods/49889
- Player Rotation in ShowRaceMenu  
  https://www.nexusmods.com/skyrimspecialedition/mods/36095

**Décisions :**

- `RaceMenu Undress` est ajouté pour pouvoir déshabiller le personnage dans RaceMenu.
- Le mod de lumière RaceMenu est différé.
- Le slider apparaît comme `$Undress slider` : à vérifier / corriger plus tard.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 172 validée.

---

### 173. Pause sécurité avant départ alternatif

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Éviter de lancer une vraie création de personnage avant l’installation du départ alternatif officiel.

**Décision :**

- Ne pas lancer de vraie création personnage avant `Skyrim Unbound`.
- Préparer l’installation de `Skyrim Unbound`.

**Test :**  
Aucun test supplémentaire.

**Statut :**  
Étape 173 validée comme pause de sécurité.

---

### 176. Hotkeys UI légers

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Ajouter deux systèmes légers de gestion de touches / activation, sans surcharger prématurément le setup.

**Mods installés :**

- `Extended Hotkey System`
- `Dynamic Activation Key - MCM`

**Liens :**

- Extended Hotkey System  
  https://www.nexusmods.com/skyrimspecialedition/mods/32225
- Dynamic Activation Key  
  https://www.nexusmods.com/skyrimspecialedition/mods/96273

**Mods non installés / différés :**

- `Unbind Hidden Hotkeys 1-8`
- `Extended Hotkey System Tweaks`
- `Dynamic Activation Key Addons Collection`

**Note ajoutée :**  
`Better AltTab` est à installer plus tard avec un test individuel ALT+TAB en jeu.

**Test de validation :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- Aucun master manquant : OK
- Aucun message DLL : OK
- `Overwrite` vide : OK

**Statut :**  
Étape 176 validée.

---

### 177. Audit anti-doublon UI

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Éviter les doublons ou installations prématurées dans le bloc UI/HUD/Menus.

**Déjà installés :**

- `Better Container Controls for SkyUI`
- `Notification Log SSE`
- `Yes Im Sure`

**Différés / non installés :**

- `Show Follower Carry Weight`
- `Show Mount Carry Weight`
- `Too many notifications`

**Raisons :**

- `Show Follower Carry Weight` demande `Rogue’s Gallery`, donc il est différé.
- `Show Mount Carry Weight` est différé avec le même bloc de réflexion.
- `Too many notifications` est différé car le bloc UI contient déjà :
  - `Notification Log SSE`
  - `Notification Filter - Remove unwanted notifications - CONFIG INI A FAIRE PLUS TARD`

**Test :**  
Aucun test nécessaire.

**Statut :**  
Étape 177 validée comme audit / décisions anti-doublon.

---

### 178. Fin provisoire du bloc UI

**Module :** 03 - UI HUD MENUS

**Objectif :**  
Clôturer provisoirement le module UI/HUD/Menus avant de passer au module audio.

**Ajouts cosmétiques / captures / menu principal différés :**

- `Main Menu Customizer`
- `Main Menu Replacer`
- `Main Menu Randomizer`
- `Random Main Menu Music`
- `Photo Mode`
- `HideUI`

**Décision module :**

- Fin provisoire de `03 - UI HUD MENUS`.
- Passage au module `04 - AUDIO MUSIC SOUNDS`.

**Statut :**  
Étape 178 validée.

---

## État final provisoire du module UI

Le module `03 - UI HUD MENUS` est considéré comme provisoirement clos après l’étape 178.

Les éléments suivants restent volontairement différés :

- patches Vel’dun UI selon mods parents ;
- corrections / acceptation du `$Undress slider` de `RaceMenu Undress` ;
- mod de lumière RaceMenu ;
- `Better AltTab` avec test individuel ALT+TAB ;
- `Show Follower Carry Weight` / `Show Mount Carry Weight` ;
- `Too many notifications` ;
- ajouts cosmétiques de menu principal ;
- `Photo Mode` ;
- `HideUI`.
