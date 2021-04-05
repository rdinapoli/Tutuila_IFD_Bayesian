# Tutuila_IFD_Bayesian
This repository contains Bayesian calibration models presented in Morrison,A.E., DiNapoli, R.J., Allen, M.S., Rieth, T.M. (in press) "Application of the Ideal Free Distribution Model to Pacific Island Settlement Patterns: A Case Study from Tutuila Island, American Sāmoa"

## Bayesian models

All Bayesian models were conducted in OxCal v. 4.4.2. All Tutuila radiocarbon dates were calibrated using the IntCal20 radiocarbon calibration curve (Reimer et al. 2020), and all unidentified charcoal dates are modeled as charcoal outliers following Dee and Bronk Ramsey (2014). Code and results files are located in the OxCal_code directory.

Note that these models rely on the Reef/Santa Cruz Islands colonization estimate from Sheppard et al. (2015) as a prior for the Tutuila land-unit start boundaries. Using this required updating the paired charcoal-shell delta R from Sheppard et al. (2015) for Marine20 (Heaton et al. 2020). To do this we calculated the delta R using methods outlined in Reimer and Reimer (2017) using the online delta R application available at http://calib.org/JS/JSdeltar20/ using the “Radiocarbon Dated Nohem” method. Marine radiocarbon age and marine radiocarbon sigma set to 3137 ± 24 (NZA-53598) and 14C BP and 14C uncertainty set to 2768 ± 15 (NZA-53697), resulting in an updated delta R of -93 ± 36. The updated colonization estimate for the Santa Cruz Islands (from Nanngu (SE-SZ-8)) is 3005-2780 cal BP (95.4% HPD, rounded out 5 years), which is similar to Sheppard et al.’s (2015) estimate using Intcal13 and Marine13 with a delta R of 122 ± 28, which was 2920-2793 cal. BP (95.4% HPD)

## References

Dee MW, Bronk Ramsey C (2014) High-Precision Bayesian Modeling of Samples Susceptible to Inbuilt Age. Radiocarbon 56:83–94. https://doi.org/10.2458/56.16685

Heaton TJ, Köhler P, Butzin M, et al (2020) Marine20—The Marine Radiocarbon Age Calibration Curve (0–55,000 cal BP). Radiocarbon 62:779–820. https://doi.org/10.1017/RDC.2020.68 

Reimer PJ, Austin WEN, Bard E, et al (2020) The IntCal20 Northern Hemisphere Radiocarbon Age Calibration Curve (0–55 cal kBP). Radiocarbon 62:725–757. https://doi.org/10.1017/RDC.2020.41

Reimer RW, Reimer PJ (2017) An Online Application for ΔR Calculation. Radiocarbon 59:1623–1627. https://doi.org/10.1017/RDC.2016.117

Sheppard PJ, Chiu S, Walter R (2015) Re-dating Lapita Movement into Remote Oceania. Journal of Pacific Archaeology 6:26–36

