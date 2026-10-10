PONDO VERSION 8 — WEEKLY BUDGET TRACKER

Files: index.html, service-worker.js, manifest.webmanifest, icons/.

Install/update: upload the contents of pondo_pwa/ to the repository root on the main branch. Do not delete the existing local website data or uninstall the installed PWA. The app preserves the existing localStorage key pondo-weekly-budget-v1 and migrates Version 7 records on first load.

Version 8 features: Sunday-Saturday budget weeks; new allowance prompt when a new Sunday is detected; archived week records; hamburger menu without letter labels; manual savings entries (no automatic transfer); calendar List/Grid; full expense history; CSV export for expenses and savings; reset archives the active week rather than deleting history; date-not-set legacy records remain undated until manually assigned.

Important: records remain local to each browser/device. CSV export is recommended before updating. Test using a backup/export before publishing.
