# ECODash

An interactive dashboard coded purely in Python, utilizing Plotly's interactive graphs and deployed as a web app using Dash, whose aim is to investigate various socio-economic indicators and economic trends in order to gain insights into the relationships and patterns within different countries within Europe


Makes use of data from OECD: https://www.oecd.org/switzerland/, taking into consideration the following socio-economic indicators:

- Inflation
- Poverty
- Unemployment
- GNI (Gross National Income)
- Household Wealth
- Imports
- Exports
- Life Expectancy
- Fertility Rates
- Native Women Unemployment
- Native Men Unemployment
- Nominal House Prices (meaning: nominal house prices for purchasing, not adjusted for inflation)
- Nominal Rent Prices
- Household Savings
- Population

The dashboard is designed to cater towards countries under Europe, notable examples being Austria, Switzerland, France, Germany, Italy and many more. It makes use of Plotly's graphical visualizations to compare across different indicators, and derive answers to certain research questions, few of which are highlighted below:


| Question | Description |
| --- | --- |
| Is there a correlation between inflation and unemployment in 2020? | Investigate the relationship between inflation and unemployment rates in the year 2020. |
| How are the nominal and rent prices in Italy? | Examine the current nominal and rent prices in Italy and compare them to historical data. |
| How have the export/import rates changed over time in Switzerland? | Analyze the trends and changes in export and import rates in Switzerland over a specific time period. |
| How have inflation rates changed in countries over the past decade? | Study the inflation rates in various countries and observe their changes over the past ten years. |
| How are poverty, GNI, fertility, and life expectancy correlated in each country? | Explore the correlation between poverty, Gross National Income (GNI), fertility rate, and life expectancy in different countries. |
| Which European countries have the highest and lowest unemployment rate? | Identify the European countries with the highest and lowest rates of unemployment. |



## Demo of the First Dashboard

- Two dropdowns have been implemented in the first board, one is for selecting the country ( all of which belong to the European continent), and second is for a more fine-grained analysis including the Year ( we have data from around 10 years to track evolution across different socio and economic indicators).

- A combination of line, symbol and bar charts has been used to analyse the raw data and determine insights


https://github.com/deepansha16/ECODash/assets/49023785/9fa7f05b-ebe2-41c1-aebf-361527aa8228


## Demo of the Second Dashboard

- The second dashboard caters offers a time series view, providing a intriguing combo of a scatter plot and line plots, where on the left you select the first indicator you want to consider, and on the right the second indicator to be compared with.

- A linear and log scale has been provided for more precise result

- Hovering over the countries on the scatter plot produces the data for the indicators over a decade on the adjacent line plot, so for example on selecting  `Imports` and `Exports`, and clicking on `Austria`, will fetch you the comparison line plot for the two indicators.