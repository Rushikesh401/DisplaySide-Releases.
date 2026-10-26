# DisplaySlide

A small macOS menu bar app for an everyday annoyance: rearranging your displays whenever you move your MacBook.

Change where your external monitor sits relative to your MacBook with a keyboard shortcut or a few clicks in the menu bar.

## Download

Get the latest DMG from this repository’s **[Releases](../../releases)** page.

This repository hosts public downloads and release notes. The app’s source code is maintained privately.

## Features

- Position your external monitor above, below, left, or right of your MacBook.
- Switch arrangements with customisable keyboard shortcuts.
- Preview your current display arrangement.
- Undo the last arrangement change.
- Optionally launch at login.
- Works offline.

## Requirements

- macOS 14 Sonoma or later.
- A MacBook with Apple silicon.
- The MacBook’s built-in display active.
- One external monitor in extended mode.

Mirrored displays, closed-lid setups, and multiple external monitors are currently unsupported.

## Installation

1. Download the `.dmg` file from the latest release.
2. Open the DMG.
3. Drag DisplaySlide into **Applications**.
4. Launch DisplaySlide from Applications.
5. Click its icon in the menu bar to access the controls.

## Keyboard Shortcuts

| Arrangement | Default shortcut |
| --- | --- |
| Above MacBook | Control + Option + ↑ |
| Below MacBook | Control + Option + ↓ |
| Left of MacBook | Control + Option + ← |
| Right of MacBook | Control + Option + → |

To customise or disable shortcuts, open the menu bar controls, click the gear icon, and choose **Keyboard Shortcuts**.

## Launch at Login

Open **Settings → General → Launch at login** to enable automatic launch.

Enable this from the copy installed in Applications. If macOS requests approval, follow the app’s link to Login Items settings.

## Things to Know

- Arrangement changes preserve your main display, resolution, scaling, rotation, and refresh rate.
- Quitting the app leaves the current arrangement in place for the login session.
- Saved layouts and automatic restoration after reconnecting or logging in are not included.
- Undo restores only the previous arrangement and is cleared when the app restarts or the display setup changes.

## Feedback

Found a problem or have a suggestion? Open an issue in this repository. Include your macOS version, MacBook model, monitor setup, and what happened.
