# ShowUp-analysis-using-optimized-XGBosst
Using optimized XGBoost to predict SHOW/No Show status
This particular problem suffers with class imbalance partitioning i.e negative class has very few observations.
We are trying to predict it using XGBoost with stratified sampling and optimized values of max_depth and n_estimators.
A seperate setup of XGBoost is required to run it and this may take a little time as we are using gridsearch to find the values of parameters
