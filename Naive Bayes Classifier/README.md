
# Naive Bayes Classifier for Adult Dataset

This repository contains a Naive Bayes classifier implementation for the Adult Dataset from the UCI Machine Learning Repository. The classifier is designed to predict whether an individual earns more than $50,000 per year based on various features such as work class, education level, hours worked per week, relationship status, and occupation.

## Dataset

The Adult Dataset from the UCI Machine Learning Repository is used in this project. This dataset contains demographic information about individuals, including both numerical and categorical features. The target variable is the income level, categorized as '>50K' or '<=50K'.

## Implementation

The classifier is implemented in Python using the scikit-learn library. Here's a brief overview of the implementation steps:

1. **Data Preprocessing**: Categorical variables are encoded using label encoding. Correlation analysis is performed to understand the relationships between features.

2. **Feature Selection**: Features such as work class, education level, hours worked per week, relationship status, occupation, and income are selected for modeling.

3. **Model Training**: The Naive Bayes classifier is trained on the training dataset using the selected features.

4. **Model Evaluation**: The trained model is evaluated on the test dataset using metrics such as accuracy and F1-score. A confusion matrix is also generated to visualize the performance of the classifier.

5. **Prediction**: The trained model is used to make predictions on new instances provided by the user.

## Usage

To use the Naive Bayes classifier:

1. Clone this repository:

   ```
   git clone <repository_url>
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the classifier by running the ipynb file:


4. Follow the instructions to provide new instances for prediction.

## Results

The trained Naive Bayes classifier achieves an accuracy of approximately 82% and an F1-score of around 0.74 on the test dataset.

## Example Predictions

Here are some example predictions made by the classifier:

1. Instance 1: '>50K'
2. Instance 2: '<=50K'
3. Instance 3: '>50K'

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
