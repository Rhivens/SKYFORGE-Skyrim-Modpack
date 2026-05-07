# Changelog configuration SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun fichier de mod ou fichier soumis à redistribution restreinte n’est inclus dans ce dépôt.

---

## Création de la structure de configuration

**Objectif :**  
Préparer une documentation dédiée aux réglages `.ini`, `.toml`, `.json`, `.yaml`, `.txt`, exports MCM, presets et fichiers générés.

**Raison :**  
Les modpacks comme Nolvus ou Nefaram reposent fortement sur une couche de configuration. SKYFORGE doit donc documenter non seulement les mods installés, mais aussi les réglages choisis et les raisons de ces choix.

**Fichiers ajoutés :**

- `docs/configuration/00_regles_configuration.md`
- `docs/configuration/01_engine_skse_ini.md`
- `docs/configuration/02_ui_hud_ini.md`
- `docs/configuration/03_audio_ini.md`
- `docs/configuration/04_survival_immersion_mcm.md`
- `docs/configuration/05_sexlab_devious_mcm.md`
- `docs/configuration/99_configurations_differees.md`
- `docs/configuration/CHANGELOG_CONFIGURATION.md`

**Fichier mis à jour :**

- `docs/SKYFORGE_Procedure_Reproduction_PC.md`

**Décisions documentées :**

- Ne pas recopier automatiquement les configurations Nolvus / Nefaram.
- Documenter toute modification importante avec fichier, valeur, raison et test.
- Différer les réglages subjectifs tant que les tests ingame ne permettent pas de juger.
- Les réglages moteur / SKSE sensibles doivent être testés individuellement.
- Les voix supplémentaires anglaises sont exclues par défaut.
- `BaboDialogue` sera traité en version `6.12 hotfix`, sans reprise automatique des patches Nefaram basés sur la version `5.70`.
- `Devious Followers` est exclu par défaut, sauf dépendance réelle et indispensable.

**Statut :**  
Structure créée. Les réglages réels seront documentés progressivement.