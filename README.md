
# Liver-Cirrhosis-Stage-Prediction

**Liver cirrhosis** is a progressive liver disease marked by damage and scarring. This project uses machine learning to predict the **stage of cirrhosis** a patient is in, based on clinical and biochemical data.

---

![Liver Structure](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.neuraldesigner.com%2Flearning%2Fexamples%2Fdiagnose-hcv%2F&psig=AOvVaw1Z8iiCF9J0E4tvnJwSaN3M&ust=1751041764119000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJjk44TBj44DFQAAAAAdAAAAABAE)

---

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

![Liver Stages](https://img.freepik.com/free-vector/informative-illustration-stages-liver-disease-leading-cirrhosis_1308-50030.jpg?w=1380&t=st=1719405003~exp=1719405603~hmac=5d11077a0ed6d62289a60ee3cc05f5822151fc8cd88b027d8cb24ebdee6fa6b6)

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

![Machine Learning Workflow](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/03/Pipeline-1024x292.jpg)

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
