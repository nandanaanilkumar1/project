# 🏠 House Price Prediction using Linear Regression
### A Statistical Approach to Real Estate Valuation

## 📌 Project Overview
This project focuses on predicting house prices in Boston using **Multivariate Linear Regression**. By analyzing various socio-economic and environmental factors, we aim to understand the underlying mathematical relationships that drive property values.

## 🎓 Mathematical Framework
The core of this project is the **Ordinary Least Squares (OLS)** method. We model the relationship between the target (Median Value) and features as:

$$y = \beta_0 + \beta_1x_1 + \beta_2x_2 + \dots + \beta_nx_n + \epsilon$$

Where:
* $y$ is the predicted price.
* $\beta_0$ is the Y-intercept.
* $\beta_1 \dots \beta_n$ are the coefficients (slopes) for each feature.
* $\epsilon$ represents the error term.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `Pandas` for data manipulation.
    * `NumPy` for numerical computations.
    * `Scikit-Learn` for model training and evaluation.
    * `Seaborn` & `Matplotlib` for statistical visualization.



## 📊 Dataset: Boston Housing
The dataset contains 506 observations of housing prices with 13 features, including:
- **RM:** Average number of rooms per dwelling.
- **LSTAT:** % lower status of the population.
- **PTRATIO:** Pupil-teacher ratio by town.
- **CRIM:** Per capita crime rate by town.

## 🚀 Project Workflow
1. **Data Preprocessing:** Handled missing values and analyzed feature distributions.
2. **Correlation Analysis:** Identified strong linear relationships using a Pearson Correlation matrix.
3. **Model Splitting:** Utilized an 80/20 train-test split to ensure model validity.
4. **Training:** Implemented the `LinearRegression` algorithm from Scikit-Learn.
5. **Evaluation:** Measured performance using $R^2$ Score and Mean Squared Error (MSE).



## 📈 Results (Sample)
* **R² Score:** `Insert your score here (e.g. 0.72)`
* **Mean Squared Error:** `Insert your score here`

## 📂 How to Run
1. Clone this repository: `git clone https://github.com/yourusername/project-name.git`
2. Install dependencies: `pip install pandas scikit-learn seaborn`
3. Run the notebook: `jupyter notebook project.ipynb`# project
This project utilizes Multivariate Linear Regression to predict real estate prices using the Boston Housing Dataset. By applying the Ordinary Least Squares method and correlation analysis in Python, I modeled the impact of 13 variables on property value. The model’s accuracy was validated using R-squared and Mean Squared Error metrics.
