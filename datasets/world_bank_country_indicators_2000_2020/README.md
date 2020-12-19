## World Bank indicators at country level (2000-2020)

Source: World Bank https://data.worldbank.org/indicator

### Contents

- `world_bank_indicators_dictionary.tsv`: ID and description of selected indicators
- `world_bank_indicators_data.tsv`: Data in narrow form
- `indicators_by_year`: Data by year in long form with very generalised country boundaries in GeoJSON
- `all_indicators`: List of all available indicators (as of December 2020)

### Included variables

Note that the completeness of the indicators might vary year by year.

|   indicator_id                |   indicator                                                                                                    |
|-------------------------------|----------------------------------------------------------------------------------------------------------------|
|   2.0.hoi.Ele                 |   HOI: Electricity                                                                                             |
|   3.0.Gini                    |   Gini Coefficient                                                                                             |
|   3.1.Gini                    |   Gini, Rural                                                                                                  |
|   3.2.Gini                    |   Gini, Urban                                                                                                  |
|   6.0.GDPpc_constant          |   GDP per capita, PPP (constant 2011 international $)                                                          |
|   BX.TRF.PWKR.GD.ZS           |   Workers' remittances, receipts (% of GDP)                                                                    |
|   EN.ATM.PM25.MC.M3           |   PM2.5 air pollution, mean annual exposure (micrograms per cubic meter)                                       |
|   GB.XPD.RSDV.GD.ZS           |   Research and development expenditure (% of GDP)                                                              |
|   GFDD.OI.13                  |   Remittance inflows to GDP (%)                                                                                |
|   IN.TRANSPORT.TRAFDEATH.NUM  |   Number of road traffic deaths                                                                                |
|   IS.ROD.TOTL.KM              |   Roads, total network (km)                                                                                    |
|   IS.VEH.PCAR.P3              |   Passenger cars (per 1,000 people)                                                                            |
|   IT.NET.USER.ZS              |   Individuals using the Internet (% of population)                                                             |
|   MS.MIL.XPND.GD.ZS           |   Military expenditure (% of GDP)                                                                              |
|   NE.TRD.GNFS.ZS              |   Trade (% of GDP)                                                                                             |
|   NW.NCA.PC                   |   Natural capital per capita (constant 2014 US$)                                                               |
|   NY.GDP.MKTP.CD              |   GDP (current US$)                                                                                            |
|   NY.GDP.MKTP.PP.CD           |   GDP, PPP (current international $)                                                                           |
|   SH.STA.AIRP.P5              |   Mortality rate attributed to household and ambient air pollution, age-standardized (per 100,000 population)  |
|   SI.POV.HCRT.MI              |   Multidimensional poverty, Headcount ratio (% of population)                                                  |
|   SL.ISV.IFRM.ZS              |   Informal employment (% of total non-agricultural employment)                                                 |
|   SP.DYN.LE00.IN              |   Life expectancy at birth, total (years)                                                                      |
|   SP.POP.GROW                 |   Population growth (annual %)                                                                                 |
|   SP.POP.TOTL                 |   Population, total                                                                                            |
|   SP.RUR.TOTL.ZS              |   Rural population (% of total population)                                                                     |
|   SP.URB.TOTL.IN.ZS           |   Urban population (% of total population)                                                                     |
|   ST.INT.ARVL                 |   International tourism, number of arrivals                                                                    |
|   ST.INT.DPRT                 |   International tourism, number of departures                                                                  |
|   UNDP.HDI.XD                 |   Human development index (HDI)                                                                                |

Extracted with R package following 
https://econandrew.github.io/wdi-api-R-gettingstarted/using-r-to-access-the-world-bank-api.html

Date: Dec 2020