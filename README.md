ANKIT TYAGI 2315000314
INSIGHT:
1.Newer cars (year) tend to have higher prices.
2.Cars with higher km_driven usually have lower prices.
3.Diesel cars often have slightly higher resale value than Petrol, especially for older vehicles.
4.CNG and LPG cars usually have lower prices, suggesting lower market demand.
5.Individual sellers often offer better deals
6.Automatic > Manual
7.1st Owner > 2nd > 3rd+

MODEL RESULTS:
MAE=0.36006920754873406
MSE=0.2269159704367208
RMSE=0.476356977944819
R2 Score=0.6709635479274084
Accuracy=67%

CONCLUSION:
1.The model achieved an R² score of ~0.67 on the test set, indicating it can explain around 67% of the variation in car prices.
2.There is no significant overfitting, as training and test R² scores are close (Train ≈ 0.69, Test ≈ 0.67).
3.Features like car year and kilometers driven had a strong impact on price.
4.Categorical variables (like fuel type and seller type) also contributed positively when encoded.
