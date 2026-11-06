# iPad StandBy Clock

A lightweight, self-contained clock page designed for older iPads, including iPad mini 2 / iOS 12.

## Features
- Large 24-hour digital clock
- Live weekday and date
- Black display with tap-to-toggle red night mode
- No external libraries, fonts, trackers, or network requests

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` deploys the site whenever a commit is pushed to `main`.

After the first successful deployment, the site should be available at:
https://trish1107.github.io/ipad-standby-clock/

## Add to iPad Home Screen
1. Open the published URL in Safari on the iPad.
2. Tap **Share → Add to Home Screen**.
3. Launch the new StandBy icon from the Home Screen.
4. For a desk-clock setup, use landscape orientation and set **Settings → General → Auto-Lock → Never** (if available).

The iPad must remain awake for the clock to stay visible. This is a web app, not Apple's native StandBy mode.
