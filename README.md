# Bird Farm Manager V2 — Update package

A mobile-first, installable PWA for managing a bird farm. The interface supports Arabic (RTL) and English (LTR).

## Included features
- Dashboard, farm tasks, monthly calendar, goals and progress tracking.
- Bird profiles with editable band/ring number, sex, birth/hatch date, status, source, notes, and event timeline.
- Pair registration with male/female selection and pair status.
- Nest records linked to pairs.
- Egg records with fertility/condition status, laying date, expected hatch date, and notes.
- Register a chick from a hatched egg and link it to its parents, pair, nest, and egg.
- Search birds, band numbers, pairs, nests, and eggs.
- Food entries, seed mixes, lighting schedules, JSON backup and restore.
- Existing local data is retained when the updated app opens in the same browser profile.

## Update / publish
Replace the repository's app files with the files in this package, keeping the same root-level layout. Cloudflare Pages should deploy the commit automatically. The Service Worker cache version has been increased so installed clients can receive the new version.

## Important limitations
- Data is stored locally in the browser on this device. There is no cross-device cloud sync.
- Scheduled Android notifications are not implemented.
- Export a JSON backup regularly and before changing phones or clearing browser data.
- The app has not been connected to a hosted database or user accounts.
