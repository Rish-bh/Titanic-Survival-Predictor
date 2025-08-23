🛳️ Titanic Survival Prediction

This project uses machine learning to predict passenger survival on the Titanic based on the official passenger dataset. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and the training and evaluation of several classification models to find the best predictor.

📂 Project Structure

A clear project structure is essential for reproducibility. This repository is organized as follows:
```
Titanic-Survival-Predictor/
│
├── data/                     # (Optional) Place dataset files here
│   └── Titanic.csv
│
├── notebooks/
│   └── Titanic_Survival_Predictor.ipynb   # Your main notebook
├── requirements.txt          # List of Python dependencies
├── README.md                 # Project description, setup, and usage
└── .gitignore                # Ignore unnecessary files
```

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Rish-bh/Titanic-Survival-Predictor.git
cd Titanic-Survival-Predictor
```

### 2. Create and activate a virtual environment (Recommended):
```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install the required libraries:
This command reads the `requirements.txt` file and installs all the necessary packages.
```
pip install -r requirements.txt
```
### 4. Place the dataset:
Ensure you have the `Titanic-Dataset.csv` file inside the data/ directory.

### 🚀 How to Run the Project
Once your environment is set up, you can run the analysis.

1. Start the Jupyter Notebook server:
From your terminal in the project's root directory, execute:

jupyter notebook

2. Open the notebook:
Your default web browser will open. Navigate to the notebooks/ folder and click on Titanic_Survival_Predictor.ipynb.

3. Run the analysis:
You can run all the cells in the notebook from top to bottom (Cell > Run All) to see the complete workflow, from data loading and visualization to model training and final predictions.

📊 Results Summary
The analysis confirmed historical accounts and provided clear insights:

* Gender: Being female was the single most important factor for survival.

* Passenger Class: First-class passengers had a significantly higher chance of survival compared to those in second and third class.

* Model Performance: The Gradient Boosting Classifier achieved the highest accuracy among the models tested (Logistic Regression, Random Forest, SVM), making it the most reliable model for this prediction task.
