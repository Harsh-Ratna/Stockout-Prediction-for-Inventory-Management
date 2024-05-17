# Stockout-Prediction-for-Inventory-Management
This project aims to investigate the primary factors contributing to stockouts in the organization and suggest strategies to mitigate or minimize their frequency, using various classification algorithms along with ensemble approach.

<p align='center'><a href="https://github.com/Harsh-Ratna/Stockout-Prediction-for-Inventory-Management/blob/main/images/Backorders%20poster.png" target="blank"><img align="center" src="https://github.com/Harsh-Ratna/Stockout-Prediction-for-Inventory-Management/blob/main/images/Backorders%20poster.png" height="300" /></a></p>

## Data 
The dataset was acquired from https://www.kaggle.com/datasets/chandanareddy12/back-order-prediction which contains 1687861 rows and 23 columns. 

## Features Explained In-detail
* Sku- number of units

* National inventory - number of items in the inventories 

* Lead_time- expected time for delivery

* In_transit_qty-  quantities currently in transaction (on the way)

* Forecast_3 - number of units expected to sell in the next 3 months

* Sales_3 - number of units sold in the past 3 months

* Min_bank - some reserved stock that companies always maintain.

* Potential risk- some risk (eg. shortage of semiconductors in electronics company)

* Performance - how is the performance of that supplier (deliver the commodity on time, it would be one)

* Local_bo_qty- not able to get bulk order, to keep the supply chain on the go, we source products locally, what will be the quantity 

* Deck_risk - if the shipment are through ship, and major risk is there, then the ship captain has the right to throw cargo to save lives of crew. So products in low deck risk, buried deep in the deck have lower risk and low cost commodity have higher deck risks.

* Oe_constraint- original equipment manufacturers do they have any constraints? So in case we have to upscale our production

* Ppap risk- identifying and solving a process, giving consumers evidence that our service is reliable, that we deliver our products on time. Means that supplier has low risk.

* Stop_auto- mechanism of auto ordering, they know every 15 days they have to deliver

* Rev_stop- reviewing stop, 

* Went_on_backorder- product went out of stock/exhausted
