#  Rainfall Prediction in Australia

##  Project Overview
This project builds a Machine Learning predictive system to forecast whether it will rain tomorrow in Australia based on historical weather data. The focus of this project is on applying **Dimensionality Reduction** techniques to optimize model performance and efficiency.

##  Technical Approach
1. **Data Preprocessing:** Handled missing values using median (numerical) and mode (categorical), and applied `StandardScaler`.
2. **Hybrid Dimension Reduction:** - **Feature Selection:** Used `SelectKBest` (ANOVA) to select the top 15 most impactful features.
   - **Feature Extraction:** Applied **PCA (Principal Component Analysis)** to compress the 15 features into **8 Principal Components**, eliminating multicollinearity and speeding up computation.
3. **Modeling:** Trained a tuned **Random Forest Classifier** (`class_weight='balanced'`) and compared it against a Logistic Regression baseline.

##  Key Results
- **Accuracy:** Reached **83.54%** using only 8 PCA components (reducing the feature space by >60%).
- **ROC-AUC Score:** ~89%, demonstrating strong pattern recognition capabilities.

## 👥 Team Members
- Ali Ahmed Atef
- Alaa Elnagih
- Nardin Shaker
- Habeba Mazhar
- Zahraa Ashraf
