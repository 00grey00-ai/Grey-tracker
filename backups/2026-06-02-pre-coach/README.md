# Backup — 2026-06-02, pre-coach

Snapshot of Grey Tracker taken right before building the progression "coach" feature.

**State captured:** weight chart, gist sync (merge-based), local Save-to-Files backup + age
indicator, bike cardio with distance/RPM + History-tab progress modal (last 30 entries), edit
history entries (pencil), completed-day green-check + weekly lock cycle, missed-day red-X logged
to History, service-worker auto-update.

Corresponds to git tag `pre-coach-2026-06-02`.

## How to restore
Copy `index.html` and `sw.js` from this folder back to the repo root, bump the `CACHE` version
string in `sw.js`, commit, and push. Or `git checkout pre-coach-2026-06-02 -- index.html sw.js`.
