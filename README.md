# MSCS 634 – Project Deliverable 3
## Classification, Clustering, and Pattern Mining

### Group Members:
Pabitra Bhandari
Haeri Kyoung
Vamsi Krishna Gajulapalli
Prakash Tamang


### Classification
Two models were developed:
- Logistic Regression (baseline)
- Random Forest (with hyperparameter tuning via GridSearchCV)

Performance was evaluated using:
- Confusion Matrix
- ROC Curve (AUC)
- Accuracy
- F1-score

The tuned Random Forest model demonstrated improved performance in identifying high-value customers.

### Clustering
K-Means clustering was applied to customer-level features.
Clusters were visualized using PCA.
Distinct customer segments were identified, supporting targeted marketing strategies.

### Association Rule Mining
Apriori algorithm was used to identify frequent itemsets and generate association rules.
High-lift rules revealed meaningful product relationships useful for cross-selling and recommendation systems.

### Practical Applications
- Customer segmentation for targeted marketing
- Identification of high-value customers
- Product bundling strategies
- Recommendation system enhancement

### Challenges
- Column naming inconsistencies
- Skewed monetary distribution
- Large basket matrix size during rule mining
