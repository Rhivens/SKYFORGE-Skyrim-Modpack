# Règles MO2 officielles — SKYFORGE

## Objet du fichier

Ce fichier centralise les conventions durables liées à Mod Organizer 2, au panneau gauche, aux snapshots, aux suffixes de suivi et aux reprises du projet SKYFORGE.

Il doit être lu avant toute reprise, audit, installation, déplacement, renommage ou proposition de mod dans MO2.

Ce fichier ne remplace pas les notes spécialisées existantes. Il sert de table centrale des règles MO2 et renvoie vers les fichiers dédiés lorsque nécessaire.

---

## 1. Source de vérité

Le dépôt GitHub est la source officielle de vérité documentaire pour SKYFORGE.

Avant toute nouvelle proposition d'installation, vérifier en priorité :

1. `docs/procedure/00_resume_etat_actuel.md`
2. le dernier changelog de validation ;
3. le fichier thématique du module en cours ;
4. le dernier snapshot MO2 panneau gauche courant ;
5. les fichiers de règles ou vigilances spécialisés.

Ne jamais repartir d'un ancien snapshot si un snapshot plus récent est documenté comme référence courante.

---

## 2. Snapshot MO2 panneau gauche

Le snapshot MO2 panneau gauche courant sert de référence anti-doublon.

Règles :

- ne pas proposer un mod déjà présent dans le snapshot courant ;
- ne pas déduire le compteur ESP + ESM non-light depuis le panneau gauche ;
- le compteur non-light doit venir du panneau droit MO2 communiqué par Fabien ;
- les snapshots plus anciens sont conservés comme jalons historiques uniquement ;
- un snapshot historique ne doit pas être modifié, sauf restauration d'erreur.

À l'état post-480, le snapshot courant est :

```text
docs/configuration/SKYFORGE_Load_Order_MO2_panneau_gauche_etape_480.md
```

Le snapshot étape 450 reste un jalon historique post-450.

---

## 3. Convention future des snapshots

Pour éviter les blocages du connecteur GitHub sur certains noms de mods ou séparateurs techniques sensibles, les futurs snapshots MO2 seront créés en deux temps.

Iris crée le fichier avec :

- l'en-tête officiel ;
- l'état associé ;
- les règles de lecture ;
- un bloc texte réservé ;
- les notes post-snapshot éventuelles.

Fabien colle ensuite manuellement le texte brut du panneau gauche MO2 entre les balises :

````markdown
```txt
COPIER LE TEXTE BRUT DU LOAD ORDER MO2 ICI
```
````

Cette convention est particulièrement importante pour les futurs blocs contenant des noms techniques liés aux frameworks adultes, tenues NSFW, SexLab/Nefaram ou autres modules susceptibles de déclencher inutilement les filtres automatiques.

---

## 4. Séparateurs MO2 vides

Certains séparateurs du panneau gauche MO2 peuvent être volontairement vides.

Ils servent à préparer l'architecture future du modpack.

Règles :

- un séparateur vide n'est pas une erreur ;
- ne pas le supprimer sans décision explicite ;
- ne pas interpréter son absence de mods comme une anomalie ;
- ne pas remplir un séparateur futur sans cohérence avec le module en cours.

---

## 5. Mods `- FR`

Les mods dont le nom se termine par `- FR` sont des traductions personnelles de Fabien.

Règles :

- ils sont présents dans le panneau gauche MO2 ;
- ils restent volontairement décochés tant que le modpack n'est pas stabilisé ;
- ils ne doivent pas être activés automatiquement ;
- ils seront activés plus tard par petits groupes contrôlés ;
- chaque activation de groupe devra être suivie d'un test SKSE / menu.

---

## 6. Convention MO2 — suffixes de suivi temporaires

Dans SKYFORGE, certains mods du panneau gauche MO2 peuvent être renommés avec un suffixe de suivi temporaire.

Exemples :

- `- FOMOD A REVOIR PLUS TARD`
- `- FOMOD À REVOIR PLUS TARD`
- `- PATCHES A VOIR PLUS TARD`
- `- PATCHES À VOIR PLUS TARD`
- `- A COMPLETER PLUS TARD`
- `- A REINSTALLER PLUS TARD`
- `- DECOCHE`
- `- RESERVE`
- `- RESERVE ENB`
- `- RESERVE SEXLAB`

Ces suffixes ne signifient pas forcément que le mod est désactivé, cassé ou incorrect.

Ils indiquent qu'une partie du mod, un choix FOMOD, un fichier optionnel, un patch, une dépendance ou une décision de placement devra être réauditée plus tard.

### Interprétation pratique

- `FOMOD A REVOIR PLUS TARD` : le mod principal est installé avec des choix provisoires ou sobres ; certaines options pourront être réévaluées si le contexte change.
- `PATCHES A VOIR PLUS TARD` : le mod principal est accepté, mais des patches sont différés car leurs masters, modules ou priorités ne sont pas encore validés.
- `A COMPLETER PLUS TARD` : le mod ou patch hub est installé partiellement ; des composants seront ajoutés lors d'un module futur.
- `A REINSTALLER PLUS TARD` : installation actuelle provisoire, incomplète ou volontairement minimale ; réinstallation propre prévue quand le module correspondant sera ouvert.
- `DECOCHE` : le mod ou plugin est volontairement désactivé pour réserve, incompatibilité actuelle, module futur ou test différé.
- `RESERVE` : le mod est conservé pour usage potentiel, mais non actif ou non retenu dans la configuration courante.

