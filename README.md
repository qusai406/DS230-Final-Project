# DS230-Final-Project


## Project Overview
This project focuses on analyzing customer purchasing behavior and predicting whether a product will be reordered using machine learning classification techniques. The project covers data preparation, exploratory data analysis (EDA), and model training and evaluation.


## Dataset
The dataset is based on an online grocery ordering system and includes:
- Orders and order-product interactions
- Product metadata
- Aisle and department information

All datasets are loaded from Google Drive and merged to form a unified dataset for analysis.


## Project Structure
The project is implemented in a single Jupyter Notebook and follows this structure:

1. Mounting Google Drive and setting the data path  
2. Data loading  
3. Data merging  
4. Sampling  
5. Final merging  
6. Exploratory Data Analysis (EDA), including:
   - Post-merge dataset overview  
   - Missing values analysis  
   - Target distribution  
   - Target vs key numeric features  
   - Numeric and categorical feature distributions  
   - Correlation analysis  
   - Correlation with target  
   - Time-based ordering patterns  
   - Outlier analysis  
7. Modeling and evaluation using Random Forest  


## Modeling
A **Random Forest Classifier** was trained to predict the target variable `reordered`.  
Class imbalance was handled using `class_weight="balanced"`.

Model evaluation includes:
- Classification Report
- ROC-AUC score


## How to Run
1. Open the notebook using **Google Colab**.
2. Mount Google Drive when prompted.
3. Ensure the dataset files are located in the specified Google Drive directory.
4. Run the notebook cells sequentially.



## Team Members & Work Distribution
This project was completed collaboratively with equal contribution from both team members:

- **Nour Aldaoud (50%)**: Data loading and merging, exploratory data analysis (EDA), model training, and evaluation.
- **Qusai Rawadieh (50%)**: Data preparation support, exploratory analysis, model evaluation, and result interpretation.

---

## Course
DS230 – Data Science
