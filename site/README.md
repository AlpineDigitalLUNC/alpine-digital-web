# LUNC Strategist Toolkit

**Owner:** Adrian Voss (`05-Head-of-Crypto/01-LUNC-Adrian-Voss/`) | **Last Updated:** May 2026

The complete LUNC strategy website + toolkit Adrian uses to publish thesis, run scenario analysis, manage portfolios, and call out validator/blockchain intelligence. Originally branded "Alpine Digital" — renamed to **LUNC Strategist Toolkit** to disambiguate from the Liquid-Network tokenization "Alpine Digital" project under BD/01-Digital-Investment-Office.

---

## Layout

```
LUNC-Strategist-Toolkit/
├── README.md                       # This file
├── index.html                      # Site entry
├── index-lightblue.html            # Alt theme
├── terra-luna-story.html           # Hero / origin story page
├── alpine-banner.jpg               # Banner image (legacy "Alpine" branding)
│
├── 01-InvestmentThesis/            # 6 HTML — BlockchainIntel, Catalysts, Compelling, Emergence, History, ValidatorIntel
├── 02-EvaluationScenario/          # ScenarioAnalysis, BinomialPricingModel
├── 03-PortfolioManagement/         # ModelPortfolios, TradePlanner, WalletAnalyzer
├── 04-Utilities/                   # CEXLinks, DEXLinks, SeedGenerator, WalletProviders, WalletScanner
├── 05-LunaClassicIntel/            # BlockchainIntel, ValidatorIntel (LUNC-specific)
│
├── Archive/                        # Prior versions (v1.0, v2.0, v3.0, v3.1)
├── Images/                         # Site imagery (Alpine-branded backgrounds, profile shots)
└── Old Versions/                   # Pre-restructure HTML
```

---

## Notes

- **Fonts:** Spezia is at `00-Claude Code/04-Shared-Resources/fonts/Spezia/` (StandardVersion + VariableFont). Other projects also reference it.
- **Re-branding:** Many filenames still say "Alpine" (e.g., `alpine-banner.jpg`, `Alpine Digital 1.jpeg`) — these can be renamed gradually as the LUNC Strategist brand is finalized.
- **Investment thesis content** (`01-InvestmentThesis/`) doubles as Adrian's working investment-thesis library, not just static website pages.

---

## Open Questions / Next Actions

- [ ] Decide if "Alpine" branding stays or goes (and where) — could be: keep as the visual brand, drop from filenames, or rename everywhere
- [ ] Consolidate `Archive/` and `Old Versions/` (one or the other)
- [ ] Inventory `Images/` for what's actually used vs orphaned
