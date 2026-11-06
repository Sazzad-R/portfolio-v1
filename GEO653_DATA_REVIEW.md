# GEO 653 — Quality review for public research portfolio

**Project:** The Padma Corridor as a Spatial Transformer: A Remote Sensing Analysis of LULC Change of Southern Bangladesh.

## What was integrated

- Original maps extracted from the GEO653.pptx and GEO653_report(2).pdf uploads.
- The scope, three classes, supervised classification workflow, training/testing split, validation summary, comparison with nighttime lights/accessibility, and methodological limitations.
- Top five vegetation-to-impervious conversion rates as given in the report (Batiaghata 31.17%; Paikgachha 22.48%; Morrelganj 16.82%; KCC Kotwali 15.18%; Dumuria 14.05%).
- Both report and slides are available in the package for source transparency.

## Discrepancy needing source-data review before public launch

The report's Table 1 places 2017 impervious area at **2,306.2413 km²** and 2025 impervious area at **3,081.1237 km²**, implying a **774.8824 km² gain**.

The presentation's earlier table instead places 2017 impervious area at **3,256.3166 km²**, 2021 at **2,306.2413 km²**, and 2025 at **3,081.1237 km²**; from those entries alone, 2017–2025 would be **-175.1929 km²** net. The 2017 area in the report appears to equal the 2021 value in the presentation.

Until the classified rasters and area summaries are reconciled, do not present an absolute net change in impervious surfaces as validated. The website withholds this aggregate change, and does not invent replacement values.

## Research interpretation

A visual relationship between land-cover conversion, nighttime light and modeled accessibility is not evidence of independent causal impact. Aggregate map comparisons do not independently measure economic growth or isolate the Padma Bridge from other influences. The 90.9% accuracy and Kappa ≈ 0.86 are reported validation results only; no raw samples were supplied to independently verify them.

## Suggested next verification

Re-export area summaries for 2017, 2021, 2025 from the classified rasters, check class-value mappings and projection/resolution, and confirm whether the conversion-rate denominators and sample designs match between years. Revise the report tables, slides and website together.
