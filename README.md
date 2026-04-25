# Housing Price Prediction Using Socioeconomic, Crime and Air Quality Data

## Project Overview
This project explores the factors influencing housing prices in the United States by combining three independent data sources:

- U.S. Housing dataset  
- Crime statistics dataset  
- Air quality / pollution dataset  

The objective is to investigate how socioeconomic variables, crime rates, and environmental indicators affect housing prices and to build predictive Linear Regression models.

## Research Questions
- Which factors have the strongest influence on housing prices?
- Do crime rates significantly affect property values?
- Does air quality contribute to housing price prediction?
- How well can housing prices be predicted using Linear Regression?
- How does model performance change when important predictors are removed?

## Datasets
### Housing Data
- Average Area Income  
- House Age  
- Number of Rooms  
- Number of Bedrooms  
- Area Population  
- Price

### Crime Data
- Violent Crime  
- Burglary  
- Robbery  
- Murder  
- Property Crime

### Air Quality Data
- NO2  
- O3  
- SO2  
- CO

## Project Structure
Data-Science-Exam-Project/
- data/
- ImpactHousingPricesUSA.ipynb
- README.md
- .gitattributes

## Methods
- Data cleaning and preprocessing  
- Data merging from multiple sources  
- Exploratory Data Analysis (EDA)  
- Correlation analysis  
- Distribution and outlier analysis  
- Linear Regression modeling  
- Feature importance comparison  
- Comparative model testing  

## Models Evaluated
### Full Linear Regression Model
Performance:
- MAE ≈ 79,525
- RMSE ≈ 99,529
- R² ≈ 0.917

### Without Average Area Income
- Significant drop in predictive power

### Crime and Air Quality Only
- Very weak predictive performance (R² near zero)

## Key Findings
- Average Area Income is the strongest predictor of housing prices.
- Housing characteristics and population contribute significantly.
- Crime variables show weak negative relationships with prices.
- Air quality indicators have limited standalone predictive power.
- Socioeconomic factors dominate housing price prediction.

## Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## How to Run
Clone the repository:
git clone https://github.com/cvetelinamin/Data-Science-Exam-Project.git

Install:
pip install pandas numpy matplotlib seaborn scikit-learn

Run:
jupyter notebook

Open:
ImpactHousingPricesUSA.ipynb

## References
- https://scikit-learn.org
- https://www.statlearning.com
- https://hastie.su.domains/ElemStatLearn/

## Author
Cvetelina Mincheva  
SoftUni Data Science Final Exam Project
