# Décisions différées et points à revoir — partie 3

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie complète les décisions différées à partir du module **07 - CITIES TOWNS INTERIORS LIGHTING**.

---

## Décisions importantes ajoutées après l’étape 319

- `Lux Orbis - Patch Hub - A REINSTALL PLUS TARD` est installé mais devra être complété / réinstallé plus tard selon les villes, villages, routes, intérieurs et patches retenus.
- Les patch collections Great Town / Great Village / Great City sont conservées en `A COMPLETER PLUS TARD` pour la future phase de patching.
- Les nouveaux villages / settlements ajoutés entre les étapes 290 et 298 gardent leurs patches différés.
- Les patches Player Homes restent différés.
- Les patches / LOD / DynDOLOD du sous-bloc `07.2 - FARMHOUSES` restent différés.
- Les patches du sous-bloc `07.3 - OTHER LOCATIONS` restent différés.
- `Dragon Bridge` est différé, car la zone est plus complexe à patcher avec routes / ponts / Lux / villes.
- `The Great City Of Falkreath SSE Edition` est retenu en choix Nolvus ; éviter le mélange COTN / JK / patchs complexes pour Falkreath.
- `Cities of the North - Dawnstar` et `Cities of the North - Dawnstar - Update 1.4` sont décochés / remplacés par `The Great City Of Dawnstar SSE Edition`.
- `Cities of the North - Winterhold` est décoché / remplacé par `The Great City Of Winterhold SSE Edition`.
- `Cities of the North - Morthal` est décoché, choix final Morthal à revoir.
- `The Great Cities - CC Fishing Patch` est identifié mais différé jusqu’à stabilisation du bloc Great Cities.
- `3DNPC-TGCoMM Patch by WiZkiD` est différé jusqu’à installation éventuelle de `3DNPC`.
- `Dunmer Settlements of Solstheim` est retenu en version ESL pour limiter l’impact sur le compteur non-light.
- Les patches Solstheim / Raven Rock / Tel Mithryn sont différés.
- `Settings Loader Hearthfire Multiple Adoptions` est annulé / introuvable.
- Patch Verdant de `Sicarius' Refuge SSE` zappé tant que `Verdant` n’est pas présent dans SKYFORGE.
- `Lakeview Manor - As It Should Be` est un ajout externe Fabien, installé et validé.
- Traduction FR du patch CC Fishing de Lakeview Manor non installée, jugée inutile par Fabien.
- Parallax retenu pour la stack Farmhouses.
- `Nordic Stonewalls v3.11` retenu au lieu de l’ancienne référence Nolvus `1.12`.
- `Scarecrows of Skyrim - BOS - SOS Patch` installé mais décoché à cause du master manquant `Simplicity of Snow.esp`.
- `This Is Jorrvaskr - KASA` non installé.
- Aucun patch Jorrvaskr / Dawnguard / Volkihar installé à ce stade.
- Liens corrigés pour `JK's Fort Dawnguard` et `JK's Castle Volkihar`.
- LOD / DynDOLOD ne sont pas générés pendant ce bloc ; à faire plus tard.
- **Étape 551 :** `CoMAP`, `CoMAP 4 for Skyrim 1.5`, `Flat World Map Framework` et `Skyrim Paper Map by Caro Tuts for FWMF` sont différés et devront être regroupés dans un bloc map dédié.

---

### Étape 267 — Lux Orbis Patch Hub

**Décision :**  
`Lux Orbis - Patch Hub - A REINSTALL PLUS TARD` est installé mais non finalisé.

**Raison :**  
Les choix de villes, villages, routes, intérieurs, météo et patches évoluent encore. Le patch hub devra être repris plus tard lorsque le module 07 sera suffisamment stabilisé.

**Statut :**  
Installé, réinstallation / complément différé.

---

### Étapes 269 à 298 — Patch collections Great Cities / COTN / Environs / villages

**Décision :**  
Les patch collections sont installées lorsqu’elles sont utiles, mais marquées `A COMPLETER PLUS TARD` ou `PATCHES A VOIR PLUS TARD`.

**Raison :**  
Les patchs doivent dépendre des mods réellement installés et de l’ordre final retenu pour les villes, villages, Lux / Lux Orbis, routes, AI Overhaul, Embers XD, Lanterns of Skyrim II, No Snow Under the Roof, Ryn’s modules, Solstheim, Raven Rock, Tel Mithryn, etc.

**Statut :**  
Patching final différé.

---

### Étape 274 — 3DNPC-TGCoMM Patch by WiZkiD

**Décision :**  
`3DNPC-TGCoMM Patch by WiZkiD` n’est pas installé.

**Raison :**  
`3DNPC` n’est pas encore installé.

**Action future :**  
Reprendre ce patch uniquement si `3DNPC` est installé ou officiellement retenu.

**Statut :**  
Différé.

---

### Étape 551 — CoMAP / FWMF / paper map

**Décision :**  
Installation de `CoMAP` différée.

**Raison :**  
SKYFORGE prévoit d’utiliser :

- `Flat World Map Framework`
- `Skyrim Paper Map by Caro Tuts for FWMF`

Ces mods touchent directement à la world map, aux marqueurs et à l’ordre de plugins de carte. `CoMAP` doit donc être audité avec le bloc map complet, et non installé isolément.

**Mods concernés :**

- `CoMAP - Common Marker Addon Project`
- `CoMAP 4 for Skyrim 1.5`
- `Flat World Map Framework`
- `Skyrim Paper Map by Caro Tuts for FWMF`

**Point technique important :**  
Avec FWMF / paper map, les plugins liés à la map doivent rester très bas dans le load order. Il faut éviter que des plugins non liés à la map, par exemple armures, tenues, outfits, gameplay ou autres plugins ajoutés plus tard, se retrouvent sous les plugins FWMF / paper map.

**Risque connu si l’ordre est mauvais :**  
Map violette.

**Décision technique :**  
Ne pas installer `CoMAP` maintenant. Ne pas installer `CoMAP 4 for Skyrim 1.5` maintenant. Créer plus tard un bloc dédié map / paper map / markers.

**État conservé :**

- Aucune installation.
- Aucun plugin ajouté.
- Compteur ESP + ESM non-light inchangé : 128.
- Overwrite inchangé : vide.
