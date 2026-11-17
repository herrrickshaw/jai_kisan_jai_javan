# Jai Kisan, Jai Javan: FCI-sourced ready-to-cook rations for the Indian Armed Forces

A written policy proposal for moving Indian Army, Air Force and Navy field rations from private-vendor
supply to ready-to-cook (RTC) and ready-to-eat (MRE) meals produced at Food Corporation of India (FCI) mills
and sourced through FCI, state grain boards, APMCs, NAFED and farmer producer organisations. The repository
is documents only: a strategy, a sourcing framework, a five-year financial model, a Cabinet brief, two MRE
extensions and a 12-slide presentation in Markdown, HTML, PPTX and PDF. There is no code and no data.

> Status: research-only draft (v1.0, 31 July 2026). This is an independent proposal drafted with AI
> assistance; nothing in the repository records submission to, review by, or endorsement from the Ministry
> of Defence, FCI, OFB, AFMC or any other agency. All cost, capacity and farmer-income figures are the
> authors' estimates, not sourced government data, and they are not fully consistent across documents
> (see Limitations).

## What it does
- Sets out the core case: private-vendor rations at ~Rs 71/unit replaced by FCI RTC meals at ~Rs 27/unit (a 62% reduction), produced at 20 distributed FCI mills with Panipat, Ranipet and Kanpur modified first (`STRATEGY.md`).
- Specifies a five-tier sourcing mix (FCI 50%, state grain boards 20%, APMC/direct farmers 15%, NAFED 10%, SFAC/FPOs 5%) and estimates Rs 251 Cr reaching about 50,000 farmers from Rs 300 Cr annual procurement (`SOURCING_CHANNELS.md`).
- Models per-unit costs, a five-year projection (750K units in Y1 rising to 4.1M units/year from Y2), break-even and sensitivity cases (`FINANCIAL_MODEL.md`).
- Provides a Cabinet Committee on Security brief with a phased timeline and service-wise volumes (Army 2.5M, IAF 1M, Navy 600K units/year) (`CABINET_SUBMISSION_BRIEF.md`).
- Extends the carbohydrate-based menu to protein: powdered egg, meat and pulse MREs, fortified powders and thermal-heated no-fire meals, targeting +10-15 g protein per soldier per day (`PROTEIN_MRE_STRATEGY.md`).
- Describes storage and deployment scenarios from forward depots (<30 days, 1,000-5,000 troops) through export, with a storage cost model and technology recommendations (`MRE_STORAGE_DEPLOYMENT_SCENARIOS.md`).

## Quick start
Nothing to install. Clone and read, or open the files on GitHub.

```bash
git clone https://github.com/herrrickshaw/jai_kisan_jai_javan.git
cd jai_kisan_jai_javan
open CABINET_SUBMISSION_BRIEF.md     # the executive summary; start here
open CABINET_PRESENTATION.html      # the 12-slide deck in a browser
```

Suggested order: `STRATEGY.md` (vision and 12-month roadmap), `CABINET_SUBMISSION_BRIEF.md`,
`FINANCIAL_MODEL.md`, `SOURCING_CHANNELS.md`, then the two MRE extensions. For plain-language use with an AI
assistant see [`HOW_TO_USE_WITH_AI.md`](HOW_TO_USE_WITH_AI.md).

## How it works
The documents build on each other: the strategy fixes the product set (khichdi, poha, rajma and regional
variants; 7 core products), unit-cost target and mill plan; the sourcing document allocates the grain
procurement across five channels; the financial model turns volumes and unit costs into a five-year cash
view; the Cabinet brief condenses all three for approval; the protein and storage documents extend the
menu and the logistics. The presentation (`CABINET_PRESENTATION.*`) is a 12-slide summary of the same
material plus an 18-month timeline.

Headline figures as stated in `FINANCIAL_MODEL.md`: setup cost Rs 2.85 Cr; annual operating cost about
Rs 1.24 Cr at 4.1M units/year against Rs 2.92 Cr for the private model; net five-year savings Rs 7.12 Cr;
ROI on setup 250%; payback 12 months (break-even in July 2027 at Rs 23 lakh/month run-rate savings).
Private-vendor cost is assumed to rise 8.3% a year against a locked 1.8% escalator for FCI.

## Repository layout
| Path | Purpose |
|---|---|
| `STRATEGY.md` | Core vision, unit-cost comparison, 20-mill distributed production, 12-month phased roadmap |
| `SOURCING_CHANNELS.md` | Five-tier sourcing model, farmer income distribution, governance, risk mitigation |
| `FINANCIAL_MODEL.md` | Per-unit cost breakdown, three volume scenarios, 5-year projection, break-even, sensitivity |
| `CABINET_SUBMISSION_BRIEF.md` | CCS-format executive summary |
| `PROTEIN_MRE_STRATEGY.md` | Egg, meat, pulse and thermal MRE formats with landed-cost estimates |
| `MRE_STORAGE_DEPLOYMENT_SCENARIOS.md` | Forward-depot to export storage scenarios, cost model, technology, deployment checklists |
| `CABINET_PRESENTATION.{md,html,pptx,pdf}` | The same 12-slide deck in four formats |
| `CHANGELOG.md` | v1.0 release notes and planned v1.1 / v2.0 scope |
| `CONTRIBUTING.md` | Issue labels and suggested file conventions for pilot results and feedback |
| `LICENSE` | MIT with additional terms (see Licence) |
| `.github/workflows/quality-gates.yml` | gitleaks secret scan on push / PR |

## Limitations and known issues
- Figures disagree between documents and have not been reconciled: five-year net savings appear as Rs 17 Cr (old README, brief header), Rs 6.4 Cr (brief table, `CHANGELOG.md`) and Rs 7.12 Cr (`FINANCIAL_MODEL.md`); ROI as 773% and 250%; payback as 3 months, 3.5 months and 12 months; the roadmap as 12 months (`STRATEGY.md`) and 18 months (`CHANGELOG.md`, presentation); steady-state volume as 2.25M and 4.1M units/year. Treat `FINANCIAL_MODEL.md` as the working set.
- No source is cited for the Rs 71/unit private-vendor cost, the 20-mill FCI capacity, the 1.407M personnel count or the 54,700-jobs estimate; these are assumptions.
- `CONTRIBUTING.md` proposes directories (`ANALYSIS/`, `RESEARCH/`, `STAKEHOLDER_BRIEF/`) that do not exist in the repository, and `CHANGELOG.md` says `CONTRIBUTING.md` is "to be added" although it is present.
- `CHANGELOG.md` cites a `github.com/government-strategy/...` URL and `@gov.in` contact addresses that are not verifiable from this repository; the canonical location is `github.com/herrrickshaw/jai_kisan_jai_javan`.
- Pilot data, FCI capacity confirmation, state-board commitments and NAFED/SFAC agreements listed under "Planned for v1.1" do not exist; nothing after v1.0 has been added.
- The `.pptx` and `.pdf` are generated from the Markdown deck and are not regenerated automatically.

## Related repositories
- [india-mandi-arrivals](https://github.com/herrrickshaw/india-mandi-arrivals) — Agmarknet / UPAG mandi arrivals and price collectors, relevant to the APMC sourcing tier.

## Licence
`LICENSE` is the MIT licence text with appended "Additional Terms for Government Use"; it names
"Ministry of Defence, India" as copyright holder, which this repository's history does not substantiate.
GitHub classifies the file as "Other" because of the appended terms.
