# Mini-project/Mental Health

In this project, factors influencing mental health are investigated. The primary focus is on a variable called severity, where participants ranked low, medium, or high in perceived mental health after visiting a healthcare specialist. 

The dataset 
Includes demographic information (age, gender, occupation), lifestyle factors (sleep duration, physical activity), and psychological indicators (stress levels, consultation history).

Method
A Random Forest was used to rank feature importance, while XGBoost was applied for classification accuracy across the low, medium, and high severity levels. XGBoost was chosen for its strong performance in predictive models with imbalanced data. Random Forest was selected for its robustness in handling small datasets, ensuring reliable feature importance rankings despite potential sample size limitations. Additionally, statistical correlation analyses were conducted to validate the relationships identified, enhancing the robustness of the result.

Result
The analysis identified sleep hours (R=0.72), stress
levels (R=0.68), and consultation history (R=0.65) as the
most significant predictors of perceived mental health
severity. XGBoost achieved an 81% accuracy rate, with
sleep hours contributing 19%, stress levels 17%, and
consultation history 15% to the model's predictions.
XGBoost weighted f1-score: 0.79.
Educators, finance professionals and health care workers
reported the highest severity scores, aligning with
predictors such as stress and lack of recovery time.
Educators: mean severity score: 1.02. Finance (1.01)
Healthcare Professionals mean severity: 0.98.

Both the mental health condition and the severity variable
were influenced by stress and sleep deprivation. Stress
emerged as a stronger predictor for mental health
condition, while sleep patterns played a more prominent
role in severity. The findings can suggest a cyclical
interaction: stress disrupts sleep, exacerbating both
severity and condition.
These results emphasize the importance of workplace
interventions targeting stress reduction to promot healthy
sleep patterns. Social support was identified as a
potential mitigating factor, particularly for educators and
healthcare workers, where high stress and demands are
prevalent.
