# TrendScope India

TrendScope India is a static GitHub Pages dashboard for India-focused ecommerce trend discovery, seasonal product tracking, supplier readiness, and product opportunity scoring.

## Required GitHub Pages Structure

Upload the files like this:

```text
TrendScope/
├── index.html
├── README.md
└── data/
    └── live-trends.json
```

The dashboard reads JSON from:

```text
./data/live-trends.json
```

## Files

- `index.html` — main dashboard file.
- `data/live-trends.json` — product trend data used by the dashboard.
- `README.md` — setup and testing instructions.

## How to Upload to GitHub

1. Upload `index.html` to the repository root.
2. Create a folder called `data`.
3. Upload `live-trends.json` inside the `data` folder.
4. Upload this `README.md` to the repository root.

## How to Test

Open the JSON directly:

```text
https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/data/live-trends.json
```

Then open the dashboard:

```text
https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/
```

In the dashboard, open **India Trend Radar** and click **Refresh JSON Radar**.

## Notes

Do not place API keys inside `index.html`. For live API collection, use GitHub Actions to regenerate `data/live-trends.json` from collectors such as YouTube, GDELT, Google News RSS, Wikimedia Pageviews, Reddit optional, and Hacker News Algolia.
