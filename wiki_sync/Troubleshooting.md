# Troubleshooting

Most problems fall into one of the groups below. If yours does not, open an [issue](https://github.com/DefinitivTim/farbound/issues/new/choose) and include the details listed at the bottom of this page.

## Known issues

| Problem | Status and workaround |
|---|---|
| **Vessels look broken or flicker with shaders** | Known issue of Create: Aeronautics with Iris on moving vessels. Try without shaders. Euphoria Patches improve compatibility with the shipped Complementary packs, but results vary. |

## There is no quest book

The quest mods are a separate download on the first launch. Follow the steps on the start screen, or see [[Installation]]. If you skipped the screen, restart the game and it appears again.

## The game does not start or crashes on launch

1. **Wait on the first launch.** It takes much longer than usual and can look frozen.
2. **Check your RAM.** Allocate at least 8 GB, but do not allocate more than your system can spare.
3. **Did you change the mods?** Remove your changes or reinstall the instance, then try again.
4. **Update the pack completely** through your launcher. A half-updated instance is a common cause of crashes.
5. **Still crashing?** Open the instance folder, then `crash-reports` and `logs/latest.log`, and attach them to an issue.

## "Mod mismatch" or "Cannot connect" on a server

- Server and client need the **same pack version**. Update your pack or ask the server owner.
- Remove any mods you added yourself and try again.

## Low FPS or stutter

See [[Performance and Settings]]. The usual suspects, in order:

1. Shaders active.
2. High simulation distance with many vessels around.
3. Too little (or far too much) allocated RAM.

## Vehicles behave strangely

- Large or complicated vessels can lag or glitch. Try a smaller version to see if the problem remains.
- Check whether the vessel is partly in unloaded chunks.
- Open the Contraption Diagram: missing parts, bad balance or blocked propellers show up there.
- If the problem only appears with shaders, see the first entry in the table above.

## Missing items, settings or quests after an update

Updates can remove items, reset `options.txt` or change quests. The [[Changelog]] lists these changes at the top of each version. See [[Updating]] for how to update safely.

## What to include in a bug report

- Pack version and launcher
- Singleplayer or multiplayer
- Allocated RAM and your system (CPU, GPU)
- Whether shaders were active
- Whether you added, removed or updated mods yourself
- What you did, what you expected, what happened
- Your `latest.log` (for example through https://mclo.gs) and, for crashes, the crash report

The issue form asks for exactly this, so you can simply fill it out.
