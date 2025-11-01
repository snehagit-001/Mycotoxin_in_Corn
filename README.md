# Mycotoxin-in-Corn
Overview
This project aims to predict the concentration of vomitoxin (measured in parts per billion, ppb) in agricultural products using various machine learning models. The dataset contains various features related to the agricultural samples, and the target variable is the vomitoxin concentration. The project involves data preprocessing, feature selection, model training, and evaluation using different algorithms.

Repository Structure
The repository is structured as follows:

vomitoxin-prediction/

├── data/                    # Directory containing the dataset

│   └── TASK-ML-INTERN.csv   # Dataset file

├── notebooks/                # Directory containing Jupyter notebooks

│   └── DON_task.ipynb       # Main notebook for data preprocessing, model training, and evaluation

├── README.md                # This file

└── requirements.txt         # File listing the required Python libraries


Installation
To run the code in this repository, you need to install the required dependencies. Follow the steps below:

Clone the repository:

bash
Copy
git clone https://github.com/snehagit-001/Mycotoxin-in-corn.git
cd Mycotoxin-in-corn
Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the dependencies:

pip install -r requirements.txt
The requirements.txt file contains the following dependencies:
pandas
numpy
matplotlib
seaborn
tensorflow
scikit-learn
xgboost


Running the Code
Launch Jupyter Notebook:
jupyter notebook

Open the notebook:
Navigate to the notebooks/ directory.
Open DON_task.ipynb.

Run the notebook cells:
Execute the cells in the notebook sequentially to preprocess the data, train the models, and evaluate their performance.

Dataset
The dataset used in this project is stored in a CSV file named TASK-ML-INTERN.csv. It contains the following columns:
hsi_id: A unique identifier for each sample (dropped during preprocessing).
Other features: Various numeric features related to the agricultural samples.
vomitoxin_ppb: The target variable representing the vomitoxin concentration in parts per billion.

Models
The following machine learning models were trained and evaluated:
XGBoost Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
Neural Network
Evaluation Metrics

The models were evaluated using the following metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared (R²)
