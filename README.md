## Credit Card Fraud Anomaly Detection

This project explores the precision performance of a Hierarchical Agglomerative Clustering Model, Mahalanobis Distance Model, Local Outlier Factor Model, and Isolation Forest in identifying fraudulent transactions in the Credit Card Fraud Kaggle Dataset. 

To show a statistically robust precision performance for Isolation Forest and Local Outlier Factor, a Stratified K-Fold CrossValidation and Grid Search pipeline was implemented and employed. Because of the Agglomerative Clustering Model’s temporal inability to utilize the pipeline, a repeated hold-out method was used to examine performance. Given the lack of parameters for Mahalanobis Distance, only Stratified K-Fold Cross-Validation was used. 

The pipeline showed a strong performance in precision scores for both the Isolation Forest and the Mahalanobis Distance model with average test precision scores of 0.66 and 0.24 accordingly. Our results for Local Outlier Factor and Hierarchical Agglomerative Clustering were poor with both having an average precision score of 0. This paper shows that the Mahalanobis Distance Model and Isolation Forest are viable models to identify fraudulent transactions in the [Credit Card Fraud Kaggle Dataset](https://www.kaggle.com/code/vijeetnigam26/credit-card-fraud-detection) and that the Local Outlier Model and Agglomerative Clustering Model are not.
