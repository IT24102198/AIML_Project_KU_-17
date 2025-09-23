
Overview of the project
This project focuses on the data preprocessing of a survey dataset related to mental health in tech workplaces. The process involves several key steps to clean, standardize, and prepare the data for analysis or modeling.


Dataset Details
The dataset used is a survey containing information about mental health in the tech industry. It is loaded from a CSV file named survey.csv and is processed sequentially through the notebooks. After all the preprocessing steps, the final dataset has a shape of 1219 rows and 51 columns.


Group Member Roles
IT24102436 - Missing values handling: This role involves identifying and managing missing data in the dataset to ensure it's complete and accurate.
IT24101538 - Gender Standardization: This role focuses on cleaning and standardizing the 'Gender' feature so all entries are consistent and properly categorized.
IT24100253 - Outlier Removal: This role is responsible for identifying and removing outliers, which are data points that can skew analysis.
IT24101019 - Normalization: This role involves transforming numerical features to a standard scale, which is crucial for many machine learning algorithms.
IT24102198 - Encoding: This role handles the conversion of text-based, categorical data into a numerical format that machine learning models can process.
IT24100667 - Feature Engineering: This role involves creating new features from existing ones to improve model performance and expose new relationships in the data.



How to Run the Code
The notebooks are designed to be run in a specific order, as each step saves a cleaned version of the dataset that is then used as input for the next step. Follow these steps to run the code:

Missing Data Handling: Run IT24_Missing_Data_Handling.ipynb first. This notebook reads the original survey.csv and saves a cleaned version as survey_cleaned.csv.

Gender Standardization: Run IT24_Gender_Standardizing.ipynb. It loads survey_cleaned.csv and saves the updated file as survey_cleaned_II.csv.

Outlier Removal: Run IT24_Oulier_Removal.ipynb. This notebook takes survey_cleaned_II.csv as input and saves the data without outliers to survey_no_outliers.csv.

Normalization: Run IT24_Normalization.ipynb. This notebook reads survey_no_outliers.csv, normalizes the data, and saves it as survey_scaled.csv.

Encoding: Run IT24_Encoding.ipynb. This notebook uses survey_scaled.csv as its input.


Feature Engineering: Finally, run IT24100667_Feature_Engineering.ipynb. This notebook reads the encoded data from survey_encoded.csv and performs feature engineering, saving the final principal components as survey_final_features.csv.

