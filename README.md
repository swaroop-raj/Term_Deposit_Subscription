# Problem statement (Term Deposit Sale)

We have data from a Portuguese bank on details of customers related to selling a term deposit. The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio.

### What is a Term Deposit?
A Term deposit is a deposit that a bank or a financial institution offers with a fixed rate (often better than just opening deposit account) in which your money will be returned back at a specific maturity time.

### Attribute Information
age
job : type of job
marital : marital status
education
default: has credit in default?
housing: has housing loan?
loan: has personal loan?
balance in account
contact: contact communication type
month: last contact month of year
day: last contact day of the month
duration: last contact duration, in seconds
campaign: number of contacts performed during this campaign and for this client
pdays: number of days that passed by after the client was last contacted from a previous campaign
previous: number of contacts performed before this campaign and for this client
poutcome: outcome of the previous marketing campaign
Output variable ('Target'): has the client subscribed a term deposit?

### Resources Available
The historical data for this project is available in file https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

### Project Outline :
The below items have been defined in the project 

- Univariate analysis
- Make a function to plot ‘countplot’ if the variable is categorical and ‘distplot’ if the variable is numeric.
- Identify outliers using IQR and verify the same using plots. Also mention the percentage of data points which are considered outliers. Should we treat them, why or why not?
- Multivariate analysis
- Make a function to plot boxplots for all continuous variables VS ‘Target’ variable and countplots for all categorical variables VS ‘Target’ variable?
- Bi-variate analysis between predictor variables and target column. Comment on your findings in terms of their relationship and degree of relation if any. Visualize the analysis using pair plots, heatmaps, histograms or density curves.
- Label encode or create dummy variables for categorical variables. Give reason for selecting either of them.
- Create the training set and test set in a ratio of 70:30. Make sure and verify distribution of classes is the same in the full dataset and train test split data. 
- Build the ensemble models (Bagging and Boosting) and Decision Tree model (at least 4 models in total). Note the model performance by using different metrics. Use confusion matrix to evaluate class level metrics i.e. Precision/Recall.
- Also reflect the training and testing score of all the models. Build a dataframe with model names as row index and all the metrics calculated as columns
- Explain the confusion matrix related terms like recall, precision etc. Also, select the best metric to choose one of the models from above. Give your reason for the same.

### Buisness questions outcomes concluded in the models:

- Suggest some changes for the organization so that they can increase the number of customers who take term deposit.
- How much influence does the previous campaign and mode of interaction have on financial performance.
- Which features should be more/less focused by the bank to get better results and why?
- What did you learn about banking industries from this data?
- Note : Use random_state=7 (wherever the parameter can be used) so that we can compare all submissions.

### Machine learning models used in this project :

- Decision Tree
- Random Forest
- Ada Boost Classifier
- Bagging Classifier
- Gradient Boosting  Classifier
- XG BOOST Classifier
