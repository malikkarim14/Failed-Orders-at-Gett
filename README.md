# Failed-Orders-at-Gett

## Description

This project is inspired by stratascratch.com, and I will be looking for insights from failed orders in the Gett app. I use Python to prepare the data and Tableau to visualize it.

## Scenario

Gett, formerly GetTaxi, is an Israeli-developed technology platform devoted solely to corporate Ground Transportation Management (GTM). They have an app where customers can order taxis and drivers can accept them (offers). When a client clicks the Order button in the app, the matching system searches for the most relevant drivers and offers them the order. In this task, we'd like to look into some matching metrics for orders that didn't go as planned, i.e., the customer didn't end up getting a car.

## Data Description

The data set `data_orders` is stored in CSV format. The columns in the `data_orders` are as follows:

- `order datetime` = order time 
- `origin longitude` = order longitude 
- `origin latitude` = order latitude
- `order gk` = order number 
- `m order eta` = time before order arrival
- `order status key` = status, an enumeration of the following mappings:
    - 4 (canceled by the client), 
    - 9 (canceled by the system, indicating a rejection)
- `is_driver assigned key` = whether or not a driver has been assigned 
- `cancellation time in seconds` = the number of seconds that passed before cancellation

## Source Code

You can see my code for preparing the data in [here](https://github.com/malikkarim14/Reddit-Scraping/blob/9f8e159faf693c05f8dcc5a3aa1b629705e82bf3/Scrape_Reddit.ipynb)

## Result

To see the visualization that I made in Tableau, you can click [here](https://public.tableau.com/views/FailedOrdersatGett/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


#### Creation Date

November 24th, 2022
