🛳️ Titanic Survival PredictionThis project uses machine learning to predict passenger survival on the Titanic based on the official passenger dataset. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and the training of several classification models to achieve the best possible prediction accuracy.📂 Project Structuretitanic_survival_predictor/
├── data/
│   └── Titanic-Dataset.csv       # The dataset used for training and testing
├── notebooks/
│   └── Titanic_Survival_Predictor.ipynb  # Jupyter Notebook with all analysis and modeling
├── requirements.txt              # A list of all Python dependencies
└── README.md                     # This documentation file

⚙️ Setup and Installation:To run this project, you'll need to set up a Python environment and install the required libraries.1. Clone the repository (or create the structure manually):git clone <>
cd titanic_survival_predictor
2. Create a virtual environment (recommended):python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install the required libraries:Make sure you have the requirements.txt file in your main project directory.pip install -r requirements.txt
4. Place the dataset:Download the Titanic-Dataset.csv and place it inside the data/ directory.
🚀 How to Run the ProjectOnce the setup is complete, you can run the analysis.Start Jupyter Notebook:From your terminal in the project's root directory, run:jupyter notebook
Open the notebook:Your browser will open a new tab. Navigate to the notebooks/ folder and click on Titanic_Survival_Predictor.ipynb.
Run the cells:You can run all the cells in the notebook sequentially to see the full analysis, from data loading to model prediction.

📊 Results SummaryThe analysis revealed several key factors influencing survival:Gender: Females had a significantly higher survival rate.Passenger Class: First-class passengers had the best survival chances.Model Performance: The Gradient Boosting Classifier achieved the highest accuracy among the tested models, including Logistic Regression, Random Forest, and SVM.
