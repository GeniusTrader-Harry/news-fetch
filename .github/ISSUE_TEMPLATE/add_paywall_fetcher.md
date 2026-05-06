---
name: Add a paywalled outlet
about: Propose adding a fetcher for another paywalled news source (Economist, Barron's, etc.)
title: "[Outlet] Add fetcher for "
labels: enhancement, paywall-fetcher
---

## Outlet

<!-- e.g. The Economist, Barron's, Nikkei Asia, Politico Pro -->

## Subscription you have

- [ ] Personal
- [ ] University / library access
- [ ] Other (specify)

## Bot-protection level (rough check)

Try `curl_cffi` against an article URL with your cookies. What happens?

- [ ] HTTP 200, full article body visible — `curl_cffi` works (FT-tier difficulty)
- [ ] HTTP 200, but body needs unusual extraction (no JSON-LD, no clean paragraph tags) — solvable, just custom regex
- [ ] HTTP 403, "Are you a robot?" page — PerimeterX or similar, won't work via curl_cffi (Bloomberg-tier; needs Playwright)
- [ ] Haven't tested yet

## What body extraction looks like

<!-- After fetching the page HTML, where does the article body live? -->
<!-- - JSON-LD `articleBody` field (FT-style)? -->
<!-- - `<p data-type="paragraph">` tags (WSJ-style)? -->
<!-- - `<article>` tag with paragraph children? -->
<!-- - Other (describe)? -->

## RSS feed available?

<!-- For story triage. URL: -->

## Any other notes

<!-- Quirks, anti-scraping behaviour you've noticed, etc. -->
