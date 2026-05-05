# Black Wing Product Selector

Internal field tool for Black Wing Ventures agents — carrier routing, condition lookup, medication search, and build chart evaluation for Final Expense Whole Life products.

## What it does

Helps agents instantly determine which carrier to write for any given client based on:

- **Quoter** — Age + coverage + health → ranked carrier list (highest payout first)
- **Conditions** — Search any health condition, see disposition across all 5 carriers
- **Medications** — Search any drug, see which carriers auto-decline
- **Build Chart** — Height + weight → Level / Graded / Decline across all 5 carriers

## Carriers loaded

- Transamerica (FE Express + Graded FE Express)
- Mutual of Omaha (Living Promise Level + Graded)
- Corebridge (SimpliNow Legacy + Legacy Max + GI)
- Fidelity Life via Instabrain (RAPIDecision FE + GI)
- Ethos / TruStage (TAWL + GAWL)

## Sources

All underwriting data sourced directly from carrier UW guides:

- Transamerica FE Express Solution UW Guide (01/26)
- Corebridge SimpliNow Legacy UW Guide (REV0424)
- Mutual of Omaha Living Promise FL Application + Express Life Reference Guide (27857_0426)
- Fidelity Life RAPIDecision Final Expense Guide (OCT 2023)
- TruStage Life Underwriting Guide 2025 + Health Needs Assessment Guide

## Usage

Just open `index.html` in any browser. No install, no build step, works offline after first load.

## Hosting

This repo is configured for GitHub Pages. Once enabled, the tool is live at:
`https://<your-username>.github.io/<repo-name>/`

## Internal Use Only

For Black Wing Ventures licensed agents only. Always verify final UW decisions with the carrier's current underwriting guide before binding.
