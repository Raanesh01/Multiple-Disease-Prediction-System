# Multiple Disease Prediction System

## Project Description
The Multiple Disease Prediction System is a machine learning-based application that predicts the likelihood of three diseases:
- Heart Disease
- Parkinson's Disease
- Diabetes

The application allows users to input relevant medical information and provides predictions in an easy-to-use interface, deployed using Streamlit.

## Features
- Predicts the likelihood of Heart Disease, Parkinson's Disease, and Diabetes.
- Simple, interactive web interface using Streamlit.
- User-friendly input forms for entering medical data.
- Real-time prediction based on trained machine learning models.

## Technology Stack
- **Programming Language**: Python
- **Machine Learning Libraries**: scikit-learn, pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Deployment**: Streamlit

## Project Workflow
1. **Data Preprocessing**:
   - Cleaned and preprocessed datasets for Heart disease, Parkinson's disease, and Diabetes disease predictions.
   - Normalized features and standardized the data.
2. **Model Training**:
   - Trained individual models for each disease using algorithms like Logistic Regression and SVM.
3. **Evaluation**:
   - Evaluated models on accuracy score.
4. **Deployment**:
   - Deployed the system using Streamlit for real-time user interaction.

## Usage
1. Open the application by running `streamlit run app.py`.
2. Select the disease you want to predict (Heart, Parkinson's, or Diabetes).
3. Enter the required medical details in the input fields.
4. Click on the respective "Test Result" button to view the results.

## Installation Instructions
Follow these steps to set up the project locally:

1. Clone the repository:
git clone https://github.com/Raanesh01/multiple-disease-prediction.git

2. Navigate to the project directory:
cd Multiple-Disease-Prediction-System

3. Install the required dependencies

4. Run the Streamlit app:
streamlit run app.py
