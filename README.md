Diabetes Prediction
Overview
This project uses a K-Nearest Neighbors (KNN) classifier to predict the risk of diabetes based on the Pima Indians Diabetes dataset. The model was optimized for the number of neighbors (K) and achieved a test accuracy of 77.9%, demonstrating effective classification performance.
Features

Data Preprocessing: Standardized features using StandardScaler to improve KNN performance.
Exploratory Data Analysis: Visualized class distributions and feature relationships.
Model Training: Tested KNN with K values from 1 to 19 to find the optimal K (K=11).
Evaluation: Measured model performance with accuracy score.
Visualization: Plotted accuracy vs. K values using Matplotlib and Seaborn.

Technologies Used

Python: Core programming language.
Pandas: For data manipulation and preprocessing.
Scikit-learn: For KNN modeling and preprocessing.
Matplotlib & Seaborn: For data visualization.

Installation

Clone the repository:git clone https://github.com/Aerglo/diabetes-prediction.git


Install dependencies:pip install pandas scikit-learn matplotlib seaborn


Download the dataset (pima-indians-diabetes.csv) and place it in the data/ folder.
Run the Jupyter notebook:jupyter notebook diabetes_prediction.ipynb



Usage

Open the diabetes_prediction.ipynb notebook.
Execute cells to preprocess data, train the model, and visualize results.
Outputs include accuracy plots and model performance metrics.

Results

Achieved 77.9% accuracy with K=11.
Identified plasma glucose and BMI as key predictors of diabetes risk.

Future Improvements

Test other classifiers like SVM or Random Forest for comparison.
Address potential data imbalances with oversampling techniques.
Add confusion matrix visualization for detailed performance analysis.

Contact
For questions or feedback, reach out to me at imnima82@gmail.com or via GitHub.
