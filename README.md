# Dr Md Jahan Ali — Portfolio Site

A single-page static portfolio built from your CV/resume content (About, Core Expertise,
Experience, Education, Publications, Awards, Contact). No build step, no dependencies —
just `index.html` plus fonts loaded from Google Fonts.

## Deploy to Vercel

You have two easy options. Both are free on Vercel's Hobby plan.

### Option A — Vercel CLI (fastest, from your own computer)

1. Unzip this folder anywhere on your computer.
2. Install the Vercel CLI if you don't have it:
   ```
   npm install -g vercel
   ```
3. From inside this folder, run:
   ```
   vercel
   ```
   Log in when prompted (GitHub, GitLab, or email). Accept the defaults — Vercel
   auto-detects it as a static site, no framework needed.
4. To publish it live (production URL), run:
   ```
   vercel --prod
   ```
5. Vercel will give you a live URL like `https://your-project.vercel.app`. You can
   later add a custom domain from the Vercel dashboard (Project → Settings → Domains).

### Option B — Drag-and-drop / GitHub import (no terminal needed)

1. Create a new GitHub repository and push this folder's contents to it
   (or use GitHub's "upload files" web UI if you don't want to use git).
2. Go to https://vercel.com/new, sign in, and click "Import Project".
3. Select the GitHub repository. Leave all build settings blank/default
   (Framework Preset: "Other", no build command, output directory: `./`).
4. Click Deploy. Vercel will give you a live URL within a minute.

## Editing content later

Everything lives in `index.html` — the CSS is in the `<style>` block at the top and the
content is plain HTML further down (Experience, Publications, etc. are simple lists you
can edit directly). No rebuild step is required; just save and redeploy.

## Files

- `index.html` — the entire site (structure, styling, and a small script for the mobile
  menu and the "show all publications" toggle)
