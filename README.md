# Available .BET One-Word Domains (8,151)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C151%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C151%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .bet one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 8,151 rows · **Live catalog:** 8,151 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/bet`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/bet?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./bet.csv">CSV</a> / <a href="./bet.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BET search](https://unique.domains/domains/tld/bet?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BET search](https://unique.domains/domains/tld/bet?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BET one-word domain catalog.

### Files

- `bet.csv` — public CSV extract (8,151 rows)
- `bet.json` — public JSON extract (8,151 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bet-oneword-domains/main/bet.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar         |
| -------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ----------------- |
| resume.bet     | available | $14.99     | $33.99        | 98             | 35     | 6      | name.com          |
| fucking.bet    | resell    | $2,297.70  | $33.99        | 58             | 41     | 7      | Sav.com, LLC - 38 |
| enterprise.bet | premium   | $325       | $325          | 68             | 61     | 10     | namecheap         |
| adaptive.bet   | available | $14.99     | $33.99        | 76             | 32     | 8      | name.com          |
| alligator.bet  | resell    | $12,650    | $12,650       | 106            | 14     | 9      | Spaceship, Inc.   |
| athletics.bet  | premium   | $325       | $325          | 69             | 52     | 9      | namecheap         |
| toast.bet      | available | $14.99     | —             | 68             | 32     | 5      | name.com          |
| covered.bet    | resell    | $14.99     | $33.99        | 74             | 14     | 7      | GoDaddy.com, LLC  |
| hotel.bet      | premium   | $1,300     | $1,300        | 70             | 45     | 5      | namecheap         |
| aesthetic.bet  | available | $14.99     | $33.99        | 88             | 31     | 9      | name.com          |
| beautiful.bet  | resell    | —          | —             | 104            | 99     | 9      | Porkbun LLC       |
| nice.bet       | premium   | $53,552.05 | $33.99        | 86             | 42     | 4      | Porkbun LLC       |
| building.bet   | available | $35.98     | —             | 74             | 28     | 8      | namecheap         |
| back.bet       | resell    | —          | —             | 76             | 99     | 4      | Epik LLC          |
| dental.bet     | premium   | $14.99     | $33.99        | 90             | 36     | 6      | name.com          |
| curative.bet   | available | $14.99     | $33.99        | 92             | 27     | 8      | name.com          |
| blank.bet      | resell    | —          | —             | 64             | 99     | 5      | Sav.com, LLC      |
| advance.bet    | premium   | $1,250     | $1,250        | 110            | 33     | 7      | name.com          |
| showcase.bet   | available | $14.99     | —             | 82             | 27     | 8      | name.com          |
| crazy.bet      | resell    | —          | —             | 86             | 98     | 5      | Name.com, Inc.    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,151-row public sample | 8,151 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bet?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bet?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .BET One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BET page](https://unique.domains/domains/tld/bet?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bet_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
