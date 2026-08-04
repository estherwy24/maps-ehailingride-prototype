# Booking a ride without leaving Maps — clickable prototype

An eight-screen concept prototype: a newly arrived traveller books an e-hailing ride from inside Google Maps, then lands in a paid local discovery feed.

Single file, no build step, no dependencies except an icon webfont loaded from a CDN.

## Publish it (GitHub Pages)

1. Create a new **public** repo on your personal account, e.g. `maps-ride-prototype`.
2. Upload `index.html` and this `README.md` to the root of the `main` branch. (Drag-and-drop works: **Add file → Upload files**.)
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, folder `/ (root)`. Save.
4. Wait about a minute. Your link is:

   `https://<your-username>.github.io/maps-ride-prototype/`

Anyone with the link can open it. No sign-in, works on mobile.

## Deep links

Each screen has its own anchor, so you can send someone straight to the screen you want to discuss:

- `.../#s1` arrival detection
- `.../#s2` provider comparison
- `.../#s3` sign-up and identity check
- `.../#s4` booking confirmed
- `.../#s5` payment prompt
- `.../#s6` driver tracking
- `.../#s7` discovery upsell
- `.../#s8` billable events

## Notes

Concept prototype for discussion. Not affiliated with Google, Grab, Bolt or inDrive — brand names are placeholders illustrating a multi-provider surface. No real booking or payment functionality.
