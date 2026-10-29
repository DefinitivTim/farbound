# Changelog

All notable changes to Farbound are documented here. Newest version first.
Always back up your worlds before updating.

## 1.1.1fix3 (2026-10-29)

*A small patch for a lighter first start.*

### Under the Hood
- Shaders no longer start switched on for new installs. You can still turn on Complementary Reimagined with Euphoria Patches in the video settings.
- No mod changes in this version.

### Config Changes
- Iris: the preset that enabled shaders by default is no longer shipped.
- Distant Horizons: the shipped config is gone again, so it falls back to its own defaults.

## 1.1.1fix2 (2026-10-29)

*Another small step to keep things steady.*

### Fixed
- Rolled back Player Animation Library to 1.1.6.
- Removed an obsolete glider script left over from older installs. Glider slot tags are now handled in one place.

### Config Changes
- No config changes in this version.

### Mod Shelf
**Downgraded**
- **Player Animation Library:** `2.0.4` → `1.1.6`

## 1.1.1fix (2026-10-29)

*A quick patch to get your key bindings and Distant Horizons settings in order.*

### Fixed
- Old key binding scripts from earlier versions could fight with the new defaults. They are cleared now, and the Farbound key bindings apply once more after this update.
- The Distant Horizons config was missing from 1.1.1. It is back.

### Config Changes
- Distant Horizons: generator plan is Surface Then Chunks (was disabled) and the low memory warning on startup is off.
- Key bindings: the one-time apply marker was raised so everyone gets the latest defaults.

## 1.1.1: Eyes on the Horizon (2026-10-29)

> [!IMPORTANT]
> Several content mods were removed in this update. Their items and blocks will disappear from existing worlds. Please back up your worlds before updating. Your key bindings are also set to the new Farbound defaults once after updating.

*Ahoy, Farbounders! Radar sees further, the pack carries fewer extras, and your update notes now show up in game. Time to scan the skies and head out.*

### Setting Sail
- **Create: Radar 5.0.** A big step up: Sable ships show up as silhouettes on the radar, there is a new targeting computer for cannon auto-fire, chaff, and volume sliders for the radar sounds.
- **Update notes in game.** Modpack Update Checker tells you when a new version is out and shows what changed.
- **One home for key bindings.** Vehicles, horses, voice chat, pings and more now follow a single set of Farbound defaults.
- **Leaner pack.** Sixteen mods are gone, among them Async Particles, Chunky, BBE and Create: Copper and Zinc.
- **Smoother servers.** ServerCore is now switched on with a lower monster cap.
- **Fresh looks for mobs.** New resource packs for zombies, illagers and blazes.
- **Icy's Better Horses 2.1.7.** Horses can plough, take a "wander" dismount command and show ability banners.

### New Arrivals
- Just Enough Items with JEI Optimizer and IrisSearch
- Modpack Update Checker, Raise Sound Limit Simplified, Cubes Without Borders, Nowheel and Reflex AntiLag
- Battle Music, Animated Hearts, Corn Expansion, Create Furnace Lava Adapter and Simply Create Model
- Optimized Block Entities is back
- New resource packs: Bray's Zombie Overhaul 1.5, Drodi's Blazes 1.4.1, Drodi's Illagers 5.3.2 and Fresh Weapons and Tools Compat

### Under the Hood
- Enhanced Celestials 2 now runs on its Core module instead of Default Lunar Events.
- Reworked the REMI stack groups, about 100 files fewer than before.
- Five quests that belonged to removed mods are gone, six chapters were adjusted and Corner Cafe is now Cafe Corner.
- Update notes now come from Modpack Update Checker instead of the FancyMenu screen.

### Farewells
- Async Particles, BBE, Chunky, Dynamic Sound Culling, Particle Interactions, Chunk Activity Tracker, Does It Tick and SSRD
- Create: Copper and Zinc (its Asurine and Veridium recipes stay), Molten Metals, Pipe Organs, Visual Workbench, Peaceful Moon 2, In Control and Supplemental Patches
- Sable Photomancy

