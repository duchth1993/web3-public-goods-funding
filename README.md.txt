# Web3 Public Goods Funding Tracker (2021–2025)

> 📊 A clean, unified dataset of **public goods funding** across Gitcoin Grants and Allo Protocol — designed for researchers, model builders, and DAO analysts.

As stated by [OmniacsDAO](https://omniacsdao.xyz):  
> *“We create online training material, accessible code repositories, build machine learning models, design algorithms, provide analysis services and experiment with AI applications to help proliferate data science knowledge.”*

This dataset directly supports that mission — by enabling **better analysis, modeling, and decision-making** for open data projects.

---

## 📦 What’s Included?

| Field | Description |
|-------|-------------|
| `round` | Grant round (e.g., GR9, GR20, Allo-Q3) |
| `project_name` | Name of funded project (e.g., `OmniacsDAO`, `Cryptopond`) |
| `category` | Domain: Data, AI, Privacy, Tooling, etc. |
| `recipient_address` | Anonymized Ethereum address |
| `amount_usd` | Funding amount in **standardized USD** |
| `token` | Original token (USDC, DAI, ETH, etc.) |
| `matching_pool` | Quadratic (Gitcoin) or Direct (Allo) |
| `platform` | Gitcoin or Allo |
| `year` | Year of funding |

✅ **50+ records**  
✅ **7 grants to OmniacsDAO** (across Data, Education, Tooling, Research)  
✅ **Clean, consistent, ready-to-analyze**

---

## 🛠️ How to Use

### In R
```r
df <- read.csv("funding_data.csv")
head(df)
import pandas as pd
df = pd.read_csv("funding_data.csv")
print(df.head())
For Modeling
Train GrantsMatchingAI improvements (see GrantsMatchingAI )
Analyze trends in underfunded categories (e.g., Data Science)
Build dashboards like numerdash or eth2-validator-health-dashboard

🌐 Why This Matters
OmniacsDAO has delivered:

✅ 12+ open datasets
✅ 8+ statistical models
✅ 5+ public dashboards
✅ 3+ hackathon placings
But to sustain this, we need transparent, open funding data — so builders know where support exists, and funders know where gaps remain.

This dataset is a step toward data-driven public goods allocation.

🔗 My Pond profile: https://cryptopond.xyz/developer/fcc064a3-6b5f-11f0-a1f3-024775222cc3

✅ Call to Action
If you believe public goods deserve better funding…
If you believe data should be open, clean, and useful…

👉 Support $IACS — the token that turns data science into public infrastructure.
👉 Contribute to @OmniacsDAO — builders of the data commons.

🌊 “Public goods for all, and all for the public good!”
— The Omniacs