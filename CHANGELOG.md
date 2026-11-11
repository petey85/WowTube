# WowTube changelog

## 0.2.8 (2026-11-11)

- New like button on the bar, beside the menu button, in the video-only view. That view hides YouTube's own like button, so the bar now carries one: A click presses YouTube's button for the video on show, on Shorts and on regular videos. It is filled in gold on a video you already like, and a second click takes the like back. When the YouTube page is on show the button is not on the bar, since YouTube's own is there. To keep it on the bar all the time, tick "Always show the like button on the bar" in the menu.
- New full screen button on the bar, beside the menu button. One click fills the player with the video, and one click on it brings the YouTube page back, so you no longer need the menu to leave a full-screen Short. To have it on the bar only while the video fills the player, untick "Show the full screen button on the bar" in the menu.
- When you bring the page back on a Short, the next Shorts stay on the page too, until you choose the full-screen view again.
- The bottom edge of the border is now a progress bar: A dim track runs the whole edge and a bright line fills it as the video plays. It is drawn on the border, so nothing covers the video.
- When you change the volume or mute, a line up the right edge shows the level for about two seconds, then goes away.
- With "hide the border" turned on, the progress bar stays on show by itself and the rest of the border still hides.
- The bar shows the time beside the name, for example WowTube 0:17 / 0:45. On a narrow bar the time is shortened or left out, and the name always stays.
- To turn the progress bar, the volume line and the time off, untick "Show the video's progress and volume on the player's border" in Settings.
- YouTube's mini player, which appears when you search or browse while a video plays, is now drawn smaller in its corner, so it no longer covers most of a small player. Its controls work as before.
- A right-click in the player no longer opens a menu, neither YouTube's nor the browser's.
- The bar no longer shows the long "video full screen" text. It says WowTube and the time.
- Fixed: After a search in YouTube's search box, the list of suggestions could stay open over the results.
- The bar's title no longer wraps onto two lines on a narrow player.

## 0.2.7 (2026-11-10)

- New button on the bar, left of maximize: It swaps the player between a wide shape for regular videos and a tall shape for YouTube Shorts.
- Each shape remembers its own size and place. Resize or move the tall player once, and it comes back that way every time you switch to it.
- The first time you switch, the tall player is exactly the shape of a Short, a little over a third of the height of the game, and stands where the wide one stood.
- The player picks the shape by itself: It goes tall when you open a YouTube Short and wide again when you leave Shorts. If you pick a shape by hand, it leaves your choice alone. To turn this off, untick "Automatically switch to the tall shape for YouTube Shorts" in Settings.
- A Short opens in the video-only view by itself, a few seconds after it appears: You see the Short alone, filling the player, with none of the YouTube page around it. Roll the mouse wheel over it to go to the next Short or back to the last one. The page, with its like and comment buttons, comes back when you press Ctrl+Alt+F or leave Shorts. To turn this off, untick "Automatically show Shorts in the video-only view" in Settings.
- Shorts now play one after another: When a Short ends, the next one starts by itself. This carries on while the player is hidden. To have a Short replay until you scroll, as YouTube normally does, untick "Automatically play the next Short when one ends" in Settings.
- The same switch is in the player menu as "Shorts shape (tall player)", with a tick when it is on.
- "Reset size" now resets only the shape on show.
- Settings is arranged under headings: Hotkeys, Player, YouTube Shorts, When you are away from the game, and WowTube.

## 0.2.6 (2026-11-10)

- New hotkey: Ctrl+Alt+Q mutes and unmutes the video, without changing the volume level. You can change the key in Settings.
- Resting your pointer on a button in the bar now shows what it does, with its hotkey.
- If another program already uses one of WowTube's hotkeys, a notice at start now names the hotkey, so you can pick a different one in Settings.
- In the player menu, "Hide video" is now "Hide WowTube", and it shows the hotkey that brings the player back.
- The About window no longer has the line of small print above the Close button, and Close sits on the right with more space above it.
- Help has a new Settings section: How to open it, how to change or turn off a hotkey, and what each choice does.
- Help, the first-steps text and the README now say that your keyboard's own play and pause key works on the video while you are in the game.
- Wording tidied throughout: The first word after a colon is capitalized.

## 0.2.5 (2026-11-09)

Playing while you are away

- The video keeps playing when you switch away from the game (Alt+Tab, or minimizing it). The player still hides, and you keep the sound. To get the old behavior back, tick "Pause the video when you switch away from the game" in Settings.
- When you hide the player yourself and show it again, the video carries on playing if it was playing before. This covers the Ctrl+Alt+Y hotkey, the X on the bar, "Hide video" in the menu and a click on the tray icon.
- Fixed: The video could keep playing with no player on screen if you turned it off from the tray while another program was in front.