### Config Changes
**Server**
- ServerCore is now active: villager lobotomizing and dynamic performance checks are on, the monster cap is 50 (was 70), and Friends & Foes Glares and Rascals have their own caps. This also clears the config warning about Glares.

**Client defaults**
- Sodium Extra: cloud height override is on at 319, system and tutorial toasts are off.
- VanillaBackport: falling leaves and the sheep wool undercoat are off.
- Soft Imprints: imprint model contact is off.
- Punchy: new camera animations option, on by default.
- Distant Horizons: the config file was dropped in this version and returns in 1.1.1fix.

**New options from updated mods**
- Create Radar: targeting computer, chaff, Sable silhouette and radar sound settings.
- Amendments: pets follow teleports, bubble columns pass through grates.
- Icy's Better Horses: ploughing, dismount command, radial style and ability banners.
- Foundation: attribute icons. Sophisticated Inventory Interactions: sort button offset for the decoration table.
- Collective: the mob drop loop setting is gone.

**Resource packs**
- Added: Bray's Zombie Overhaul 1.5, Drodi's Blazes, Drodi's Illagers 5.3.2, Fresh Weapons and Tools Compat.
- Removed: Fresh Animations with its extensions and compat packs, Beautiful Enchanted Books, the Create Simple Storage packs, Vocal Villagers and the Fresh Flower Pots packs.

### Mod Shelf
37 mods were updated.

- **Amendments:** `2.2.0` → `2.2.4`
- **Better End:** `21.0.38` → `21.0.39`
- **Better Nether:** `21.0.29` → `21.0.30`
- **C2ME:** `0.4.0-alpha.0.123` → `0.4.0-alpha.0.124`
- **Cinematic Respawn:** `1.4.1` → `1.4.3`
- **Collective:** `8.62` → `8.68`
- **Create Encased:** `1.10.0` → `1.10.0-fix1`
- **Create Flight Control:** `0.7.7` → `0.8.3`
- **Create Lazy Tick:** `2.7.31-6.0.10` → `2.7.33-6.0.10`
- **Create Radar:** `0.4.9.4` → `5.0.3`
- **Enhanced Celestials 2:** Default Lunar Events `2.0.1.3` → Core `2.0.3.3`
- **Envelope:** `0.8.0` → `0.8.1`
- **ExtraLib:** `3.2.2` → `3.3.1`
- **Friends & Foes:** `5.0.3` → `5.0.4`
- **Fzzy Config:** `0.7.7` → `0.7.7+fix1`
- **Hexalia:** `1.3.8.1` → `1.3.8.2`
- **Icy's Better Horses:** `2.1.4` → `2.1.7`
- **LDLib2:** `2.2.42` → `2.2.44`
- **ModernFix:** `5.27.26` → `5.27.27`
- **Modonomicon:** `1.120.7` → `1.121.0`
- **Nature's Spirit:** `2.3.1` → `2.3.2`
- **Platform:** `1.4` → `1.4.2`
- **Player Animation Library:** `1.1.6` → `2.0.4`
- **Polytone:** `5.2.0` → `5.3.4`
- **Punchy:** `2.8g` → `3.0`
- **Puzzles Lib:** `21.1.65` → `21.1.66`
- **Random Optimization:** `1.7.5` → `1.7.6`
- **REMI:** `4.7.12` → `4.8.1`
- **Sodium Extra:** `0.9.4` → `0.9.5`
- **Sophisticated Backpacks:** `3.26.14` → `3.26.17`
- **Sophisticated Core:** `1.5.17` → `1.5.19`
- **Sophisticated Inventory Interactions:** `0.1.14` → `0.1.15`
- **Sophisticated Storage:** `1.6.8` → `1.6.10`
- **SuperMartijn642's Core Lib:** `1.1.25` → `1.1.26`
- **The Lead Age:** `1.2.0` → `1.2.1`
- **VanillaBackport:** `1.2` → `1.2.2`
- **WorldWeaver:** `21.0.29` → `21.0.30`

*Fair winds and soft landings. See you in the skies!*
*Tim*

## 1.1.0fix (2026-10-22)