### Règles associées

- Le mod principal peut rester installé et coché malgré un suffixe de suivi.
- Les options non retenues dans le FOMOD ne doivent pas être installées avant audit.
- Les fichiers optionnels dépendant de masters absents restent différés.
- Les patches liés à des followers, quêtes, lieux, SexLab, DBVO, traductions `- FR` ou autres modules futurs sont installés uniquement quand leurs masters et leur module sont validés.
- Le suffixe doit être supprimé, remplacé ou précisé quand les patches/options concernés sont installés, exclus définitivement ou déplacés dans un module dédié.
- Les notes de suivi sont portées directement dans le nom MO2 du mod principal quand c'est la pratique déjà utilisée dans le bloc.
- Ne pas créer de dossiers vides séparés sauf décision explicite.

---

## 7. Patches, optional files et masters absents

Les patches et fichiers optionnels ne doivent pas être installés par automatisme.

Règles :

- installer un patch uniquement si ses masters sont présents, validés et actifs ;
- différer un patch si un master est absent ;
- ne pas activer un patch qui signale un master manquant ;
- ne pas installer les patches de followers, quêtes, lieux, intérieurs, DBVO, traductions ou systèmes spécialisés avant validation du module concerné ;
- noter les patches importants dans la procédure ou dans la dette technique lorsqu'ils devront être repris plus tard.

---

## 8. Outils à ne pas lancer sans demande explicite

Certains outils génèrent des outputs lourds ou modifient fortement l'état de l'installation.

Ils ne doivent pas être lancés par automatisme.

### LOOT

LOOT n'est pas lancé pendant la progression actuelle.

Le load order est construit manuellement et documenté par blocs.

### DynDOLOD / LOD

DynDOLOD et les LOD ne sont pas générés maintenant.

Ils seront traités plus tard, quand les villes, lieux, extérieurs, paysages, arbres, eau, ruines, worldspaces et patches associés seront stabilisés.

### BodySlide

BodySlide Output n'est pas généré maintenant.

Il sera traité plus tard, quand le body final, les tenues, armures, physics, conversions, outfits et presets seront stabilisés.

Voir aussi :

```text
docs/configuration/08_body_skins_bodyslide_vigilances.md
```

### Pandora

Pandora a été généré avec succès à l'étape 411 et son Output est actif.

Pandora ne doit pas être relancé sauf :

- demande explicite de Fabien ;
- ajout ou modification d'un mod d'animation / comportement qui le nécessite réellement ;
- étape dédiée documentée.

---

## 9. Règle vampire SKYFORGE

La règle vampire détaillée est documentée ici :

```text
docs/configuration/09_regle_vampire_skyforge.md
```

Rappel court :

- Fabien ne prévoit pas de jouer vampire ;
- éviter les mods principalement orientés PJ vampire ;
- privilégier les mods utiles aux NPC vampires ou utiles à la fois au PJ et aux NPC ;
- ne pas empiler d'addons vampire sans bénéfice NPC clair ;
- `Sacrosanct` est la base vampire retenue ;
- ne pas ajouter Better Vampires, Scion, Sacrilege ou addons feeding/progression joueur sans décision explicite.

---

## 10. Créatures, werebeasts et futurs systèmes spécialisés

Les futurs systèmes issus de la logique Nefaram peuvent impacter fortement :

- créatures ;
- formes transformées ;
- werebeasts ;
- vampire lord ;
- animations ;
- skeletons ;
- meshes ;
- frameworks ;
- patches associés.

Règles :

- différer ou auditer prudemment tout mod touchant aux créatures, animations créatures, formes transformées ou skeletons/meshes associés ;
- ne pas ajouter de système créature ou werebeast lourd sans audit dédié ;
- privilégier les choix sobres tant que les futurs modules spécialisés ne sont pas ouverts ;
- ne pas relancer Pandora par automatisme après un mod de ce type sans étape dédiée.

---

## 11. Conventions de réponse attendues pour l'intendant SKYFORGE

Lorsqu'une étape est proposée :

- proposer une seule étape à la fois ;
- indiquer la source du mod : Nolvus Awakening, Nefaram ou proposition spécifique SKYFORGE ;
- donner l'emplacement MO2 recommandé ;
- préciser les choix FOMOD si nécessaire ;
- indiquer les plugins attendus ;
- attendre le test de Fabien avant validation ;
- ne pas considérer l'étape validée avant retour de test.

Lorsqu'une étape est validée :

- fournir un bloc Markdown prêt à copier/coller pour GitHub ;
- ne pas ajouter de second récapitulatif narratif dans le chat ;
- si l'étape est annulée ou différée, fournir un bloc Markdown court de décision/différé.

---

## 12. Statut documentaire

Ce fichier est une convention permanente de travail pour SKYFORGE.

Il doit être mis à jour lorsqu'une nouvelle règle MO2 durable est validée par Fabien.

Les fichiers spécialisés restent valables et doivent être conservés lorsqu'ils détaillent une règle particulière.
