# Règles de configuration SKYFORGE

> Procédure personnelle du projet **SKYFORGE**. Aucun mod, archive Nexus, fichier Bethesda, fichier Creation Club, fichier SKSE, ENB ou élément soumis à redistribution restreinte n’est inclus dans ce dépôt.

Ce dossier documente les réglages de configuration de SKYFORGE : fichiers `.ini`, `.toml`, `.json`, `.yaml`, `.txt`, MCM exportés, presets et fichiers générés par les outils.

---

## Principe général

SKYFORGE ne reprend pas automatiquement les configurations de Nolvus ou Nefaram.

Les configurations Nolvus / Nefaram peuvent servir de références d’analyse, mais chaque réglage doit être repris uniquement s’il est pertinent pour SKYFORGE.

---

## Règles de modification

1. Ne pas modifier un fichier de configuration sans raison documentée.
2. Préférer les valeurs par défaut tant que le module concerné n’est pas stabilisé.
3. Créer un mod MO2 dédié pour les fichiers générés ou modifiés quand c’est pertinent.
4. Documenter chaque modification importante avec :
   - le fichier concerné ;
   - la valeur d’origine si elle est connue ;
   - la nouvelle valeur ;
   - la raison ;
   - le test effectué.
5. Ne pas recopier aveuglément une configuration Nolvus / Nefaram.
6. Différer les réglages subjectifs tant que les tests ingame ne permettent pas de juger.
7. Les réglages moteur / SKSE sensibles doivent être testés individuellement.

---

## Types de fichiers concernés

- `.ini`
- `.toml`
- `.json`
- `.yaml`
- `.txt`
- exports MCM
- fichiers générés dans `Overwrite`
- presets de mods

---

## Exemples de réglages à documenter plus tard

- `SSEDisplayTweaks.ini`
- `EngineFixes.toml` / `EngineFixes.ini`
- `po3_Tweaks.ini`
- `ScrambledBugs.json`
- `PapyrusTweaks.ini`
- `SkyHUD.txt`
- fichiers TrueHUD / STB / Oxygen Meter
- `MenuMaid2.ini`
- `Notification Filter.ini`
- configurations audio
- MCM Survival / Immersion
- MCM SexLab / Devious / BaboDialogue

---

## Statut actuel

Structure créée en anticipation.

Les configurations seront documentées progressivement, au fur et à mesure des tests et des besoins réels.