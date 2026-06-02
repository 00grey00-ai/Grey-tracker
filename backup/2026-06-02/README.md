# Backup — 2026-06-02

Snapshot of the Grey Tracker app at a known-good, fully working state before further changes.

## What this version includes
- 4-tab app: Dashboard, Weight, Workout, History (photos removed)
- Merge-based GitHub Gist sync with tombstones (no data loss on flaky connections)
- Derived personal records (auto-corrects when workouts are edited/deleted)
- Workout delete from History
- Weight chart with time-scaled x-axis and 200 lb goal line
- Last-session reference under each exercise
- Local-timezone date handling
- Clear-on-save for workout forms
- Offline service worker (`sw.js`, cache `grey-tracker-v2`)
- iOS fixes: 16px inputs (no zoom), 44px done buttons, safe-area nav, wake lock

## Restore instructions
Copy `index.html` and `sw.js` from this folder back to the repo root, commit, and push.
This is a verified-working baseline — last commit before this backup parsed cleanly and passed full browser testing.
