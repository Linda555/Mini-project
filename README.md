# Mini-project

In this project, the key factors influencing mental health are investigated. The primary focus is on a variable called Severity, where participants ranked as low, medium, or high in perceived mental health after visiting a healthcare specialist. 

The dataset 
Includes demographic information (age, gender, occupation), lifestyle factors (sleep duration, physical activity), and psychological indicators (stress levels, consultation history).

Method
A Random Forest model was used to rank feature importance, while XGBoost was applied for classification accuracy across the low, medium, and high severity levels. XGBoost was chosen for its strong performance in predictive models with imbalanced data. Random Forest was selected for its robustness in handling small datasets, ensuring reliable feature importance rankings despite potential sample size limitations. Additionally, statistical correlation analyses were conducted to validate the relationships identified by the models, enhancing the robustness of the results.

