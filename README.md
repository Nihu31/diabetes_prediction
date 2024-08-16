**Diabetes Mellitus Prediction**
This project is focused on predicting the likelihood of diabetes mellitus based on various patient attributes using machine learning techniques. The dataset used in this project is a diabetes prediction dataset that includes features such as gender, age, hypertension status, heart disease status, smoking history, BMI, HbA1c level, and blood glucose level.

**Project Structure**
**Data Loading and Exploration**:

The dataset is loaded using Pandas, and the first few rows of the data are displayed to understand the structure and contents of the dataset.
**Data Preprocessing**:

**Handling Missing Values**: Missing values in the numeric columns are handled using the mean imputation strategy.
**Feature Selection**: Numerical and categorical features are separated for appropriate preprocessing.
**Standardization**: Features are standardized to ensure uniform scaling across different attributes.
**Label Encoding**: Categorical variables are converted to numerical form using label encoding.
**Modeling**:

**Model Selection**: Multiple models are used for training, including Stochastic Gradient Descent (SGD) Classifier and Multi-Layer Perceptron (MLP) Classifier.
**Cross-Validation**: The performance of the models is evaluated using cross-validation.
**Hyperparameter Tuning**: GridSearchCV is used to find the optimal hyperparameters for the models.
**Evaluation**:

The models are evaluated based on their accuracy scores on the test data.
**Dependencies**
To run the code, you'll need the following Python packages:

pandas
numpy
scikit-learn
You can install the required packages using pip:

bash
Copy code
pip install pandas numpy scikit-learn
**Dataset**
The dataset used for this project contains the following columns:(this dataset is from data.world)

gender: Gender of the patient
age: Age of the patient
hypertension: Whether the patient has hypertension (0 or 1)
heart_disease: Whether the patient has heart disease (0 or 1)
smoking_history: Smoking history of the patient (categorical)
bmi: Body Mass Index of the patient
HbA1c_level: Hemoglobin A1c level of the patient
blood_glucose_level: Blood glucose level of the patient
diabetes: Target variable indicating whether the patient has diabetes (0 or 1)
**How to Run**
Clone the repository to your local machine.
Install the required dependencies.
Run the Jupyter Notebook to train and evaluate the models.
**Results**
The project demonstrates the use of machine learning models for predicting the likelihood of diabetes based on patient data. The models are evaluated on their accuracy, and the best model is selected based on cross-validation results and hyperparameter tuning.

**License**
This project is licensed under the MIT License