*A quick patch to keep your airships where you parked them.*

### Fixed
- Rolled back Create Deep Seas to 3.3.0. The newer 3.4.4 made airships take off and fly away on their own.

### Mod Shelf
**Downgraded**
- **Create Deep Seas:** `3.4.4` → `3.3.0`

## 1.1.0: Tracks & Tides (2026-10-22)

> [!IMPORTANT]
> Several content mods were removed in this update. Their items and blocks will disappear from existing worlds. Please back up your worlds before updating.

*Ahoy, Farbounders! Rails now run through the world, the quests have a fresh start, and the pack wakes up 10 to 30 seconds faster. Time to head out and come back with a few stories.*

### Setting Sail
- **Quests, rebuilt from the ground up.** Every questline got a fresh start.
- **Changelogs in game.** Read what changed without leaving the game.
- **Create: Steam 'n' Rails.** Trains and railways are now part of the pack.
- **Vanilla Backport update.** More of modern Minecraft, including features from the Copper Age and Mounts of Mayhem drops and a few from Wilderness Bound.
- **Tom's Simple Storage.** Connect your chests and reach everything from one place.
- **Renewable Copper and Zinc.** Create: Copper and Zinc can be produced again and again, so you never run dry.
- **Hybrid Birds.** Birds now take to the air and fly around the world.
- **Faster loading.** Startup is 10 to 30 seconds shorter, depending on your system.
- **Leaner pack.** The Kaleidoscope mods and SimpleHats are gone.
- **Distant Horizons is optional.** Enable it in the options (restart required). Loading screens can take up to 60 seconds longer with it.
- **New resource packs.** Create Ultra, Metals Ultra and Stained Glass Ultra.

### New Arrivals
- Create: Steam 'n' Rails, Create: Copper and Zinc, Create Contraption Terminals and Create Aeronautics Physics Gantry
- Tom's Simple Storage, Hybrid Birds, Hybrid Delights, Magic Vibe Decorations, Let's Do Smoker and Better Than Mending
- Apple Wood Rebarked is back
- Performance mods: Async, BBE, Faster Iris Shadow Mapper, Ixeris, Random Optimization and Dynamic Sound Culling

### Under the Hood
- Completely reworked the quest system.
- Added the in-game changelog viewer.
- Reduced startup time by 10 to 30 seconds.
- Updated NeoForge to 21.1.264.

### Farewells
- Kaleidoscope Cookery, Tavern, Nether and End
- Create: Gears and Tavern, Ender's Delight, Spud's Shops, Better Beds, SimpleHats, Grind Enchantments and Field Guide
- Constant Music, Reactive Music, Entity Sound Features, Fancy Entity Renderer, Optimized Block Entities, Smooth Boot, CIT Resewn and Extra Mod Integrations

### Mod Shelf
50 mods were updated.

