# Human-Development-Index-Regression-Analysis
![human-development-index-hdi asp-final-57aa610efde34482bf9a48594216674a](https://github.com/user-attachments/assets/c9d60bd7-3fac-4804-a53e-082b49e78f8d)

A project for analyzing other underlying factors that would affect Human Development Index value in the province of West Java using regression analysis models.

# Workflow
## Data Collection
Data was compiled from multiple datasets available and obtained from annual open publication data issued by the Bureau of Statistics of Indonesia.

## Data Preprocessing
1. Describe the dataset using plots, including scatter plot and box plot.
2. Check correlations between the predictor variables with the response variable.

## Train Model
1. Create a base Linear Regression model to check assumptions (Normality, Homoscedasticity, Autocorrelation, Multicollinearity).
2. Assess and address the failed assumptions using different regression models that fit the purpose.
3. Check whether the new regression model successfully passed the assumption test that failed when tested with the normal linear regression.
4. If there are multiple failed assumptions, compare each regression model used for addressing those assumptions with each other.

## Model
The linear regression model created from the dataset suggested that there are two failed assumptions, the autocorrelation and multicollinearity assumption. To address both of them, a Cochrane-Orcutt Regression model and Ridge Regression model is created.
