# 🧪 Supply Chain Analytics with R

This project dives into exploratory and operational analytics for a simulated supply chain system. Using R, we analyze multiple aspects of product movement from production costs to customer satisfaction to support smarter decision-making.

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Question 1A.rmd` | Cleaning and joining product-related data |
| `Question 1B.rmd` | Cost analysis and shipping cost calculations |
| `Question 2A.rmd` | Delay risk analysis and distribution patterns |
| `Question 2B.rmd` | Statistical analysis of delays, ratings, and returns |
| `Question 3.rmd` | Predictive modeling for delay risk |
| `Final Data cleaning.rmd` | Consolidated, cleaned dataset for modeling |
| `Products.csv` | Product details including ID, name, gender target, price, and weight |
| `Production Costs.csv` | Factory-wise manufacturing costs per product |
| `Warehouse Shipping Costs.csv` | Costs to ship from factories to warehouses |
| `Log Data.csv` | Shipment logs, including order details, delays, and customer ratings |

## 🔍 Key Questions Explored

- Which factories and warehouses are contributing most to delay risks?
- How are costs and product returns linked to customer dissatisfaction?
- Can we build a model to predict delay risks ahead of time?
- What features drive poor ratings and high return rates?

## 🧹 Data Preparation

We cleaned and integrated four primary datasets:

- Merged factory, product, and warehouse shipping data
- Handled missing values and incorrect formatting
- Parsed date-time features and categorical variables

## 📊 Analysis Performed

- **Descriptive Statistics**: Summary of sales, returns, and ratings
- **Shipping Performance**: Actual vs. expected shipping times
- **Cost Modeling**: Identifying cost-effective supply paths
- **Customer Feedback**: Analyzing batch-level satisfaction scores
- **Predictive Modeling**: Logistic regression for identifying delay-prone shipments

## 📈 Sample Insights

- Warehouses receiving shipments from **Factory A** had the highest average delay
- **Lightweight** products had better average ratings and lower return rates
- Shipping delays were more common when order size exceeded **3000 pieces**
- A predictive model achieved **>80% accuracy** in flagging potential delays

## 🔧 Tools Used

- `tidyverse` for data wrangling and visualization
- `lubridate` for date-time parsing
- `ggplot2` and `plotly` for visualizations
- `dplyr` for pipelines
- `caret` and `glm` for modeling

## 🚀 How to Run

1. Clone this repo
2. Open the `.Rmd` files in RStudio
3. Knit each file in order (start from `Question 1A.rmd`)
4. Follow comments inside each RMarkdown file for interpretation

## 📌 Author

Tanushree Poojary  
Graduate Student, MSIM @ UIUC  
Data Analyst | BI Enthusiast | R Programmer
