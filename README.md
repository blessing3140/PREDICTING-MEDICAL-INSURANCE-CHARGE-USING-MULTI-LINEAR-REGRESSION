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
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
### *⿢ Install Dependencies*  
bash
pip install -r requirements.txt


### *⿣ Run colab Notebook for Analysis*  
bash
colab notebook


### *⿤ Train the Model*  
bash
python main.py


### *⿥ Run Streamlit App (If Deployed)*  
bash
streamlit run app/app.py

## *📈 Models Used*  
✔ *Linear Regression*  
✔ *Ridge Regression*  
  

## *📜 License*  
This project is licensed under the *MIT License*.  






