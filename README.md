# Mental Health in Tech Survey – Data Preprocessing  

## 📌 Overview of the Project  
This project focuses on **data preprocessing** of a survey dataset related to mental health in tech workplaces. The process involves several key steps to clean, standardize, and prepare the data for analysis or modeling.  

---

## 📊 Dataset Details  
- **Source File:** `survey.csv`  
- **Domain:** Mental health in the tech industry  
- **Final Dataset Shape:** **1219 rows × 51 columns**  
- Data is processed sequentially through multiple Jupyter notebooks.  

---

## 👥 Group Member Roles  

| Member ID    | Role                  | Description                                                                 |
|--------------|-----------------------|-----------------------------------------------------------------------------|
| IT24102436   | Missing Values Handling | Identify and manage missing data to ensure dataset completeness.            |
| IT24101538   | Gender Standardization | Clean and standardize the `Gender` feature for consistency.                 |
| IT24100253   | Outlier Removal        | Detect and remove outliers to prevent skewed analysis.                      |
| IT24101019   | Normalization          | Transform numerical features to a standard scale for modeling.              |
| IT24102198   | Encoding               | Convert categorical data into numerical form suitable for ML models.        |
| IT24100667   | Feature Engineering    | Create new features to enhance model performance and reveal relationships.  |

---

## ⚙️ How to Run the Code  

The preprocessing must be executed in the **following order**, as each step produces a new dataset for the next step:  

1. **Missing Data Handling**  
   - Notebook: `IT24_Missing_Data_Handling.ipynb`  
   - Input: `survey.csv`  
   - Output: `survey_cleaned.csv`  

2. **Gender Standardization**  
   - Notebook: `IT24_Gender_Standardizing.ipynb`  
   - Input: `survey_cleaned.csv`  
   - Output: `survey_cleaned_II.csv`  

3. **Outlier Removal**  
   - Notebook: `IT24_Outlier_Removal.ipynb`  
   - Input: `survey_cleaned_II.csv`  
   - Output: `survey_no_outliers.csv`  

4. **Normalization**  
   - Notebook: `IT24_Normalization.ipynb`  
   - Input: `survey_no_outliers.csv`  
   - Output: `survey_scaled.csv`  

5. **Encoding**  
   - Notebook: `IT24_Encoding.ipynb`  
   - Input: `survey_scaled.csv`  
   - Output: `survey_encoded.csv`  

6. **Feature Engineering**  
   - Notebook: `IT24100667_Feature_Engineering.ipynb`  
   - Input: `survey_encoded.csv`  
   - Output: `survey_final_features.csv`  


