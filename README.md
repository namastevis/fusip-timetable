# Event timetable

A one-page, mobile-friendly timetable for a multi-day event, with
separate tracks for two batches. Open it on a phone and it shows
what's on today; one tap shares it on WhatsApp.

Live: https://namastevis.github.io/fusip-timetable/

## What it was for
Built for the FLAME University Summer Immersion Program (FUSIP) 2026,
29 June – 8 July 2026, so students and facilitators could check the
day's sessions, venues and meal times on their phones.

## Reuse it for your event
1. Click **Use this template** (or fork the repo).
2. Open `index.html` and find the block marked `SCHEDULE DATA`.
3. Change the batch names (`b1`, `b2`), then each day's date, venue
   and slots. Each slot has a start and end time (`s`, `e`), a label,
   and optionally a facilitator (`fac`). Sessions that differ by
   batch use separate `b1` and `b2` entries.
4. Change the title, the header text and the WhatsApp share message
   (search for `wa.me`).
5. In **Settings → Pages**, publish from the `main` branch. Your
   timetable is live.

## How it works
One HTML file: no build step, no server, no database. Hosted free on
GitHub Pages.

## Licence
MIT: use it, change it, share it.
