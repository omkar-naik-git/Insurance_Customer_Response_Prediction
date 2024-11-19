# Predicting Customer Responses to Insurance Policy Offers

 Overview
This project focuses on building a machine learning model to predict customer responses to insurance policy offers. The goal is to optimize targeted marketing strategies and improve sales efficiency by identifying customers more likely to purchase policies.

 Features
- Exploratory Data Analysis (EDA): Insights into the data using statistical measures and visualizations.
- Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical data.
- Imbalanced Data Handling: Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
- Modeling: Implemented multiple machine learning models including Logistic Regression, Decision Tree, and Random Forest.
- Hyperparameter Tuning: Optimized model performance using GridSearchCV.
- Deployment: Deployed the best-performing model using Streamlit and Anaconda Navigator for interactive predictions.

 Dataset
The dataset contains information on customers and their responses to insurance policy offers with the following columns:
- `Gender`
- `Age`
- `Driving_License`
- `Region_Code`
- `Previously_Insured`
- `Vehicle_Age`
- `Vehicle_Damage`
- `Annual_Premium`
- `Policy_Sales_Channel`
- `Vintage`
- `Response` (Target Variable)

 Key Steps
1. Data Collection: Collected relevant customer data for model building.
2. EDA: Visualized distributions and relationships to uncover patterns in customer behavior.
3. Preprocessing:
   - Encoded categorical variables.
   - Handled missing and inconsistent data.
   - Scaled numerical features.
4. Model Training: Trained Logistic Regression, Decision Tree, and Random Forest models. 
   - Best Model: Random Forest with an accuracy of 83.98%.
5. Deployment: Created a web app using Streamlit to make predictions based on user inputs.

 Files in the Repository
- `Customer_Response_Prediction.ipynb`: Jupyter Notebook with complete code for data preprocessing, EDA, modeling, and evaluation.
- `requirements.txt`: Dependencies required to run the project locally.
- `streamlit_app.py`: Streamlit script for the deployment of the model.
- Sample Data: Includes a sample dataset for testing the application.

 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/omkar-naik-git/insurance-response-prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run streamlit_app.py
   ```

 Results
- Logistic Regression Accuracy: 77.71%
- Decision Tree Accuracy: 77.71%
- Random Forest Accuracy: 83.98%

The Random Forest model was selected as the best-performing model for deployment.

 Future Enhancements
- Add more features to the dataset to improve model performance.
- Explore advanced techniques such as XGBoost or ensemble models.
- Enhance the user interface of the deployed application.

 Contact
For queries or suggestions, feel free to reach out:
- Email: omkarnaik5259@gmail.com
- GitHub: (https://github.com/omkar-naik-git)
