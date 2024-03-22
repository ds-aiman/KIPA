Purpose Of The Project - To find out if Electricity price is affecting the waste price for suppliers in Germany.

WASTE DATASET FEATURES – (Waste dataset cannot be provided due to Data privacy policy)

- Contain waste price information for country Germany divided into cluster formation where each cluster represents few area of the country.
- In total there are 10 clusters in this dataset
- In total there are 4 categories of waste categories and not each cluster have all of them.
- The data is given on weekly basis starting from week 37 of year 2020.
- The waste price (wpreis) basically means the amount supplier has to pay to get the waste materials (when wpreis is negative) or the amount the suppliers get to take the waste materials ( when wpreis is positive).

ELECTRICITY DATASET
Datum - date of the day.
von - beginning hour
Zeitzone von - Time zone for the beginning hour.
bis - Ending hour.
Zeitzone bis - Time zone for ending hour.
Spotmarktpreis in ct/kWh - Price of the Electricity for given time period.

This dataset has been fetched from an online source - https://www.netztransparenz.de/EEG/Marktpraemie/Spotmarktpreis
The data starts from January 1, 2021.
The data is given in hourly basis , that means for each day we have 24 rows
The electricity price is in unit ct\kWh - cent per KiloWatt Hour
The electricity data was not available in cluster or region basis, rather the whole germany data, so we will work with same.

PROCESS FOLLOWED
- Extraction of both datsets
- cleaning of both datasets
- comparing prices for each cluster separately
- making a hypothesis based on all the visualizations.
