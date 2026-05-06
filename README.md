# Available .GLASS One-Word Domains (12,406)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C406%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .glass one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,406 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,406 domains · **Median ask:** $81.84 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/glass`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/glass?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./glass.csv">CSV</a> / <a href="./glass.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GLASS search](https://unique.domains/domains/tld/glass?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GLASS search](https://unique.domains/domains/tld/glass?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GLASS one-word domain catalog.

### Files

- `glass.csv` — public CSV extract (1,000 rows)
- `glass.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/glass-oneword-domains/main/glass.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Trex.glass      | available | $99.98    | —             | 80             | 24     | 5      | namecheap |
| WiFi.glass      | available | $99.98    | —             | 83             | 37     | 5      | namecheap |
| finals.glass    | available | $72.99    | $72.99        | 80             | 7      | 6      | namesilo  |
| jewels.glass    | available | $77.99    | —             | 80             | 15     | 6      | name.com  |
| geton.glass     | available | $77.99    | —             | 82             | 10     | 6      | name.com  |
| getup.glass     | available | $77.99    | —             | 82             | 14     | 6      | name.com  |
| toneup.glass    | available | $77.99    | —             | 80             | 5      | 7      | name.com  |
| hangon.glass    | available | $77.99    | —             | 82             | 6      | 7      | name.com  |
| makeit.glass    | available | $77.99    | —             | 82             | 22     | 7      | name.com  |
| pierogi.glass   | available | $77.99    | —             | 82             | 7      | 7      | name.com  |
| messages.glass  | available | $72.99    | $72.99        | 80             | 16     | 8      | namesilo  |
| robots.glass    | available | $72.99    | $72.99        | 62             | 47     | 6      | namesilo  |
| jobs.glass      | premium   | $500      | —             | 79             | 42     | 4      | name.com  |
| shortcuts.glass | available | $77.99    | —             | 48             | 41     | 10     | name.com  |
| homes.glass     | premium   | $123.75   | —             | 86             | 34     | 5      | name.com  |
| lets.glass      | available | $77.99    | —             | 77             | 39     | 4      | name.com  |
| tickets.glass   | premium   | $500      | —             | 64             | 34     | 7      | name.com  |
| tips.glass      | premium   | $500      | —             | 80             | 26     | 4      | name.com  |
| stories.glass   | available | $77.99    | —             | 58             | 36     | 7      | name.com  |
| loans.glass     | premium   | $500      | —             | 58             | 24     | 5      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,406 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/glass?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/glass?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .glass domains, which makes it narrower and more theme-specific than mainstream extensions. The set includes generic words, broad consumer terms, and some names that may echo existing brands or products, such as WiFi.glass or Trex.glass. For founders, the main question is whether the word is memorable, easy to explain, and credible on a niche extension. For investors, the key test is whether the word has clear category relevance and enough buyer fit to justify the ask. With a median ask of 81.84, price discipline matters less than name quality, clarity, and trademark risk.

- All domains in this set use the .glass extension
- 12,406 one-word domains are included
- Median ask across the selection is 81.84
- Check brand fit, clarity, and trademark exposure

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GLASS One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GLASS page](https://unique.domains/domains/tld/glass?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_glass_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
