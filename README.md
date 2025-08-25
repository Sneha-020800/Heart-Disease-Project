# ❤ Heart Disease Project

This project explores and analyzes a heart disease dataset using *Python* and *Jupyter Notebook*.  
The goal is to perform *Exploratory Data Analysis (EDA)*, create visualizations, and gain insights into factors that may influence the likelihood of heart disease.

## 📂 Project Structure
- Heart_Disease_Project.ipynb → Jupyter Notebook containing all the code, analysis, and visualizations.  
- heart_disease_dataset.xlsx → Dataset used for analysis.  

## ⚙ Installation & Requirements
To run this project locally, install the following dependencies:

```bash
pip install pandas matplotlib seaborn jupyter

Required libraries:

Python 3.x
pandas
matplotlib
seaborn
Jupyter Notebook

▶ How to Run

1. Clone this repository or download the ZIP file.

git clone https://github.com/yourusername/Heart-Disease-Project.git

2. Open the folder in Jupyter Notebook.

3. Run the notebook Heart_Disease_Project.ipynb step by step.

📊 Analysis Workflow

Performed data cleaning and preprocessing (renamed columns, handled missing values, removed duplicates) on a heart disease dataset with 3,069 records.

Conducted exploratory data analysis (EDA) to uncover trends and risk factors using countplots, histograms, and heatmaps.

Found that 40% of patients had heart disease (1,239 out of 3,069), with cases most common in the 50–80 years age group and among males.

Identified risk factors:

Chest pain: atypical angina most common, but chest pain type alone did not clearly separate diseased vs non-diseased.

Resting BP: 72.69% of patients at risk (≥120 mmHg).

Cholesterol: 70% had borderline or high cholesterol, strongly linked with heart disease.

BMI & Lifestyle: 39% obese, 35% smokers → both emerged as significant risk contributors.

Fasting blood sugar: Higher sugar levels more frequent in diseased patients, but most cases fell in the normal range.

Created data visualizations (countplots, histplots, subplots, heatmaps) to communicate insights effectively.

📸 Example Visualizations

Age distribution of patients

Chest pain type vs Heart Disease

Correlation heatmap of all features

Subplots of various features

📜 License

This project is licensed under the MIT License.
You are free to use, modify, and share this work with proper attribution.

👩‍💻 Author

Sneha Dhingra
A data science enthusiast exploring health-related datasets to gain practical insights.
