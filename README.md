# WowTube

Watch YouTube in a framed window on top of World of Warcraft: On a flight path, during a crafting session, or in a small window that stays up while you play.

**Status:** early test build (0.3.1), shared with a few testers.

WowTube is not affiliated with, approved by or endorsed by Blizzard Entertainment or YouTube.

## Download

Get the latest `WowTube-Setup-<version>.exe` from the [Releases page](https://github.com/petey85/WowTube/releases) and run it. It needs no administrator rights, adds WowTube to the Start menu, and a newer Setup updates it in place. A welcome window then shows the hotkey and lets you try the player on the desktop before you start the game.

Prefer no installer? `WowTube-<version>-win-x64.zip` on the same page holds the same app: Unzip it, read `README-FIRST.txt`, and run `WowTube.exe`. Nothing else needs installing on most PCs.

- **Windows 10 or 11, 64-bit.** Not Mac or Linux.
- **WoW in "Fullscreen (Windowed)" or "Windowed" mode.**
- Tested with WoW: Forever on Windows 11. Other WoW versions and Windows 10 are untested.
- The downloads are not code-signed yet, so Windows SmartScreen warns on first run: Choose **More info**, then **Run anyway**.

## What it does

- A small tray app. Press **Ctrl+Alt+Y** in the game to show or hide the video.
- One player showing the full YouTube site. Drag its border to resize, or press the maximize button (or **Ctrl+Alt+S**) to fill the game and again to go back. Press **Ctrl+Alt+F** for video full screen: The video alone, filling the player.
- The player is wide for regular videos and tall for YouTube Shorts. It switches by itself, and Shorts play one after another.
- The bottom edge of the border is a time line you can click or drag to jump through the video, and the bar shows the time. Home, Shorts and Share buttons go to those YouTube pages and copy a link to the video on show. A video full screen button fills the player with the video alone, and a like button there presses YouTube's own.
- Click the video to pause it, or scroll the page, **without taking your keyboard away from the game**.
- **Lock** fixes the frame in place and lets clicks pass through it to the game.
- The border, and optionally the bar, hide when your pointer is away.
- The frame stays inside the game window, hides when the game is minimized or covered (the video keeps playing unless you choose otherwise in Settings), and stays hidden when the game is launched until you ask for it.
- Every hotkey can be changed or turned off in Settings, which also holds opacity, the other options and a reset to defaults. Open it from the player's menu or the tray icon.
- Your keyboard's own play and pause key works on the video while you are in the game.
- Sign in to YouTube inside the player for your subscriptions and history. If you have YouTube Premium, videos play without ads, as they do on the website. WowTube remembers the sign-in.

## What it does not do

It checks GitHub for a newer version at start, every 3 hours and when you close the game. The check is always on. It only asks which version is newest and sends nothing about you. It does not read the game's memory, modify the game, inject into it, or send it any input. It is a separate window that floats above the game, and it looks only at where the game window is and which window is in front.

Blizzard has not approved it. We found no rule that forbids a passive video window, and none that authorizes one. Using it on your account is your decision.

YouTube plays through the normal YouTube site, with its ads and controls untouched.

## Feedback

Open an [issue](https://github.com/petey85/WowTube/issues). Say what you were doing, what you expected, what happened, and how many monitors you use.

For requests, fan mail and business inquiries, email Adam Peterson at [petersonadam1985@gmail.com](mailto:petersonadam1985@gmail.com).

## More

- How to use it: [HELP.md](HELP.md)
- First steps and removal: [README-FIRST.txt](README-FIRST.txt)
- Changes in each version: [CHANGELOG.md](CHANGELOG.md).

## Ownership

Copyright (c) 2026 Adam Peterson (Petey85). All rights reserved. No license is granted: You may run the official builds for your own use, but you may not copy, modify or redistribute the app or its source code without permission. See [LICENSE.txt](LICENSE.txt). The third-party software included in the builds is listed in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
