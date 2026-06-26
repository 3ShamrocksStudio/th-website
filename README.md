# Trashure-Hunters™ — Marketing Website

Official marketing site for **Trashure-Hunters™** — a real-world adventure game where cleaning up actual trash heals a living, magical world.

> **Clean the World. Win the Game.**

## Sections
- **Hero** — 2026 logo, slogan, positioning, floating Elemonster cluster ("Pokémon GO meets Ingress meets a Pixar environmental movie")
- **Concept** — the core contract: clean real trash → heal the game world ("No villains, only neglect"), King Grime vs. restored world
- **Gameplay showcase** — phone mockups of the real app (splash, live map, realm hunts)
- **How It Works** — four steps: explore the map, scan with the AI Trash-Cam, clean it up, heal & collect
- **Elemonsters** — the team lineup band + the six elemental guardians (Bloop, Sproutz, Blazo, Wispo, Cosmix, Orbo)
- **Impact** — real-world cleanup impact
- **Studio** — 3Shamrocks Studio credit
- **Waitlist** — email signup

## Brand
Display type is **Fredoka**; body/UI is the locked **Inter**. Uses the 2026 rebrand logos
(`TH26_*`), white-removed (transparent) Elemonsters, and real gameplay screenshots in
`assets/` (logos/, elemonsters/, app/, screens/). Heavy art is resized + JPEG-compressed for the web.

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
