# Crude Oil Production in the United States
Crude Oil Production in the United States is monitored and reported by the United States Energy Information Agency (EIA).  The reported data was used to create a dashboard that visualizes and explains current production trends.  
The Tableu dashboard can be seen at https://public.tableau.com/profile/matthew.m5135#!/vizhome/CrudeOilProductionintheUnitedStates/EIAPRODUCTIONOIL?publish=yes

Features include:
  - automatic update of all values
  - KPIs regarding oil production
  - current production values of the country, Petroleum Administration for Defense Districts (PADD) regions, and states
  - month of month changes in production values
  - month of month percent changes in production values
  - color association in increase or decrease to help convey analysis in month over month changes
  - shape association in increase or decrease to help convey analysis in month over month changes
  - sparklines to show trends in country and regional productions
  - map of the United States showing state production
  - dynamic parameter actions to view states by PADD
  - stacked line graph to visually compare different production values from states
  
Python programming was used to extract data from the EIA, transform, and load results into Tableau software.  Specifically, crude_production.ipynb reads in the EIA data, removes unwanted date entries, cleans its header descriptions, transforms data by assigning a state and PADD region as categorical data to each date recorded.  This transfrmed dataset as well as EIA data was used in visualizations.

The Tableu dashboard can be seen at https://public.tableau.com/profile/matthew.m5135#!/vizhome/CrudeOilProductionintheUnitedStates/EIAPRODUCTIONOIL?publish=yes
Visit my LinkedIn page at https://www.linkedin.com/in/matthewjmccarroll/
The EIA data can be found at  https://www.eia.gov/dnav/pet/pet_crd_crpdn_adc_mbblpd_m.htm
