
# *Supervised Machine Learning Project*

## *Problem Statement*
Fyntra is one of the largest online clothing companies in the USA. It sells clothing online but also provides in-store styling and clothing advice sessions. Customers visit the store, have sessions with a personal stylist, and later order their chosen clothes either through a *mobile app* or a *website*.

The company wants to decide whether to *focus on improving the mobile app experience or continue investing in the website*. As a drastic measure, it is also considering shutting down the website.

As a *Machine Learning expert*, your role is to help the company make an informed decision by analyzing sales trends, customer interactions, and revenue patterns.

## *Objective*
The project aims to analyze customer behavior and revenue generation based on interactions across platforms (*website vs. mobile app) using **Supervised Machine Learning techniques*.

---

## *Tasks Performed*
1. *Data Analysis & Correlation Studies*  
   - Created joint plots using *Seaborn* to compare:
     - *Time on Website vs. Yearly Amount Spent*  
     - *Time on App vs. Yearly Amount Spent*  
   - Identified which medium (app or website) has a stronger correlation with revenue.

2. *Exploratory Data Analysis (EDA)*  
   - Studied relationships between features in the dataset.
   - Identified key influencing factors for Yearly Amount Spent.

3. *Model Building*  
   - Created a *Linear Regression Model* with:
     - *Length of Membership* and *Yearly Amount Spent* as key predictors.
   - Checked if the data fits well in the linear model.

4. *Model Training & Evaluation*  
   - Trained and tested the model using *random_state=85*.
   - Evaluated model accuracy using:
     - *Predictions vs. Actual Data*
     - *Root Mean Squared Error (RMSE)*

5. *Business Insights*  
   - Based on *model coefficients, provided insights on whether the company should invest more in its **mobile app* or keep focusing on the *website*.

## *Technologies Used*
- *Python*
- *Pandas*
- *NumPy*
- *Seaborn*
- *Matplotlib*
- *Scikit-Learn (Linear Regression Model)*

## *Dataset*
- The dataset contains customer purchase behavior, time spent on platforms, and yearly expenditure.
- Used for analyzing trends and building predictive models.

## *Results & Conclusion*
- Identified whether customer spending is influenced more by the *website* or the *mobile app*.
- Provided a *data-driven recommendation* for Fyntra’s business strategy.

## *How to Run the Project*
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Supervised-ML-Project.git

2. Navigate to the project folder:

cd Supervised-ML-Project


3. Install required libraries:

pip install -r requirements.txt


4. Open and run supervised_ML.ipynb in Jupyter Notebook.

Future Scope

Extend the model to include customer demographics and marketing strategies.

Improve prediction accuracy using advanced regression models.
