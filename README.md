# Liver Disease Detection Project
![Liver-Disease-scaled](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/c5e252a0-3089-4924-9a45-7ef38f67d6c8)
In this project, we used the Liver Patient Records dataset.
The objective of this project is to predict the risk of liver disease in individuals. It uses machine learning algorithms to predict the likelihood of a person developing liver disease based on health records.
Ultimately, the combination of clinical, laboratory and machine learning algorithms can be used to assess the risk of Liver Disease in individuals, and help to provide personalized interventions to help reduce the risk.

# Dataset
Dataset consist of 615 patient records with 13 variable that potentially impact wheather someone has liver disease. These variables include age, gender,bilirubin, albumin, alanine aminotransferase, and proteins, etc.
There is one column name Category it has few status like no disease, suspect disease, hepatitis, fibrosis and cirrhosis.
# EDA
* The percentage of category disease
![Screenshot 2024-07-11 231509](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/3adf7036-28a3-4e1d-935c-b4b0aba65997)
# Auto EDA
* Sweetviz

![Screenshot 2024-01-26 182627](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/00343280-8969-41b4-b015-69d1a00e8d46)
# Feature Engineering
* LabelEncoder for Category disease
# Balancing the Data
* SMOTE for leveling  As the given data is not balanced, we have balanced the training dataset using SMOTE (Synthetic Minority Over-Sampling technique)
![download](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/e3f0f5f9-5eea-46b8-8d3f-90c2890d9aa6)
# Model Building
* Model	                    Accuracy
*	LogisticRegression	     0.918699
* Naive Bayes	             0.894309
*	RandomForestClassifier	 0.934959
*	Gradient Boost	         0.934959
*	SVM	                     0.910569

Here we can observe that Random Forest Classifier model is having highest accuracy among all the other models. So we used Random Forest model for deployment.
# Model Deployment Using Streamlit
![Screenshot 2024-01-26 174305](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/dbc41149-6253-4671-ae1c-d3400bbfae2e)
![Screenshot 2024-01-26 174318](https://github.com/Niro105/Liver-Disease-Detection/assets/126443419/b1f73a9f-db68-4b77-a853-f04ddb3503ef)

# Conclusion
In conclusion, the Random forest-based model for liver disease prediction demonstrates promising results, showcasing its potential in accurately classifying individuals at risk. Further validation and real-world testing are essential to solidify its reliability and applicability in clinical settings. Continuous refinement and integration of diverse datasets may enhance the model's robustness, ultimately contributing to more effective early detection and management of liver diseases.

