# light-merge-site

The public-facing static site for Light Merge, served by GitHub Pages at
`https://light-merge.blubalab.com`. It exists as its own **public** repo because the game's
source repo (`Light-Merge`) stays private, and GitHub Pages' free tier only serves from
public repos.

Two pages:

- `index.html` — the landing page
- `privacy/index.html` — the privacy policy (canonical text is authored in the game repo at
  `Docs/Marketing/PrivacyPolicy.html`; copy changes over here when it's updated)

No build step. GitHub Pages serves this repo's root directly. `CNAME` pins the custom domain;
`.nojekyll` turns off Jekyll processing since this is plain static HTML.
