# Available .LIVE One-Word Domains (9,960)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C960%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .live one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,960 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,960 domains · **Median ask:** $29.24 · **High-demand under $2,500:** 1

**Last updated:** 2026-09-25
**Canonical page:** `https://unique.domains/domains/tld/live`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/live?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./live.csv">CSV</a> / <a href="./live.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LIVE search](https://unique.domains/domains/tld/live?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LIVE search](https://unique.domains/domains/tld/live?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LIVE one-word domain catalog.

### Files

- `live.csv`, public CSV extract (1,000 rows)
- `live.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/live-oneword-domains/main/live.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| beautiful.live | premium   | $260      | $520          | high           | low    | 9      | namecheap                                                 |
| vitamin.live   | resell    | —         | —             | high           | low    | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| breakfast.live | premium   | $39       | $78           | high           | low    | 9      | namecheap                                                 |
| madison.live   | premium   | $650      | $1,300        | high           | low    | 7      | namecheap                                                 |
| consent.live   | resell    | —         | —             | high           | low    | 7      | Sav.com, LLC - 34                                         |
| interest.live  | resell    | —         | —             | high           | low    | 8      | Dynadot Inc                                               |
| employ.live    | resell    | —         | —             | high           | low    | 6      | Sav.com, LLC - 41                                         |
| ages.live      | available | $3.99     | —             | medium         | low    | 4      | name.com                                                  |
| esteem.live    | resell    | $3.99     | —             | high           | low    | 6      | Spaceship, Inc.                                           |
| ate.live       | premium   | $140      | $280          | high           | low    | 3      | namecheap                                                 |
| arum.live      | available | $2.98     | $39.48        | medium         | low    | 4      | namecheap                                                 |
| phrase.live    | resell    | $3.99     | —             | high           | low    | 6      | Dynadot Inc                                               |
| bce.live       | premium   | $69.30    | $138.60       | high           | low    | 3      | namecheap                                                 |
| aunt.live      | available | $3.49     | $32.99        | high           | low    | 4      | namesilo                                                  |
| pineapple.live | resell    | $3.99     | —             | high           | low    | 9      | Dynadot Inc                                               |
| beg.live       | premium   | $140      | $280          | high           | low    | 3      | namecheap                                                 |
| boer.live      | available | $2.98     | $39.48        | high           | low    | 4      | namecheap                                                 |
| ass.live       | resell    | —         | —             | high           | low    | 3      | Name.com, Inc.                                            |
| cxv.live       | premium   | $64.35    | $128.70       | high           | low    | 3      | namecheap                                                 |
| clxv.live      | available | $2.98     | $39.48        | medium         | low    | 4      | namecheap                                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,960 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/live?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/live?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of one-word .live domain names spans everyday words and short brandable terms suited to live events, streaming, sports, and real-time services. With a median ask of $55, pricing stays accessible while the set covers over 9,000 names across the .live TLD. Compare available options like domain.live, wakeup.live, and sportsday.live to shortlist a name that fits your brand, or weigh renewal cost and TLD fit before committing.

- 9,042 one-word .live domains, median ask $55
- Short, brandable names like domain.live, wakeup.live
- TLD suited to live events, streaming, real-time brands
- Compare pricing and renewal before you commit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LIVE One-Word Domains*. Version 2026-09-25. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIVE page](https://unique.domains/domains/tld/live?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
