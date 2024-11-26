This project uses machine learning to classify different types of fruits based on their physical characteristics such as mass, width, height, and color score. A Logistic Regression model is trained and evaluated to predict the fruit label, demonstrating a complete machine learning pipeline.

-> Features:

1. Data Preprocessing:
- Selects relevant features for classification.
- Splits the data into training and testing sets for model evaluation.
  
2. Model Training:
- Trains a Logistic Regression model for multiclass classification.

3. Model Evaluation:
Provides detailed evaluation using:
- Accuracy
- F1-Score
- Precision
- Recall
- Confusion Matrix
- Classification Report
  
4. Modular Implementation:
- Encapsulates functionality in reusable functions for better organization and extensibility.

-> Technologies Used:

- Python: Programming language.
- Pandas: For data manipulation and analysis.
- Scikit-learn: For model training, evaluation, and preprocessing.

-> How It Works:

1. Data Loading:
- Reads the fruit dataset from a CSV file.
  
2. Preprocessing:
- Extracts relevant features (mass, width, height, color_score) and target labels (fruit_label).
- Splits the data into training and testing sets.
  
3. Model Training:
- Trains a Logistic Regression model to classify the fruits.
- 
Model Evaluation:
- Evaluates the model on test data and reports metrics like accuracy, F1-score, precision, recall, and confusion matrix.
