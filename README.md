# Analysis of real estate price evolution with Python
# I. Context
As part of a consulting mission, I worked as a Business Intelligence Analyst for _Les Plus Beaux Logis de Paris_, a prestigious B2B and B2C real estate company based in Paris.

Due to financial constraints, this family-owned firm needed to sell some of its real estate assets to maintain a sufficient level of cash flow. However, internal conflict arose: the CEO’s children (his son managing the private residential segment and his daughter managing the corporate real estate portfolio) strongly opposed selling their respective properties.

I was brought in as a neutral party to help guide their decision-making using data-driven insights.

The CEO had recently learned about data science techniques that could be used to predict real estate price trends. He requested that I conduct a study on the evolution of Parisian real estate prices using machine learning algorithms, with the goal of determining which market segment (private or corporate) would be most valuable in the coming years. This formed the first part of my mission.

Additionally, to assist the CEO’s daughter in streamlining her research and operations, I was asked to create an algorithm capable of predicting and automatically classifying real estate opportunities, based on property types. This was the second part of the mission.

# II. Methodology
## 1. Prepararion of the dataset for the price evolution prediction
- Verified and standardised data types

- Cleaned the dataset by removing unnecessary columns and missing data

- Created new variables such as price per square meter to enrich the dataset

## 2. Predictive data analysis (Private vs Corporate segments)
- Performed correlation analysis (Pearson and Spearman) to identify relationships between variables

- Analysed price evolution trends in both the private and corporate markets

- Applied One-Hot Encoding to prepare categorical data for modeling

- Split the data using train_test_split to train and evaluate the model

- Used linear regression as the supervised machine learning model to predict future price trends for each segment

## 3. Preparation of the dataset for the property classification
- Re-verified and cleaned the dataset

- Created additional features (eg: price per square meter) to enhance clustering performance

## 4. Unsupervised learning for automatic classification
Applied K-Means clustering, an unsupervised algorithm, to group data around two centroids. Each cluster represented a type of property: private or corporate.

The algorithm automatically assigned new property listings to one of the two clusters based on similarities.

## 5. Presentation of the results
Delivered a comprehensive report including:

- Visualisations of price evolution and clustering results

- A detailed explanation of the methodology used

- Insights and recommendations tailored to the CEO's and both stakeholders’ objectives

# III. Tools used

**Anaconda Navigator**: Environment management

**Jupyter Noteboo**k: Interactive data analysis and prototyping

**Python** with: Pandas (data manipulation), Matplotlib (data visualisation), Scikit-Learn (machine learning : linear Regression, K-Means)

**Microsoft PowerPoint**: Final presentation and reporting
