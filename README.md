NSAP Eligibility Prediction using Multi-Class Classification

📌 Project Overview :

- The National Social Assistance Programme (NSAP) provides financial assistance to elderly, widows, and disabled individuals from below-poverty-line households. Manual eligibility verification is time-consuming and prone to errors.cThis project uses Machine Learning (Multi-Class Classification) to predict the most appropriate NSAP scheme for applicants based on demographic and socio-economic features.

The solution: 
- Automates scheme prediction ensures faster, transparent processing is deployed on IBM Watson Machine Learning (WML) for scalability.

📂 Dataset Source: https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html

- Features: finyear, lgdstatecode, lgddistrictcode, schemecode (target), totalbeneficiaries, totalmale, totalfemale, totalsc, totalst, totalgen, totalobc, totalaadhaar, totalmpbilenumber
- Target: schemecode → NSAP Scheme Code (Multi-Class)

⚙️ Technology Stack :
- Programming Language: Python 3.8+
- Libraries: pandas, numpy, scikit-learn, xgboost, joblib
- Cloud Services: IBM Cloud Lite,
                  IBM Watsonx.ai Studio
                  IBM Watson Machine Learning
                  IBM AutoAI

📊 Methodology :

Step 1: Data Cleaning & Preprocessing.

Step 2: Feature Engineering.

Step 3: Model Training (Multi-Class Classification).

Step 4: Model Evaluation (Accuracy, F1-score, Confusion Matrix).

Step 5: Deployment on IBM Watson Machine Learning.