- **3d-Skin-Layers:** `1.11.3` → `1.11.4`
- **Accessories:** `1.1.0-beta.53` → `1.1.0-beta.54`
- **Accessories Compatibility Layer:** `0.1.12` → `0.1.13`
- **AdvancedCoreInfo:** `1.4.0` → `1.5.0`
- **AdvancedLootInfo:** `2.4.0` → `2.5.0`
- **Almanac:** `1.5.2` → `1.26.10.3`
- **AmbientSounds:** `6.3.10` → `6.3.11`
- **Amendments:** `2.1.11` → `2.2.0`
- **AsyncParticles:** `21.1.4.7` → `21.1.4.10`
- **BCLib:** `21.0.27` → `21.0.28`
- **Better End:** `21.0.37` → `21.0.38`
- **Better Mods Button:** `21.1.0` → `21.1.1`
- **Better Nether:** `21.0.28` → `21.0.29`
- **Cinematic Respawn:** `1.4.0` → `1.4.1`
- **Climbable Ropes for Create Aeronautics:** `2.1.4` → `2.2.0`
- **Collective:** `8.54` → `8.62`
- **Continuity: NeoForged:** `3.0.0` → `3.0.9`
- **Create Encased:** `1.9.0-ht3` → `1.10.0`
- **Create: Compatible Storage:** `2.13.0` → `2.14.0`
- **Enhanced Boss Bars:** `1.1.1` → `1.1.2`
- **Envelope:** `0.7.5` → `0.8.0`
- **Fallingleaves:** `2.5.1` → `2.6.0`
- **Forgified Fabric API:** `0.116.15+2.3.5` → `0.116.15+2.3.6`
- **Friends & Foes:** `5.0.2` → `5.0.3`
- **Icy's Better Horses:** `2.1.3` → `2.1.4`
- **Immersive Overlays:** `1.8.5` → `1.8.6`
- **Let's Do Bakery:** `2.1.10` → `2.1.11`
- **Let's Do Meadow:** `1.4.9` → `1.4.10`
- **LetMeDespawn:** `1.5.0` → `1.26.10.2`
- **Lightspeed:** `2.0.5` → `2.0.5+hotfix`
- **Nature's Spirit:** `2.2.6` → `2.3.1`
- **oωo:** `0.12.15.5-beta.1` → `0.12.15.6-beta.1`
- **Petrolpark's Library:** `1.5.10` → `1.5.12`
- **Pipe Organs:** `0.8.2` → `0.9.2.1`
- **Platform:** `1.3.3` → `1.4`
- **Polytone:** `5.1.2` → `5.2.0`
- **Punchy:** `2.8f` → `2.8g`
- **Puzzles Lib:** `21.1.64` → `21.1.65`
- **Separate Sable Render Distance:** `1.8.6` → `1.8.7`
- **Sophisticated Backpacks:** `3.26.12` → `3.26.14`
- **Sophisticated Core:** `1.5.13` → `1.5.17`
- **Sophisticated Storage:** `1.6.7` → `1.6.8`
- **Sound Physics Remastered:** `1.5.1` → `1.5.2`
- **Starter Kit:** `8.3` → `9.0`
- **Supplementaries:** `4.0.1` → `4.0.2`
- **The Lead Age:** `1.1.2` → `1.2.0`
- **Vanilla Backport Compat:** `2.2` → `2.3`
- **VanillaBackport:** `1.1.7.10` → `1.2`
- **WaveyCapes:** `1.11.2` → `1.11.3`
- **WorldWeaver:** `21.0.27` → `21.0.29`

*Fair winds and soft landings. See you in the skies!*
*Tim*

## 1.0.4fix3 (2026-10-18)

### Removed
- Removed Carry On and its EMF Compat addon, because it caused severe client lag.

## 1.0.4fix2 (2026-10-17)

### Fixed
- Adjusted the seat config to fix severe lag when sitting on a slab or stair while in a vehicle.

## 1.0.4fix (2026-10-16)

### Added
- Added Create: Ballast, a ballast block that makes balancing Create Aeronautics contraptions easier.
- Enabled Presence Footsteps and Presence Footsteps x Sable for more natural footstep sounds, including on Sable contraptions.

### Removed
- Removed MoreJS.
- Removed Carry On and its EMF Compat addon.
- Removed EMI Loot and EMI Ores.

### Fixed
- Fixed a crash when opening a villager's trade screen on a server. It was caused by a client and server mismatch.
- Fixed a joining error caused by mismatched mod versions.

### Mod Shelf
15 mods were updated.

- **Collective:** `8.53` → `8.54`
- **EMF Compat: Core:** `2.3.0` → `2.3.2`
- **EMF Compat: Immersive Melodies:** `1.2.0` → `1.2.1`
- **EMF Compat: Supplementaries:** `1.1.0` → `1.1.1`
- **EMF Compat: Take a Seat:** `2.0.0` → `2.0.1`
- **Enhanced Boss Bars:** `1.0.0` → `1.1.1`
- **Field Guide:** `1.21.4` → `1.21.5`
- **Icy's Better Horses:** `2.1.2` → `2.1.3`
- **Let's Do Farm & Charm:** `1.1.28` → `1.1.29`
- **Let's Do Furniture:** `1.1.9` → `1.1.10`
- **Let's Do Vinery:** `1.5.5` → `1.5.6`
- **Lightspeed:** `2.0.3` → `2.0.5`
- **SeeU:** `0.9.1.1` → `0.9.5`
- **Sophisticated Core:** `1.5.12.2400` → `1.5.13.2404`
- **Sophisticated Storage:** `1.6.6.2181` → `1.6.7.2184`

