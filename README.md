# DeckVerse Rules (GitHub Pages)

This is a minimal static site for DeckVerse rules.

## Structure
- `index.html` — scenarios list
- `scenarios/werewolf/index.html` — Werewolf rules
- `assets/style.css` — shared styles

## Run locally
Just open `index.html` in your browser.

## Publish on GitHub Pages
1. Create a repository (e.g., `deckverse-rules`) and push these files.
2. In the repo: Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, Folder: `/` → Save.
3. Wait 1–3 minutes. Your site will be at `https://USER.github.io/deckverse-rules/`.
4. Optional: set a custom domain in Settings → Pages → Custom domain.

## Add more scenarios
Copy `scenarios/werewolf/` to a new folder (e.g., `scenarios/mafia/`), update content, and add a card link in `index.html`.
