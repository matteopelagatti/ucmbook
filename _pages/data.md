---
layout: default
title: Data
permalink: /data/
nav_order: 2
nav: true
---

# Data 

Here, you can find the datasets used in the book, along with some additional time series.

-   [airline.csv]({{ '/assets/data/airline.csv' | relative_url }}){: download })
    -   Description: the famous airline time series from Box and Jenkins' book.
    -   Measurement: number of U.S. airline passengers in thousands.
    -   Frequency: monthly.
    -   Period: Jan-1949 -- Dec-1960.
    -   Source: Box, Jenkins, and Reinsel (1976) *Time Series Analysis, Forecasting and Control*. Third Edition. Holden-Day.
-   [AustraliaIntAirPassengers.csv]({{ '/assets/data/AustraliaIntAirPassengers.csv' | relative_url }}){: download }
    -   Description: number of passengers carried by international airlines to/from Australia.
    -   Measurement: number of passengers.
    -   Frequency: monthly.
    -   Period: Jan-1985 -- Dec-2013
    -   Source: https://www.bitre.gov.au/
-   [brent.csv]({{ '/assets/data/brent.csv' | relative_url }}){: download }
    -   Description: crude oil data to verify the spot-future price relationship.
    -   Measurements: Brent spot price, Brent future price, interest rate of the risk-free asset.
    -   Frequency: trading days (5-day week).
    -   Period: 2008-01-24 -- 2014-12-02.
    -   Source: ?
-   [conferenceBoardBcIndex.csv]({{ '/assets/data/conferenceBoardBcIndex.csv' | relative_url }}){: download }
    -   Description: the four time series the U.S. Conference Board uses to build the business
    cycle coincident index.
    -   Measurements: monthly (symmetric) growth rate of employees on nonagricultural payrolls (EMP),
    personal income less transfer payments (INC), industrial production index (IPI),
    manufacturing and trade sales (SAL).
    -   Frequency: monthly.
    -   Period: Jan-1960 -- Dec-2013
    -   Source: https://www.conference-board.org/topics/business-cycle-indicators/
-   [CPI_Restaurants.csv]({{ '/assets/data/CPI_Restaurants.csv' | relative_url }}){: download }
    -   Description: Italian consumer price index for restaurants and hotels.
    -   Measurements: consumer price index for restaurants and hotel, base 1995, step variable for
    a level shift starting on Jan-2002 (Euro introduction), and ramp starting form Feb-2002 for
    modelling a slope shift.
    -   Frequency: monthly.
    -   Period: Jan-1996 -- Dec-2010
    -   Source: ISTAT and my elaborations
-   [elettro.zip]({{ '/assets/data/elettro.zip' | relative_url }}){: download }
    -   Description: electric load on the Italian day-ahead market. There is a CSV with the load
    time series and a XLSX file with Holiday-related dummies.
    -   Measurements: electric load in MWh recordered on the Italian day-ahead market: there is one
    time series for each our of the day.
    -   Frequency: hourly, but the dataset is organized in 24 daily time series.
    -   Period: 2005-01-01 -- 2014-12-31 (all 24 hours).
    -   Source: https://www.mercatoelettrico.org/ and my elaborations.
-   [EWweddingsMonthly.csv]({{ '/assets/data/EWweddingsMonthly.csv' | relative_url }}){: download }
    -   Description: number of marriages by month in England and Wales.
    -   Measurements: number of marriages.
    -   Frequency: monthly.
    -   Period: Jan-1947 -- Dec-2011.
    -   Source: Office for National Statistics.
-   [EWweddingsQuarterly.csv]({{ '/assets/data/EWweddingsQuarterly.csv' | relative_url }}){: download }
    -   Description: number of marriages by quarter in England and Wales.
    -   Measurements: number of marriages.
    -   Frequency: quarter.
    -   Period: 1947-Q1 -- 2011-Q4.
    -   Source: my elaboration on the monthly data by the Office for National Statistics.
-   [GDP_IP_US.csv]({{ '/assets/data/GDP_IP_US.csv' | relative_url }}){: download }
    -   Description: U.S. Gross Domestic Product and U.S. Industrial Production Index
    -   Measurements: seasonally adjusted U.S. Industrial Production Index (base 2013) and
    seasonally adjusted U.S. Gross Domestic Product (billions of dollars).
    -   Frequency: monthly (IPI) and quarterly (GDP, first two months coded as missing).
    -   Period: Jan-1947 -- Dec-2014.
    -   Source: ?
-   [GDPEU.csv]({{ '/assets/data/GDPEU.csv' | relative_url }}){: download }
    -   Description: Gross Domestic Product of the European Union (28 countries) at 2010 prices.
    -   Measurements: Gross Domestic Product of the European Union (28 countries) in billions
    of 2010 Euros.
    -   Frequency: quarterly.
    -   Period: 1995-Q1 -- 2014-Q3.
    -   Source: Eurostat.
-   [injured.csv]({{ '/assets/data/injured.csv' | relative_url }}){: download }
    -   Description: monthly number of injuries due to car accidents in Italy.
    -   Measurements: number of injuries.
    -   Frequency: monthly.
    -   Period: Jan-2001 -- Dec-2013.
    -   Source: ISTAT.
-   [nile.csv]({{ '/assets/data/nile.csv' | relative_url }}){: download }
    -   Description: Famous time series of the flow of the river Nile at Aswan.
    -   Measurements: flow in 100,000,000 cubic meters.
    -   Frequency: yearly.
    -   Period: 1871 -- 1970.
    -   Source: Durbin and Koopman (2001) *Time Series Analysis by State Space Methods*. Oxford University Press.
-   [NYtemperature.csv]({{ '/assets/data/NYtemperature.csv' | relative_url }}){: download }
    -   Description: average monthly temperature in New York City.
    -   Measurements: average monthly temperature in Fahrenheit.
    -   Frequency: monthly.
    -   Period: 1895 -- 2013.
    -   Source: ?
-   [USmacro07.csv]({{ '/assets/data/USmacro07.csv' | relative_url }}){: download }
    -   Description: U.S. real GDP, consumption, and private investments.
    -   Measurements: quarterly seasonal adjusted time series in billions of 2007 dollars.
    -   Frequency: quarterly.
    -   Period: 1947-Q1 -- 2007-Q2.
    -   Source: ?
-   [USunempGDP.csv]({{ '/assets/data/USunempGDP.csv' | relative_url }}){: download }
    -   Description: U.S. unemployment rate and real GDP.
    -   Measurements: seasonally adjusted U.S. unemployment rate (%), U.S. GDP in billion of dollars.
    -   Frequency: quarterly.
    -   Period: 1948-Q1 -- 2014-Q2.
    -   Source: ?
