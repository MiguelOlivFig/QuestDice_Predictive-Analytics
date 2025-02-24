# QuestDice_Predictive Analytics
Supervised Learning algorithms: Nearest Neighbours, Decision Trees, Neural Networks, and others - creation of predictive models to forecast customer purchasing patterns, reduce advertising expenditure and maximize ROI

## QuestDice: Enhancing Customer Targeting Through Predictive Analytics:
**Introduction:**

QuestDice, a rapidly growing board game company, was founded with the mission to deliver engaging and innovative gaming experiences. 

Following the tremendous success of its first product — which reached 198,723 customers — QuestDice is preparing to launch its second board game. In the initial phase, a direct advertising campaign was conducted targeting a small subset of previous customers. Of the 15,589 customers reached, 8,477 proceeded with a purchase.

Taking into consideration advertising costs of €3 per customer and a profit margin of €8 per sale (excluding marketing expenses), the campaign yielded a profit of €21,049. To enhance future profitability, QuestDice aims to adopt a more analytical approach to customer targeting. By identifying customers most likely to purchase the second product, the company seeks to reduce advertising costs and increase revenue when extending the campaign to the broader customer base of 198,723 individuals.

**Data Description**:

The project utilizes two datasets:

- **train.csv:** Contains 15,589 observations used for model training. This dataset includes customer demographics, firmographic details, and responses to 14 survey questions about the first product. The target variable, 'Buy_Product,' indicates whether a customer purchased the second product (1) or not (0).

- **test.csv:** Consists of 5,195 observations without the target variable. The objective is to predict and populate the 'Buy_Product' variable for this dataset.

Key features:

- **Customer Information:** Unique customer ID, name, year of birth, membership type, and preferred game genre.
  
- **Engagement Metrics:** Newsletter subscription status and accumulated fidelity points.
  
- **Survey Responses:** Fourteen questions evaluating various aspects of the first game, rated on a scale from 0 (Completely Disagree) to 5 (Completely Agree).

**Objective**:
The primary goal of this project is to develop and implement predictive models capable of forecasting customer purchasing behavior for the second product launch. Using data from customer surveys and previous purchasing history, the objective is to accurately predict which customers are most likely to make a purchase. This targeted approach will optimize advertising expenditure and maximize return on investment (ROI) by focusing marketing efforts on high-potential customers.

**Methodology**:

**Data Collection & Preparation:**
- Analyze customer survey responses and purchasing behaviors.
- Perform feature engineering to extract meaningful variables from the dataset.

**Model Development**:
- Implement supervised learning algorithms, including K-Nearest Neighbors (KNN) and decision trees.
- Train models on historical data to predict customer purchasing likelihood.

**Model Evaluation**:
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score, with a primary focus on maximizing the F1-score to balance precision and recall.
