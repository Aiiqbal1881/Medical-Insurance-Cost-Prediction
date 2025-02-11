# Medical Insurance Cost Prediction

## Overview
This project predicts medical insurance costs based on various factors like age, BMI, number of children, smoking habits, and region. It uses **Machine Learning** techniques with **Linear Regression** in Python to analyze and predict insurance expenses.

## Features
- Exploratory Data Analysis (EDA) on medical insurance dataset
- Data preprocessing and feature engineering
- Model training using **Linear Regression**
- Evaluation using train-test split
- Visualization of prediction results

## Technologies Used
- Python
- Pandas & NumPy (for data manipulation)
- Matplotlib & Seaborn (for data visualization)
- Scikit-learn (for model building and evaluation)

## Dataset
The dataset consists of the following features:
- `age`: Age of the individual
- `sex`: Gender (male/female)
- `bmi`: Body Mass Index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status (yes/no)
- `region`: Region of the insured individual
- `charges`: Medical insurance cost (target variable)

## Installation
Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/Medical-Insurance-Cost-Prediction.git
cd Medical-Insurance-Cost-Prediction
pip install -r requirements.txt
```

## Usage
Run the `insurance_cost_prediction.py` script to train and test the model:

```bash
python insurance_cost_prediction.py
```

## Model Training
1. **Data Preprocessing**:
   - Handling missing values (if any)
   - Encoding categorical variables
   - Feature scaling (if necessary)
   
2. **Train-Test Split**:
   - Splitting the dataset into **80% training** and **20% testing**
   - Using `train_test_split` from `sklearn.model_selection`

3. **Training the Model**:
   - Applying **Linear Regression** from `sklearn.linear_model`
   - Evaluating model performance using Mean Squared Error (MSE) and R-squared score

## Results & Evaluation
- Model accuracy and loss metrics are displayed after training
- Predictions vs actual costs are visualized using scatter plots

## Contributing
Feel free to contribute by raising issues or submitting pull requests.

## License
This project is licensed under the MIT License.


