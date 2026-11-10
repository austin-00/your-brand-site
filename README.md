# Your Brand — Mockup Site

A mobile-first, social-first brand website mockup. Static HTML/CSS/JS — deployable to GitHub Pages in minutes.

## Preview locally
Just open `index.html` in a browser. No build step required.

## Customize
- **Brand name:** search for `YOURBRAND` and `YOUR BRAND` and replace.
- **Colors:** edit the `:root` CSS variables at the top of `index.html` (`--ink`, `--paper`, `--accent`).
- **Social links:** replace every `href="#"` inside `.social-icons` and `.platform` cards with your real profile URLs.
- **Products:** duplicate an `<article class="product">` block and change the text.
- **Feed grid:** swap the `.feed-tile` divs for an embedded widget (see below).

## Adding a live Instagram / TikTok feed
GitHub Pages can't run server-side code, so use a client-side embed:
- **Fouita Instagram Feed** – free, no API key: https://www.fouita.com/widgets/instagram-feed/
- **EmbedSocial** or **Behold.so** – paid, more control, still client-side friendly.

Paste the embed `<script>` + container `<div>` where the `.feed-grid` sits.

## Deploy to GitHub Pages
1. Create a new repo on GitHub called `your-brand-site`.
2. Upload `index.html` and `README.md` (or push via git).
3. Go to **Settings → Pages**.
4. Under **Source**, choose `Deploy from a branch` → `main` → `/ (root)`.
5. Save. Your site goes live at `https://<username>.github.io/your-brand-site/`.

For a custom domain: **Settings → Pages → Custom domain**, then point your DNS `CNAME` to `<username>.github.io`.