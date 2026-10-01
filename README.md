# Biochar Potassium Explorer

**[Open the Explorer](https://american-biochar-institute.github.io/potassium-explorer/)**

Biochar keeps most of the potassium in its source biomass, so potassium content depends on the
feedstock: wood biochar is lowest, and crop-residue, food-waste, digestate and manure biochars carry
several times more. The practical question for a nutrient plan is how much of that potassium a crop
can count on in the first year.

This is every potassium value the American Biochar Institute has extracted from its reference
library, plus 43 commercial products measured for the USDA-ARS Biochar Atlas, with the feedstock,
the reagent that measured each value, and the study it came from. Filters recompute the statistics,
and each figure states what its data will and will not support.

## Who it is for

Producers and agronomists, biochar manufacturers, researchers, and nutrient-planning staff who need
the underlying numbers rather than a summary. It was assembled to support ABI's comments on the
proposed revision of USDA-NRCS Conservation Practice Standard 336, Soil Carbon Amendment (Docket
NRCS-2026-0100), and in particular the potassium default in the NRCS Soil Carbon Amendment
calculator.

## What is in it

`index.html` is self-contained: one file, no build step, and it opens offline in any browser.

| View | What it shows |
|---|---|
| Total potassium by feedstock | One mark per biochar, log scale |
| What each reagent recovers | Extractable potassium by reagent |
| How much of a biochar's potassium a reagent recovers | Extractable as a percent of the same biochar's total |
| What to credit in year one | Reagent shares, release studies and crop uptake, with ABI's proposed factors |
| How much potassium an application delivers | Pounds of K₂O per acre at a chosen rate |

## The evidence base

- 316 literature biochars with a total potassium value, from 64 published sources
- 43 USDA-ARS Biochar Atlas products; published values average two laboratories
- 66 paired extractable and total values, 7 release measurements and 1 crop-uptake value
- Every literature value was checked against its source for the number, the method and the
  reporting basis

## Conversion used throughout

```
lb K2O/acre = total K (mg/kg dry) x dry short tons/acre x 0.0024092
```

where `0.0024092 = 2000 x 1.2046 / 1e6`.

## Proposed year-one factors

To replace the calculator's single 100 percent, ABI proposes provisional factors: 30 percent for
wood, 50 percent for crop-residue, food-waste, manure and digestate chars, and 10 percent for
biosolids chars. Potassium carries no conservation adjustment because it has no water-quality risk
standard. Some remaining potassium may be released later; timing, field retention and crop recovery
remain uncertain. ABI's Quick Guide uses these values.

## What this does not establish

Few studies report paired extractable and total potassium, so the factors are preliminary, not
established coefficients. The one crop-uptake value is 62 or 75 percent depending on how its
fertilizer rate is read. Many literature values do not state a moisture basis and are treated as dry,
which is an assumption. The USDA-ARS potassium method is still being confirmed with the Atlas team.
A further 215 values from 33 papers are awaiting a second reader and are not yet included.

## Related explorers

- [Biochar Phosphorus Explorer](https://github.com/American-Biochar-Institute/phosphorus-explorer)
- [Biochar Nitrogen Explorer](https://github.com/American-Biochar-Institute/nitrogen-explorer)

## Reuse and corrections

Figures may be reproduced with attribution. Please cite the page and the date it was built, since
the dataset is revised as more of the library is read.

> American Biochar Institute. Biochar Potassium Explorer. Built September 30, 2026.
> https://github.com/American-Biochar-Institute/potassium-explorer

Corrections and additions are welcome: open an issue, or write to info@biochar.org.

## About

The American Biochar Institute is a 501(c)(3) nonprofit developing standards and markets for
biochar across agricultural, industrial, and built-environment sectors.
[biochar.org](https://biochar.org)
