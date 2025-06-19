# SCT_ML_01
📈 Crop Production Prediction using Linear Regression
This project implements a Linear Regression model to predict agricultural crop production based on historical features such as area, season, crop type, and year. The model uses real-world dataset preprocessing, feature encoding, scaling, and regression techniques to estimate the target variable: production quantity.

🧰 Features
✅ Handles missing or invalid values (e.g., non-numeric entries in Production)

✅ Encodes categorical columns using Label Encoding

✅ Scales features using StandardScaler

✅ Splits data into training and test sets for evaluation

✅ Implements Linear Regression from scikit-learn

✅ Evaluates model using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared Score (R²)

📂 Dataset Columns Used
Feature-----Description
Area-----Total sown area for the crop
Season-----Season in which crop is grown
Crop-----Name of the crop
Crop_Year-----Year of cultivation
Production-----Target variable (crop yield)

🛠 Tools & Libraries Used
Python 3.x

pandas

numpy

scikit-learn (LinearRegression, metrics, preprocessing)
