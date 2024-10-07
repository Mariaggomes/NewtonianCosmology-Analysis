# Newtonian Cosmology and Comparative Analysis with Observational Data

## Objective of the Analysis

This project was developed during a undergraduate research at the National Observatory, under the supervision of Dr. Rodrigo Von Martens. The goal of this analysis is to verify how different cosmological models based on Newtonian cosmology fit the observational data. The focus is on evaluating the expansion of the universe using the Hubble parameter H(z), the growth rate f(z), and the cosmological perturbations (delta), using the Newtonian formalism to explore the perturbations and the cosmological background.

## Details of the Analyses Performed in the Code

### 1. Reading of Observational Data for \( H(z) \)

Observational data for H(z) is used, which describes the expansion rate of the universe at different epochs through redshifts (z). The data is compared with theoretical predictions for different components of the universe, such as matter (w = 0), radiation (w = 1/3), and cosmological constant (w = -1).

**Result**: The cosmological constant dominates in recent eras, while matter dominated in earlier epochs, but the model with a single fluid does not describe the data well.

### 2. Comparison of Models with Observational Data

The function `Hubble_two` is used to fit the H(z) data for a universe composed of two fluids (matter and cosmological constant). Several values of Omega_m are tested, showing how the combination of matter and cosmological constant fits the data.

**Result**: The best fit was obtained for Omega_m approx 0.29, using the chi^2 minimization method. Approximately 29% of the universe's energy content is composed of matter.

### 3. (chi^2) Analysis for Cosmological Fits

The chi^2 was calculated for different values of Omega_m, showing that Omega_m = 0.29 provides the best fit. The likelihood function was plotted, validating the fit.

**Result**: The minimum chi^2 was approximately 14.87, suggesting a good fit between the data and the model.

### 4. Growth Function and Cosmological Perturbations

The growth function D(a) describes the evolution of density fluctuations in the universe. The code numerically solves the differential equations for the density contrast delta for different values of Omega_m.

**Result**: The higher the matter density, the faster the evolution of density fluctuations.

### 5. Growth Rate f(z)

The growth rate f(z), which describes how quickly density fluctuations grow, is compared between observational data and theoretical predictions.

**Result**: Models with Omega_m = 0.7 and Omega_m = 0.9 fit the data well, confirming the validity of the Lambda CDM model.

### 6. MCMC Analysis (Markov Chain Monte Carlo Method)

The Metropolis-Hastings algorithm is implemented to adjust cosmological parameters. The posterior probability function is maximized to find the best value of Omega_m.

**Result**: The average value obtained for Omega_m was Omega_m approx 0.2918, with a standard deviation of approximately 0.028.

## Final Conclusions

1. **Validation of the Lambda CDM Model**: The Lambda CDM model, which combines matter and cosmological constant, provides a robust fit to the observational data. The value of Omega_m approx 0.29 is consistent with current estimates.

2. **Reproduction of Relativistic Results**: The Newtonian approach was effective in reproducing results consistent with relativistic models, both for the cosmological background and for perturbations.

3. **Cosmological Perturbations and Structure Formation**: The analysis of cosmological perturbations confirmed the expected behavior of density fluctuations and their relationship with structure formation in the universe.

## Author
This project was developed by Maria Gabriela Gomes. For more information or to connect, please visit my [LinkedIn profile](https://www.linkedin.com/in/maria-gabriela-gomes-27097431b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app).
