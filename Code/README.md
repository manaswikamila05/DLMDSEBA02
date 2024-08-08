# Approach Steps
1. **Sketched the ERD Diagram**: Identified relationships between tables and created a database.
2. **Connected to the Database**: Analyzed the dataset and performed data profiling, checking for missing values, outliers, and anomalies.
3. **EDA** : Performed exploratory data analysis on each feature with respect to Churn feature. Identified key predictors of churn after EDA.
4. **LTV analysis**: Analysed average LTV, tenure and usage of services of high and low LTV customers, Determined factors that lead to improvement in CLTV and analyzed LTV per group.
5. **Scaled Features**: Ensured features had a consistent range or distribution.
6. **Converted Categorical Data**: Used label encoding techniques to convert categorical data into numerical format.
7. **Divided the Dataset**: Split the dataset into training, validation, and test sets.
8. **Chose Suitable Algorithms**: Selected algorithms based on the problem type and data characteristics.
9. **Trained the Model**: Used the training dataset to teach the model to recognize patterns.
10. **Evaluated the Model**: Assessed the model's generalization capability using the test set and performance metrics.

# Model 1. Customer Churn Prediction
**Goal** :
Identify customers at risk of leaving the service.

**Value**
1. Proactively addressing potential customer churn to retain high-value customers.
2. Enhancing customer satisfaction through targeted interventions.
3. Reducing revenue loss associated with customer churn.

**Appropriate machine learning models** :
1. Use binary classification algorithms including Logistic Regression, Decision Trees, Random Forest, and XGBoost.
2. Train the models using the training data and perform hyperparameter tuning to optimize model performance.

**Model performance evaluation**
1. Using metrics such as accuracy, precision, recall, F1 score, and ROC AUC.
2. Used feature importance plots to interpret the impact of each feature on the prediction.

# Model 2. Customer Segmentation
**Goal** :
Effectively segment customers to tailor retention strategies.

**Value**
1. Grouping customers based on behavior and needs allows for targeted marketing and personalized offers.
2. Enhances customer satisfaction and loyalty by addressing specific needs of each segment.

**Appropriate machine learning models**
1. Clustering algorithms such as K-Means, Hierarchical Clustering, or DBSCAN.
2. Determine the optimal number of clusters using the Elbow method or Silhouette analysis.

**Cluster Analysis**
1. Visualized the clusters using scatter plots.
2. Analyze the characteristics of each cluster to understand customer behavior and needs.
3. Profile the clusters based on key attributes and identify potential opportunities for targeted marketing.

# Model 3. Optimizing Customer Retention (Cross-selling and Upselling)
**Goal** :
Identify opportunities for cross-selling and upselling to enhance customer value and retention.

**Value**
1. Enhances customer lifetime value by increasing the number of services subscribed to by each customer.
2. Improves customer satisfaction by offering relevant and valuable service bundles.
3. Increases revenue through effective cross-selling and upselling strategies.

**Appropriate machine learning models**
1. Apriori algorithm to identify frequent itemsets and generate association rules.
2. Set appropriate support, confidence, and lift thresholds to extract meaningful rules.

**Rule Analysis**
1. Analyze the generated rules to identify potential cross-selling and upselling opportunities.
2. Develop marketing strategies based on the identified rules, such as bundling complementary services or offering discounts on frequently purchased together items.
3. Design personalized promotions and recommendations for customers based on their purchase history and identified rules.

