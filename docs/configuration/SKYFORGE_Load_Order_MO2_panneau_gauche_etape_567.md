# SKYFORGE — Load Order MO2 panneau gauche — Étape 567

Snapshot du panneau gauche MO2 après validation de l’étape 567.

Ce fichier deviendra la référence de contrôle du panneau gauche MO2 une fois que le texte brut complet du load order aura été collé manuellement dans le bloc prévu à cet effet.

## Règles de lecture

- Ce fichier remplacera le snapshot étape 553 comme référence courante anti-doublon après collage manuel du brut MO2 complet et vérification.
- Le snapshot étape 553 deviendra alors un jalon historique post-553.
- Les mods se terminant par `- FR` sont présents mais décochés, sauf indication contraire.
- Les séparateurs vides sont normaux : ils préparent les futurs blocs SKYFORGE.
- Les suffixes de suivi temporaires (`FOMOD A REVOIR`, `PATCHES A VOIR`, `A REINSTALLER`, `DECOCHE`, `RESERVE`, etc.) sont des marqueurs de suivi et ne signifient pas forcément que le mod est invalide.
- Ce snapshot concerne le panneau gauche MO2, pas le compteur ESP/ESM non-light du panneau droit.

## État associé

- Dernière étape validée : 567
- Prochaine étape attendue : 568
- Blocs enrichis depuis le snapshot 553 :
  - `[04 - AUDIO MUSIC VOICES]`
  - `[05 - VISUAL BASE MESHES TEXTURES]`
- Compteur ESP + ESM non-light : 129
- Overwrite : vide sur les tests documentés après corrections
- LOOT : non lancé
- DynDOLOD / LOD : non générés
- BodySlide Output : non généré
- Pandora : généré depuis l’étape 411, Output actif ; non relancé pendant les étapes 554 à 567

## Changements principaux depuis le snapshot étape 553

### Bloc `[04 - AUDIO MUSIC VOICES]`

Ajouts / décisions principales :

- Immersive Sounds - Creation Club Armours
- Phoenix Compendium - FOMOD PARTIEL A REVOIR PLUS TARD
- Plugin ajouté : `CC complete ISC patch.esp`
- Compteur inchangé à l’étape 554 : 128

### Bloc `[05 - VISUAL BASE MESHES TEXTURES]`

Ajouts / décisions principales :

- Ruins Clutter Improved + Fixes
- Rustic Clutter Collection / Forgotten Retex Project / TB's Improved Dust Particles
- Rudy HQ Miscellaneous, Glazed Pottery, Skyrim 3D Misc
- Medieval Candlehorns, SD's Horn Candles, Rally's Nord War Horns, Rudy Candles Expanded
- Burned Book Retexture, Scroll SE, ingrédients alchimiques divers
- JS Bloodstone Chalice, Initiate’s Ewer, Essence Extractor, Dwarven Oil, Dwemer Kitchenware, Ichor Barrels, Torture Tools, Embalming Tools
- Arc’s Redux : Tankard, Kitchen, MeadBarrel, Kettle
- Stunning Statues, Better-Shaped Talos, JS Shrines, HD Glaze
- Statue of Sithis + Daedric Shrines AIO
- Rally’s Solstheim Shrines + Sovngarde Watcher
- CC’s Enhanced Ore Veins, HD Dwemer Automatons, Dwemer Pipework, Improved Dwemer Glass
- Dwemer Tech Glowmapped + objets JS Dwemer
- JS Attunement Sphere and Lexicons + JS Instruments of Skyrim
- Compteur final post-567 : 129

## Snapshot complet du panneau gauche MO2

