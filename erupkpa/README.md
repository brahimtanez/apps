# AppScout JSON Starter Catalog

Generated: 2026-09-01

- Apps: 82
- Games: 69
- Total catalog items: 151

## Upload layout

Create a GitHub repo and put these files in a `data/` folder.

```text
data/
  app_config.json
  manifest.json
  categories.json
  apps.json
  games.json
  home.json
```

Then replace `YOUR_USERNAME/YOUR_REPO` in `app_config.json`.

## Important

Ratings, download counts, descriptions, app icons and screenshots are intentionally empty in this starter dataset. Those values change frequently, and some media/text may need separate rights/reuse review. The stable V1 data focuses on app names, package IDs, categories, tags and direct Google Play URLs.

## Laravel migration later

Keep the same response shapes when you migrate:

- `GET /api/home` -> home.json shape
- `GET /api/apps` -> apps.json shape
- `GET /api/games` -> games.json shape
- `GET /api/categories` -> categories.json shape

Flutter can then swap the GitHub Raw base URL for your Laravel API without a UI rewrite.
