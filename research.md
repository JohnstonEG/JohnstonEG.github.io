---
title: "Research"
layout: single
author_profile: true
permalink: /research/
---

## Featured Project

### Synthetic Derivatives on Sports Betting Markets

*Pricing and backtesting derivative-like instruments on bookmaker implied probabilities using 2.52 million observations across 14 sports (2013–2024).*

This project develops a quantitative framework for pricing and backtesting synthetic derivative instruments written on sportsbook implied probability movements. Using bookmaker opening and closing odds across 943,000+ matches, I construct and evaluate options, spreads, variance swaps, and volatility-sensitive instruments on the line-movement process itself.

The project combines large-scale data engineering, econometric analysis, and quantitative finance methods. I estimate line-movement distributions using nonparametric KDE Monte Carlo methods alongside Bachelier and Student-t pricing frameworks, evaluate implied volatility structures, analyze post-PASPA market microstructure changes, and test derivative-augmented portfolio strategies using rolling-window backtesting and Monte Carlo risk simulation.

A companion C# / .NET risk engine performs portfolio stress testing, VaR/CVaR analysis, volatility scenario modeling, and regime-switching simulations using calibrated market distributions exported from the Python research pipeline.

**Methods:** Kernel density estimation, Monte Carlo simulation, implied volatility modeling, portfolio optimization, volatility clustering analysis, rolling-window backtesting, regime analysis

**Tools:** Python, C#, .NET, pandas, NumPy, SciPy, statistical modeling, data pipelines

[GitHub Repository](https://github.com/JohnstonEG/sports-betting-derivatives)

---

## Research Papers

### Displacement and Task Reallocation: Evidence from the PSID
with Ali Yousuf (Illinois State University)  
*Draft available upon request*

This paper examines how displaced workers reallocate across task types following involuntary job loss. Using plant closures as a natural experiment in the Panel Study of Income Dynamics matched with O*NET task measures, we estimate the causal effect of displacement on task composition using a difference-in-differences framework with Callaway-Sant'Anna estimators, propensity score matching, and inverse probability weighting.

---

### Sports Betting Legalization Spillover Effects in International Betting Markets
*Presented at the Midwest Economics Association (2026) and Illinois Economics Association (2025)*

This paper investigates whether the repeal of PASPA generated spillover effects in international betting markets. Using a dynamic difference-in-differences framework on 73,652 bookmaker-sport-league-month observations across European sportsbooks from 2013 to 2024, I decompose bookmaker margins into multiple components and estimate how U.S. legalization affected pricing efficiency and market behavior abroad.

---

## Works in Progress

### Service Quality and Digital Piracy: Evidence from Denuvo DRM

This paper estimates the effect of anti-piracy DRM on piracy demand using a leave-one-out publisher Denuvo adoption instrument with publisher fixed effects. The preferred IV specification finds that DRM increases active piracy demand while having little effect on piracy supply, consistent with piracy communities responding more strongly to perceived service quality than enforcement itself.

---

### Displacement and Task Composition: A Macroeconomic Perspective

This project extends Jaimovich and Siu (2020) using a Bartik shift-share local projections IV framework on CPS data spanning 1976–2026. Using state-level industry employment shares mapped to CES supersectors, I examine the persistence and macroeconomic dynamics of task reallocation following labor market shocks.

---

## Research Interests

- Labor economics
- Industrial organization
- Digital markets and platform economics
- Market microstructure
- Applied econometrics
- Quantitative risk systems
- Market design and information aggregation
