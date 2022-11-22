# quantile-prediction

+ We need to predict different quantiles values in country , NAICS Title and OCC Title level.
+ we have to predict it in such a way that pct_10 < pct_25 < Median < pct_75 < pct_90
+ Define and monitor custom metric - sum(Wi*mod((Qi - Pred_Qi)/Qi))/sum(Wi)
+ W = [0.1, 0.2, 0.4, 0.2, 0.1]
