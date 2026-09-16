# DI-Weather

A public Grounded DI archive of DI Weather Station and StormWise event records, corridor forecasts, visual comparisons, and weather-oriented prototype artifacts from June through September 2025.

**Published by Grounded DI LLC · Source records identify Grounded DI / MSW · Repository history begins July 24, 2025**

## Overview

This repository preserves a dated public record of how Grounded DI described weather observation, event classification, corridor forecasting, entropy/override logic, and outcome comparison. It includes Markdown case records, PDFs containing screenshots or reports, a small set of map/forecast images, and one cross-domain cyclone record.

The collection is an evidence and prototype archive, not a live forecasting service, meteorological data feed, installable application, or complete source release. The strongest claims below are stated as recorded outputs or documented timelines, with independent validation kept separate.

## Why It Matters

Weather decisions often depend on short lead times, local conditions, and the difference between a broad probability and a specific corridor or hazard state. The artifacts show a control vocabulary built around manual triggers, visual observations, corridor mapping, threshold changes, override paths, and archived comparisons. That makes the repository useful for technical diligence and for scoping a future, qualified proof of concept.

## Evidence Map

| Record | Inspectable evidence | Status in this repository |
| --- | --- | --- |
| **June 19, 2025 tornado-class event** | [`DI_Histroric_Tornado_Detection_6_19_25.md`](DI_Histroric_Tornado_Detection_6_19_25.md) records a manual trigger at 5:17 PM, a DI declaration at 5:18 PM near Landenberg, a heatmap at 5:41 PM, and a cited Delco Times/NWS confirmation at 7:32 PM. [`DI_Tornado_Screenshot_6_19.pdf`](DI_Tornado_Screenshot_6_19.pdf) preserves the displayed service comparison. | **RECORDED TIMELINE / DISPLAYED COMPARISON** — the repository does not include raw radar, Ring, AccuWeather, or runtime data sufficient to independently reproduce the lead-time conclusion. |
| **July 12 StormWise record** | [`StormWise_Report-7-12-25.pdf`](StormWise_Report-7-12-25.pdf) records a still-tower observation, a 6:55–7:30 PM collapse window, rainfall/outflow observations, and a comparison with displayed legacy forecast ranges. | **REPORTED CASE RECORD** — the PDF is a creator-produced report and is not an independent meteorological audit. |
| **July 13 Bonham, Texas discrepancy** | [`DI_Weather_Bonham_TX_7-13-25.pdf`](DI_Weather_Bonham_TX_7-13-25.pdf) and [`Report_Bonham_TX_7-13-25.pdf`](Report_Bonham_TX_7-13-25.pdf) record a 30% public forecast against rainfall observed by radar and at street level; the report explicitly marks `Match: No`. | **RECORDED DISCREPANCY / FAILURE CASE** — useful because the archive preserves a miss rather than presenting only successful forecasts. |
| **July 16 Case 003 lightning record** | [`DI_Storm_Event_Case003_7_16_25.md`](DI_Storm_Event_Case003_7_16_25.md) and [`DI_Storm_Event_Screenshots_Case003_7_16_25.pdf`](DI_Storm_Event_Screenshots_Case003_7_16_25.pdf) preserve a 4:48–7:20 PM timeline involving a tower-cloud observation, a locked forecast, and a reported Jackson Township, New Jersey lightning event. | **RECORDED CASE / SCREENSHOT SET** — the Markdown heading says “June 16” while its date field, filename, and timeline say July 16; this README preserves that discrepancy for review. |
| **July 19 WIPHA-25 pre-landfall record** | The file `Cyclone_Pre_Landfall_Report_HazardWise.md ` (the tracked filename retains a trailing space) describes a pre-landfall comparison of GDACS/JTWC and a DI/StormWise corridor view for inland flood risk. | **PRE-LANDfall RECORD** — the document itself says post-impact validation would follow; no such validation is included here. |
| **August 13 Case 004** | [`StormWise_Case004_The_555_Trigger.md`](StormWise_Case004_The_555_Trigger.md) records a stated risk change from 75% to 85% before reported rain at 5:55 PM in southeastern Pennsylvania. | **REPORTED EVENT RECORD** — no raw forecast feed or independent comparison package is included. |
| **August 15 SE Pennsylvania comparison** | [`DI_Weather-Intell_vs_Legacy_SE-PA_8-15-25.pdf`](DI_Weather-Intell_vs_Legacy_SE-PA_8-15-25.pdf) displays an 83% rain probability, a 92/100 confidence field, and a comparison with displayed 5–24% legacy ranges. | **DISPLAYED COMPARISON** — values are preserved as shown, not independently benchmarked. |
| **Corridor and regional artifacts** | [`StormWise DI2 Corridor Forecast - SE PA.pdf`](<StormWise DI2 Corridor Forecast - SE PA.pdf>), [`Corridor_Forecast_Visual.pdf`](Corridor_Forecast_Visual.pdf), [`SE_PA_frame_000.png`](SE_PA_frame_000.png), [`SE_PA_frame_001.png`](SE_PA_frame_001.png), and [`IMG_7584.jpeg`](IMG_7584.jpeg) show next-48-hour corridors, radar overlays, and localized Exton/West Chester comparisons. | **VISUAL / DOCUMENTARY PROTOTYPES** — no live service or data pipeline is included. |
| **AI risk and third-party commentary** | [`DI_Global_AI_Risk_Matrix_8_15_25.pdf`](DI_Global_AI_Risk_Matrix_8_15_25.pdf) and [`Third-Party GPT Assess Novel Tornado Detection.pdf`](<Third-Party GPT Assess Novel Tornado Detection.pdf>) preserve public positioning and an AI-generated assessment of the June 19 record. | **PUBLIC COMMENTARY** — these files are not independent meteorological review or certification. |

