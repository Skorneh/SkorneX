# Changelog

What changed in each SkorneX version. Updates shows the installed version and
the newest one; each version is also a release on GitHub.

## 0.5.6
- New Startup apps settings: choose which apps start when you log in, like
  Task Manager's Startup tab. Apps' own "start when I log in" options (Discord,
  Steam) now work too.
- Search can be clicked again after closing it by clicking a full-screen game
  or anywhere else; before, it stopped responding until the taskbar restarted.
- Updating no longer stops with "stowing files would cause conflicts".

## 0.5.5
- Settings has a search box (Ctrl+F) that finds any setting, like "push to
  talk" or "refresh rate", and jumps to it.
- Sound: push to talk that works in games and every app (hold Caps Lock or a
  key you pick; the mic stays muted otherwise). Off unless you turn it on.
- Sound: "Only use this microphone" turns the others off, so apps wait for
  your mic when it's unplugged instead of switching to the webcam's.
- Sound: turning the microphone cap on or off no longer cuts the sound in
  TeamSpeak, Discord and other apps.
- Region screenshots freeze the screen first, so menus stay in the shot.
- Taskbar: search can always be clicked; right-click menus on apps open every
  time, also with search open; the Windows key closes an open menu.
- The PC no longer lands on the text login when the NVIDIA driver is slow to
  load, and the saved screen layout applies even if a monitor is late.

## 0.5.4
- The Windows key shows the whole taskbar along with search over full-screen
  games and videos, like Windows.
- Date & time: search for your time zone by city or UTC offset instead of
  scrolling through hundreds of them.

## 0.5.3
- Dragging taskbar icons to reorder them follows the mouse; before, you had
  to drag far past where you wanted them.
- Alt+Print Screen copies the active window again instead of asking you to
  drag a box, without the black strips some apps added along the edges.

## 0.5.2
- Identify in Display settings shows each monitor's number on it.
- Double-clicking a program or installer you downloaded (.run, .sh,
  .AppImage) asks, then runs it in Terminal.

## 0.5.1
- Alt+Print Screen copies the window you're using, like Windows.
- Display settings keep the monitor layout you arrange when you press Apply.

## 0.5.0
- Setup asks which web browser you want: LibreWolf (recommended), Firefox,
  Helium or none. Firefox is no longer part of the base install; updating
  leaves the browser you have alone.

## 0.4.0
- New settings modules: Date & time (time zone, automatic time, 12- or
  24-hour clock), Default apps, and Account (change your password).
- Night light in Display settings.
- VLC for videos and music; zip files in Files (Extract here, Compress).
- Pictures open in Paint.
- A firewall (ufw) blocks incoming connections; everything going out works
  as before. SSH stays reachable where it's set up.

## 0.3.3
- The README shows each tool in action: search, the taskbar panels, Run, the
  desktop, Task Manager, Paint, Snipping Tool and Settings.

## 0.3.2
- The project is now called SkorneX on GitHub too: github.com/Skorneh/SkorneX.

## 0.3.1
- Power settings on laptops: separate lock, screen off and sleep times, and
  lid action, for plugged in and on battery. It switches by itself when you
  plug in or unplug.

## 0.3.0
- Power settings module: lock, screen off and sleep times, lock on sleep,
  the power button and (on laptops) the lid.
- Icons in the desktop right-click menu.

## 0.2.10
- Each version is published as a release on GitHub, with these notes.

## 0.2.9
- Desktop: drag a box to select several icons, Ctrl+click to add or remove one,
  and drag them all together.
- Drop files onto the Recycle Bin to delete them. The Recycle Bin itself only
  ever moves.

## 0.2.8
- Your changes are kept: SkorneX's defaults (theme, Notepad's look, default
  apps, Files' sidebar) are applied once, so whatever you change stays.
- Taskbar pins are your own file; updates never touch them.
- Updating sets your own edits to SkorneX's files aside and puts them back.
- `~/.bashrc.local` and `~/.config/kitty/local.conf` for your own settings.

## 0.2.7
- Files: Documents, Downloads, Pictures, Music and Videos under My Computer,
  set up at login.
- Public, Templates and Projects folders are skipped.

## 0.2.6
- Win+R opens folders in your home folder without typing `~/`.

## 0.2.5
- Snipping Tool (search "Snipping Tool"): rectangle or full screen, a delay,
  then Save, Copy or Edit in Paint.
- Windows without an icon show a plain app icon instead of labwc's logo.

## 0.2.4
- Folders open in Files; Win+R ignores capital letters in paths.
- Documents, Downloads, Music, Pictures and Videos are created.

## 0.2.3
- Win+R opens apps by name, folders and websites.
- Win+V clicks and scrolling work; the volume pop-up keeps its size.

## 0.2.2
- Desktop right-click: New folder, New text document, Settings; Rename for files.
- Win+V shows every item.

## 0.2.1
- Battery icon on laptops.
- Win+V opens on the right and starts recording right after an update.

## 0.2.0
- Win+V clipboard history.
- Update SkorneX no longer updates your other apps.

## 0.1.5
- Ctrl+W closes Settings, the settings modules, Paint and Task Manager.

## 0.1.4
- Updates knows what's actually installed.
- The sound icon keeps its size when muted.
- Microphone cap goes down to -40 dB.

## 0.1.3
- Notepad comes to the front right away; volume pop-up above the sound icon.
- Display settings apply as soon as you change them; draggable microphone cap.

## 0.1.2
- Display: drag monitors into place; pick the main display.
- Alt+Tab shows on one screen.

## 0.1.1
- Mouse acceleration off by default.
- Notepad comes to the front when you open a file that's already open.

## 0.1.0
- First version with a version number.
