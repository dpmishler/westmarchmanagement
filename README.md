# westmarchmanagement.com

Static site for Westmarch Management LLC — AI process consultation &
integration. Hosted on GitHub Pages with a custom domain.

- `index.html` — the whole site: single page, embedded CSS/JS, zero
  dependencies, no build step. The hero contour map is a hand-rolled
  marching-squares renderer over gradient noise (2D canvas, ~100 lines).
- `fonts/` — self-hosted Sentient + Switzer variable fonts (Fontshare,
  ITF Free Font License — license permits web embedding/self-hosting).
- `CNAME` — custom-domain binding for GitHub Pages (do not delete)
- `404.html` — not-found page

Motion is progressive enhancement: scroll-driven animations sit behind
`@supports (animation-timeline: view())`, and everything (including the
canvas) respects `prefers-reduced-motion`.

Deploys automatically on push to `main` (Pages, branch build). DNS lives at
the domain registrar: apex A records → GitHub Pages IPs, `www` CNAME →
`dpmishler.github.io`.

Placeholders to confirm: the contact address `hello@westmarchmanagement.com`
must exist (set up email forwarding at the registrar or swap the address);
the Fieldwork case study describes the client engagement without naming it —
name it only with the client's permission.
