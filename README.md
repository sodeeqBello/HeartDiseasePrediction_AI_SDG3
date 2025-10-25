## 🩺 Heart Disease Prediction – AI for Sustainable Development (SDG 3)
## 📘 Project Overview
This project demonstrates how Artificial Intelligence (AI) and Machine Learning (ML) can contribute to achieving the United Nations Sustainable Development Goal 3 (SDG 3): Good Health and Well-being.
Cardiovascular diseases (CVDs) are one of the world’s leading causes of death, responsible for over 17 million deaths annually. Early detection is essential to reducing mortality rates. This project leverages Machine Learning models to predict the likelihood of heart disease based on medical and lifestyle data.
By enabling early risk identification, the project supports Target 3.4 — reducing premature mortality from non-communicable diseases through prevention and treatment.
## 🎯 Project Objectives
 - To build a predictive AI model for identifying individuals at high risk of heart disease.
 - To demonstrate the application of supervised learning techniques in healthcare.
 - To support the SDG 3 vision of ensuring healthy lives and promoting well-being for all ages.
## 🧠 Machine Learning Approach
1. Learning Type
Supervised Learning — classification problem (disease presence or absence).

2. Models Used
Logistic Regression
Random Forest Classifier

3. Dataset
The project uses the Heart Disease Dataset (UCI) hosted on Kaggle, containing various clinical features such as:
Age, Sex, Chest Pain Type, Cholesterol, Blood Pressure, Max Heart Rate, and more.

* 📦 Dataset Link: Heart Disease Dataset (UCI) – Kaggle
* 🙏 Acknowledgment:
  Special thanks to Ketan Gangal, the dataset provider, for making this valuable resource publicly available for research and learning purposes.

## ⚙️ Tools and Technologies
| Tool	| Purpose |
| ---- | ---- |
| Python (3.x)	| Programming language |
|Google Colab |	Development environment |
|Pandas, NumPy |	Data processing |
|Matplotlib, Seaborn |	Visualization|
|Scikit-learn |	Machine Learning models|
|Joblib	| Model saving (optional)|
## 🧩 Project Workflow
**Step 1: Data Loading & Exploration**
 - Mounted Google Drive and loaded the dataset from /data/heart.csv.
 - Checked for null values, duplicates, and column statistics.
 - Visualized correlations using a heatmap.

**Step 2: Data Preprocessing**
 - Encoded categorical variables.
 - Normalized numeric features.
 - Split dataset into 80% training and 20% testing sets.

**Step 3: Model Training**
 - Trained two ML models — Logistic Regression and Random Forest Classifier.

**Step 4: Model Evaluation**
|Model | Accuracy |
| --- | ---|
|Logistic Regression |	79.5% |
|Random Forest |	98.5%|
 - Random Forest performed best, capturing complex data relationships.

**Step 5: Visualization**
 - Feature importance chart highlighted key predictors such as cholesterol, max heart rate, and chest pain type.

**Step 6: Ethical Reflection**
 - Bias minimized through normalization and consistent data sampling.
 - Dataset is anonymized and publicly available — ensuring privacy and ethical use.

## 🌍 SDG 3 Alignment – Good Health and Well-being
|SDG Target	| How This Project Contributes |
| --- | --- | 
| 3.4 – Reduce premature mortality from non-communicable diseases | AI model assists in the early detection of heart risks |
| 3.d – Strengthen health capacity | Provides data-driven insights for better health planning|

## 🧪 Results Summary
 - The Random Forest model achieved 98.5% accuracy, indicating high predictive reliability.
 - Enables early detection of heart disease risk, potentially reducing mortality through preventive healthcare.
 - Forms a foundation for community-level health monitoring and AI-driven medical diagnostics.

## 🧭 Future Improvements
 - Integrate real-time patient data via APIs.
 - Deploy a web-based prediction interface using Flask or Streamlit.
 - Expand dataset to include more diverse populations for fairness and generalization.

## 🧑‍⚖️ Ethical & Sustainability Considerations
 - Fairness: Ensure inclusive datasets representing all demographics.
 - Transparency: Clearly document data sources and methodologies.
 - Sustainability: Promote low-cost, scalable healthcare AI solutions for underserved regions.

## 🫶 Acknowledgments
This project was created as part of the PLP Academy – AI for Sustainable Development program.
Gratitude to:
 - PLP Instructors for guidance and mentorship.
 - Ketan Gangal (Kaggle) for the Heart Disease Dataset (UCI) - https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci?
 - Open-source AI community for providing accessible learning tools and frameworks.

## 💬 Author
 - Sodeeq Opeyemi Bello
 - Email: bellosodeeq87@gmail.com
 - GitHub: @sodeeqbello

> “AI can be the bridge between innovation and sustainability.” – UN Tech Envoy
