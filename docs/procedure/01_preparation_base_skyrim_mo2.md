# Préparation base Skyrim / MO2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Contient les étapes **1 à 8**.

---

### 1. Préparation de Skyrim

**Objectif :**  
Installer Skyrim Anniversary Edition via Steam et lancer le jeu une première fois pour initialiser les fichiers de base et le contenu AE / Creation Club.

**Lien :**  
https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/

**Résultat attendu :**  
Skyrim est installé, initialisé, et le contenu Anniversary Edition est présent.

---

---

### 2. Verrouillage des mises à jour Steam

**Objectif :**  
Empêcher Steam de mettre à jour Skyrim automatiquement pendant la construction du modpack.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
L’option Steam est réglée sur “Attendre que je lance le jeu” et le fichier `appmanifest_489830.acf` est en lecture seule.

---

---

### 3. Création du dossier Stock Game SKYFORGE

**Objectif :**  
Créer une copie isolée de Skyrim dans un dossier dédié au projet SKYFORGE.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le dossier `D:\SKYFORGE\Stock Game\` contient une copie complète du dossier Skyrim Steam.

---

---

### 4. Downgrade vers Skyrim SE 1.5.97

**Objectif :**  
Appliquer le downgrade **Best of Both Worlds** sur le Stock Game afin de conserver le contenu AE tout en utilisant l’exécutable Skyrim SE 1.5.97.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/169962

**Résultat attendu :**  
`SkyrimSE.exe` dans `D:\SKYFORGE\Stock Game\` est en version `1.5.97.0`.

---

---

### 5. Installation de SKSE 1.5.97

**Objectif :**  
Installer SKSE compatible Skyrim SE 1.5.97 dans le Stock Game.

**Lien :**  
https://skse.silverlock.org/

**Résultat attendu :**  
`skse64_loader.exe`, `skse64_1_5_97.dll` et `skse64_steam_loader.dll` sont présents dans `D:\SKYFORGE\Stock Game\`.

---

---

### 6. Installation de Mod Organizer 2 portable

**Objectif :**  
Installer MO2 en instance portable dédiée à SKYFORGE.

**Lien :**  
https://www.nexusmods.com/skyrimspecialedition/mods/6194

**Résultat attendu :**  
MO2 2.4.4 est installé dans `D:\SKYFORGE\MO2\` et pointe vers `D:\SKYFORGE\Stock Game\SkyrimSE.exe`.

---

---

### 7. Création du profil MO2 de base

**Objectif :**  
Créer un profil isolé pour SKYFORGE.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Le profil `00 - SKYFORGE Base` existe avec sauvegardes et fichiers INI spécifiques au profil activés.

---

---

### 8. Création de l’ossature des séparateurs MO2

**Objectif :**  
Créer une structure visuelle propre dans le panneau gauche de MO2.

**Lien :**  
Aucun téléchargement requis.

**Résultat attendu :**  
Les séparateurs SKYFORGE sont créés, de `00 - BASE GAME` à `18 - TRADUCTIONS FR`, avec `Overwrite` conservé tout en bas.

---