## Technical Model as Depicted

The recurring control path can be summarized as:

```text
Observation, forecast, or alert
        ↓
Manual trigger or StormWise interpretation
        ↓
Corridor / threshold / override logic
        ↓
Displayed forecast, heatmap, or protective classification
        ↓
Outcome comparison and archived case record
```

Project terms used in the records include:

- **DI Weather Station:** the named weather-observation and logic context in the June/July records.
- **StormWise:** the weather-focused system label used for event, corridor, and winter/storm records.
- **Entropy / override:** terminology for divergence between observations, alerts, and a stated logic path.
- **Corridor forecast:** a spatially bounded risk or impact area shown in maps and PDFs.
- **ScrollLock / sealed record:** archival language used to mark a declared state or preserved artifact.

This flow reflects the public documents. It is not evidence that a common executable weather engine is present in this repository.

## What the Record Demonstrates

- The repository preserves dated event narratives with explicit trigger, observation, forecast, and comparison times.
- The June 19 record preserves a manual initiation, an early tornado-class declaration, a later heatmap, and a cited public confirmation; the evidence hierarchy is visible in the source file and screenshot PDF.
- The July 13 Bonham record preserves a negative comparison (`Match: No`), which is an important boundary against presenting the archive as a success-only collection.
- The July 16 screenshot set preserves source observations and a timeline that can be compared with the accompanying narrative.
- Corridor PDFs and PNGs make the intended spatial-output format inspectable even though no live feed or forecast API is included.

These are separate propositions: a recorded forecast, an observed outcome, a model-comparison screenshot, a reproducible runtime, and independent meteorological validation are not interchangeable.

## Validation and Testing

The current tree contains 19 tracked files: 5 Markdown documents, 11 PDFs, and 3 raster images. It has no package manifest, dependency specification, source runtime, test harness, or deployment configuration. No automated weather or forecast test can be rerun from this repository.

Checks performed during this review:

- **PASS — inventory:** all 19 tracked files and the trailing-space filename were inspected;
- **PASS — chronology:** Git history was inspected from July 24 through September 27, 2025;
- **PASS — text and visual review:** Markdown, PDF text layers, PDF screenshots, PNG/JPEG dimensions, and the cited event fields were reviewed;
- **RECORDED — public source reference:** the June 19 Markdown record preserves a Delco Times link for the cited NWS confirmation; and
- **UNVERIFIED — independent validation:** no outside reproduction, raw station/radar dataset, or professional meteorological audit package is included.

