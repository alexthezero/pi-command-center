# Pi Command Center

A custom Chromium start page for Alex's Raspberry Pi, hosted with GitHub Pages.

## Live dashboard

https://alexthezero.github.io/pi-command-center/

## Included

- Live clock, date, and Palm Coast weather
- Web search and address bar
- Shortcuts for ChatGPT, Gmail, GitHub, YouTube, CUPS, Home Assistant, Pi-hole, and the router
- Editable local-service addresses
- Browser connection and dashboard status
- Fullscreen mode
- Quick notes saved locally on the Raspberry Pi
- Responsive layout for desktop, touchscreen, and phone

## Open it automatically on Raspberry Pi OS

To launch the dashboard in fullscreen Chromium:

```bash
chromium --start-fullscreen https://alexthezero.github.io/pi-command-center/
```

On older Raspberry Pi OS releases, the command may be `chromium-browser` instead of `chromium`.

Dashboard settings and quick notes use browser storage, so they remain on the device and are not committed to this repository.
