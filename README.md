## Big Data Churn Prediction with Spark

### Project Overview
In this project, we developed a big data classification model using the Spark library to predict customer churn. Customer churn refers to the phenomenon where customers stop doing business with a company or cancel a service. It’s a critical metric for businesses, as high churn rates indicate customer dissatisfaction or better alternatives in the market, impacting a company's revenue and growth potential. By building a churn prediction model, companies can identify which customers are likely to leave, allowing them to take proactive steps to improve retention.

![Churn Prediction Visualization](https://miro.medium.com/v2/resize:fit:1400/1*TgciopaOk-C8fwtPmmet3w.png)

### Key Features
- **Data Processing**: Utilized Spark’s data handling capabilities to preprocess large datasets, including modules from **PySpark SQL** for data transformation.
- **Feature Engineering**: Applied `VectorAssembler` from **PySpark ML** to transform data into the required vector format.
- **Classification Model**: Used `GBTClassifier` (Gradient Boosted Trees) from **PySpark ML** for customer churn prediction.
- **Evaluation**: Assessed model accuracy using `BinaryClassificationEvaluator` to measure the model's predictive performance.

### Results
The model successfully predicts customer churn with high accuracy, showcasing the effectiveness of Spark's ML library in handling large-scale data for classification tasks.
