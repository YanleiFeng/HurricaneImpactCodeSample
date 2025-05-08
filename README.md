# Hurricane Impact Model – Sample Code

This repository contains sample code for building a **Hurricane Impact Model** using machine learning techniques. It demonstrates the full workflow, from data collection and preprocessing to model training, evaluation, and prediction.

## Overview

The notebook includes the following key steps:

1. **Data Collection**
   - Import hurricane-related datasets.
   - Explore and reshape data for modeling.
2. **Data Cleaning**
   - Handle missing values (`NaN`) and outliers.
3. **Feature Engineering**
   - Normalize and encode features using `StandardScaler` and `OneHotEncoder`.
4. **Model Training**
   - Train several models:
     - Linear Regression
     - Ridge & Lasso Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest Regressor
     - Multi-layer Perceptron (MLP) Regressor
5. **Model Evaluation**
   - Evaluate model performance using:
     - R² score
     - Mean Squared Error
     - Explained Variance Score
     - F-beta score (if applicable)
   - Use cross-validation for robust performance estimates.
6. **Hyperparameter Tuning**
   - Grid Search and Randomized Search for optimal model parameters.

## Usage

This sample notebook is intended for use in:

- Risk modeling
- Catastrophe (Cat) risk modeling
- Insurance risk modeling

## Dependencies

To run the code, you will need:

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- numpy
- matplotlib
- scikit-image

Install the required packages using pip:

```bash
pip install scikit-learn pandas numpy matplotlib scikit-image
```

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.