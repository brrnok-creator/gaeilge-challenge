# Gaeilge — An Dúshlán

A lightweight installable Progressive Web App (PWA) for practising Irish noun forms.

## Features
- Randomly asks for plural, genitive singular, or genitive plural
- Randomly specifies whether the definite article is required
- Strict answer checking: ignores case and extra spaces, but requires correct spelling, fadas, and article
- Streak ends on a wrong answer; restart immediately
- Best streak and correct-today counters saved locally
- Offline shell caching after the first successful load
- Responsive Android-friendly layout

## Run locally
A PWA service worker requires localhost or HTTPS. From this folder run:

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in a browser.

## Install on Android
1. Host this folder on an HTTPS static host (for example GitHub Pages, Netlify, or Cloudflare Pages).
2. Open the HTTPS URL in Chrome on Android.
3. Open Chrome's menu and choose **Install app** or **Add to Home screen**.
4. Launch Gaeilge from the home screen.

## Important language-data note
This is a starter deck, not a claim that every form has been independently verified against a single authoritative dictionary. Irish genitive and plural forms can vary by dialect, meaning, and declension; several entries need editorial review before using this as a formal assessment tool. The game uses strict exact-answer matching, so review the data before public release. See Teanglann (https://www.teanglann.ie/en/) and the National Corpus of Irish (https://www.corpas.ie/) when validating entries.
