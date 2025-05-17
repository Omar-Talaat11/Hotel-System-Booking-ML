# Hotel-System-Booking-ML
Hotel Booking Status Prediction
a model to predict hotel booking statuses.

🔍 Step 1: Exploratory Data Analysis (EDA)

Cleaned the dataset and handled null values, data types, and formatting.

Performed:

Univariate analysis with histograms and pie charts

Bivariate analysis using scatter plots

Multivariate analysis with pairplots and correlation matrices

Outlier detection using Z-score and box plots

🛠️ Step 2: Data Preprocessing

Checked for nulls, inconsistencies, and whitespace issues

Handled outliers using both IQR and Z-score, chosen based on data skewness

📈 Step 3: Feature Engineering

Applied feature selection

Used PCA (Principal Component Analysis) for dimensionality reduction

🤖 Step 4: Model Training
Trained and evaluated several models:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting Classifier

⚙️ Step 5: Hyperparameter Tuning

Tuned each model using RandomizedSearchCV for faster and effective optimization

📦 Step 6: Model Extraction

Exported the best-performing model using the pickle library for deployment

