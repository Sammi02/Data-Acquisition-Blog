# Data-Acquisition-Blog

## Overview

This project explores global air travel trends over the past five years, focusing on the impact of COVID-19 and the subsequent recovery. Using data scraped from Wikipedia, I analyzed:

- Which countries and airports consistently had the most passengers flying through their airports. 

- Which countries and airports bounced back the quickest after COVID-19 pandemic. 

- The analysis is presented as a Quarto blog with plots, tables, and insights for easy interpretation.


## Dataset

Source: [Wikipedia: List of Busiest Airports by Passenger Traffic](https://en.wikipedia.org/wiki/List_of_busiest_airports_by_passenger_traffic)

Time period: 2020–2024

Columns used:

- Rank – Airport ranking by year

- Airport – Airport name

- Location – City/location of the airport

- Country – Country of the airport

- Code – Airport IATA code

- TotalPassengers – Number of passengers

- RankChange – Change in ranking from previous year

- Year – Year of data

- Percent change numeric – Scraped numeric percent change

- PercentChangeSigned – Cleaned percent change, including negative values for drops


## Highlights

Here are some of the highlights from my analysis:

- Hartsfield–Jackson Atlanta International Airport, Dallas Fort Worth, and Denver consistently appear in the top 10 by total passengers.

- The United States dominates the top rankings, with a few international hubs in Europe, Asia, and the Middle East.

- The United States bounced back the fastest after Covid in 2021, while Europe and Asia bounced back stronger in 2022. 