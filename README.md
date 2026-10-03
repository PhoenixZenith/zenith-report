# Zenith Report

A Trials of Osiris lobby lookup for Destiny 2 on PC. When a match is loading, press F8 and the app
reads the Nearby roster, finds every player's Bungie Name and shows all six of them on your second
monitor: Elo, flawless runs, K/D, loadouts, fireteams, head to head and a win chance.

When the board is empty it shows this week in Trials instead: maps, the countdown, rewards and
what weapons people are using.

Unofficial, not affiliated with Bungie.

## Install

1. Download `ZenithReport-Setup-<version>.exe` from the [latest release](../../releases/latest).
2. Run it. It installs for your Windows user only, no admin needed, and starts the app.
3. Windows might say "Windows protected your PC" because the installer isn't signed. Click
   **More info**, then **Run anyway**.

## Updates

When a new version is out, an **Update** button shows up in the title bar. Click it and the app
downloads the update, installs it and restarts. It only checks when it starts and every few hours,
and nothing downloads until you click.

## Using it

- Keep the game on one monitor and the app on another. The app never takes focus from the game.
- When a Trials match starts loading, press **F8** (or click Scan). The app opens the roster with
  your Roster key (U by default), hovers each player, closes it again and puts your cursor back.
  It takes a few seconds.
- The first scan works out which player is you from the top of the roster. If it gets it wrong,
  click your name and pick **This is me**, or set it in Settings.
- Click a player for their full report. Ctrl K searches for anyone. Press ? for all shortcuts.

If you changed the Roster keybind in game, change it in Settings too.

If a name can't be read with certainty, the app flags it and lets you pick from suggestions
instead of guessing.

## About the game input

To read the roster the app presses your Roster key and moves the mouse over the player list, the
same as you would by hand, and only while Destiny is the focused window. It doesn't read or change
game memory, hook into the game or touch its network traffic. Still, it's a third party tool, so
use it at your own risk.

## Your data

Settings, searches and recent lobbies stay on your PC, in `%APPDATA%\Zenith Report`. The only
thing that goes out is the lookups themselves, to Bungie.net, Trials Report and DestinyTracker.

## Problems

If something goes wrong, open an issue here and attach `app.log` from `%APPDATA%\Zenith Report`.
