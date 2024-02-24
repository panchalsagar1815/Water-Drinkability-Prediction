# Water-Drinkability-Prediction

**Project: Water Drinkability Prediction**

**Objective:**
The Water Drinkability Prediction project focuses on assessing the potability of water based on various chemical and physical features. The dataset comprises key parameters such as pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, Turbidity, and Potability. Through data preprocessing, cleaning, and machine learning models, the goal is to predict whether water is suitable for consumption.

**Data Processing:**
1. **Data Cleaning and Preprocessing:**
   - Addressed missing values, outliers, and inconsistencies in the dataset.
   - Ensured data quality and integrity for accurate predictions.
2. **Data Visualization and EDA:**
   - Explored relationships, distributions, and correlations through visualizations.
   - Gained insights into the characteristics affecting water potability.

**Machine Learning Models:**
Utilized a range of machine learning models for prediction:
1. **Logistic Regression:**
   - Used for binary classification to predict water potability.
   - Provided insights into the linear relationship between features.
   
2. **K-Nearest Neighbors (KNN) Classifier:**
   - Leveraged for classification based on the similarity of data points.
   - Assessed neighboring instances to determine water potability.

3. **Random Forest Classifier:**
   - An ensemble learning model for improved predictive accuracy.
   - Explored decision trees to capture complex relationships in the data.

4. **Gaussian Naive Bayes (NB):**
   - A probabilistic model based on Bayes' theorem.
   - Assumed independence between features for classification.

5. **Support Vector Classifier (SVC):**
   - Applied to separate potable and non-potable water instances.
   - Explored hyperplane-based classification.

**Model Performance:**
Evaluated model performance based on accuracy:
- Logistic Regression: 62.65%
- K-Nearest Neighbors: 63.57%
- Random Forest Classifier: 80.03%
- Gaussian Naive Bayes: 61.58%
- Support Vector Classifier: 68.29%

**Precision and Recall Calculation:**
Precision and recall metrics were calculated to assess the model's ability to correctly predict potable and non-potable water instances. These metrics provide a comprehensive understanding of the model's performance in practical scenarios.

**Conclusion:**
The Water Drinkability Prediction project successfully employed machine learning models to assess water potability. The Random Forest Classifier demonstrated the highest accuracy, emphasizing its potential for reliable predictions. Precision and recall metrics offer nuanced insights into the model's performance, contributing to informed decision-making regarding water suitability for consumption.
