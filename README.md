# The Retirement of Myogiryu — 断髪式

A visual story about attending the *danpatsu-shiki* (topknot-cutting ceremony) of sumo wrestler **Myogiryu Yasunari** at Ryogoku Kokugikan, Tokyo.

**[View the presentation →](https://russellhunter.github.io/mexico-city-flash-talk/)**

---

## About

In October 2025, I travelled to Tokyo to witness one of sumo's most sacred traditions: the retirement ceremony of Myogiryu, a wrestler who competed at the sport's highest levels for 15 years, earning 601 career wins and reaching the rank of Sekiwake.

The *danpatsu-shiki* is part wedding, part funeral — a two-and-a-half-hour ritual where every person who shaped the wrestler's career takes a turn cutting a piece of his topknot. The final cut, made by his stablemaster, severs the last physical tie to his life as a competitor.

This flash talk was originally presented at the Automattic GTM Revenue Team Meetup in Mexico City, February 2026.

## Navigating the Presentation

| Input | Action |
|-------|--------|
| `→` `↓` `Space` `Enter` | Next slide |
| `←` `↑` | Previous slide |
| `F` | Toggle fullscreen |
| `R` | Reset to first slide |
| `Home` / `End` | Jump to first / last slide |
| **Click** right half | Next slide |
| **Click** left half | Previous slide |
| **Swipe** left / right | Next / previous slide (touch) |

## Design

The presentation uses a traditional Japanese color palette:

| Color | Name | Hex | Usage |
|-------|------|-----|-------|
| ![#0d1b2a](https://placehold.co/12x12/0d1b2a/0d1b2a) | Kon (紺) | `#0d1b2a` | Deep navy background |
| ![#f5f0e6](https://placehold.co/12x12/f5f0e6/f5f0e6) | Kinari (生成) | `#f5f0e6` | Undyed silk cream text |
| ![#c53d43](https://placehold.co/12x12/c53d43/c53d43) | Shu (朱) | `#c53d43` | Vermillion highlights |
| ![#d4a574](https://placehold.co/12x12/d4a574/d4a574) | Kitsune (狐) | `#d4a574` | Gold accents |
| ![#1e3a5f](https://placehold.co/12x12/1e3a5f/1e3a5f) | Ai (藍) | `#1e3a5f` | Indigo blue |

Typography: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) for English, [Noto Serif JP](https://fonts.google.com/noto/specimen/Noto+Serif+JP) for Japanese.

Visual effects include seigaiha wave patterns, enso circles, ink-splash reveals, Ken Burns panning on photographs, and floating particle animations evoking incense smoke.

## Running Locally

No build step. Open the file directly or serve it:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## Structure

```
├── index.html              # Self-contained presentation (HTML + CSS + JS)
├── assets/
│   └── images/             # Original photography from the ceremony
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment
├── LICENSE
└── README.md
```

## License

MIT — see [LICENSE](LICENSE).

All photographs are original and taken by the author at Ryogoku Kokugikan, Tokyo.
