# Memora 🧠

Memora is a browser-based memory adventure with four worlds: Missing Object, Pattern Recall, Sequence Sprint, and Memory Pairs. Each world has 12 levels, XP, streaks, and browser-local progress.

## Play

When GitHub Pages is enabled, the game will be available at https://kaidenbudhani-design.github.io/memora/

You can also open `index.html` directly in a browser to play locally. No installation is needed.

## Privacy

The player game currently makes no research data submissions. Game progress is saved in the player's own browser using localStorage. The Supabase research database and private developer dashboard are separate. Do not add passwords, Supabase secret/service-role keys, or participant records to this repository.

Before collecting research data from real people, implement voluntary informed consent, a secure ingestion endpoint, data deletion/withdrawal, and review by an adult mentor or research supervisor.

## Deployment

The repository contains `.github/workflows/pages.yml`. Enable **Settings → Pages → Build and deployment → Source: GitHub Actions**. Commits to `main` will then deploy the static site.
