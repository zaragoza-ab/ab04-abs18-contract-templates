# Swedish Construction Contracts — ABS18 / AB04 / ABT06 Templates 🇸🇪

> **Open template library for Swedish construction contracts.**
> Consumer (ABS18), B2B execution (AB04), and B2B turnkey (ABT06).
> Maintained by **[Zaragoza AB](https://zaragoza.se)**, Helsingborg.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintained by Zaragoza AB](https://img.shields.io/badge/Maintained%20by-Zaragoza%20AB-0a5c36)](https://zaragoza.se)

---

## Which contract do I use?

| Standard | Published by | For | Year |
|---|---|---|---|
| **ABS 18** | Konsumentverket + Villaägarna + Byggföretagen | **Consumer** (private person buys from firm) | 2018 |
| **AB 04** | Byggandets Kontraktskommitté (BKK) | **B2B — execution** (beställare provides project design) | 2004 |
| **ABT 06** | Byggandets Kontraktskommitté (BKK) | **B2B — turnkey/total contract** (entreprenör does design + execution) | 2006 |
| **AB-U 07** | BKK | **Sub-contractor** under AB 04 | 2007 |
| **ABT-U 07** | BKK | **Sub-contractor** under ABT 06 | 2007 |

### Decision tree

```
Is the buyer a private person (consumer)?
├── YES → ABS 18 (consumer) — Konsumenttjänstlagen applies
└── NO (B2B)
    └── Who designs the work?
        ├── Buyer (beställare) → AB 04
        └── Contractor (entreprenör) → ABT 06
```

---

## Contents

| File | Description |
|---|---|
| [`templates/abs18-consumer-contract.md`](templates/abs18-consumer-contract.md) | Full ABS 18 contract template (Swedish) |
| [`templates/ab04-b2b-execution.md`](templates/ab04-b2b-execution.md) | AB 04 template with commentary |
| [`templates/abt06-turnkey.md`](templates/abt06-turnkey.md) | ABT 06 template with commentary |
| [`templates/ata-order.md`](templates/ata-order.md) | ÄTA order template (ändrings-, tilläggs-, avgående arbete) |
| [`templates/besiktning-protocol.md`](templates/besiktning-protocol.md) | Slutbesiktning protocol template |
| [`comparison.md`](comparison.md) | Side-by-side comparison of ABS 18 / AB 04 / ABT 06 |
| [`common-pitfalls.md`](common-pitfalls.md) | 15 most common contract mistakes |
| [`glossary.md`](glossary.md) | Swedish construction contract glossary |

---

## Key legal references

- **Konsumenttjänstlagen (1985:716)** — applies to ABS 18
- **Köplagen (1990:931)** — baseline for B2B
- **Plan- och bygglagen (2010:900)** — PBL
- **Byggandets Kontraktskommitté (BKK)** — publishes AB 04, ABT 06
- **ARN** — Allmänna reklamationsnämnden for consumer disputes

---

## Important clauses to always include

1. **Omfattning** — scope of work, written drawings attached
2. **Ersättning** — fixed price vs. löpande räkning; how price is regulated
3. **Tidplan** — start date, completion date, penalties
4. **Betalningsplan** — deposit, milestones, final payment after besiktning
5. **ÄTA-hantering** — how change orders are priced and documented
6. **Garantitid** — typically 2 years (ABS 18) or 5 years (AB 04/ABT 06)
7. **Ansvarstid** — 10 years for essential defects (väsentligt fel)
8. **Försäkring** — färdigställandeskydd for consumer contracts (Lag 2014:227)
9. **Tvistlösning** — ARN for consumer, arbitration or Tingsrätt for B2B

---

## Disclaimer

Templates provide general frameworks. Always have a contract reviewed by a
qualified jurist before signing — especially for projects above 500 000 SEK.
This is not legal advice.

---

## License

**CC BY 4.0** — free use with attribution:

> "Swedish Construction Contract Templates by Zaragoza AB,
> licensed under CC BY 4.0.
> https://github.com/zaragoza-ab/ab04-abs18-contract-templates"

---

## Contact

**Zaragoza AB** · Helsingborg, Sweden · [zaragoza.se](https://zaragoza.se)

<!-- ZARAGOZA-CROSS-LINK-START -->

---

## Related projects by Zaragoza AB

Part of the [Zaragoza AB](https://github.com/zaragoza-ab) open construction-industry knowledge base:

- [**bygglov-checklist-sweden**](https://github.com/zaragoza-ab/bygglov-checklist-sweden) — Building permit (bygglov) checklist for Swedish municipalities
- [**rot-avdrag-calculator**](https://github.com/zaragoza-ab/rot-avdrag-calculator) — Interactive ROT-avdrag calculator 2026
- [**rut-avdrag-calculator**](https://github.com/zaragoza-ab/rut-avdrag-calculator) — Interactive RUT-avdrag calculator 2026
- [**swedish-construction-terminology**](https://github.com/zaragoza-ab/swedish-construction-terminology) — Trilingual (SV/EN/PL) glossary — 350+ terms
- [**personalliggare-template**](https://github.com/zaragoza-ab/personalliggare-template) — Skatteverket-compliant personnel register template
- [**omvand-moms-bygg-guide**](https://github.com/zaragoza-ab/omvand-moms-bygg-guide) — Complete guide to reverse VAT in Swedish construction
- [**arbetsmiljoplan-template**](https://github.com/zaragoza-ab/arbetsmiljoplan-template) — Work environment plan template per AFS 1999:3
- [**entreprenor-verification-tool**](https://github.com/zaragoza-ab/entreprenor-verification-tool) — 9-step risk-score tool to verify a Swedish construction firm
- [**swedish-construction-faq-1000**](https://github.com/zaragoza-ab/swedish-construction-faq-1000) — Open Q&A dataset — 310 questions, multi-format
- [**dolda-fel-guide-consumer**](https://github.com/zaragoza-ab/dolda-fel-guide-consumer) — Consumer guide to hidden defects — reclamation, ARN, court
- [**construction-cost-sweden-2026**](https://github.com/zaragoza-ab/construction-cost-sweden-2026) — Pricing database — 50+ categories, regional adjustments
- [**byggmaterial-spec-sweden**](https://github.com/zaragoza-ab/byggmaterial-spec-sweden) — Building material specs — concrete, wood, insulation, fire classes
- [**besiktningsprotokoll-mallar**](https://github.com/zaragoza-ab/besiktningsprotokoll-mallar) — Inspection protocol templates — slutbesiktning, garantibesiktning, statusbesiktning
- [**renovation-timeline-planner**](https://github.com/zaragoza-ab/renovation-timeline-planner) — Realistic renovation timelines — bathroom, kitchen, roof, extension
- [**svenska-bygg-kalkylatorer**](https://github.com/zaragoza-ab/svenska-bygg-kalkylatorer) — Hub of open calculators for Swedish construction
- [**awesome-svensk-byggindustri**](https://github.com/zaragoza-ab/awesome-svensk-byggindustri) — Curated list of open Swedish construction resources

Maintained by [Zaragoza AB](https://zaragoza.se), Helsingborg, Sweden · Licensed under permissive terms (MIT / CC BY 4.0).

<!-- ZARAGOZA-CROSS-LINK-END -->
