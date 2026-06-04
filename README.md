# Available .REVIEWS One-Word Domains (12,092)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C092%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .reviews one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,092 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,092 domains · **Median ask:** $27.26 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/reviews`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/reviews?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./reviews.csv">CSV</a> / <a href="./reviews.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REVIEWS search](https://unique.domains/domains/tld/reviews?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REVIEWS search](https://unique.domains/domains/tld/reviews?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REVIEWS one-word domain catalog.

### Files

- `reviews.csv` — public CSV extract (1,000 rows)
- `reviews.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/reviews-oneword-domains/main/reviews.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar              |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------- |
| matt.reviews      | available | $7.99     | —             | 72             | 71     | 4      | name.com               |
| quick.reviews     | resell    | —         | —             | 72             | 43     | 5      | Sav.com, LLC           |
| air.reviews       | premium   | $260      | $260          | 84             | 48     | 3      | namecheap              |
| bloom.reviews     | available | $7.99     | —             | 72             | 51     | 5      | name.com               |
| fake.reviews      | resell    | —         | —             | 84             | 32     | 4      | Dynadot Inc            |
| wow.reviews       | premium   | $78.54    | $78.54        | 80             | 47     | 3      | namesilo               |
| bridge.reviews    | available | $7.99     | —             | 68             | 49     | 6      | name.com               |
| race.reviews      | resell    | —         | —             | 78             | 29     | 4      | Go France Domains, LLC |
| dna.reviews       | premium   | $118.80   | $118.80       | 78             | 47     | 3      | namesilo               |
| yes.reviews       | available | $7.99     | —             | 132            | 47     | 3      | name.com               |
| rated.reviews     | resell    | —         | —             | 66             | 11     | 5      | GoDaddy.com, LLC       |
| genius.reviews    | premium   | $250      | $250          | 98             | 44     | 6      | name.com               |
| edge.reviews      | available | $7.99     | —             | 72             | 47     | 4      | name.com               |
| justnow.reviews   | resell    | —         | —             | 56             | 10     | 8      | Wild West Domains, LLC |
| awesome.reviews   | premium   | $35.40    | $35.40        | 98             | 44     | 7      | namesilo               |
| beam.reviews      | available | $7.99     | —             | 66             | 44     | 4      | name.com               |
| scale.reviews     | premium   | $118.80   | $118.80       | 96             | 42     | 5      | namesilo               |
| andrew.reviews    | available | $7.99     | —             | 70             | 40     | 6      | name.com               |
| earth.reviews     | premium   | $242      | $242          | 62             | 42     | 5      | namesilo               |
| alexander.reviews | available | $7.99     | —             | 66             | 38     | 9      | name.com               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,092 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/reviews?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/reviews?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .reviews domains. The strongest candidates are the ones where the word and the extension read naturally together, as in analysis.reviews or library.reviews. For founders, that usually means a name that is easy to understand, easy to remember, and specific enough to support a review-led brand. For investors, the key test is whether the word has broad commercial use and clear resale logic inside a niche TLD. The median ask here is 24.61, so the main decision is rarely entry price alone. Focus more on semantic fit, renewal exposure, and whether the word creates immediate credibility with .reviews.

- Prioritize words that pair naturally with .reviews
- Generic terms usually age better than obscure words
- Check renewal costs before treating low asks as bargains
- Avoid words with obvious trademark or category conflicts

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REVIEWS One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REVIEWS page](https://unique.domains/domains/tld/reviews?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reviews_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
