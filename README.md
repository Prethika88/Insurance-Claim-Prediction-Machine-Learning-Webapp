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

**Clone the repository**:
   git clone https://github.com/Prethika88/Insurance-Claim-Prediction-Machine-Learning-Webapp.git
   
   cd Insurance-Claim-Prediction-Machine-Learning-Webapp
   
**Install dependencies**:
   
   python -m pip install --user -r requirements.txt
   
**Run the application**: 

  python app.py
  
**Access the application**:

  Open your browser and go to http://localhost:5000.

## Technologies Used
1.Programming Language: Python

2.Web Framework: Flask 

3.Frontend: HTML, CSS

4.ML Libraries: Scikit-learn, Pandas, NumPy, Matplotlib

5.Data Storage: model.pkl, insurance3r2 

6.Dependency Management: requirements.txt 

7.Version Control: Git 

## How it Works
1.Data Preprocessing:

-Handle missing values, if any.

-Encode categorical features like sex, smoker, and region.

-Normalize numerical features like age, BMI, and steps.

2.Model Training:

-Train machine learning models such as Linear Regression, Random Forest, or Gradient Boosting on the dataset.

-Evaluate model performance using metrics like Mean Squared Error (MSE) and R².

3.Web App:

-Provide user input forms to predict insurance charges based on the given features.

-Display predictions and insights.


