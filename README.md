# BBS Calculator

A free, offline, single-file Bar Bending Schedule (BBS) calculator for Indian construction practice — built for real site use on a viaduct pier cap, but generic enough for any RCC member.

**Use it:** download [`src/bbs-calculator.html`](src/bbs-calculator.html) and open it in any browser (phone or laptop). No install, no internet, no dependencies. Work autosaves in the browser; projects can be saved/shared as `.json` files.

## Features

- **Cutting lengths per IS 2502 / SP-34** — shape library (straight, L, U, crank with the 0.42D rule, closed stirrup, circular ring, spiral/helix, chair, custom segments), hook allowances, bend deductions (1d/2d/3d/4d), round-up to 25 mm (IS 2502 Cl. 5.1.1)
- **Auto laps** from stock length (default 12 m), lap factor per bar (e.g. 35d/50d per IRC:112 favourable/unfavourable bond)
- **Payable vs procurement weight** — MoRTH Cl. 1608 billing basis (excludes laps) shown separately from ordering tonnage (includes laps + wastage % + rolling margin %)
- **IS 1786 nominal masses** for billing weight (d²/162 fallback)
- **Dimensioned SVG sketch of every bar**, on screen and in print
- **Cutting plan** — first-fit-decreasing nesting into stock bars, per diameter: bars to buy, cut map per bar, utilization and waste %
- **Audit warnings** — laps on >32 mm bars (use couplers, IRC:112 15.2.6), bars longer than stock without laps, duplicate marks
- **Formal A4-landscape print sheet** with project header, dia-wise summary and signature blocks
- **CSV export** for Excel, JSON project save/load
- Every rule is editable in Settings; built-in Help (formulas with code clauses) and a step-by-step usage Guide — no coding needed to adapt it

## Disclaimer

This is a draft estimation aid, **not a substitute for an approved Bar Bending Schedule**. All quantities must be verified by a qualified engineer against issued-for-construction drawings before procurement or billing.
