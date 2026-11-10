---
title: "Data"
layout: single
author_profile: true
permalink: /data/
---

Building datasets is a hobby of mine: when the data to answer a question does not exist, I collect and clean it myself. A few of the datasets I have built:

### Wine retail offers: 251,706 records
Parsed from raw retailer listings covering 200 wines across all 51 U.S. jurisdictions. About 1,560 offers were priced per case but recorded as single bottles; those 1.29% of rows drove 62% of the estimated price effect until I found and corrected them.

### Shipping policy corpus
Hand-coded retailer shipping policies, UPS and FedEx alcohol shipping rules, and state statutes, joined to the offer data by retailer and destination state to show which offers could lawfully be delivered.

### Bookmaker price panel: 16 million rows
Five-minute resolution prices from 30 venues around 15 prosecuted manipulation cases, collected through OddsAPI.

### Multi-sport betting line panel: 2.5 million observations
Opening and closing odds, timestamps, and bookmaker identifiers for 943,134 matches across 600+ leagues, collected through a JavaScript scraping pipeline.

### CPS microdata: about 64 million person-records
Extracted from fixed-width files spanning 1976 to 2026, with IND1990 codes mapped to CES supersectors for Bartik instrument construction.

### PSID displacement panel
Built from biennial waves, matching Census occupation codes to O*NET task ratings through Census-to-SOC crosswalks across two code vintages.

### Steam and PCGamingWiki enrichment: 3,938 titles
DRM notices, multiplayer flags, achievement counts, and other controls, matched to PCGamingWiki for DRM classification at a 91.3% match rate.

### OpenAlex publication records: 2,922 publications, 215 authors
Built as a research assistant: publications resolved by ORCID first with an article-title fallback, from a hand-compiled list of 606 U.S. Economics PhD graduates, with duplicate and false-match rates measured rather than assumed.
