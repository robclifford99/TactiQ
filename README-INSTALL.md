# MatchTracker — installable iPhone + Windows app

This folder is ready to publish as a Progressive Web App (PWA).

## What is already included
- `index.html` — the app
- `manifest.json` — makes it installable
- `sw.js` — offline caching/service worker

## Easiest way to make it an iPhone app
1. Put these files on a web host using HTTPS.
2. Open the site in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Launch MatchTracker from the Home Screen.

## Windows 11
Open the HTTPS site in Microsoft Edge or Chrome.
Use the browser's Install App / Install MatchTracker option.

## GitHub Pages
Create a GitHub repository and upload all files in this folder to the repository root.
Then enable Settings → Pages → Deploy from branch → `main` / root.
Open the generated HTTPS address on your phone.

## Important
The app currently stores match data locally in the browser/device. It does not automatically synchronize between iPhone and Windows.


## Analytics
The app now includes an Analytics tab with:
- score and match KPI cards
- shots on/off target
- pass completion breakdown
- tackles/interceptions
- goals/key passes
- player contribution chart
- pitch action-density heatmap


## Enhanced features
- Independent Home/Away possession timer
- Live possession percentages
- Custom statistics with per-statistic pitch-location ON/OFF
- Point events and start/end pass events
- Clean professional pitch styling with pass arrows
- Custom Home/Away/primary/accent colours
- Home and Away club crest uploads
- Branding and possession settings persist in browser storage
- Buttons use text labels without emoji icons


## Consistency and branding
- Match setup team names are the single source of truth across Setup, Live Match, Pitch, Analytics, Players, dashboard and reports.
- Lineup/player changes are saved to the same match state used by event and pitch selectors.
- Possession has independent Home/Away timers; only one side can run at a time, with pause and reset.
- Club crest images and Home/Away/Accent colours are saved locally and reflected across the dashboard/report.
- The interactive pitch has professional field markings, penalty areas, goals, centre circle and clearer event markers.
- Visible UI buttons contain text only; emoji icons have been removed.
