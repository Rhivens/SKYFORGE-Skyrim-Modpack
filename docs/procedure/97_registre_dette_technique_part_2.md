# Registre central de dette technique SKYFORGE — partie 2

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Cette partie complète le registre central de dette technique avec les dettes liées aux **ajouts personnels**, notamment les tenues / armures / vêtements validés dans l’ancien environnement Nefaram de Fabien.

---

## État de référence

- Dernière étape validée : `Étape 327 — Pause technique Nexus`
- Dernière étape d’installation validée : `Étape 326 — Ryn’s Standing Stones`
- Module en cours : `07 - CITIES TOWNS INTERIORS LIGHTING`
- Sous-bloc en cours : `07.4 - LANDS`
- Compteur ESP + ESM non-light : `79`
- Source des ajouts : fichier Excel `Ajout Tenues.xlsx` fourni par Fabien

---

## Registre synthétique — tenues / armures / vêtements personnels

| Module | Étape | Élément | Type | Raison | Dépend de | Moment de reprise | Priorité | Statut |
|---|---:|---|---|---|---|---|---|---|
| 96 - Ajouts personnels / Tenues | À venir | Tenues validées fonctionnelles dans Nefaram | `VERIFICATION` | Ces tenues ont été validées dans Nefaram mais doivent être vérifiées dans SKYFORGE. | Nolvus outfits, CBBE / 3BA, BodySlide, SMP, High Heels, conflits de fichiers. | Module armures / tenues / BodySlide. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Variantes BHUNP vs CBBE / 3BA | `CHOIX_A_REVOIR` | Certaines tenues existent en BHUNP et CBBE / 3BA ; SKYFORGE devra éviter les variantes inutiles. | Choix corps final CBBE / 3BA. | Avant installation des tenues. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Conversions 3BA / BodySlide | `VERIFICATION` | Plusieurs tenues nécessitent une conversion ou un patch BodySlide 3BA. | BodySlide, CBBE / 3BA, presets BodySlide. | Avant génération BodySlide globale. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Tenues SMP / HDT-SMP | `VERIFICATION` | Certaines tenues utilisent SMP / HDT-SMP et doivent être testées avec la future stack physics. | Faster HDT-SMP, skeleton, body, animations. | Module skeleton / physics / BodySlide. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Talons / High Heels / Heels Sound | `VERIFICATION` | Certaines tenues ou bottes nécessitent une logique talons / sons de talons. | High Heels, sound patches, footwear framework éventuel. | Module outfits / physics / audio. | Moyenne | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Tenues 4K | `CHOIX_A_REVOIR` | Certaines tenues sont en 4K ; vérifier intérêt visuel / coût VRAM. | Politique textures SKYFORGE, VRAM RTX 4070 12 Go. | Audit texture outfits. | Moyenne | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | Doublons potentiels avec Nolvus / Nefaram | `VERIFICATION` | Vérifier si certaines tenues sont déjà présentes ou remplacées par Nolvus / Nefaram. | Load order final outfits / armures. | Avant installation des ajouts personnels. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | `EGIL Annoying Bard` | `PATCHES_A_REVOIR` | Prévoir le patch `Annoying Patch for JK's Bard College` si `JK's Bard College` est utilisé. | JK's Bard College. | Module villes / collèges / outfits. | Moyenne | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | `Derketo Priestess 3BA Patch` | `PATCHES_A_REVOIR` | Patch BodySlide 3BA dépendant du main file `Obi's Derketo Priestess Outfit`. | Main file Derketo Priestess, BodySlide, 3BA. | Module outfits / BodySlide. | Haute | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | `Shas' Chains and Silks Update 1.0.1` | `PATCHES_A_REVOIR` | Update à installer après la base uniquement si la tenue est retenue. | Shas' Chains and Silks base. | Module outfits / BodySlide. | Moyenne | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | `Vertigo Boots - Heels Sound` | `PATCHES_A_REVOIR` | Complément son à installer seulement si la tenue / les bottes Vertigo sont retenues. | Vertigo Thigh High Boots, système talons / sons. | Module outfits / audio. | Faible | Ouvert |
| 96 - Ajouts personnels / Tenues | À venir | `MME Milk Harness` | `VERIFICATION` | Tenue LoversLab potentiellement liée à MME / BodySlide / 3BA. | MME éventuel, BodySlide, 3BA, LoversLab requirements. | Module SexLab / outfits. | Moyenne | Ouvert |

---

## Liste de contrôle avant intégration des tenues

Avant d’installer les tenues validées dans Nefaram dans SKYFORGE, vérifier :

1. **Doublon modlist** : déjà présent dans Nolvus, Nefaram ou un pack existant ?
2. **Corps utile** : retenir la variante CBBE / 3BA si SKYFORGE reste sur 3BA ; éviter BHUNP sauf nécessité réelle.
3. **BodySlide** : fichier BodySlide présent, conversion correcte, génération globale future prévue.
4. **SMP / physics** : vérifier compatibilité avec Faster HDT-SMP et skeleton final.
5. **High Heels / talons** : vérifier si un framework ou un patch son est nécessaire.
6. **Textures** : éviter 4K / 8K inutiles sauf tenue très visible ou justification forte.
7. **Plugin** : vérifier si ESP, ESPFE, ESL ou aucun plugin.
8. **Patches** : ne pas installer de patch si le mod parent n’est pas retenu.
9. **Conflits de fichiers** : surveiller meshes / textures / Bodyslide output.
10. **Intérêt réel** : garder uniquement les tenues utiles pour SKYFORGE, pas tout l’ancien stock Nefaram par réflexe.

---

## Tenues concernées par cette dette technique

La liste détaillée est conservée dans :

`docs/procedure/96_ajouts_personnels_skyforge.md`

Section :

`Tenues / armures validées fonctionnelles dans Nefaram — Excel Fabien`

Cette section contient notamment :

- Invicta Couture Black Rose BHUNP / CBBE 3BA ;
- qdaro Silver Witch 3BA SMP ;
- Obi's Derketo Priestess Outfit + patch 3BA ;
- DX Fetish Fashion Volume 2 ;
- Invicta Couture Lingerie BHUNP / CBBE 3BA ;
- Chain Bikini Armor ;
- Dark Rebel ;
- Shas' Chains and Silks ;
- Minou Aradia Lace Dress / Bikini ;
- Aether CBBE 3BA ;
- Lady Ritual ;
- Bisquits Priestess of Mara ;
- MME Milk Harness ;
- Vertigo Thigh High Boots / Heels Sound ;
- RELICS OF THE TSAESCI ;
- EGIL Annoying Bard.

---

## Règle de maintenance

À chaque ajout de nouvelles tenues / armures / vêtements personnels :

- les inscrire dans `docs/procedure/96_ajouts_personnels_skyforge.md` ;
- ajouter ici uniquement les dettes techniques transversales ou sensibles ;
- éviter de créer une ligne de dette par tenue sauf cas particulier ;
- créer une ligne spécifique si la tenue nécessite un patch, un master, une conversion, une version verrouillée ou un réglage particulier.
