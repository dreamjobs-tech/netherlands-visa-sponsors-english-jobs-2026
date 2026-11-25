# Recognised Visa Sponsors and English-Speaking Job Ads in the Netherlands, November 2026

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24520893.svg)](https://doi.org/10.5281/zenodo.24520893)

Aggregate counts from live job ads collected by [Qarera](https://www.qarera.com), ads open and seen **November 10 – 24, 2026**.

- 📊 **Full report:** [www.qarera.com/reports/netherlands-visa-sponsors-english-jobs-2026](https://www.qarera.com/reports/netherlands-visa-sponsors-english-jobs-2026)
- 📄 **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use with attribution to Qarera.

## Key findings

- **1,184 IND-recognised sponsors** had live ads: 8,299 of 28,577 Dutch ads.
- **65% of recognised sponsors' ads are in Dutch or ask for Dutch**; 35% are in English without a Dutch requirement (other employers: 18%).
- 167 of 557 sponsors with 3+ live ads have no English ad without Dutch.
- Open to English speakers by city: Amsterdam 39%, Eindhoven 25%, Rotterdam 18%, Utrecht 12%; Munich 32%, Berlin 30%, Leipzig 7%.

## Files

| File | Rows | Description |
|---|---|---|
| `nl-recognised-sponsors-live-ads.csv` | 1,184 | Every IND-recognised sponsor with live ads: ads, English ads without a Dutch requirement, ads asking for or written in Dutch, refusals. |
| `nl-sponsors-vs-other-employers.csv` | 3 | Recognised sponsors vs other employers. |
| `de-nl-by-city.csv` | cities with ≥200 ads | Germany and the Netherlands: share of ads open to English speakers by city. |
| `de-nl-by-job-family.csv` | job families with ≥200 ads | Same by job family. |

Counts are ads, one per job (the same job on a career site and on LinkedIn/Indeed counts once). Percentages are shares of
the ads in that row. No ad text and no personal data are included.

## Methodology and limits

Every open job ad in Qarera's index in the Netherlands (28,577) and Germany (47,675) seen November 10 – 24, 2026, counted once per job. Dutch employers matched by organisation name (legal forms such as B.V./N.V. removed; generic names and agencies skipped) to the IND public register of recognised sponsors for work as published on 2026-11-03 (13,089 organisations); 40 random matches checked by hand were all correct. A brand hiring under a differently named entity is missed, so sponsor counts are a floor. 'Open to English speakers' = written in English and not asking for Dutch/German as a requirement ('a plus' does not count), using the rules of Qarera's English-speaking jobs report.

## Citation

> Qarera (2026). *Recognised Visa Sponsors and English-Speaking Job Ads in the Netherlands, November 2026* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24520893. CC BY 4.0.