## 1.0.4 (2026-10-15)

### Mod Shelf
9 mods were updated.

- **AsyncLogger:** `2.2.2` → `2.2.3`
- **Collective:** `8.52` → `8.53`
- **Create Aeronautics: Automated Logistics:** `0.6.2` → `0.7.0`
- **Create Lazy Tick:** `2.7.30-6.0.10` → `2.7.31-6.0.10`
- **Entity Model Features:** `3.3.11` → `3.3.12`
- **Entity Texture Features:** `7.2.5` → `7.2.6`
- **Let's Do Wilder Nature:** `1.1.7` → `1.1.8`
- **Nature's Delight:** `1.13.1` → `1.13.2`
- **Nature's Spirit:** `2.2.5` → `2.2.6`

## 1.0.3 (2026-10-14)

### Added
- New accessory slots for spyglasses, gliders and lanterns.

### Changed
- Goggles and glasses now go into the dedicated glasses and goggles slots.
- Resource pack adjustments: new textures for buttons, sliders and other menu elements, new food and air bubble icons, and a new hotbar.
- The Farbound logo was updated.
- The Create questlines were reordered so the progression follows a logical order.

### Mod Shelf
49 mods were updated.

- **Amendments:** `2.1.10` → `2.1.11`
- **AsyncParticles:** `21.1.4.6` → `21.1.4.7`
- **BCLib:** `21.0.26` → `21.0.27`
- **Better End:** `21.0.35` → `21.0.37`
- **Better Nether:** `21.0.27` → `21.0.28`
- **C2ME:** `0.4.0-alpha.0.122` → `0.4.0-alpha.0.123`
- **Collective:** `8.42` → `8.52`
- **CorgiLib:** `5.0.0.9` → `5.0.0.10`
- **Create: Gears and Tavern:** `1.1.8` → `1.1.9`
- **CreativeCore:** `2.13.50` → `2.13.51`
- **DragonLib:** `3.0.28` → `3.0.29`
- **Field Guide:** `1.21.2` → `1.21.4`
- **Friends & Foes:** `5.0.1` → `5.0.2`
- **Icy's Better Horses:** `2.1.1` → `2.1.2`
- **ImmediatelyFast:** `1.6.14` → `1.6.15`
- **Kaleidoscope Compat:** `2.9.7-Patch` → `2.9.7-Patch.2`
- **Kaleidoscope Cookery:** `1.5.1` → `1.6.0`
- **Let's Do Alpine Whispers:** `1.0.3` → `1.0.4`
- **Let's Do Bakery:** `2.1.8` → `2.1.10`
- **Let's Do Brewery:** `2.1.12` → `2.1.13`
- **Let's Do Candlelight:** `2.1.14` → `2.1.15`
- **Let's Do Farm & Charm:** `1.1.27` → `1.1.28`
- **Let's Do Furniture:** `1.1.6` → `1.1.9`
- **Let's Do Hearth & Timber:** `1.0.4` → `1.0.5`
- **Let's Do Wilder Nature:** `1.1.6` → `1.1.7`
- **Lightspeed:** `2.0.2` → `2.0.3`
- **Lithostitched:** `1.8.0` → `1.8.1`
- **Moonlight Lib:** `3.7.1` → `3.7.2`
- **Oh The Biomes We've Gone:** `2.6.2` → `2.6.3`
- **Oh The Trees You'll Grow:** `5.3.4` → `5.3.5`
- **Optimized Block Entities:** `1.1.45` → `1.1.52`
- **Particle Rain:** `4.0.1` → `4.0.2`
- **Placebo:** `9.9.3` → `9.9.4`
- **Polytone:** `4.5.3` → `5.1.2`
- **Punchy:** `2.8e` → `2.8f`
- **Puzzles Lib:** `21.1.62` → `21.1.64`
- **Reliable EMI:** `4.7.9` → `4.7.12`
- **Sophisticated Backpacks:** `3.26.9.2195` → `3.26.12.2208`
- **Sophisticated Backpacks Create Integration:** `0.2.2.188` → `0.2.3.194`
- **Sophisticated Core:** `1.5.7.2381` → `1.5.12.2400`
- **Sophisticated Storage:** `1.6.2.2159` → `1.6.6.2181`
- **Sophisticated Storage Create Integration:** `0.1.22.238` → `0.1.23.246`
- **Sophisticated Storage In Motion:** `0.10.35.372` → `0.10.36.381`
- **Subtle Effects:** `1.15.0` → `1.15.1`
- **Supplementaries:** `3.9.9` → `4.0.1`
- **Take a Seat:** `1.0.3` → `1.0.4`
- **VS Sable Hose Connectors:** `0.1.8` → `0.2.2`
- **WorldWeaver:** `21.0.26` → `21.0.27`
- **WunderLib:** `21.0.10` → `21.0.11`

