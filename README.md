# Amazon-Predictions-Data-Mining-Innopolis-2024
## Project Overview
This project analyzes Amazon US reviews specifically focused on electronics. The goal is to enhance user experience by developing a recommendation system that predicts customer preferences based on their review history. The project follows the CRISP-DM methodology, covering stages from business understanding to evaluation.

## Data
### Data Files
The `data/processed` folder contains the following processed datasets:
- **df_filtered_removed_outliers.csv**: Data with outliers removed.
- **df_no_cold_start.csv**: Data excluding cold start users and items.
- **filtered_simple_personalized.csv**: Filtered data for personalized recommendations.
- **unfiltered_personalized.csv**: Unfiltered data for personalized recommendations.

### Notebooks
The `notebooks` folder contains Jupyter notebooks used for different stages of the project:
- **DataPreparation.ipynb**: Notebook for data cleaning and preprocessing.
- **EDA.ipynb**: Notebook for exploratory data analysis.
- **Modeling.ipynb**: Notebook for building and evaluating recommendation models.

## Project Report
The detailed project report can be found in the `Project_report.pdf` file. It includes:
- Business understanding
- Data understanding and exploration
- Data preparation
- Modeling and evaluation
- Conclusions and next steps

## Usage
### Exploratory Data Analysis
Run the **EDA.ipynb** notebook to perform univariate, bivariate, and time series analysis. This helps in understanding the data distribution and relationships between variables.

### Data Preparation
Run the **DataPreparation.ipynb** notebook to clean and preprocess the data. This includes removing outliers, handling missing values, and creating new features.

### Modeling
Run the **Modeling.ipynb** notebook to build and evaluate recommendation models using the Alternating Least Squares (ALS) method. The notebook includes steps for parameter tuning and assessing model performance.
