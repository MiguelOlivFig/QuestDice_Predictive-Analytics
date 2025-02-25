# QuestDice_Predictive Analytics
Supervised Learning algorithms: Nearest Neighbours, Decision Trees, Neural Networks, and others - creation of predictive models to forecast customer purchasing patterns, reduce advertising expenditure and maximize ROI

## QuestDice: Enhancing Customer Targeting Through Predictive Analytics:
**Introduction:** <br>
QuestDice, a rapidly growing board game company, was founded with the mission to deliver engaging and innovative gaming experiences. <br>
Following the tremendous success of its first product — which reached 198,723 customers — QuestDice is preparing to launch its second board game. In the initial phase, a direct advertising campaign was conducted targeting a small subset of previous customers. Of the 15,589 customers reached, 8,477 proceeded with a purchase. <br>
Taking into consideration advertising costs of €3 per customer and a profit margin of €8 per sale (excluding marketing expenses), the campaign yielded a profit of €21,049. To enhance future profitability, QuestDice aims to adopt a more analytical approach to customer targeting. By identifying customers most likely to purchase the second product, the company seeks to reduce advertising costs and increase revenue when extending the campaign to the broader customer base of 198,723 individuals.

**Data Description**: <br>
The project utilizes two datasets:
- **train.csv:** Contains 15,589 observations used for model training. This dataset includes customer demographics, firmographic details, and responses to 14 survey questions about the first product. The target variable, 'Buy_Product,' indicates whether a customer purchased the second product (1) or not (0)
- **test.csv:** Consists of 5,195 observations without the target variable. The objective is to predict and populate the 'Buy_Product' variable for this dataset

Key features:
- **Customer Information:** Unique customer ID, name, year of birth, membership type, and preferred game genre
- **Engagement Metrics:** Newsletter subscription status and accumulated fidelity points
- **Survey Responses:** Fourteen questions evaluating various aspects of the first game, rated on a scale from 0 (Completely Disagree) to 5 (Completely Agree)

**Objective**:
- Develop and implement predictive models capable of forecasting customer purchasing behavior for the second product launch
- Accurately predict which customers are most likely to make a purchase, reducing advertising expenditure and maximizing ROI

**Methodology**:

**Data Collection & Preparation:**
- Analyze customer survey responses and purchasing behaviors
- Perform feature engineering to extract meaningful variables from the dataset

**Model Development**:
- Implement supervised learning algorithms, including K-Nearest Neighbors (KNN) and decision trees
- Train models on historical data to predict customer purchasing likelihood

**Model Evaluation**:
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score, with a primary focus on maximizing the F1-score to balance precision and recall

## Technologies Used:
Programming Language: **Python**

Libraries/Frameworks:

- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical operations
- **Matplotlib & Seaborn:** Data visualization
- **Scikit-learn:** Machine learning (feature selection, model training, and evaluation)
- **SciPy:** Statistical methods and hypothesis testing
- **Graphviz & Pydotplus:** Decision tree visualization
- **Warnings:** Suppressing unwanted warning messages

## The repository is organized as follows:
- Data: folder containing all the data files used for the project
- OLD: folder containing older versions of the notebook
- Project Statement
- Notebook (.ipynb):
  - data collection (importing libraries, loading datasets)
  - data exploration, describing the data available and extracting meaningful insights that may be helpful in addressing the problem at hand
  - preprocessing:
    - data cleaning, transformation, and feature engineering
    - business-related transformations and creation of new features
    - feature selection (Chi-square method for categorical data, and Variance, Spearman correlation, Decision Trees, Recursive Feature Elimination and Lasso for numerical data) 
  - modeling and assessment:
    - comapared different algorithms and experimented with different combinations of features through 3 distinct datasets
    - determined the 3 best algorithms taking into consideration validation accuracy and overfitting
    - optimized the models by using techniques like Random Search and Grid Search
    - selected the best model by resorting to ROC curve and AUC, and F1 Score
  - deploy model and obtain predictions on the test data
- Final solution: excel containing the prediction for each customer
- Report

