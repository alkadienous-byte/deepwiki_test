# Kendall and Pearson Correlation Calculator for Adult Dataset

This repository contains a Python script for calculating Kendall and Pearson correlations for selected features in the Adult Dataset from the UCI Machine Learning Repository. The script provides custom implementations for calculating these correlations and compares the results with built-in functions.

## Dataset

The Adult Dataset from the UCI Machine Learning Repository is used in this project. This dataset contains demographic information about individuals, including features such as age, education level, capital gain, capital loss, hours per week, and income.

## Implementation

The Python script reads the Adult Dataset, selects specific features for analysis, and preprocesses the data by handling missing values and encoding categorical variables. It then calculates Kendall and Pearson correlations using custom implementations of these methods. Additionally, the script compares the results with built-in functions (`kendalltau` and `pearsonr`) from the `scipy.stats` module.

## Usage

To use the correlation calculator:

1. Clone this repository:

   ```
   git clone <repository_url>
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the script from the ipynb file:

4. View the calculated correlations between selected features.

## Results

The script generates Kendall and Pearson correlation coefficients between selected features in the Adult Dataset. It provides both custom and built-in correlation values for comparison.

## Example Output

Below is a sample output showing the calculated correlations between selected features:

- Correlations between age and fnlwgt:
  - Custom Kendall correlation: -0.036
  - Custom Pearson correlation: -0.079

- Correlations between age and educational-num:
  - Custom Kendall correlation: -0.069
  - Custom Pearson correlation: -0.051

... (output truncated)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
