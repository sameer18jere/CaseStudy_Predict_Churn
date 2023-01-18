# Telecom Churn Group Case Study
 In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, your task in this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

## Table of Contents
* [General Info](#general-information)
The main goal of the case study is to build ML models to predict churn. The predictive model built will meet the following purposes:
1) It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
2) It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
3) Recommend strategies to manage customer churn based on your observations.

* [Technologies Used](#technologies-used)
1) pandas
2) numpy
3) seaborn
4) matplolib
5) sklearn

* [Conclusions](#conclusions)
- Positive Predictors for CHURN
- - days_since_last_rech: If the customer has NOT done any recharge for a long time, then he is a positive candidate for CHURN
- - rech_diff_act_good_ph: If the customer has shown an sudden difference in RECHARGE activity - different from good phase, then he might be a Churn customer.

- Negative Predictors for HOT LEADS
- - max_rech_amt_diff_act_good_ph: If there is huge dip in max amount spent for recharges, Customer might be a CHURN customer
- - total_og_mou_diff_act_good_ph: If there is a too much dip in total outgoing calls, Customer might be a CHURN customer
- - total_ic_mou_diff_act_good_ph: If there is a too much dip in total incoming calls, Customer might be a CHURN customer
- - total_rech_num_diff_act_good_ph: If there is a too much dip in number of recharges, Customer might be a CHURN customer
- - aon: As long as the customer is on Network, there is less chances of CHURN
- - rech_amt_diff_act_good_ph: If there is a too much dip in recharge amounts, Customer might be a CHURN customer

* [Acknowledgements](#acknowledgements)
 -Sanchit
