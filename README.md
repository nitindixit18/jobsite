# Free Govt Jobs Aggregator
1. Create a GitHub repo, upload these files.
2. Settings > Pages > Source: **GitHub Actions**.
3. Actions tab > run "scrape-and-deploy" manually once.
4. Add sources in scraper/sources.json. Test locally: pip install -r requirements.txt; python scraper/scrape.py; python scraper/build.py
Note: verify each source's robots.txt/terms. Some sites need a custom selector (add per-source later).
