# ATF_Challenge_Health_Status
Overview
This project focuses on predicting the 10-year risk of coronary heart disease (CHD) using machine learning techniques. The dataset is sourced from an ongoing cardiovascular study conducted on residents of Framingham, Massachusetts, and is available on Kaggle. It comprises over 4,000 records and includes 15 attributes related to demographic, behavioral, and medical risk factors.

Features
Demographic:
Sex: male or female (Nominal)
Age: Age of the patient (Continuous)
Behavioral:
Current Smoker: Indicates if the patient is a current smoker (Nominal)
Cigarettes Per Day: Average number of cigarettes smoked per day (Continuous)
Medical (history):
BP Meds: Indicates if the patient was on blood pressure medication (Nominal)
Prevalent Stroke: Indicates if the patient had a previous stroke (Nominal)
Prevalent Hypertension (Hyp): Indicates if the patient was hypertensive (Nominal)
Diabetes: Indicates if the patient had diabetes (Nominal)
Medical (current):
Total Cholesterol (Tot Chol): Total cholesterol level (Continuous)
Systolic Blood Pressure (Sys BP): Systolic blood pressure (Continuous)
Diastolic Blood Pressure (Dia BP): Diastolic blood pressure (Continuous)
Body Mass Index (BMI): Body Mass Index (Continuous)
Heart Rate: Heart rate (Continuous)
Glucose: Glucose level (Continuous)
Predict Variable
10-year risk of coronary heart disease CHD (binary: “1” indicates “Yes”, “0” indicates “No”)
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/Eselase-Noble/ATF_Challenge_Health.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook CHD_prediction.ipynb to train the machine learning model and make predictions.
The notebook includes data preprocessing, exploratory data analysis, model training, evaluation, and prediction.
Requirements
Python 3.x
Jupyter Notebook
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn