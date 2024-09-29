# Medical Expenditure Prediction-ML-Python-Gradio

### Project Description
This repository hosts the code for a **Medical Expenditure Prediction System**, designed to estimate the total annual medical costs for individuals based on various demographic and health-related factors. The project involves comprehensive Exploratory Data Analysis (EDA), feature engineering, scaling, encoding, model training using machine learning algorithms (Linear Regression and Random Forest), and deployment via Gradio for user interaction. The system predicts medical expenditure based on inputs such as age, sex, BMI, number of children, smoking status, and region.

### Technologies Used

#### Languages
- Python

#### Tools
- Jupyter Notebook

#### Libraries
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Scikit-learn**: Machine learning tools (Linear Regression, Random Forest) and preprocessing (scaling, encoding)
- **Gradio**: Easy-to-use UI for model deployment

#### Dataset Source
[Dataset](https://www.kaggle.com/datasets/harshsingh2209/medical-insurance-payout)

### Features and Process
1. **EDA (Exploratory Data Analysis)**: 
   - Analyzing the data, understanding patterns, and finding correlations between features like age, BMI, smoker status, and region with medical expenses.
  
2. **Feature Engineering**: 
   - Created new features such as interaction terms between BMI and smoking status, age and BMI, age and smoker.
  
3. **Preprocessing**: 
   - **Scaling**: Applied standard scaling on features like `age` to improve model performance.
   - **Encoding**: 
     - Label encoding for categorical variables such as `sex` and `smoker`.
     - One-hot encoding for `region`.

4. **Model Training**: 
   - Trained and evaluated two models: 
     - **Linear Regression**
     - **Random Forest Regressor**
   
5. **Gradio Deployment**: 
   - Built a user-friendly interface using Gradio where users can input features such as age, sex, BMI, number of children, smoking status, and region to get a prediction of their medical expenditure.

### Project Screenshots

![image](https://github.com/user-attachments/assets/e32287d5-ce31-4d4c-81d3-0a28b32619ed)

![image](https://github.com/user-attachments/assets/7d97e42c-af87-4832-bc57-647b0ab02599)

![image](https://github.com/user-attachments/assets/a8acb933-d27d-4b9c-967c-55793c38784e)

![image](https://github.com/user-attachments/assets/9a4175c6-6693-49ca-a2e6-36f1d15ad63b)

![image](https://github.com/user-attachments/assets/23771838-b275-452a-8220-d6fe4277ed0b)



