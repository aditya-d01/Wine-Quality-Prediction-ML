# Wine-Quality-Prediction-ML
🍷 Wine Quality Prediction using Machine Learning
This project focuses on predicting the quality of wine based on its physicochemical properties using machine learning techniques. The goal is to analyze the dataset, identify important features, train an effective classification model, and build a predictive system that classifies wine as good or bad quality.

The project includes data exploration, visualization, preprocessing, model training, evaluation, and real-time prediction.

📌 Project Objectives
Analyze wine quality data using statistical and visualization techniques
Understand the relationship between chemical properties and wine quality
Preprocess and prepare data for machine learning
Train and evaluate a classification model
Develop a system to predict wine quality for new input values

📂 Dataset
The dataset used in this project is the Wine Quality (Red Wine) dataset, containing 1599 samples and 12 attributes.

Features:
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Target:
Quality score (0–10), converted into:
1 → Good quality (≥ 7)
0 → Bad quality (< 7)

🔍 Exploratory Data Analysis (EDA)
To understand the dataset, several analysis and visualization techniques were applied:
Statistical summary using describe()
Distribution of wine quality
Bar plots showing feature vs quality relationships
Correlation heatmap to analyze dependencies between variables
These steps helped identify important features affecting wine quality.

⚙️ Data Preprocessing
The following preprocessing steps were performed:
Checked for missing values (no missing data found)
Separated features and target labels
Converted quality scores into binary labels
Prepared data for training and testing
Feature matrix: X
Target label: Y

🧠 Model Training
A Random Forest Classifier was used for training the model due to its robustness and ability to handle complex feature interactions.

Steps:
Split data into training and testing sets (80% / 20%)
Trained the model using training data
Optimized default hyperparameters
Fitted the model for classification

Algorithm used:
Random Forest Classifier (Scikit-learn)

📊 Model Evaluation
The trained model was evaluated using accuracy score.
Performance:
Test Accuracy: 92.5%

Evaluation steps:
Generated predictions on test data
Compared predicted labels with actual labels
Calculated accuracy score
This shows that the model performs well in predicting wine quality.

🔮 Predictive System
A predictive system was implemented to classify new wine samples.

Workflow:
Accept physicochemical input values
Convert input to NumPy array
Reshape for prediction
Pass input to trained model
Display prediction result

Output:
Good Quality Wine
Bad Quality Wine
This allows real-time testing of wine samples.

🛠 Tools & Libraries
The following tools and libraries were used:
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab
