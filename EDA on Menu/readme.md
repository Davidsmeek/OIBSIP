# Menu Dataset Analysis

## Project Overview
This project analyzes a restaurant's menu dataset to gain insights into the items offered, their nutritional information, and pricing. The goal is to provide actionable insights that can help optimize the menu for customer preferences and business objectives.

## Data Sources
The dataset used is **`menu (1).csv`**, containing information about menu items, their categories, prices, and nutritional details.

## Tools
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## Data Cleaning/Preparation
- Loaded the dataset and inspected the structure using `df.info()` and `df.head()`.
- Stripped whitespace from column names for consistency.
- Removed rows with missing values to ensure clean data for analysis.

## Exploratory Data Analysis (EDA)
- Explored the distribution of menu categories and items.
- Visualized price distributions across different menu categories.
- Analyzed nutritional values such as calories, fat, and protein content.
- Identified high-calorie and high-priced items to understand outliers.

## Data Analysis
- Performed descriptive statistical analysis to summarize key metrics.
- Grouped items by category to compare average prices and nutritional content.
- Created visualizations (boxplots and bar charts) to highlight differences across menu sections.

## Results/Findings
- Certain categories like **Burgers** and **Desserts** have higher calorie counts than others.
- Drinks tend to have lower calorie content but vary widely in price.
- High-priced items often correlate with higher nutritional content (e.g., protein-heavy meals).

## Recommendations
- Consider adding healthier options within high-calorie categories to cater to health-conscious customers.
- Reevaluate pricing strategy for drinks given their wide price variation.
- Highlight high-protein, lower-calorie options on the menu to attract fitness-focused clientele.

## Limitations
- The dataset does not include sales data, limiting insights into customer preferences or profitability.
- Geographic or demographic data is unavailable, making it difficult to tailor recommendations for specific audiences.
- Missing data was dropped, which could have led to a loss of valuable information if not random.

