# LLume_Intern_Project

The analysis has mainly three part: data import, data visualization, and data analysis.

## Data import
Source: https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset?resource=download

Data set name: Heart Disease Health Indicators Dataset

Import the csv through Pandas

## Visualization

### Heat map
Heat map helps to give an overview of how each column correlates to each other (not causation).
We can select several columns having higher correlation value with the labal.

### Bar plot
Among some of those higher correlation columns, we have some categorical data, e.g. HighBP, Smoker, etc.
Then, for each group of having or not having heart disease, we can plot the percentage of those attendants' status in those categorical values to see if there is indeeed a correlation and how large the difference is visually.

## Data Analysis
### Decision Tree
For such a classification problem, we can use KNN, logistic regression, decision tree, etc. 
Since this dataset has quite a lot of columns whcih are mostly categorical values, I chose decision tree.

### Evaluation
After the model is trained, we can see from the confusion matrix and the AUC curve that the result is actually not satisfying. 


## Potential improvement
- Try different features
- Try other algorithms
- Decision trees with different hyperparamters
- Random forest to avoid the bad effect of correlation between factors
