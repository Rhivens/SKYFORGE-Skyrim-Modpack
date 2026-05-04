# Survival, immersion et roleplay

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes classées dans le module **12 - SURVIVAL IMMERSION ROLEPLAY**.

---

### 174. Skyrim Unbound Reborn

**Module :** 12 - SURVIVAL IMMERSION ROLEPLAY

**Objectif :**  
Installer le départ alternatif officiel de SKYFORGE et permettre les premiers tests ingame limités à la salle de départ.

**Mod installé :**

- `Skyrim Unbound Reborn - A REINSTALL PLUS TARD`

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/27962

**Placement MO2 :**  
Dans `12 - SURVIVAL IMMERSION ROLEPLAY`.

**Choix FOMOD :**

- `Female by Default` : coché
- `CC Fishing` : coché
- Tous les autres addons : décochés
- Tous les patches : `None` / décochés

**Patches non installés :**

- GDO
- RDO
- Timing is Everything
- At Your Own Pace
- Dragon Soul Absorb
- New Gnisis
- Thalmor
- Meeko
- OWL
- autres patches proposés mais non retenus à cette étape

**Raison du tag :**  
Le mod est renommé `A REINSTALL PLUS TARD` car les patches pourront être réévalués selon les futurs modules quêtes, dialogues, factions, dragons et overhauls.

**Test ingame individuel validé :**

- SKSE via MO2 : OK
- Menu principal atteint : OK
- `New Game` : OK
- Salle de départ Skyrim Unbound atteinte : OK
- Aucun CTD : OK
- Aucun master manquant : OK
- Aucun message DLL : OK

**Overwrite généré :**

`SKSE\Plugins\MenuMaid2_ConfigEditorIds.ini`

**Correction effectuée :**  
Le fichier a été déplacé dans :

`Menu Maid 2 - Generated INI`

**Résultat :**  
`Overwrite` vidé.

**Statut :**  
Étape 174 validée.

---

### 175. Sauvegarde test Unbound

**Module :** 12 - SURVIVAL IMMERSION ROLEPLAY

**Objectif :**  
Valider la stabilité minimale du départ alternatif et créer une sauvegarde technique temporaire.

**Effectué :**

- Jeu relancé.
- Salle Skyrim Unbound atteinte.
- Sauvegarde manuelle créée.
- Une autosave a aussi été créée automatiquement.

**Nom / note de sauvegarde :**

`SKYFORGE_STEP_174_UNBOUND_OK - TEST A SUPPRIMER`

**Décision :**  
Ces sauvegardes sont des sauvegardes techniques temporaires. Elles devront être supprimées avant la vraie partie finale.

**Validation :**

- Retour bureau sans CTD : OK
- `Overwrite` vide : OK
- RaceMenu accessible : OK
- `$Undress slider` visible : à corriger / vérifier plus tard

**Statut :**  
Étape 175 validée.

---

## Notes de sécurité après installation de Skyrim Unbound

- `Skyrim Unbound` est installé et validé comme départ alternatif officiel.
- Les tests ingame restent limités à la salle de départ.
- Les sauvegardes de test et autosaves devront être supprimées avant la partie finale.
- Ne pas commencer une vraie partie finale à ce stade.
