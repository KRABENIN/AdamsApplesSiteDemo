# 🍎 Adams Apples — Orchard Management Platform

GPS-enabled orchard management platform. Track trees by health, variety & rootstock across multiple locations. Manage work orders, clients & invoices from a single dashboard. Built with Leaflet maps, real-time filtering, and a clean dark UI. Pure HTML/CSS/JS — no dependencies beyond Leaflet.

**[Live Demo →](https://YOUR_USERNAME.github.io/adams-apples-app/)**

---

## Features

- **GPS Map** — Interactive Leaflet map with per-location tree placement, health indicators, and click-to-add tree placement
- **Tree Registry** — Full tree database with scion variety, rootstock, growth stage, health status, and planting history
- **Variety & Species Catalog** — Vigor, taste, CAR ratings, and ripening group tracking across apple, pear, cherry, peach, and plum
- **Work Orders** — Create, filter, and track field operations by type, priority, and status
- **Client Management** — Multi-client support with location assignments, billing history, and payment terms
- **Invoices** — Invoice tracking with paid/outstanding/overdue status and revenue summaries

## Stack

| Layer | Tech |
|---|---|
| UI | Vanilla HTML/CSS/JS |
| Maps | [Leaflet.js](https://leafletjs.com/) + CartoDB Dark tiles |
| Fonts | Inter (Google Fonts) |
| Hosting | GitHub Pages |

## Getting Started

No build step required. Clone and open in a browser:

```bash
git clone https://github.com/YOUR_USERNAME/adams-apples-app.git
cd adams-apples-app
open index.html
```

Or visit the [live demo](https://YOUR_USERNAME.github.io/adams-apples-app/).

## Embedding

```html
<iframe
  src="https://USERNAME.github.io/adams-apples-app/"
  width="100%"
  height="750px"
  style="border: none; border-radius: 12px;"
  loading="lazy"
  title="Adams Apples Orchard Platform">
</iframe>
```

## License

MIT
