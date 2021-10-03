Patients Cardiovascular Disease prediction :


- Proposal: Used data from Kaggle’s “Cardiovascular Disease” dataset to model if the patient will be having a Cardiovascular Disease or not.
	
	
- Background: 
		
	Cardiovascular disease is defined as any disease that affects the heart or the blood vessels. Cardiovascular disease is considered one of the leading causes of death worldwide. Duo to the importance of the cardiovascular system in every human body and the existence of many machine learning models that helped in the medical field, The research aim to help doctors to early predict the probability of a patient having a cardiovascular disease to prevent the patients from having angina, heart attack or heart failure. Also, it will aim to find the main factors that led the patients to have cardiovascular disease. 	
	
- Data: 
	- Kaggle Dataset "Cardiovascular Disease dataset"

	- URL: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

	- The dataset consist of : 
		- 70,000 patients' records 
		- The "cardio" variable is the target variable that indicates the presence of cardiovascular disease. 
		- 12 medical history features are: 
			- Age in (days)
			- Height in (cm)
			- Weight in (kg)
			- Gender 1: women, 2: men
			- Systolic blood pressure 
			- Diastolic blood pressure 
			- Cholesterol  1: normal, 2: above normal, 3: well above normal 
			- Glucose  1: normal, 2: above normal, 3: well above normal 
			- Smoking
			- Alcohol intake
			- Physical activity 
		
		- Additional Features: 
			- Body Mass Index (BMI) : 1: Underweight, 2: Normal weight, 3: overweight, 4: Obesity 
	
- Methodology & Approach: 
	- I Hypotheesize that patients who are young and their weight is normal will have less probability of having Cardiovascular disease. The patients that are most likely to have Cardiovascular disease are patients who are old, smoke, drink alcohol, and have a well above normal Cholesterol rate.

- Tool: 
	- Python (Pandas, NumPy, Scikit-Learn, Statsmodels, requests, Matplotlib, Seaborn, Google Maps API)
	- Jupyter Notebook

- Models: 
	- Logistic Regression 
	- SVM 
	- Decision Tree 
	- Other models could be used to get the best results (Accurecy, F1, Precesion)
	
	- Minimum Viable Product:  
- Logistic Regression predictive model that predicts the probability of a patient having a Cardiovascular disease to help Doctors in making decisions for their patients and warn their patients in case the model predicted them as haveing a Cardiovascular diseases.   
			