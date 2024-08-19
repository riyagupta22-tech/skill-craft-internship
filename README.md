# skill-craft-internship
Hands on session experience on Machine learning internship by skillcraft.
# House Price Prediction

This project implements a linear regression model to predict house prices based on features such as square footage, number of bedrooms, and bathrooms.

## Features

- Data preprocessing including handling missing values
- Linear regression model implementation
- Model evaluation with RMSE and R-squared
- Visualization of predicted vs actual prices
- Prediction on test set and CSV output generation

## Usage

1. Ensure you have the required libraries installed: pandas, numpy, scikit-learn, matplotlib
2. Place your 'train.csv' and 'test.csv' files in the project directory
3. Run the script: `python house_price_prediction.py`
4. Check the output for model performance and the generated 'submission.csv' file

## Data

The model uses the following features:
- GrLivArea: Above grade living area square feet
- BedroomAbvGr: Number of bedrooms above grade
- FullBath: Number of full bathrooms
- HalfBath: Number of half bathrooms
- TotalBsmtSF: Total square feet of basement area
```

Edit the `.gitignore` file to exclude unnecessary files:

```
# Data files
*.csv

# Python cache
__pycache__/
*.py[cod]

# Jupyter Notebook
.ipynb_checkpoints

# Environment
.env
venv/

# OS generated files
.DS_Store
Thumbs.db
```

Now, add and commit your files:

```bash
git add .
git commit -m "Initial commit: House price prediction model"
```
## Code File is mentioned for more clear reference.
