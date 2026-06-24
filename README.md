# A+ Stocks — Railway Ready

Premium dark-mode stock screener website for day traders and swing traders.

## Included

- `public/` folder included
- Mobile-first premium dashboard
- Grid view + master table view
- Search and filters
- Trade plan pills: Entry, Stop, T1, T2, R:R
- Near Breakout pulse styling
- Score badges: A+, A, B, C
- Sparkline mini charts
- CSV export
- Railway config

## GitHub + Railway deployment

1. Extract this ZIP.
2. Upload the extracted files to a new GitHub repository.
3. In Railway, choose **New Project → Deploy from GitHub repo**.
4. Select your repo.
5. Railway will run `npm start` automatically.
6. Open Railway **Networking** and generate a public domain.

## Required structure

```text
package.json
server.js
railway.json
README.md
.gitignore
public/
  index.html
  styles.css
  app.js
```

## Note

This version uses professional mock stock data so it deploys immediately without an API key. You can later connect Polygon, Finnhub, Twelve Data, or another API.
