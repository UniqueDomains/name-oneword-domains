# Available .NAME One-Word Domains (16,657)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C657%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .name one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,657 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,657 domains · **Median ask:** $33.38 · **High-demand under $2,500:** 20

**Last updated:** 2026-08-24
**Canonical page:** `https://unique.domains/domains/tld/name`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/name?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./name.csv">CSV</a> / <a href="./name.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NAME search](https://unique.domains/domains/tld/name?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NAME search](https://unique.domains/domains/tld/name?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NAME one-word domain catalog.

### Files

- `name.csv`, public CSV extract (1,000 rows)
- `name.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/name-oneword-domains/main/name.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| aft.name          | available | $8.98     | $9.98         | low            | low    | 3      | namecheap        |
| crab.name         | resell    | —         | —             | high           | low    | 4      | Dynadot Inc      |
| cxx.name          | available | $8.98     | $9.98         | low            | low    | 3      | namecheap        |
| unit.name         | resell    | —         | —             | high           | low    | 4      | Key-Systems GmbH |
| ilx.name          | available | $8.98     | $9.98         | low            | low    | 3      | namecheap        |
| extra.name        | resell    | —         | —             | high           | low    | 5      | OVH sas          |
| ixl.name          | available | $8.98     | $9.98         | low            | low    | 3      | namecheap        |
| object.name       | resell    | —         | —             | medium         | low    | 6      | Key-Systems GmbH |
| lxi.name          | available | $8.98     | $9.98         | low            | low    | 3      | namecheap        |
| airport.name      | resell    | —         | —             | medium         | low    | 7      | Key-Systems GmbH |
| tie.name          | available | $9.98     | —             | high           | low    | 3      | namecheap        |
| lottery.name      | resell    | —         | —             | high           | low    | 7      | Dynadot Inc      |
| xxv.name          | available | $9.98     | —             | medium         | low    | 3      | namecheap        |
| tobacco.name      | resell    | —         | —             | medium         | low    | 7      | DomainSite, Inc. |
| agog.name         | available | $8.98     | $9.98         | low            | low    | 4      | namecheap        |
| function.name     | resell    | —         | —             | high           | low    | 8      | Key-Systems GmbH |
| also.name         | available | $9.98     | —             | high           | low    | 4      | namecheap        |
| identity.name     | resell    | —         | —             | high           | medium | 8      | Dynadot Inc      |
| ashy.name         | available | $8.98     | $9.98         | low            | low    | 4      | namecheap        |
| spaceshuttle.name | resell    | —         | —             | high           | low    | 13     | GoDaddy.com, LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,657 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 20 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/name?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/name?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word domain names registered under the .name extension, from everyday nouns like finals.name to compound phrases like windowshop.name. With 10,782 names in this selection and a median asking price near $59, .name offers a lower-cost path to short, memorable domains that may already be unavailable in more competitive extensions. Compare word clarity, length, and pricing to identify names worth acquiring or building a brand around.

- 10,782 one-word .name domains tracked, updated daily
- Median asking price near $59 across this selection
- Includes words like headout, coffeeberry, and solarpower
- Short, brandable format suited for founders and investors

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NAME One-Word Domains*. Version 2026-08-24. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NAME page](https://unique.domains/domains/tld/name?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
