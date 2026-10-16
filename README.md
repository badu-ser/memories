# Our Memory Book ♡

A cute, responsive, pastel-kawaii scrapbook starter website.

## Run locally
Open `index.html` in a browser, or deploy this folder as a static site to Vercel.

## Current features
- Home dashboard
- Add photo/moment/note memories
- Love letters
- Timeline
- Export and restore JSON backup
- Mobile-friendly layout and PWA manifest

## Important limitation
This first version stores content in the current browser using `localStorage`. That means memories are **not shared between your phone and Akshaya's phone**, and uploaded photos are stored in that browser only. Do not use this as the only copy of important memories.

For a real shared private website, the next step is to connect authentication + a cloud database and photo storage (for example, Supabase or Firebase Storage/Firestore, or your OCI PostgreSQL backend). Add access controls so only both of you can read and write the shared book.
