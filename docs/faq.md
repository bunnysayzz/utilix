# FAQ

## Is Utilix open-source?
No. The app is closed‑source. This community repo hosts docs, releases, and issues only.

## Where is my data stored?
Locally on your Mac. Clipboard history, snippets, notes, and preferences are not sent to servers. The optional AI Chat sends only what you type to the provider you configured, using your own API key (stored in the macOS keychain, never in files).

## Does Utilix auto-update?
It checks in the background (toggle in Preferences → General) but never installs without asking. When an update is available, Check for Updates… in the menu (or Preferences → General) shows it with release notes; after installing, the palette shows a What's New banner once. Or download any version from GitHub Releases or [macbunny.co/utilix](https://macbunny.co/utilix).

## What permissions are required?
Accessibility (Desktop Switch, Window Snap, shortcuts, automation), Screen Recording (Mac Vision OCR, GIF recording). Calendars is optional (meeting join links); Full Disk Access is optional for file utilities. See `permissions.md`.

## How do I uninstall?
Quit Utilix, delete it from Applications, optionally remove preferences in `~/Library/Preferences`.

## Keyboard shortcut conflicts?
⌘Space needs Spotlight's shortcut disabled first (System Settings → Keyboard → Shortcuts → Spotlight) — the app shows a one-time guide. Disable or change other conflicting shortcuts in macOS, or toggle Utilix global shortcuts off in Preferences → Shortcuts. 