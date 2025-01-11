# Data Preprocessing Pipeline

## Goal
The primary objective is to enhance the overall performance of customer service operations by understanding feature correlations and identifying critical factors that drive success. This includes improving data quality, deriving actionable insights, and optimizing processes through comprehensive analysis.

## Additional Documentation
For further details on the business requirements, refer to the [Business Requirements Document (BRD)](./doc/BRD.md).


## Sections Overview

### 1. Setup
Prepare the environment and necessary libraries for data preprocessing.

### 2. Standardization
- Standardize column names for consistency.
- Validate updates to column names.

### 3. Data Cleaning
- Identify missing values in key columns such as `customer_remarks`, `order_date_time`, and `item_price`.
- Handle missing data through imputation or dropping rows as appropriate.
- Remove irrelevant columns and duplicates to streamline the dataset.

### 4. Feature Engineering
- Convert date columns to standard formats.
- Calculate derived metrics such as `Resolution Time` and `Survey Delay`.
- Generate additional features like `order_year` and `order_month` for analysis.

### 5. Exploratory Data Analysis (EDA)
- Examine dataset characteristics: categorical, numerical, and datetime columns.
- Visualize distributions and correlations to understand feature relationships.
- Address key business questions, including:
  - Performance analysis by city.
  - Efficiency of customer support.
  - Insights into issue categories.

### 6. Correlation Analysis
- Encode categorical variables.
- Compute correlation matrix to identify significant relationships.

### 7. Business Insights
- Analyze trends in customer satisfaction and issue resolution across categories.
- Derive actionable insights for improving service efficiency and satisfaction.

## Key Results
- **Cities with Highest CSAT Scores:** Focus on top-performing cities to maintain customer satisfaction.
- **Resolution Time Impact:** Highlight the critical threshold where quicker resolution improves satisfaction.
- **Issue Category Trends:** Identify categories with room for improvement to prioritize resource allocation.

## Visualization
Utilize various plots (histograms, correlation heatmaps, bar charts) to uncover data patterns and support decision-making.

## Challenges Addressed
- Handling missing and inconsistent data.
- Developing derived metrics for enhanced analysis.
- Providing actionable insights for business improvement.
