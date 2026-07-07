# Available .ZONE One-Word Domains (78,773)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-78%2C773%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .zone one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **78,773 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 78,773 domains · **Median ask:** $25.90 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/zone`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/zone?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./zone.csv">CSV</a> / <a href="./zone.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ZONE search](https://unique.domains/domains/tld/zone?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ZONE search](https://unique.domains/domains/tld/zone?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ZONE one-word domain catalog.

### Files

- `zone.csv`, public CSV extract (1,000 rows)
- `zone.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/zone-oneword-domains/main/zone.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                          |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------------ |
| grew.zone    | available | $14.99    | —             | high           | low    | 4      | name.com                                                           |
| caps.zone    | resell    | —         | —             | medium         | high   | 4      | Domain Science Kutatási Szolgáltató Korlátolt Felelősségű Társaság |
| inc.zone     | premium   | $854      | $854          | medium         | low    | 3      | namesilo                                                           |
| brook.zone   | available | $14.99    | —             | medium         | low    | 5      | name.com                                                           |
| film.zone    | resell    | —         | —             | high           | low    | 4      | Porkbun LLC                                                        |
| science.zone | premium   | $1,040    | $1,040        | high           | medium | 7      | namecheap                                                          |
| farms.zone   | available | $14.99    | —             | medium         | low    | 5      | name.com                                                           |
| seed.zone    | resell    | —         | —             | medium         | low    | 4      | Porkbun LLC                                                        |
| hanoi.zone   | available | $14.99    | —             | medium         | low    | 5      | name.com                                                           |
| send.zone    | resell    | —         | —             | high           | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd                       |
| ohoh.zone    | available | $14.99    | —             | high           | low    | 5      | name.com                                                           |
| album.zone   | resell    | —         | —             | high           | low    | 5      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn)            |
| plier.zone   | available | $14.99    | —             | high           | low    | 5      | name.com                                                           |
| drive.zone   | resell    | —         | —             | high           | low    | 5      | DNSPod, Inc.                                                       |
| roofs.zone   | available | $14.99    | —             | low            | low    | 5      | name.com                                                           |
| nifty.zone   | resell    | —         | —             | high           | low    | 5      | Porkbun LLC                                                        |
| shoot.zone   | available | $14.99    | —             | high           | low    | 5      | name.com                                                           |
| nurse.zone   | resell    | —         | —             | medium         | low    | 5      | DNSPod, Inc.                                                       |
| trios.zone   | available | $14.99    | —             | low            | low    | 5      | name.com                                                           |
| dollar.zone  | resell    | —         | —             | high           | low    | 6      | DNSPod, Inc.                                                       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 78,773 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/zone?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/zone?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=related_pricing)

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

This selection includes 78,773 one-word .zone domain names, with a median asking price near $26. The list spans short, dictionary-style names across sectors such as real estate, technology, insurance, and lifestyle, giving founders a brandable shortlist and investors a consistently priced pool to evaluate within the .zone extension.

- 78,773 one-word .zone domains tracked in this set
- Median asking price near $26 across the list
- Short, brandable names like tech.zone and data.zone
- Covers sectors from real estate to insurance to lifestyle

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ZONE One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ZONE page](https://unique.domains/domains/tld/zone?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_zone_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
