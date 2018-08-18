Predicted housing prices by optimizing the machine learning models using Lasso, Ridge, decision tree, and random forest with predictive accuracy of 93%.

Python Machine Learning


## House Sales Pricing, IOWA using Machine Learning (Modeling - Lasso, Ridge, Random Forest, and XGBoost) 

- First steps with data understanding
    - Checking all the data
    - Categorizing - non-numerical and numerical 
    - Structural/ unstructural
    - Resolving any conflicts in the data and handling redundancies
    
- Data Cleaning 
    - Determining Missing values 
    - Correcting inconsistencies within the data
    - Smoothing out noisy data
    
- Data Exploration
    - Making hypothesis 
    - Transformation such as normalization, aggregation of data using ELT methods
    - Analyzing the data by visualization
    - identifying patterns

- Feature Engineering
    - Selecting parameter that can affect the overall outcome
    - Tuning significant data / eliminating not significant data
    
- Choosing algorithm / predictive modeling
    - Training a perceptron via sklearn
    - Returning the cross validation rmse error to evaluate the quality of the models. 
    - Depending on the score, there will be another computational / tuning in the features
    
- Modeling class probabilities via Lasso, Ridge regulation. 
    - Lasso & Ridge intuition and conditional probabilities
    - Learning the weights of cost function
    - Training a logistic regression model with scikit-learn
    - Tackling overfitting via regularization
    
- Decision tree learning
    - Maximizing information gain – getting the most bang for the buck
    - Building a decision tree
    - Combining weak to strong learners via random forests

- Summary - Lasso 0.1201, Ridge 0.125, Random Forest score: 0.913
