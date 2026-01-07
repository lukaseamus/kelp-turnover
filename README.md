# Kelp biomass turnover dataset
This global dataset compiles *in situ* measurements of annual biomass turnover for kelps (Laminariales and other brown seaweeds referred to as kelps). Various measures of biomass turnover were considered (e.g. production to biomass ratio, relative growth rate etc.) as long as they were representative of annual timescales. `Turnover.csv` contains all data and `References.pdf` gives a full bibliography of the cited studies. The folder `Screenshots` contains all figures from which data were extracted with WebPlotDigitizer v4.6 (https://automeris.io). The data are structured into these variables:

- `Reference` Citations in chronological order
- `DOI` Digital object identifier
- `Location` Descriptor of study site
- `Species` Latest binomial name according to AlgaeBase (https://www.algaebase.org)
- `Level` Measurement level with categories "Lamina", "Thallus" and "Forest"
- `Turnover` Biomass turnover given as a relative rate per year
- `Source` Data source within `Reference`
- `Notes` Further information on how `Turnover` was extracted from `Source` or calculated

Luka Seamus Wright, 7th January 2026
