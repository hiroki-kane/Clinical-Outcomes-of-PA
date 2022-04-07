# Machine Learning-Based Models for Predicting Clinical Outcomes After Surgery in Unilateral Primary Aldosteronism

This repository contains code of the study published [here](https://www.nature.com/articles/s41598-022-09706-8) in Scientific Reports Journal.

## Abstruct
Unilateral subtype of primary aldosteronism (PA) is a common surgically curable form of endocrine hypertension. However, more than half of the patients with PA who undergo unilateral adrenalectomy suffer from persistent hypertension, which may discourage those with PA from undergoing adrenalectomy even when appropriate. The aim of this retrospective cross-sectional study was to develop machine learning-based models for predicting postoperative hypertensive remission using preoperative predictors that are readily available in routine clinical practice. A total of 107 patients with PA who achieved complete biochemical success after adrenalectomy were included and randomly assigned to the training and test datasets. Predictive models of complete clinical success were developed using supervised machine learning algorithms. Of 107 patients, 40 achieved complete clinical success after adrenalectomy in both datasets. Six clinical features associated with complete clinical success (duration of hypertension, defined daily dose (DDD) of antihypertensive medication, plasma aldosterone concentration (PAC), sex, body mass index (BMI), and age) were selected based on predictive performance in the machine learning-based model. The predictive accuracy and area under the curve (AUC) for the developed model in the test dataset were 77.3% and 0.884 (95% confidence interval: 0.737–1.000), respectively. In an independent external cohort, the performance of the predictive model was found to be comparable with an accuracy of 80.4% and AUC of 0.867 (95% confidence interval: 0.763–0.971). The duration of hypertension, DDD of antihypertensive medication, PAC, and BMI were non-linearly related to the prediction of complete clinical success. The developed predictive model may be useful in assessing the benefit of unilateral adrenalectomy and in selecting surgical treatment and antihypertensive medication for patients with PA in clinical practice.

## About the data
The data used to develop the model included:  
AGE = age at diagnosis of primary aldosteronism  
BMI = body mass index  
Clinical_outcome = achieve complete clinical success or not  
DDD = defined daily dose of antihypertensive medication  
DURATION = duration of hypertension (years)  
PAC = plasma aldosterone concentration  
SEX = sex of the patient

Each institution owns the data of its own institution, and restrictions apply to the availability of these data, which were used under license for the current study and therefore are not publicly available. Data are, however, available from the authors upon reasonable request and with permission from each institute.

## Requirements
#### Tested Config
- conda : 4.10.3
- python : 3.7.11
- scikit-learn : 0.24.2

## Cite this work
Hiroki Kaneko, Hironobu Umakoshi, Masatoshi Ogata, et al. Machine Learning-Based Models for Predicting Clinical Outcomes After Surgery in Unilateral Primary Aldosteronism. Sci Rep 12, 5781 (2022). https://doi.org/10.1038/s41598-022-09706-8.
