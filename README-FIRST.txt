WowTube 0.2.9 (test build)
==========================

Watch YouTube in a framed window on top of World of Warcraft.
This is an early test build shared with a few testers. It is not made,
approved or endorsed by Blizzard Entertainment or YouTube.


BEFORE YOU START
----------------
* Windows 10 or 11, 64-bit. It does not run on Mac or Linux.
* WoW must be in "Fullscreen (Windowed)" or "Windowed" display mode.
* Blizzard has not approved this program. It does not read the game's
  memory, change the game, or press keys for you: It is a video window
  that floats over the game. No rule we found forbids that, but nothing
  authorizes it either. Using it on your WoW account is your choice.


HOW TO START IT
---------------
1. Put WowTube.exe anywhere you like (your Desktop is fine).
2. Start World of Warcraft and log in to a character.
3. Double-click WowTube.exe.

   Windows will probably show "Windows protected your PC" the first
   time, because this test build is not signed. Click "More info",
   then "Run anyway".

4. It asks once whether to start with Windows. Either answer is fine.
5. The player appears over the game showing YouTube. Sign in to
   YouTube in it if you want your subscriptions or Premium.

After this, WowTube waits in the system tray (the small icons near the
clock. Look for a dark circle with a gold play triangle). When you
launch the game later, the video stays hidden until you ask for it.


HOTKEYS (work while you are playing)
------------------------------------
  Ctrl+Alt+Y        Show / hide the player
  Ctrl+Alt+S        Maximize over the game / back to your size
  Ctrl+Alt+L        Lock / unlock
  Ctrl+Alt+P        Play / pause
  Ctrl+Alt+Up/Down  Volume
  Ctrl+Alt+Q        Mute / unmute
  Ctrl+Alt+F        Video full screen, on and off

Every hotkey can be changed or turned off. Open Settings from the
menu button on the player, or right-click the tray icon. Click a
hotkey's box and press the new keys, then Save.

Your keyboard's own media keys work too: If it has a play and pause
key, that key pauses and plays the video while you are in the game.


THE PLAYER
----------
The bar along the top:

  Menu (three lines)  Back, Open copied link, Lock, Reset size,
                      hide the bar or border, Settings, What's new,
                      Quit WowTube.
  Anywhere on the bar Drag to move the player.
  Four corners        Full screen: Fill the player with the video
                      alone. It turns into a bent arrow, which
                      brings the YouTube page back.
  Thumbs-up           Like the video. It shows while the video
                      fills the player.
  Phone or screen     Swap between a wide player for regular videos
                      and a tall one for YouTube Shorts. Each keeps
                      its own size and place.
  Square              Maximize: Fill the game with the video.
                      Click again to go back to the size you had.
                      Double-clicking the bar does the same.
  X                   Close the video. Ctrl+Alt+Y brings it back.

* To resize, drag the small gold corner at the bottom right, or an
  edge of the thin gold border (you do not need to hit the line
  exactly). The border and (if you choose) the bar hide when
  your pointer is away, and return when it comes back.
* For video full screen at any size, click the four-corners button,
  press Ctrl+Alt+F or choose "Video full screen" in the menu: It
  fills the player, not your monitor. The same button, key or menu
  line leaves it. The F key and Esc cannot do it, because your
  keyboard stays with the game.
* While maximized, the bar hides. Move your pointer to the very top
  of the screen to bring it back. Esc returns the player to the size
  it had. (While maximized the game does not receive Esc.)
* Lock fixes the player in place and lets your clicks pass through
  the video to the game. Unlock from the menu or with Ctrl+Alt+L.
* To open a link you copied somewhere else, choose "Open copied link"
  in the menu. Or just search inside YouTube.

Clicking the video pauses and plays it without taking your keyboard
away from the game. To type (search, sign in), click a text box. Your
keyboard goes back to the game when you press Enter or Esc, or click
elsewhere.


GOOD TO KNOW
------------
* The player hides when you minimize the game, or when another
  program is in front of the game on the same monitor. The video
  keeps playing, so you still hear it. To have it pause instead,
  tick "Pause the video when you switch away from the game" in
  Settings.
* It stays put when you click onto a second monitor.
* YouTube's ads play as normal unless you are signed in with Premium.
* Right-click the tray icon for Settings, Reset size, Help,
  What's new, About, and Quit. Help has all of this in one window.


SENDING FEEDBACK
----------------
Tell whoever sent you this (they may have shared a feedback form), or
open an issue at:
  https://github.com/petey85/WowTube/issues

Useful things to say: What you were doing, what you expected, what
happened, and whether you use one monitor or more.

If something goes wrong, the log helps. WowTube keeps it on your own
PC and never sends it anywhere. Press Win+R, paste
  %AppData%\WowTube\logs
press Enter, and send the file wowtube.log. It records what the app
did, not which videos you watched.


REMOVING IT
-----------
1. Right-click the tray icon and choose Settings. If "Start with
   Windows" is ticked, untick it and press Save.
2. Choose Quit.
3. Delete WowTube.exe.
4. Optional: Delete the folder %AppData%\WowTube (press Win+R, paste
   that, press Enter). It holds your settings and YouTube sign-in.


OWNERSHIP
---------
WowTube is copyright (c) 2026 Adam Peterson (Petey85). All rights
reserved. You may run the official builds for your own use. You may
not copy, modify or redistribute the app or its source code without
permission. The third-party software it includes is listed in
THIRD-PARTY-NOTICES.txt.


UPDATING
--------
WowTube tells you when a newer version is out: A notice near the clock
when you are out of the game, and a "New Version ... available" item in
the tray menu. Click either to open the download page. It only asks
GitHub which version is newest and sends nothing about you. The check
is always on.

Quit WowTube from the tray, download the new zip from
  https://github.com/petey85/WowTube/releases
and replace WowTube.exe. Your settings and sign-in are kept.
