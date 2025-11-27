The point of this repository is to use the Adult Census Data Set to predict whether a given person would make more or less than 50,000 dollars. Factors include occupation, age, education, or employment type ( private, public, self employed etc).

The Jupyter Notebook starts with a bit of exploratory data analysis. I am trying to see what connections exist between variables to get a feel for what models would work best, as well as how good the model should be overall. If there seems to be few obvious correlations and the variables are irregularly distributed then I would expect a poor model regardless of what algorithm I would use. 

I will be using XGboost as the model, and then trying to optimize the algorithm to better predict the smaller class.

Data from: https://archive.ics.uci.edu/dataset/2/adult
