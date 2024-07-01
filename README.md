### Title : Online-shoppers-behaviour-prediction
#### Author : Anshila K
#### Organisation : Entri
#### Date (Submission / Evaluation Date) : 1-07-2024

### Table Of Content
1. Overview
2. Data Collection
3. Data Description
4. EDA
5. Data Preprocessing
6. Visualization
7. Feature Engineering
8. Data Splitting
9. Model Selection
10. Feature Selection
11. Hyperparameter Tuning
12. Model Deployment
13. Conclusion
    
### Overview
Predicting whether a visitor will generate revenue for the online shopping website based on various features

### Objective
The main goal of this project is to develop a machine learning model that can accurately predict if a visitor will make a purchase during their session on the website. 

## Data Description
1. Data Source
The dataset is collected from Kaggle : <a href="https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset">Dataset</a>

2. Dataset Overview
- Size: The dataset contains 3810 rows and 18 columns.
- Features: The features are a mix of numerical and categorical data that describe various aspects of user behavior and session details on the online shopping website. Below is a brief description of each feature:

 -- Administrative: Number of pages visited by the visitor about administrative.
 -- Administrative_Duration: Total time spent by the visitor on administrative pages.
 -- Informational: Number of pages visited by the visitor about information .
 -- Informational_Duration: Total time spent by the visitor on informational pages.
 -- ProductRelated: Number of pages visited by the visitor about products.
 -- ProductRelated_Duration: Total time spent by the visitor on product-related pages.
 -- BounceRates: The percentage of visitors who enter the website and then leave rather than continuing to view other pages.
 -- ExitRates: The percentage of pageviews on the website that were the last in the session.
 -- PageValues: The average value for a web page that a user visited before completing an e-commerce transaction.
 -- SpecialDay: Closeness of the visit to a special day.
 -- Month: Month of the year when the visit occurred.
 -- OperatingSystems: Operating system used by the visitor.
 -- Browser: Browser used by the visitor.
 -- Region: Geographic region of the visitor.
 -- TrafficType: Source of traffic.
 -- VisitorType: Whether the visitor is a returning visitor or a new visitor.
 -- Weekend: Whether the visit happened on a weekend.
 -- Revenue: Whether the visit resulted in a transaction.

### Limitations
Imbalanced Data: The dataset has a disproportionate number of samples in classe , the model may become biased towards the majority class. This imbalance can lead to poor performance in predicting the minority class, which is often the class of most interest.

### Conclusion
Random Forest seems like the best overall choice due to its strong performance and effective feature importance analysis. Gradient Boost follows closely behind with competitive accuracy and interpretability.

### Future Work
-	Collect More Data: Increasing the dataset size can provide more information for the model to learn from, improving its accuracy and robustness.
-	Try Different Algorithms: Experimenting with other algorithms, including advanced deep learning models, might enhance accuracy.
- Resample for Imbalanced Data: Undersampling the majority class can address data imbalance and improve model performance.
-	Add More Features: Including additional relevant features can help the model capture more complex patterns, leading to better predictions.

