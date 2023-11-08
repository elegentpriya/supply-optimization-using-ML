# supply-optimization-using-ML


## Overview

A Fast Moving Consumer Goods (FMCG) company entered into the instant noodles business two years back. Their higher management has noticed that there is a mismatch in the demand and supply. Where the demand is high, supply is pretty low and vice-versa which results in a loss in inventory cost and ultimately loss to the company. Hence, the higher management wants to optimize the supply quantity in each and every warehouse in the entire country.

## Goals

The objective of this exercise is to build a model, using historical data that will determine an optimum weight of the product to be shipped each time from the respective warehouse.

Focus on all steps of data science (EDA, data processing, model, evaluation, charts)
Highlight any trend in data, deep insight, novel steps that you take
Highlight next steps and improvements.
Apply 5 to 6 machine learning algorithms and evaluate it using Test dataset.
## Data Dictionary

Variable	Description	Data Type
Ware_house_ID	Unique Warehouse id where product is prepared for dispatch.	Object
WH_Manager_ID	Manager Id present in the warehouse	Object
zone	Zone of the Warehouse	String
WH_regional_zone	Regional Zone of the warehouse	Object
num_refill_req_l3m	Refilling request received by the warehouse in the last 3 months	integer
transport_issue_l1y	No. of transport issued for warehouse in last 1 year	integer
Competitor_in_mkt	No. of competitors in the market	integer
retail_shop_num	Number of retail shops who sell noodles produced by the warehouse	integer
wh_owner_type	The warehouse is owned by the company or it is on rent	String
distributor_num	No. of distributor who works between warehouse and retail shops	integer
flood_impacted	Is the warehouse in a flood impacted area or not	integer
flood_proof	Flood_proof: Warehouse is having flood proof indicator	integer
electric_supply	Does the warehouse have proper electric supply along with some power backup	integer
dist_from_hub	distance from the warehouse to production hub	integer
workers_num	no. workers in the warehouse	integer
wh_est_year	warehouse establishment year	integer
storage_issue_reported_l3m	storage issues reported by the warehouse in the last 3months	integer
temp_reg_mach	warehouse having temperature regulating machine indicator or not	integer
approved_wh_govt_certificate	Type of approval warehouse having been issued by government	Object
wh_breakdown_l3m	Number of times the warehouse faces the breakdown in the last 3 months	integer
## Next Steps and Improvements

Collect more data to improve the accuracy of the model.
Use more sophisticated machine learning algorithms.
Deploy the model to a production environment.
## License

This project is licensed under the MIT License.
