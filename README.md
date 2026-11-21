# Multiple Linear Regression: Concepts and Walkthrough

A learning notebook that builds a multiple linear regression model step by step in Python, explaining the reasoning behind every preprocessing and modelling decision.

## What the Notebook Covers

- Starting from a simple linear regression and extending it to many predictors
- Checking for a linear relationship with scatter plots and a correlation heatmap
- Train/test split before any scaling
- Converting yes/no columns to 1/0 and creating dummy variables (n-1 columns for n categories)
- Feature scaling: Min-Max normalisation vs standardisation
- Two ways to build the model: add variables one at a time, or start with all and drop weak ones
- Using p-values, R-squared and VIF to decide which features to keep

## Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, statsmodels, Jupyter Notebook

## Repository Contents

- `Multiple Linear Regression.ipynb`: the full notebook with notes in markdown cells

## How to Run

1. Clone the repository
2. Install the libraries: `pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter`
3. Update the dataset path in the notebook to your local copy
4. Run the cells in order with `jupyter notebook`

## Related

The applied version of this work is in the House Price Prediction project in this profile.

## Author

Ritesh Pardeshi, Data Scientist
