## 📊 Overview

This project applies advanced machine learning and deep learning models to forecast hospitalization trends related to respiratory viruses, focusing on COVID-19 in the USA. The goal is to assist healthcare systems in planning and resource allocation, using CDC's real-world hospitalization data.

📍 Project Duration: Jan 2024 – April 2024  
👩‍🔬 Team: Bala Sai Santhoshi, Venkata Sai Swaroop, Kesari Nandan, Ruchita Das ,Raja Pavan Kalyan.
📚 Institution: Under the supervision of Prof. Masoud Soroush, DATA-602

## 🎯 Why This Project?

The COVID-19 pandemic underscored the urgent need for data-driven decision-making in healthcare. By predicting hospitalizations, this project aims to:

- Optimize health resource allocation
- Enhance emergency preparedness
- Inform public health policies
- Support data-driven pandemic response

## 🗃️ Dataset

- 📌 Source: [CDC Respiratory Virus Response (RVR)](https://data.cdc.gov/Public-Health-Surveillance/Respiratory-Virus-Response-RVR-United-States-Hospi/9t9r-e5a3)
- 📊 Rows: ~84,000 | 🧬 Columns: 115
- 📅 Time Range: Jan 2021 – Early 2024
- 📍 Coverage: National, HHS region, state/territory level
- 👶 Pediatric Focus: COVID admissions segmented by age groups (0–4, 5–11, 12–17)

## 🛠️ Methodology

1. **Data Cleaning**: Handled missing values, removed >50% null columns, managed duplicates
2. **Exploratory Data Analysis**: Seasonal peaks, state-level trends, age-group insights
3. **Feature Selection**: Correlation matrix, random forest importance ranking
4. **Modeling**:
   - 🔁 Regression: Linear, Polynomial, Decision Tree, SVR, XGBoost, Random Forest
   - 🧠 Neural Nets: Classic and CNN architectures
   - 🧪 Ensemble: Stacking classifier
5. **Evaluation**: R², MSE, accuracy %, generalization vs. overfitting analysis

## 📈 Results

- 🔍 **Best Model**: Random Forest Regressor (R² ≈ 0.96)
- 🧠 CNN performed with R² ≈ 0.83 and good validation visualization
- ⚙️ XGBoost and Ensemble models showed high consistency across test/train
- 🚑 Key Factors: Age, flu comorbidity, bed availability, region, and season



## Visuals 
#### 📈 COVID-19 Hospital Admissions Over Time
This line graph shows the number of all confirmed COVID-19 hospital admissions across the USA over time. You can clearly see the surges and seasonal waves, especially during winter months 
<img width="612" alt="image" src="https://github.com/user-attachments/assets/277946e7-497e-4a12-93e5-8b7f15c8a22c" />

#### 🔥 Feature Correlation Heatmap
This heatmap displays the correlation between numerical features in the hospitalization dataset. It helps identify relationships between variables like:
COVID-19 admissions by age group
ICU and bed occupancy rates
Hospital reporting metrics
<img width="968" alt="image" src="https://github.com/user-attachments/assets/e266b0f0-1304-4224-9ecd-101714f53e85" />

## Results 
Model Performance Comparison (R² Scores)
<img width="607" alt="image" src="https://github.com/user-attachments/assets/f3383506-eea5-4ec5-a438-97f658b9ed40" />

The Random Forest and Classic Neural Network models show the highest predictive accuracy, while models like SVR and Stacking performed less effectively.



## 🌍 Insights & Public Health Impact

- 🎯 High-risk groups and seasons identified (elderly, winter months)
- 🗺️ Regional disparities in hospitalization trends
- 🏥 Predictions support proactive bed/staff allocation
- 📢 Can guide future policy on vaccinations, masking, and outreach


## Goal of This Project
The goal of this project is to develop predictive models that forecast COVID-19 hospitalizations using data provided by the Centers for Disease Control and Prevention (CDC) on the website cdc.gov
By doing so, the project aims to help healthcare systems in the United States allocate resources more effectively and manage healthcare services more efficiently during the pandemic.
This will ultimately improve health outcomes and reduce the impact of the pandemic in the future.

 ## 🧑‍💻 Team & Contributions
This project was collaboratively developed as part of the Data 602 course under the guidance of **Prof. Masoud Soroush**. Each team member played a key role in bringing this project to life.

| Name | Contributions |
|------|---------------|
| **Raja Pavan Kalyan** | Data preprocessing, Feature engineering, Model building (Random Forest, SVR) |
| **Bala Sai Santhoshi** | Exploratory Data Analysis (EDA), Visualization, Model tuning (XGBoost, AdaBoost) |
| **Venkata Sai Swaroop** | Neural Network implementation, CNN structure, Model evaluation and comparison |
| **Kesari Nandan** | Dataset research, Missing data handling, Literature review |
| **Ruchita Das** | Report writing, Presentation design, Insights and public health impact analysis |

🧪 Built using: **Python, Scikit-learn, Pandas, Matplotlib, Seaborn, TensorFlow/Keras**

🤝 Collaboration powered by: **Jupyter Notebooks + GitHub**


## Conclusion 
Insightful Patterns Identified: Our models have identified that age and pre-existing health conditions are significant predictors of hospitalization due to respiratory viruses. Seasonal trends also play a crucial role, with spikes in hospitalizations typically occurring in the winter months.
Geographical Variations: There are notable differences in hospitalization rates across different states, indicating that local health policies and population density may influence these trends.
Resource Allocation: Our models can inform health authorities about potential spikes in hospitalizations, allowing for better resource allocation, such as beds and medical staff.
Policy Formulation: Insights from the models can guide public health policies, particularly in vaccination drives and public health advisories.



