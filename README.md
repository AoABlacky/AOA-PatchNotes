# AOA-PatchNotes
# Build 0.1.65 (December 2024)


# New Features:
- Introduced a beacon show function for easier navigation.
- Added follow system (v1) via /follow command in chat.
- A combat range visualizer was added for enhanced strategy planning.
- Expanded tattoo system and improved dissolve effects for characters.
- New camera zoom and pan functionality added.
- Launcher finalized (Alpha stage, initial releases - will get patches and bug fixes from here on out).
- 0.1.65 officially released for testers.

# Dungeons & Puzzles:
- Reworked TOTE with new puzzles (v1) and post-processing.
- Introduced sequential puzzle systems with reset functionality.
- Fully implemented collection and rotation puzzles with sound extensions.

# Gameplay Improvements:
- Targeting System Overhaul: Refined targeting controllers for precision.
- Loot system revamped — players can now pick up items using the interact key.
- Removed right-click for attack mode to simplify control schemes.

# Environment & Effects:
- Updated terrain data and details for better immersion.
- New vignette script added to coordinate visual effects.
- Self-shop animations and footsteps detection revamped.

# Creature Updates:
- Slime slot mechanics reworked with a focus on VFX integration.
- Added Wyrmbat mob and its resource pointers for biome integration.

# Game Mechanics:
- Major updates to environmental elements such as terrain, water systems, and foliage.
- Updated and optimized draw detail settings for various areas.
- Resolved target portrait loading issues for NPCs/mobs.
- Introduced time control in character selection, capped at 23:59.

# Visuals & Audio:
- Initial implementation of a vignette script for visual enhancements.
- Adjustments to audio scripts in various contexts, including inventory interactions.
- Townhall fixes with revamped atmospheric biomes for F1.
- Addressed audio biome playback errors and other minor terrain fixes.
- Restored point light systems for street lamps and optimized godrays.
  Added silence tracks and emitter prefabs for smoother audio transitions.

# Performance & Bugs:
- Significant terrain and environmental optimization for smoother gameplay, especially in F1.
- Added DCA manager for frame optimization during character loading.
- Terrain improvements and grass density adjustments.
- Fixed crafting station canvas hover issue.
- Enhanced fireflies, SSGI rendering, and resolved puzzle system errors.




# Build 0.1.18 (October 2023)

# General:
- Maintenance: Bug tracker added! DM Blacky for access if you want to help and report bugs you find.
- Removed the issue where morphing into a bunny lets you carry around weapons on its back.
- Multiple new code features & scripts added for various use-cases like sounds, animation behaviors and optimization behavior.

# World:
- Velledor Spring added, mostly fleshed out. Proping required.
- Dozens of Quests added - including new ones in Silirad.
- Main Questline (Part 1) finalized.
- Rathos Village has been put on the map and already has NPCs with quests. Layout & buildings are works in progress.
- Woodcutter Camp has been put on the map.
- Greenwood Ruins added.
- Greenwood Ruins (Outer) have been added.
- Greenwood Tomb has been added.
- Greenwood Spring Pond added.
- Silirad Ponds added.
- Gremlin Camps (multiple locations) added.
- Bandit Camp area terrain mapped out - albeit not yet added.
- Rathos Fields have been added.
- Mobs around Greenwood & the Rathos Fields have been added.
- Velledor (instance) has been added.
- Water shaders & visuals have been redesigned.
- Missing water areas, rivers and
- Missing Loot Tables on certain mobs have been added & spawn rates have been adjusted.
- Level-up Rewards have been added for leveling up your player level.
- Gathering nodes (fishing, mining, herbalism, woodcutting) have been laid out around the map and enabled.
- Additional weapons and weapon styles (Dual-Shields) have been added since 0.1.11, albeit Dual-Shields are not yet usable.
- Silirad area has been upgraded visually, a fair bit optimized.
- New vegetation has been added, many plants and a variety of bushes.
- Impostors for all objects have been recreated from scratch including new LOD levels and settings.
- Server mob-loading performance has been optimized and increased.
- New wildlife mobs have been added.
- Visual effects for nature (birds, etc.) have been added & existing ones have been adjusted for performance.
- Fish have been optimized.
- All old VFX for water has been completely replaced.
- Camera underwater effects for all underwater zones have been implemented.
- Various shader performance optimizations.
- Enabled a multitude of new terrains (which will be fleshed out in the following weeks).
- Magma Cave Dungeon added (Floor 4 proof-of-concept showcase).
- Forgotten Cavern Dungeon added (Floor 1 - no TP option yet).

# Gameplay and Combat:
- Complete rework of the player's abilities (values, timing, damage, animations, and sound).
- Complete rework of mob abilities (same as for players).
- All monsters have their own AI and a set of 3 different attacks depending on their cooldown times and health status.
- Skills are now locked to the ability level (not all unlock at once, instantaneously). This will be fleshed out further in 2024 for a skill-tree unlock system.
- All equipment has been completely rebalanced (armor, accessories). Weapons as well as monster stats still need proper values and bosses fall like flies.
- Bug fixes for animation durations and transitions, missing animations.
- All missing swim zones have been implemented.
- Added roaming NPCs around the map.
- Added sample "bark" dialogue chatter to NPCs. Currently, it's placeholder talk.
- Added the first instance of a Notice Board in Silirad. This will be fleshed out in future builds.

# Audio:
- Music zones set up almost everywhere in all new locations.
- SFX zones are set up for almost all objects that need it (streams, lakes, waterfalls).
- Wildlife mobs have now sounds attached.

# Report requests (please report the following as bugs): 
- Missing sounds for things you believe need a sound.
- Missing visual effects for any mob or player attack.
- Issues with sound abruptly cutting off, ending, or disappearing instead of smoothly fading out.
- Issues with sound getting distorted.
- Falling through the terrain, anywhere (remember about /stuck).
- Missing Loot from mobs (or wrong loot, or nonsensical loot).
- Game Settings not carrying over between maps/worlds/play sessions.
- Broken, too high, too low, or missing swimming areas.
- Ground sounds being wrong, missing, or simply not appearing in certain areas.


# There are many more fixes... 
- but frankly speaking, we literally get so much done, that we forget to list all of it. Full change history of every change to the game, ever, can be found on our Discord.
- https://discord.com/channels/147113220820172800/717068695599448065
- 
