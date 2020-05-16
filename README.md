# predictive-modeling-process

We follow CRoss Industry Standard Process (CRISP) for predictive modeling.

## Different Steps

### 1. Data Load 
          - Pandas (python Api)
          - Pyspark (Spark Api)

### 2. Data Tranformation
          -  Categorical(factor) to Numerical Values using Encoding Techniques
          
### 3. Data Understanding - Descriptive Statistics
          - Check for any Null values
          - check Multicolinearilty 
          - Binning or Bucketing

### 4. Variable Selection - Methods
          - Information Value(IV) using Weight of evidence(WOE)
          - Variable Inportance using Random Forest or Extra Tree classifier 
              (https://www.thekerneltrip.com/statistics/random-forest-vs-extra-tree/)
          - Recursive Feature Elimination
          - Chi Square Best classifier
          - L1 based feature Selection
          
### 5. Model Selection
        - Tree Based Models
          - Random Forest
          - GBM
          - Xgboost
        - Logistic Regression
        - Neural Network
        - Gradient Boosting
        .. Lot more

### 6. Hyper Parameter Tuning(model tuning)

### 7. Model Perfomance - Evaluation
        - LIFT Chart or GAIN Chart
        - CROSSTAB
        - ROC/AUC Curve
        - KS Statistics
        - Decile Plots
        
### 8. Saving Model Object and Label Encoder

### 9. Scoring




