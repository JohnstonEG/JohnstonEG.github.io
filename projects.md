---
title: "Projects"
layout: single
author_profile: true
permalink: /projects/
---

## Bank Management Simulation

*President and CEO of a simulated bank, Banking Fundamentals coursework, Stephen F. Austin State University, Fall 2024*

I led a five-person executive team, with vice presidents for lending, deposits, securities, and treasury, through a simulated recession and recovery on the American Bankers Association Bank Management Simulation.

- **Credit:** tightened credit standards ahead of the forecast recession, which cut the loan loss provision in half.
- **Funding:** shifted borrowing from federal funds at 3.08% to repurchase agreements at 2.91%, reducing borrowed federal funds from $77.2 million to $36.3 million over two quarters.
- **Capital:** when total risk-based capital fell to the 8.0% minimum, rebuilt it by cutting the dividend per share from $0.25 to $0.15 and issuing $5 million in subordinated debt.
- **Earnings:** net interest margin rose for four consecutive quarters.

I wrote the president's strategy report each quarter, covering returns, margin, growth, and capital.

---

## Student Investment Fund

*Financial and Technology Sector Analyst, Stephen F. Austin State University, 2024 to 2025*

I covered the financial and technology sectors for a student-managed portfolio of about $900,000.

- Built a multi-factor Excel valuation model on 159 technology firms from FactSet data. Price-to-sales was regressed on net income margin, forecast sales growth, firm size, beta, and R&D intensity; the model explained about half the variation and flagged firms trading well above or below their fundamentals.
- Screened 221 financial-sector firms on price-to-book against forward return on equity, earnings growth, and beta.
- Recommended a 25 basis point technology overweight in a 15-slide sector analysis.
- Presented fund performance to the university Board of Regents with the analyst team.

---

## Mentor and Mentee Matching System

*Built for a grant-funded departmental mentorship program, Illinois State University, 2026*

Mentors said whether they could take one or two mentees; every mentee needed exactly one mentor; every mentor needed at least one mentee. Within those limits, the tool finds the pairing with the best overall fit, and a second version maximizes the fit of the worst-matched student instead. Showing both lets program leadership see the trade-off and decide it, rather than leaving it to the algorithm.

Preferences come from ranked survey responses, and the tool runs as a single self-contained page, so participant data never leaves the operator's computer. I also designed the survey instruments, the mentor agreement, and the program's communication protocol.

**Methods:** Hungarian algorithm (capacitated assignment), bottleneck assignment.

---

## Educational Games

### Space Pirate Statistics

*Browser game built for ECO 138, Illinois State University, 2026*

The player is an accountant kidnapped by space pirates, and the captain wants numbers before every raid: odds, intervals, and test results. Each job is worked at a desk of monitors holding the request, statistical tables, a calculator, and reference sheets. The player answers the quartermaster and then makes the call on whether to raid. Faster correct answers earn more plunder, finishing with 90% accuracy or better makes the player captain of the ship, and three fully missed jobs in a row send the player out the airlock.

The jobs cover an introductory statistics course: the Empirical Rule, probability from two-way tables, counting, expected value and variance, binomial and normal distributions, the sampling distribution of the mean, confidence intervals and sample size, z and t tests, Type I and Type II errors, two-sample and two-proportion tests, and correlation. Every job is generated with fresh numbers, a worked solution follows a miss, and every answer key is checked against an independent Python verifier.

It runs in any modern browser, with a guided tutorial and an untimed practice mode.

[Play Space Pirate Statistics](https://johnstoneg.github.io/space-pirate-statistics/)
