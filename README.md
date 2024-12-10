# d2kAssesment
Solving the Assessment Test

## Credit Card Churning
A detailed analysis about credit card data and customer attrition.

## Key Data Insights
1. Fig 1 describes the univariate distribution of the categorical features in datasets.

2. Fig 2 describes the univariate distribution of the numerical features in datasets providing valuable insights into their underlying patterns.The presence of skewness in the distributions is analyzed, revealing whether the data is symmetric, positively skewedo r negatively skewed.

3. Fig3 shows that for credit limit less than equal to 20000 attrited customer exhibit a lower total transaction amount of 2500. This might indicate limited usage of their accounts, possibly due to restrictions imposed by the lower credit limit or a lack of need for higher spending. And for credit limit greater then  34500  the total transaction amount increases to 10,000 for attrited customers, suggesting that a moderate credit limit allows for higher account activity.

4. Fig 4 Customers aged 30 to 60 are highly attrited when the credit limit is less than 5,000, likely due to insufficient financial flexibility. Conversely, this age group is predominantly retained with credit limits greater than 5,000, as it better suits their spending needs. However, for credit limits above 34,500, attrition increases among customers aged 40 to 60, possibly due to dissatisfaction with non-monetary factors like fees or services. These patterns suggest the need for tailored credit strategies to balance retention and satisfaction.

5. Fig 5 for credit limits between 5,000 and 10,000, attrited customers have transaction counts from less then equal 20 to 63, while existing customers show higher activity with counts from 64 to 125. Similarly, for credit limits above 34,000, attrited customers' transaction counts range from ≤20 to 83, whereas existing customers' counts are higher, from 85 to 139. These trends highlight that higher transaction activity is strongly associated with customer retention across different credit limit ranges.

6. Fig 6 describe in  elbow curve the bending of line starts from 7.5 that indicates that the optimal number of clusters for the data is from 7.5 or 8 or 10. This suggests that increasing the number of clusters beyond 8 or 10 does not significantly reduce the within-cluster variance, meaning the data is best represented by 8 or 10 distinct clusters. Therefore, 8 or 10 clusters capture the most meaningful segments of the data while avoiding overfitting.

## Model Performance
1. RandomForest -> Accuracy Score -> 95.21 %
2. DecisionTree -> Accuracy Socre -> 91.75 %
3. LogisticRegression -> Accuracy Score -> 86.17 %
4. XGBoost -> Accuracy Score -> 97.38 %