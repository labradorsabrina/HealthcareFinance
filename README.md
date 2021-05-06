# Healthcare Cost Forecasting 
This is a prediction of the healthcare cost from claims database of the Hospital Sigma using Watson Health Analytics Workbench.  The notebook includes live code that accesses the sample data assets stored in COS, prepares those data, and builds a machine-learning model using the PySpark interface. 

The sample data assets include synthetic healthcare beneficiary claims data publicly available from the Agency for Healthcare Research and Quality (HRAC). The data records contain ICD9 diagnosis for claims data that follow the FHIR specification. One of the data assets contains clinical classification categories to which the diagnostic codes from the claims data are converted. The notebook trains a linear regression model from a subset of the data, and validates it on another, validation subset. The model predicts future medical service costs. 

The notebook runs on the latest Python version and Spark.
