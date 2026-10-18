# Python Library — 30-Day Consistency Tracker

A lightweight installable web app for tracking one daily commitment. It starts on **19 October 2026** and ends on **17 November 2026**.

## Quickest way to put it on an Android home screen

The app needs an HTTPS website address for the best installable/offline experience. The easiest free option is GitHub Pages:

1. Sign in to GitHub and create a new **public** repository, for example `python-30-day-tracker`.
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` to the repository's root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. Open the URL it provides on your Android phone in Chrome.
6. In Chrome, tap **⋮ → Add to Home screen** (or **Install app**, if shown).

Once opened from the published HTTPS URL, the app can cache its files for offline use. Check-ins and notes are saved in that browser on that device. They are not automatically synced across devices, so use **Export backup** periodically.

## Tracker behavior

- 30 days: 19 Oct–17 Nov 2026.
- Tap each day to toggle completion.
- Tracks total completed days, completion percentage, remaining check-ins, and the current run of marked days.
- Saves the chosen library, next task, notes, and check-ins locally.
- Includes JSON export and a reset control.

If you want a different start date or want the tracker to be tailored to a specific Python library, edit `START` in `index.html` or fill in the library field in the app.