```txt
[00 - BASE GAME]
[01 - SKSE PLUGINS & CORE UTILITIES]
Address Library for SKSE Plugins 1.5.97
Backported Extended ESL Support
CrashLogger
Crash Logger SkyrimSE 1.5.97.0 - PDB addresses
SKYFORGE - Local Configs - MCM CrashLogger
PapyrusUtil SE - Modders Scripting Utility Functions
powerofthree's Papyrus Extender
powerofthree's Tweaks
powerofthree's Tweaks - Generated INI
JContainers SE
MCM Helper SE (1.5.97 BACKPORT)
NL_MCM - A Modular MCM Framework
SKSE Menu Framework
Execute Hotkeys - Without Keyboard Through UI - SKSE Menu Framework
ConsoleUtilSSE NG
Fuz Ro D-oh - Silent Voice
Fuz Ro D-oh - Generated INI
Spell Perk Item Distributor (SPID)
Spell Perk Item Distributor - Generated INI
Keyword Item Distributor (KID)
Base Object Swapper (BOS)
Object Categorization Framework - A REINSTALLER PLUS TARD
FormList Manipulator - FLM
AnimObject Swapper
FileAccess Interface for Skyrim SE Scripts - FISSES (Special Edition)
Console Commands Extender
More Informative Console 1.2.2
ConsolePlusPlus
ConsolePlusPlus - Generated INI
Scaleform Translation Plus Plus NG
Auto Input Switch (1.5.97)
dTry's Key Utils SE
ENB Helper SE 1.5 for SSE 1.5.97
Better Jumping SE
Dynamic Activation Key
Behavior Data Injector SE
SkyPatcher - SE
Kris's Papyrus Extender - DECOCHE RESERVE
Container Item Distributor
Andrealletius' Papyrus Functions
MergeMapper
Perk Entry Point Extender
KiLoader for Skyrim
KiLoader - Generated Empty Folders - SKYFORGE
ENB Extender Skyrim - DECOCHE RESERVE ENB
Dynamic String Distributor (DSD)
Media Keys Fix SKSE
DPI Scaling Fix
dMenu
dMenu NG
ImGui Icons
[02 - BUG FIXES & ENGINE PATCHES]
Unofficial Skyrim Special Edition Patch - USSEP 4.2.5b
Unofficial Skyrim Special Edition Patch - USSEP 4.2.5b - FR
Unofficial Skyrim Creation Club Content Patch
Unofficial Skyrim Modder's Patch - USMP SE 2.6.7
Unofficial Skyrim Modder's Patch - USMP SE 2.6.7 - FR
Vanilla Script MicroOptimizations
Vanilla Scripting Enhancements Loose version
Keyword Patch Collection - A REINSTALL PLUS TARD
SSE Engine Fixes
Bug Fixes SSE - Special Edition (1.5.97.0 and earlier)
Scrambled Bugs - Special Edition (1.5.97.0 and earlier)
Script Effect Archetype Crash Fix
Papyrus Tweaks NG 4.1.1
Papyrus Tweaks NG - Generated INI
PapyrusUtil TFC Fix
Recursion Monitor Fix
Actor Limit Fix - Special Edition (1.5.97.0 and earlier)
Mfg Fix
Face Discoloration Fix SE (1.5.97)
NPC AI Process Position Fix - NG - A REINSTALLER PLUS TARD
Animation Queue Fix
LeveledList Crash Fix AE
LeveledList Crash Fix for Skyrim 1.5 (AE Backported)
RemoveAllItems Freeze Fix
Save & Load Accelerator for SKSE Cosaves (S.L.A.C.K.)
SSE Display Tweaks
Stay At The System Page - Updated
Disable Auto Vanity Mode - Stops Camera Spinning Around Player Character
Stuck on Screen Load Door Prompt Fix
WE05 Script Fix
Ulfric... Tullius... Give me a Break
Delphine Skyhaven Bugfix MQ203
Better Combat Escape - SSE
Bethesda.net Mods Manager Menu Disable Hide Remove
Aurora Fix
TrapSwingingWall Script Fix
Southfringe Sanctum Crash Fix
Sky Reflection Fix for ENB
Fast Travel Crash Fix
DLC2 Miraak BossFightScript Fix
Source of Stalhrim Quest Fix
Source of Stalhrim Quest Fix - FR
Taarie's Dialogue Fix
Taarie's Dialogue Fix - FR
Standing Ambusher Fix
Excuse Me
Excuse Me - FR
Quest Journal Limit Bug Fixer - Recover Disappeared Quests
Bone Wolf Shutdown Fix
Survival Mode Prompt Removed
Optimized USSEP Valdr Quest
OnMagicEffectApply Replacer Effective
Stagger Effect Fix
Equip Enchantment Fix for 1.5.39 - 1.6.353
Unequip Quiver SE (NG)
Unequip Quiver SE (NG) - FR
WIDeadBodyCleanupScript Crash Fix
Chillwind Depths CTD Fix
Halldir's Cairn CTD Fix
Nchuanthumz Papyrus Load Fix
HearthFires - Customizable Fertile Soil
HearthFires - Customizable Fertile Soil - FR
HearthFires - Customizable Fertile Soil - CC Farm Patch
Magic Student (WIChangeLocation04) Quest Fix
Rock Traps Trigger Fixes - BASE - PATCHES A REVOIR PLUS TARD
Dangerous Trap Fixes (D.T.F.)
Mannequin Management
Rogue's Gallery
Dynamic Collision Adjustment
Dynamic Collision Adjustment - FR
Disk Cache Enabler 1.2
A0D789 patch 1.1
Skyrim Cell load Freeze fix NG
Navigator - Navmesh Fixes - BASE CC - PATCHES A REVOIR PLUS TARD
Wordkeys - BASE - PATCHES MAGIE A REVOIR PLUS TARD
Wordkeys - Optional Plugin
World Encounter Hostility Fix - Performance version
Zero Bounty Hostility Fix
Enchantable Special Item Fix
Enchantable Special Item Fix - FR
Enchantable Special Item Fix for Skyrim 1.5
Enchantments and Potions Work for NPCs - EPW4NPCs (SKSE64) (SPID Plugin ini)
Hide Quest Items in Container Menu
Pickpocket Reset
Dwemer Gates Don't Reset
Dwemer Gates Don't Reset - FR
Sharpen Other Swords II - AnimObject Swapper
dunPOISoldiersRaidOnStart Script Tweak
dunPOISoldiersRaidOnStart Script Tweak - FR
Nifty AI Tweaks AIO - SSE
bc036's Tweaks
bc036's Tweaks - FR
Andrealletius' Exploit Fixes — FOMOD A REVOIR PLUS TARD
Power of Creation - Fishing
Power of Creation - Fishing - FR
Fish Anywhere With Water
Fish Anywhere With Water - FR
Soul-Cairn Objects Secured
Soul-Cairn Objects Secured - FR
Bard Instrumentals Mostly - Sing Rarely
Horns Are Forever (Persistent Argonian Horns)
Player Eyes Blink Fix
Floating Ash Pile Fix
Divine Crusader Creation Club Sword Fix
Nix-Hound Eyes Fix (Creation Club Nixhound Patch)
Iron Plate - Creation Club Content - Properly Environment Mapped
Orcish Plate - Creation Club Content - Properly Environment Mapped
Dwarven Armored - Creation Club Content - Properly Environment Mapped
Dead Man Dread - Creation Club Content - Properly Environment Mapped
Blackreach Tentacle Mesh Fix
Labyrinthian Shalidor's Maze Fixes
Labyrinthian Shalidor's Maze Fixes - FR
Assorted mesh fixes
Dlizzio's Mesh Fixes
LOD Unloading Bug Fix
I'm Walkin' Here NG with Pets
Sensible Sleepwalking - Wake up at nearest All-Maker Stone
Sprint Sneak Movement Speed Fix
Motionless Rocks Killing People Fix
Universal Cured Serana Eye Fix
MuJointFix
Dual Casting Fix
Explosion Collision Fix
FenixFixes
CrosshairRefEventsFix 0.0.1
Best In Class - SKSE Remake
Best in Class for Skyrim 1.5
Sound Fix for Large Sector Drives
Adoption Spouse and Moving Fixes
Adoption Spouse and Moving Fixes - FR
World Encounter Noble Riding Horse Fix - WERoad02
Thalmor Don't Report Crimes To Stormcloaks
Stuck on Sleeper Fix - Exit Noble Bed Double 02
Horse Save Load Fix
Better AltTab
Terrain Helper CS-ENB
Light Placer
ENB Terrain Blending Fix
Lightened Skyrim - Base Object Swapper edition
First Person Sneak Strafe-Walk Stutter Fix
Mum's the Word NG
To Your Face SE - AE - VR
Magic Fixes and Tweaks SKSE - BASE - OPTIONS MAGIE A REVOIR PLUS TARD
Magic Fixes and Tweaks SKSE - BASE - OPTIONS MAGIE A REVOIR PLUS TARD - FR
Magic Fixes and Tweaks for Skyrim 1.5
Persistent Favorites
[03 - UI HUD MENUS]
SkyUI 5.2 SE
SkyUI - Ghost Item Bug Fix
Regional Save Names
Notification Log SSE
Yes Im Sure
Copy and Paste in Console
Essential Favorites
Favorite Misc Items
Better Container Controls for SkyUI
Better MessageBox Controls
Better Dialogue Controls
Read Or Take SKSE
Use Or Take SKSE
Improved Help Command - SE - AE
Disable Numpad
Notification Filter - Remove unwanted notifications - CONFIG INI A FAIRE PLUS TARD
Security Overhaul SKSE - Lock Variations
Security Overhaul SKSE - Add-ons
Security Overhaul SKSE - Regional Locks
Security Overhaul SKSE - Some More Locks - BASE - PATCHES A REVOIR PLUS TARD
Security Overhaul SKSE - Extra Locks
UIExtensions
UIExtensions - FR
moreHUD SE
moreHUD Inventory Edition
A Matter of Time - A HUD clock widget
A Matter of Time - A HUD clock widget - Traduction FR
A Matter Of Time - Legacy Settings Loader
SkyHUD - A REINSTALLER PLUS TARD
Patch - SkyHUD 0.90.1B - A REVOIR APRES REINSTALL SKYHUD
TrueHUD - HUD Additions
TrueHUD - HUD Additions - FR
TrueHUD Curated Bosses
iWant Widgets
IWant Widgets NG
STB Widgets
STB Active Effects
Wheeler - Quick Action Wheel Of Skyrim
Infinity UI
Compass Navigation Overhaul
Detection Meter
Casting Bar
Better Third Person Selection - BTPS
Better Third Person Selection - BTPS - FR
OxygenMeter2
HD Local Map
Local Map Upgrade
Modern Wait Menu
Modern Wait Menu - FR
Atlas Map Markers - Updated with MCM - A REINSTALLER PLUS TARD
Atlas Map Markers - Updated with MCM - A REINSTALLER PLUS TARD - FR
Atlas Map Markers SE - Updated with MCM - Settings Loader
RaceMenu Special Edition v0-4-16
RaceMenu 0.4.16 Memory Leak Hotfix (SE)
RaceMenu Undress
Player Rotation in ShowRaceMenu
Extended Hotkey System
Dynamic Activation Key - MCM
Dynamic Activation Key - MCM - FR
Dialogue History
Dialogue History - FR
Subtitles
Hotkey Reminder
Load Screen Shading Fix
Menu Zoom
Notification Log SSE NG
Yes Im Sure NG
Too many notifications
PhotoMode
Skyrim Character Sheet
Name Those Ashpiles
Menu Maid 2 - MCM manager
Menu Maid 2 - MCM manager - FR
Menu Maid 2 - Generated INI
Show Player In Menus
Show Player In Menus - FR
Horse Stamina HUD - Script-Free
Floating Damage
Inventory Interface Information Injector
Inventory Interface Information Injector for Skyrim 1.5
Inventory Interface Information Injector - FR
I4 - SkyUI Weapons Pack
The Handy Icon Collection Collective
B.O.O.B.I.E.S (aka Immersive Icons) - FOMOD A REVOIR PLUS TARD
Aura's Scrumptious Supplement
Phenomenally Enriched and Nuanced Ingredients for SkyUI
Standing Stones - I4 icon
Diseases - I4 icon
Racial Abilities - I4 icons - FOMOD A REVOIR PLUS TARD
I4 Shout Icons Overhaul - FOMOD A REVOIR PLUS TARD
Unread Books Glow Redone
Unread Books Glow Redone - FR
Whose Quest is it Anyway NG
Vel'dun UI - A REINSTALLER PLUS TARD
Dragonborn Reskin - STB Widgets
Dragonborn Reskin - STB Active Effects
Dragonborn - Wheeler Reskin
Dragonborn Reskin - SkyUI Inventory Category Icons
[04 - AUDIO MUSIC VOICES]
Sound Record Distributor
Acoustic Space Improvement Fixes - SkyPatcher
Audio Overhaul for Skyrim (4.1.3) - A REINSTALLER PLUS TARD
Immersive Sounds - Compendium - A REINSTALLER PLUS TARD
Audio Overhaul - Immersive Sounds Integration (AOS - ISC Compatibility Patch) - A REVOIR APRES REINSTALLATION AOS ISC
Patches for Immersive Sounds 3.0 - Creation Club and more
Phoenix Compendium - - FOMOD PARTIEL A REVOIR PLUS TARD
Regional Sounds Expansion (SRD - Wilds Dungeons Towns Ambience Birds - Fixes)
Reverb Interior Sounds Expansion
NPC Dialogue Audio Enhancer
Meridia Revoiced SE
The Black Door Revoiced - Feminine
Quiet Better Jumping for CGO - Audio Overhaul - Immersive Sounds Integration - A REVOIR SI CGO ABSENT
Thundering Shouts
Authentic Wolf Howls and Aggro
More Painful Death Sounds SE
Update Plugin More Painful Death Sounds SE
50 Percent Chance More Painful Death Sounds SE
Blackreach Eerie Ambience
Nordic Winds
Ambient Warfare
Whales Off The Coast - FOMOD A REVOIR PLUS TARD
Distant Rolling Thunder
The Sounds of Towns and Cities
Murmurs and Mead - FOMOD A REVOIR PLUS TARD
Solstheim Exterior Soundscapes
Volkihar Soundscape Overhaul - A REINSTALLER PLUS TARD
Revenant Spirits of the Soul Cairn
Whispering Tomes of Apocrypha - FOMOD A REVOIR PLUS TARD
The Standing Sound Stones - A REINSTALL PLUS TARD
Bleeding Edge - Bladed Weapons SFX Overhaul - - A REINSTALLER PLUS TARD
Skullbreaker - Blunt Weapons SFX
Bulwark - Shield Audio Overhaul
Wildwood Echoes
Murder of Songbirds
Combat Music Fix NG Updated
New Game Sound on Continue (SKSE)
MEMOSPORE - UI Sound Effects
Still - Skyrim Inspired Music
Chapter II - Jeremy Soule Inspired Music
Melodies of Civilization - Skyrim Fan-Made Music
Hun Lovaas - Skyrim Fan-Made combat music
The Northerner Diaries - Immersive Edition (music by Jeremy Soule)
The Elder Songs - Complete - A REINSTALL PLUS TARD
Songs to Play Skyrim to - A Music Mod All in One
The Southerner Diaries - A Soundtrack Expansion
Symphonic Soundtrack - Extension HIGH QUALITY
Ragnarok - Viking Battle Music
BA Bard Songs
Magic College Music - Songs for Academy - DECOCHE - FORM 43
[05 - VISUAL BASE MESHES TEXTURES]
Static Mesh Improvement Mod
Static Mesh Improvement Mod - SMIM - Quality Addon
Unofficial Material Fix
SMIM - Quality Addon - Unofficial Material Fix Patch
Unofficial Material Fix - Assorted Mesh Fixes Patch
Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch
SMIM - Assorted Mesh Fixes Patch
Particle Patch for ENB
Ruins Clutter Improved SE
Ruins Clutter Improved - Fixes
RUSTIC CLUTTER COLLECTION - Special Edition - 2K
Forgotten Retex Project
TB's Improved Dust Particles
Rudy HQ - Miscellaneous SE - - FOMOD PARTIEL A REVOIR PLUS TARD
Glazed Pottery 2K-8K by iimVampy
Glazed Pottery HD - SE by Xtudo - 2K
Skyrim 3D Misc - Butterchurn
Skyrim 3D Misc - Chopping Block and Axe
Skyrim 3D Misc - Mammoth Cheese
Skyrim 3D Misc - Traps
Medieval Candlehorns and Sconces - FOMOD A REVOIR PLUS TARD
SD's Horn Candles SE 2k
Rally's Nord War Horns
Rudification - Rudy Candles Expanded - FOMOD A REVOIR PLUS TARD
Burned Book Retexture - 2k
Retexture for The Scroll
Eerie Ectoplasm
Surreal Spriggan Sap
Dusty Vampire Dust
Freezing Cold Frost Salts - SE
Volatile Void Salts
JS Bloodstone Chalice SE
JS Initiate's Ewer SE
JS Essence and Ash Extractors SE
JS Dwarven Oil SE
JS Dwemer Kitchenware SE
JS Dwemer Ichor Barrels SE
JS Torture Tools SE
JS Embalming Tools SE
Arc's Tankard Redux 2k
Arc's Kitchen redux 2k
Arc's MeadBarrel Redux 2k
Arc's Kettle Redux 2k
Stunning Statues of Skyrim
LeanWolf's Better-Shaped Talos with Greatsword
JS Shrines of the Divines SE
HD Glaze for JS Shrines of the Divines
Statue of Sithis 2k - PATCH WINTERSUN A VOIR
Daedric Shrines - All in One - 2K - PATCH WINTERSUN A VOIR
Rally's Solstheim Shrines
Sovngarde Watcher Retexture
CC's Enhanced Ore Veins SSE - 2K - 10.0
CC's HD Dwemer Automatons - Remastered - 2K
Dwemer Pipework Reworked 5 - refreshed
Improved Dwemer Glass - PATCHES A REVOIR
Dwemer Tech Glowmapped
JS Dwemer Puzzle Cube SE - 2k Textures
JS Dwemer Puzzle Cube SE - Glowmapped
JS Dwemer Control Cube SE - 2k Textures
JS Dwemer Control Cube SE - Glowmapped
JS Dwemer Artifacts SE - 2k Textures
JS Dwemer Artifacts SE - Glowmapped
JS Attunement Sphere and Lexicons SE - 2k Textures
JS Attunement Sphere and Lexicons SE - Glowmapped
JS Instruments of Skyrim SE - 2k
[05.1 - PARALLAX FRAMEWORK TEXTURES]
[06 - LANDSCAPE GRASS TREES WATER]
Terrain Fixes for CC Mods
Landscape Fixes For Grass Mods
Complementary Grass Fixes - A REINSTALLER PLUS TARD
Skyrim Landscape and Water Fixes - A REINSTALLER PLUS TARD
Majestic Mountains Main - A REINSTALLER PLUS TARD
Atlantean Landscape -Complete- 2K - DECOCHE A REINSTALLER PLUS TARD
Happy Little Trees - A REINSTALLER PLUS TARD
Happy Little Trees - Patch - A REVOIR APRES REINSTALLATION HLT
Enhanced Landscapes - Oaks Standalone SSE - Marsh Pines - Dilon Vul
Renthal Nettle SSE
Mari's flora
DrJacopo's - 3D Pine Grass (Old)
Origins Of Forest - 3D Forest Grass
Folkvangr - Grass and Landscape Overhaul
QW's Grass Patch 2 - Origins of Forest - Cathedral - Folkvangr
Cathedral - 3D Pine Grass for ENB Complex Grass
Origins of forest for ENB Complex Grass
Folkvangr for ENB Complex Grass
QW's Grass Patch 2 for ENB Complex Grass
GKB Waves Reborn
Splashes Of Storms
Water for ENB - No Parallax - A REINSTALLER PLUS TARD
Waterplants for Skyrim
Rudy HQ - Falling Leaves and Needles SE
Snowy Surfaces Sound Collision and Aesthetics - A REINSTALLER PLUS TARD
WAVY Waterfalls Effect
Storm Lightning for SSE and VR (Minty Lightning 2019)
ETHEREAL CLOUDS - Special Edition
Picta Series - Improved Sky Meshes
Rainbows Remade - 4K Version
Rainbows Remade - Hotfix Patch
Rainbows Remade - No Initialization Notification Patch
Shooting Stars SE
High Poly Canticle Tree
Canticle Tree Retexture - Bark
Canticle Tree Retexture - Tree
Canticle Tree Retexture - Draw Knife
Detailing the Eldrich - Higher-Res Apocrypha - Temple of Miraak - Black Books
Diverse Windmill Sails - Base Object Swapper
Giant Crab Shells- Mihail's Shards of Immersion (SE-AE version)
Sovngarde HD
Remove Hanging Moss From Trees
Edmond's Official Unique Flowers and Plants SSE
Better Dirt Cliffs and Alphas (2K)
the Pebbles SE
Man-Eater Giants - Base Object Swapper
Bloody Mammoth Carcasses- Mihail's Shards of Immersion (SE-AE version)
Bloody Mammoth Carcasses - My optimized textures and Hi-Poly meshes SE by Xtudo
[07 - CITIES TOWNS INTERIORS LIGHTING]
Lux Via (main)
Lux Via main plugin update
Updated Lux - Resources plugin
Lux Via meshes update
Lux Orbis - A COMPLETER PLUS TARD
Lux Orbis (patch hub) - A REINSTALLER PLUS TARD
Lux - PATCH HUB A FAIRE PLUS TARD
The Great Cities- Resources
The Great Town of Shor's Stone SSE
Rob's Bug Fixes - TGC Shor's Stone
The Great Town of Shor's Stone Patch Collection
The Great Village of Kynesgrove
Rob's Bug Fixes - TGC Kynesgrove - A REINSTALLER PLUS TARD
The Great Village of Kynesgrove Patch Collection - A COMPLETER PLUS TARD
The Great Village of Old Hroldan SSE
Rob's Bug Fixes - TGC Old Hroldan
The Great Village of Old Hroldan Patch Collection - A COMPLETER PLUS TARD
The Great Town of Karthwasten SSE
The Great Town of Karthwasten Patch Collection - A COMPLETER PLUS TARD
The Great Village of Mixwater Mill SSE
TGCoMM - SMIM Rope by WiZkiD
Rob's Bug Fixes - TGC Mixwater Mill
The Great Village of Mixwater Mill Patch Collection - A COMPLETER PLUS TARD
The Great Town of Ivarstead SSE
The Great Town of Ivarstead Patch Collection - A COMPLETER PLUS TARD
The Great City of Rorikstead SSE Edition
Rob's Bug Fixes - TGC Rorikstead - A REINSTALLER PLUS TARD
The Great City of Falkreath SSE Edition - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD
The Great City of Dawnstar SSE Edition
Cities of the North - Morthal - DECOCHE CHOIX A REVOIR
The Great City of Winterhold SSE Edition
Lainalten
Half-Moon Mill - Cities of the North Addon - CHOIX NOLVUS - PATCHES A VOIR PLUS TARD
Half-Moon Mill - Cities of the North Addon Patch Collection - A COMPLETER PLUS TARD
Anga's Mill - Cities of the North Addon
Anga's Mill - Cities of the North Addon - FR
Anga's Mill - Cities of the North Addon Patch Collection - A COMPLETER PLUS TARD
Environs - Master Plugin
Environs - Hroggar's House
Environs - Hroggar's House - A COMPLETER PLUS TARD
Sunthgat - PATCHES A VOIR PLUS TARD
Oakwood - PATCHES A VOIR PLUS TARD
Reich Corigate - PATCHES A VOIR PLUS TARD
Granite Hill Village - PATCHES A VOIR PLUS TARD
Amber Guard - PATCHES A VOIR PLUS TARD
Dunpar Wall - PATCHES A VOIR PLUS TARD
Vernim Wood - PATCHES A VOIR PLUS TARD
Vernim Wood USSEP Patch
Stonehills - PATCHES A VOIR PLUS TARD
Dunmer Settlements of Solstheim ESL - PATCHES A VOIR PLUS TARD
Amol Village - PATCHES A VOIR PLUS TARD
Laintar Dale - PATCHES A VOIR PLUS TARD
The Great Settlement of Darkwater Crossing - PATCHES A VOIR PLUS TARD
Darkwater Crossing - TGV Addon Patch Collection - A COMPLETER PLUS TARD
[07.1 - PLAYER HOMES]
Hearthfire multiple adoptions - Now with custom home support for kids and spouse
JK's Riverfall Cottage - PATCHES A VOIR PLUS TARD
JK's Riverfall Cottage - PATCHES A VOIR PLUS TARD - FR
Sicarius' Refuge SSE - A Hitman's Hideout - Assassin Home - PATCHES A VOIR PLUS TARD
Sicarius' Refuge SSE - A Hitman's Hideout - Assassin Home - PATCHES A VOIR PLUS TARD - FR
Ruska - Riften Player Home - PATCHES A VOIR PLUS TARD
Ruska - Riften Player Home - PATCHES A VOIR PLUS TARD - FR
Wind Path SSE 1.3.1 - PATCHES A VOIR PLUS TARD
Wind Path SSE 1.3.1 - PATCHES A VOIR PLUS TARD - FR
Lakeview Manor - As It Should Be
Lakeview Manor - As It Should Be - FR
Lakeview Manor - As It Should Be - CC Fishing Compatibility Patch
[07.2 - FARMHOUSES]
Northern Vanilla Farmhouses
Unique Northern Vanilla Farmhouses - Non Snowy Regions
Nordic Stonewalls
HD Classic Farmhouses - Complex Parallax - 2k
Stonewall Parallax - Alternate Grey Color - 4K
Farmhouse Fences SE Version 2 - 2k
CC's HQ Carts - 2K - 1.0
CC's HQ Buckets - 2K - 1.1
HD Wheat 2K
Scarecrows of Skyrim - BOS
Scarecrows of Skyrim - BOS - SOS Patch - DECOCHE REQUIERT SIMPLICITY OF SNOW
Iconic's REAL HAY - Redux 2K
R's Windmill
[07.3 - OTHER LOCATIONS]
Near Vanilla Project - College of Winterhold Floor
This Is Jorrvaskr - Home Of The Companions - PATCHES A VOIR PLUS TARD
This Is Jorrvaskr - Home Of The Companions - PATCHES A VOIR PLUS TARD - FR
JK's Fort Dawnguard - PATCHES A VOIR PLUS TARD
JK's Fort Dawnguard - PATCHES A VOIR PLUS TARD - FR
JK's Castle Volkihar - PATCHES A VOIR PLUS TARD
JK's Castle Volkihar - PATCHES A VOIR PLUS TARD - FR
[07.4 - LANDS]
Drinking Fountains of Skyrim for SSE - A REINSTALL PLUS TARD
Drinking Fountains of Skyrim for SSE - A REINSTALL PLUS TARD - FR
Drinking Fountains - My HD version ESPFE SE
Drinking Fountains - My HD version ESPFE SE - FR
Hold Border Banners - PATCHES A VOIR PLUS TARD
Hold Border Banners - PATCHES A VOIR PLUS TARD - FR
Man Those Borders Reborn 1.0.3 - PATCHES A VOIR PLUS TARD
Man Those Borders Reborn 1.0.3 - PATCHES A VOIR PLUS TARD - FR
Road Signs Overhaul - PATCHES A VOIR PLUS TARD
My Road Signs are Beautiful - A REINSTALL PLUS TARD - FR
Road Signs - WiZkiD Signs stack - A REVOIR PLUS TARD
Road Signs - WiZkiD Specific Signs
Solitude Temple Frescoes - Complete (No Lanterns) ESL
Solitude Temple Frescoes - Complete (No Lanterns) ESL - FR
Sepolcri - A Complete Burial Sites Overhaul - PATCHES A VOIR PLUS TARD
Sepolcri - A Complete Burial Sites Overhaul - PATCHES A VOIR PLUS TARD - FR
Imperial Forts Parallax Meshes
HD Remastered Imperial Forts - 2k
Ryn's Lady Stone - PATCHES A VOIR PLUS TARD
Ryn's Standing Stones - PATCHES A VOIR PLUS TARD
Ryn's Standing Stones - PATCHES A VOIR PLUS TARD - FR
Ryn's Anise's Cabin - PATCHES A VOIR PLUS TARD
Ryn's Saarthal - PATCHES A VOIR PLUS TARD
Ryn's Saarthal - PATCHES A VOIR PLUS TARD - FR
Ryn's White River Watch - PATCHES A VOIR PLUS TARD
Ryn's White River Watch - PATCHES A VOIR PLUS TARD - FR
Ryn's Halted Stream Camp - PATCHES A VOIR PLUS TARD
Ryn's Secunda's Kiss - PATCHES A VOIR PLUS TARD
Ryn's Secunda's Kiss - PATCHES A VOIR PLUS TARD - FR
Ryn's Bleakwind Basin - PATCHES A VOIR PLUS TARD
Ryn's Bleakwind Basin - PATCHES A VOIR PLUS TARD - FR
Ryn's Bleakwind Basin USSEP Patch
Ryn's Goldenglow Estate - PATCHES A VOIR PLUS TARD
Ryn's Bleak Falls Tower - PATCHES A VOIR PLUS TARD
Ryn's Crabber's Shanty and Titanclaw Lair - PATCHES A VOIR PLUS TARD
Ryn's Crabber's Shanty and Titanclaw Lair - PATCHES A VOIR PLUS TARD - FR
Ryn's Valtheim Towers - PATCHES A VOIR PLUS TARD
Ryn's Valtheim Towers - PATCHES A VOIR PLUS TARD - FR
Ryn's Bleak Falls Barrow - PATCHES A VOIR PLUS TARD
Ryn's Loreius Farm - PATCHES A VOIR PLUS TARD
Ryn's Loreius Farm - PATCHES A VOIR PLUS TARD - FR
Ryn's Sarethi Farm - PATCHES A VOIR PLUS TARD
Ryn's Sarethi Farm - PATCHES A VOIR PLUS TARD - FR
Ryn's Ustengrav - PATCHES A VOIR PLUS TARD
Ryn's Mistwatch Folly - PATCHES A VOIR PLUS TARD
Ryn's Mistwatch Folly - PATCHES A VOIR PLUS TARD - DSD FR
Ryn's Karthspire - PATCHES A VOIR PLUS TARD
Ryn's Karthspire - PATCHES A VOIR PLUS TARD - DSD FR
Ryn's Western Watchtower - PATCHES A VOIR PLUS TARD
Ryn's Western Watchtower - PATCHES A VOIR PLUS TARD - DSD FR
Ryn's Snow Shod Farm - PATCHES A VOIR PLUS TARD
Ryn's Robber's Gorge - PATCHES A VOIR PLUS TARD
Ryn's Robber's Gorge - PATCHES A VOIR PLUS TARD - DSD FR
Orc Strongholds - Narzulbur - PATCHES A VOIR PLUS TARD
Orc Strongholds - Narzulbur - PATCHES A VOIR PLUS TARD - DSD FR
Orc Strongholds - Largashbur 2 ESL - PATCHES A VOIR PLUS TARD
Orc Strongholds - Largashbur 2 ESL - PATCHES A VOIR PLUS TARD - DSD FR
Orc Strongholds - Mor Khazgur - PATCHES A VOIR PLUS TARD
Orc Strongholds - Mor Khazgur - PATCHES A VOIR PLUS TARD - DSD FR
Orc Strongholds - Dushnikh Yal - PATCHES A VOIR PLUS TARD
Orc Strongholds - Dushnikh Yal - PATCHES A VOIR PLUS TARD - DSD FR
[07.5 - RUINS]
RUSTIC RELIEFS
RUSTIC RELIEFS - Parallax
CleverCharff's Nordic Ruins
Gorgeous Ruin Door SE 2K
Tower Ruins 2k Texture Replacer
[07.6 - INTERIORS]
Underground - a dungeon texture overhaul
Underground - Complex Parallax Addon
CC's HQ Barset - 2K - 1.2
Skyrim Sewers 415
Skyrim Sewers 415 - FR
Distinct Interiors - PATCHES A VOIR PLUS TARD
Distinct Interiors - PATCHES A VOIR PLUS TARD - FR
Distinct Interiors - Fixes
Distinct Interiors - Fixes - FR
JK's Dragonsreach - PATCHES A VOIR PLUS TARD
JK's Dragonsreach - PATCHES A VOIR PLUS TARD - FR
RedBag's Dragonsreach - SE - PATCHES A VOIR PLUS TARD
JK's and Redbag's Dragonsreach Patch
JK's and Redbag's Dragonsreach Patch - FR
JK's The Winking Skeever - PATCHES A VOIR PLUS TARD
JK's The Winking Skeever - PATCHES A VOIR PLUS TARD - FR
JK's Angeline's Aromatics - PATCHES A VOIR PLUS TARD
JK's Angeline's Aromatics - PATCHES A VOIR PLUS TARD - FR
JK's Bits and Pieces - PATCHES A VOIR PLUS TARD
JK's Bits and Pieces - PATCHES A VOIR PLUS TARD - FR
JK's Radiant Raiment - PATCHES A VOIR PLUS TARD
JK's Radiant Raiment - PATCHES A VOIR PLUS TARD - FR
Ryn's Sleeping Giant Inn - PATCHES A VOIR PLUS TARD
Ryn's Sleeping Giant Inn - PATCHES A VOIR PLUS TARD - FR
Ryn's Hod and Gerdur's House - PATCHES A VOIR PLUS TARD
Ryn's Hod and Gerdur's House - PATCHES A VOIR PLUS TARD - FR
Ryn's Sven's and Hilde's House - PATCHES A VOIR PLUS TARD
Ryn's Sven's and Hilde's House - PATCHES A VOIR PLUS TARD - FR
Ryn's Faendal's House - PATCHES A VOIR PLUS TARD
Ryn's Faendal's House - PATCHES A VOIR PLUS TARD - FR
Ryn's Alvor and Sigrid's House - PATCHES A VOIR PLUS TARD
EEKs Whiterun Interiors SSE - PATCHES A VOIR PLUS TARD
JK's The Bannered Mare - PATCHES A VOIR PLUS TARD
JK's Arcadia's Cauldron - PATCHES A VOIR PLUS TARD
JK's Warmaiden's - PATCHES A VOIR PLUS TARD
JK's Belethor's General Goods - PATCHES A VOIR PLUS TARD
JK's The Drunken Huntsman - PATCHES A VOIR PLUS TARD
The JK's Interiors of EEK's Whiterun - A REINSTALLER PLUS TARD
JK's White Phial
JK's Sadri's Used Wares
JK's New Gnisis Cornerclub
JK's Palace of the Kings - PATCHES A VOIR PLUS TARD
JK's Blue Palace - PATCHES A VOIR PLUS TARD
Blue Palace Frescoes Simplified - PATCHES A VOIR PLUS TARD
JK's Elgrim's Elixirs - PATCHES A VOIR PLUS TARD
JK's The Bee and Barb - PATCHES A VOIR PLUS TARD
JK's The Pawned Prawn
JK's The Ragged Flagon
JK's Mistveil Keep
JK's The Temple of Mara
JK's Silver-Blood Inn
JK's Arnleif and Sons Trading Company
JK's The Hag's Cure
JK's Riverwood Trader - PATCHES A VOIR PLUS TARD
Riverwood Trader Is A Mess - PATCHES A VOIR PLUS TARD
JK's Understone Keep - PATCHES A VOIR PLUS TARD
JK's Candlehearth Hall - PATCHES A VOIR PLUS TARD
JK's Temple of Dibella - PATCHES A VOIR PLUS TARD - VERIFIER SEXLAB DIBELLA SISTERHOOD
JK's Temple of Kynareth - PATCHES A VOIR PLUS TARD
JK's Temple of Talos - PATCHES A VOIR PLUS TARD
JK's Temple of the Divines - PATCHES A VOIR PLUS TARD
Dunmeri Furniture in Gray Quarter - PATCHES A VOIR PLUS TARD
JK's Haelga's Bunkhouse - PATCHES A VOIR PLUS TARD
JK's Jorrvaskr - PATCHES A VOIR PLUS TARD
JK's High Hrothgar - PATCHES A VOIR PLUS TARD
JK's Sky Haven Temple - PATCHES A VOIR PLUS TARD
JK's Septimus Signus's Outpost - PATCHES A VOIR PLUS TARD
JK's Sinderion's Field Laboratory - PATCHES A VOIR PLUS TARD
JK's Castle Dour - PATCHES A VOIR PLUS TARD
JK's The Bards College - PATCHES A VOIR PLUS TARD
JK's College of Winterhold - PATCHES A VOIR PLUS TARD
College of Winterhold Brazier Overhaul - PATCHES A VOIR PLUS TARD
JK's Dark Brotherhood Sanctuaries - PATCHES A VOIR PLUS TARD
JK's Nightingale Hall - PATCHES A VOIR PLUS TARD
GG's Thieves Guild Headquarters - PATCHES A VOIR PLUS TARD - main 1.3 + plugin update 1.3.1 + cubemap update installés
GG's Thieves Guild Headquarters Update Main Plugin
GG's Thieves Guild Headquarters Update Customs Cubemaps
PELTAPALOOZA Special Edition - FULL
RUGNAROK - Special Edition - 2K
Detailed Rugs SE
Detailed Rugs clean SE
JS Rumpled Rugs SE
Sigils of Skyrim - Shields
Sigils of Skyrim - Banners
Thrones of Skyrim SE
Snazzy Furniture and Clutter Overhaul SE - FOMOD aucune optionaddon coché - PATCHES A VOIR PLUS TARD
Statue of Kynareth - PATCHES A VOIR PLUS TARD
Kynareth - My patches SE by Xtudo - LUX JKs Temple
[08.1 - CORE CHARACTERS TOOLS]
Expressive Facegen Morphs SE
BodySlide and Outfit Studio - v5.8.1
High Poly Head SE
High Poly Head UV Stretch Fix (NECK SEAM FIXED)
[08.2 - HAIR-EYES-BROWS-OVERLAYS]
Flawn's Vanilla Argonians Redux
Vanilla hair remake
High Poly Vanilla Hair
Vanilla hair - Salt and Wind
Conditional Expressions - Subtle Face Animations
Conditional Expressions Extended
RS Children Overhaul - CHOIX NOLVUS - A REINSTALL PLUS TARD
KS Hairdos SSE
KS Hairdos - HDT SMP (Physics)
Hair Suppression Fix
Chooey's KS Hairdos Retexture - Vanilla Match
Chooey's KS Hairdos and Vanilla Hair Retexture
Chooey's KS Hairdos Retexture - HDT-SMP Addon
[Dint999] HairPack02 SSE 1.11 (base)
[Dint999] BDOR Hairs SSE 0.24
Expressive Facial Animation -Male Edition-
Expressive Facial Animation -Female Edition-
The Eyes Of Beauty SSE
Kala's Eyes
Kala's Eyes Update 1.2
Kala's Eyes ESL Plugin
The Eyes of Beauty - Vampire Eyes SE - PATCHES A VOIR PLUS TARD
Kalilies Brows
Just Blood - Dirt and Blood Lite - PROVISOIRE - SANG LEGER UNIQUEMENT - HYGIENE A REVOIR PLUS TARD
Lamenthia's Marks of Beauty 2k
Community Overlays 1 - Main - CBBE 2K
Community Overlays 1 - Bugfix Patch
Community Overlays 1 - Female Face Overlays
Community Overlays 1 - Male Face Overlays
Community Overlays 2 - Main - CBBE and Male - CHOIX PROVISOIRE CBBE+MALE - COHERENT 3BA3BBB - A REVOIR SI BODY FINAL CHANGE
SkFO SE -Skin Feature Overlays- 4K - INSTALLE PLUS TOT QUE PREVU - OK SI TEST MENU PROPRE - A REVOIR AU BLOC SKINS
Female Makeup Suite - Face - 4K - INSTALLE PLUS TOT QUE PREVU - OK SI TEST MENU PROPRE - A REVOIR AU BLOC SKINS
Community Overlays 3 - Main - CBBE and Male
Yyvengar Bodypaints - Female and Male (CBBE)
Sakora's Make Over Kit - SKSE64
Lyru's Tattoo pack collection
[08.3 - BODY - SKINS - BODYSLIDE]
Caliente's Beautiful Bodies Enhancer - CBBE - MORPHS RACEMENU NON INSTALLES - A REVOIR AVEC 3BA OBODY BODYSLIDE
RoughSpun Tunic and Prisoner Bloody Fix
CBBE 3BA (3BBB) - A REINSTALL PLUS TARD - OPTIONS SOS COLLISIONS
The New Gentleman - PATCHES A VOIR PLUS TARD
The New Gentleman - Generated INI
PB's Silky Skin - SKIN PJ UNIQUEMENT A TERME - ACTUELLEMENT ECRASEE PAR BNP - A ISOLER PLUS TARD
Tempered Skins for Males - SOS Full Version
BnP female skin (Replacer+Player version)
BnP female small update
[09 - ANIMATIONS SKELETON PHYSICS]
Faster HDT-SMP
CBPC - Physics with Collisions - FPS CONFIG 120 SI SKYRIM LIMITE A 120
XP32 Maximum Skeleton Special Extended - XPMSSE - A VERIFIER FOMOD PLUS TARD
Auto Skeleton Patch - Universal Behaviour Runtime
Open Animation Replacer
SKYFORGE - Open Animation Replacer Output
Animation Motion Revolution
Payload Interpreter
Paired Animation Improvements - PATCHES A VOIR PLUS TARD
Pandora Behaviour Engine v4.3.1-beta
SKYFORGE - Pandora Output
No Spinning Death Animation Merged LITE
True Directional Movement - Modernized Third Person Gameplay
Precision - Accurate Melee Collisions - TK DODGE RE A VERIFIER PLUS TARD
TK Dodge SE
TK Dodge RE - Script Free - FOMOD A REVOIR PLUS TARD
Sound For TK Dodge SE
Smooth TK Dodge Attack - DAR REQUIREMENT COUVERT PAR OAR
[10 - GAMEPLAY COMBAT MAGIC PERKS]
Valhalla Combat
Nether's Follower Framework - FOMOD À REVOIR PLUS TARD
Nether's Follower Framework - Legacy Settings Loader
Comprehensive Attack Rate Patch - SKSE
Wait Your Turn - Enemy Circling Behaviour
NPCs Take Cover - Smarter Anti-Cheese AI
NPCs Use Potions - FOMOD A REVOIR PLUS TARD
NPCs Use Potions - SKYFORGE Config
Smart Optimal Salves - Optimal Potion Hotkey MCM
Smart Optimal Salves - Optimal Potion Hotkey MCM - Settings Loader
Simple Offence Suppression
Simple Offence Suppression MCM - Block Friendly Fire
I'm Talkin' Here
Instantly Skip Dialogue NG
Disable Follower Collision
I'm Walkin' Here
No Furniture Camera
Pick Up Radius
A Closer Look SSE
Headhunter - Bounties Redone - FOMOD & PATCHES A REVOIR PLUS TARD
Simplest Horses (and other mounts)
Animated Whistling
Simplest Horses - Animated Whistling Patch
No Need to Ask... Bounty Is Served
State Your Claw
Food For The Thirsty - FOMOD A REVOIR PLUS TARD
Skyrim's Got Talent - Improve As a Bard - PATCHES ET FIXES À REVOIR PLUS TARD
Switch Camera During Dialogue
Dragon Claws Auto-Unlock
Take a Peek - New Stealth Mechanic - PATCHES A REVOIR PLUS TARD
Classic Sprinting Redone (Latest version for SE)
Taunt Your Enemies - Taunting Matters
Remote Interactions
SkyParkour v3 - Procedural Parkour and Climbing Framework (SPPF)
SkyParkour v3 - Additional Pandora Patch For CRC32 Cache
SkyParkour v3 - SKYFORGE ini
NPC No Block Exhaustion
NPC No Block Exhaustion - MCM
3rd Person Camera Stagger Remover
Block Enchantments
Archery Locational Damage
Bow Charge Plus
No BS AI Projectile Dodge
VioLens - A Killmove Mod SE
VioLens - A Killmove Mod SE - Settings Loader
[10.1 - RACES WEREBEASTS VAMPIRES]
Aetherius - A Race Overhaul - FOMOD A REVOIR PLUS TARD
Aetherius - Race Menu Racial Passive Descriptions
Mundus - A Standing Stone Overhaul
Sacrosanct - Vampires of Skyrim
Cover Your Head - Sacrosanct
Sun Affects NPC Vampires
Manbeast - A Werewolf Overhaul
[11 - QUESTS WORLDS FOLLOWERS]
[11.1 - FOLLOWERS NPCS DIALOGUES]
Bandit Lines Expansion
Civil War Lines Expansion
Forsworn and Thalmor Lines Expansion
Vampire Lines Expansion
Brawl Lines Expansion and Fixes
Additional Dremora Faces - PATCHES A VOIR PLUS TARD
Dremora Lines Expansion
NPCs React To Necromancy (And More)
NPCs React To Invisibility
Bow of Shadows (CC) - Invisibility Patch
NPCs React To Frenzy
Carriages and Stables Dialogue Bundle
Show NPC Disposition Relationship Rank
Dialogue Window Auto Close Exit Begone
Scared of Shootings - NPCs react to aiming bows
Dialogue Expansion - Windhelm
Dialogue Expansion - Shor's Stone
Dialogue Expansion - Khajiit Caravans
Neutral Whiterun Guards
Truly Neutral Prisoners
More Sensible Quartermasters
Robber's Gorge Fixes - FOMOD À REVOIR PLUS TARD
Guard Dialogue Overhaul SE
Guard Dialogue Overhaul MCM
GuardsTalk
Misc Dialogue Edits - FOMOD À REVOIR PLUS TARD
More Dialogue Options - FOMOD À REVOIR PLUS TARD
Relationship Dialogue Overhaul - RDO SE
Relationship Dialogue Overhaul - Update and MCM
Cutting Room Floor - FOMOD À REVOIR PLUS TARD
RDO - CRF and USSEP Patches Final
AI Overhaul SSE - FOMOD À REVOIR PLUS TARD
AI Overhaul - Relationship Dialogue Overhaul Patch
AI Overhaul - Cutting Room Floor Patch
Run For Your Lives
Realistic Conversations
Considerate Followers - Followers are Silent During Dialogue
Considerate Followers for Skyrim 1.5
Chatty NPCs and Followers
Collision Dialogue Overhaul
Additional Healing Reactions
Shouts of Stallholders
Falmer Servant Lines Expansion
Missing Voices in Hearthfire Added Back
Cheeky Kids
SPID NPC Trap Safety
More to Say - FOMOD A REVOIR PLUS TARD
Follower Dialogue Expansion - Olfina Gray-Mane
REBEL NORTH - Immersive Dialogue Expansion - Stormcloaks
Follower Dialogue Expansion - Uthgerd the Unbroken
Follower Dialogue Expansion - Ysolda
Follower Dialogue Expansion - Jordis the Sword-Maiden
Follower Dialogue Expansion - Camilla Valerius
Follower Dialogue Expansion - Illia - PATCHES A VOIR PLUS TARD
Follower Dialogue Expansion - Lydia
Follower Dialogue Expansion - Mjoll the Lioness - PATCHES A VOIR PLUS TARD
Follower Dialogue Expansion - Brelyna Maryon - PATCHES A VOIR PLUS TARD
Follower Dialogue Expansion - Erik the Slayer
Follower Dialogue Expansion - Faendal
Follower Dialogue Expansion - Roggi Knot-Beard
Follower Dialogue Expansion - Marcurio (FDE)
Follower Dialogue Expansion - Sapphire (FDE)
Follower Dialogue Expansion - Rayya
Follower Dialogue Expansion - Borgakh the Steel Heart
Follower Dialogue Expansion - Aranea Ienith
Follower Dialogue Expansion - Faralda
Follower Dialogue Expansion - Jenassa - PATCHES A VOIR PLUS TARD
Follower Dialogue Expansion - Eola
Follower Dialogue Expansion - Aela the Huntress - PATCHES A VOIR PLUS TARD
RDO - FDE Compatibility Patch
[11.2 - CUSTOM FOLLOWERS COMPANIONS]
INIGO
FDE Illia Inigo patch
FDE Brelyna Inigo patch
FDE Jenassa Inigo patch
FDE Aela Inigo Patch
FDE Aela Patch - Thogra
Lucien - Immersive Fully Voiced Male Follower
FDE Brelyna Lucien patch
FDE Aela Lucien Patch
Song of the Green (Auri Follower)
FDE Mjoll Auri patch
FDE Brelyna Auri Patch
FDE Jenassa Auri Patch
FDE Aela Auri Patch
Remiel - Custom Voiced Follower - FOMOD A REVOIR PLUS TARD
Remiel - Missing Voice Lines
Remiel - 1.7.6 HotFix
FDE Mjoll Remiel patch
FDE Aela Remiel Patch
Xelzaz - Custom Fully Voiced Argonian Telvanni Follower
Xelzaz Anniversary Edition Plugin 1.12.0
Xelzaz Follower Wyrmstooth Patch - DECOCHE EN ATTENTE DU BLOC QUETES
Xelzaz Sirenroot Patch - DECOCHE EN ATTENTE DU BLOC QUETES
FDE Xelzaz Aela Patch
Skyrim's Got Talent - Xelzaz Reacts To Your Music
Xelzaz' Telvanni Spellsword Armor Enhanced
Lulu's Xelzaz - Xelzaz Visual replacer
Thogra gra-Mugur - Orc Follower and Quest - PATCHES A VOIR PLUS TARD
Gore - A Companion Mod - FOMOD & PATCHES A REVOIR PLUS TARD
Serana Dialogue Add-On SE - PATCHES A VOIR PLUS TARD
Serana Re-Imagined
Hood Plus Hair for Serana Re-Imagined
Dovahnique's High Poly Inigo
Dovahnique's High Poly Inigo Replacer - ESPFE
Skyrim's Got Talent - Inigo Reacts To Your Music
Snazzy Items for Inigo
Mr. Dragonfly ENB Particle Light
Cosmos Lucien Replacer
Majestic Auri - A visual replacer
Majestic Auri - A Visual Replacer - Human Teeth
Song of the Green Auri Follower Inigo Banter Patch ESLified
Skyrim's Got Talent - Auri Reacts To Your Music
Snazzy Items for Auri (Song of the Green)
BiR's Remiel Replacer
Serana Dialogue Add-On Patch Hub - FOMOD A REVOIR PLUS TARD
Axarien's Animations - Custom Followers - Lucien
Axarien's Animations - Custom Followers - Auri
Axarien's Animations - Custom Followers - Inigo
Menagerie - An Anniversary Edition Pet Overhaul
Show Follower Carry Weight
Show Mount Carry Weight
[12 - SURVIVAL IMMERSION ROLEPLAY]
Skyrim Unbound Reborn - ALTERNATE START - A REINSTALLER PLUS TARD
[13 - SEXLAB CORE ADULT FRAMEWORKS]
MuJointFix - Sexlab Ostim Patch - DECOCHE RESERVE SEXLAB
[13.1 - SEXLAB ANIMATIONS ADULT RESOURCES]
[14 - DEVIOUS DEFEAT SLAVERY PROSTITUTION]
[15 - ARMORS CLOTHES OUTFITS NSFW]
[15.1 - BODYSLIDE OUTPUTS OUTFITS]
[16 - PATCHES CONFLICT RESOLUTION]
[17 - DYNDOLOD OUTPUTS GENERATED FILES]
[18 - TOOLS OUTPUTS]
SKYFORGE - Creation Kit Output
SKYFORGE - ESP-ESM-Translator Output
SKYFORGE - xTranslator Output
SKYFORGE - Photo Mode Output
[19 - TRADUCTIONS FR]
Overwrite
```

---

## Notes post-snapshot

- Snapshot créé avec emplacement manuel réservé pour éviter les blocages du connecteur GitHub.
- Après collage manuel du brut MO2 complet, ce fichier devra être vérifié puis déclaré comme nouvelle référence courante dans `docs/procedure/00_resume_etat_actuel.md`.
- Le README devra être ajusté manuellement si le connecteur GitHub continue de bloquer sa mise à jour automatique.
