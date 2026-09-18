# Troubleshooting

## Install blocked ("Not Opened" / "Open Anyway")
Follow [`install.md`](install.md) steps 2–3 with screenshots: Done (not
Move to Bin) → Privacy & Security → Open Anyway → launch → confirm →
Touch ID/password. One time only.

## Permissions appear enabled but features don’t work
- Toggle the permission OFF and ON again in System Settings
- Quit and relaunch Utilix (required after a Screen Recording grant — the
  OS attaches it to the next process)
- Re-check from Preferences → Permissions (live status + deep links)

## Mac Vision OCR captures blank text
- Ensure Screen Recording permission is enabled for Utilix, then relaunch
- Try capturing a larger region with clear text
- Non-English text: turn on **All languages** in the Mac Vision pane
- Increase screen brightness or zoom in

## Desktop Switch edges don’t show or don’t switch
- Enable it explicitly (row is always visible; panels need the toggle)
- Check Accessibility permission (first edge-click asks once)
- Needs the Ctrl–←/→ Mission Control shortcuts enabled
  (System Settings → Keyboard → Shortcuts)
- On multiple monitors, each display gets its own edges

## App doesn’t launch
- Right‑click Utilix in Applications → Open (to pass Gatekeeper once)
- Re-download latest dmg from Releases
- Check Console logs for messages filtered by “Utilix”
- Attach `~/Library/Logs/Utilix/app.log` (launch → login-item → update lines)

## Still stuck?
Open an issue using the Bug Report template and include macOS version, chip type, Utilix version, and steps to reproduce. From inside the app, the bug icon files a report with diagnostics attached.
