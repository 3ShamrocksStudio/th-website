# Trashure-Hunters™ — Marketing Website

Official marketing site for **Trashure-Hunters™** — a real-world adventure game where cleaning up actual trash heals a living, magical world.

> **Clean the World. Win the Game.**

## Sections
- **Hero** — slogan, logo, positioning ("Pokémon GO meets Ingress meets a Pixar environmental movie")
- **Concept** — the core contract: clean real trash → heal the game world ("No villains, only neglect")
- **How It Works** — four steps: explore the map, scan with the AI Trash-Cam, clean it up, heal & collect
- **Elemonsters** — the six elemental guardians (Bloop, Sproutz, Blazo, Wispo, Cosmix, Orbo)
- **Impact** — real-world cleanup impact
- **Waitlist** — email signup

## Tech
Single-file static site (`index.html`) with embedded CSS/JS and brand assets in `assets/`. No build step. Hosted on GitHub Pages.

### Waitlist signups
The form stores emails in `localStorage` by default. To capture real signups, set `FORM_ENDPOINT` in the `<script>` block at the bottom of `index.html` to a [Formspree](https://formspree.io) / Getform / Basin URL.

## Local preview
```bash
python3 -m http.server 8099
# open http://localhost:8099
```

---
© 2026 3Shamrocks Studio · Trashure-Hunters™
