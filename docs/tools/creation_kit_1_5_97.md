# SKYFORGE — Installation du Creation Kit pour Skyrim SE 1.5.97

Procédure validée pour installer et lancer le **Creation Kit** dans l’environnement SKYFORGE :

- Skyrim SE runtime **1.5.97** ;
- contenus AE / Creation Club conservés ;
- **Stock Game** séparé ;
- **Mod Organizer 2 portable** ;
- chemin de référence : `D:\SKYFORGE`.

Cette procédure s’inspire de la méthode utilisée par Nolvus, adaptée et testée pour SKYFORGE.

---

## 1. Objectif

Installer un Creation Kit fonctionnel dans :

```text
D:\SKYFORGE\Stock Game\
```

afin de pouvoir le lancer depuis MO2, notamment pour :

- ouvrir / sauvegarder proprement certains plugins ;
- convertir ponctuellement des plugins **Form 43** vers **Form 44** ;
- inspecter des cellules, quêtes ou dialogues lorsque xEdit ne suffit pas ;
- disposer d’un CK portable avec le dossier SKYFORGE.

> Règle de prudence : xEdit reste l’outil principal d’analyse. Le Creation Kit ne doit être utilisé que lorsque nécessaire.

---

## 2. Pré-requis

- Skyrim Special Edition installé via Steam.
- Creation Kit installé depuis la bibliothèque Steam.
- MO2 portable déjà configuré pour SKYFORGE.
- Dossier Stock Game existant :

```text
D:\SKYFORGE\Stock Game\
```

- Steam lancé au moins une fois sur la machine.

---

## 3. Installer le Creation Kit via Steam

Dans Steam :

1. Ouvrir la bibliothèque.
2. Afficher les **Outils**.
3. Installer :

```text
Skyrim Special Edition Creation Kit
```

Le Creation Kit s’installe dans le dossier Skyrim officiel Steam, par exemple :

```text
D:\STEAM\steamapps\common\Skyrim Special Edition\
```

Ne pas utiliser directement cette version pour SKYFORGE.

---

## 4. Télécharger les bons depots Steam du Creation Kit

Ouvrir la console Steam :

1. `Win + R`
2. Saisir :

```text
steam://open/console
```

3. Dans la console Steam, lancer successivement les deux commandes suivantes.

### Depot 1

```text
download_depot 1946180 1946182 5099162879680505807
```

Attendre la fin complète du téléchargement.

### Depot 2

```text
download_depot 1946180 1946183 1633303557398589581
```

Attendre la fin complète du téléchargement.

Les fichiers doivent apparaître dans un dossier de ce type :

```text
D:\STEAM\steamapps\content\app_1946180\
```

avec les deux dossiers :

```text
depot_1946182
depot_1946183
```

---

## 5. Copier les fichiers dans le Stock Game SKYFORGE

### Depuis `depot_1946182`

Copier :

```text
CreationKit.exe
```

vers :

```text
D:\SKYFORGE\Stock Game\
```

### Depuis `depot_1946183`

Copier **tout le contenu** du dossier :

```text
D:\STEAM\steamapps\content\app_1946180\depot_1946183\
```

vers :

```text
D:\SKYFORGE\Stock Game\
```

Accepter l’écrasement des anciens fichiers CK copiés précédemment, si nécessaire.

---

## 6. Patcher / downgrader `CreationKit.exe`

Télécharger manuellement le patcher CK depuis Nexus :

```text
https://www.nexusmods.com/skyrimspecialedition/mods/67096
```

Copier le patcher dans :

```text
D:\SKYFORGE\Stock Game\
```

Lancer le patcher et vérifier que la cible est bien :

```text
D:\SKYFORGE\Stock Game
```

Puis cliquer sur :

```text
Start Patching
```

Validation attendue :

```text
Finished Patching, enjoy your game!
```

> Ne relancer le patcher que si `CreationKit.exe` est remplacé plus tard par une version fraîche venue de Steam ou d’un depot.

---

## 7. Installer SSE CreationKit Fixes

Télécharger manuellement les deux fichiers du mod :

```text
https://www.nexusmods.com/skyrimspecialedition/mods/20061
```

Fichiers utilisés :

```text
CK64Fixes Release 3.2
FaceFXWrapper 0.4
```

Extraire le contenu des deux archives directement dans :

```text
D:\SKYFORGE\Stock Game\
```

