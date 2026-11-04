# Wuaklock

A desktop companion for Deadlock on Windows: what to buy next, an in-game overlay, enemy scouting on the loading screen, post-match grades and your match history.

This repository only hosts the downloads. The source code is not published here.

## Download and install

1. **[Download Wuaklock for Windows](https://github.com/quakeob/wuaklock-releases/releases/latest/download/Wuaklock-win-x64.zip)**. This one link always gets the newest version.
2. Unzip it anywhere and run `Wuaklock.exe`.
3. In Wuaklock, go to **Settings → Install on this PC**. It moves itself to `%LOCALAPPDATA%\Wuaklock` and adds Start menu and desktop shortcuts.
4. Play Deadlock in **borderless** or **windowed** mode so the overlay can show.

The download isn't code-signed yet, so Windows SmartScreen may warn you. Choose **More info → Run anyway** if you trust this source.

## Updates

Installed copies update themselves. Wuaklock checks this repository a few times a day, downloads a new version, checks its SHA-256 fingerprint and installs it when you close the app. It never updates during a match, and your settings and match history are kept.

## Is it safe?

- **It reads. It never touches.** Like other Deadlock companion apps that show live match data, Wuaklock reads the game while you play: your hero, items, souls and the lobby. It only reads. It never injects code, changes game files or sends input, and it reads directly rather than through a platform like Overwolf. As with any third-party tracker, nobody can promise how anti-cheat will treat it, so we won't pretend otherwise.
- **Unofficial.** Wuaklock is not made, endorsed or supported by Valve.
- **Public data.** Scouting, profiles, builds and grades use public match data from [deadlock-api.com](https://deadlock-api.com). Scouting is off until you allow it; when allowed, the Steam account IDs of the players in your match are sent there to look up their public records. Your screen, chat and files are never sent.
- **Discord** status is off unless you turn it on.

## Feedback

Found a bug or have an idea? Open an issue in this repository.
