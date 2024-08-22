# Predicting Real Estate Prices Using Machine Learning

## Project overview

1. We developed a machine learning model to predict real estate prices, aimed at providing investors and real estate developers with a powerful tool to more accurately assess market risks and opportunities.

2. By utilizing MIS and MIC scores, we identified the key factors influencing real estate prices and further validated the importance of these factors through machine learning model.

3. We conducted a comprehensive exploratory data analysis, combining MIS, MIC scores, and the feature importance assessment from the machine learning model to select the most influential features. Additionally, we experimented with over a dozen different machine learning algorithms and optimized the model performance using Gridsearch and stacking techniques, ensuring the model provides the most accurate price predictions.

## EDA

In the exploratory data analysis, I utilized various methods to identify the key features that have the most significant impact on property prices. Here are a few highlights.
![chart1](https://github.com/user-attachments/assets/8eb53109-3598-497c-afe4-b5e8d82edc31)
![chart2](https://github.com/user-attachments/assets/b433e04d-b8c7-42f7-a1f0-036b6ceafaf1)
![chart3](https://github.com/user-attachments/assets/edef4661-1217-405b-bb29-3623a9b5cde8)

## Model Building

1. We applied different feature encoding techniques based on the characteristics of the data, and then we split the dataset into training and test sets, with the test set comprising 25% of the data.
![chart4](https://github.com/user-attachments/assets/c263976c-9b3a-4aa9-b746-de2f64d20f2f)(by Jia Si)  

2. Through exploratory data analysis (EDA), MIC, MIS, and feature importance scores, we ultimately identified the most impactful features.

3. To optimize model performance, we selected two different feature sets—one more comprehensive and the other more streamlined. We will ultimately choose the feature set that maximizes model performance.

4. During the model selection phase, we experimented with twelve different algorithms and calculated their respective scores. I chose R² as the evaluation metric because it is intuitive and effectively measures the model's fit across the entire dataset.

## Model performance
The Gradient Boosting Regressor gives the best result.

Best cross-validation score: 0.870
Final test sample score: 0.902420934571331







