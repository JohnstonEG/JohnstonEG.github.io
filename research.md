---
title: "Research & Projects"
layout: single
author_profile: true
permalink: /research/
---

## Featured Projects

### State Shipping Bans and Wine Market Access

*How thirty-five states restrict direct wine shipping — and why the binding constraint turns out to be private carrier contracts rather than the statutes themselves.*

Thirty-five states bar out-of-state retailers from shipping wine to consumers. The standard argument against those bans assumes they raise prices. They barely do. Using 251,706 retail offers parsed from 10,198 pages covering 200 wines across all 50 states, I find that roughly 80% of the price gap between prohibited and permitted states is reproduced by merchant presence alone — almost nobody charges more, but fewer sellers reach you.

The mechanism is a participation margin, and it is not enforced by the state. A prohibited state's only lever is license revocation, which is empty against a firm that holds no license there. The binding sanction is a private carrier refusing or destroying the package, and 54% of the merchant policies I hand-coded push that loss onto the buyer by contract through title-at-origin terms.

Prohibition cuts the probability that a merchant serves a state by 13.7 points. Merchants who do serve a prohibited state list just as much — there is no assortment curation, only a participation decision.

**Data construction:** 251,706 offers parsed from raw HTML; 65 merchant shipping policies and the governing UPS and FedEx tariffs hand-coded to establish the compliance chain end to end; state statutes coded from NCSL.

**Legal context:** *Granholm v. Heald* (2005), *Tennessee Wine v. Thomas* (2019), and the live circuit split between *Lebamoff* (6th Cir.) and *B-21 Wines* (4th Cir.).

**Methods:** Nested fixed effects, decomposition of price gaps into participation and pricing margins, linear probability models, counterfactual reweighting.

---

### Mentor–Mentee Matching System

*A two-sided assignment mechanism built for a grant-funded departmental mentorship program.*

I formulated mentor assignment as a capacitated bipartite matching problem and solved it exactly with the Hungarian algorithm, with a bottleneck-assignment variant that maximizes the quality of the worst pairing rather than the total. Running both makes the efficiency–equity trade-off visible instead of assumed.

Preferences are elicited as partial rankings across research interests, career paths, and support needs, weighted by an inverse-frequency transform that down-weights items nearly everyone selects. The whole tool is a single self-contained page — participant data never leaves the operator's machine.

I also designed the survey instruments, the mentor agreement, and the program's communication protocol.

**Methods:** Hungarian algorithm, bottleneck assignment, bipartite maximum matching, inverse-frequency weighting.

---

## Research Papers

### Detection and Dealer Response in Prosecuted Market Manipulation Cases

*What do market makers do when they learn a contract has been manipulated?*

I built a 16-million-row price panel at five-minute resolution across 30 venues around 16 prosecuted manipulation cases, then tested how bookmakers responded using a triple-difference design with fixed effects and exact tests suited to a 16-case sample.

Firms withdrew the manipulated contract entirely rather than widening margins — the reverse of the documented response to insider trading in equities, where dealers price the risk instead of exiting.

**Methods:** Triple-difference with fixed effects, exact inference for small case counts, event-window construction.

---

### Service Quality and Digital Piracy: Evidence from Denuvo DRM

This paper estimates the effect of anti-piracy DRM on piracy demand using a leave-one-out publisher Denuvo adoption instrument with publisher fixed effects. The preferred IV specification finds that DRM increases active piracy demand while having little effect on piracy supply, consistent with piracy communities responding more strongly to perceived service quality than enforcement itself.

---


## Research Interests

- Industrial organization and market structure
- Regulation, enforcement, and compliance
- Digital markets and platform economics
- Market design and matching
- Applied econometrics and novel data construction
