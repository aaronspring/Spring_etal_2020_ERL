# Data

Only globally-averaged output is provided. Please approach me for 3D files personally or consult <https://www.mpimet.mpg.de/en/grand-ensemble/>.

## Primary data from model output used for analysis

-   `co2atm.nc`: prescribed atm. CO2 forcing in simulations based on Integrated Assessment Models. Forcing component of method described in 2.2
-   `GE_co2_flux.nc`: 100-member, 3-scenario land, ocean and combined global sum of CO2 fluxes
-   `GE_GMST_ym.nc`: 100-member, 3-scenario global mean surface 2m temperature to compare with Marotzke 2019, not shown in paper
-   `CMIP6_C4MIP_ensemble_CO2_co2_flux.nc`: CO2 fluxes from 10 ensemble members of C4MIP (interactive CO2) historical ensemble (unpublished) used for verification of method: Fig. SI1

## (intermediate) results

-   `GE_diagnosed_atm_CO2.nc` diagnosted global mean atm. CO2 based on method described in 2.2
-   `MPIESM_GE_P_{varname}_bootstrap_500.nc` probabilities `P_RCPx` and `P_{N,S}` bootstrapped with replacement 500 times for `varname` in:
    -   `GMST`: Global mean surface 2m temperature to compare with Marotzke 2019, not shown in paper
    -   `CO2_co2_flux`: diagnosted atm. CO2 based on land and ocean CO2 flux
    -   `CO2_co2_flx_land`: diagnosted atm. CO2 only based on land CO2 flux, not shown in paper
    -   `CO2_co2_flx_ocean`: diagnosted atm. CO2 only based on ocean CO2 flux, not shown in paper
