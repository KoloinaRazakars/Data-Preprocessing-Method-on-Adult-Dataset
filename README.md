# Data-Preprocessing-Method-on-Adult-Dataset
This project focuses on data preprocessing using the Adult dataset.  
The objective is to transform raw structured data into a clean and usable format for machine learning tasks.

## Dataset
The Adult dataset contains demographic and socio-economic information used to predict whether an individual's income exceeds $50K per year.

## Data Preprocessing Steps
- Handling missing values
- Removing or analyzing inconsistencies
- Encoding categorical variables
- Feature scaling

## Why Data Preprocessing Matters
Data quality has a significant impact on machine learning performance.  
This project highlights the importance of proper preprocessing before model training.

# Machine Learning Pipeline
Although the main focus of this project is data preprocessing, a set of classification models was applied to evaluate the impact of data preparation on predictive performance.

### Models Used
- Logistic Regression
- Support Vector Classifier (SVC)
- Random Forest

### Evaluation Metrics
The models were evaluated using standard classification metrics:
- Accuracy
- Precision
- Recall
- F1-score

## Results & Insights

The dataset presents several challenges such as missing values, skewed distributions, and low feature correlations.

Key observations:
- Highly skewed features (e.g., capital-gain) required scaling and outlier handling
- Correlation analysis shows weak linear relationships between features
- LDA projection reveals partial class separability, indicating a non-trivial classification task

Model comparison:
- Logistic Regression achieves strong recall, making it suitable for detecting positive cases
- SVC provides higher precision but lower recall, indicating a more conservative model
- Random Forest offers a balanced performance across metrics

### Conclusion
This experiment demonstrates that proper data preprocessing significantly impacts model performance and that different models demonstrate distinct trade-offs between precision and recall.
