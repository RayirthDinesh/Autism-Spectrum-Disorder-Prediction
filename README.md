# Autism-Spectrum-Disorder-ASD-Prediction

Abstract:
This research aims to accurately diagnose Autism Spectrum Disorder (ASD) and identify significant predictors of ASD using demographic, genetic, behavioral, and other medical history data. The importance of this study lies in addressing the high prevalence of ASD without a functional means of prevention. Identifying what factors have little to significant impact on a patient's risk of bearing this disorder can help research in this field reach a step closer to finding a viable means of prevention. 

The study collected data from clinical assessments and analysis techniques such as statistical modeling and machine learning algorithms, including regression analysis and neural networks. These methods were used to identify patterns and accurately diagnose ASD. Logistic regression, random forest, and neural network models achieved over 85% accuracy in predicting ASD. The Autism Spectrum Quotient (AQ) 10-item screening tool and AQ1-10 screening test scores showed the strongest association with ASD, with scores above 50%. 

The major conclusions indicate that factors like age, gender, and ethnicity have weak associations with ASD diagnosis. In contrast, having an immediate family member diagnosed with autism and high scores on the AQ1-10 screening test shows moderate to strong associations with ASD diagnosis.


Features:
1. ID - ID of the patient
2. A1_Score to A10_Score - Score based on Autism Spectrum Quotient (AQ) 10 item screening tool
3. age - Age of the patient in years
4. gender - Gender of the patient
5. ethnicity - Ethnicity of the patient
6. jaundice - Whether the patient had jaundice at the time of birth
7. autism - Whether an immediate family member has been diagnosed with autism
8. contry_of_res - Country of residence of the patient
9. used_app_before - Whether the patient has undergone a screening test before
10. result - Score for AQ1-10 screening test
11. age_desc - Age of the patient
12. relation - Relation of patient who completed the test
13. Class/ASD - Classified result as 0 or 1. Here 0 represents No and 1 represents Yes. This is the target column, and during submission submit the values as 0 or 1 only.
