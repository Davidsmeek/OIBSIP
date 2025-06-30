# Retail Sales Data Analysis

## Project Overview
This project involves exploratory and descriptive data analysis of a retail sales dataset. The goal is to uncover sales trends, customer behaviors, and product performance, and to derive actionable insights for business decision-making.

## Data Sources
- **retail_sales_dataset.csv**: Contains transactional records including purchase date, customer demographics, product category, unit price, quantity, and total sales amount.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning/Preparation
- Imported the dataset using Pandas.
- Converted date columns to datetime format.
- Handled missing values and ensured data types were appropriate for analysis.
- Verified data consistency in key columns such as `Gender`, `Category`, and `Total Amount`.

## Exploratory Data Analysis
- Computed basic statistics (mean, median, standard deviation) for numerical variables such as `Total Amount`, `Price Per Unit`, and `Quantity`.

| Product Category | Mean              | Median | Standard Deviation   |
|------------------|-------------------|--------|-----------------------|
| Beauty           | 467.48            | 120.0  | 563.61                |
| Clothing         | 443.25            | 120.0  | 550.70                |
| Electronics      | 458.79            | 150.0  | 567.54                |

  ### 📊 Monthly Sales Trend (January–December 2023)
  ![image](https://github.com/user-attachments/assets/f6f59d46-a8ba-46c5-9d6e-89d6dd0e8715)

#### Chart Description
This line chart illustrates the total sales amount recorded each month throughout the year 2023.

#### Observations
- **May** recorded the **highest total sales**, peaking above 53,000. This could indicate a promotional campaign, seasonal demand, or product restocking.
- **September** had the **lowest sales** (excluding January 2024), dipping just below 25,000. This might reflect a slump in demand, stock depletion, or reduced marketing activity.
- Sales were relatively high in **February**, **May**, **October**, and **December**, suggesting potential peak periods.
- There was a **sharp decline in March** after a strong February, followed by a **steady climb into May**.
- A second peak occurred in **October**, again followed by fluctuations into December.
- **January 2024** shows an apparent drop to zero, likely due to incomplete data for that month or data collection cutoff.

### 📊 Gender-Based Sales Distribution by Product Category
  ![image](https://github.com/user-attachments/assets/5165f892-3814-4ded-9e0d-09da7434720b)

This bar chart compares **sales performance across three product categories—Beauty, Clothing, and Electronics—segmented by gender** (Female and Male).

#### Key Observations

- **Balanced Total Sales**  
  The overall sales volumes for both genders are nearly identical, suggesting that gender is not a major driver in total spending behavior in this dataset.

- **Category Ranking Consistency**  
  For both male and female consumers, the **ranking of product categories by sales volume is consistent**:
  1. **Electronics** (highest)
  2. **Clothing**
  3. **Beauty** (lowest)  
  This trend indicates a universal preference across genders for electronics-related purchases in this sample.

- **No Strong Gender Category Skew**  
  The height differences of each category between male and female bars are minimal, indicating **no significant gender-based preference** for any specific product line. This could imply a well-balanced marketing reach or a product mix equally appealing to all consumers.


### 📈 Total Sales Per Product Category
  ![image](https://github.com/user-attachments/assets/365c1c0c-7938-4784-8995-dbb9555e9900)

This bar chart illustrates the **total revenue generated across three main product categories** Beauty, Clothing, and Electronics offering a clear snapshot of sales performance by category.

#### Key Insights

- **Clothing dominates** with the highest total revenue, approaching the 160,000 mark. This suggests a stronger consumer demand or higher pricing strategies in this segment.
- **Electronics comes in second**, just trailing behind Clothing. Despite its close performance, the slight drop might indicate more competitive pricing or less frequent purchases.
- **Beauty has the lowest revenue**, with figures substantially lower than the other two categories. This might point to either a narrower target audience or lower product prices on average.
## Data Analysis
- Identified peak sales periods and seasonality.
- Assessed top-selling product categories and their average sales volume.
- Explored gender-wise purchasing behavior and product preferences.
- Mapped customer age distribution and purchasing frequency.

## Results/Findings
- Significant seasonal trends in retail sales were observed, with noticeable peaks during certain months.
- A few product categories consistently outperformed others in both revenue and quantity sold.
- Gender-based differences in category preferences were identified, with some categories being more popular among a specific gender.
- Age groups between 25–34 and 35–44 formed the majority of the customer base.

## Recommendations
- Focus marketing efforts on top-performing product categories during peak months.
- Tailor product promotions by gender preferences to improve targeting.
- Implement loyalty programs for the most active age groups to increase retention.
- Stock high-demand products in preparation for seasonal peaks.

## Limitations
- The dataset does not include customer location, which limits geographical analysis.
- No information on promotional campaigns or discounts, which may affect sales interpretation.
- External factors such as holidays or macroeconomic variables are not considered.


