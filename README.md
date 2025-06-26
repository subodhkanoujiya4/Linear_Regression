# Linear_Regression

# 🏠 Housing Price Prediction using Linear Regression
This project implements Simple and Multiple Linear Regression models using Python to predict housing prices based on various features. It uses the Housing.csv dataset and evaluates models using metrics like MAE, MSE, and R² Score.

# 📁 Dataset
The dataset Housing.csv contains 545 entries with 13 columns:
Target variable: price (house price)
Numerical features: area, bedrooms, bathrooms, stories, parking
Categorical features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

# 🛠️ Tools & Libraries
Python 
Pandas
NumPy
Scikit-learn
Matplotlib

# 🚀 Tasks Performed
✅ Data Preprocessing
Loaded dataset using Pandas

Converted categorical variables to numeric using one-hot encoding (pd.get_dummies)

# ✅ Simple Linear Regression
Used area as the single feature
Trained a Linear Regression model
Evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
Plotted regression line 

# ✅ Multiple Linear Regression
Used all numerical + encoded categorical features
Trained a model
Evaluated using the same metrics
Printed model coefficients (interpretability)

# 📊 Sample Output
Simple Linear Regression (area → price)
MAE: ~9.7 Lakhs
R²: ~0.65
Slope: ~Price per square foot
Multiple Linear Regression
R² Score improved using all features

# 📌 How to Run

# Step 1: Clone the repository
git clone [https://github.com/subodhkanoujiya4/Linear_Regression.git]
cd Linear_Regression

# Step 2: Install required libraries (if needed)
pip install pandas numpy matplotlib scikit-learn

# Step 3: Run the Python script or notebook
python housing_regression.py
# OR open and run housing_regression.ipynb
Make sure Housing.csv is present in the same directory.

# 📁 Project Structure

# 📦 housing-linear-regression
 ┣ 📄 Housing.csv
 ┣ 📄 housing_regression.py
 ┣ 📄 housing_regression.ipynb
 ┗ 📄 README.md
 
# 📌 Author
Subodh Kanoujiya
Feel free to connect on LinkedIn or reach out for collaborations!

