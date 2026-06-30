# More Qi Calculator — Great Tomb of Nazarick

A single-page calculator for the **More Qi** upgrade (Anima), themed after the
Great Tomb of Nazarick from *Overlord*.

It tells you the total Anima cost to go from your current level to a target
level, the cost of your next level, and — if you enter how much Anima you have —
whether you can afford it and how many rank tiers you still need to climb.

## Run locally
Just open `index.html` in a browser.

## Deploy on GitHub Pages
1. Create a repo and push these files (keep the folder layout):
   ```
   index.html
   assets/bg-throne.jpg
   assets/emblem.png
   README.md
   ```
2. Repo **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Your site will be live at `https://<user>.github.io/<repo>/`.

## Notes
- All paths are relative (`assets/...`), so it works from any sub-path on Pages.
- The Cinzel / EB Garamond fonts load from Google Fonts; if offline it falls
  back to Georgia/serif.
- Cost formula and number suffixes are taken directly from the in-game values
  (`681 × 6.10016^(level − 4)`).
- Background art and the Ainz Ooal Gown emblem are fan/anime images included for
  a personal fan project; replace them if you need different licensing.
