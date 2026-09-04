# Available .CFD One-Word Domains (20,026)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C026%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cfd one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,026 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,026 domains · **Median ask:** $49.04 · **High-demand under $2,500:** 70

**Last updated:** 2026-09-04
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

- `cfd.csv`, public CSV extract (1,000 rows)
- `cfd.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cfd-oneword-domains/main/cfd.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                          |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------- |
| agone.cfd | available | $1.39     | $26.98        | low            | low    | 5      | namecheap                          |
| dna.cfd   | resell    | —         | —             | high           | medium | 3      | Global Domains International, Inc. |
| aft.cfd   | premium   | $192      | $384          | low            | low    | 3      | namesilo                           |
| aloud.cfd | available | $1.49     | —             | high           | low    | 5      | name.com                           |
| boot.cfd  | resell    | —         | —             | high           | low    | 4      | Global Domains International, Inc. |
| ala.cfd   | premium   | $76.76    | $165.12       | high           | low    | 3      | namesilo                           |
| apart.cfd | available | $1.49     | —             | high           | low    | 5      | name.com                           |
| deal.cfd  | resell    | —         | —             | medium         | low    | 4      | Global Domains International, Inc. |
| Ann.cfd   | premium   | $329.60   | $659.20       | high           | low    | 3      | namesilo                           |
| aroid.cfd | available | $1.39     | $26.98        | low            | low    | 5      | namecheap                          |
| grow.cfd  | resell    | —         | —             | high           | medium | 4      | Namecheap                          |
| any.cfd   | premium   | $90.30    | $180.60       | high           | medium | 3      | namecheap                          |
| badly.cfd | available | $1.49     | —             | medium         | low    | 5      | name.com                           |
| Guys.cfd  | resell    | —         | —             | medium         | low    | 4      | Global Domains International, Inc. |
| ate.cfd   | premium   | $76.76    | $165.12       | high           | low    | 3      | namesilo                           |
| barky.cfd | available | $1.39     | $26.98        | low            | low    | 5      | namecheap                          |
| nice.cfd  | resell    | —         | —             | high           | medium | 4      | Namecheap                          |
| bag.cfd   | premium   | $384      | $768          | medium         | low    | 3      | namesilo                           |
| beamy.cfd | available | $1.39     | $26.98        | low            | low    | 5      | namecheap                          |
| crowd.cfd | resell    | —         | —             | high           | low    | 5      | Global Domains International, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,026 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 70 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cfd?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cfd?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=related_pricing)

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

This list covers 12,332 one-word .CFD domain names, ranging from everyday nouns to compound brandable terms. Names such as Watches, Geton, Rolemodel, and Furnishings show the range of vocabulary available under this extension, with a median asking price near $62. Because .CFD is a newer, lower-cost extension, pricing tends to sit below legacy TLDs, making it a common testing ground for short, memorable one-word names.

- 12,332 one-word .CFD names available for comparison
- Median ask near $62 — low entry point for testing ideas
- Brandable single words: Watches, Geton, Rolemodel, Acup
- Evaluate renewal cost and brand fit before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CFD One-Word Domains*. Version 2026-09-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CFD page](https://unique.domains/domains/tld/cfd?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cfd_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
