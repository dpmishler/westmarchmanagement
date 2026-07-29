# westmarchmanagement.com

Static marketing site for Westmarch Management LLC, hosted on GitHub Pages
with a custom domain.

- `index.html` — the whole site (single page, embedded CSS, no build step)
- `CNAME` — custom-domain binding for GitHub Pages (do not delete)
- `404.html` — not-found page

Deploys automatically on push to `main` (Pages, branch build). DNS lives at
the domain registrar: apex A records → GitHub Pages IPs, `www` CNAME →
`dpmishler.github.io`.

Placeholders to confirm: the contact address `hello@westmarchmanagement.com`
must exist (set up email forwarding at the registrar or swap the address);
the "Current work" section describes the client engagement without naming it —
name it only with the client's permission.
