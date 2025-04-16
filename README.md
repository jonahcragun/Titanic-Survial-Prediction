# Titanic-Survial-Prediction
### Project Description
Machine learning model to predict which passengers will survive based on the kaggle Titanic dataset. Performs Exploratory Data Analysis on the training data using Pandas and Seaborn. Model uses SKLearn and XGBoost to create a machine learning pipeline to clean, train, and predict results.

### Table of Contents
- Project Description
- Technologies Used
- Methodology
- Results
- Setup Instructions
- Future Improvements

### Technologies Used
- python, pandas, seaborn, sklearn, xgboost
- jupyter notebook

### Methodology
- eda
- data cleaning 
    - imputed with median
    - one hot encoding for categorical
- modeling
    - xgboost
    - sklearn
    - pipeline

### Results
- 76% accuracy (better than baseline (73%))
- vizualizations done with seaborn 
- insites show key predictors to be
    - age
    - class
    - gender
    - fare price
- impact: cleaned and analyzed complex data, vizualize trends, and built predictive model (relevant to data analyst positions in industry)

### Setup Instructions
1. clone repo
2. install dependencies
3. Open file in Jupyter
4. run all cells

### Future Improvements
- improve accuracy using an ensemble method
- incorperate new features into the model
