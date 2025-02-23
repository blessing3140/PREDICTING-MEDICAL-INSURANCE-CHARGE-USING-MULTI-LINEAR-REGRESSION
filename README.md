# PREDICTING MEDICAL INSURANCE CHARGE USING MULTIPLE LINEAR REGRESSION MODEL
## *📌 Overview*  
This project analyzes a medical insurance dataset and builds a predictive model to estimate *insurance charges* based on various factors like age, BMI, smoking status, and region.  

## *📂 Dataset*  
- *Source:* [Kaggle - Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- *Description:* The dataset contains *1,338* records with *7 columns*, including
  personal and health-related details.  
- *Columns:*  
  - age: Age of the individual  
  - sex: Gender (male or female)  
  - bmi: Body Mass Index (BMI)  
  - children: Number of dependent children  
  - smoker: Whether the person is a smoker (yes or no)  
  - region: Residential region (northeast, northwest, southeast, southwest)  
  - charges: Medical insurance cost (target variable)  

## *📊 Objective*  
- Perform *Exploratory Data Analysis (EDA)* to understand correlations.  
- Build *Machine Learning models* (Linear Regression, Ridge Regression, etc.) to predict insurance costs.  
- Deploy the model using *Streamlit / Flask*.

- ### *Key Insights and Recommendations Based on the Dataset*  

#### *1. Factors Affecting Insurance Charges*
- *Smoking status*: Smokers have significantly higher insurance costs than non-smokers. If possible, promoting smoking cessation programs can help lower premiums.  
- *BMI (Body Mass Index)*: Higher BMI is associated with higher charges. Encouraging a healthier lifestyle (diet and exercise) may reduce long-term costs.  
- *Age*: Older individuals tend to have higher insurance costs. Providing affordable options for elderly customers can be beneficial.  
- *Number of children*: Having more children slightly increases insurance costs. Family plans should be structured accordingly.
#### 2. Regional Pricing Strategies
- The dataset includes four regions: southwest, southeast, northwest, and northeast. If one region has higher average charges, insurers can investigate why and adjust pricing or offer discounts based on risk levels.  

#### 3. Predictive Modeling for Pricing
- A linear regression model can predict insurance charges based on input features like age, BMI, and smoking status.

 ##*📦 Project Structure*  

├── data/                  # Dataset files  
├── notebooks/             # Jupyter/Colab notebooks for EDA & modeling  
├── models/                # Trained models (e.g., model.pkl)  
├── app/                   # Streamlit/Flask app for deployment  
├── requirements.txt       # Dependencies  
├── README.md              # Project documentation  
└── main.py                # Main script for training  


## *🛠 Installation & Usage*  
### *⿡ Clone the Repository*  
bash
git clone https://github.com/blessing3140/predicting-medical-insurance-charge-using-multile-linear-regression-model.git
cd your-repo-name
### *⿢ Install Dependencies*  
bash
pip install -r requirements.txt


### *⿣ Run colab Notebook for Analysis*  
colab notebook


### *⿤ Train the Model*  
bash
colab main.py


### *⿥ Run Streamlit App (If Deployed)*  
bash
streamlit run app/app.py

## *📈 Models Used*  
✔ *Linear Regression*  
✔ *Ridge Regression*  



  

## *📜 License*  
This project is licensed under the *MIT License*.  






