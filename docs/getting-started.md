# Getting Started

## Download
- Go to the [GitHub Releases page](https://github.com/bunnysayzz/utilix/releases) and download the latest `.dmg`
  (one Universal build for Apple Silicon and Intel), or visit
  [itch.io](https://bunnysayzz.itch.io/utilix).
- Each release also attaches an **Install Guide PDF** — the illustrated
  version of the steps below.

## Install
See the full walkthrough: [`install.md`](install.md). Short version:
1. Open the `.dmg` and drag Utilix to `Applications` (never run it from the disk image).
2. First launch is blocked by Gatekeeper: click Done, allow it in
   System Settings → Privacy & Security → Open Anyway, launch again,
   confirm, authenticate once.

## First Launch Checklist
- The command palette opens automatically (later: ⌘Space — disable
  Spotlight's shortcut first, the app guides you). The menu-bar icon opens
  the utilities dropdown.
- 22 utilities are already on; only Calendar stays opt-in. Desktop Switch
  needs explicit enabling (its row is always visible).
- Web AI works immediately, no key needed. API chat needs your provider key
  (Settings → AI Settings → Add key, stored in the keychain).
- Utilix registers launch-at-login on first install (Settings → General)
  and updates itself silently in the background.
- Open Settings → Permissions to see live grant status: Accessibility,
  Screen Recording, Calendars, Full Disk Access, Notifications — each is
  asked the first time its feature runs, never at launch. After granting
  Screen Recording, quit + reopen Utilix once before capturing.

## Updates
New versions published on the Releases page install themselves silently
in the background, verified by signature — no action, no account needed.
After each update, the palette shows a What's New banner once with the
highlights.

## Uninstall
- Quit Utilix from the menu bar
- Remove `Utilix.app` from `Applications`
- Optionally delete preferences in `~/Library/Preferences` and data in
  `~/Library/Application Support/Utilix`
