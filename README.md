# Insurance-Claim-Prediction-Machine-Learning-Webapp

This project aims to predict insurance claim amounts based on various features like age, gender, BMI, smoking status, and more. Accurate prediction helps insurance companies reduce financial losses and improve efficiency in processing claims.

## Dataset Description
The dataset contains the following features:

| Feature    | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `age`      | Age of the policyholder.                                                    |
| `sex`      | Gender of the policyholder (female=0, male=1).                              |
| `BMI`      | Body Mass Index, a ratio of weight to height (kg/m²), ideally 18.5 to 25.   |
| `steps`    | Average walking steps per day of the policyholder.                          |
| `children` | Number of children or dependents of the policyholder.                       |
| `smoker`   | Smoking state of the policyholder (non-smoker=0; smoker=1).                 |
| `region`   | Residential area of the policyholder in the US (northeast=0, northwest=1, southeast=2, southwest=3). |
| `charges`  | Individual medical costs billed by health insurance. (Target variable)      |

## Project Features

- Exploratory Data Analysis (EDA)
- Feature engineering and preprocessing
- Machine Learning Model Training and Evaluation
- Prediction of insurance claims using the trained model
- Web application for user interaction (using `Flask` or `Streamlit`)

## Prerequisites

Before running this project, ensure you have the following installed:

- Python 3.7.0 or higher
- Required libraries listed in the `requirements.txt` file

## Installation Steps

1. **Clone the repository**:
   git clone https://github.com/Prethika88/Insurance-Claim-Prediction-Machine-Learning-Webapp.git
   
   cd Insurance-Claim-Prediction-Machine-Learning-Webapp
   
2. **Install dependencies**:
   
   python -m pip install --user -r requirements.txt
   
3.**Run the application**: 

  python app.py
  
4.**Access the application**:

  Open your browser and go to http://localhost:5000.

## Technologies Used
1.Programming Language: Python 3.7+

2.Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Flask/Streamlit

3.IDE: Jupyter Notebook, VS Code

## How it Works
Data Preprocessing:
1.Handle missing values, if any
2.Encode categorical features like sex, smoker, and region
3.Normalize numerical features like age, BMI, and steps

Model Training
1.Train machine learning models such as Linear Regression, Random Forest, or Gradient Boosting on the dataset.
2.Evaluate model performance using metrics like Mean Squared Error (MSE) and R².

Web App:
1.Provide user input forms to predict insurance charges based on the given features.
2.Display predictions and insights.


