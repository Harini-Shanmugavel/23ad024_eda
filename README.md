# Student Performance Case Study

## Project Overview
This project analyzes and predicts student performance using the Students Performance in Exams dataset from Kaggle. The dataset has been enriched through feature engineering to create **≥15 features** for predictive modeling. The project includes data preprocessing, feature engineering, EDA and visualizations, a Deep Learning model (MLP) for classifying student performance levels, and model evaluation using accuracy, confusion matrix, and ROC-AUC.

## Folder Structure
Student_Performance_CaseStudy/
├── student_performance_case_study.ipynb # Full Jupyter notebook with code
├── StudentsPerformance.csv # Dataset (or provide Kaggle link)
├── Report.pdf # Project report
├── README.md # This file
└── plots/ # Optional folder to save generated plots
## How to Run
1. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
Load the dataset:

Place StudentsPerformance.csv in the working directory

OR mount Google Drive in Colab and update the DATA_PATH in the notebook

Open and run the notebook:

Open student_performance_case_study.ipynb in Jupyter or Google Colab

Run all cells from top-to-bottom

Visualizations:

All plots are generated in the notebook

Optionally, save plots using:

plt.savefig('plots/plot_name.png', dpi=300)


Model Evaluation:

Check the final accuracy, classification report, confusion matrix, and ROC-AUC metrics in the notebook

Dataset

Kaggle link: Students Performance in Exams

Submission Contents

student_performance_case_study.ipynb → Jupyter notebook with code

StudentsPerformance.csv → Dataset

Report.pdf → Complete project report

README.md → Instructions to run & reproduce results

Optional plots/ folder → Saved visualization images
