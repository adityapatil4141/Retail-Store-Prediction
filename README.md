# Retail-Store-Prediction
Overview

Rossmann, a prominent drug store chain operating in 7 European countries, faces the challenge of predicting daily sales for over 3,000 stores. This project utilizes historical sales data, including factors such as promotions, competition, holidays, and more, to forecast sales up to six weeks in advance.

Problem Statement

Rossmann managers aim to predict daily sales accurately, considering the influence of various factors on store sales. The goal is to create a robust model that can forecast sales even when stores are temporarily closed for refurbishment.

Conclusion

After a thorough analysis, we observed that the Sales column contained 172,817 rows with zero sales. Removing these rows resulted in training a model with around 74% accuracy. However, when considering the entire dataset, including rows with Sales = 0, our model achieved a significantly higher accuracy of approximately 98%. We discovered that removing zero sales rows led to a loss of valuable information, given the substantial size of the dataset.

Our best Root Mean Square Percentage Error (RMSPE) score was obtained using the Random Forest model and gradient boosting techniques like Adaboost and XGBoost. We fine-tuned model parameters to avoid overfitting.

Data Description

Rossmann Stores Data.csv: Historical data including sales.
store.csv: Supplemental information about the stores.
