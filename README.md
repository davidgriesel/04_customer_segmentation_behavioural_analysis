# Customer Segmentation & Behavioural Analysis
*This project was completed as part of the [CareerFoundry Data Analytics Programme](https://careerfoundry.com/en/courses/become-a-data-analyst/).*

## Overview
An online grocery store that engages with customers through a mobile app is looking to refine its marketing strategy using data-driven insights. This project uses Python to analyse demographic and transactional data, creating customer segments and spending profiles that inform targeted product placement and personalised marketing strategies.

## Tools
- **Python** (Jupyter | Anaconda) - Scripting
- **pandas | numpy | os** - Data Processing & Manipulation
- **matplotlib | seaborn** - Plotting | Visualisation
<!--- **Excel** - Reporting-->

## Process
- **Data Preparation** - Wrangling | Merging | Subsetting | Grouping | Aggregation | Deriving new Variables
- **Analysis** - Exploratory Analysis | Segmentation & Profiling | Descriptive Statistics | Trend Analysis
- **Communication** - Visualisation | Reporting

## Data
This analysis uses publicly available data originally sourced from **Instacart** via **Kaggle**. The links as well as an additional customers dataset was provided by **CareerFoundry** as part of their Data Analytics Course.

- [**Customers**](https://s3.amazonaws.com/coach-courses-us/public/courses/data-immersion/A4/A4_Data_Assets/customers.zip) - Customer ID, Name, Surname, Gender, State, Age, Date Joined, Dependants, Family Status, and Income
- [**Dataset**](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)

    - **Departments** - Department id and name
    - **OrdersProducts** - Order id, product id, add to cart order, and reorder indicator.
    - **Orders** - Order is, order number, order day of week, order hour of day, days since prior order.
    - **Products** - Product id, name, aisle, department, and price.

The Instacart Dataset was accessed on 7 September 2024.

<!--## Deliverables
- **Excel Report**
- [**Detailled Case Study**](https://davidgriesel.com/online-grocery-store/)

## Key Questions
1. How does order volume fluctuate over time?
2. How does average spending per product vary over time?
3. How can products be categorised into price ranges to support product placement?
4. Which products, within their respective departments and categories, are most popular?
5. How can ordering behaviour and demographic information be used to categorise customers?
6. How does ordering habits vary across customer profiles?

## Key Insights

## Key Recommendations

## Takeaways
### Successes
The project provided actionable insights into ordering behaviour across customer profiles, enabling a more targeted marketing strategy through better product placement.

### Challenges
While data wrangling was straightforward, producing clear visualisations in Python required significant customisation. Unlike Tableau’s interactive interface, Python tools like Matplotlib and Seaborn needed more effort to ensure readability and interpretability.

### Way Forward
Building a Tableau storyboard to present key findings in an interactive format could enhance storytelling and enable stakeholders to explore trends, segments, and behaviours through dynamic dashboards and filters.
