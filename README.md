# Great Leap Years — Interactive Technology Timeline

An interactive, scrollable DAG timeline visualising Stephen Fry's *Great Leap Years* podcast (Season 1, 6 episodes). Maps 2 million years of technology history as a connected node graph — from the first stone tools to AlphaGo.

**[Open timeline →](prototype.html)** — download and open in any modern browser. No install, no build step.

---

## How it works

Click any node to highlight its **causal chain** in both directions:

- **Amber** — ancestors: the path that led *to* this invention
- **Slate** — descendants: everything this invention made possible
- Unrelated nodes dim but stay visible and clickable
- Click any node to expand its body text; click **Tap here to collapse all** to reset

---

## Features

- 43 nodes across 5 eras, each with a body text summary
- Proportional date-based vertical positioning (a node at 1,800 CE sits higher than one at 1,850 CE)
- Y-fork SVG connectors for competing paths (solid trunk, dashed ghost branch)
- Era-to-era continuation chevrons where no direct causal link exists
- Portrait photos for people (Wikipedia), emoji icons for inventions and events
- Inline expand/collapse — no modals, no page navigation

---

## Episode coverage

| # | Title | Era covered |
|---|-------|-------------|
| 1 | When We Were Very Young | Prehistory · first tools, language, agricultural revolution |
| 2 | A Faustian Pact | Ancient World + Medieval · writing, paper, Gutenberg, Reformation |
| 3 | Bells | Industrial · electromagnetism, Morse, telegraph, Bell, telephone |
| 4 | Raising the Vail | Industrial · Hertz, radio waves, Marconi, wireless telegraphy |
| 5 | Monopoly | Industrial · Volta, Faraday, Edison, Tesla, War of Currents |
| 6 | Iota-Tron | Computing · vacuum tube, transistor, Shannon, Moore's Law, AlphaGo |

---

## The podcast

**Great Leap Years** by Stephen Fry — available on [BBC Sounds](https://www.bbc.co.uk/sounds) and major podcast platforms (Spotify, Apple Podcasts).

---

## Tech

- Vanilla HTML / CSS / JS — zero dependencies, zero build step
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts CDN
- ~1,100 lines, single self-contained file
- Tested in Chrome, Firefox, Safari

---

## File structure

```
prototype.html      — the timeline (open this)
README.md           — this file
```

Audio files and transcripts are not included in this repository.
