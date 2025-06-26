
# Liver-Cirrhosis-Stage-Prediction

**Liver cirrhosis** is a progressive liver disease marked by damage and scarring. This project uses machine learning to predict the **stage of cirrhosis** a patient is in, based on clinical and biochemical data.

---
![liver structure](https://cdn.lecturio.com/assets/Porta-Hepatis-and-liver-inferior-view.png)

## 🔗 GitHub Repository

👉 [View Full Project on GitHub](https://github.com/Rajithareddy05/liver-cirrhosis-prediction)

---

## 🎯 Objective

Predict the stage of liver cirrhosis based on clinical features. The stages include:

* **Stage 1**: Normal
* **Stage 2**: Fatty Liver
* **Stage 3**: Liver Fibrosis
* **Stage 4**: Liver Cirrhosis

This classification helps in timely treatment planning and disease management.

---

![Liver Stages](https://www.verywellhealth.com/thmb/NrdFXEEHLu7yebnfAg2WJ7skKE0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/SignsofLiverDamageandWaystoTell-final-d2f8ff9d20884a5ea35131a971b96dcb.png)

---

## 🩺 Dataset Context

This dataset comes from the **Mayo Clinic’s PBC (Primary Biliary Cirrhosis) trial**, conducted between 1974–1984. It includes 418 patients with measurements related to liver health, demographics, and survival status.

---

## 📊 Features

| Feature       | Description                                             |
| ------------- | ------------------------------------------------------- |
| ID            | Unique patient ID                                       |
| N_Days        | Days from registration to event or end of study         |
| Status        | C (censored), CL (censored after transplant), D (death) |
| Drug          | Treatment given: D-penicillamine or placebo             |
| Age           | Age in days                                             |
| Sex           | Gender (M/F)                                            |
| Ascites       | Fluid accumulation (Y/N)                                |
| Hepatomegaly  | Enlarged liver (Y/N)                                    |
| Spiders       | Vascular spiders (Y/N)                                  |
| Edema         | N (none), S (controlled), Y (uncontrolled)              |
| Bilirubin     | Serum bilirubin level (mg/dl)                           |
| Cholesterol   | Serum cholesterol (mg/dl)                               |
| Albumin       | Serum albumin (gm/dl)                                   |
| Copper        | Urinary copper (ug/day)                                 |
| Alk_Phos      | Alkaline phosphatase (U/l)                              |
| SGOT          | SGOT enzyme level (U/ml)                                |
| Triglycerides | Triglyceride level (mg/dl)                              |
| Platelets     | Platelet count (per 1000/ml)                            |
| Prothrombin   | Clotting time (seconds)                                 |
| Stage         | Disease stage (1–4)                                     |

---

## ⚙️ Project Pipeline

1. **Data Preprocessing** – Handle missing values, encode categorical features
2. **EDA** – Explore trends, outliers, and relationships
3. **Feature Engineering** – Select and transform relevant features
4. **Model Building** – Use ML models like Random Forest, XGBoost, and SVM
5. **Evaluation** – Measure accuracy, precision, recall, F1-score, and confusion matrix
6. **Prediction** – Predict patient liver stage from clinical data

---

![Machine Learning Workflow](https://www.mdpi.com/livers/livers-01-00023/article_deploy/html/images/livers-01-00023-g001.png)

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **XGBoost**
* **VS Code / Jupyter Notebook**

---

## 📚 Acknowledgements

Data Source:

> Fleming, T.R. and Harrington, D.P. (1991).
> *Counting Processes and Survival Analysis*, Wiley Series in Probability and Mathematical Statistics.
