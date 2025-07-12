# iFood Customer Segmentation Project

## Project Overview
This project analyzes customer purchasing behavior from iFood, an online food delivery service, using clustering techniques. The goal is to identify distinct customer segments to help iFood tailor its marketing strategies and improve customer targeting.

## Data Sources
The dataset used is **`ifood_df.csv`**, which contains customer demographics, purchase history, and campaign response details.

## Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn)
- Jupyter Notebook

## Data Cleaning/Preparation
- Loaded the dataset and checked for null values.
- Performed descriptive analysis to understand variable distributions.
- Created new features such as `Customer_Days` (tenure in days) and `MntTotal` (total spending across product categories).
- One-hot encoded categorical variables like marital status and education levels.
- Standardized numerical features using `StandardScaler` for clustering.

## Exploratory Data Analysis (EDA)
- Visualized distributions of key features such as income, total spending, and campaign responses.
- Examined correlations between demographic variables and purchasing behaviors.
- Plotted boxplots to explore variability in income and total spending.

## Data Analysis
- Applied K-Means clustering to segment customers.
- Used the Elbow Method to identify the optimal number of clusters (`k=4`).
- Analyzed cluster characteristics:
  - **Segment 0**: Low income, low spending, low campaign engagement.
  - **Segment 1**: High income, high spending, highly engaged in campaigns.
  - **Segment 2**: Moderate income and spending, moderate engagement.
  - **Segment 3**: Younger customers with lower tenure and spending.

## Results/Findings
- Four distinct customer segments were identified based on spending habits, income, and campaign responses.
- Higher-income segments tend to engage more with campaigns and spend significantly on wine and meat products.
- Lower-income segments require different marketing approaches due to lower spending and engagement.

## Recommendations
- Develop personalized marketing campaigns targeting high-spending segments to maximize ROI.
- Consider loyalty programs or promotions to engage younger, lower-spending customers (Segment 3).
- Analyze additional behavioral data (e.g., web/app interactions) to refine segmentation further.

## Limitations
- The dataset is static and may not capture recent customer behavior changes.
- No geographic data included, limiting the ability to consider location-based trends.
- The clustering approach assumes spherical clusters, which may not perfectly capture complex customer relationships.

