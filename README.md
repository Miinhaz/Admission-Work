
# Predictive Modeling, Interpretability, and Sustainability in Public University Admissions: A Case Study from Bangladesh

## Overview

This repository contains the code, data, and results of the study titled *"Predictive Modeling, Interpretability, and Sustainability in Public University Admissions: A Case Study from Bangladesh"*. The study employs machine learning classifiers to analyze factors influencing university admissions in Bangladesh and explores the use of explainable AI techniques like SHAP and LIME to interpret model predictions. The ultimate aim is to improve the transparency, equity, and inclusivity of the admissions process, particularly for underrepresented students.

## Research Objectives

- **Predictive Modeling:** Utilizing machine learning classifiers such as Bagging, Random Forest, Gradient Boosting, and Extra Trees to predict admission outcomes based on a variety of factors.
  
- **Interpretability:** Applying SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) to interpret the results and understand the influence of key factors on admission success.
  
- **Sustainability in Higher Education:** The study advocates for targeted interventions and systemic changes to make university admissions more equitable and sustainable.

## Data Description

The dataset used in this study was collected via an online survey and includes 15 attributes that are crucial to predicting university admission success. These attributes encompass academic achievements, socio-economic factors, and access to resources.

The dataset is available in the file `Undergraduate.csv`.

## Repository Structure

- **Insights From dataset:** Contains the initial analysis with the raw dataset before any sampling techniques are applied.
  
- **Over sampling:** Contains the analysis conducted on oversampled data to handle class imbalance.
  
- **Under sampling:** Contains the analysis conducted on undersampled data to handle class imbalance.
  
- **without sampling:** Contains the analysis conducted using the raw data without any sampling techniques applied.
  
- **Sustainable_Future_Admission.pdf:** The final paper detailing the study, findings, and recommendations.
  
- **Undergraduate.csv:** The raw dataset with attributes relevant to university admission predictions.

## Key Findings

- **Predictive Accuracy:** Various machine learning classifiers were evaluated, and their performance was compared using metrics like accuracy, precision, recall, and F1-score.
  
- **Feature Importance:** SHAP and LIME were used to identify the most influential features in the admissions process, such as academic performance and socio-economic background.
  
- **Recommendations:** The study highlights the importance of supporting underrepresented students and making the admissions process more inclusive.

## Methodology

1. **Data Preprocessing:** The data was cleaned, and missing values were handled before applying machine learning algorithms.
  
2. **Handling Class Imbalance:** Different strategies like oversampling, undersampling, and no sampling were applied to address the imbalance in the dataset.
  
3. **Model Training:** Several machine learning models were trained and tuned using Grid Search for hyperparameter optimization.

4. **Explainable AI:** SHAP and LIME were used to provide transparent explanations for model predictions, helping us understand the contribution of different features to the admission outcomes.

## Threats to Validity

While the methodology is robust, potential threats to validity exist:

- **Selection Bias:** The data collected via online surveys may not fully represent the entire demographic of university applicants in Bangladesh.
  
- **Construct Validity:** Other unexamined factors may also influence admissions.
  
- **Sample Size Disparity:** The sample size between students from public and private universities may impact the robustness of the findings.

## Future Work

- **Data Expansion:** Gathering more diverse data could improve the generalizability of the results.
  
- **Additional Explainable AI Techniques:** The use of other explainable AI methods like Integrated Gradients and DeepLIFT could provide additional insights.
  
- **Longitudinal Study:** A future study could focus on the long-term impacts of the findings and recommendations on admissions systems.


