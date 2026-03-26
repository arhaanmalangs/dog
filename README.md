# Jumping Cat Game

A tiny browser game where a cat runs and jumps over incoming obstacles.

## Run locally

Open `index.html` directly in your browser, or serve this folder with a static server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Controls

- **Space** or **Up Arrow**: jump
- **Mouse / touch tap**: jump
- If you lose, press jump again to restart

## Deploy on Vercel

1. Push this repository to GitHub/GitLab/Bitbucket.
2. In Vercel, click **Add New → Project** and import the repo.
3. Keep the default settings (Framework Preset: **Other**).
4. Deploy. Vercel will serve `index.html` as a static site.

The included `vercel.json` rewrites all routes to `index.html`, so refreshing deep links still works.

