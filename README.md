# Available .LIVE One-Word Domains (6,654)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-6%2C653%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C654%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .live one-word domains from Unique Domains.

> **Important:** this repository is a **public 6,653-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **6,654 domains** on the canonical page below.

**Public extract:** 6,653 rows · **Live catalog:** 6,654 domains

**Last updated:** 2026-04-13  
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

- `live.csv` — public CSV extract (6,653 rows)
- `live.json` — public JSON extract (6,653 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/live-oneword-domains/main/live.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| holding.live   | available | $3.99     | —             | 72             | 19     | 7      | name.com                                                |
| short.live     | resell    | $123.75   | $123.75       | 76             | 36     | 5      | Dynadot Inc                                             |
| athletics.live | premium   | $1,300    | $1,300        | 69             | 52     | 9      | namecheap                                               |
| sorry.live     | available | $3.99     | $43.99        | 140            | 18     | 5      | name.com                                                |
| oil.live       | resell    | $250      | $250          | 74             | 29     | 3      | Spaceship, Inc.                                         |
| abc.live       | premium   | $3,250    | $3,250        | 102            | 50     | 3      | namecheap                                               |
| roller.live    | available | $3.99     | —             | 70             | 18     | 6      | name.com                                                |
| basement.live  | resell    | $3.99     | —             | 68             | 29     | 8      | Spaceship, Inc.                                         |
| all.live       | premium   | $3,125    | $3,125        | 88             | 48     | 3      | name.com                                                |
| rectify.live   | available | $3.99     | $43.99        | 78             | 17     | 7      | name.com                                                |
| developed.live | resell    | $3.99     | $43.99        | 72             | 8      | 9      | NameCheap, Inc.                                         |
| green.live     | premium   | $1,300    | $1,300        | 108            | 44     | 5      | namecheap                                               |
| rookie.live    | available | $3.99     | —             | 76             | 17     | 6      | name.com                                                |
| lively.live    | resell    | —         | —             | 70             | 98     | 6      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| insurance.live | premium   | $780      | $780          | 76             | 44     | 9      | namecheap                                               |
| rats.live      | available | $3.99     | —             | 70             | 17     | 4      | name.com                                                |
| checkout.live  | resell    | —         | —             | 68             | 79     | 9      | Sav.com, LLC                                            |
| haven.live     | premium   | $130      | $260          | 68             | 42     | 5      | namecheap                                               |
| totally.live   | available | $3.99     | $43.99        | 70             | 17     | 7      | name.com                                                |
| paddle.live    | resell    | —         | —             | 86             | 78     | 6      | Xiamen ChinaSource Internet Service Co., Ltd            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 6,653-row public sample | 6,654 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/live?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/live?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LIVE One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIVE page](https://unique.domains/domains/tld/live?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
