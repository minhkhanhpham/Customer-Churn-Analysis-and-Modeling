# Customer-Churn-Analysis-and-Modeling
In the bank industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the bank industry experiences a high annual churn rate.Therefore, retaining high profitable customers is the number one business goal.
To reduce customer churn, banks need to predict which customers are at high risk of churn.
In this analysis, we will analyse customer-level data of a bank, build predictive models to identify customers at high risk of churn.
## Data: The dataset include 14 fields as below
- RowNumber: The number of the row
- CustomerId: The unique customer id
- Surname: Customers Surname
- CreditScore: Their credit score
- Geography: Which Country they belong to
- Gender: Their Gender
- Age: Age
- Tenure: The time of bond with company
- Balance: The amount left with them
- NumofProducts: The products they own.
- HasCrCard: Do they have a credit card or not
- IsActiveMember: How active member they are
- EstimatedSalary: Their estimated salary
- Exited: Whether they stay in the or leave
## Data Exploration
- Examine the structure of the dataset (columns, data types, missing values).
- Explore basic statistics (mean, median, standard deviation, etc.).
- Gain more insights about the data by creating data visualizations.
## Data Preprocessing 
- Removing Outliers
- Converting categorical variables to numerical data (One-Hot Encoding).
- Removing Unnecessary Columns
- Splitting the data into train and test sets
## Built model Machine Learning
- Modelling (Logistic Regression, SVM, Random Forest).
- Train the model and fine-tune hyperparameters.
- Evaluate the models' performance
## Result
Random forest has the best results for our problem. Random Forest has the best accuracy and lowest false negative rate.Hence we’ll choose Random Forest.
