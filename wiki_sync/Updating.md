# Updating

Farbound gets regular updates: new mods, new quests, fixes and balance changes. Updating is quick, but a few habits keep your world safe.

## Before you update

1. **Back up your world.** Copy the world folder from `saves` in your instance folder somewhere safe. Updates can remove mods or items, and there is no undo.
2. **Read the changelog.** The [[Changelog]] marks important changes at the top of each version, for example removed items or settings that get reset.
3. **Note your own changes.** Mods you added yourself and settings you changed may be overwritten.

## How to update

- The title screen tells you when a newer version is out.
- In the **Modrinth App**, open the instance and update it there. Other launchers have their own update or reimport function.
- **Never mix files from different pack versions by hand.** A half-updated instance is the most common cause of crashes.
- If the quest mod screen appears again after the update, repeat the steps from [[Installation]].

## Things an update can change

| What | What to do |
|---|---|
| **Removed items or blocks** | They disappear from existing worlds and inventories. The changelog lists them. Back up first. |
| **`options.txt`** | Some updates overwrite it, for example to fix key bindings. The changelog warns you. Back it up if you care about your video settings and keys. |
| **Shipped configs and shader settings** | Pack defaults can change. Your own choices may have to be set again. |
| **Mods you added** | They are not part of the pack and may break or disappear. |

## On a server

Server and all clients must run the **same pack version**. Update the server first, then tell your players. See [[Multiplayer]].

## Something broke?

Restore your backup, then check [[Troubleshooting]]. If the problem stays, open an [issue](https://github.com/DefinitivTim/farbound/issues/new/choose) with the old and the new pack version.
