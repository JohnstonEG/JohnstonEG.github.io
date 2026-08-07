---
title: "Data"
layout: single
author_profile: true
permalink: /data/
---

Most of my projects start the same way: the dataset needed to answer the question doesn't exist, so I build it. Below is what I've constructed, how, and what each one made possible.

### Wine retail offers — 251,706 records
Parsed from 10,198 raw Wine-Searcher result pages covering 200 wines across all 50 states. Required detecting multi-bottle lot pricing from format badges — roughly 36% of offer cards are lots rather than single bottles, and reading them as singles produces a price effect that is almost entirely artifact.

### Merchant and carrier policy corpus — 65 policies, 35 merchants
Hand-coded shipping policies, UPS and FedEx alcohol tariffs, and state statutes from NCSL, joined to the offer data by merchant identity and destination state. Establishes the compliance chain from statute through carrier to consumer.

### Bookmaker price panel — 16 million rows
Five-minute resolution prices from 30 venues around 16 prosecuted manipulation cases using OddsAPI.

### Multi-sport betting line panel — 2.5 million matches
Opening and closing odds, timestamps, and bookmaker identifiers across 600+ leagues, collected via a JavaScript scraping pipeline from OddsPortal.

### CPS microdata — approximately 64 million person-records
Extracted from fixed-width files spanning 1976–2026, with IND1990 codes mapped to CES supersectors for Bartik instrument construction.

### PSID displacement panel
Built from biennial waves, matching Census occupation codes to O*NET task ratings through Census-to-SOC crosswalks across two code vintages.

### Steam and PCGamingWiki enrichment — 3,938 titles
DRM notices, multiplayer flags, achievement counts, and 47 control variables, matched to PCGamingWiki for DRM classification at a 91.3% match rate.

### OpenAlex publication records — 2,922 publications, 215 authors
Resolved ORCID-first with article-title fallback, from a hand-compiled frame of 606 U.S. Economics PhD graduates.
