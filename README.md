# Available .LIVE One-Word Domains (15,900)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C900%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .live one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,900 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,900 domains · **Median ask:** $51.13 · **High-demand under $2,500:** 3

**Last updated:** 2026-09-27
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

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| abls.live | available | $3.49     | $32.99        | medium         | low    | 4      | namesilo                                            |
| hot.live  | resell    | —         | —             | high           | medium | 3      | Name.com, Inc.                                      |
| abc.live  | premium   | $3,250    | $3,250        | high           | medium | 3      | namecheap                                           |
| ahuh.live | available | $3.49     | $32.99        | medium         | low    | 4      | namesilo                                            |
| net.live  | resell    | —         | —             | high           | medium | 3      | Chengdu West Dimension Digital Technology Co., Ltd. |
| abm.live  | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                            |
| akha.live | available | $3.49     | $32.99        | medium         | low    | 4      | namesilo                                            |
| rob.live  | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC                                    |
| ale.live  | premium   | $140      | $280          | high           | low    | 3      | namecheap                                           |
| amah.live | available | $2.98     | $39.48        | medium         | low    | 4      | namecheap                                           |
| aloe.live | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC - 13                                   |
| atc.live  | premium   | $512      | $512          | high           | low    | 3      | namesilo                                            |
| cive.live | available | $2.98     | $39.48        | medium         | low    | 4      | namecheap                                           |
| baas.live | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC                                        |
| atf.live  | premium   | $64.35    | $128.70       | high           | low    | 3      | namecheap                                           |
| dike.live | available | $2.98     | $39.48        | medium         | low    | 4      | namecheap                                           |
| bier.live | resell    | —         | —             | medium         | low    | 4      | Sav.com, LLC - 49                                   |
| bel.live  | premium   | $242      | $242          | high           | low    | 3      | namesilo                                            |
| heap.live | available | $2.98     | $39.48        | high           | low    | 4      | namecheap                                           |
| cord.live | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC - 20                                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,900 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
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

> Unique Domains. *Available .LIVE One-Word Domains*. Version 2026-09-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIVE page](https://unique.domains/domains/tld/live?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_live_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
