# Titanic Dataset Analysis

## Project Overview  
This project performs **Data Cleaning** and **Exploratory Data Analysis (EDA)** on the **Titanic dataset** from Kaggle. The goal is to explore relationships between variables, identify patterns, and understand factors influencing passenger survival.


## Task Objective  
This project fulfills the requirements of **Task 2** from my internship at **Prodigy InfoTech**:  
- Perform **data cleaning** on a chosen dataset.  
- Conduct **exploratory data analysis** (EDA).  
- Identify relationships, patterns, and trends in the data.  


## Dataset
**Source:** Titanic dataset from Kaggle
**Description:**
The Titanic dataset provides details about the passengers aboard the RMS Titanic, which sank on April 15, 1912. The dataset includes key features like:
    - **Survived:** Survival status (0 = No, 1 = Yes)
    - **Pclass:** Passenger class (1 = First, 2 = Second, 3 = Third)
    - **Sex:** Gender of the passenger
    - **Age:** Age of the passenger in years
    - **SibSp:** Number of siblings or spouses aboard
    - **Parch:** Number of parents or children aboard
    - **Fare:** Ticket price paid by the passenger
    - **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
    - **Other features:** Name, Ticket number, Cabin (partially available)


## Key Steps  

1. **Data Cleaning**  
   - Handled missing values in features like *Age* and *Cabin*.  
   - Created new features, e.g., *FamilySize* to analyze family-based survival trends.  

2. **Exploratory Data Analysis (EDA)**  
   - **Univariate Analysis**: Explored individual features like Age, Fare, and Gender.  
   - **Bivariate Analysis**: Analyzed relationships between features (e.g., Gender vs. Survival, Pclass vs. Survival).  
   - **Multivariate Analysis**: Studied combined effects of features like *Gender* and *Pclass* on survival.  
   - **Correlation Analysis**: Evaluated numerical relationships between variables.  

3. **Key Visualizations**  
   - Survival distribution by Age and Fare  
   - Survival rates based on Gender and Class  
   - Family size impact on survival  
   - Correlation heatmap  


## Insights  

- **Gender**: Females had significantly higher survival rates than males.  
- **Class**: First-class passengers had better survival chances compared to lower classes.  
- **Fare**: Higher fare-paying passengers were more likely to survive.  
- **Age**: Children under 10 had better survival rates, aligning with evacuation priorities.  
- **Family Size**: Small family groups had slightly higher survival rates compared to individuals or large families.  


## Tools and Libraries  

- **Python**: Analysis and visualization  
- **Libraries**: `pandas`, `numpy`, `matplotlib`


## Conclusion  
This project successfully performed **data cleaning** and **exploratory data analysis** on the Titanic dataset. Relationships, patterns, and trends were identified, offering clear insights into passenger survival factors.

For detailed code and analysis, refer to the **[Titanic_Analysis.ipynb](Titanic_Analysis.ipynb)** file.


## Acknowledgments  
- **Dataset Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Task**: Prodigy InfoTech Internship  