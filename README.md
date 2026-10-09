# Hot Bottle Dog

Holding site for **Hot Bottle Dog**, an Irish games studio. Features **BallouT** — the portrait mobile puzzle currently in development.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
npx --yes serve .
```

## Deploy to Netlify

### Option A — Drag & drop

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drop this folder (or zip it first)

### Option B — Git

1. Push this repo to GitHub / GitLab / Bitbucket
2. In Netlify: **Add new site → Import an existing project**
3. Build settings: leave build command empty; publish directory = `/` (or `.`)
4. Deploy

`netlify.toml` already sets the publish directory.

## Customise

- Contact email: replace `hello@hotbottledog.com` in `index.html` when you have a real inbox
- Domain: Netlify → Domain settings → add `hotbottledog.com` (or similar)

## Stack

Static HTML / CSS / JS — no build step required.
