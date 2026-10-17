# We'll Keep Looking: a Shazam concept

A clickable iPhone prototype from my Shazam product teardown.

**Problem:** when Shazam can't find a song, the user hits a dead end. "No Result", one button (Try Again), and nothing is saved, so the song is lost.
**Concept:** *We'll Keep Looking.* Shazam keeps the sound thumbprint (codes, never audio), checks it again every day for 30 days as new music joins the library, and sends one notification when it finds the song. The miss screen also offers a lyrics search right away.
**North Star:** songs caught per week. Key input: rescue rate, the share of misses that end in the right song within 30 days.

## What's inside
- `index.html`: the phone on its own. Tap anything. "Skip 3 days" shows a missed song being found; "Start over" resets.
- `walkthrough.html`: the same phone with an 8-step guide comparing today's app with the concept at each step.

Both pages are self-contained, with no build step. Unchanged screens (Home, Listening, Expanding search, No Result, the Library ••• menu) are recreated from the real app on an iPhone 16, Oct 2026.

## Run locally
Open `index.html` in a browser.

## Deploy
On Vercel: Add New → Project → import this repo → Framework preset "Other", no build command → Deploy.

---
Concept work for a product teardown by Pritesh Kabra. Not affiliated with Apple or Shazam. Songs and artists are invented.
