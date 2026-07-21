# The Value of Staircase, marketing/value site

A single, self-contained `index.html` that tells the "Value of Staircase" story for prospects and customers. Editorial, trustworthy, Gainsight-adjacent. No build step, no external dependencies except Google Fonts loaded via `<link>`. Trivially deployable to static hosting (GitHub Pages).

## Copy source
All wording is drawn from the finalized copy at:
`inbox/workshop/staircase-value-story/value-story.md`

Substance, claims, and argument structure are preserved. Only web microcopy (nav labels, button text, pull-stat framing) was lightly adapted. Hard brand rules honored: no em dashes anywhere; no hype/AI-tell phrasing; the customer's implicit questions are handled by the narrative, not turned into an FAQ.

## Structure
1. Hero: Full-Spectrum Capture, honest framing, animated relationship-signal readout across the five channels.
2. Day one: the five outputs (Topics, Sentiment, Events and signals, Summaries, AI Analysts) plus the standing-view line.
3. Three pillars, each visually distinct with use cases and one pull-stat.
4. Staircase inside Gainsight CS, set apart as a dark "featured chapter."
5. The value journey: Unlock, Adopt, Prove, as an ascending staircase, plus what you can measure.
6. Closing "the short version" and a soft, non-pushy footer.

## Design notes
- Palette: cool violet-tinted paper, deep indigo ink, electric-indigo primary (`#5A32E6`), a teal "live signal" accent used sparingly, deep-violet Gainsight chapter. Dark mode via `prefers-color-scheme`.
- Type: Fraunces (editorial display), Inter (body), IBM Plex Mono (labels, data, signal annotations).
- Signature: the hero signal-readout trace (a live relationship signal), echoed by the ascending staircase in the journey (a nod to the product name).
- Accessible: semantic HTML, keyboard-focusable sticky nav, visible focus rings, `prefers-reduced-motion` respected.

## Run locally
Served via `.claude/launch.json` entry `staircase-value-story` (python http.server on port 8780), or:
```
python3 -m http.server 8780 --directory .
```

## Status
NOT deployed. Local build only. Not pushed to git.
