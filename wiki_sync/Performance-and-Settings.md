# Performance and Settings

Farbound ships with a full optimization stack (Sodium, Lithium, ModernFix, C2ME and many more) and is tuned to run well out of the box. A few options are left to you, because they depend on your hardware.

## RAM

- **8 GB minimum** allocated to Minecraft.
- Do not allocate everything your PC has. Leave a few GB to the system.
- The first launch is slow (mod setup, asset and shader compilation). That is normal and only happens once.

## Shaders

**Iris** is included, and the pack ships **Complementary Reimagined** and **Complementary Unbound** with Euphoria Patches, tuned for Farbound. Shaders are optional and your own choice stays when you update.

⚠️ **Create: Aeronautics has known rendering issues with Iris shaders.** Moving vessels (airships in flight, ships under way) may render incorrectly with some shader packs. Euphoria Patches improve compatibility with the Complementary packs, but results vary. If your vessel looks wrong in motion, try without shaders before reporting a bug.

## Good starting settings

These are starting points, not rules. Adjust to your hardware.

| Setting | Suggestion |
|---|---|
| Render distance | 10 to 12 chunks |
| Simulation distance | 6 to 8 chunks. Physics vessels are CPU intensive, so this matters. |
| Shaders | Off while you are building and testing large vehicles |
| Particles | Lower them if storms or busy kitchens cost you frames |

## If performance drops

1. Disable shaders, especially around large moving vessels.
2. Lower the simulation distance.
3. Lower the render distance.
4. Check how many vessels are loaded nearby. Very large or numerous vessels cost real performance. Elegant beats enormous.
5. Park vehicles away from your main base, and in one place rather than scattered across many chunks.

## Reporting performance issues

Please include your specs, allocated RAM, whether shaders were active, and which vessels were nearby. Report on the [issue tracker](https://github.com/DefinitivTim/farbound/issues/new/choose).
