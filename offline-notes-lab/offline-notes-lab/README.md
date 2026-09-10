# Offline Notes Lab

Abdurrasheed Abdurrahman Ola
Mechatronics Engineering
2024/1/98188ET

## Run locally
```
npm install
npm run dev
```

## Verify the build
```
npm run check
npm run build
npm run preview
```

## PWA test
Open the preview, install or inspect the manifest, switch Network to Offline, reload, and create a note.

## Node.js version used
20.x LTS

## Deployed application URL
_(add the live URL here after deployment)_

## Offline test performed
1. Opened the production preview and reloaded once while online.
2. Opened DevTools → Network and set to Offline.
3. Reloaded the page — the app shell still loaded from cache.
4. Created a note, then refreshed again — the note remained (stored in localStorage).
5. Confirmed the entry in DevTools → Application → Cache Storage.
