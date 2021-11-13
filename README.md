![](https://github.com/virajvaidya/VARAustraliaHousingForecast/blob/main/Screenshot%202021-11-13%20at%206.28.38%20PM.png)

# Australia Housing Data Forecast - Structural Autoregressive Model

This project was completed as a group project with Mr. John Dundas and Mr. Timothy Geary for the ECMT6003 Applied Business Forecasting Unit as part of my Master of Economics course at The University of Sydney.

The model is a Structural Vector Autoregressive Model modelled with the following twenty variables sourced from the Australian Burea of Statistics (ABS) and the Reserve Bank of Australia's Statistical Tables.



| Variable name | Variable description            | ABS/RBA Description | Unit |
|---------------|---------------------------------|---------------------|------|
|batotalvol     | Building Approvals| Total value of building jobs; Chain Volume Measures; Total Sectors; Total Residential; New| AUD Thousands|
|ctotalvol      | Building Commencements |Value of work commenced; Chain Volume Measures; Total Sectors; Total Residential; New| AUD Thousands| 
|dwell_complete | Dwelling completions| Dwelling units completed; Total Sectors; Total (Type of building); Total (Type of work) | Number|
|ipd_natdi     |Investment deflator| Private; Gross fixed capital formation - Dwellings - Total| Index
|natdi          | Dwelling investment | Private; Gross fixed capital formation - Dwellings - Total| AUD Thousands| 
|wdnewvol        | Work done, new and used | Value of work done during quarter; Chain Volume Measures; Total Residential; Private Sector; New | AUD Thousands| 
|cash           | Reserve Bank of Australia Interbank Overnight Cash Rate | Quarter average |Percent |
|inf_exp        | Inflation expectations | Market economists' inflation expectations one year ahead | Percent |
|rinc            | Real disposable income | Total income divided by the Consumer Price Index (CPI) | Percent|
|rinc_per_capita | Real disposablew income per person (age 15 years and above| rinc divided by wap(working age population) | AUD|
|i_10y_bond     | 10 year Australian Government bond yield | Commonwealth Government 10 year bond | Percent|
|house_price_index | Real CPI House Price | Residential Property Price Index; Weighted average of eight capital cities | Index|
|rrent              | Real CPI rents | Index Numbers; Rents; Australia |Index |
|stock          | Housing stock |bHousing stock; Chain Volume Measures |AUD Thousands |
|ur         | Unemployment Rate | Unemployment Rate; Persons | Percent |
|mr             | Variable Mortgage Rate |Lending rates; Housing Loans; Variable; Standard; Owner-Occupier | Percent    
|wap            |Working Age Population | Civilian population aged 15 years and over; Persons | Thousands|
|under          | Underemployment rate| Underemployment rate expressed as proprtion of Labour Force population; person | Percent
|gdp_aggregate_milaud  |Aggregate Gross Domestic Product | Aggregate GDP; Chain Volume Measures | AUD Millions |
|gdp_per_capita       | Per capita Gross Domestic Product | gdp_aggregate_milaud divided by total population | AUD |

The data is quarterly - starting from March 1987 to December 2020, spanning the observations of the twenty variables over 136 quarters.
The model computes a Vector Autoregressive forecast for the following 4 quarters, i.e. for the year 2021.





The ForecastFile.ipynb file might have some issues loading on some devices due to it's size.

In such an instance, please click this link for an off-GitHub version of the Python code at https://colab.research.google.com/drive/15blME9jemV8DiQYXmJWgNDg-LwSWR7tA?usp=sharing
