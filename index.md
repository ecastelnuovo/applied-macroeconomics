---
layout: default
title: Empirical Methods in Macroeconomics
---

# Empirical Methods in Macroeconomics

**Efrem Castelnuovo** · University of Padova · Master and PhD level

Lecture slides and replication codes for a course on Vector Autoregressions (VARs):
specification and estimation, Bayesian priors, identification of structural shocks,
counterfactuals, local projections, and historical decompositions.

## Lectures

| # | Topic | Main references | Slides | Code |
|:-:|:------|:----------------|:------:|:----:|
| 1 | **Reduced-form VARs**<br><small>Specification, lag selection and truncation bias, stationarity, breaks, informational sufficiency, FAVARs</small> | Sims (1980); Bernanke, Boivin, Eliasz (2005); De Graeve, Westermark (2025) | [PDF](slides/01_Reduced_form_VAR.pdf) | – |
| 2 | **Priors for VARs: a primer**<br><small>Minnesota, sum-of-coefficients and single-unit-root priors; hierarchical priors; priors for the long run; application to a monetary VAR</small> | Doan, Litterman, Sims (1984); Giannone, Lenza, Primiceri (2015, 2019) | [PDF](slides/02_Priors_VAR.pdf) | – |
| 3 | **Cholesky VARs**<br><small>Recursive identification, IRFs, FEVDs, historical decompositions, internal-instrument VARs vs LP-IV</small> | Christiano, Eichenbaum, Evans (1999, 2005); Stock, Watson (2001); Plagborg-Møller, Wolf (2021) | [PDF](slides/03_Cholesky_VAR.pdf) | – |
| 4 | **Sign restrictions**<br><small>Set identification, rotations, a bivariate example, monetary policy shocks</small> | Faust (1998); Canova, De Nicolò (2002); Uhlig (2005, 2017); Fry, Pagan (2011) | [PDF](slides/04_Sign_restrictions_VAR.pdf) | – |
| 5 | **Refinements to sign restrictions**<br><small>Narrative restrictions, policy coefficient restrictions, penalty function approach, ratio restrictions</small> | Antolín-Díaz, Rubio-Ramírez (2018); Arias, Caldara, Rubio-Ramírez (2019); Caldara et al. (2016) | [PDF](slides/05_Refinements_sign_restrictions_VAR.pdf) | – |
| 6 | **Counterfactuals**<br><small>Policy counterfactuals in VARs and the Lucas critique</small> | Sims, Zha (1995); McKay, Wolf (2023) | [PDF](slides/06_Counterfactuals_VAR.pdf) | – |
| 7 | **Local projections or VARs? It's all in the lags**<br><small>Bias-variance trade-off, long-lag VARs, LPs as VARs of increasing order</small> | Montiel Olea, Plagborg-Møller, Qian, Wolf (2025); Baumeister (2025); Ludwig (2024) | [PDF](slides/07_Comparison_LP_VAR.pdf) | – |
| 8 | **The historical decomposition roller coaster**<br><small>Deterministic components, whimsical historical decompositions, the single-unit-root prior, drivers of post-covid inflation</small> | Bergholt, Canova, Furlanetto, Maffei-Faccioli, Ulvedal (2026) | [PDF](slides/08_Historical_decomposition_rollercoaster_VAR.pdf) | – |

Replication codes will be added progressively in the [`code`](code/) folder.

## Using these materials

Feel free to use and adapt these materials for teaching and research, with attribution.

- **Slides:** [Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).
- **Code:** [MIT License](LICENSE.md).
- **Third-party figures:** figures reproduced from published papers are used for teaching purposes, with full attribution, and remain the property of their respective copyright holders. They are not covered by the licence above.

Comments, corrections, and suggestions are welcome: please open an [issue](https://github.com/ecastelnuovo/applied-macroeconomics/issues).