Les fichiers doivent se retrouver à côté de :

```text
D:\SKYFORGE\Stock Game\CreationKit.exe
```

Ne pas installer ces fichiers comme des mods MO2 : ce sont des correctifs du Creation Kit lui-même.

---

## 8. Premier lancement hors MO2

Lancer directement :

```text
D:\SKYFORGE\Stock Game\CreationKit.exe
```

Au premier lancement, le CK peut afficher :

```text
Scripts.zip is newer than the extracted scripts. Extract Scripts.zip?
```

### Comportement constaté dans SKYFORGE

- Cliquer sur **Oui** peut lancer l’extraction très lentement ou en arrière-plan.
- Si le dossier suivant existe déjà, il est possible de cliquer sur **Non** pour accéder à l’interface du CK :

```text
D:\SKYFORGE\Stock Game\Data\Scripts\Source\
```

Validation attendue :

```text
D:\SKYFORGE\Stock Game\Data\Scripts\Source\
```

existe et contient les sources extraites.

Si une ou plusieurs fenêtres de copie apparaissent après coup, les laisser terminer. Ne pas relancer le CK pendant la copie.

---

## 9. Créer un mod de sortie MO2

Dans MO2, créer un mod vide :

```text
Creation Kit Output
```

Ce mod recevra les fichiers générés par le CK au lieu de polluer `Overwrite`.

---

## 10. Ajouter le Creation Kit dans MO2

Dans MO2 :

```text
Executables → + → Add from file
```

Sélectionner :

```text
D:\SKYFORGE\Stock Game\CreationKit.exe
```

Configuration validée :

```text
Title: Creation Kit
Binary: D:\SKYFORGE\Stock Game\CreationKit.exe
Start in: D:\SKYFORGE\Stock Game\
Arguments: vide
Steam AppID: 1946180
Create files in mod instead of overwrite: coché
Output mod: Creation Kit Output
Force load libraries: coché
```

> Contrairement à xTranslator ou EET, le Creation Kit utilise ici `Force load libraries`, conformément à la méthode validée.

---

## 11. Test final via MO2

Depuis MO2, lancer :

```text
Creation Kit
```

Validation attendue :

```text
- le CK démarre depuis MO2 ;
- CK64Fixes se charge ;
- FaceFXWrapper se lance ;
- l’interface principale du Creation Kit apparaît ;
- aucun plugin n’est chargé lors du premier test ;
- rien n’est sauvegardé ;
- les sorties éventuelles vont dans Creation Kit Output.
```

---

## 12. Notes importantes

### Ne pas repatcher inutilement

L’extraction de `Scripts.zip` ne modifie pas `CreationKit.exe`.

Donc, une fois que :

```text
CreationKit.exe est patché
CK64Fixes est installé
FaceFXWrapper est installé
Data\Scripts\Source existe
le CK se lance via MO2
```

il n’est pas nécessaire de relancer le patcher.

### Portabilité vers un autre PC

Si le dossier SKYFORGE est copié vers un autre PC avec exactement le même chemin :

```text
D:\SKYFORGE
```

alors le Creation Kit devrait rester fonctionnel, même si le CK n’a pas été installé via Steam sur cet autre PC, à condition que :

```text
- Steam soit installé ;
- Skyrim SE soit possédé sur le compte Steam ;
- MO2 conserve les mêmes chemins ;
- l’exécutable MO2 Creation Kit garde Steam AppID 1946180 ;
- Force load libraries reste coché.
```

### Utilisation recommandée

Utiliser le CK uniquement pour les opérations qui le nécessitent réellement :

```text
- conversion ponctuelle Form 43 → Form 44 ;
- visualisation CK ;
- sauvegarde officielle d’un plugin ;
- corrections spécifiques impossibles ou peu pratiques dans xEdit.
```

Pour l’analyse de conflits, de records et de load order, privilégier :

```text
SSEEdit / xEdit
```

---

## 13. Statut SKYFORGE

Statut validé :

```text
Creation Kit installé dans D:\SKYFORGE\Stock Game
Depots Steam corrects copiés
CreationKit.exe patché/downgradé
CK64Fixes Release 3.2 installé
FaceFXWrapper 0.4 installé
Scripts extraits dans Data\Scripts\Source
Lancement direct validé
Lancement via MO2 validé
Creation Kit Output configuré
```
