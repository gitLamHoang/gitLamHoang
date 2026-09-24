# A two-minute project tour

Start with a working interaction, then follow the evidence into the code.

## 1. Explore a forecast · 60 seconds

Open the [NYC Mobility Intelligence map](https://gitlamhoang.github.io/nyc-mobility-intelligence/). Choose a zone, move through the historical hours, and compare recorded pickups with the forecast and weekly baseline. Look for a place where the model struggles.

The display contains **12,576 zone-hours: 262 zones × 48 hours**, from April 7–8, 2026 in New York. It is a small historical demonstration, not an estimate of future performance. Its [export record](https://github.com/gitLamHoang/nyc-mobility-intelligence/blob/main/reports/demo_export.json) connects it to saved predictions with content hashes.

For the engineering decisions, read the [walk-forward evaluation](https://github.com/gitLamHoang/nyc-mobility-intelligence/blob/main/reports/WALK_FORWARD_REVIEW.md) and [observation-delay study](https://github.com/gitLamHoang/nyc-mobility-intelligence/blob/main/reports/LATENCY_REVIEW.md). The broader evaluation covers February–April; the two-day display is not the full benchmark. The code separates Python modeling, SQL summaries, and the TypeScript interface.

## 2. Follow a review decision · 30 seconds

Open [Document Date Review](https://github.com/gitLamHoang/pharma-ocr-date-rag) and follow its quickstart. Index the synthetic documents, inspect a candidate date with its source context, then record a review decision. Re-indexing an unchanged document preserves its identity; changed content receives a new version.

The useful question is whether a reviewer can trace a decision back to the document—not whether every extracted date looks plausible. The public fixture demonstrates behavior on a small, synthetic set; it does not establish extraction accuracy on a real document population.

## 3. Check who is held out · 30 seconds

Open [EEG State Classifier](https://github.com/gitLamHoang/Classfying-brain-wave-state) and follow the grouped evaluation example. Inspect how participant identities separate training from evaluation, including during parameter tuning.

Nearby windows from the same participant can be too similar to support a useful generalization claim. The synthetic demonstration verifies the split and pipeline mechanics; independent participant data would be needed to measure real performance.

## Go deeper

Each repository includes setup commands, tests, limitations, and source code. These are independent learning prototypes at different stages, with their evidence boundaries stated explicitly. Questions about actual users, operational feeds, and deployment requirements remain part of the work ahead.
