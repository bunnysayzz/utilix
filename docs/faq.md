# FAQ

## Is Utilix open-source?
No. The app is closed‑source. This community repo hosts docs, releases, and issues only.

## Where is my data stored?
Locally on your Mac (`~/Library/Application Support/Utilix`). Clipboard history, snippets, notes, and preferences are not sent to servers. The optional API Chat sends only what you type to the provider you configured, using your own API key (stored in the macOS keychain, never in files). Web AI loads provider websites you visit — like using them in a browser.

## Does Utilix auto-update?
Yes — silently. New versions download, verify by signature, install, and relaunch on their own. After each update, the palette shows a What's New banner once. Or download any version from GitHub Releases or [itch.io](https://bunnysayzz.itch.io/utilix).

## What permissions are required?
None at launch. Accessibility (snap, snippets, shortcuts, automation) and Screen Recording (OCR, GIF) are asked on first use; Calendars on first calendar open; Notifications on first delivery; Full Disk Access must be flipped manually (macOS offers no prompt). See `permissions.md`.

## Which utilities are on by default?
Everything except Calendar (opt-in so macOS never prompts uninvited) — clipboard, snippets, OCR, AI chat, shortcuts, and the rest. Desktop Switch shows its row but needs explicit enabling.

## How do I uninstall?
Quit Utilix, delete it from Applications, optionally remove preferences in `~/Library/Preferences` and data in `~/Library/Application Support/Utilix`.

## Keyboard shortcut conflicts?
⌘Space needs Spotlight's shortcut disabled first (System Settings → Keyboard → Shortcuts → Spotlight), the app shows a one-time guide. Utilix hotkeys (⌥X, ⌥T, ⌃⌥ set) are on by default; conflicting apps (Rectangle-style) degrade per-key, shown in Settings → Shortcuts. Disable any set there.