Video full screen (the view with only the video and no YouTube page around it)

- New hotkey: Ctrl+Alt+F turns the video-only view on and off. You can change the key in Settings.
- New line in the player menu: "Video full screen", with a tick when it is on.
- The F key on its own cannot do this while you play, because your keyboard stays with the game. The hotkey and the menu line are the way in.
- The app remembers the view. If you quit with the video-only view on, it goes back into it the next time it starts, without you clicking anything.
- The player keeps its size when the view changes. Only what is inside it changes.

Double-clicking the video

- The setting "Maximize the player when a video goes full screen" has been renamed "Double-clicking the video maximizes the player", because that is now exactly what it does.
- With the setting ticked: A double-click on the video makes the player fill the whole game. Another double-click puts it back to the size it had. The video stays in its video-only view both times, so you never drop back to the YouTube page by accident.
- Before this version, with the same setting ticked, the first double-click could take the video out of its video-only view without changing the player's size, the second filled the game, and the third went back to the small player showing the page. That three-step cycle is gone.
- With the setting unticked, nothing changes: A double-click turns YouTube's video-only view on and off at the player's current size.
- Esc while the player fills the game still puts it back to its earlier size. With the setting ticked it now keeps the video-only view when it does.

New versions

- WowTube now tells you when a newer version is out. It asks GitHub when it starts and every 3 hours, and sends nothing about you.
- The notice appears only when you are out of the game (switched to another program, or the game closed), never while you are playing. It reads "New Version X available. Click here to download." Clicking it opens the download page.
- The tray icon blinks for half a minute and then keeps a dot until you update. "New Version X available" also appears in the tray menu and the player menu.
- The About window has a "Check for updates" button. The answer is green when you have the latest version. It is red and flashing when a newer one exists, and clicking it opens the download page.
- Nothing is downloaded or installed for you. You can turn the check off in Settings.

Other changes

- The player menu has two ways out: "Hide video" and "Quit WowTube".
- The Donate button is now called "Buy me a Coffee".
- The owner is shown as Adam Peterson (Petey85), and the About window has a contact address for requests and business inquiries.

## 0.2.4 (2026-11-09)

- About window, from the tray icon and the menu button: What WowTube is, its version, and the ownership notice.
- Help window with the hotkeys, the bar, moving and resizing, Lock, and tips.
- Buttons for the GitHub page and for donating. Both open in your web browser.
- A list of the third-party software included in the app, with its licenses.

## 0.2.3 (2026-11-09)

- While the player is maximized, Esc brings it back to the size it had, and leaves YouTube's full-screen view at the same time. A maximized player covers the whole game, so the game does not receive Esc until the player is back to normal size. At normal size, Esc still goes to the game as before.

## 0.2.2 (2026-11-09)

- The border is now a single-pixel line, the same weight as the bar's outline, and lines up exactly with the bar's edges.
- Resizing is easier: The edges respond a few pixels either side of the line, though only the line is visible. The gold corner still works.
- New setting, off by default: "Maximize the player when a video goes full screen". With it on, YouTube's full-screen view (double-click the video, or its button) also fills the game, and leaving that view puts the player back.

## 0.2.1 (2026-11-09)

- The border now fades in and out, like the bar.
- Double-click the top bar to maximize, and again to go back, as on a Windows title bar.
- "Open copied link" in the ≡ menu is grayed out unless a YouTube link is copied.
- While a video is in YouTube's full-screen view, the bar says how to leave it (double-click the video) and the ≡ menu has "Exit video full screen". Esc cannot do it, because your keyboard stays with the game.

## 0.2.0 (2026-11-09)

Shaped by the first tester feedback.

- One player instead of two sizes. The mini size and the Size button are gone. The player opens showing the full YouTube site at half the game's width, and you resize it by dragging its border.
- Maximize button (next to ✕): One click fills the game with the video. Click again to return to the size you had. Ctrl+Alt+S does the same. While maximized, the bar hides until your pointer reaches the top of the screen.
- For a video-only view at any size, use YouTube's own full-screen button: It fills the frame, not your monitor.
- The gold border is now a thin line, and it hides when your pointer is away, leaving just the video. Turn the hiding off in Settings if you prefer the border always showing. A small gold corner at the bottom right is the easy place to grab for resizing.
- The ≡ button opens a menu holding Back, Open copied link, Reset size, Lock, Hide bar, Hide border, Settings and What's new.
- Drag the frame by any part of the top bar.
- The address box is gone: Search and paste links in YouTube itself. "Open copied link" in the ≡ menu opens a YouTube link you have copied.
- What's new: This window, from the tray icon or the ≡ menu.
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
