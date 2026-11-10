# WowTube changelog

## 0.2.4 (2026-11-09)

- About window, from the tray icon and the menu button: what WowTube is, its version, and the ownership notice.
- Help window with the hotkeys, the bar, moving and resizing, Lock, and tips.
- Buttons for the GitHub page and for donating. Both open in your web browser.
- A list of the third-party software included in the app, with its licenses.

## 0.2.3 (2026-11-09)

- While the player is maximized, Esc brings it back to the size it had, and leaves YouTube's full-screen view at the same time. A maximized player covers the whole game, so the game does not receive Esc until the player is back to normal size. At normal size, Esc still goes to the game as before.

## 0.2.2 (2026-11-09)

- The border is now a single-pixel line, the same weight as the bar's outline, and lines up exactly with the bar's edges.
- Resizing is easier: the edges respond a few pixels either side of the line, though only the line is visible. The gold corner still works.
- New setting, off by default: "Maximize the player when a video goes full screen". With it on, YouTube's full-screen view (double-click the video, or its button) also fills the game, and leaving that view puts the player back.

## 0.2.1 (2026-11-09)

- The border now fades in and out, like the bar.
- Double-click the top bar to maximize, and again to go back, as on a Windows title bar.
- "Open copied link" in the ≡ menu is greyed out unless a YouTube link is copied.
- While a video is in YouTube's full-screen view, the bar says how to leave it (double-click the video) and the ≡ menu has "Exit video full screen". Esc cannot do it, because your keyboard stays with the game.

## 0.2.0 (2026-11-09)

Shaped by the first tester feedback.

- One player instead of two sizes. The mini size and the Size button are gone. The player opens showing the full YouTube site at half the game's width, and you resize it by dragging its border.
- Maximize button (next to ✕): one click fills the game with the video. Click again to return to the size you had. Ctrl+Alt+S does the same. While maximized, the bar hides until your pointer reaches the top of the screen.
- For a video-only view at any size, use YouTube's own full-screen button: it fills the frame, not your monitor.
- The gold border is now a thin line, and it hides when your pointer is away, leaving just the video. Turn the hiding off in Settings if you prefer the border always showing. A small gold corner at the bottom right is the easy place to grab for resizing.
- The ≡ button opens a menu holding Back, Open copied link, Reset size, Lock, Hide bar, Hide border, Settings and What's new.
- Drag the frame by any part of the top bar.
- The address box is gone: search and paste links in YouTube itself. "Open copied link" in the ≡ menu opens a YouTube link you have copied.
- What's new: this window, from the tray icon or the ≡ menu.
- Your old large size and position carry over from 0.1.x.

## 0.1.3 (2026-11-09)

First build shared with testers.

- Opacity sliders in Settings.
- Version number shown in the tray menu.
- The log no longer records which videos are watched.
- Clearer message if Microsoft's WebView2 Runtime is missing.

## 0.1.2 (2026-11-09)

- Lock now also fixes the frame in place.
- The bar fades in and out when set to hide.
- "Slim" renamed "Hide bar".

## 0.1.1 (2026-11-09)

- Fixed the settings window being cut off and hiding behind the video.
- The frame stays inside the game window.
- Hide became Close (✕). Added the option to hide the bar.

## 0.1.0 (2026-11-09)

First build of the real app.

- Lives in the system tray. Stays hidden when the game is launched until you ask for it.
- Click, scroll, move and resize without taking the keyboard from the game.
- Lock, Reset, rebindable hotkeys, start with Windows.
