---
title: "Research & Projects"
layout: single
author_profile: true
permalink: /research/
---

## Featured Projects

### State Shipping Bans and Wine Market Access
 
*Thirty-eight states close the interstate retailer channel. Consumers there pay more — but no retailer charges them more, and the constraint is applied through private carrier contracts rather than by the states directly.*
 
Thirty-eight of the fifty-one U.S. jurisdictions bar out-of-state retailers from shipping wine to consumers. The figure is often reported as far smaller, because most sources describe the *winery* regime: winery direct shipping is lawful in 49 of 51 jurisdictions, out-of-state retailer shipping in 13. The two are separate systems, and a state's position in one predicts little about the other.
 
Using 251,706 retail offers for 200 wine-vintages, collected across all 51 jurisdictions in mid-2026, I find that retailers post national prices: 89.5% of multi-state retailer–wine pairs carry an identical posted price in every state served, and within a wine, retailer identity accounts for 42.6% of price variance against 0.2% for the destination. Nobody is charging closed-state consumers more.
 
They pay more anyway, because the price a consumer pays is the lowest one available rather than the average one posted. Where out-of-state retailers may ship, 36% more retailers reach a given wine in a given state, and the best available price falls accordingly. Conditional on that count, openness carries no further price advantage — the entire difference runs through participation. About nine-tenths of the price gap between open and closed states is composition rather than pricing, on two independent estimators.
 
Prohibition cuts the probability that a retailer serves a state by 13.7 points. Retailers who do serve a closed state list just as many wines there as anywhere else — there is no assortment curation, only a participation decision.
 
**Listing is not delivery.** Merchant domicile makes lawfulness observable offer by offer, and the closed-state menu turns out to be largely notional: in states permitting only their own retailers to ship, 3.6% of listed offers may lawfully reach the buyer; where retailer shipping is barred outright, none may. Where a lawful source exists it is usually a single seller — the median such case has exactly one, against nine where the channel is open — and the best available price there is 20% higher. Measured on listings alone the gap looks like two percent; measured on what can actually arrive, it is an order of magnitude larger.
 
**Who enforces it.** A state's instrument against a retailer is the licence, exercised through inspection and revocation, and that is empty against a firm holding no licence there. What the state can reach is the carrier. UPS and FedEx each condition alcohol carriage on a signed agreement, restrict it to a published list of states, disclaim any duty to interpret the law, and reserve the right to destroy non-compliant shipments. The states remain the enforcers; the carriers are the instrument. This is gatekeeper liability in Kraakman's sense — a third party enlisted to police conduct the enforcer cannot reach directly — and because the compliance matrices are published documents, the enforcement boundary can be observed and its market consequences measured. Of 52 retailer policies I hand-coded, 28 pass title at origin, placing the residual loss on the buyer by contract.
 
**Data construction:** 251,706 offers parsed from raw HTML, with multi-bottle lots and non-standard formats separated from single bottles by reading each offer's format badge; 65 merchant shipping policies and the governing UPS and FedEx tariffs and addenda hand-coded to establish the compliance chain end to end; retailer domicile matched to destination to determine lawfulness offer by offer.
 
**Legal context:** *Granholm v. Heald* (2005) and *Tennessee Wine v. Thomas* (2019) left the retailer question open. Both circuits to reach it — *Lebamoff* (6th Cir. 2020) and *B-21 Wines* (4th Cir.) — sustained the restriction, differing in reasoning rather than outcome.
 
**Methods:** Nested fixed effects; decomposition of the price gap into participation and pricing margins; a wine-level counterfactual price index; mediation of the best available price through retailer count; linear probability models; wine-clustered bootstrap.

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

I built a 16-million-row price panel at five-minute resolution across 30 venues around 15 prosecuted manipulation cases, then tested how bookmakers responded using a triple-difference design with fixed effects and exact tests suited to a 16-case sample.

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
