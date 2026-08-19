# Adriatic IT Pay Explorer 🌊

**Same salaries. Two rankings.** A single-file, dependency-free interactive page comparing IT pay, wage premiums, ICT exports and pay-transparency status across 8 Balkan & Adriatic markets — with every figure's **basis (net/gross), source and vintage printed on the label**.

> Balkan IT talks in *net*; EU statistics and the Pay Transparency Directive talk in *gross*. Benchmark across that line carelessly and country rankings quietly flip. This page makes the flip visible.

## Interactive features

- **NET ⇄ GROSS toggle** — bars animate and re-rank; Slovenia and Croatia visibly trade places on the same data
- **Salary translator** — enter any amount, pick market and basis, and see the gross an employer must pay for the same net (with % deltas) and the net the same gross leaves, across all 8 markets
- **Live tooltips** on every bar (hover on desktop, tap on mobile) with the source and fine print
- **Inline SVG flags** — hand-drawn simplified marks, so flags render identically on every OS (emoji flags don't load on Windows)
- **Animated bars** that sweep in on scroll; `prefers-reduced-motion` respected

## What's inside

| Sheet | Content |
|---|---|
| **T.01 — Pay ladders** | Developer pay by seniority (Serbia · Croatia · Slovenia). Solid bars = as reported; hatched bars = converted estimates. |
| **T.02 — Salary translator** | Your amount, translated: employer-cost gross to match your net, and net kept from the same gross, in all 8 markets. |
| **T.03 — The IT premium** | IT vs. national-average multiples (RS ≈2.3× · MK ≈1.7× · SI 1.35× · HR 1.21×) — plus explicit *data-gap* rows for BG, BiH, ME, AL, because the gap is a finding. |
| **T.04 — Sector weight** | ICT exports (bases and years labeled — read as orders of magnitude) + workforce headcounts. |
| **T.05 — Pay-transparency tracker** | EU Directive 2023/970 status: all three EU members in the region missed the 7 June 2026 deadline. |
| **Annex** | Full methodology: net/gross conversion ratios per country, FX assumptions, numbered sources, known limitations. |

## Data sources (snapshot: August 2026)

FishingBooker IT Salary Survey (RS, net) · TABU.hr by Bornfight (HR, net) · Slovenian developer survey 2025 by M. Medven (SI, gross) · dev.bg & BASSCOM Barometer (BG) · national statistical offices (RZS, DZS, SURS, Makstat) · Eurostat ICT-specialist series · NBS/The Recursive export data · EU transposition monitors (beqom, Pinsent Masons).

All figures are from public sources, paraphrased/aggregated with attribution. Crowd-sourced surveys skew toward engaged, higher-earning respondents — limitations are documented in the page itself.

## Run it

No build, no dependencies, no tracking. Open `index.html` in a browser. That's it.


## Update the data

All figures live in one clearly marked `DATA` block at the top of the `<script>` in `index.html` (`LADDER`, `RATIOS`, `PREMIUM`, `EXPORTS`, `EMPLOY`, `TRANSPARENCY`). Edit the values, keep the `basis`/source notes honest, refresh.

**Found fresher numbers or an error?** PRs and issues are very welcome — that's the point of putting this in public.

## Disclaimer

Personal open-data project. Not compensation advice, not affiliated with any source cited. Net/gross conversions use national average-wage ratios applied uniformly — a documented simplification (progressive taxation means high IT salaries convert less favorably; contribution caps and allowances are not modeled).

## License

MIT — fork it, correct it, extend it.

---

Built by **Vojislav Vujić** · HR data & analytics · [LinkedIn](https://www.linkedin.com/in/vojislavvujic) · [GitHub](https://github.com/vjslvvjc)