The `PASS` labels describe repository inspection, not proof that every forecast or comparison is correct.

## Repository Structure

```text
README.md                                  This evidence index
DI_Histroric_Tornado_Detection_6_19_25.md  June 19 tornado-class event record
DI_Storm_Event_Case003_7_16_25.md          July 16 lightning case narrative
StormWise_Case004_The_555_Trigger.md       August 13 Case 004 narrative
Cyclone_Pre_Landfall_Report_HazardWise.md  Pre-landfall cyclone record (trailing space in name)
*.pdf                                      Screenshots, reports, comparisons, and visual exports
*.png / *.jpeg                             Corridor and local forecast visual artifacts
```

## Quick Start

No package installation is required for an archival review.

```bash
git clone https://github.com/Grounded-DI/DI-Weather.git
cd DI-Weather
git log --reverse --date=iso --stat
git ls-files
```

Start with the June 19 record and screenshot, then compare the July 12–16 case files, the Bonham discrepancy, and the August corridor/comparison artifacts. A standard PDF reader is sufficient; PDF text can optionally be extracted with Poppler:

```bash
pdftotext DI_Weather-Intell_vs_Legacy_SE-PA_8-15-25.pdf -
```

The commands inspect files and history. They do not execute a weather runtime or reproduce a forecast.

## Commercial and Integration Context

The archive can support an initial evaluation of:

- local observation-to-corridor workflows;
- event classification and threshold/override design;
- audit-oriented forecast and outcome records; and
- requirements for a future weather situational-awareness proof of concept.

Potential integration would require a separately validated implementation, current data sources, qualified meteorological review, and acceptance criteria appropriate to the intended use. The public repository does not represent a deployed forecasting service or regulatory product.

Commercial, licensing, and technical inquiries: [contact@groundeddi.ai](mailto:contact@groundeddi.ai)

## Authorship and Provenance

Git history attributes the repository commits to **Grounded DI LLC** using `mark@groundeddi.ai`. The case records and PDFs use Grounded DI / MSW attribution and preserve their original dates, filenames, status labels, and terminology. Git commits, file paths, and embedded timestamps provide chronology and identity evidence; they do not independently establish legal ownership, forecast correctness, or patent priority.

## Intellectual Property and Licensing

Several artifacts use “Patent-Pending” or protected-architecture language. Those phrases are preserved as statements made in the source records. This README makes no claim that a patent issued, remains pending, or has a particular claim scope.

No formal `LICENSE` file is present in the repository. Public access is not an open-source, commercial, regulatory, or modified-redistribution grant beyond any express permission in the repository or a separate written agreement. Copyright and other rights remain with Grounded DI LLC and applicable authors.

## Scope and Limitations

This is a static weather evidence and prototype archive. The public records include manual observations, screenshots, authored comparisons, AI-generated commentary, and declared system outputs. They do not include the underlying weather feeds, source code, forecast model, reproducible runtime, or independent meteorological review needed to establish general forecasting performance.

The repository also preserves internal inconsistencies rather than silently normalizing them: the July 16 Case 003 narrative contains a “June 16” heading, and a separate July 12 PDF also uses the `SW-003` case identifier. These should be resolved in any future formal case registry.

## Citation

Suggested citation:

> Grounded DI LLC, *DI-Weather: Public Weather Station and StormWise Evidence Archive*, GitHub repository created July 24, 2025, cited by commit identifier and access date, https://github.com/Grounded-DI/DI-Weather.

## Related Public Records

- [DI_Principles-](https://github.com/Grounded-DI/DI_Principles-)
- [DI-Engineering](https://github.com/Grounded-DI/Deterministic-Engineering)
- [DI-HazardWise](https://github.com/Grounded-DI/DI-HazardWise)
- [Grounded DI — Deterministic Intelligence](https://github.com/Grounded-DI/deterministic-intelligence)

## Status

**ACTIVE PUBLIC WEATHER RECORD / PROTOTYPE ARCHIVE.** The repository is suitable for historical, technical, provenance, and preliminary commercial review. It is not presented as a live or certified forecasting service.

#DeterministicWeather #StormWise #WeatherIntelligence #RiskModeling #Auditability #Provenance #GroundedDI
