# Byte Me
## 2025 Synchrony Datathon
We are Mann Talati, Samarth Nadgir, Prerith Arunkumar, and Heta Patel from Byte Me and are participating in the 2025 Synchrony Datathon. With the following problem statement given, we have decided to tackle this through a three-pronged approach. We have first worked towards creating a forecasting model which gives us predictions about the Q4 data, our next step was to create the classification/cluster model which is dependent on account data, and we finally worked towards creating the model that will help to identify credit limit adjustments.

## Libraries Used
The following libraries are necessary to be installed within the runtime environment.
```
pip install pandas
pip install torch
pip install scikit-learn
pip install numpy
pip install neuralforecasting
pip install statsmodels
pip install matplotlib
```

## Forecasting Model


## Classification Model
Features Considered:

```external_status_reason_code```, ```cu_bhv_scr```, ```cu_crd_bureau_scr```, ```mo_tot_sales_array_1 through mo_tot_sales_array_6```, ```cu_cash_line_am```, ```cu_crd_line```, ```cu_otb```, ```cu_nbr_days_dlq```, ```ca_max_dlq_lst_6_mnths```, ```ca_nsf_count_lst_12_months```, ```return_check_cnt_total```, ```gross_fraud_amt```, ```net_fraud_amt```, ```transaction_return_cnt```

Which Model We Used & Why: 

## Credit Limit Adjustments Model
