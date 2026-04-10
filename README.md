# Available .NAME One-Word Domains (5,621,926)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C141%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C621%2C926%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .name one-word domains from Unique Domains.

> **Important:** this repository is a **public 8,141-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,621,926 domains** on the canonical page below.

**Public extract:** 8,141 rows · **Live catalog:** 5,621,926 domains

**Last updated:** 2026-04-10  
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

- `name.csv` — public CSV extract (8,141 rows)
- `name.json` — public JSON extract (8,141 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/name-oneword-domains/main/name.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar              |
| --------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ---------------------- |
| enjoy.name      | available | $9.98       | —             | 88             | 66     | 5      | namecheap              |
| australia.name  | resell    | —           | —             | 66             | 99     | 9      | Porkbun LLC            |
| outdoor.name    | premium   | $1,184.50   | —             | 85             | 32     | 7      | Realtime Register B.V. |
| nationwide.name | available | $9.98       | —             | 76             | 66     | 10     | namecheap              |
| luxembourg.name | resell    | —           | —             | 60             | 97     | 10     | InterNetX GmbH         |
| crazy.name      | premium   | $355,217.34 | —             | 64             | 32     | 5      | Dynadot Inc            |
| seventeen.name  | available | $9.98       | —             | 84             | 62     | 9      | namecheap              |
| taiwan.name     | resell    | —           | —             | 66             | 92     | 6      | Dynadot Inc            |
| option.name     | premium   | $9.98       | —             | 104            | 20     | 6      | namecheap              |
| athletics.name  | available | $9.98       | —             | 69             | 52     | 9      | namecheap              |
| authentic.name  | resell    | —           | —             | 76             | 83     | 9      | Dynadot Inc            |
| abnormal.name   | premium   | $676.20     | $676.20       | 74             | 17     | 8      | name.com               |
| strategy.name   | available | $9.98       | —             | 74             | 43     | 8      | namecheap              |
| identity.name   | resell    | —           | —             | 80             | 65     | 8      | Dynadot Inc            |
| central.name    | premium   | —           | —             | 70             | 100    | 7      | —                      |
| experience.name | available | $9.98       | —             | 74             | 42     | 10     | namecheap              |
| fantastic.name  | resell    | —           | —             | 88             | 63     | 9      | GoDaddy.com, LLC       |
| gay.name        | premium   | —           | —             | 122            | 99     | 3      | —                      |
| learning.name   | available | $9.98       | —             | 76             | 41     | 8      | namecheap              |
| which.name      | resell    | —           | —             | 66             | 59     | 5      | Dynadot Inc            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,141-row public sample | 5,621,926 live domains                           |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/name?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/name?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .NAME One-Word Domains*. Version 2026-04-10. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NAME page](https://unique.domains/domains/tld/name?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_name_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
