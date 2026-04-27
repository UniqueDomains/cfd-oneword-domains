# Available .CFD One-Word Domains (12,140)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C140%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cfd one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,140 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,140 domains

**Last updated:** 2026-04-27  
**Canonical page:** `https://unique.domains/domains/tld/cfd`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cfd?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cfd.csv">CSV</a> / <a href="./cfd.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CFD search](https://unique.domains/domains/tld/cfd?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CFD search](https://unique.domains/domains/tld/cfd?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CFD one-word domain catalog.

### Files

- `cfd.csv` — public CSV extract (1,000 rows)
- `cfd.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cfd-oneword-domains/main/cfd.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                          |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------- |
| inhouse.cfd     | available | $1.49     | —             | 70             | 23     | 8      | name.com                           |
| jobs.cfd        | resell    | —         | —             | 79             | 42     | 4      | Dynadot LLC                        |
| CocaCola.cfd    | premium   | $360.50   | $721          | 92             | 82     | 9      | namecheap                          |
| distributed.cfd | available | $1.49     | —             | 64             | 21     | 11     | name.com                           |
| finds.cfd       | resell    | —         | —             | 62             | 16     | 5      | Global Domains International, Inc. |
| winners.cfd     | premium   | $165.12   | $330.24       | 60             | 81     | 7      | namesilo                           |
| generations.cfd | available | $1.49     | —             | 56             | 20     | 11     | name.com                           |
| nets.cfd        | premium   | $22.40    | $44.80        | 54             | 81     | 4      | namecheap                          |
| knows.cfd       | available | $1.49     | —             | 48             | 20     | 5      | name.com                           |
| insight.cfd     | premium   | $360.50   | $721          | 76             | 69     | 8      | namecheap                          |
| orders.cfd      | available | $1.49     | —             | 60             | 19     | 6      | name.com                           |
| online.cfd      | premium   | $360.50   | $721          | 70             | 62     | 7      | namecheap                          |
| gobeyond.cfd    | available | $1.49     | —             | 76             | 18     | 9      | name.com                           |
| donuts.cfd      | premium   | $180.60   | $361.20       | 54             | 62     | 6      | namecheap                          |
| makes.cfd       | available | $1.49     | —             | 66             | 17     | 5      | name.com                           |
| RedSox.cfd      | premium   | $360.50   | $721          | 72             | 60     | 7      | namecheap                          |
| intune.cfd      | available | $1.49     | —             | 72             | 16     | 7      | name.com                           |
| farmers.cfd     | premium   | $360.50   | $721          | 54             | 59     | 7      | namecheap                          |
| reflections.cfd | available | $1.49     | —             | 53             | 16     | 11     | name.com                           |
| skills.cfd      | premium   | $180.60   | $361.20       | 58             | 47     | 6      | namecheap                          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 12,140 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cfd?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cfd?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .CFD One-Word Domains*. Version 2026-04-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CFD page](https://unique.domains/domains/tld/cfd?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
