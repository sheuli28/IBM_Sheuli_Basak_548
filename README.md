# Predicting Eligibility for Social Welfare Schemes using Machine Learning

## 📜 Project Overview
This project focuses on automating the allocation of *National Social Assistance Program (NSAP)* welfare schemes using *Machine Learning*.  
The NSAP program provides financial assistance to elderly, widows, and disabled individuals from below-poverty-line (BPL) households.  
Manual verification of applications is time-consuming and error-prone, leading to delays in delivering benefits.  
We developed a *multi-class classification ML model* to predict the most suitable NSAP scheme for applicants based on their demographic and socio-economic data.

---

## 🎯 Objectives
- Automate eligibility classification for multiple NSAP schemes.
- Minimize human errors and reduce verification time.
- Build a scalable and deployable ML model to assist government welfare programs.

---

## 🗂️ Dataset
- *Source:* Open Government Data (OGD) India (synthetic & anonymized for project use)
- *Records:* 2085  
- *Features:* 16 demographic and socio-economic attributes (state, district, Aadhaar availability, gender counts, caste data, etc.)  
- *Target:* schemecode (multi-class classification)

---

## 🧰 Technologies Used
- *Programming Language:* Python  
- *Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- *Model:* Random Forest Classifier  
- *Environment:* Jupyter Notebook, IBM Cloud  
- *IBM Services:*
  - IBM Cloud Object Storage
  - IBM Watson Studio
  - IBM Watson Machine Learning
  - IBM Cloud Pak for Data

---

## ⚙️ Model Performance
| Metric          | Score   |
|-----------------|---------|
| Accuracy        | 99.04%  |
| Precision       | ~99%    |
| Recall          | ~99%    |

- High accuracy and balanced precision/recall indicate strong model performance.
- Key predictive features: Aadhaar availability, gender distribution, caste category.

---

## 📊 Visualizations
- Confusion Matrix for model evaluation  
- Feature Importance chart to identify key attributes  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sheuli28/IBM_Sheuli_Basak_548.git
