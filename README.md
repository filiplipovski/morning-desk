# Morning Desk

A daily pre-market business brief covering CNBC, WSJ, Chicago Tribune and NYT headlines, markets, the economic calendar, rates, derivatives, metals and banking. Every story has a plain-English explainer.

## Files

- `index.html`: the whole site
- `briefs/index.json`: the list of editions (newest is shown first)
- `briefs/YYYY-MM-DD.json`: one file per edition

To add an edition, drop in a new `briefs/<date>.json` and add a line for it to `briefs/index.json`. The site picks it up on the next page load. You can link straight to an edition with `#2026-10-01` at the end of the URL.

## Put it online (GitHub Pages, free)

1. Create an account at https://github.com/signup.
2. Click **+ → New repository**. Name it `morning-desk`, set it to **Public**, and click **Create repository**.
3. On the empty repo page, click **uploading an existing file**. Drag in `index.html`, `README.md`, `robots.txt` and the `briefs` folder, then click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, set Branch to **main** and **/(root)**, and click **Save**.
5. After about a minute the site is live at `https://<your-username>.github.io/morning-desk/`.

## Get it into Google search

1. Go to https://search.google.com/search-console and add a **URL prefix** property for your site's address.
2. Verify ownership with the **HTML tag** method: paste the meta tag into `index.html` under `<head>` and commit the change.
3. Under **Sitemaps** or **URL inspection**, submit the homepage and click **Request indexing**.

Google usually takes a few days to a few weeks to show a new site in search results.
