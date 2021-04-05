All Bayesian model code and results are located in the [Morrison_etal_Tutuila_IFD_Final](./Morrison_etal_Tutuila_IFD_Final) directory. The script to run each model has a `.oxcal` file extention, and results have the extensions `.js`,`.log`,`.txt`,and `.prior`. The `.prior` files result from exporting and saving the `Boundary()` Start estimates from each model.

`SC_Nanggu_Colonization.oxcal` contains the single-phase Bayesian colonization model for the Reef/Santa Cruz Islands presented in Sheppard et al. (2015). Note that this model uses an updated marine reservoir correction for Marine20. The Boundary start estimate from this model, `SC_colonization.prior` is used as a prior constraint on the Boundary start estimate for each of the Tutuila Land Units.

`LU_3350_v2.oxcal` is the model for Fagali'i land unit.

`LU_3577_v2.oxcal` is the model for Vainu'u land unit

`LU_3679_v2.oxcal` is the model for Tafuna/Leone land unit.

`LU_4545_v2.oxcal` is the model for Fagamalo land unit.

`LU_4686_v2.oxcal` is the model for Fatumafuti land unit.

`LU_5284_v2.oxcal` is the model for Aasu land unit.

`LU_7053_v2.oxcal` is the model for Aganoa land unit.

`LU_7254_v2.oxcal` is the mdoel for Utumea land unit.

`LU_7469_v2.oxcal` is the model for Pago Pago  land unit.

`LU_9497_v2.oxcal` is the model for Tula land unit.

`LU_984_v2.oxcal` is the model for Asili'i land unit.

`LU_Ridgeline_v2.oxcal` is the model for the Ridgelines land unit.

`Final_results_order_v2.oxcal` is takes all the Boundary start estimates from the Land Unit models above (exported as `.prior` files) and calculates their settlement order probabilities. A table shoing the results of this ordering can be found in `final_results_order_v2.csv` and a figure is available in `Final_results_order_v2.svg`.
