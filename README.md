# Winnix — Vercel Deployment

Quick steps to deploy this static site to Vercel:

1. Install Vercel CLI (optional):

```bash
npm install -g vercel
```

2. From the project root run:

```bash
vercel
```

Or push this repo to GitHub/GitLab/Bitbucket and import the project in the Vercel dashboard.

Files added to help deployment:

- [package.json](package.json) — minimal scripts (`start` uses `vercel dev`).
- [vercel.json](vercel.json) — routing and clean URL settings.
- [.vercelignore](.vercelignore) — files excluded from deployments.

If you want a build step (SASS, bundlers, frameworks), update the `build` script in [package.json](package.json).
