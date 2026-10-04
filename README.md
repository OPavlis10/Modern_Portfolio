# Ondřej Pavlis — Portfolio

Personal portfolio site for **Ondřej Pavlis** (`@opavlis10`).
Student at SSPŠ Prague · Developer · Cybersecurity Enthusiast.

→ Live: [ondrej.pavlis.net](https://ondrej.pavlis.net)

## About

Single-file, single-page-app style portfolio — five pages (Home, Work, Skills, About, Contact) behind a full-screen menu that paints in from the corner.

- **WebGL backgrounds per page** — LineWaves on Home, ColorBends on Work, Beams on Skills / About / Contact. Each one only renders while its page is showing.
- **Interactive hero wordmark** — hover a letter to see its dashed vector outline and selection frame; drag letters off the baseline and they spring back.
- **Fold-in headings** — section titles unfold panel by panel when a page opens or scrolls into view.
- **Tilt cards** on the Skills page — spring-driven 3D tilt with a cursor-following inversion circle.
- 14 projects on the Work page, a school path on About, live Prague clock on Contact.
- Custom cursor, magnetic buttons, scrolling marquees, `prefers-reduced-motion` respected throughout.

Vanilla HTML, CSS and JavaScript — no framework, no build step. Libraries load from jsDelivr:
[ogl](https://github.com/oframe/ogl), [three.js](https://threejs.org) and [GSAP](https://gsap.com).

## Run locally

Just open `index.html` in a modern browser.

```bash
open index.html
```

## Deploy

GitHub Pages serves `index.html` from `main`. The `CNAME` file points the custom domain `ondrej.pavlis.net` at it — keep it in the repo.

## Credits

- Background and text effects ported to vanilla JS from [React Bits](https://reactbits.dev) — LineWaves, ColorBends, Beams, FoldText, TechText.
- Skill cards based on [unlumen-ui](https://ui.unlumen.com) TiltCard (Tilt + ClippedCircle).
- Quote: _"Be uncommon amongst uncommon people."_ — David Goggins

---

Built in 2026.
