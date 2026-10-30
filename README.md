# Global-shifts-interdependence-under-climate-change
This repository contains coding for manuscript "Global shifts in land–atmosphere interdependence under climate change"

Read me!

Create the conda environment:

conda env create -f env.yml 
Then start a notebook: Jupiter notebook

Annual_global_CMIP6_rev3.ipynb: Calculates the mean and standard deviation of projected changes in hydroclimatic variables at the annual scale using CMIP6 model outputs.
Annual_global_Era5_rev3.ipynb: Calculates the mean and standard deviation of projected changes in hydroclimatic variables at the annual scale using ERA5 outputs.

Seasonal_global_CMIP6_rev3.ipynb: Calculates the mean and standard deviation of projected changes in hydroclimatic variables at the seasonal scale using CMIP6 model outputs.
Seasonal_global_ERA5_rev2.ipynb: Calculates the mean and standard deviation of projected changes in hydroclimatic variables at the seasonal scale using ERA5 outputs.

Tas_GlobalVSAll_rev3.ipynb contains the code for producing Figure 2 and its related Figure for annual data analysis
Tas_GlobalVSAll_seasonal_rev3 contains the code for producing Figure 2 and its related Figure for seasonal data analysis

Variability_interdependence_rev3.ipynb contains the code for producing Figure 3 and its related Figure for annual data analysis
Variability_interdependence_seasonal3.ipynb contains the code for producing Figure 3 and its related Figure for seasonal data analysis

RFandSHAP_rev4a_boostrap.ipynb: Calculates Granger Causality and RF-SHAP for JJA
RFandSHAP_rev4_boostrap.ipynb: Calculates Granger Causality and RF-SHAP for DJF

RF_and_SHAP_fig2.ipynb contains the code for producing Figure of interdependence
interdependence_rev4.ipynb contains the code for producing summary Figure of interdependence (Fig. 4)

Fraction_change.ipynb contains the code for producing Fig. 5
Adjacent_matrics_rev1.ipynb contains the code for producing network modulations (detail for Fig. 5)

E_over_P_rev1.ipynb contains the code for calculating Evaporation/Precipitation and related figure
P-E_seasonal.ipynb contains the code for calculating Precipitation - Evaporation and related figure
