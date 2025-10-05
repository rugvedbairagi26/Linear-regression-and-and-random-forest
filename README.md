# Linear-regression-and-and-random-forest
House Value Regression: Linear Regression vs Random Forest
Overview
This project demonstrates and compares the effectiveness of Linear Regression and Random Forest Regression in predicting California house values using the scikit-learn California Housing dataset. The workflow includes data preprocessing, normalization, model training, evaluation, and results visualization. The project emphasizes how Random Forest, a powerful tree-based ensemble, outperforms traditional linear models on complex, non-linear tabular data.

Dataset
Source: California Housing Dataset (via scikit-learn)

Features: Median income, house age, average rooms/bedrooms, population, occupancy, latitude, longitude

Target: Median house value (MedHouseVal)

Size: ~20,000 samples, 8 feature columns

Workflow
1. Data Preparation
Load dataset and review structure using pandas

Separate features (X) and target (y)

Split into train/test sets (80:20 ratio using a random seed for reproducibility)

2. Feature Scaling
Normalize and standardize features using StandardScaler for robust comparison

3. Linear Regression Model
Train a linear regression model on the training split

Predict house values for the test set

Evaluate predictions using:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R² Score

Visualize results with actual vs predicted scatter plot (s=10 for better readability)

Example Results
text
MSE: 0.5559
MAE: 0.5332
R2 Score: 0.576
4. Random Forest Regression Model
Train a random forest regressor (n_estimators=100) on the same training data

Predict house values for the test set

Evaluate using same metrics (MSE, MAE, R² Score)

Visualize results with scatter plot

Example Results
text
Random Forest MSE: 0.2554
Random Forest MAE: 0.3275
Random Forest R2 Score: 0.8051
Results & Conclusion
Random Forest regression outperforms Linear Regression on this dataset, as shown by lower MSE and MAE values and a higher R² score. This demonstrates Random Forest’s superior ability to capture complex, non-linear feature interactions and provide more accurate predictions for tabular regression tasks.

Project Structure
text
/notebooks/          # Jupyter notebooks or Python scripts
/data/               # Data folder (auto-downloaded via scikit-learn)
/plots/              # Output visualizations (scatter plots)


Linkdein-https://www.linkedin.com/in/rugved-bairagi-7882b5285/
