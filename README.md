# Stroke Prediction Project

## I. Introduction:

In order to determine the elements that contribute to the occurrence of strokes, this data science project will examine a dataset of stroke patients and create a predictive model. Stroke is a devastating medical disorder that impacts millions of individuals worldwide. By understanding the major risk factors, stroke can be better prevented and treated. 

The dataset is composed of 43,400 patient records, each of which contains details about the patient's demographics, medical background, way of life, and other health markers. The project's goal is to identify the major stroke risk factors and to create a model that can precisely predict the possibility of a stroke occurring based on these factors. 

Accuracy, precision, recall, and F1-score are some of the measures that will be used to assess the project's outcomes. The report concludes with an assessment of the findings' implications and recommendations for further study or development. The outcomes of patients could be improved by using the project's findings to guide stroke prevention and treatment measures.

## II. Data Information:

- **Dataset:** Stroke Patients Dataset
- **Number of Records:** 43,400
- **Features:** Demographics, Medical History, Lifestyle Factors, Health Markers
- **Target Variable:** Stroke (Yes/No)

## III. Methodology:

1. **Data Preprocessing:** Cleaning the dataset, handling missing values, encoding categorical variables, and scaling numerical features.
   
2. **Exploratory Data Analysis (EDA):** Analyzing the distribution of features, identifying correlations, and visualizing relationships between variables.
   
3. **Feature Selection:** Selecting relevant features that have a significant impact on stroke prediction.
   
4. **Model Building:** Building and training machine learning models using various algorithms such as Logistic Regression, Random Forest, and Gradient Boosting.
   
5. **Model Evaluation:** Evaluating models using performance metrics like accuracy, precision, recall, and F1-score. Tuning hyperparameters to improve model performance.
   
6. **Final Model Selection:** Selecting the best-performing model based on evaluation metrics and using it for stroke prediction.

## IV. Results:

- The logistic regression model achieved an AUC of 0.85 on the test set, indicating good predictive performance.
- The accuracy, precision, recall, and F1 score of the logistic regression model were 0.97, 0.13, 0.1, and 0.11, respectively.
- Logistic regression outperformed KNN and SVM models in terms of AUC and F1 score, suggesting it may be the optimal solution for this specific stroke dataset.
  
## V. Discussion:

The logistic regression model appears to be better than the KNN and SVM models in terms of AUC and F1 score, demonstrating that it is a more accurate model for predicting the occurrence of strokes. However, by investigating additional models or adjusting the hyperparameters of the logistic regression model, significant advancements can be achieved. The fact that KNN and SVM have precision, recall, and F1 scores being very small may, however, be a warning regarding the quality of our data.

## VI. Conclusion:

The project successfully identified key risk factors for stroke and developed a predictive model to assess stroke risk in patients. By leveraging these findings, healthcare professionals can implement targeted interventions and preventive measures to reduce the incidence of strokes and improve patient outcomes.

## VII. Future Work:

- Explore additional datasets to further validate the model and identify additional risk factors.
- Investigate the impact of lifestyle modifications and medical interventions on reducing stroke risk.
- Collaborate with healthcare providers to integrate the predictive model into clinical practice for personalized stroke prevention strategies.
