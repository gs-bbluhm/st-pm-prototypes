# ST PM Prototypes

Shareable product prototypes, demos, and executive narratives for Staircase AI (a Gainsight company), served via GitHub Pages.

**Live site:** https://gs-bbluhm.github.io/st-pm-prototypes/

## Structure

```
index.html                          # Landing page (index of prototypes)
prototypes/<name>/index.html        # Each prototype, served at /prototypes/<name>/
```

## Prototypes

| Prototype | URL |
|-----------|-----|
| Analyst Agents by Gainsight | https://gs-bbluhm.github.io/st-pm-prototypes/prototypes/staircase-agents-overview/ |

## Deploying a new prototype

1. Add `prototypes/<name>/index.html` (self-contained HTML).
2. Add a card linking to it in the root `index.html`.
3. Commit and push to `main`. GitHub Pages auto-deploys in ~1 minute.
