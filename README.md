# Tutuila_IFD_Bayesian
This repository contains Bayesian calibration models and results presented in Morrison,A.E., DiNapoli, R.J., Allen, M.S., Rieth, T.M. (in press) "Application of the Ideal Free Distribution Model to Pacific Island Settlement Patterns: A Case Study from Tutuila Island, American Sāmoa", a chapter in the forthcoming volume _Theoretical Approaches to Prehistoric Coastal Adaptations: Global Perspectives on Evolutionary Ecology at the Coastal Margins_, Thakar, H., Flores, C. (eds). Gainesville: University Press of Florida.


## Bayesian models

All Bayesian models were conducted in OxCal v. 4.4.2. OxCal code and results files are located in the OxCal_code directory. For each Land Unit (LU) we created a single-phase model to estimate the timing of initial settlement, which is provided by the `Boundary` Start range for each model. All Tutuila radiocarbon dates were calibrated using the IntCal20 radiocarbon calibration curve (Reimer et al. 2020), and all unidentified charcoal dates are modeled as charcoal outliers using an `Outlier_model` following Dee and Bronk Ramsey (2014). Note that these models rely on the Reef/Santa Cruz Islands colonization estimate from Sheppard et al. (2015) as a prior for the Tutuila land-unit start boundaries. This  required updating the paired charcoal-shell delta R from Sheppard et al. (2015) for Marine20 (Heaton et al. 2020). To do this we calculated the delta R using methods outlined in Reimer and Reimer (2017) using the online delta R application available at http://calib.org/JS/JSdeltar20/ using the “Radiocarbon Dated Nohem” method. Marine radiocarbon age and marine radiocarbon sigma were set to 3137 ± 24 (the CRA of NZA-53598, Trochus sp. shell) and 14C BP and 14C uncertainty were set to 2768 ± 15 (CRA of NZA-53697, charcoal from within Trochus shell). This resulted in an updated delta R of -93 ± 36. The updated colonization estimate for the Santa Cruz Islands (from Nanngu (SE-SZ-8)) is 3005-2780 cal BP (95.4% HPD, rounded out 5 years). We then exported the Boudary Start estimate for this model as `.prior` file and used this as a prior on the Boundary Start estimates for each Land Unit model. To examine the probability that any given Land Unit was settled before another, we used OxCal's `Order()` query.

## References

Dee MW, Bronk Ramsey C (2014) High-Precision Bayesian Modeling of Samples Susceptible to Inbuilt Age. Radiocarbon 56:83–94. https://doi.org/10.2458/56.16685

Heaton TJ, Köhler P, Butzin M, et al (2020) Marine20—The Marine Radiocarbon Age Calibration Curve (0–55,000 cal BP). Radiocarbon 62:779–820. https://doi.org/10.1017/RDC.2020.68 

Reimer PJ, Austin WEN, Bard E, et al (2020) The IntCal20 Northern Hemisphere Radiocarbon Age Calibration Curve (0–55 cal kBP). Radiocarbon 62:725–757. https://doi.org/10.1017/RDC.2020.41

Reimer RW, Reimer PJ (2017) An Online Application for ΔR Calculation. Radiocarbon 59:1623–1627. https://doi.org/10.1017/RDC.2016.117

Sheppard PJ, Chiu S, Walter R (2015) Re-dating Lapita Movement into Remote Oceania. Journal of Pacific Archaeology 6:26–36

