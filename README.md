# Antonia: The Rise and Fall · Demo Hub

The demo hall and codex for **Antonia: The Rise and Fall (Book One)**, a mobile kingdom-building and siege strategy game by Thiink Media Graphics.

One place for every playable demo and every extra:

- **The Games:** a card library of mechanic demos (Siege of Lysa, Bastion, Vassal, Oath Stones, Shared Granaries, City of Five Ranks, The Open Road), each tagged with its status.
- **The Book of Providence:** the opening pages of the Book One story (the Note, Persephi's First Page and Pages I to III), with page turns, swipe and tabs. Later pages stay in the game.
- **The Character Deck:** a fanned deck that deals into a grid of seven characters, each with a full profile.

## Run it

It is a single static file. Open `index.html` in a browser, or visit the Vercel deployment.

## Design

Art Nouveau × medieval × Greco-Roman: Mucha-arched cards with halos, blackletter initials and wax seals, Roman inscriptional capitals and a Greek-key band, in gilt on vellum. Fonts: Cinzel, Cinzel Decorative, Cormorant Garamond and UnifrakturMaguntia (Google Fonts). Card art is placeholder emblems until illustrations exist.

## Adding a demo

Add an entry to `LIBRARY.games` in `index.html`. Give it a `route` once the demo is playable.

## Demos

- `siege/` · **The Siege of Lysa** (demo I): a three-minute siege. Break the walls, then bargain from strength.
- `siege-command/` · **Siege Command** (prototype): the siege rebuilt to test control. Tap-and-drag or lanes (chosen on first launch, switchable in Settings), Charge/Hold/Fall back stances, ram, siege tower, ladders and boiling oil. Uses the sprites in `siege/sprites/`.

## The pitch site (`pitch/`)

`pitch/` is the public pitch website, https://antonia-rise-and-fall.vercel.app. It was uploaded to Vercel by hand until November 2026 and now lives here. It is a static page: `index.html`, `fonts/`, `vendor/three.min.js`, and `i18n/` (Spanish, German and French dictionaries keyed by the English text; any missing sentence falls back to English).

Its Vercel project (`antonia-rise-and-fall`) is connected to this repository with **Root Directory = `pitch`**, so every push to `main` updates it.

Public copy must stay teaser-level: no hidden lore twists or secret reveals.