## 1.0.2fix (2026-10-10)

> [!IMPORTANT]
> **Your `options.txt` will be overwritten again by this update.** Back it up first if you want to keep your video settings and other client options.

### Changed
- The default `options.txt` was adjusted again.

## 1.0.2 (2026-10-10)

> [!IMPORTANT]
> **Your `options.txt` will be overwritten again by this update.** Back it up first if you want to keep your video settings and other client options. This time the default keybinds in the file are correct.

### Added
- [Scribble](https://modrinth.com/project/yXAvIk0x)

## 1.0.1 (2026-10-10)

> [!IMPORTANT]
> **Your `options.txt` will be overwritten by this update.** Back it up before updating if you want to keep your video settings, keybinds and other client options, and re-apply them afterwards.

### Added
- [Peaceful Moon 2](https://modrinth.com/project/tasFtZEL)
- [Critters and Companions](https://modrinth.com/project/Yd4wb5wZ)
- [Constant Music](https://modrinth.com/project/tvuSEM6E)
- [Reactive Music](https://modrinth.com/project/Bqnfeesx)
- [Lighty](https://modrinth.com/mod/lighty)

### Changed
- Four quest-related mods were moved out of the main pack into a separate download, because keeping them inside prevented the launcher from applying updates:
  - certain_questing_additions
  - ExtraQuests
  - FTBQuestsOptimizer
  - more_quest_types

### Fixed
- The configs of Advancement Disable Mod were adjusted, so **Keep Some Inventory works again**.

## 1.0.0fix

### Fixed
- Shader packs were only partially included in 1.0.0. The shader pack selection is now complete.

## 1.0.0 (2026-10-09)

First official release of Farbound for Minecraft 1.21.1 on NeoForge.

### Highlights
- **Vehicles of every kind:** walkable airships with Create: Aeronautics, steamships and submarines, trains and land vehicles, and late in the pack, rockets.
- **A world worth crossing:** vast continents, hand-crafted structures in every dimension and living oceans. Structure loot is instanced per player.
- **Engineering without a wall:** a large, curated collection of Create addons covering logistics, diesel, radar, cannons, electronics and nuclear power.
- **A home worth returning to:** cooking, baking, brewing, a tavern, a cheese cellar, furniture, photography and instruments, all automatable with Create.
- **Quests as a travel journal:** a large quest book that guides without gating. Vanilla advancements are replaced by quests that fit the pack.
- **Built to run:** a full optimization stack. Heavy extras like Distant Horizons are optional and ship disabled.

### Pack details
- Create, Create: Aeronautics and Sable as the technical core.
- Custom item stack groups for REMI, built by hand.
- Custom main menu with version check and RAM notice.
- Client and server support.
- Recommended: 8 GB RAM (12 GB with Distant Horizons).

### Known issues
- Shaders (Iris) can cause rendering problems on moving airships. See [Troubleshooting](https://github.com/DefinitivTim/farbound/wiki/Troubleshooting).