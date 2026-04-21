# Bingo Night — Orchard Hill Elementary

A single-page web app for running a school bingo night event. Designed to run on a laptop connected to a projector, with a separate operator view for the person calling numbers.

**Live site:** [bingo.theiehls.com](https://bingo.theiehls.com)

---

## Views

| View | Purpose |
|---|---|
| **Projection Board** | Full-screen display for the projector — shows the called number grid, current ball, and sponsor carousel |
| **Operator Controls** | Private controls for the caller — enter or click numbers, undo the last call, start a new round |

## Features

- **Number board** — Tracks all 75 balls; called numbers are highlighted as they're drawn
- **Sponsor management** — Add sponsors with a name, prize description, and optional logo; sponsors rotate through a carousel on the projection view
- **Multi-round support** — Clear the board and advance the round counter without losing sponsor data
- **Persistent state** — All called numbers, round count, and sponsor info are saved in `localStorage` so a page refresh won't lose progress
- **Responsive layout** — Automatically adjusts for landscape/portrait and various screen sizes

## Tech

Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build step, no server required.

## Deployment

Hosted on [GitHub Pages](https://pages.github.com) with a custom domain via CNAME.

## License

MIT — see [LICENSE](LICENSE)
