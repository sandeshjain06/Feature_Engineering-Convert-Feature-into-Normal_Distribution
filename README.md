# Feature_Engineering  -  Convert Feature into Normal_Distribution


**Feature Transformation : Transforming the features distribution into normal distribution**


    Most algorithm requires the feature into normal distibution while some does not requires .
    1) Linear and logistic regression requires the data in normal distribution.
    2) Decision tree , random forest, here it does not matter whether the feature distribution is normal or not.
    
    How to check feature is normal or not  :   
    
    1) sns.distplot()

    2) Check the skewness - if pd.skew() = 0 , then normal else skewed.

    3) QQ plot - Reliable way to check whether feature distribution is normal or not.

    In QQ Plot if line is straight then it is normal else skewed


**Types of Feature Transformation**


    1) Log Transform : If data is right skewed data then use it.

    2) Reciprocal Transform 

    3) Power Transform - square , square root : If data is left skewed data then go with square power transform.

    4) Box-Cox Transform

    5) Yeo-Johnson Transform.


    Function Tranformer   - Log Transform   /  Reciprocal Transform   /  Power Transform - square , square root

    Custom Transformer    - Power Transform / Box-Cox Transform : 1. values > 0 , 2.values cannot be negative / Yeo-Johnson Transform : Overcome problem of box-cox transform.


