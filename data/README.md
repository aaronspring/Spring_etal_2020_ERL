# Data

Only globally-averaged output is provided. Please approach me for 3D files personally or consult <https://www.mpimet.mpg.de/en/grand-ensemble/>.

## Primary data from model output used for analysis

-   `co2atm.nc`: prescribed atm. CO2 forcing in simulations based on Integrated Assessment Models. Forcing component of method described in 2.2
-   `GE_co2_flux.nc`: 100-member, 3-scenario land, ocean and combined global sum of CO2 fluxes
-   `CMIP6_C4MIP_ensemble_CO2_co2_flux.nc`: CO2 fluxes from 10 ensemble members of C4MIP (interactive CO2) historical ensemble (unpublished) used for verification of method: Fig. SI1
-   `compatible_emissions.nc`: Compatible emission, see Jones et al. 2013

## (intermediate) results

-   `GE_diagnosed_atm_CO2.nc` diagnosted global mean atm. CO2 based on method described in 2.2
-   `MPIESM_GE_P_{varname}_bootstrap_500.nc` probabilities `P_RCPx` and `P_{N,S}` bootstrapped with replacement 500 times for `varname` in:
    -   `CO2_co2_flux`: diagnosted atm. CO2 based on land and ocean CO2 flux
