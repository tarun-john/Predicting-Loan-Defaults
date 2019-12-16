Credit One has been experiencing higher rates of customer loan defaults. They supplied data (file: default.csv) to find factors 
that can help predict loan defaults. The provided data has 30,000 rows and 24 attributes, with the last column a boolean 
value on default. I cleanse the data: ID attribute is dropped, and relevant data types are changed to “category." After that 
independent (x values) and dependent variable (y value) are categorized, with loan default attribute being the dependent variable. 
The dependent variable can be changed to either “category” or “boolean,” both produced same results. The data is then split into 
training set and test set, with 80% of the data being assigned to training. Two models are then created and their scores evaluated. 
From the scores RF model is selected, and then three parameters are evaluted, and these new values are used to tune the RF model. 
The tuned RF model produced an accuracy score of 82.2. Using this model, the most relevant factors that determine default are then 
displayed. 
 
As can be seen, payment history, payment amount history, and amount of credit given are the most important factors that predict a 
loan default. Therefore I recommend that these factors be given more consideration in future loan applications, to reduce chances 
of default.
