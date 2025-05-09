# HR Analytics - Employee Attrition Prediction

This project is focused on analyzing and predicting employee attrition using a real-world HR dataset. It combines data cleaning, visualization, and machine learning to identify patterns in employee behavior and forecast attrition outcomes.

## 📊 Dataset

- Source: Kaggle HR Analytics dataset
- Format: CSV
- Target Variable: Attrition (Yes/No → Encoded to 1/0)
- Size: Includes features such as Age, Job Role, Monthly Income, OverTime, etc.

## 🔧 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn 📊
- Scikit-learn 🤖
- Jupyter Notebook

## 📈 Project Workflow

1. *Data Import & Cleaning*
   - Loaded CSV using pandas
   - Checked for missing values
   - Label Encoded categorical columns

2. *Exploratory Data Analysis*
   - Visualized attrition count
   - Analyzed attrition by Job Role, Overtime, and other key variables

3. *Feature Engineering*
   - Dropped unnecessary features like EmployeeNumber, Over18, StandardHours
   - Encoded all object type columns

4. *Model Building*
   - Used *Random Forest Classifier* to predict employee attrition
   - Split dataset into 80% train / 20% test

5. *Evaluation*
   - Accuracy score
   - Confusion matrix
   - Classification report

6. *Export*
   - Predictions saved to Excel for reporting

## 📊 Example Visualization

- Attrition Count Plot
- Job Role vs Attrition
- Heatmaps & Histograms

## 📁 How to Run

bash
# Clone this repository
git clone https://github.com/your-username/hr-analytics-project.git
cd hr-analytics-project

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook HR_Analytics.ipynb


## 📌 Results

- Trained model achieved good accuracy in predicting attrition
- Business can now identify which employees are at risk of leaving

## 💡 Future Improvements

- Hyperparameter tuning
- Use of other models like XGBoost, Logistic Regression
- Dashboard with Power BI or Streamlit

---
